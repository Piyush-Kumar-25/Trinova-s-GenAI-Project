#📚 TRINOVA — Shiksha AI with Context Pruning
Turning dense textbooks into smart, efficient learning — powered by Retrieval & Context Pruning.

##🧠 The Problem

Educational textbooks (like NCERT) are often:

📖 Too lengthy — students struggle to find exact answers
💸 Costly to process — sending full documents to LLMs increases token usage
⏱️ Slow — large inputs increase latency
🚫 Inefficient — irrelevant content reduces answer quality

##💡 The Solution

TRINOVA AI Tutor is an intelligent learning system that:

Retrieves only the most relevant parts of a document using semantic search
Applies Context Pruning to remove unnecessary information
Generates efficient, focused answers for student queries
Minimizes cost and improves performance

##⚡ Core Technique — Context Pruning

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

##🔧 Optimization Pipeline
Step	Technique	Benefit
1️⃣	PDF Text Extraction	Converts document into usable text
2️⃣	Chunking	Breaks large text into smaller parts
3️⃣	Embedding Generation	Converts text → vectors
4️⃣	FAISS Retrieval	Finds most relevant chunks
5️⃣	Context Pruning	Removes low-relevance content
6️⃣	Response Generation	Produces final answer

👉 Result: Significant reduction in unnecessary processing

##🖥️ Features

✅ Ask questions from textbooks
✅ Upload your own PDF files
✅ Preloaded NCERT books
✅ Context pruning for efficiency
✅ Fast semantic search using FAISS
✅ Chat history tracking
✅ File upload & delete system
✅ Real-time processing metrics

##📁 Project Structure
Trinova-AI-Tutor/
├── 📄 app.py              ← Main Streamlit app
├── 📦 requirements.txt    ← Dependencies
├── 📖 README.md
│
├── 📁 data/
│   ├── 📚 ncert/          ← Preloaded books
│   └── 📂 user_uploads/   ← User files

##🚀 Setup & Installation
###Prerequisites
Python 3.10+
pip installed
Step 1 — Clone Repo
git clone https://github.com/YOUR_USERNAME/Trinova-AI-Tutor.git
cd Trinova-AI-Tutor
Step 2 — Install Dependencies
pip install -r requirements.txt
Step 3 — Run App
streamlit run app.py

###🎮 How to Use
Select a book from available list OR upload your own PDF
Enter your question (e.g., “Explain coordinate compounds”)
System retrieves relevant content
Context pruning removes unnecessary parts
Answer is displayed with optimized information

###🏗️ Architecture
User → Streamlit UI → Backend Logic → PDF Processing  
     → Embeddings → FAISS → Retrieval → Context Pruning → Answer
📊 Optimization Insight

##Trinova focuses on efficient processing:

Reduced unnecessary text before answering
Faster response time
Lower computational cost
🌍 Real-World Use Case

##Designed for:

📚 Students using NCERT textbooks
🌐 Low-bandwidth environments
💸 Cost-sensitive AI deployments

👉 Works even with minimal resources

##🛠️ Tech Stack
Layer	Technology
Frontend	Streamlit
Backend	Python
AI/ML	Sentence Transformers
Retrieval	FAISS
Processing	PyMuPDF
Data	NumPy

##🔮 Future Improvements
Integration with advanced LLM APIs
Better UI (React-based frontend)
Multi-language support
Voice-based interaction
Faster indexing & caching

##🙏 Acknowledgements
Sentence Transformers
FAISS
NCERT resources
💬 Final Note

#TRINOVA — 
because learning should be fast, efficient, and accessible to everyone.
