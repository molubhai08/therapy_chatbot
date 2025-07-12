# therapy_chatbot

# 🕉️ Gita Counselor – Therapy Chatbot

A calm, caring therapy chatbot inspired by the **Bhagavad Gita**, built using **Flask**, **LangChain**, **Groq**, and **Pinecone**.  
It gently reflects emotions, offers simple spiritual insights, and helps users process complex thoughts through thoughtful sub-question decomposition.

---

## 🌟 Features

- 🧘 Therapist-like chatbot persona
- 📿 Wisdom based on the Bhagavad Gita
- 🔍 Breaks down complex emotional questions into sub-questions
- 🧠 Uses Groq + LangChain to generate responses
- 🔎 Pinecone-powered vector search for knowledge retrieval
- 💬 Beautiful animated chat interface with spiritual effects

---

## 🛠️ Tech Stack

- **Frontend:** HTML + Tailwind CSS + JavaScript (chat UI)
- **Backend:** Flask (Python)
- **LLM:** Groq API (`llama3-70b-8192`)
- **RAG System:** LangChain + Pinecone
- **Session Handling:** Flask `session`

---

## 📂 Project Structure

therapy_bot/
│
├── app.py # Main Flask application
├── chat.html # Frontend chat interface
├── templates/
│ └── index.html # (Optional landing page)
├── static/ # (Optional static files)
├── requirements.txt # Python dependencies
└── README.md # Project documentation
