# Trinova-s-GenAI-Project

## 🚀 Overview
Trinova AI Tutor is a full-stack web application that allows users to interact with textbook PDFs using natural language queries. It provides answers, summaries, and explanations by intelligently retrieving relevant content from documents.

## 👥 Team Trinova
- Team Size: 3 Members  
- Project developed for efficient, scalable AI-powered education in low-resource environments 

## 🎯 Features

- 📄 Upload PDF documents
- 📚 Preloaded NCERT book support
- 🔍 Semantic search using embeddings
- ✂️ Context pruning for optimized responses
- ⚡ Fast retrieval using FAISS
- 🧠 Ask questions, summaries, explanations
- 🌐 Full web interface (frontend + backend)
- 📊 Efficient and low-cost processing


## ⚙️ How It Works

1. User uploads or selects a PDF
2. Backend extracts text using PyMuPDF
3. Text is split into chunks
4. Each chunk is converted into embeddings
5. FAISS indexes embeddings for fast search
6. Relevant chunks are retrieved based on query
7. Context pruning reduces unnecessary data
8. Final response is generated and sent to frontend


## 📊 Optimization

- Reduced data processing using context pruning
- Faster response time
- Lower computational cost
