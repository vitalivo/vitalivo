# 👋 Hey, I'm Vitaliy — Python Backend Engineer

**I build battle-tested, scalable backend systems that stay up under real production load and grow with your business.**

🔥 **Core expertise:** Event-driven architecture · Real-time systems · Microservices · High-load APIs  
🌍 Remote / Worldwide  
📧 vitalivo@gmail.com  
💬 Telegram: [@vitalivo](https://t.me/vitalivo) (fast response)

---

## 🚀 What I deliver in production (not just “familiar with”)

| Your challenge | My production-grade solution |
|---|---|
| Need horizontal scaling | Kafka / Redis Streams + event-driven design |
| Real-time dashboards / chat / tracking | WebSockets (Channels / FastAPI) + consumers |
| Microservices that don’t fall apart | gRPC + Docker Compose + health checks + retries/backoff |
| Database becoming a bottleneck | PostgreSQL optimization (indexes, EXPLAIN, CTEs, partitioning, N+1 fixes) |
| Background jobs & queues | Celery / Streams / Kafka pipelines, idempotency, dedup, DLQ patterns |

---

## 🛠 Battle-tested tech stack

**Backend**  
`FastAPI` `Django / DRF / Django-Ninja` `asyncio` `gRPC` `Celery`

**Real-time & Messaging**  
`Apache Kafka` `Redis Streams` `WebSockets` `Django Channels`

**Databases**  
`PostgreSQL` `SQLAlchemy 2.0` `Redis`

**DevOps & Infra**  
`Docker` `Docker Compose` `Linux` `CI/CD (GitHub Actions)`

**Frontend (when needed fast)**  
`React` `Next.js` `TypeScript`

---

## 🔥 Featured Production-Ready Projects (Docker + tests)

### 1) 🧠 Listings Monitoring → Telegram (Avito-style) — event-driven, scalable, 24/7-ready
Subscription-based monitoring: users add a category/city/search link and receive new listings in Telegram with low end-to-end latency.
- Fair per-user rate limiting (1–10 RPS tiers)
- Redis Streams queues (consumer groups, XAUTOCLAIM) → at-least-once delivery
- PostgreSQL dedup → no duplicate notifications after restarts/retries
- Admin panel + internal stats/metrics + Prometheus endpoint
➜ https://github.com/vitalivo/Parser

### 2) 🤖 AI-Powered Video Analytics Telegram Bot (LLM-to-SQL)
Natural language → SQL analytics for video performance metrics in PostgreSQL.
- Robust prompt strategy focused on correctness and edge cases
- Docker-first delivery + tests
Stack: **FastAPI** • **PostgreSQL** • **AsyncPG** • **LLM (Groq/OpenAI)** • **aiogram** • **Docker Compose**  
➜ https://github.com/vitalivo/video_analytics_bot

### 3) Mini-CRM — Smart Weighted Lead Distribution Engine (2025)
Mathematically correct weighted routing with strict concurrent limits per operator.  
How to see it in action: `./test_clean.sh` → 50 leads distributed in ~15 sec.  
Stack: FastAPI • SQLAlchemy 2.0 • Docker  
➜ https://github.com/vitalivo/mini-crm

### 4) Custom JWT + Full RBAC Auth System (48 hours)
Zero third-party auth packages. Custom user, access/refresh tokens, granular permissions, admin tooling.  
➜ https://github.com/vitalivo/myauth_project

### 5) Production-Ready Blog API
Clean architecture, structured logging, monitoring-ready, high test coverage.  
Stack: Django Ninja • PostgreSQL • Docker Compose • Unit Tests  
➜ https://github.com/vitalivo/blog-backend

### 6) RentFlow — gRPC + Kafka Microservices
Cross-service communication & data sync between Django and FastAPI services via events.  
➜ https://github.com/vitalivo/rentfow

### 7) FleetTrack — Real-Time Vehicle Tracking
Kafka → live WebSocket dashboards, multi-service setup.  
➜ https://github.com/vitalivo/fleettrack

### 8) Task Manager with Telegram Bot
Instant sync via WebSockets + scheduled Telegram notifications.  
➜ https://github.com/vitalivo/task_manager_telegram

### 9) Course Builder — Fullstack Test Task (Dec 2025)
Live demo: https://frontend-v2v7h4ezo-vitalivo-gmailcoms-projects.vercel.app  
Demo login: `demo@demo.com` / `demo123`  
Backend: FastAPI + SQLModel + PostgreSQL  
Tech: Next.js 14, TypeScript, Tailwind, Zustand, Docker  
➜ https://github.com/vitalivo/Test-task

---

## 🏆 LeetCode Journey
[![LeetCode](https://img.shields.io/badge/LeetCode-vitalivo-EFF01D?logo=leetcode&logoColor=black&style=for-the-badge)](https://leetcode.com/u/vitalivo/)

---

## 💼 What you get when working with me
- Systems that scale horizontally without rewriting
- Clean, tested code, Docker-first delivery
- Production mindset: metrics, retries/backoff, idempotency, failure modes

## 📬 Currently open to
- Remote Middle+/Senior Backend roles
- Contract & long-term maintenance (2 weeks+)
- Interesting open-source collaboration

**Contact me** → vitalivo@gmail.com or Telegram [@vitalivo](https://t.me/vitalivo)

> **“I don’t just ship APIs — I build reliable systems that handle real production traffic and scale with your business.”**
