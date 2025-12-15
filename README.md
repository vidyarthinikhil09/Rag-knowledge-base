# 🧠 Gemini RAG Knowledge Base

A local **Retrieval-Augmented Generation (RAG)** application that allows users to "chat" with their PDF documents. Built using **Google Gemini 1.5 Pro**, **LangChain**, and **FAISS** vector storage.

## 🚀 Features
- **📄 Document Ingestion**: Loads PDFs and splits them into semantic chunks.
- **🔍 Vector Search**: Uses FAISS for high-speed local similarity search.
- **🤖 Grounded Answers**: Strict prompt engineering ensures the bot answers ONLY from your documents (no hallucinations).
- **📌 Source Citations**: Returns the exact source file and page number for verification.

## 🛠️ Tech Stack
- **LLM**: Google Gemini 1.5 Flash
- **Embeddings**: Gemini Text-Embedding-004
- **Framework**: LangChain v0.2
- **Vector DB**: FAISS (CPU)

## ⚙️ Setup

1. **Clone the repo**
   ```bash
   git clone [https://github.com/YOUR_USERNAME/gemini-rag-knowledge-base.git](https://github.com/YOUR_USERNAME/gemini-rag-knowledge-base.git)
   cd gemini-rag-knowledge-base
