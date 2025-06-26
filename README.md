# 🤖 RAG-Based Q&A System (FAISS + OpenAI)

This project is a **Retrieval-Augmented Generation (RAG)** system using:

- **FAISS** for fast vector similarity search
- **OpenAI** GPT models for answering user questions
- **LangChain** for orchestration
- A `.env` file for securely storing API keys

You can ask questions based on any document (like a PDF or text file) after indexing it.

---

### ⚙️ Features

- Load and embed document content using OpenAI
- Store vectors using **FAISS**
- Ask natural language questions
- Uses **retrieved context** + GPT for accurate responses

---

### 📦 Install Dependencies

Install all required packages with:

```bash
pip install openai langchain faiss-cpu python-dotenv
