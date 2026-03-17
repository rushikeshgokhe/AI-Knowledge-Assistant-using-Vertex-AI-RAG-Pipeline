🤖 AI Knowledge Assistant using Vertex AI & RAG Pipeline

An intelligent AI chatbot built using Google Vertex AI and a Retrieval-Augmented Generation (RAG) pipeline to provide accurate, context-aware responses from custom documents.

🚀 Overview

Large Language Models (LLMs) can generate incorrect or generic responses due to lack of domain-specific knowledge.
This project enhances LLM performance using RAG (Retrieval-Augmented Generation) by retrieving relevant information from documents before generating answers.

✨ Features

Document-based Question Answering

Semantic search using vector embeddings

Document chunking for efficient processing

Context-aware response generation using LLM

Prompt engineering for improved accuracy

🏗️ Architecture

Documents → Chunking → Embeddings → Vector Store
User Query → Embedding → Similarity Search → Context Retrieval → LLM → Response

🛠️ Tech Stack

Programming Language: Python

Platform: Google Vertex AI

Concepts Used:

Retrieval-Augmented Generation (RAG)

Vector Embeddings

Semantic Search

Prompt Engineering

🔄 Workflow

Upload documents (PDF/Text)

Split documents into chunks

Convert chunks into vector embeddings

Store embeddings in a vector database

Convert user query into embedding

Perform similarity search

Retrieve relevant chunks

Send context to LLM

Generate final response

📌 Use Cases

Student learning assistant

Company knowledge chatbot

Document-based Q&A system

Customer support automation

⚙️ Installation & Setup
1. Clone the repository

git clone https://github.com/rushikeshgokhe/ai-knowledge-assistant.git

cd ai-knowledge-assistant

2. Install dependencies

pip install -r requirements.txt

3. Configure Google Cloud

Enable Vertex AI API

Authenticate using:
gcloud auth application-default login

4. Run the project

python main.py

📂 Project Structure

ai-knowledge-assistant/
│
├── data/
├── embeddings/
├── src/
│ ├── chunking.py
│ ├── embeddings.py
│ ├── retrieval.py
│ ├── prompt.py
│ └── main.py
│
├── requirements.txt
└── README.md

📈 Future Improvements

Add Streamlit or web-based UI

Multi-document support

Authentication system

Performance optimization

Logging and analytics

🎯 Learning Outcomes

Understanding of RAG architecture

Hands-on experience with Vertex AI

Implementation of vector embeddings

Improved prompt engineering skills

👨‍💻 Author

Rushikesh Gokhe
Aspiring AI / Software Developer
