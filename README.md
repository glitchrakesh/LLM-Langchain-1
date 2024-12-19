# Langchain Server and Client

This project demonstrates a simple integration of Langchain with Streamlit. It provides a user interface to generate responses using OpenAI's ChatGPT and Ollama's LLaMA2 models.

---

## Features

- **OpenAI ChatGPT Integration:** Generates responses to user queries using OpenAI's GPT-3.5 Turbo model.
- **Ollama LLaMA2 Integration:** Generates responses to user queries using Ollama's LLaMA2 model.
- **Streamlit UI:** A user-friendly interface for interacting with the language models.

---

## Installation

### Prerequisites

- Python 3.8+
- Streamlit
- Langchain
- dotenv
- Other dependencies listed in `requirements.txt`

---

### Steps

1. Clone the repository:
   ```bash
   git clone <repository-url>
   cd <repository-folder>
2. Create a virtual environment and activate it:
   ```bash
   python -m venv venv
   source venv/bin/activate # On Windows: venv\Scripts\activate
3. Install dependencies:
   ```bash
   pip install -r requirements.txt
4. Set up environment variables:
  Create a .env file in the root directory.
5. Run the OpenAI Streamlit client:
   ```bash
   streamlit run ./app.py
   streamlit run ./localama.py

---
##Usage

1. **Run the Applications:** Ensure both Streamlit applications are running on localhost:8501.
2. **Interact via Streamlit:** Open the Streamlit app in your browser at the URL shown in the terminal (usually http://localhost:8501).
3. **Generate Content:** Enter a topic in the input field to receive a response from the selected language model.

---

##File Structure

-MultipleFiles/app.py: Streamlit app for OpenAI GPT-3.5 Turbo integration.
-MultipleFiles/localama.py: Streamlit app for Ollama LLaMA2 integration.

---

##Notes

-Ensure that the OpenAI and Langchain API keys are valid and active.
-Customize prompt templates in app.py and localama.py as needed.
-Adjust the host and port in the Streamlit commands if necessary.

---

## Contributors

- [Rakesh Shetty](https://github.com/glitchrakesh)

---
