<div align="center">

# Kartik Lathiyan

### Full Stack Developer · Backend Focused · AI & Distributed Systems

Building **production-ready web applications, scalable backend systems, real-time platforms, and AI-powered products.**

<p>
  <a href="https://www.linkedin.com/in/kartik-lathiyan-665b712a1">
    <img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" />
  </a>
  <a href="https://github.com/kartik7310">
    <img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" />
  </a>
</p>

</div>

---

## 👨‍💻 About Me

I'm a **Full Stack Developer with a backend-first mindset**, experienced in building production-oriented applications across **backend architecture, REST APIs, databases, real-time systems, AI integrations, authentication, and cloud deployment**.

I enjoy solving engineering problems involving **performance optimization, concurrency, database design, background processing, and scalable API architecture**.

### What I Work With

* ⚙️ Backend architecture & REST API design
* 🗄️ Database modeling, indexing & query optimization
* ⚡ Redis caching, queues & background processing
* 🔄 Real-time applications with WebSockets
* 🤖 LLM applications, RAG & AI integrations
* 🔐 JWT, OAuth, OTP & RBAC
* 💳 Payment integrations & webhook systems
* ☁️ Docker, AWS & CI/CD

---

# 💼 Professional Experience

### Full Stack Developer Intern

**AreKiv Global Research Platforms Pvt. Ltd.** · Remote
`Jan 2026 – Jul 2026`

* Designed and developed a **Real Estate SaaS platform end-to-end**, covering property listings, lead management, meeting bookings, multiple user roles, approval workflows, admin controls, featured listing plans, and Razorpay payments.
* Identified and resolved a **race-condition risk in concurrent booking**, implementing a concurrency-safe solution using **MongoDB partial unique indexes**.
* Improved backend performance by **40%** through compound indexing and reduced redundant frontend API calls by **25–30%** using debounced search and lazy loading.
* Independently developed the **HRMS module**, delivering **30+ REST APIs** and an admin interface for employee lifecycle management, department/designation administration, and invitation-based onboarding.
* Implemented multi-role **RBAC**, payment idempotency, validation, and production-oriented backend workflows.

**Tech:**
`Node.js` `Express.js` `MongoDB` `Mongoose` `Next.js` `React` `Razorpay` `RBAC`

---

# 🚀 Featured Projects

<table>
<tr>

<td width="50%" valign="top">

<h3 align="center">🔗 Connexto</h3>

<p align="center">
  <strong>Real-Time Social & Subscription Platform</strong>
</p>

<p align="center">
  <a href="https://github.com/kartik7310/Connectly">
    <img src="https://img.shields.io/badge/Source_Code-181717?style=flat&logo=github&logoColor=white"/>
  </a>
  <a href="https://connexto.site/">
    <img src="https://img.shields.io/badge/Live_Demo-success?style=flat&logo=google-chrome&logoColor=white"/>
  </a>
</p>

Full-stack real-time platform for **user discovery, messaging, blogging, notifications, and subscription-based premium access**.

### Engineering Highlights

* Designed and shipped the platform **end-to-end from schema design to deployment**
* Diagnosed ~**420ms API latency** caused by unindexed queries
* Reduced average API response time by **75% to ~105ms** using Redis caching and MongoDB compound indexing
* Verified performance using **Autocannon at 100 concurrent users**
* Built real-time **online presence and typing indicators** using Socket.io + Redis
* Implemented automated cron workflows and deployed using **Docker + GitHub Actions on AWS EC2**

**Stack**

`React` `Tailwind CSS` `Node.js` `Express.js` `MongoDB` `Redis` `Socket.io` `Docker` `AWS` `Razorpay`

</td>

<td width="50%" valign="top">

<h3 align="center">🎙️ VoiceSaathi</h3>

<p align="center">
  <strong>AI Mock Interview Platform</strong>
</p>

<p align="center">
  <a href="https://github.com/kartik7310/VoiceSaathi">
    <img src="https://img.shields.io/badge/Source_Code-181717?style=flat&logo=github&logoColor=white"/>
  </a>
  <a href="https://prep-saathi.vercel.app/">
    <img src="https://img.shields.io/badge/Live_Demo-success?style=flat&logo=google-chrome&logoColor=white"/>
  </a>
</p>

AI-powered mock interview platform with **real-time voice interaction, automated question generation, and AI feedback**.

### Engineering Highlights

* Built live voice interviews using **Vapi AI** with Speech-to-Text and Text-to-Speech
* Integrated **Groq LLMs** for dynamic interview question generation
* Reduced question-generation latency from **4–5s to ~2s** through LLM pipeline optimization
* Built AI feedback and scoring for interview responses
* Added shareable interview sessions, email invitations, and Google OAuth
* Used Supabase PostgreSQL for session and interview data management

**Stack**

`Next.js` `Supabase` `PostgreSQL` `Vapi AI` `Groq` `Tailwind CSS`

</td>

</tr>

<tr>

<td width="50%" valign="top">

<h3 align="center">🛒 ProductHub</h3>

<p align="center">
  <strong>E-Commerce Backend System</strong>
</p>

<p align="center">
  <a href="https://github.com/kartik7310/ProductHub">
    <img src="https://img.shields.io/badge/Source_Code-181717?style=flat&logo=github&logoColor=white"/>
  </a>
</p>

Modular e-commerce backend covering **products, categories, orders, inventory, payments, authentication, and API documentation**.

### Engineering Highlights

* Designed modular architecture using **NestJS**
* Prevented inventory overselling with **Prisma atomic transactions and stock locking**
* Implemented JWT/RBAC authentication
* Eliminated an **N+1 query problem** in order creation through batch fetching
* Integrated **Stripe payments**
* Documented REST APIs using **Swagger/OpenAPI**

**Stack**

`NestJS` `PostgreSQL` `Prisma` `Stripe` `JWT` `TypeScript` `Swagger`

</td>

<td width="50%" valign="top">

<h3 align="center">🧠 KnowledgeBase</h3>

<p align="center">
  <strong>AI Document Assistant · RAG</strong>
</p>

<p align="center">
  <a href="https://github.com/kartik7310/KnowledgeBase">
    <img src="https://img.shields.io/badge/Source_Code-181717?style=flat&logo=github&logoColor=white"/>
  </a>
  <a href="https://knowledge-base-blue.vercel.app/">
    <img src="https://img.shields.io/badge/Live_Demo-success?style=flat&logo=google-chrome&logoColor=white"/>
  </a>
</p>

AI-powered document assistant that uses **retrieval-augmented generation** to answer questions from uploaded documents.

### Engineering Highlights

* Built PDF ingestion, text chunking, embedding, and retrieval pipeline
* Used **Pinecone** for vector storage and semantic search
* Integrated **LangChain + Groq / LLaMA**
* Implemented context-grounded responses to reduce unsupported answers
* Added rate limiting, file validation, and prompt-injection protection

**Stack**

`Node.js` `Express.js` `LangChain` `Pinecone` `Groq` `React` `TypeScript` `Tailwind`

</td>

</tr>

<tr>

<td width="50%" valign="top">

<h3 align="center">💳 WalletGuardian</h3>

<p align="center">
  <strong>Expense Management SaaS</strong>
</p>

<p align="center">
  <a href="https://github.com/kartik7310/Fino">
    <img src="https://img.shields.io/badge/Source_Code-181717?style=flat&logo=github&logoColor=white"/>
  </a>
</p>

Expense management SaaS for **transaction tracking, recurring payments, analytics, reports, and AI-assisted financial Q&A**.

### Engineering Highlights

* Implemented asynchronous monthly report generation using **BullMQ + Redis**
* Designed idempotent and retry-safe background jobs
* Integrated Groq-powered financial chatbot
* Implemented Stripe subscription enforcement with webhook signature validation
* Added JWT, Google OAuth, OTP authentication and Zod validation
* Applied API rate limiting for protected endpoints

**Stack**

`Node.js` `Express.js` `MongoDB` `Redis` `BullMQ` `Stripe` `Groq` `React` `TypeScript`

</td>

<td width="50%" valign="top">

<h3 align="center">⚡ Engineering Interests</h3>

<p align="center">
  <strong>Areas I Enjoy Working On</strong>
</p>

<br>

* Backend architecture
* Scalable REST APIs
* Real-time systems
* Distributed background jobs
* Database optimization
* Concurrency & transactions
* AI-powered applications
* RAG pipelines
* Authentication & authorization
* Cloud deployment & CI/CD

</td>

</tr>
</table>

---

# 🛠️ Technical Skills

### 💻 Languages

<p>
<img src="https://skillicons.dev/icons?i=js,ts,python" />
</p>

`JavaScript` · `TypeScript` · `Python`

---

### ⚙️ Backend & APIs

<p>
<img src="https://skillicons.dev/icons?i=nodejs,express,nestjs,fastapi" />
<img src="https://cdn.simpleicons.org/socketdotio/010101" width="48"/>
</p>

`Node.js` · `Express.js` · `NestJS` · `FastAPI`

`REST APIs` · `WebSockets` · `Socket.io` · `BullMQ` · `Cron Jobs`

---

### 🎨 Frontend

<p>
<img src="https://skillicons.dev/icons?i=react,nextjs,tailwind" />
</p>

`React` · `Next.js` · `Tailwind CSS` · `shadcn/ui`

---

### 🗄️ Databases & ORM

<p>
<img src="https://skillicons.dev/icons?i=mongodb,postgres,mysql,redis" />
<img src="https://cdn.simpleicons.org/prisma/2D3748" width="48"/>
</p>

`MongoDB` · `Mongoose` · `PostgreSQL` · `MySQL` · `Redis` · `Prisma ORM`

**Core Concepts**

`Database Modeling` · `Indexing` · `Query Optimization` · `Transactions` · `Concurrency` · `Locking` · `Caching`

---

### 🔐 Security & Authentication

<p>
<img src="https://cdn.simpleicons.org/jsonwebtokens/000000" width="48"/>
</p>

`JWT` · `OAuth 2.0` · `Google OAuth` · `OTP` · `RBAC`

`Zod Validation` · `Rate Limiting` · `API Security` · `Webhook Validation`

---

### 🤖 AI & Integrations

<p>
<img src="https://cdn.simpleicons.org/langchain/1C3C3C" width="48"/>
<img src="https://cdn.simpleicons.org/pinecone/000000" width="48"/>
</p>

`Groq` · `LLaMA 3.1` · `LangChain` · `Pinecone` · `Vapi AI`

`RAG` · `Vector Embeddings` · `Semantic Search` · `Document Retrieval` · `LLM Integration`

---

### 💳 Payments & Services

`Stripe` · `Razorpay` · `Supabase`

---

### ☁️ Cloud & DevOps

<p>
<img src="https://skillicons.dev/icons?i=docker,aws,nginx,githubactions,linux" />
</p>

`Docker` · `AWS EC2` · `AWS S3` · `Nginx` · `GitHub Actions` · `CI/CD` · `Linux`

---

### 🧰 Developer Tools

<p>
<img src="https://skillicons.dev/icons?i=git,github,vscode,postman,ubuntu" />
</p>

`Git` · `GitHub` · `VS Code` · `Postman` · `Swagger / OpenAPI`

---

# 🏆 Achievements

### 🥇 5th Rank — Hackathon

**Shri Ram Group of Colleges** · April 2026

---

# 📜 Certifications

* **Oracle — Agentic AI Foundations Associate**
* **Udemy — Backend Development with Node.js**
* **AWS — Getting Started with Compute**
* **Udemy — Full Stack Development**

---

# 🎓 Education

**Bachelor of Computer Applications (BCA)**
**Maa Shakumbhari University, Uttar Pradesh, India**

`2023 – 2026`

---

<div align="center">

### Let's Build Something Great 🚀

<a href="https://www.linkedin.com/in/kartik-lathiyan-665b712a1">
  <img src="https://img.shields.io/badge/Connect_on_LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" />
</a>

<a href="https://github.com/kartik7310">
  <img src="https://img.shields.io/badge/View_GitHub-181717?style=for-the-badge&logo=github&logoColor=white" />
</a>

</div>
