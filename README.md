# Hi, I'm Aayush Kumar 👋

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=flat&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/aayush-kumar-97b377295)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat&logo=github&logoColor=white)](https://github.com/aayushverma246-ai)
[![Email](https://img.shields.io/badge/Email-connect.aayush19%40gmail.com-D14836?style=flat&logo=gmail&logoColor=white)](mailto:connect.aayush19@gmail.com)

**Computer Science Undergraduate (2023–2027)** at **Birla Institute of Technology, Mesra** (CGPA: 8.47 / 10).  
Focused on **backend systems, data pipelines, automation workflows, and production LLM integrations**.

---

## 📌 About Me

I design and build backend services, database-backed web applications, and intelligent document processing pipelines. My technical focus centers on transforming complex real-world workflows into reliable, performant systems—from schema architecture and cache optimization to multi-model LLM routing with deterministic fallbacks.

- 🎓 **Education:** B.Tech in Computer Science & Engineering, BIT Mesra (Class of 2027)
- 📍 **Location:** Ranchi, Jharkhand, India
- 💼 **Recent Experience:** AI & Automation Intern at [Sankshit Pvt. Ltd.](#experience--achievements) (May 2026 – Jul 2026)
- ⚙️ **Core Interests:** Distributed APIs, Relational Data Modeling, Document Processing, LLM Evaluation & Fallbacks

---

## 🚀 Featured Projects

### 1. [PaperWait](https://github.com/aayushverma246-ai/PaperWait) — Multi-Format Document Processing & Classification Engine
> **Live Platform:** [paperwait.me](https://paperwait.me) • **Tech Stack:** Next.js 16, TypeScript, PostgreSQL (Supabase), pgvector, NVIDIA NIM APIs (Llama 3.1 & Nemotron), Canvas, PDF.js

* **Multi-Format Extraction Pipeline:** Engineered ingestion and text extraction across 7 distinct document formats (PDF, images, Word, Excel, PowerPoint, CSV, plain text) leveraging direct parsing with an asynchronous concurrency-limited OCR worker fallback.
* **Dual-Path LLM Routing:** Implemented concurrent classification using Llama 3.1 8B (fast path, 8-second ceiling) and Nemotron-3-Nano-Omni (deep reasoning path); routes common financial documents through a ≥0.90 confidence fast path with graceful error handling.
* **Database Isolation & Matching:** Enforced PostgreSQL Row-Level Security (RLS) for tenant isolation, coupled with exact, substring, and Levenshtein fuzzy matching to dynamically organize files into semantic folder hierarchies.

---

### 2. [SarkarHamariHai](https://github.com/aayushverma246-ai/sarkarhamarihai) — Government Exam Discovery & Recommendation Platform
> **Live Platform:** [sarkarhamarihai.app](https://sarkarhamarihai.app) • **Tech Stack:** React 19, Node.js/Express, PostgreSQL (Supabase), Google Gemini API, Tailwind CSS

* **17,000+ Exam Catalog:** Designed and structured a large-scale PostgreSQL catalog with automated status-checking jobs and fingerprint-based duplicate detection (normalized title, conducting agency, exam year).
* **Hybrid Recommendation Engine:** Developed a multi-signal recommendation pipeline combining subject syllabus overlap (40%), semantic similarity (30%), keyword matching (20%), and category alignment (10%). Leveraged Google Gemini to structure sparse official notifications prior to comparison.
* **Payload Optimization:** Optimized the `/all-minimal` catalog transport API via positional array serialization, reducing benchmark JSON payload size by ~49% for high-speed client loads.
* *Selected for Round 2 of Prasunethon 2.0.*

---

### 3. [VoyagerPulse](https://github.com/aayushverma246-ai/VoyagerPulse) — Content & Engagement Analytics Platform
> **Live Platform:** [voyagerpulse.vercel.app](https://voyagerpulse.vercel.app/) • **Tech Stack:** Next.js 16, TypeScript, PostgreSQL (Supabase), Prisma ORM, Recharts, TanStack Query

* **Relational Schema Modeling:** Modeled 5 relational database entities (`Profile`, `Post`, `Analytics`, `RefreshHistory`, `Settings`) in Prisma/PostgreSQL to track post lifecycle and engagement velocity over time.
* **Algorithmic Engagement Insights:** Extracted top 5 hashtags by average engagement, identified high-velocity discussion topics, and generated data-backed post-length recommendations calculated from the top 25% of performing content.
* **Interactive Visualization:** Built responsive analytics dashboards using Recharts and TanStack Table featuring real-time filtering, multi-column sorting, pagination, and client-side CSV exports.

---

## 🛠️ Technical Skills

| Domain | Technologies & Competencies |
| :--- | :--- |
| **Languages** | Python, C++, C, Java, JavaScript (ES6+), TypeScript, SQL |
| **Backend & Architecture** | Node.js, Express, Next.js API Routes, REST APIs, Webhooks, Concurrency Control |
| **Databases & Storage** | PostgreSQL (Supabase), Prisma ORM, MongoDB, pgvector, Relational Schema Design, Row-Level Security (RLS) |
| **AI, RAG & Automation** | n8n Workflows, RAG Pipelines, Vector Search & Embeddings, Google Gemini API, NVIDIA NIM (Llama 3.1, Nemotron), Claude |
| **Frontend & Visualization** | React.js, Next.js, HTML5, CSS3, Tailwind CSS, Recharts |
| **CS Fundamentals & Testing** | Data Structures & Algorithms, OOP, DBMS, Operating Systems, Computer Networks, System & Regression Testing |
| **Developer Tools** | Git, GitHub, VS Code, Vercel, ADB, TWRP |

---

<a id="experience--achievements"></a>
## 💼 Experience & Achievements

### Experience
* **AI & Automation Intern** — **Sankshit Pvt. Ltd.** *(May 2026 – Jul 2026)*
  * Built and verified multi-channel automation workflows (including a 108-node n8n workflow) integrating webhooks, external APIs, structured LLM outputs, and Supabase state.
  * Architected a project-scoped RAG pipeline: extracted files, chunked text (3,000 characters with 150-character overlap), generated vector embeddings, and retrieved context for real-time dashboard queries.
  * Designed data ingestion pipelines across Facebook and Instagram with knowledge retrieval, intent classification, human-in-the-loop review, and escalation logic.
* **Open-Source Testing Contributor & Android ROM/Kernel Tester** *(2023 – Present)*
  * Conducted functional and regression testing on 15+ custom Android ROM and kernel builds using ADB and TWRP on physical devices (Xiaomi Poco X2).
  * Captured bootloop logs (`logcat`, `dmesg`), reproduced edge-case regressions, and coordinated with developers to ship reproducible fixes.

### Key Achievements
* **150+ DSA Problems Solved:** Practiced algorithms and data structures across LeetCode, GeeksforGeeks, and Code 360 (primarily in C++).
* **Prasunethon 2.0:** Selected for Round 2 with SarkarHamariHai for scalable civic tech architecture.

---

## 📬 Contact & Links

* **Email:** [connect.aayush19@gmail.com](mailto:connect.aayush19@gmail.com)
* **LinkedIn:** [linkedin.com/in/aayush-kumar-97b377295](https://www.linkedin.com/in/aayush-kumar-97b377295)
* **GitHub:** [github.com/aayushverma246-ai](https://github.com/aayushverma246-ai)
* **Location:** Ranchi, Jharkhand, India
