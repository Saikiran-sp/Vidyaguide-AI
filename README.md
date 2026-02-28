VidyaMitra – Intelligent Career Agent 🚀

VidyaMitra is a modern, AI-powered monolithic application designed to help job seekers optimize their career paths. It integrates an intelligent backend with a premium glassmorphic frontend to deliver resume analysis, skill gap detection, personalized career roadmaps, and adaptive AI-driven quizzes.

✨ Features

AI Resume Analyzer
Upload a PDF or paste resume text to receive an instant score, strength analysis, and keyword density insights.

Dynamic Skill Gap Analysis
Compare your current skill set with a target role to identify missing competencies.

AI Career Roadmap
Generate a 3–5 year career progression plan with timelines and recommended certifications.

Adaptive Training Quizzes
Create topic-specific quizzes (e.g., Python, React) with instant AI-generated feedback.

Skills Radar Chart
Visual comparison of your proficiency against market requirements.

Monolithic Architecture
Unified Python backend (FastAPI) serving a pre-built React frontend for streamlined deployment.

🛠️ Tech Stack

Backend: Python 3.10+, FastAPI

Frontend: React (Vite), Tailwind CSS, Framer Motion

Database: Supabase (PostgreSQL)

Charts: Recharts

Icons: Lucide React

AI: Google Gemini Pro 2.5

🚀 Getting Started
Prerequisites

Python installed

Node.js (required only for frontend modifications)

Installation

Clone the repository

Set up a virtual environment

python -m venv venv
.\venv\Scripts\activate
pip install -r requirements.txt
Configure Environment Variables

API keys are not committed to the repository for security reasons.

Duplicate .env.example and rename it to .env

Add your credentials:

# Database (Supabase)
SUPABASE_URL=your_supabase_url
SUPABASE_KEY=your_supabase_anon_key

# AI (Gemini)
GEMINI_API_KEY=your_gemini_api_key

# Training (Optional)
YOUTUBE_API_KEY=your_youtube_api_key

Note: AI features require a valid Gemini API key.

🏃 Running the Application

Run the entire application with a single command:

uvicorn app.main:app --reload

Access the app at: http://localhost:8000

Project Note:
VidyaMitra is implemented as a monolith. The React frontend located in src/ is pre-built into the dist/ directory and served automatically by the FastAPI backend. If frontend code is modified, run npm run build to reflect changes.
