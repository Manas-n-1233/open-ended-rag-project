# Open Ended RAG Project using LangChain and FAISS

This project demonstrates a simple Retrieval-Augmented Generation (RAG) pipeline using:

- LangChain
- FAISS Vector Database
- Sentence Transformers
- Hugging Face Transformers
- Python

# Features:
- Text loading using LangChain
- Text chunking
- Embedding generation
- FAISS vector storage
- Semantic search
- Simple RAG workflow

# Folder Structure
open-ended-rag-project/
│
├── open_ended.ipynb
├── hydroponics.txt
├── README.md
├── requirements.txt
├── .gitignore


# Project Architecture

```text
User Query
     ↓
Text Retrieval using FAISS
     ↓
Semantic Similarity Search
     ↓
Relevant Chunks Retrieved
     ↓
Response Generation


Installation:
git clone https://github.com/your-username/open-ended-rag-project.git

cd open-ended-rag-project

pip install -r requirements.txt

Run:
jupyter notebook

Author:
Manasa N Nayaka
