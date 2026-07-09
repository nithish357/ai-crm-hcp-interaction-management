# ai-crm-hcp-interaction-management
An AI-powered CRM system for Healthcare Professional (HCP) interaction management built with React, FastAPI, PostgreSQL, LangGraph, and Groq LLM.
# 🤖 AI CRM – HCP Interaction Management System

An AI-powered Customer Relationship Management (CRM) system for Healthcare Professionals (HCPs). This application enables medical representatives to log doctor interactions, manage follow-ups, and retrieve interaction history using an AI assistant powered by Groq and LangGraph.

---

## 📌 Project Overview

AI CRM is designed to simplify the management of healthcare professional interactions. It combines a modern React frontend, FastAPI backend, PostgreSQL database, and AI-powered natural language querying to provide an intelligent CRM experience.

---

## ✨ Features

### 📋 HCP Interaction Management
- Log doctor interactions
- Store hospital information
- Record discussion details
- Manage follow-up schedules

### 📊 Dashboard
- Total Interactions
- Total Doctors
- Total Hospitals
- AI Query Statistics
- Analytics Dashboard

### 🤖 AI Assistant
- Ask questions in natural language
- Retrieve doctor interaction history
- AI-powered responses using Groq LLM
- LangGraph agent workflow

### 📈 Analytics
- Dashboard Statistics
- Visual Analytics Charts
- Real-time CRM Overview

---

# 🛠 Tech Stack

## Frontend
- React.js
- Vite
- Tailwind CSS
- Framer Motion
- Recharts
- Axios
- React Hot Toast
- Lucide React Icons

## Backend
- FastAPI
- Python
- SQLAlchemy
- Pydantic
- Uvicorn

## Database
- PostgreSQL

## AI Technologies
- Groq API
- LangChain
- LangGraph

---

# 📂 Project Structure

```
AI_CRM_PROJECT
│
├── backend
│   ├── app
│   │   ├── ai
│   │   ├── database
│   │   ├── models
│   │   ├── routers
│   │   ├── schemas
│   │   └── services
│   │
│   ├── main.py
│   └── .env
│
├── frontend
│   ├── src
│   │   ├── components
│   │   │   ├── chat
│   │   │   ├── dashboard
│   │   │   ├── interactions
│   │   │   ├── layout
│   │   │   └── ui
│   │   │
│   │   ├── pages
│   │   ├── redux
│   │   ├── services
│   │   └── styles
│   │
│   └── package.json
│
└── README.md
```

---

# ⚙️ Installation

## Clone Repository

```bash
git clone https://github.com/yourusername/AI_CRM_PROJECT.git
```

---

## Backend Setup

```bash
cd backend

python -m venv venv

venv\Scripts\activate

pip install -r requirements.txt

uvicorn main:app --reload
```

Backend runs on

```
http://127.0.0.1:8000
```

---

## Frontend Setup

```bash
cd frontend

npm install

npm run dev
```

Frontend runs on

```
http://localhost:5173
```

---

# 🔑 Environment Variables

Create a `.env` file inside the backend folder.

```env
DATABASE_URL=postgresql://username:password@localhost:5432/ai_crm

GROQ_API_KEY=your_groq_api_key
```

---

# 🚀 API Endpoints

## Health

```
GET /health
```

---

## Log Interaction

```
POST /interaction/log
```

---

## Get All Interactions

```
GET /interaction/all
```

---

## AI Chat

```
POST /ai/chat
```

---

## Dashboard Statistics

```
GET /dashboard/stats
```

---

# 📸 Application Screens

- Dashboard
- HCP Interaction Form
- Interaction History
- AI Assistant
- Analytics Dashboard

(Add screenshots after uploading to GitHub.)

---

# 🤖 AI Workflow

```
User Question
        │
        ▼
LangGraph Agent
        │
        ▼
Groq LLM
        │
        ▼
Database Search
        │
        ▼
AI Response
```

---

# 📊 Future Enhancements

- User Authentication
- Role-Based Access Control
- Appointment Scheduling
- Email Notifications
- Advanced AI Insights
- PDF Report Generation
- Cloud Deployment
- Multi-user Support

---

# 👨‍💻 Author

**Rodda Nithish Kumar**

B.Tech – Computer Science & Engineering

Python Full Stack Developer

---

# 📄 License

This project is developed for educational and learning purposes.

---

# ⭐ Acknowledgements

- FastAPI
- React
- PostgreSQL
- LangChain
- LangGraph
- Groq
- Tailwind CSS
- Recharts

---

## 📬 Contact

For queries or collaboration:

**Email:** :nithishkumarrodda@gmail.com

**LinkedIn:** :www.linkedin.com/in/rnkp

**GitHub:** https://github.com/nithish357

