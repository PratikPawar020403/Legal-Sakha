# Legal-Sakha 
# Indian Legal AI Assistant

AI-powered chatbot for querying Indian legal documents with accurate citations.

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

## 📚 Dataset

**Drive link for Legal Documents**: "https://drive.google.com/drive/folders/1sZsDxZxz203ZYGI_2vS0rvwxXgod6vxk?usp=sharing"

Contains 40+ official Indian legal documents including:
- Indian Constitution
- Bharatiya Nyaya Sanhita (BNS) 2023
- Online Gaming Act 2023
- and more ...

## Setup

1. **Download legal documents** from the link above and upload to your Google Drive
2. **Mount Google Drive** with PDFs in Colab
3. **Install dependencies**: Run the requirements cell
4. **Load models** and process documents
5. **Build FAISS index** from document embeddings
6. **Launch Gradio interface**

## Usage

Ask legal questions in plain language → Get answers with relevant act/section references.

**Example queries**:
- "What are the fundamental rights in Indian Constitution?"
- "Explain Section 103 of BNS 2023"
- "Online gaming regulations in India"

## Requirements

- Google Colab (Free T4)
- Google Drive
- Indian legal PDFs (drive link provided above)
