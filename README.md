# 📚 Chat with Your PDFs – AI PDF Question Answering App

This is a Streamlit web application that allows users to upload PDF files, process the content using embeddings, and ask questions about the content using natural language. The app leverages **LangChain**, **FAISS**, and **OpenAI embeddings** for semantic search and intelligent question answering.


## 🚀 Features

- 📄 Upload multiple PDF files
- 📚 Extract and chunk text from PDFs
- 🤖 Generate vector embeddings for semantic search
- 🔍 Ask questions in natural language and get relevant answers
- 💾 Save and load FAISS index for fast retrieval
  

## 🛠️ Tech Stack

- **Python**
- **Streamlit** – for the web interface
- **LangChain** – for question answering
- **FAISS** – for vector similarity search
- **OpenAI / HuggingFace Embeddings** – for encoding text
- **PyMuPDF (`fitz`)** – for PDF parsing

---

## 📁 Project Structure
pdf_project/
│
├── app.py # Main Streamlit app
├── faiss_index/ # Saved FAISS index and metadata
├── requirements.txt # Required Python packages
├── utils.py # Optional: for helper functions
└── README.md # This file

