# 🎯 Micro-Budget Advisor

AI-powered budgeting assistant that helps users quickly generate personalized mini-budget plans and savings suggestions based on simple inputs.

## 🚀 Features

- Simple income & expense input
- AI-powered budget allocation
- Personalized savings suggestions
- Visual budget breakdowns
- Anonymous mode with local storage
- Optional cloud sync

## 🛠️ Tech Stack

- Frontend: Next.js + Tailwind CSS
- Backend: FastAPI
- Database: Supabase (PostgreSQL)
- AI: LangChain with OpenAI/Ollama
- Hosting: Vercel (frontend) & Fly.io (backend)

## 🏗️ Project Structure

```
├── frontend/          # Next.js frontend application
├── backend/           # FastAPI backend service
├── docs/              # Documentation
└── scripts/           # Development and deployment scripts
```

## 📦 Getting Started

1. Clone the repository
2. Set up the frontend:
   ```bash
   cd frontend
   npm install
   npm run dev
   ```
3. Set up the backend:
   ```bash
   cd backend
   python -m venv venv
   source venv/bin/activate  # or `venv\Scripts\activate` on Windows
   pip install -r requirements.txt
   uvicorn app.main:app --reload
   ```

## 📄 License

MIT