# 📚 TRINOVA — Shiksha AI with Context Pruning  
Turning dense textbooks into smart, efficient learning — powered by Retrieval & Context Pruning.

---

## 👥 Team Trinova
- Team Size: 3 Members  
- Project developed for efficient, scalable AI-powered education in low-resource environments

--- 


# 🧠 The Problem  
Educational textbooks (like NCERT) are often:

📖 Too lengthy — students struggle to find exact answers  
💸 Costly to process — sending full documents to LLMs increases token usage  
⏱️ Slow — large inputs increase latency  
🚫 Inefficient — irrelevant content reduces answer quality  

---

# 💡 The Solution  
TRINOVA Shiksha AI is an intelligent learning system that:

- Retrieves only the most relevant parts of a document using semantic search  
- Applies Context Pruning to remove unnecessary information  
- Generates efficient, focused answers for student queries  
- Minimizes cost and improves performance  

---

# ⚡ Core Technique — Context Pruning  

Instead of sending full documents to an AI model:

Full Textbook (50,000+ words)  
        ↓  
Text Chunking  
        ↓  
Semantic Retrieval (FAISS)  
        ↓  
Context Pruning Engine  
        ↓  
Optimized Context  
        ↓  
Response Output  

👉 Only the most relevant information is processed.

---

# 🔧 Optimization Pipeline  

| Step | Technique | Benefit |
|------|----------|--------|
| 1️⃣ | PDF Text Extraction | Converts document into usable text |
| 2️⃣ | Chunking | Breaks large text into smaller parts |
| 3️⃣ | Embedding Generation | Converts text → vectors |
| 4️⃣ | FAISS Retrieval | Finds most relevant chunks |
| 5️⃣ | Context Pruning | Removes low-relevance content |
| 6️⃣ | Response Generation | Produces final answer |

👉 Result: Significant reduction in unnecessary processing

---

# 🖥️ Features  

✅ Ask questions from textbooks  
✅ Upload your own PDF files  
✅ Preloaded NCERT books  
✅ Context pruning for efficiency  
✅ Fast semantic search using FAISS  
✅ Chat history tracking  
✅ File upload & delete system  
✅ Real-time processing metrics  

---

# 📁 Project Structure  

Trinova-Shiksha-AI/  
├── App.css
├── App.jsx  
├── README.md 
├── index.css
├── main.jsx
├── server (1).js  

---

# 🚀 Setup & Installation  

## Prerequisites  
- Python 3.10+  
- pip installed  

---

## Step 1 — Clone Repo  

git clone https://github.com/Piyush-Kumar-25/Trinova-s-GenAI-Project.git  
cd Trinova-Shiksha-AI  

---

## Step 2 — Install Dependencies  

pip install -r requirements.txt  

---

## Step 3 — Run App  

streamlit run app.py  

---

# 🎮 How to Use  

1. Select a book OR upload a PDF  
2. Enter your question  
3. System retrieves relevant content  
4. Context pruning removes unnecessary parts  
5. Optimized answer is displayed  

---

# 🏗️ Architecture  

User → Streamlit UI → Backend Logic → PDF Processing → Embeddings → FAISS → Retrieval → Context Pruning → Answer  

---

# 📊 Optimization Insight  

- Reduced unnecessary text before answering  
- Faster response time  
- Lower computational cost  

---

# 🌍 Real-World Use Case  

Designed for:
- Students using NCERT textbooks  
- Low-bandwidth environments  
- Cost-sensitive AI systems  

---

# 🛠️ Tech Stack  

Frontend: Streamlit  
Backend: Python  
AI/ML: Sentence Transformers  
Retrieval: FAISS  
Processing: PyMuPDF  
Data: NumPy  

---

# 🔮 Future Improvements  

- LLM integration  
- Better UI (React)  
- Multi-language support  
- Voice input  
- Performance optimization  

---


# 📜 License  

MIT License  

---

# 🙏 Acknowledgements  

- Sentence Transformers  
- FAISS  
- NCERT  

---

## Version
The current version of the project successfully implements context pruning and retrieval-based answering. Due to time constraints, further improvements such as enhanced answer formatting and advanced prompt optimization were not fully implemented. These enhancements can significantly improve answer quality and user experience in future iterations.

# 💬 Final Note  
TRINOVA — because learning should be fast, efficient, and accessible to everyone.
