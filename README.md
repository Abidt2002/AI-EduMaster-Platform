# 🎓 AI EduMaster Platform

An **AI-Powered Educational Platform** that transforms the learning experience using Generative AI and LLMs.

---

## 🚀 Features

### 🧑‍🏫 **Teacher Dashboard**
- Upload study materials (PDFs, slides, notes)
- Automatically extract content and generate summaries
- Create AI-generated quizzes and questions

### 👨‍🎓 **Student Portal**
- Ask questions directly from uploaded materials
- Get AI-powered explanations and summaries
- Practice with generated quizzes and get instant feedback

### 🧑‍💼 **Admin Dashboard**
- Manage teachers, students, and materials
- View usage statistics and system analytics
- Secure role-based authentication

---

## 🧠 Tech Stack
- **Python 3.10+**
- **Streamlit** (UI)
- **SentenceTransformers / FAISS** (for embeddings & retrieval)
- **PyPDF2** (PDF parsing)
- **SQLite** (user database)
- **LangChain** (for LLM logic)
- **Hugging Face Transformers** (free LLM)
- **Ngrok or LocalTunnel** (for Colab deployment)

---

## 🧩 Folder Structure
/AI-EduMaster-Platform/
│
├── requirements.txt # Python dependencies
├── data/ # Uploaded teacher materials
├── quizzes/ # Generated quizzes
└── db/ # User & analytics database

💡 Usage Flow

**Teacher uploads PDF files
**AI automatically extracts text and generates embeddings
**Student can ask any question like “Summarize chapter 1”
**AI retrieves relevant context and generates answers
**Teacher clicks “Generate Quiz” to produce 5–10 questions
**Admin reviews analytics and manages user access

🛡️ Authentication
**Secure login for Teacher, Student, and Admin roles using streamlit-authenticator.
**Passwords stored securely (hashed).

🤖 AI Backend

**Uses Hugging Face Transformers for text generation
**Uses Sentence Transformers for embeddings
**Integrates with LangChain for retrieval-based QA

🏁 License
This project is open-source under the MIT License.
