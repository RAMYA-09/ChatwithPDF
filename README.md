# Chat with Multiple PDF Documents

This project enables users to interact with and retrieve information from multiple PDF documents via a chat interface. Users can upload PDFs, and the system extracts and indexes the text content, allowing users to ask questions and receive contextually accurate answers based on the uploaded documents.

## Features

- **Multiple PDF Upload**: Upload and process multiple PDF files at once.
- **Text Extraction**: Uses `PyPDF2` for extracting text content from PDFs.
- **Text Chunking**: Large texts are split into manageable chunks to ensure efficient processing and retrieval.
- **Contextual Response Generation**: Utilizes `GoogleGenerativeAIEmbeddings` to generate compact embeddings for text chunks and `FAISS` for efficient similarity search.
- **Interactive Chat Interface**: Built using `Streamlit`, users can easily ask questions based on the PDF content and receive detailed answers.

## Requirements

- Python 3.7+
- Streamlit
- PyPDF2
- FAISS
- GoogleGenerativeAIEmbeddings
- ChatGoogleGenerativeAI

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/chat-with-pdf.git
   cd chat-with-pdf

2. pip install -r requirements.txt

3. Ensure you have the correct API access for GoogleGenerativeAIEmbeddings and ChatGoogleGenerativeAI.

## Usage

1. Run the Stremlit app:
streamlit run app.py

2. Upload your PDF documents via the interface.

3. Ask a question based on the content of the uploaded PDFs.

4. The system will extract relevant information and provide detailed responses.
