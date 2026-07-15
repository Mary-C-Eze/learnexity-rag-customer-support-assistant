# Learnexity RAG-Powered Customer Support Assistant

## Project Overview

This project demonstrates the implementation of a Retrieval-Augmented Generation (RAG) system that answers customer support questions using a custom knowledge base.

Instead of relying solely on a Large Language Model's pre-trained knowledge, the assistant retrieves relevant information from a Learnexity customer support knowledge base before generating responses.

The project was developed as the final capstone project for a RAG Systems course.

---

## Features

- Custom customer support knowledge base
- Semantic document retrieval
- Sentence Transformer embeddings
- ChromaDB vector database
- Configurable document chunking
- Question Answering using Hugging Face Transformers
- Confidence-based response handling
- Source attribution
- Edge case detection

---

## Knowledge Base

The knowledge base includes detailed documentation covering:

- Company Overview
- Programs and Services
- Pricing and Payment Plans
- Enrollment Process
- Technical Support
- FAQs
- Customer Support
- Company Policies

---

## Technologies

- Python
- ChromaDB
- Sentence Transformers
- Hugging Face Transformers
- Retrieval-Augmented Generation (RAG)
- Google Colab

---

## Project Architecture

Knowledge Base

↓

Document Chunking

↓

Sentence Embeddings

↓

ChromaDB Vector Database

↓

Semantic Retrieval

↓

Question Answering Model

↓

Customer Response

---

## Example Questions

- How much does the AI Engineering Bootcamp cost?

- What is Learnexity's refund policy?

- How can I reset my password?

- Does Learnexity offer scholarships?

- Can organizations request customized training?

---

## Results

The assistant was evaluated using four categories of questions:

- Simple factual questions
- Detailed explanation questions
- Comparative questions
- Edge case questions

The system successfully retrieved relevant documents and generated grounded responses with source attribution.

---

## Future Improvements

- Hybrid Search (BM25 + Semantic Search)

- Cross-Encoder Reranking

- GPT-powered Response Generation

- Conversational Memory

- Web Interface using Streamlit

- Persistent ChromaDB Storage


