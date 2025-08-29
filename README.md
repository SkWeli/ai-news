# AI News Aggregator

An **AI-powered news pipeline** that continuously fetches articles from global RSS feeds, filters for **Technology / AI / ML / Computer Science** topics, and ranks them by importance.  

The system uses embeddings, heuristics, and ranking signals (recency, authority, relevance) to display the **most important tech news on top**.

---

## ✨ Features

- 🔄 Fetches and cleans articles from multiple sources (RSS, APIs, crawlers).  
- 🌐 Language detection + (optional) translation pipeline.  
- 🤖 Filters to tech/AI/ML/CS topics using embeddings + keyword heuristics.  
- 📊 Ranks articles based on **recency, authority, relevance, and impact**.  
- 🗄️ Stores articles + embeddings in **PostgreSQL + pgvector**.  
- ⚡ Provides a **FastAPI backend** with `/top` endpoint for serving ranked news.  
- 📦 Dockerized infra (Postgres, Redis, Adminer for DB UI).  

Planned: semantic clustering, summarization, frontend UI (Next.js), and feeds (email/Telegram/Slack).

---

## 🛠️ Tech Stack

- **Backend:** Python 3.11, FastAPI, SQLAlchemy  
- **Data Processing:** feedparser, trafilatura, sentence-transformers, simhash  
- **Database:** PostgreSQL with pgvector extension  
- **Cache/Queue:** Redis  
- **Infrastructure:** Docker Compose (Postgres, Redis, Adminer)  
- **Frontend (planned):** Next.js + Tailwind  

---



