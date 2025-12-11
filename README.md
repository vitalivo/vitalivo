# 👋 Hey, I'm Vitaliy — Python Backend Engineer

**I build battle-tested, scalable backend systems that stay up under real production load and grow with your business.**

🔥 **Core expertise**: Event-driven architecture · Real-time systems · Microservices · High-load APIs  
🌍 Remote / Worldwide  
📧 vitalivo@gmail.com  
💬 Telegram: [@vitalivo](https://t.me/vitalivo) (fastest response)

---

### 🚀 What I deliver in production (not just "familiar with")

| Your challenge                          | My production-grade solution                                      |
|-----------------------------------------|-------------------------------------------------------------------|
| Need horizontal scaling                 | Kafka + Redis Streams + event-driven design                       |
| Real-time dashboards / chat / tracking  | WebSockets (Channels / FastAPI) + Kafka consumers                 |
| Microservices that don't fall apart     | gRPC + Docker Compose + proper health checks & retries           |
| Database becoming a bottleneck          | PostgreSQL deep optimization (indexing, CTEs, partitioning, N+1 fixes) |
| Background jobs & queues                | Celery Beat + Redis + Kafka producers/cons; dead-letter handling |

### 🛠 Battle-tested tech stack

**Backend**  
`FastAPI` `Django / DRF / Django-Ninja` `asyncio` `gRPC` `Celery`

**Real-time & Messaging**  
`Apache Kafka` `Redis Streams` `WebSockets` `Django Channels`

**Databases**  
`PostgreSQL` `SQLAlchemy 2.0` `Redis`

**DevOps & Infra**  
`Docker` `Docker Compose` `GitHub Actions CI/CD` `Linux`

**Frontend (when needed fast)**  
`React` `Next.js` `TypeScript`

---

🔥 Featured Production-Ready Projects (Docker + tests included)

1. 🤖 **AI-Powered Video Analytics Telegram Bot** (LLM-to-SQL)

Analyzed complex natural language queries (Russian NL-to-SQL) for video performance metrics against a PostgreSQL database. **Solved critical data-typing issues, forced complex JOINs, and managed date-time conversions** via targeted system prompts.
* **Key Achievement:** Created a robust, production-grade SYSTEM_PROMPT to ensure **100% test coverage** across all edge cases (unique dates, aggregated growth, final statistics, and complex ID matching).
* Stack: **FastAPI** • **PostgreSQL** • **AsyncPG** • **LLM Integration (Groq/OpenAI)** • **aiogram** • **Docker Compose**
* ➜ github.com/vitalivo/video_analytics_bot

2. Mini-CRM – Smart Weighted Lead Distribution Engine (2025)

Mathematically correct weighted routing with strict concurrent limits per operator
** How to see it in action: `./test_clean.sh` → 50 leads distributed perfectly in ~15 sec
Stack: FastAPI • SQLAlchemy 2.0 • Docker • Weighted Random
➜ github.com/vitalivo/mini-crm

3. Custom JWT + Full RBAC Auth System from Scratch (48 hours)

Zero third-party auth packages. Not a single line of `simplejwt` or `django.contrib.auth`
Custom User + bcrypt
Access + refresh tokens (PyJWT)
Granular permissions system (14 permissions, own/all scope)
`@require_permission` decorator with correct 401/403
Admin panel, soft delete, refresh endpoint
Beat DRF bug that silently reset `request.user`
➜ github.com/vitalivo/myauth_project

4. Production-Ready Blog API

Clean architecture, 100% test coverage, structured logging, monitoring-ready
Stack: Django Ninja • PostgreSQL • Docker Compose • Unit Tests
➜ github.com/vitalivo/blog-backend

5. RentFlow — gRPC + Kafka Microservices

Cross-service communication & data sync between Django and FastAPI services via events
➜ github.com/vitalivo/rentfow

6. FleetTrack — Real-Time Vehicle Tracking

Kafka → live WebSocket dashboards, multi-service setup
➜ github.com/vitalivo/fleettrack

7. Task Manager with Telegram Bot

Instant sync via WebSockets + scheduled Telegram notifications
➜ github.com/vitalivo/task_manager_telegram

8. Course Builder — Fullstack Test Task (Dec 2025)

Live demo: https://frontend-v2v7h4ezo-vitalivo-gmailcoms-projects.vercel.app
Demo login: `demo@demo.com` / `demo123` Full-featured web app for building personal courses from video lessons.
Features: JWT authentication, Lesson catalog, Course builder, Responsive UI.
Backend: FastAPI + SQLModel + PostgreSQL
Tech stack: Next.js 14, TypeScript, Tailwind, Zustand, FastAPI, PostgreSQL, Docker
Private repo — available upon request One-command start: `docker-compose up --build`

---
### 🏆 LeetCode Journey
[![LeetCode](https://img.shields.io/badge/LeetCode-vitalivo-EFF01D?logo=leetcode&logoColor=black&style=for-the-badge)](https://leetcode.com/u/vitalivo/)

> Just getting started • Deepening my DSA fundamentals for even more efficient production code  
> Algorithms aren't just theory—they're the key to writing scalable, optimized backends that handle real-world loads without breaking a sweat.

---

### 💼 What you get when working with me

- Systems that scale horizontally without rewriting  
- Clean, typed, fully tested code  
- Docker-first: `docker-compose up --build` and everything just works  
- Full CI/CD pipelines out of the box  
- DB optimizations that save thousands on infrastructure  
- LLM/AI-ready endpoints (already implementing in current contracts)

### 📬 Currently open to

- Remote Senior/Middle+ Backend roles  
- Contract & freelance projects (2 weeks+)  
- Interesting open-source collaboration (AI/automation tools)

**Contact me** → vitalivo@gmail.com or Telegram [@vitalivo](https://t.me/vitalivo)

> **“I don’t just ship APIs — I build reliable systems that handle real production traffic and scale with your business.”**

⭐ Star this profile if you're tired of junior-level code in production ;)

