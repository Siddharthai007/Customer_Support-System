
```
 conda create -p env python=3.10 -y
```
```
conda activate env
```
```
uvicorn main:app --reload --port 8001
```
# 📞 Customer Support System  
**AI-ready backend for customer query handling with FastAPI, Retrieval, Data Ingestion, and Prompt Libraries.**

---

## 🚀 Overview  
This project is a **modular Customer Support System** designed to handle customer queries, retrieve relevant information, and serve responses through a FastAPI backend.

The system includes:
- 🔹 **FastAPI Application** (`main.py`)  
- 🔹 **Data Ingestion Pipeline** (`data_ingestion/`)  
- 🔹 **Retriever Module** (`retriever/`)  
- 🔹 **Prompt Library for LLMs** (`prompt_library/`)  
- 🔹 **Frontend Templates** (`templates/`, `static/`)  
- 🔹 **Sample Data & Testing Scripts**

It is built to help developers prototype **customer-support chatbots**, **FAQ assistants**, or **retrieval-based support tools** quickly.

---

## 📂 Project Structure

├── main.py # FastAPI entry point
├── data/ # Raw / processed datasets
├── data_ingestion/ # Scripts for ingestion & preprocessing
├── retriever/ # Retrieval engine / vector search logic
├── prompt_library/ # Predefined prompts for LLM workflows
├── templates/ # HTML templates for UI
├── static/ # CSS, JS, and static assets
├── test.py # Testing script
├── requirements.txt
└── setup.py


High-performance asynchronous API server for handling requests and serving templates.

## 🧩 Features

✔️ FastAPI Backend

High-performance asynchronous API server for handling requests and serving templates.

✔️ Data Ingestion Pipeline

Upload, clean, and store data used for retrieval.

✔️ Retriever Engine

Search and fetch relevant support information from your dataset.

✔️ Prompt Library

Centralized store of prompts used for LLM-based responses.

✔️ Simple Frontend UI

HTML templates & assets included for quick demo usage.

✔️ Modular & Extendable

## Easily integrate vector DBs, LLM APIs, or custom pipelines.
💡 Future Improvements

Vector DB integration (FAISS, ChromaDB, Weaviate)

OpenAI / Llama 3 / Groq API integration

Add memory/chat history

Convert tests to pytest

GitHub Actions CI/CD workflow

Improved UI with chat interface
