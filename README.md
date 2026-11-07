<h1 align="center">Kennedy Maingi</h1>
<p align="center"><b>Software Engineer · Backend & Full-Stack</b><br>Nairobi, Kenya · E&amp;M Technology</p>

<p align="center">
  <a href="mailto:kennedykyalo2000@gmail.com"><img src="https://img.shields.io/badge/Email-kennedykyalo2000%40gmail.com-0A66C2?style=flat-square&logo=gmail&logoColor=white" alt="Email"></a>
  <img src="https://img.shields.io/badge/Location-Nairobi%2C%20Kenya-2E7D32?style=flat-square" alt="Location">
  <img src="https://img.shields.io/badge/Open%20to-collaboration-6A1B9A?style=flat-square" alt="Open to collaboration">
</p>

---

### About

I build backend services and full-stack web applications, from REST APIs and relational data models to the interfaces people actually use. My work spans **AI products** (LLM assistants and retrieval-augmented knowledge bases), **fintech** (loan origination and KYC), **commerce** (point-of-sale, inventory and food ordering) and **web platforms** with authentication, file storage and admin tooling.

I studied **Computer Science at Egerton University**, and I'm especially interested in **secure software**: access control, data protection and building systems people can trust.

---

### Expertise

| Area | What I work with |
|---|---|
| **Backend** | Node.js, Express, Java 17, Spring Boot 3 (Web, Data JPA), REST API design, Socket.io, layered controller → service → repository architecture |
| **AI & LLMs** | OpenAI and Google Gemini APIs, retrieval-augmented generation (RAG), document ingestion and indexing, web scraping (Puppeteer, Cheerio) |
| **Integrations** | Stripe billing, Twilio voice, Google OAuth, transactional email |
| **Frontend** | React, JavaScript (ES6+), HTML5, CSS3, Material UI, Bootstrap, Alpine.js |
| **Desktop** | Electron (cross-platform packaging for Windows and macOS) |
| **Databases** | MongoDB, MySQL, MariaDB, PostgreSQL, H2, Firebase, schema design |
| **Platforms & tools** | Supabase (Auth, Row-Level Security, Storage, Edge Functions), Gradle, Git, PHP |
| **Security** | OWASP Top 10 hardening, multi-tenant isolation, JWT and OAuth authentication, role-based access, row-level security, KYC workflows |

<p>
  <img src="https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white" alt="Java">
  <img src="https://img.shields.io/badge/Spring%20Boot-6DB33F?style=for-the-badge&logo=springboot&logoColor=white" alt="Spring Boot">
  <img src="https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white" alt="Node.js">
  <img src="https://img.shields.io/badge/Express-000000?style=for-the-badge&logo=express&logoColor=white" alt="Express">
  <img src="https://img.shields.io/badge/MongoDB-47A248?style=for-the-badge&logo=mongodb&logoColor=white" alt="MongoDB">
  <img src="https://img.shields.io/badge/OpenAI-412991?style=for-the-badge&logo=openai&logoColor=white" alt="OpenAI">
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" alt="JavaScript">
  <img src="https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB" alt="React">
  <img src="https://img.shields.io/badge/Electron-47848F?style=for-the-badge&logo=electron&logoColor=white" alt="Electron">
  <img src="https://img.shields.io/badge/PHP-777BB4?style=for-the-badge&logo=php&logoColor=white" alt="PHP">
  <img src="https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white" alt="MySQL">
  <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white" alt="PostgreSQL">
  <img src="https://img.shields.io/badge/Supabase-3FCF8E?style=for-the-badge&logo=supabase&logoColor=white" alt="Supabase">
  <img src="https://img.shields.io/badge/Firebase-FFCA28?style=for-the-badge&logo=firebase&logoColor=black" alt="Firebase">
  <img src="https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white" alt="Git">
</p>

---

### Selected work

#### 🤖 Pamilo AI: AI business assistant platform *(Node.js · Express · MongoDB · React · OpenAI / Gemini)*
A multi-tenant SaaS platform where businesses deploy an AI assistant trained on their own knowledge, built for a Canadian company.
- **Knowledge base and RAG Q&amp;A**: ingests PDFs, Word documents, CSVs and scraped websites, indexes them, and grounds AI answers in the business's own content, with knowledge-gap detection
- **Embeddable chat widget** with real-time conversations (Socket.io), lead capture, and AI phone lines through Twilio
- **Business workspace and platform-admin console** with memberships, audit logging, Stripe billing and token-based usage pricing
- **Security hardening** against the OWASP Top 10: tenant isolation, SSRF protection, rate limiting, Helmet headers, input sanitisation, JWT and Google OAuth sign-in
- *Private repository: client work*

#### 🏦 Loan Origination System: backend *(Java · Spring Boot · JPA · MySQL)*
Backend for a lending platform, covering the loan lifecycle from first contact to application.
- REST controllers for **lead management, customer onboarding, KYC profiles, document management and loan applications**
- Clean layered design (controllers, services, JPA repositories) on Spring Boot 3 and Java 17
- Runs on MySQL or MariaDB in production and H2 for local development
- *Private repository: professional work at E&amp;M Technology*

#### 🎓 [Plumbline](https://github.com/KEN001-cloud/plumbline): expert fellowship platform *(Supabase · PostgreSQL · Alpine.js)*
A complete platform where subject experts apply, get verified, and are paid to review and teach AI.
- **8-step onboarding** that saves progress to the applicant's account and resumes on any device
- **Fellow workspace** for tasks, training and payouts, plus an **admin dashboard** for ID verification, task review and CSV export
- Security built on **PostgreSQL Row-Level Security**, a private file bucket, and admin-only status changes enforced by database triggers
- Email notifications through a Supabase Edge Function, with a 47-check end-to-end browser test suite

#### 🛍️ [Trendy Essentials](https://github.com/KEN001-cloud/trendy-app): point-of-sale desktop app *(Electron · React · Firebase)*
A cross-platform desktop app for running a retail shop.
- Sales, product inventory, returns and user administration
- **Daily and monthly sales reports** with printable receipts
- Firebase backend with offline local storage (NeDB), packaged for Windows and macOS

#### 🍔 [FoodOnWheelz](https://github.com/KEN001-cloud/FoodOnWheelz): online food ordering *(PHP · MySQL · JavaScript)*
A restaurant ordering site with a dish catalogue, cart and checkout, order management and a MySQL data model.

#### 🌐 [WebProject](https://github.com/KEN001-cloud/WebProject): course and training website *(PHP · JavaScript)*
A responsive education site with course catalogue, events and trainers pages, client-side form validation and AJAX ordering.

---

### Currently

- 🤖 Building **Pamilo AI**, an AI business assistant platform, for a Canadian company
- 🔧 Building production backend systems at **E&amp;M Technology**
- 🔐 Deepening my work in **application security**
- 🤝 Open to collaborating on **AI, backend, fintech and security-focused** projects

<p align="center"><a href="mailto:kennedykyalo2000@gmail.com">Get in touch</a></p>
