# Local-LLM-App-with-Streamlit-and-Ollama-llama3.2-latest-
A simple demonstration of Local LLM App with streamlit and ollama models

# **Prerequisites**

1. **Python**: Ensure you have Python 3.7 or later installed. You can download it from [python.org](https://www.python.org/).
2. **Streamlit**: Install Streamlit using pip
    
    ```python
    pip install streamlit
    ```
    
3. **Ollama:** To use and install models with Ollama, follow these steps:
    - Download Ollama: Visit the [Ollama website](https://ollama.com/) and download the appropriate version for your OS.
    - List Models: Verify the downloaded models with `ollama list`.
    - Download and Run a Model: Execute the model with `ollama run [model_name]`.

## A. Setting Up the Virtual Environment

Before installing the required packages, it’s a good practice to create a virtual environment. This isolates your project and avoids conflicts with other packages.

```
pip install virtualenv
virtualenv venv
```

Activate the Virtual Environment:

- Linux/MacOS:
- `source venv/bin/activate`
- Windows:
- `.\venv\Scripts\activate`

## **B. Installing Required Packages**

Within the activated virtual environment, install the required packages:

```
pip install streamlit llama-index
```

## **C. Run the Streamlit App**

```
streamlit run ollama-streamlit-app.py
```
>>>>>>> f01e8b4 (Main Commit)
