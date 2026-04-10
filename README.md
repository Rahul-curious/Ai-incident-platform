# 🤖 AI Ops: Incident Prediction & Automation Platform

An enterprise-grade AI-powered platform that predicts, detects, 
and automates responses to system incidents in real time.

> Built with a production-ready full-stack architecture including 
> CI/CD, containerization, JWT auth, and E2E testing.

---

## 🚀 Live Demo
[Add your live link here]

## 📸 Screenshots
[Add screenshots from your /screenshots folder]

---

## 🛠️ Tech Stack

### Backend
- **FastAPI** — High-performance Python REST API
- **PostgreSQL** — Production SQL database
- **SQLModel** — ORM for database interactions
- **Pydantic** — Data validation & settings management
- **JWT Authentication** — Secure token-based auth
- **Pytest** — Unit & integration testing

### Frontend
- **React** + **TypeScript** — Modern UI
- **Vite** — Lightning-fast build tool
- **Tailwind CSS** + **shadcn/ui** — Beautiful components
- **Playwright** — End-to-End testing
- Dark mode support 🌙

### DevOps & Infrastructure
- **Docker Compose** — Dev & production containerization
- **GitHub Actions** — CI/CD pipeline
- **Traefik** — Reverse proxy & load balancer
- **Mailcatcher** — Local email testing

---

## ✨ Key Features

- 🔍 AI-powered incident prediction & detection
- ⚡ Automated incident response workflows
- 📊 Real-time analytics dashboard
- 🔐 Secure JWT authentication system
- 📧 Email-based password recovery
- 🧪 Full test coverage (unit + E2E)
- 🐋 One-command Docker deployment
- 🔄 CI/CD with GitHub Actions

---

## 🏃 Getting Started

### Prerequisites
- Docker & Docker Compose installed
- Python 3.10+
- Node.js 18+

### Run Locally
```bash
# Clone the repo
git clone https://github.com/Rahul-curious/Ai-incident-platform.git
cd Ai-incident-platform

# Copy environment file
cp .env.example .env

# Start all services
docker compose up -d
```

Visit: `http://localhost:5173`
API Docs: `http://localhost:8000/docs`

---

## 🧪 Running Tests

```bash
# Backend tests
pytest

# E2E tests
playwright test
```

---

## 📁 Project Structure
---

## 🔐 Environment Variables

| Variable | Description |
|---|---|
| SECRET_KEY | JWT secret key |
| POSTGRES_PASSWORD | Database password |
| FIRST_SUPERUSER | Admin email |

---

## 👨‍💻 Author
**Rahul** — [github.com/Rahul-curious](https://github.com/Rahul-curious)

---

## 📄 License
MIT License
