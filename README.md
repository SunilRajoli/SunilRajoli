<!-- Profile Header -->
<h1 align="center">👋 Hi, I'm Sunil</h1>
<p align="center">
  <b>Backend Developer</b> — Node.js • TypeScript • PostgreSQL • Sequelize<br/>
  <i>Turning ideas into secure, scalable backend systems</i>
</p>

<p align="center">
  <a href="#"><img src="https://img.shields.io/badge/Code-Node.js%20%2B%20TS-3178C6?logo=node.js" /></a>
  <a href="https://www.linkedin.com/in/sunil-rajoli-731478212/"><img src="https://img.shields.io/badge/LinkedIn-Connect-0A66C2?logo=linkedin" /></a>
  <a href="mailto:rajolisunilkumar@gmail.com"><img src="https://img.shields.io/badge/Email-rajolisunilkumar%40gmail.com-D14836?logo=gmail" /></a>
</p>

---

## ⚡ About Me
- 🌱 Building production-grade backends with **Node.js + TypeScript + Express + PostgreSQL (Sequelize)**
- 🔐 Obsessed with **security & reliability**: JWT + refresh rotation, role-based auth, rate limiting, audit logs
- 🤖 Actively building **AI/LLM-powered systems** — dynamic SQL generation, RAG pipelines, Groq API
- 🧠 Practicing **DSA** & **system design** to level up fundamentals
- 🎯 12–18 month goal: **ship AI-native backend systems** and grow into a high-ownership engineering role

---

## 🚀 What I'm Building Right Now

### 🗺️ **SAP Order-to-Cash Graph System**
> Enterprise ERP data visualized as an interactive knowledge graph with a natural language query interface

- _Backend:_ Node.js, Express, SQLite (better-sqlite3), Groq API (llama-3.3-70b-versatile)
- _Frontend:_ React, React Flow, dagre layout engine, Tailwind CSS
- _Highlights:_
  - Ingests 19 SAP O2C entity tables (orders, deliveries, billing, payments, customers, products)
  - Auto-builds graph of interconnected business entities with colored node types
  - LLM-powered chat: natural language → dynamic SQL generation → grounded answer
  - Two-step pipeline: SQL generation call → execute on SQLite → narration call
  - Multi-layer guardrail system (regex pre-check + LLM guardrail + SQL allowlist)
  - Handles complex O2C flow tracing: Sales Order → Delivery → Billing → Journal Entry → Payment

<p align="center">
  <a href="https://github.com/SunilRajoli/sap-o2c-graph"><img src="https://img.shields.io/badge/Repo-SAP%20O2C%20Graph-181717?logo=github" /></a>
  <a href="#"><img src="https://img.shields.io/badge/Stack-Node.js%20%2B%20React%20Flow%20%2B%20Groq-FF6B35?logo=javascript" /></a>
  <a href="#"><img src="https://img.shields.io/badge/AI-LLM%20Powered-8B5CF6?logo=openai" /></a>
  <a href="#"><img src="https://img.shields.io/badge/Status-Complete-success" /></a>
</p>

---

### 🛰️ **Pulse Notification System**
> Instagram/Twitter-style feed + notifications stack

- _Backend:_ Node.js, Express, PostgreSQL, Sequelize, Redis, BullMQ, JWT
- _Frontend:_ React 18, Vite, React Router, CSS Modules, lucide-react
- _Highlights:_ async like notifications, aggregation with functional index, Redis cache-aside, worker-based invalidation, responsive dark editorial UI

<p align="center">
  <a href="https://github.com/SunilRajoli/Pulse-Notification-System"><img src="https://img.shields.io/badge/Repo-Notification%20System-181717?logo=github" /></a>
  <a href="#"><img src="https://img.shields.io/badge/Stack-Node.js%20%2B%20PostgreSQL%20%2B%20React-61DAFB?logo=javascript" /></a>
  <a href="#"><img src="https://img.shields.io/badge/Status-Feature%20Complete-success" /></a>
</p>

---

### 🏯 **Omotenashi Connect (おもてなし Connect · Hospitality Connect)**
> Japan-focused booking backend (SaaS → Marketplace path)

- _Stack:_ Node.js, TS, Express, Sequelize, PostgreSQL, Redis/BullMQ, Swagger
- _Highlights:_ timezone-safe bookings, overlap guards (`EXCLUDE USING GIST`), email flows, EN/JA i18n

<p align="center">
  <a href="https://github.com/SunilRajoli/omotenashi-connect"><img src="https://img.shields.io/badge/Repo-View%20on%20GitHub-181717?logo=github" /></a>
  <a href="#"><img src="https://img.shields.io/badge/Docs-OpenAPI%20%2F%20Swagger-85EA2D?logo=swagger" /></a>
  <a href="#"><img src="https://img.shields.io/badge/Status-In%20Development-blue" /></a>
</p>

---

### 🧩 **CareBridge**
> Disaster-aid coordination backend

- _Highlights:_ secure auth, email verification, password reset, refresh tokens, migrations
- _Stack:_ Node.js, Express, Sequelize, PostgreSQL, Nodemailer

<p align="center">
  <a href="https://github.com/polimera0000-glitch/carebridge-backend"><img src="https://img.shields.io/badge/Repo-View%20on%20GitHub-181717?logo=github" /></a>
  <a href="#"><img src="https://img.shields.io/badge/Docs-Readme%20Overview-4B32C3?logo=readme" /></a>
  <a href="#"><img src="https://img.shields.io/badge/Status-Stable%20Core-success" /></a>
</p>

---

### 💼 **PPL (Premier Project League)**
> Developer collaboration + startup incubation platform

- _Stack:_ Node.js, TypeScript, Express, Sequelize, PostgreSQL, Flutter (Android client)
- _Highlights:_ contact request system, investor / hiring roles, message queues, admin panel

<p align="center">
  <a href="https://github.com/polimera0000-glitch/ppl"><img src="https://img.shields.io/badge/Repo-View%20on%20GitHub-181717?logo=github" /></a>
  <a href="#"><img src="https://img.shields.io/badge/Docs-Project%20Spec-orange?logo=markdown" /></a>
  <a href="#"><img src="https://img.shields.io/badge/Status-Active%20Development-yellow" /></a>
</p>

---

## 🛠️ Tech Stack
**Languages:** TypeScript, JavaScript (ES6+), SQL
**Backend:** Node.js, Express, REST APIs
**Database:** PostgreSQL, SQLite, Sequelize ORM (migrations, transactions, constraints)
**AI/LLM:** Groq API, LLM Integration, Prompt Engineering, Dynamic SQL Generation
**Infra & DX:** Docker, CI/CD (GitHub Actions), Redis, BullMQ, Swagger/OpenAPI
**Security:** JWT + refresh rotation, role-based access, rate limiting, audit logs
**Tools:** Cursor, Claude Code, Postman, Git
**Learning:** System Design, Distributed Systems, RAG Pipelines, Vector Databases

---

## 🧩 Highlights
- Built an **LLM-powered query interface** over SAP ERP data with dynamic SQL generation and multi-layer guardrails
- Designed **booking concurrency** using PostgreSQL `tstzrange` + `EXCLUDE USING gist`
- Implemented **email verification** & **password reset** with hashed tokens + expiry
- Built **seeders & migrations** for consistent environment replication
- Documented APIs with **Swagger** and tested via REST Client / cURL

---

## 📚 Roadmap (Next Up)
- 🧠 RAG pipeline — personal knowledge base with vector search
- 💳 Payments integration (Stripe / Pay.jp) — deposits vs full prepay + JP receipts
- 🔍 Search & discovery (PostGIS, filters) + observability (metrics, logs, traces)
- 🏗️ Multi-tenant hardening, import tools, and i18n expansion

---

## 📫 Connect With Me
- **LinkedIn:** <a href="https://www.linkedin.com/in/sunil-rajoli-731478212/">sunil-rajoli-731478212</a>
- **Email:** <a href="mailto:rajolisunilkumar@gmail.com">rajolisunilkumar@gmail.com</a>
