# AI Document Retrieval and Comprehension System

## Project Description

This project implements an AI-powered document retrieval and comprehension system. The system leverages a **retrieval-augmented generation (RAG)** approach where relevant documents are retrieved from a large corpus based on user queries and then used as context for generating more informative answers using a language model (DistilGPT-2).

The system is built using **SentenceTransformers** for generating embeddings and **FAISS** for fast vector-based document retrieval. The **DistilGPT-2** model is used for generating human-like responses based on the retrieved documents.

## Features

- Document encoding using **SentenceTransformers**.
- Efficient document retrieval using **FAISS** (Fast Approximate Nearest Neighbor Search).
- Text generation using the **DistilGPT-2** model.
- Retrieval-augmented generation (RAG) to improve the accuracy and relevance of answers.

## Installation

### 1. Clone the repository:

```bash
git clone https://github.com/your-username/document-retrieval-comprehension.git
cd document-retrieval-comprehension
