<h1 align="center">Hi 👋, I'm Pawan Kumar</h1>
<h3 align="center">Backend & Full-Stack Engineer · I build systems that stay reliable under real traffic</h3>

<p align="center">
  <a href="https://linkedin.com/in/guppwn"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white"/></a>
  <a href="mailto:guppwn@gmail.com"><img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white"/></a>
  <a href="https://www.npmjs.com/package/@nexocache/cache"><img src="https://img.shields.io/badge/npm-CB3837?style=for-the-badge&logo=npm&logoColor=white"/></a>
  <a href="https://github.com/Pawangupta123"><img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white"/></a>
</p>

<p align="center">
  <img src="https://komarev.com/ghpvc/?username=Pawangupta123&color=0A66C2&style=flat&label=Profile+Views"/>
  <img src="https://img.shields.io/github/followers/Pawangupta123?style=flat&color=0A66C2"/>
</p>

---

## 💫 About

Full-Stack Developer at **EaseMyResearch**, focused on **backend engineering, distributed systems, and AI-powered applications**. I'd rather solve a production problem — a cache stampede, a payment race condition, a queue that must never lose a job — than build another CRUD app.

- 🔭 Building production SaaS, payment infrastructure, and developer tooling
- 📦 Published my first open-source npm package (below)
- 🧠 200+ LeetCode problems · strong DSA fundamentals
- 💬 Ask me about **caching, Redis, queues, or Node.js internals**
- 📄 [Resume](ADD_YOUR_RESUME_LINK) · open to **backend / full-stack roles**

---

## 📦 Featured — NexoCache

**[`@nexocache/cache`](https://www.npmjs.com/package/@nexocache/cache)** — a production-grade caching library for Node.js.

<p>
  <a href="https://www.npmjs.com/package/@nexocache/cache"><img src="https://img.shields.io/npm/v/@nexocache/cache?color=cb3837&label=npm"/></a>
  <a href="https://www.npmjs.com/package/@nexocache/cache"><img src="https://img.shields.io/npm/dm/@nexocache/cache?color=cb3837&label=downloads"/></a>
  <img src="https://img.shields.io/badge/tests-557-brightgreen"/>
  <img src="https://img.shields.io/badge/coverage-97%25-brightgreen"/>
  <img src="https://img.shields.io/badge/dependencies-0-brightgreen"/>
</p>

Most caching libraries solve *how to cache*. This one solves *what happens when the cache breaks*:

- **Stampede protection** — 10,000 concurrent requests for one expired key produce **1 database query**, not 10,000
- **Fail-open** — Redis goes down, the app keeps serving; no 500s
- **Distributed locking**, **tag invalidation**, **stale-while-revalidate**, decorators for both legacy TS and TC39 Stage-3
- **Zero runtime dependencies**, dual ESM + CJS, 97% coverage plus an 80% mutation score, published with npm provenance from CI

→ **[github.com/Pawangupta123/CacheForge](https://github.com/Pawangupta123/CacheForge)**

---

## 💼 Experience

**Full-Stack Developer** — EaseMyResearch · Jodhpur, Rajasthan · *Jul 2024 – Present*

<!-- [square brackets] = metric placeholders. Put a real number, or delete the bracketed part. Even one real figure lifts the whole section. -->

- Architected a production **payment system** with Razorpay — full order-lifecycle state machine, HMAC-SHA256 webhook verification, and Redis distributed locks (Lua CAS) — [processing ~N transactions/month]
- Built a **4-process BullMQ worker pipeline** — payment webhooks, invoice generation (PDFKit + S3), transactional email, and bulk downloads with dead-letter handling — [~N jobs/day]
- Led a full backend migration to a **6-layer modular architecture** (Route → DTO → Controller → Service → Repository → Model) across **30+ modules**
- Built the frontend with **Next.js 16, React 19, TypeScript, Redux Toolkit** across **9+ feature modules**
- Integrated **AI document processing** — OCR and PDF analysis via AWS Textract and OpenAI/Claude APIs, served through Python AI services

---

## 🛠️ Tech Stack

**Languages**
<p>
  <img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white"/>
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black"/>
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white"/>
  <img src="https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=mysql&logoColor=white"/>
</p>

**Backend & Queues**
<p>
  <img src="https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white"/>
  <img src="https://img.shields.io/badge/Express-000000?style=flat-square&logo=express&logoColor=white"/>
  <img src="https://img.shields.io/badge/NestJS-E0234E?style=flat-square&logo=nestjs&logoColor=white"/>
  <img src="https://img.shields.io/badge/BullMQ-DC382D?style=flat-square&logo=redis&logoColor=white"/>
  <img src="https://img.shields.io/badge/Zod-3E67B1?style=flat-square"/>
  <img src="https://img.shields.io/badge/JWT-000000?style=flat-square&logo=jsonwebtokens&logoColor=white"/>
</p>

**Frontend**
<p>
  <img src="https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB"/>
  <img src="https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white"/>
  <img src="https://img.shields.io/badge/Redux_Toolkit-764ABC?style=flat-square&logo=redux&logoColor=white"/>
  <img src="https://img.shields.io/badge/TailwindCSS-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white"/>
  <img src="https://img.shields.io/badge/shadcn/ui-000000?style=flat-square"/>
</p>

**Databases**
<p>
  <img src="https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white"/>
  <img src="https://img.shields.io/badge/MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white"/>
  <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white"/>
  <img src="https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white"/>
</p>

**DevOps & AI**
<p>
  <img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white"/>
  <img src="https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white"/>
  <img src="https://img.shields.io/badge/AWS_S3-569A31?style=flat-square&logo=amazons3&logoColor=white"/>
  <img src="https://img.shields.io/badge/Swagger-85EA2D?style=flat-square&logo=swagger&logoColor=black"/>
  <img src="https://img.shields.io/badge/OpenAI-412991?style=flat-square&logo=openai&logoColor=white"/>
  <img src="https://img.shields.io/badge/AWS_Textract-FF9900?style=flat-square&logo=amazonaws&logoColor=white"/>
</p>

---

## 📌 More Projects

| Project | What it is |
| --- | --- |
| 🏗️ **[Node.js Production Template](https://github.com/Pawangupta123/node-templete)** | Enterprise backend starter — JWT auth, Swagger docs, Docker Compose, Redis/BullMQ, CI/CD, Husky |
| 🏗️ **[NestJS Production Template](https://github.com/Pawangupta123/Nest-templete)** | NestJS boilerplate — module architecture, TypeORM, JWT, Swagger, PostgreSQL, CI/CD |
| 💼 **EaseMyResearch** | Production research SaaS — payments, AI document processing, and real-time dashboards |

---

## 📊 GitHub Stats

<p align="center">
  <img width="48%" src="https://github-readme-stats.vercel.app/api?username=Pawangupta123&show_icons=true&theme=tokyonight&hide_border=true&count_private=true&cache_seconds=86400"/>
  <img width="48%" src="https://github-readme-streak-stats.herokuapp.com/?user=Pawangupta123&theme=tokyonight&hide_border=true"/>
</p>

<p align="center">
  <img width="48%" src="https://github-readme-stats.vercel.app/api/top-langs/?username=Pawangupta123&layout=compact&theme=tokyonight&hide_border=true&langs_count=8&cache_seconds=86400"/>
</p>

<!-- Contribution snake — generated daily by .github/workflows/snake.yml.
     It appears only after the workflow has run once (Actions tab → "Generate Snake" → Run workflow). -->
<p align="center">
  <img src="https://raw.githubusercontent.com/Pawangupta123/Pawangupta123/output/snake.svg" alt="contribution snake"/>
</p>

---

## 📫 Connect

<p>
  <a href="https://linkedin.com/in/guppwn">LinkedIn</a> ·
  <a href="mailto:guppwn@gmail.com">guppwn@gmail.com</a> ·
  <a href="tel:+918905935803">+91-8905935803</a> ·
  <a href="https://www.npmjs.com/package/@nexocache/cache">npm</a>
</p>

<p align="center"><i>Every "must not" in my code is a bug I found, measured, and fixed.</i></p>
