# Ecommerce-FAQ-RAG-Chatbot
A Retrieval-Augmented Generation (RAG) based Ecommerce Customer Support Chatbot built with LangChain, OpenAI GPT, FAISS, and Gradio. This bot retrieves answers from a structured FAQ dataset and generates helpful responses for customers.

#  🚀 Features
Retrieval-Augmented Generation (RAG) for accurate, source-based answers

Semantic Search powered by OpenAI embeddings & FAISS

Interactive Web UI using Gradio (runs in Google Colab or locally)

Easy to adapt with your own FAQ or knowledge base
#  Sample json to test
<img width="563" height="187" alt="image" src="https://github.com/user-attachments/assets/79fd9943-5cbc-4690-829b-ec4fae9fd38f" />

#  How It Works

Load your FAQ dataset (JSON, TXT, PDF, etc.)

Split into chunks for better retrieval

Embed with text-embedding-3-small model

Store in FAISS vector database

Retrieve relevant chunks when a customer asks a question

Generate answer using GPT-4/4o with the retrieved context

#   Running on public URL:  https://c124a9bf3cf318a74e.gradio.live
#  Sample demo
![Uploading image.png…]()
