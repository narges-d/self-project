# Document Question Answering Chatbot with RAG and LangChain

This project implements a **Retrieval-Augmented Generation (RAG)** system using **LangChain** that allows you to ask questions about the content of a PDF document. The system retrieves relevant information from the document and uses a Large Language Model (LLM) — such as Google Gemini via the `ChatGooglePalm` wrapper — to generate accurate, context-aware answers.

---

## Features

- Loads and processes PDF documents to create a searchable knowledge base.
- Splits documents into manageable chunks for embedding and retrieval.
- Uses vector embeddings (e.g., OpenAI embeddings) to index document chunks in FAISS.
- Retrieves relevant document chunks based on user queries.
- Generates answers conditioned on retrieved chunks using an LLM (Google Gemini or OpenAI GPT).
- Maintains conversational history for context-aware dialogue.
- Interactive web UI built with Gradio for easy question answering.

---

## Requirements

- Python 3.7+
- Install dependencies with:

```bash
pip install langchain openai faiss-cpu PyPDF2 gradio
