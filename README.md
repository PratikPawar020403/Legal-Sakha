Lega-Sakha 
# Indian Legal AI Assistant

AI-powered chatbot for querying 40+ Indian legal documents with accurate citations.

## Features

- RAG-based Q&A system for Indian laws (Constitution, BNS, Online Gaming Act, etc.)
- Semantic search with FAISS vector database
- Conversational memory and streaming responses
- OCR support for scanned PDFs
- Act/section citations with explanations

## Tech Stack

- **LLM**: Gemma 3n E4B (GGUF)
- **Embeddings**: BGE (BAAI)
- **Vector DB**: FAISS
- **UI**: Gradio
- **Platform**: Google Colab (T4 GPU)

## Setup

1. Mount Google Drive with PDFs
2. Install dependencies
3. Load models and process documents
4. Build FAISS index
5. Launch Gradio interface

## Usage

Ask legal questions in plain language → Get answers with relevant act/section references.

## Requirements

- Google Colab (Free T4)
- Google Drive
- 40+ Indian legal PDFs
