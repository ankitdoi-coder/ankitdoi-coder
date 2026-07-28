<h1 align="center">Hi 👋, I'm Ankit Kumar Gurjar</h1>
<h3 align="center">Java Backend Developer | Production-grade Spring Boot systems — security, payments, containerization, AI integration</h3>

<p align="center">
  <a href="https://twitter.com/coderankit82">
    <img src="https://img.shields.io/twitter/follow/coderankit82?logo=twitter&style=for-the-badge" alt="coderankit82" />
  </a>
</p>

---

## 🚀 About Me

Java Backend Developer focused on building systems the way they're actually built in production: JWT-secured APIs with real server-side session revocation, payment flows that cryptographically verify themselves, containerized and reproducible deployments, and guardrailed AI features — not just CRUD that happens to work.

- 🔭 **Currently building:** [Smart Hospital Management System](https://github.com/ankitdoi-coder/Hospital_System_Backend) — a full-stack healthcare platform: JWT + Redis-backed auth, OAuth2 login, role-based dashboards (Patient/Doctor/Admin), Razorpay payments with HMAC verification, a fully Dockerized deployment (backend + MySQL + Redis), and an AI Health Assistant powered by Groq's Llama 3.3.
- 🌱 **Currently deepening:** Kafka & WebSocket, for event-driven and real-time system design.
- 👯 **Open to collaborating on:** [Smart Hospital Management System](https://github.com/ankitdoi-coder/Hospital_System_Backend)
- 🤝 **Looking for help with:** [Movie Platform](https://github.com/ankitdoi-coder/Movie-Downloding-Platform.git)
- 👨‍💻 **Portfolio:** [ankitgurjar.netlify.app](https://ankitgurjar.netlify.app/)
- 📄 **Resume:** [View here](https://drive.google.com/file/d/1w3slOydgaM4NqBdt_77HARwdusu9aEiu/view?usp=sharing)
- 💬 **Ask me about:** Spring Boot, Spring Security, JWT/OAuth2, REST API design, Docker, LLM API integration, React, Redux, payment gateway integrations
- 📫 **Reach me at:** ankitdoi82@gmail.com

---

## 🏆 Featured Project

### 🏥 Smart Healthcare Appointment & Records System
A production-grade full-stack healthcare platform — 45+ REST endpoints, packaged by business feature across 9 domain modules, built and shipped solo end-to-end.

- 🔐 **Stateless JWT authentication** with RBAC across 3 roles (`PATIENT` / `DOCTOR` / `ADMIN`), Google OAuth2 login, and email OTP verification
- 🚪 **Redis-backed token blacklisting** — real server-side logout for stateless JWTs, closing the gap where a token otherwise stays valid until natural expiry
- 💳 **Razorpay payment gateway** — full order lifecycle (create → checkout → verify) with server-side HMAC-SHA256 signature verification; the backend, never the client, is the source of truth for payment status
- 💰 **Billing & revenue module** — full payment audit trail across 200+ records, real-time daily/monthly revenue analytics for admins
- 🐳 **Fully containerized** — Spring Boot + MySQL + Redis all run via a multi-stage Docker build and Docker Compose, with health-checked startup ordering and persistent volumes; spin up the entire stack with one command
- 🤖 **AI Health Assistant** — a guardrailed chatbot powered by Groq's Llama 3.3 (OpenAI-compatible API), with a system prompt restricting it to general health guidance only, integrated as a floating widget on the patient dashboard
- 🔔 Dual-channel (in-app + email) notification system, doctor-approval workflow, secure password-reset flow
- 🛡️ Global exception handling with a consistent JSON error contract across the entire API
- 📄 Server-side pagination across all major list endpoints — no unbounded full-table fetches
- 🎨 React 19 + Redux Toolkit frontend, 3 role-specific dashboards, fully documented via Swagger/OpenAPI
- 📈 480+ GitHub commits, sole engineer, end-to-end ownership

🔗 [Backend Repo](https://github.com/ankitdoi-coder/Hospital_System_Backend) · [Frontend Repo](https://github.com/ankitdoi-coder/Hospital_System_Frontend)

---

## 💼 Professional Experience

**Jr. Software Developer — SAG InfoTech Pvt. Ltd.** (Dec 2025 – Feb 2026)
Delivered 3 full-stack CA (Chartered Accountant) firm portals end-to-end using Angular + Spring Boot — tax filing, GST filing, and regulatory compliance workflows for real clients. Built multi-file upload handling with backend blob storage/serialization and integrated a payment gateway for client transactions. Diagnosed and fixed a production file-handling bug that a 5-developer team had been unable to resolve, tracing the root cause through the full request pipeline.

---

## 🔗 Connect with Me

[![Twitter](https://img.shields.io/badge/Twitter-1DA1F2?style=for-the-badge&logo=twitter&logoColor=white)](https://twitter.com/coderankit82)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/ankit-kumar-gurjar)
[![Instagram](https://img.shields.io/badge/Instagram-E4405F?style=for-the-badge&logo=instagram&logoColor=white)](https://www.instagram.com/ankitdev0/)
[![YouTube](https://img.shields.io/badge/YouTube-FF0000?style=for-the-badge&logo=youtube&logoColor=white)](https://www.youtube.com/@ProgrammerAnkit)
[![HackerRank](https://img.shields.io/badge/HackerRank-2EC866?style=for-the-badge&logo=hackerrank&logoColor=white)](https://www.hackerrank.com/ankitdoi82)
[![LeetCode](https://img.shields.io/badge/LeetCode-FFA116?style=for-the-badge&logo=leetcode&logoColor=white)](https://leetcode.com/u/ANKITDOI0/)

---

## 🛠️ Languages and Tools

### 💻 Backend
![Java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)
![Spring](https://img.shields.io/badge/Spring-6DB33F?style=for-the-badge&logo=spring&logoColor=white)
![Spring Boot](https://img.shields.io/badge/Spring_Boot-6DB33F?style=for-the-badge&logo=spring-boot&logoColor=white)
![JPA](https://img.shields.io/badge/JPA-6DB33F?style=for-the-badge&logo=hibernate&logoColor=white)
![Hibernate](https://img.shields.io/badge/Hibernate-59666C?style=for-the-badge&logo=hibernate&logoColor=white)
![Spring Security](https://img.shields.io/badge/Spring_Security-6DB33F?style=for-the-badge&logo=spring-security&logoColor=white)
![JWT](https://img.shields.io/badge/JWT-black?style=for-the-badge&logo=JSON%20web%20tokens)
![OAuth 2.0](https://img.shields.io/badge/OAuth2.0-eb5424?style=for-the-badge&logo=oauth2&logoColor=white)
![Razorpay](https://img.shields.io/badge/Razorpay-0C2451?style=for-the-badge&logo=razorpay&logoColor=white)
![Groq](https://img.shields.io/badge/Groq_LLM_API-F55036?style=for-the-badge&logo=OpenAI&logoColor=white)
![JSP](https://img.shields.io/badge/JSP-007396?style=for-the-badge&logo=java&logoColor=white)
![Servlet](https://img.shields.io/badge/Servlet-007396?style=for-the-badge&logo=java&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=for-the-badge&logo=redis&logoColor=white)

### 🎨 Frontend
![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![Angular](https://img.shields.io/badge/Angular-DD0031?style=for-the-badge&logo=angular&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-007ACC?style=for-the-badge&logo=typescript&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![Bootstrap](https://img.shields.io/badge/Bootstrap-563D7C?style=for-the-badge&logo=bootstrap&logoColor=white)
![TailwindCSS](https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white)

### 🗄️ Database & Cloud
![MySQL](https://img.shields.io/badge/MySQL-005C84?style=for-the-badge&logo=mysql&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)
![Cloudinary](https://img.shields.io/badge/Cloudinary-3448C5?style=for-the-badge&logo=cloudinary&logoColor=white)

### ⚙️ DevOps & Tools
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![Postman](https://img.shields.io/badge/Postman-FF6C37?style=for-the-badge&logo=postman&logoColor=white)
![Swagger](https://img.shields.io/badge/Swagger-85EA2D?style=for-the-badge&logo=swagger&logoColor=black)
![Figma](https://img.shields.io/badge/Figma-F24E1E?style=for-the-badge&logo=figma&logoColor=white)

---

## 📊 GitHub Stats

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=ankitdoi-coder&show_icons=true&theme=radical&locale=en" alt="ankitdoi-coder" />
</p>

<p align="center">
  <img src="https://streak-stats.demolab.com/?user=ankitdoi-coder&theme=radical" alt="ankitdoi-coder" />
</p>

<p align="center">
  <img src="https://github-readme-activity-graph.vercel.app/graph?username=ankitdoi-coder&theme=react-dark" />
</p>

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api/top-langs?username=ankitdoi-coder&show_icons=true&theme=radical&locale=en&layout=compact" alt="ankitdoi-coder" />
</p>
