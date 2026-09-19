# Hi, I'm Mridul Jain 👋

### Software Engineer II | Backend Engineer | Python, FastAPI & Data/AI Pipelines

I am a backend-focused software engineer with **3+ years of full-time experience** building APIs, scalable services, document-processing systems, and data pipelines. I currently work at **Gramener** and previously worked at **Alphastream.ai**.

🌍 Open to international remote roles · 🤝 Available for freelance backend projects

## Engineering Impact

- Reduced API latency by **30%** through backend and query optimizations
- Improved document-parsing throughput by **2×**
- Built pipelines that extract **1,000+ datapoints** from PDFs containing up to **500 pages**
- Improved model F1 score by **8–9%** and reduced false positives by **90%**
- Accelerated validation workflows by **40%** while achieving **90%+ field accuracy**

## Core Technologies

| Area | Technologies |
|---|---|
| Backend | Python, FastAPI, Tornado, REST APIs |
| Databases & Caching | PostgreSQL, SQL, Redis |
| Async & Distributed Work | Celery, background jobs, idempotent APIs |
| Data & AI | PySpark, Pandas, NumPy, PyMuPDF, LLM pipelines |
| Cloud & DevOps | AWS Lambda, S3, Textract, Docker, Jenkins, GitHub Actions |
| Engineering | Distributed Systems, Git, Linux, API Performance |

## Featured Projects

### [TaskForge API](https://github.com/MridulJain0771/taskforge-api) ⭐ Flagship Backend Project

[![TaskForge CI](https://github.com/MridulJain0771/taskforge-api/actions/workflows/ci.yml/badge.svg?branch=master)](https://github.com/MridulJain0771/taskforge-api/actions/workflows/ci.yml)

Production-style backend service built around the concerns that matter beyond CRUD: authentication, persistence, caching, rate limiting, retries, background processing, idempotency, migrations, observability, container security and automated CI.

**Engineering highlights:**
- FastAPI + async SQLAlchemy + PostgreSQL
- Redis-backed rate limiting and Celery infrastructure
- JWT authentication and scrypt password hashing
- Idempotent task creation with `Idempotency-Key`
- Request IDs, structured JSON logging, liveness/readiness probes
- Docker image running as a non-root user
- CI validates dependencies, syntax, Ruff, migrations, unit tests, integration tests, API startup and Docker runtime

**Tech:** Python, FastAPI, PostgreSQL, Redis, SQLAlchemy, Alembic, Celery, JWT, Docker, GitHub Actions

### [DocFlow](https://github.com/MridulJain0771/docflow) — Distributed Document Processing

[![DocFlow CI](https://github.com/MridulJain0771/docflow/actions/workflows/ci.yml/badge.svg?branch=main)](https://github.com/MridulJain0771/docflow/actions/workflows/ci.yml)

Distributed PDF-processing backend designed around asynchronous work and queue reliability. Uploads return immediately with a durable job ID while Celery workers process documents in the background and expose progress, retries and final results through the API.

**Engineering highlights:**
- FastAPI upload and job-status APIs with HTTP `202 Accepted`
- PostgreSQL-backed durable job state and progress tracking
- Redis + Celery worker pipeline with retry semantics
- SHA-256 duplicate detection with database uniqueness protection
- PDF text extraction with page and character metrics
- Completed-result download endpoint
- Liveness/readiness probes and Docker Compose stack
- CI validates dependencies, Ruff, migrations, unit/integration tests and Docker build security

**Tech:** Python, FastAPI, PostgreSQL, Redis, SQLAlchemy, Alembic, Celery, PyMuPDF, Docker, GitHub Actions

### [VidyaSutra](https://github.com/MridulJain0771/VidyaSutra) — Full-Stack Multi-Tenant School / College Management Platform

VidyaSutra is a full-stack school and college administration platform with organization-scoped security and role-aware workflows for administrators, staff/teachers, students and parents. It combines a Django REST backend with a React + TypeScript frontend and MongoDB persistence.

**Engineering highlights:**
- JWT authentication with rotating/revocable refresh tokens, active-account revalidation and Django PBKDF2 password hashing
- Organization-scoped permission-based RBAC with custom roles and tenant-isolated MongoDB repository queries
- Student, staff and parent enrollment, parent-child relationships, user management and class/section assignment
- Academic years, classes, sections, flexible student groups, subjects, subject offerings and staff responsibilities
- Conflict-aware timetable scheduling with teacher, room and student-audience collision checks plus room-capacity validation
- Attendance and leave workflows with teacher rosters, policies, approvals, history and attendance-percentage calculation
- Exam scheduling with room/staff/student conflict detection and automatic cancellation of overlapping class periods
- Announcements plus role-specific dashboards for students, parents and teaching staff
- React frontend with protected/permission-aware routing, TanStack Query, React Hook Form, Zod and reusable UI components
- Layered backend architecture using DRF views/serializers → services → MongoDB repositories with audit logging and automated API tests

**Tech:** Python, Django, Django REST Framework, MongoDB, PyMongo, JWT, React 19, TypeScript, Vite, TanStack Query, React Router, React Hook Form, Zod, Tailwind CSS

### [Voice2Story](https://github.com/MridulJain0771/voice2story)

Python desktop application that converts voice, typed prompts, and document context into AI-assisted conversations, articles, visual storyboards, and narrated videos.

**Tech:** Python, Gemini API, SpeechRecognition, Tkinter, MoviePy, gTTS

### [Employment Experience Analysis](https://github.com/MridulJain0771/Spottable)

Data-processing workflow that normalizes nested employment history, handles incomplete and overlapping records, and calculates professional experience and career gaps.

**Tech:** Python, pandas, NumPy, Jupyter Notebook

### [Joy Hub](https://github.com/MridulJain0771/Joy-Hub)

Python desktop suite combining a music player, Tetris, Pong, and webcam/video utilities in a graphical interface.

**Tech:** Python, Tkinter, Pygame, Pillow

## What I Can Help Build

- Backend services and REST APIs
- FastAPI and Python applications
- PostgreSQL data models and Redis caching
- Background processing and queue-based workflows
- API performance and scalability improvements
- Document extraction and AI-assisted processing pipelines
- Data automation and integration workflows

## Let's Connect

- **LinkedIn:** [linkedin.com/in/mriduljain07](https://www.linkedin.com/in/mriduljain07/)

I am open to **Backend Engineer, Software Engineer II, and SDE II opportunities**, especially with international remote teams. I am also available for selected freelance backend and automation projects.
