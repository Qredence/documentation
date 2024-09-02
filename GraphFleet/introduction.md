
<img
  className="block dark:hidden"
  src="https://imagedelivery.net/X8-iu39scv5xvBSFZpKX-A/3aecdba3-d6f2-42a8-a303-c517a5eadd00/public"
  alt="Hero Light"
/>
<img
  className="hidden dark:block"
  src="https://imagedelivery.net/X8-iu39scv5xvBSFZpKX-A/3aecdba3-d6f2-42a8-a303-c517a5eadd00/public"
  alt="Hero Dark"
/>

# Get Started Quickly

This guide provides a quick and easy way to get started with GraphFleet.

## Prerequisites

- **Python 3.11:** Ensure you have Python 3.11 installed on your system.
- **Poetry:** We recommend using Poetry for dependency management. Install it using `pip install poetry`.

## Installation

1. **Clone the Repository:**
   ```bash
   git clone https://github.com/Qredence/GraphFleet.git
   cd GraphFleet
   ```

2. **Create a Virtual Environment (Recommended):**
   ```bash
   python3.11 -m venv .venv
   source .venv/bin/activate
   ```

3. **Install Dependencies:**
   ```bash
   poetry install
   ```

## Configuration

1. **API Keys:**
   - Obtain API keys for any external services you plan to use (e.g., OpenAI).
   - Create a `.env` file in the project root and store your API keys there:
     ```
     OPENAI_API_KEY=your_openai_api_key
     ```

2. **Settings:**
   - Review the default settings in `graphfleet/settings.yaml` and customize them as needed.

## Running GraphFleet

1. **Start the FastAPI Application:**
   ```bash
   uvicorn app.main:app --reload
   ```

2. **Access the Streamlit UI:**
    ```bash
   streamlit run app/streamlit_app.py  
    ```

**Make sure to have your data indexed and ready !**


## Next Steps

- Explore the Streamlit UI to perform searches, generate questions, and manage settings.
- Refer to the documentation for more advanced configuration options and usage examples.