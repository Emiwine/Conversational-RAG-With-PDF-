# 📚 Conversational RAG Q&A Chatbot with PDF Upload and Chat History (Groq + LangChain)

This project is an advanced Retrieval-Augmented Generation (RAG) chatbot that lets users upload PDF files and ask context-based questions with chat history memory. Built using [LangChain](https://www.langchain.com/), [Streamlit](https://streamlit.io/), and [Groq LLMs](https://console.groq.com/), it processes PDFs and answers queries by retrieving relevant document chunks using embeddings and maintaining conversational context.

---

## 🚀 Features

- ✅ Upload and chat with multiple PDF files
- ✅ Conversational memory across sessions
- ✅ Uses Groq LLMs (`Gemma-2B-It`) for blazing-fast responses
- ✅ Contextual question reformulation using LangChain
- ✅ Integrated chat history with persistent memory
- ✅ Embedded document search with HuggingFace embeddings

---

## 🛠️ Tech Stack

- **Frontend**: Streamlit
- **LLM API**: Groq
- **Embedding Model**: HuggingFace (`all-MiniLM-L6-v2`)
- **Vector DB**: Chroma
- **Chat History**: LangChain Memory (in-session)
- **PDF Parsing**: LangChain + PyPDFLoader
- **Language**: Python 3.11+

---


