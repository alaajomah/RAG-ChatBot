# 📚 Multi-PDF RAG Study Assistant

A Retrieval-Augmented Generation (RAG) chatbot that allows users to upload PDF course materials and ask questions about their content.

The system retrieves the most relevant document sections using FAISS vector search and generates context-aware answers using OpenAI language models.
[![Hugging Face Spaces](https://img.shields.io/badge/HuggingFace-Live%20Demo-yellow)](h[ttps://huggingface.co/spaces/YOUR_USERNAME/YOUR_SPACE_NAME](https://huggingface.co/spaces/alaa03/GenerativeAI-Course-Study-Chatbot)

## Features

- Upload one or multiple PDF files
- Automatic document chunking and indexing
- Semantic search using embeddings
- FAISS vector database for retrieval
- OpenAI-powered answer generation
- Interactive Gradio chat interface

## Technologies Used

- Python
- LangChain
- OpenAI Embeddings
- GPT-4.1 Mini
- FAISS
- Gradio
- PyPDFLoader

## How It Works

1. Upload PDF documents.
2. The documents are split into smaller chunks.
3. Chunks are converted into vector embeddings.
4. FAISS stores and retrieves the most relevant chunks.
5. The retrieved context is passed to the LLM.
6. The chatbot generates an answer based only on the uploaded materials.

## Installation

```bash
pip install -r requirements.txt
```

## Run the Application

```bash
python app.py
```

## Usage

1. Upload one or more PDF files.
2. Click **Build Index**.
3. Ask questions about the uploaded documents.
4. Receive context-aware answers generated from the document content.

## Project Structure

```text
├── app.py
├── requirements.txt
├── README.md
```





