# End-To-End Document Q&A RAG App with Groq and Gemma



This repository contains an end-to-end implementation of a Retrieval Augmented Generation (RAG) application for document question answering. It leverages the power of Groq's fast inference capabilities and Google's Gemma model for efficient and accurate question answering over your documents.

# Kind of architecture



![RAG_Model_Arch](https://github.com/user-attachments/assets/465e80c7-44e4-443c-bceb-587eedf9c31e)


## Features



* **Document Ingestion:** Supports ingestion of various document formats (e.g., PDFs, text files).

* **Text Chunking & Embedding:** Splits documents into manageable chunks and generates embeddings for semantic search.

* **Vector Database:** Utilizes a vector database **FAISS**  for efficient similarity search.

* **Groq Inference:** Integrates with Groq for fast inference, providing low-latency responses.

* **Gemma Model:** Employs Google's Gemma model for generating accurate and contextually relevant answers.



## Technologies Used



* **Groq:** For fast inference.

* **Google Gemma:** Large Language Model.

* **Python:** Programming language.

* **Vector Database:** FAISS.

* **Embedding Model:** GoogleGenerativeAIEmbeddings .

* **Frameworks/Libraries:** LangChain, Streamlit.



## Prerequisites



* Python 3.x

* Groq API key (using Groq Cloud)

* GoogleAI Studio



## Installation



1.  Clone the repository:



    ```bash

    git clone [https://github.com/Vijayvarma115/End-To-End-Document-Q-A-RAGapp-Groq-Gemma-.git](https://www.google.com/search?q=https://github.com/Vijayvarma115/End-To-End-Document-Q-A-RAGapp-Groq-Gemma-.git)

    cd End-To-End-Document-Q-A-RAGapp-Groq-Gemma-

    ```



2.  Create a virtual environment (recommended):



    ```bash

    python -m venv venv

    source venv/bin/activate  # On macOS/Linux

    venv\Scripts\activate  # On Windows

    ```



3.  Install dependencies:



    ```bash

    pip install -r requirements.txt

    ```



4.  Set up your Groq API key:



    * Store your API key in an environment variable or configuration file.



## Usage



1.  Place your documents in the `documents/` directory.



2.  Run the application:


    ```bash

    python app.py #or whatever the main file is called.

    ```
4.  Ask questions related to your documents.
