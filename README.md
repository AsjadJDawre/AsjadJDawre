<!-- Hero -->
<div align="center">
  <img src="https://mir-s3-cdn-cf.behance.net/project_modules/max_1200/79731568097599.5b50bca477735.jpg" alt="MasterHead" style="width: 100%; max-width: 1100px; border-radius: 12px; box-shadow: 0 6px 16px rgba(0,0,0,0.15);"/>
  
  <h1>👋 Hi, I'm <b>ASJAD JOHAR DAWRE</b></h1>
  <h3>🚀 Full Stack Engineer (MERN / PERN) • Backend-Focused • System Design Enthusiast</h3>

  <a href="mailto:dawreasjad72@gmail.com">
    <img src="https://img.shields.io/badge/Email-dawreasjad72%40gmail.com-D14836?style=for-the-badge&logo=gmail&logoColor=white" />
  </a>
  <a href="https://linkedin.com/in/asjad-johar/">
    <img src="https://img.shields.io/badge/LinkedIn-asjad--johar-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" />
  </a>
  <a href="https://e-grampanchayat.onrender.com/">
    <img src="https://img.shields.io/badge/Live-Demo-00C853?style=for-the-badge&logo=vercel&logoColor=white" />
  </a>
</div>

---
 <!--
<div style="display: flex; justify-content: center;  align-items: center; margin: 20px 0;">
  <img width="400" alt="animatedGif" src="https://media.licdn.com/dms/image/D4D12AQEwYz74Mf7XKA/article-cover_image-shrink_600_2000/0/1677431973169?e=2147483647&v=beta&t=XAXpJxyem6V0COVr2qwSxPLctoigzjSXhAa4PSHczMI" style="border-radius: 10px; box-shadow: 0 4px 8px rgba(0,0,0,0.1);"/>
</div>
-->
## ⚡ About Me
- Backend-leaning full stack developer building production-grade APIs and multi-tenant systems
- Delivered 57% latency reduction across MERN/PERN apps using indexing, caching (Redis), and API tuning
- Comfortable with REST design, RBAC, JWT/OAuth, Razorpay, and scalable database schemas
- Currently focusing on: performance engineering, API observability, and clean architecture

---

## 🧠 Tech Stack
<div align="center">
  
| Category | Tools |
|---|---|
| Languages | ![JavaScript](https://img.shields.io/badge/JavaScript-ES6+-F7DF1E?logo=javascript&logoColor=000) ![TypeScript](https://img.shields.io/badge/TypeScript-Basic-3178C6?logo=typescript&logoColor=fff) ![Python](https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=fff) ![SQL](https://img.shields.io/badge/SQL-336791?logo=postgresql&logoColor=fff) |
| Backend | ![Node](https://img.shields.io/badge/Node.js-43853D?logo=node.js&logoColor=fff) ![Express](https://img.shields.io/badge/Express.js-000?logo=express&logoColor=fff) ![Nginx](https://img.shields.io/badge/Nginx-009639?logo=nginx&logoColor=fff) |
| Frontend | ![React](https://img.shields.io/badge/React-20232A?logo=react&logoColor=61DAFB) ![Vite](https://img.shields.io/badge/Vite-646CFF?logo=vite&logoColor=fff) ![Tailwind](https://img.shields.io/badge/Tailwind-38B2AC?logo=tailwindcss&logoColor=fff) |
| Databases | ![PostgreSQL](https://img.shields.io/badge/PostgreSQL-316192?logo=postgresql&logoColor=fff) ![MongoDB](https://img.shields.io/badge/MongoDB-4EA94B?logo=mongodb&logoColor=fff) ![Redis](https://img.shields.io/badge/Redis-Caching-DC382D?logo=redis&logoColor=fff) |
| Auth/Payments | ![JWT](https://img.shields.io/badge/JWT-000?logo=jsonwebtokens&logoColor=fff) ![OAuth](https://img.shields.io/badge/OAuth-Auth-3C3C3C) ![Razorpay](https://img.shields.io/badge/Razorpay-Payments-02042B?logo=razorpay&logoColor=fff) |
| DevOps/Tools | ![Docker](https://img.shields.io/badge/Docker-2496ED?logo=docker&logoColor=fff) ![GitHub](https://img.shields.io/badge/GitHub_Actions-CI%2FCD-2088FF?logo=githubactions&logoColor=fff) ![Render](https://img.shields.io/badge/Render-46E3B7?logo=render&logoColor=000) ![Vercel](https://img.shields.io/badge/Vercel-000?logo=vercel&logoColor=fff) ![Postman](https://img.shields.io/badge/Postman-FF6C37?logo=postman&logoColor=fff) |

</div>

---

## 🏆 Impact At A Glance
- 10,000+ users served across platforms
- 40–70% API performance boost via caching, indexes, and query plans
- 57% average latency reduction across services
- Built role-based multi-tenant systems with secure auth and strong isolation

---

## 🚀 Flagship Projects

### 1) E‑Gram Panchayat — Multi‑Tenant Digital Governance Platform
Tech: React, Node.js, Express, MongoDB, JWT, RBAC, Tailwind CSS

- Automated Birth/NOC/Household service flows for 10k+ villagers
- 70% faster processing via indexed queries and robust error middleware
- JWT auth with custom RBAC workflows → 60% faster onboarding
- 40% API latency reduction; uptime improved to 95.9%
- Live: `https://e-grampanchayat.onrender.com/` • Repo: [`E-Gram-Panchayat`](https://github.com/AsjadJDawre/E-Gram-Panchayat)

```mermaid
flowchart LR
  A[Village Registers] --> B[Approval]
  B --> C[Tenant Created]
  C --> D[Admins & Staff]
  D --> E[Citizens Apply]
  E --> F[Review & Verify]
  F --> G[Certificate Issued]
  subgraph Security
    H[JWT] --> I[RBAC]
  end
  C --> H
  style C fill:#c8e6c9,stroke:#2e7d32
```

---

### 2) Refill Buddy — Gas Refill Booking Platform
Tech: React, Node.js, Express, MongoDB, Razorpay, Tailwind

- REST APIs + Razorpay (prepaid/COD) with JWT-based RBAC middleware
- Automated quotas; 50% manual effort reduced, higher compliance
- Load-tested 1000+ scenarios; indexes + caching → 420ms → 180ms
- Handles 50+ concurrent sessions reliably
- Repo: [`Refill-Buddy`](https://github.com/AsjadJDawre/Refill-Buddy)

---

### 3) AcademiaSuite — Academic Management (Desktop)
Tech: React, Electron, Tailwind, Local/Cloud storage

- Desktop suite for academic ops with real-time validation and modular UIs
- Repo: [`AcademiaSuite`](https://github.com/AsjadJDawre/AcademiaSuite)

### 4) NSS Project — Service & Volunteer Management
- Digitized event scheduling, volunteer tracking, and reporting
- Focused on simple UX + transparent record-keeping

---

## 🧩 What I Do Best
- Design clean, scalable REST APIs with versioning, pagination, and middleware
- Craft efficient data models (PostgreSQL joins/indexes, Mongo aggregates)
- Build secure auth flows (JWT/OAuth, role-based permissions)
- Squeeze performance: query tuning, Redis caching, N+1 elimination
- Ship resilient systems: logging, error handling, retry/backoff, CI/CD

---

## 🧪 Recent Internship (Unified Mentor) — Sep 2024 – Dec 2024
- Shipped 3 secure MERN apps with JWT/OAuth and Razorpay
- Implemented RBAC across modules; optimized queries + caching for 40–70% perf gains
- Worked Agile, did peer reviews, and productionized APIs with CI/CD

---

## 📊 GitHub Snapshot
<div align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=asjadjdawre&show_icons=true&theme=radical&hide=issues,prs,contribs" height="160" />
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=asjadjdawre&layout=compact&theme=radical" height="160" />
</div>

---

## 🎓 Certifications
- The Complete 2024 Web Development Bootcamp — Udemy
- Cloud Computing — IBM
- C Programming — Udemy

---

## 🤝 Let’s Build Something Meaningful
I’m open to backend-heavy roles, platform engineering, and product-focused teams that value performance, clarity, and shipping.  
If you have an ambitious idea with real-world impact — let’s talk.

<div align="center">
  <a href="mailto:dawreasjad72@gmail.com">
    <img src="https://img.shields.io/badge/Email-Me-D14836?style=for-the-badge&logo=gmail&logoColor=white" />
  </a>
  <a href="https://linkedin.com/in/asjad-johar/">
    <img src="https://img.shields.io/badge/LinkedIn-Connect-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" />
  </a>
  <img src="https://komarev.com/ghpvc/?username=asjadjdawre&label=Profile%20views&color=0e75b6&style=flat" />
</div>
