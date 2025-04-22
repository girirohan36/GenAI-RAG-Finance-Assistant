# AskMy10K: A RAG-Powered Financial Report Assistant

AskMy10K is a Retrieval-Augmented Generation (RAG) based assistant that helps users query financial filings like 10-Ks and earnings reports using natural language, delivering grounded and insightful responses.

## Architecture

 PDF/HTML Financial Reports 
    -->  Text Chunking + Cleaning 
    -->  Embeddings (OpenAI, HF) 
    -->  Vector DB (FAISS / Chroma) 
    -->  Retriever + LLM (LangChain) 
    -->  Streamlit Frontend UI

## Features

- Upload and analyze financial reports (PDF)
- Ask questions in natural language (e.g., "What were the main risk factors in 2023?")
- Get grounded responses with links to document sources
- Deployable as a web app using Streamlit


##  Tech Stack

- **LangChain** – RAG framework for retrieval and QA
- **OpenAI** – GPT-based LLM for response generation
- **FAISS / Chroma** – Vector store for semantic search
- **PyMuPDF / Unstructured** – PDF text extraction
- **Streamlit** – Interactive user interface
