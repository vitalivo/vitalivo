# 👋 Hi, I'm Vitaliy

**Python Backend Engineer** specializing in scalable microservices and real-time systems

📍 Remote / Worldwide  
📧 vitalivo@gmail.com  
💬 Telegram: [@vitalivo](https://t.me/vitalivo)  
🌐 [Portfolio & Live Demos](https://vitaly-portfolio-full-st-git-2d0910-vitalivo-gmailcoms-projects.vercel.app/en)

---

## 🚀 What I Do

I design and build **production-ready backend systems** that scale. My focus is on:

- **Event-driven architectures** with Kafka and Redis
- **Real-time APIs** using WebSockets and async frameworks
- **Microservices orchestration** with Docker and gRPC
- **High-performance databases** (PostgreSQL optimization, indexing, query tuning)

---

## 🛠️ Tech Stack

**Backend & Async**  
`FastAPI` `Django/DRF` `asyncio` `Celery` `Django Channels`

**Streaming & Messaging**  
`Apache Kafka` `Redis Streams` `gRPC` `WebSockets`

**Databases**  
`PostgreSQL` `SQLite` `Redis`

**DevOps & Infrastructure**  
`Docker` `Docker Compose` `CI/CD` `GitHub Actions`

**Frontend (Basic)**  
`React` `Next.js` `TypeScript`

---

## 🧱 Featured Projects

💻 Blog Backend API — Production-Ready Blog API (New)
Stack: Django Ninja · PostgreSQL · Docker Compose · Unit Tests

A fully tested, containerized backend API for a blog, showcasing clean architecture and production readiness standards.

Key Features:

🔹 Clean API Design: Built using Django Ninja for fast, standards-compliant API development.

🔹 Token Authentication: Implemented custom Bearer Token authentication and fine-grained permissions (author-only CRUD).

🔹 Code Reliability: Ensured quality through comprehensive Unit Testing for all critical endpoints.

🔹 Monitoring Ready: Implemented structured logging (INFO/WARNING/ERROR) for easy monitoring.

View Repository → https://github.com/vitalivo/blog-backend.git

---

### Custom JWT + RBAC Authentication from Scratch (No simplejwt, No contrib.auth)  
**Stack:** Django 5.2 · PyJWT · bcrypt · PostgreSQL · Docker  

A complete custom authentication & authorization system built entirely from scratch in 48 hours — **zero third-party auth packages**.

**Implemented from the ground up:**
- Custom `User` model with bcrypt password hashing
- JWT access + refresh tokens (PyJWT) — no `djangorestframework-simplejwt`
- Custom middleware → `request.user`, `request.is_staff`, `request.user_roles`
- Full-featured RBAC: Roles → Business Elements → 14 granular permissions (own/all)
- `@require_permission` decorator with proper 401/403 responses
- Admin panel for managing roles and permissions
- Soft delete, token refresh endpoint
- **Zero usage of `django.contrib.auth` or any built-in auth backend**

**Key challenge & victory:**  
DRF’s `@api_view` was silently resetting `request.user` → defeated by switching protected views to pure Django views while keeping DRF only for serializers.

This is not a test task. This is a **production-ready**, battle-tested authentication core you can drop into any serious project.

Repository → (https://github.com/vitalivo/myauth_project.git)  

---

Mini-CRM – Smart Lead Distribution Engine (2025)  
Stack: FastAPI · SQLAlchemy 2.0 · Docker Compose · Weighted Random Routing  
Production-ready mini-CRM with intelligent lead routing based on operator weights and real-time workload limits.

Key Features:
- Mathematically correct weighted distribution using `random.choices`
- Strict enforcement of concurrent active contact limits per operator
- Graceful degradation: contacts are saved even when all operators are overloaded
- Clean layered architecture, full typing, validation, Docker-first approach
- One-command full stress test: `./test_clean.sh` → 50 contacts → perfect distribution in ~15 seconds

Test result:
Anna:     10 / 10 (limit)
Maxim:    20 / 20 (limit)
No operator: 20
Total:    50


View Repository → https://github.com/vitalivo/mini-crm.git

Run: `docker-compose up --build` · Demo: `./test_clean.sh`

Not a test task. A battle-tested, production-ready lead distribution core you can drop into any CRM or support system.

---

🏘️ RentFlow — gRPC Microservices for Lease Management
Stack: Django/DRF · FastAPI · gRPC · Kafka · PostgreSQL · Docker Compose

Event-driven microservice system for property lease management with cross-service communication.

Key Features:

✅ gRPC communication between Django and FastAPI services

✅ Data synchronization with metadata tracking across services

✅ Event-driven design using Kafka for lease lifecycle events

✅ Docker orchestration for local and production deployment

View Repository → https://github.com/vitalivo/rentfow.git

---

🚗 FleetTrack — Real-Time Fleet Management
Stack: FastAPI · Kafka · Django · React · Docker Compose

Distributed microservices system for real-time vehicle tracking.

Key Features:

🔹 Kafka-based event streaming for fleet updates

🔹 WebSocket live dashboards

🔹 Multi-service architecture with Docker

View Repository → https://github.com/vitalivo/fleettrack.git

---

✅ Task Manager — Real-Time Tasks + Telegram Bot
Stack: Django · DRF · Channels · Celery · Redis · Aiogram · Docker

Full-stack task management with instant synchronization and Telegram notifications.

Key Features:

🔹 Real-time updates via WebSockets (Django Channels)

🔹 Scheduled notifications with Celery Beat

🔹 Telegram bot integration for task alerts

View Repository → https://github.com/vitalivo/task_manager_telegram.git

---

## 💼 What I Deliver

✔️ **Scalable microservice architectures** ready for production  
✔️ **Real-time systems** with WebSockets and event streaming  
✔️ **PostgreSQL optimization** (N+1 resolution, indexing, CTE queries)  
✔️ **Async workflows** with Celery, Kafka, and Redis  
✔️ **Full CI/CD pipelines** with Docker and GitHub Actions  
✔️ **API integrations** including AI/LLM-ready endpoints (coming soon)

---

## 📬 Let's Connect

I'm open to:

- 🤝 Freelance & contract projects
- 💼 Remote backend engineering positions
- 🌱 Open-source collaboration on AI/automation tools

**Reach out:**  
📧 vitalivo@gmail.com  
💬 [@vitalivo on Telegram](https://t.me/vitalivo)

---

⭐️ *"I don't just build APIs — I build reliable systems that scale."*

