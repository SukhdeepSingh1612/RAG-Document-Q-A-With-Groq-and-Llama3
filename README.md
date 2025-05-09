
# 🧠 RAG Document Q&A with Groq and LLaMA 3

This is a Streamlit-based web application that enables users to query a set of PDF research papers using Retrieval-Augmented Generation (RAG). It utilizes the **LLaMA 3 (8B)** model from **Groq** for fast and intelligent responses, and **OpenAI embeddings** for semantic search, stored using **FAISS**.

### Deployed on Streamlit : https://rag-document-q-a-with-groq-and-llama3-8emryu2nsnveftqnq8tesb.streamlit.app/

---

## 🚀 Features

- ✅ Upload and process multiple PDF documents from a folder
- 🧠 Embedding generation via OpenAI
- ⚡ Inference powered by Groq's LLaMA 3 model
- 🔎 Document retrieval using FAISS
- 💬 Ask questions and receive contextual answers
- 🎛️ Simple and clean Streamlit interface

---

## 📁 Project Structure

```
RAG-Document-QA/
│
├── app.py                # Streamlit app source code
├── research_papers/      # Folder containing PDF documents
├── requirements.txt      # Dependencies
└── .env                  # Environment variables (excluded from GitHub)
```

---

## 🧪 Installation

### 1. Clone the repository

```bash
git clone https://github.com/yourusername/RAG-Document-QA.git
cd RAG-Document-QA
```

### 2. Create and activate a virtual environment (optional but recommended)

```bash
python -m venv venv
source venv/bin/activate  # Windows: venv\Scripts\activate
```

### 3. Install the dependencies

```bash
pip install -r requirements.txt
```

### 4. Add your API keys to `.env`

Create a `.env` file in the root directory and add:

```env
GROQ_API_KEY=your_groq_api_key
OPENAI_API_KEY=your_openai_api_key
```

---

## ▶️ Running the App

Ensure your research papers are inside the `research_papers/` folder, then run:

```bash
streamlit run app.py
```

---

## 📚 Tech Stack

- [Streamlit](https://streamlit.io/)
- [LangChain](https://python.langchain.com/)
- [Groq](https://groq.com/)
- [Meta LLaMA 3](https://ai.meta.com/llama/)
- [FAISS](https://github.com/facebookresearch/faiss)
- [OpenAI Embeddings](https://platform.openai.com/docs/guides/embeddings)

---

## 👨‍💻 Author

**Sukhdeep Singh**  
