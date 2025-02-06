# 📘 DocLLM: Your Intelligent Document Assistant

**DocLLM** is a powerful document analysis tool built using **Streamlit** and **LangChain** that allows users to upload PDF documents and ask questions about the content. The app leverages **Ollama** for natural language processing and **gTTS** for text-to-speech functionality, enabling seamless interaction and spoken responses.



## Features

- Upload PDF documents for analysis.
- Ask questions related to the uploaded document.
- Get concise, factual answers based on the document content.
- Receive responses in both text and audio (text-to-speech).
- Easily view and interact with the AI-powered assistant.



## Technologies Used

- **Streamlit**: Web framework for building interactive web applications.
- **LangChain**: Framework for building applications with LLMs (Large Language Models).
- **Ollama**: LLM for generating responses based on document context.
- **gTTS (Google Text-to-Speech)**: Converts generated text into speech.
- **PDFPlumber**: For extracting text from PDF files.
- **InMemoryVectorStore**: Used to store document embeddings for fast retrieval and similarity search.



## Installation

### Requirements

To run this app locally, you need to install the following dependencies:

- Python 3.7 or higher
- `pip`

### Steps to Run

1. **Clone the Repository:**

    ```bash
    git clone https://github.com/your-repository-name/docllm.git
    cd docllm
    ```

2. **Install the Dependencies:**

    It’s recommended to use a virtual environment. If you don’t have `virtualenv` installed, you can install it via:

    ```bash
    pip install virtualenv
    ```

    Then, create and activate your virtual environment:

    ```bash
    virtualenv venv
    source venv/bin/activate  # On Windows: venv\Scripts\activate
    ```

3. **Install the Required Libraries:**

    Install the required dependencies using `pip`:

    ```bash
    pip install -r requirements.txt
    ```

4. **Run the Application:**

    After the dependencies are installed, run the Streamlit app:

    ```bash
    streamlit run app.py
    ```

    This will open the app in your browser. You can start uploading PDFs and asking questions.



## Usage

1. **Upload a PDF Document**: Click on the "Upload Research Document (PDF)" button to select your file.
2. **Ask a Question**: Type your question in the text input box, and the app will analyze the document to provide an answer.
3. **Listen to the Answer**: The answer will be displayed as text and also converted to speech for audio playback.

## Acknowledgements

- [Streamlit](https://streamlit.io/) for building interactive web apps.
- [LangChain](https://langchain.com/) for powerful LLM integration.
- [gTTS](https://gtts.readthedocs.io/en/latest/) for easy text-to-speech conversion.
- [Ollama](https://ollama.com/) for advanced natural language processing.
- [PDFPlumber](https://github.com/jsvine/pdfplumber) for extracting text from PDFs.


