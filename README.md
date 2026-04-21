# Legal-Sakha ⚖️
# Indian Legal AI Assistant

AI-powered chatbot for querying Indian legal documents with accurate citations.

---

## 🌐 Try it Online

**Live demo (no setup needed):** [Legal-Sakha on Hugging Face Spaces](https://huggingface.co/spaces/pp22/Legal-Sakha)

Bring your own API key (OpenAI / Groq / Gemini) — it is never stored.

---

## 🖥️ Run Offline (Google Colab + GPU)

For full GPU-accelerated performance on your own documents:

1. **Download legal documents** from the Drive link below and place them in your Google Drive
2. Open the notebook in **Google Colab** (Runtime → T4 GPU)
3. Mount Google Drive and set your PDF folder path
4. Run all cells — the vector DB builds automatically
5. Use the Gradio UI that launches at the end

**Drive link for Legal Documents:**
[https://drive.google.com/drive/folders/1sZsDxZxz203ZYGI_2vS0rvwxXgod6vxk?usp=sharing](https://drive.google.com/drive/folders/1sZsDxZxz203ZYGI_2vS0rvwxXgod6vxk?usp=sharing)

Contains 40+ official Indian legal documents including:
- Indian Constitution
- Bharatiya Nyaya Sanhita (BNS) 2023
- Bharatiya Nagarik Suraksha Sanhita (BNSS) 2023
- POCSO Act
- NDPS Act
- IT Act
- Online Gaming Act 2023
- and more...

---

## Features

- RAG-based Q&A grounded in real legal documents
- Semantic search with FAISS vector database
- Streaming responses with source citations
- Supports OpenAI, Groq, and Gemini providers
- Works online (HF Spaces) and offline (Colab + GPU)

## Tech Stack

| Component    | Technology                        |
|-------------|-----------------------------------|
| Embeddings  | BAAI/bge-large-en-v1.5            |
| Vector DB   | FAISS                             |
| UI          | Gradio                            |
| Online      | Hugging Face Spaces (CPU)         |
| Offline     | Google Colab (T4 GPU)             |
| Providers   | OpenAI · Groq · Gemini            |

## Example Queries

- *"At what age is a child exempt from criminal liability?"*
- *"What are the fundamental rights in the Indian Constitution?"*
- *"Explain Section 103 of BNS 2023"*
- *"What are the cybercrime provisions under the IT Act?"*
- *"Online gaming regulations in India"*
