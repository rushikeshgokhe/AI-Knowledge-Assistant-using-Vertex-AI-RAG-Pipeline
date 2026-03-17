🤖 AI Knowledge Assistant using Vertex AI & RAG Pipeline

An intelligent AI chatbot built using Google Vertex AI and a Retrieval-Augmented Generation (RAG) pipeline to deliver accurate, context-aware answers from custom documents.

🚀 Overview

Large Language Models (LLMs) often generate generic or incorrect responses due to lack of real-time or domain-specific knowledge.
This project solves that problem using RAG (Retrieval-Augmented Generation) by retrieving relevant information from documents before generating responses.

✨ Features

📄 Document-based Question Answering

🔍 Semantic Search using Vector Embeddings

🧩 Document Chunking for efficient retrieval

⚡ Context-aware response generation using LLM

🎯 Prompt engineering for improved accuracy

🏗️ System Architecture
Documents → Chunking → Embeddings → Vector Store
                                      ↓
User Query → Embedding → Similarity Search → Context Retrieval → LLM → Response
🛠️ Tech Stack

Programming Language: Python

Platform: Google Vertex AI

Core Concepts:

Retrieval-Augmented Generation (RAG)

Vector Embeddings

Semantic Search

Prompt Engineering

🔄 Workflow

Upload documents (PDF/Text)

Split documents into smaller chunks

Convert chunks into vector embeddings

Store embeddings in vector database

Convert user query into embedding

Perform similarity search

Retrieve most relevant chunks

Pass context to LLM for response generation

📌 Use Cases

📚 Student Learning Assistant

🏢 Company Knowledge Chatbot

📄 Document-based Q&A System

🤖 Customer Support Automation

⚙️ Installation & Setup
1. Clone the Repository
git clone https://github.com/your-username/ai-knowledge-assistant.git
cd ai-knowledge-assistant
2. Install Dependencies
pip install -r requirements.txt
3. Configure Google Cloud

Enable Vertex AI API

Authenticate:

gcloud auth application-default login
4. Run the Project
python main.py
📂 Project Structure
ai-knowledge-assistant/
│
├── data/                # Input documents
├── embeddings/          # Stored embeddings (optional)
├── src/
│   ├── chunking.py
│   ├── embeddings.py
│   ├── retrieval.py
│   ├── prompt.py
│   └── main.py
│
├── requirements.txt
└── README.md
📈 Future Enhancements

🌐 Web Interface (Streamlit / React)

📊 Dashboard for analytics

🗂️ Multi-document indexing

🔐 User authentication

⚡ Faster vector search optimization

🎯 Learning Outcomes

Practical implementation of RAG architecture

Working with Vertex AI and LLMs

Understanding of vector embeddings & semantic search

Hands-on experience with prompt engineering

👨‍💻 Author

Rushikesh Gokhe

Electrical Engineering Student

Aspiring AI / Software Developer
