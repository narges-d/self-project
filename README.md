# self-project
In this reposetory i will put project i did by my-self. Feel free to customize and extend this app as needed!:)
#list of project:
1. RAG + Lang
2. summerizer
3. Gemini Chatbot
4. 
# 📄 Document Question Answering Chatbot with RAG and LangChain

This project implements a **Retrieval-Augmented Generation (RAG)** system using **LangChain** that allows you to ask questions about the content of a PDF document. The system retrieves relevant information from the document and uses a Large Language Model (LLM) — such as Google Gemini via the `ChatGooglePalm` wrapper — to generate accurate, context-aware answers.

---

## 📌 Features

- Loads and processes PDF documents to create a searchable knowledge base.
- Splits documents into manageable chunks for embedding and retrieval.
- Uses vector embeddings (e.g., OpenAI embeddings) to index document chunks in FAISS.
- Retrieves relevant document chunks based on user queries.
- Generates answers conditioned on retrieved chunks using an LLM (Google Gemini or OpenAI GPT).
- Maintains conversational history for context-aware dialogue.
- Interactive web UI built with Gradio for easy question answering.

---

# 📄 Text Summarization App

A simple interactive web application for **text summarization** built using Hugging Face Transformers and Gradio.

## 📌 Features

- Summarizes input text into a concise summary.
- Uses the pre-trained `facebook/bart-large-cnn` model for high-quality summarization.
- Interactive and easy-to-use web interface powered by Gradio.
  
----------------
# 🤖 Gemini Chatbot

A simple chatbot powered by **Google's Gemini Pro API**, designed to simulate an ebook customer service assistant. This project features a basic UI using Python, making it beginner-friendly and easy to customize.

## 📌 Features

- Interactive chatbot powered by Gemini Pro (`generativeai`)
- Lightweight UI using `Tkinter` (desktop GUI) or `Gradio` (web-based UI)
- Clean and simple code structure
- Open-source and easy to extend
