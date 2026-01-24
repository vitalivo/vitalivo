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
| Need horizontal scaling | Kafka / Redis Streams + event-driven architecture |
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

**What makes it production-ready**
- Fair per-user rate limiting (1–10 RPS tiers), scalable to 150+ users
- Redis Streams queues (consumer groups, XAUTOCLAIM) → at-least-once delivery
- PostgreSQL dedup → no duplicate notifications after restarts/retries
- Subscription visibility: last check/success/error, consecutive errors, pause status
- Internal stats/metrics endpoints + Prometheus text format metrics
- Docker Compose: backend + scheduler + workers + bot + Postgres + Redis

➜ https://github.com/vitalivo/Parser

---

### 2) 🤖 AI-Powered Video Analytics Telegram Bot (LLM-to-SQL)
Natural language → SQL analytics for video performance metrics in PostgreSQL, wrapped in a Telegram bot.

**Highlights**
- Reliable NL-to-SQL pipeline focused on correctness for analytics queries
- Handles tricky cases: date ranges, aggregation, joins, type conversions
- Docker-first delivery + testable architecture

**Stack**  
FastAPI • PostgreSQL • AsyncPG • LLM (Groq/OpenAI) • aiogram • Docker Compose

➜ https://github.com/vitalivo/video_analytics_bot

---

### 3) Mini-CRM — Smart Weighted Lead Distribution Engine (2025)
Mathematically correct weighted routing with strict concurrent limits per operator.

**Highlights**
- Correct weighted distribution under concurrency constraints
- Fast verification script: `./test_clean.sh` (demo-friendly)
- Clean service design with predictable behavior

**Stack**  
FastAPI • SQLAlchemy 2.0 • Docker

➜ https://github.com/vitalivo/mini-crm

---

### 4) Custom JWT + Full RBAC Auth System (48 hours)
Auth system built from scratch: custom user model, tokens, permissions, admin tooling.

**Highlights**
- Access + refresh tokens, secure hashing, correct 401/403 behavior
- Granular permissions (own/all scopes), decorator-based enforcement
- Admin integration, soft delete, refresh endpoint

**Stack**  
Django / DRF • PyJWT • PostgreSQL • Docker

➜ https://github.com/vitalivo/myauth_project

---

### 5) Production-Ready Blog API
Clean architecture API with high test coverage and monitoring-ready structure.

**Highlights**
- Clean separation of concerns, predictable endpoints
- Test-first mindset, structured logging patterns
- Docker Compose for one-command run

**Stack**  
Django Ninja • PostgreSQL • Docker Compose • Unit Tests

➜ https://github.com/vitalivo/blog-backend

---

### 6) 🏠 RentFlow — Microservices Rental Management Platform
Modern rental management platform built around microservices and asynchronous event-driven communication.

**Highlights**
- Django as API gateway + ORM (core business logic + admin workflows)
- FastAPI services for high-load domains (tracking, tenants, payments)
- Kafka for async service-to-service communication (event-driven sync)
- Payments service: idempotent writes, stats endpoints, Prometheus-ready metrics
- Kafka UI for local debugging and topic inspection
- Docker Compose setup for reproducible local environment

**Services (local)**
- `django-web` — API gateway, business logic, ORM — `http://localhost:8000`
- `django-consumer` — Kafka consumer for rental domain events
- `fastapi-tracking` — tracking/events — `http://localhost:8011`
- `fastapi-tenants` — tenants domain — `http://localhost:8021`
- `fastapi-payments` — payments domain — `http://localhost:8023`
- `kafka-ui` — Kafka monitoring — `http://localhost:8080`
- `react-frontend` — UI — `http://localhost:3000`

**Stack**  
Django • FastAPI • Kafka • PostgreSQL • Redis • React • Docker Compose

➜ https://github.com/vitalivo/rentfow

---

### 7) 🚗 FleetTrack — Real-Time Fleet Management System
Fullstack real-time platform to manage vehicles and drivers with live updates across the system.

**Highlights**
- Drivers & vehicles management with admin workflows
- JWT authentication + role-oriented access control
- Real-time updates: Kafka events → WebSocket dashboards (instant UI refresh)
- Microservice-ready layout: Django/DRF + FastAPI services
- Docker Compose: reproducible environment for local and demo runs

**Stack**  
Backend: Django • DRF • FastAPI • PostgreSQL • Redis • Kafka • WebSockets  
Frontend: React • Vite • TypeScript • Tailwind  
Infra: Docker • Docker Compose

**Run**
```bash
docker compose up --build
