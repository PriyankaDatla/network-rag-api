# Network RAG API (FastAPI + Ollama)

A **Retrieval-Augmented Generation (RAG) API** built from scratch using **FastAPI**, **ChromaDB**, and **Ollama**.  
This project demonstrates how to build an AI-powered backend that answers user queries based on a **custom knowledge base**.


## Project Overview

This API accepts user questions, retrieves relevant information from a vector database, and generates contextual answers using a local Large Language Model (LLM).

The project was built to understand:
- How **RAG systems work end-to-end**
- How to build and test **REST APIs**
- How embeddings enable **semantic search**
- How to run **LLMs locally** using Ollama


## How the RAG API Works

1. Documents are converted into **embeddings** using ChromaDB  
2. A user query is embedded and matched against stored vectors  
3. Relevant context is retrieved from the knowledge base  
4. The context is passed to a **TinyLLaMA model via Ollama**  
5. The model generates a clear, concise answer  


## Tech Stack

- **Python**
- **FastAPI** – API framework
- **ChromaDB** – Vector database for embeddings
- **Ollama** – Local LLM runtime
- **TinyLLaMA** – Lightweight language model
- **Uvicorn** – ASGI server
- **Swagger UI** – API testing & documentation



