#🎥 YouTube RAG Chatbot with Memory 
🚀 Overview

This project implements a Retrieval-Augmented Generation (RAG) chatbot that allows users to interact with YouTube videos conversationally.

The system:

Extracts video transcripts

Builds semantic embeddings using FAISS

Retrieves relevant context

Maintains conversation memory

Uses Groq LLM for generation

Provides Gradio-based UI

🧠 Architecture

User Query
→ Transcript Retrieval (FAISS)
→ Context Injection
→ LLM (with Memory)
→ Final Response

🛠 Tech Stack

Python

FAISS

Groq LLM

Gradio

YouTube Transcript API

🖥 Running Locally
pip install -r requirements.txt
export GROQ_API_KEY=your_key_here
python app.py

(or run notebook in Colab)

🌍 Deployment

Deployed on HuggingFace Spaces (Free tier).

📌 Key Features

Hybrid Knowledge (Transcript + Parametric)

Conversational Memory

Multi-step RAG Pipeline

Clean Modular Design
