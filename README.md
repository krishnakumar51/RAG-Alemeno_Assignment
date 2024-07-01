# RAG Chatbot

This project implements a Retrieval-Augmented Generation (RAG) chatbot using the LangChain framework. The chatbot leverages a local LLM (Llama3) through Ollama, FastEmbedEmbeddings with the "BAAI/bge-base-en-v1.5" model for embeddings, and the FAISS vector database for storing and indexing embeddings.

## Installation

1. **Clone the repository:**

    ```bash
    git clone https://github.com/yourusername/rag-chatbot.git
    cd rag-chatbot
    ```

2. **Set up a virtual environment:**

    ```bash
    python3 -m venv env
    `env\Scripts\activate`
    ```

3. **Install the dependencies:**

    ```bash
    pip install -r requirements.txt
    ```

4. **Install and configure FAISS:**

    Follow the instructions from the [FAISS installation guide](https://github.com/facebookresearch/faiss/blob/main/INSTALL.md).

5. **Set up Ollama and the Llama3 model:**

    Refer to the [Ollama documentation](https://ollama.com/docs) for installing and configuring Ollama and setting up the Llama3 model.

## Usage

1. **Run the chatbot:**

    ```bash
    streamlit run app.py
    ```

2. **Interact with the chatbot through the provided interface:**

    The chatbot interface will be accessible through the terminal or a web UI if implemented.

## Features

- **Retrieval-Augmented Generation:** The chatbot uses a combination of information retrieval and generation techniques to provide accurate and contextually relevant responses.
- **FAISS Vector Database:** Efficient storage and retrieval of document embeddings using FAISS.
- **Local LLM:** Utilizes a locally running LLM (Llama3) via Ollama for generating responses.
- **FastEmbedEmbeddings:** Employs the "BAAI/bge-base-en-v1.5" model for generating high-quality embeddings of the input text.

## Contributing

We welcome contributions to enhance the functionality and features of this RAG chatbot. If you have any suggestions or improvements, please create a pull request or open an issue.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.
