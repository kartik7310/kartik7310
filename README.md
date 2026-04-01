<div align="center">

# Kartik Lathiyan
### Full Stack Developer (Backend Focused)
[![Portfolio](https://img.shields.io/badge/Portfolio-000?logo=vercel&logoColor=white)](https://kartik-inky.vercel.app/)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?logo=linkedin&logoColor=white)](https://www.linkedin.com/in/kartik-lathiyan-665b712a1)
[![GitHub](https://img.shields.io/badge/GitHub-181717?logo=github&logoColor=white)](https://github.com/kartik7310)

</div>

---

## Featured Projects

### Connexto — Real-Time Connection & Matching Platform
[![GitHub](https://img.shields.io/badge/GitHub-181717?logo=github&logoColor=white)](https://github.com/kartik7310/Connectly)
[![Live](https://img.shields.io/badge/Live-Demo-success?logo=google-chrome)](https://connexto.site/)

Real-time platform for user discovery, messaging, blogging, and subscription-based access.

- Reduced API response time by **~75%** (from ~420ms to ~105ms) via Redis caching and MongoDB compound indexing — verified with Autocannon at 100 concurrent users
- Real-time messaging with **Socket.io** and **Redis** — typing indicators, online/offline presence, in-app notifications
- **JWT, Google OAuth, OTP** authentication with **RBAC** (Free vs Premium) and **Stripe** subscription webhooks
- Deployed via **Docker** and **GitHub Actions CI/CD** on **AWS EC2**

`Node.js` `Express` `MongoDB` `Redis` `Socket.io` `Stripe` `Docker` `AWS EC2`

---

### KnowledgeBase — AI Document Assistant (RAG)
[![GitHub](https://img.shields.io/badge/GitHub-181717?logo=github&logoColor=white)](https://github.com/kartik7310/KnowledgeBase)
[![Live](https://img.shields.io/badge/Live-Demo-success?logo=google-chrome)](https://knowledge-base-blue.vercel.app/)

Upload PDFs and ask questions — answers grounded strictly in your documents, not general model knowledge.

- Chunked ingestion pipeline: PDF parsing → text splitting → **Groq embeddings** → **Pinecone** vector storage with top-k retrieval
- **LangChain + Groq (LLaMA 3.1)** integration ensuring responses never hallucinate beyond retrieved context
- Secured AI endpoints with rate limiting, file size validation, and prompt injection guards

`Node.js` `Express` `LangChain` `Pinecone` `Groq (LLaMA 3.1)` `React` `TypeScript` `Tailwind`

---

### WalletGuardian — Expense Management SaaS
[![GitHub](https://img.shields.io/badge/GitHub-181717?logo=github&logoColor=white)](https://github.com/kartik7310/Fino)

SaaS platform for expense tracking, recurring transactions, analytics, and AI-assisted financial advice.

- **BullMQ + Redis** job queue for monthly report generation — jobs are idempotent and retry-safe
- **Groq**-powered financial chatbot — for getting finincial advice and Q/A
- **Stripe** subscription enforcement with server-side webhook signature validation
- JWT, Google OAuth, OTP auth with **Zod** input validation and rate limiting

`Node.js` `Express` `MongoDB` `Redis` `BullMQ` `Stripe` `Groq` `React` `TypeScript`

---

### VoiceSaathi — AI Voice Mock Interview Platform
[![GitHub](https://img.shields.io/badge/GitHub-181717?logo=github&logoColor=white)](https://github.com/kartik7310/VoiceSaathi)
[![Live](https://img.shields.io/badge/Live-Demo-success?logo=google-chrome)](https://prep-saathi.vercel.app/)

AI-powered mock interview platform with real-time voice conversation — simulates human interviewers using Voice AI.

- Integrated **Vapi AI** for real-time audio streaming, Speech-to-Text, and Text-to-Speech — users speak naturally as in a real interview
- **Groq**-powered question generation and feedback engine — dynamically generates job-specific questions from user-provided JD and scores answers on technical accuracy, communication, and tone
- Built on **Supabase** (PostgreSQL + Auth) for session management, transcript storage, and interview history
- **SSR with Next.js 15** App Router for fast page loads; full responsive UI with Tailwind CSS and shadcn/ui

`Next.js 15` `Supabase` `PostgreSQL` `Vapi AI` `Groq` `Tailwind CSS` `shadcn/ui`

---

### ProductHub — E-Commerce Backend
[![GitHub](https://img.shields.io/badge/GitHub-181717?logo=github&logoColor=white)](https://github.com/kartik7310/ProductHub)

Backend system modelling real purchase workflows — ensures inventory consistency under concurrent usage.

- Atomic order creation using **PostgreSQL transactions** with locking strategies to prevent overselling
- Modular **NestJS** architecture (Controller → Service → Repository) with DTO validation
- Access & Refresh Token (**JWT**) auth with API rate limiting

`NestJS` `PostgreSQL` `Prisma ORM` `JWT`

---

## Tech Stack

### Languages & Frontend
<div align="center">
<img src="https://skillicons.dev/icons?i=js,ts,html,css,react,nextjs,tailwind" />
</div>

### Backend
<div align="center">
<img src="https://skillicons.dev/icons?i=nodejs,express,nestjs" />
&nbsp;
<img src="https://cdn.simpleicons.org/socketdotio/010101" width="48"/>
</div>

```
✓ REST API Design        ✓ WebSockets (Socket.io)
✓ BullMQ Background Jobs ✓ Cron Automation
```

### Databases & Caching
<div align="center">
<img src="https://skillicons.dev/icons?i=mongodb,postgres,redis,mysql" />
&nbsp;
<img src="https://cdn.simpleicons.org/prisma/2D3748" width="48"/>
</div>

```
✓ NoSQL & Relational Modeling   ✓ Transactions & Locking
✓ Query Optimization & Indexing ✓ Redis Caching & Queues
```

### Auth & Security
<div align="center">
<img src="https://cdn.simpleicons.org/jsonwebtokens/000000" width="48"/>
&nbsp;
<img src="https://cdn.simpleicons.org/stripe/008CDD" width="48"/>
</div>

```
✓ JWT / OAuth 2.0 / OTP ✓ RBAC Authorization
✓ Rate Limiting         ✓ Stripe Webhooks
```

### AI / RAG
<div align="center">
<img src="https://cdn.simpleicons.org/langchain/1C3C3C" width="48"/>
&nbsp;
<img src="https://cdn.simpleicons.org/pinecone/000000" width="48"/>
&nbsp;
<img src="https://skillicons.dev/icons?i=openai" />
</div>

```
✓ RAG Pipelines                    ✓ Vector Embeddings & Semantic Search
✓ Document Chunking & Retrieval    ✓ LLM Integration (Groq / LLaMA 3.1)
```

### Cloud & DevOps
<div align="center">
<img src="https://skillicons.dev/icons?i=docker,aws,nginx,githubactions,linux" />
</div>

```
✓ Docker & CI/CD (GitHub Actions) ✓ AWS EC2 & S3
✓ Nginx Reverse Proxy             ✓ ImageKit / Cloudinary
```

### Tools
<div align="center">
<img src="https://skillicons.dev/icons?i=git,github,vscode,postman,ubuntu" />
</div>

---

## Education

**Bachelor of Computer Applications (BCA)**  
Maa Shakumbhari University, Uttar Pradesh · 2023–2026
