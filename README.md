# ⚡ Node.js REST API Starter

Production-ready **Node.js REST API boilerplate** — Express.js, TypeScript, JWT auth, Prisma ORM, rate limiting, Docker.

> Built by [Viprasol Tech](https://viprasol.com) — custom web development and SaaS solutions.

---

## Features

- ⚡ **Express.js + TypeScript** — typed, production-grade
- 🔐 **JWT Auth** — access + refresh tokens, bcrypt passwords
- 🗄️ **Prisma ORM** — type-safe queries (PostgreSQL/MySQL/SQLite)
- 🚦 **Rate limiting** — per-user and global
- ✅ **Zod validation** — on all endpoints
- 📝 **Logging** — Morgan + Winston
- 🐳 **Docker** — Dockerfile + docker-compose
- 📖 **Swagger docs** — auto-generated

---

## Endpoints

```
POST   /api/auth/register
POST   /api/auth/login
POST   /api/auth/refresh
DELETE /api/auth/logout
GET    /api/users/me
PATCH  /api/users/me
GET    /api/health
```

---

## Quick Start

```bash
git clone https://github.com/Viprasol/nodejs-api-starter
npm install && cp .env.example .env
npx prisma migrate dev
npm run dev
```

---

## Need a Custom API or Web App?

Built by [Viprasol Tech](https://viprasol.com).

We build: REST + GraphQL APIs, real-time apps, full-stack Next.js + Node.js, SaaS backends.

👉 **[Hire a Node.js Developer →](https://viprasol.com/services/web-development)**

---

MIT License
