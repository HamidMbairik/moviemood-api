# 🎬 MovieMood API

Backend for **MovieMood**, a SaaS that gives personalized movie recommendations based on mood.

## 🚀 Tech Stack
- [FastAPI](https://fastapi.tiangolo.com/) — Python web framework
- [Postgres](https://www.postgresql.org/) — relational database
- [Supabase](https://supabase.com/) — authentication & DB hosting (planned)
- [TMDb API](https://www.themoviedb.org/documentation/api) — movie metadata source

## 📦 Features (MVP)
- `GET /health` — health check
- `GET /v1/recommendations?mood=happy` — mock movie recs by mood
- User accounts & plan management
- API key system with rate limits
- Payments integration (Lemon Squeezy / Paddle)

## 🔧 Development Setup
Clone the repo and create a virtual environment:
```bash
git clone https://github.com/YOUR_USERNAME/moviemood-api.git
cd moviemood-api
python -m venv venv
source venv/bin/activate   # On Windows: venv\Scripts\activate
pip install -r requirements.txt
