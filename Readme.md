# 🧠 AI Assistant with Document QA + Appointment Booking

This project is a simple **Conversational AI Assistant** built in Python using:

- `LangChain` for document loading and vector storage  
- `FAISS` for similarity search  
- `transformers` for summarization and question answering  
- `dateparser` and `re` for scheduling and user input validation  

It can:
- 📄 Summarize a long text document  
- 🔍 Answer questions based on the document  
- 📞 Take user requests to be contacted  
- 📅 Book appointments using natural language  
- ✅ Collect and validate user info conversationally

---

## 🚀 Features

- 📄 **Document Ingestion & Chunking**  
- 🧠 **Semantic Embedding with HuggingFace Transformers**  
- 🔍 **Similarity Search with FAISS**  
- ✨ **Summarization and Q&A using BART and FLAN-T5**  
- 📅 **Natural Language Date Parsing**  
- 📞 **Call Request Detection & Contact Info Collection**  
- 📆 **Appointment Scheduling with Validation**

---

## 📦 Requirements

Install all dependencies:

```bash
pip install -U langchain langchain-community faiss-cpu sentence-transformers transformers dateparser
```

Run this command in your terminal to install all required packages.
