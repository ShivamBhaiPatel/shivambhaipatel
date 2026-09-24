<div align="center">
  <img src="https://github.com/ShivamBhaiPatel.png" width="120" style="border-radius: 50%;" alt="Shivam Bhai Patel" />

  # Shivam Bhai Patel
  ### Full-Stack & Backend Systems Engineer

  <p>
    <b>Building resilient Spring Boot APIs, Next.js applications, and deterministic automation engines.</b>
  </p>

  <p>
    <a href="https://shivambhaipatel.com/"><img src="https://img.shields.io/badge/Portfolio-shivambhaipatel.com-111827?style=flat-square&logo=vercel&logoColor=white" alt="Portfolio" /></a>
    <a href="https://www.linkedin.com/in/shivambhaipatel/"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
    <a href="mailto:shivambhaipatel1997@gmail.com"><img src="https://img.shields.io/badge/Email-shivambhaipatel1997%40gmail.com-EA4335?style=flat-square&logo=gmail&logoColor=white" alt="Email" /></a>
    <img src="https://img.shields.io/badge/Location-Prayagraj%20%2F%20Remote-059669?style=flat-square&logo=google-maps&logoColor=white" alt="Location" />
  </p>
</div>

---

### ⚡ Executive Summary

Systems and full-stack engineer with **4+ years of experience** architecting high-throughput JVM backends, distributed microservices, and deterministic browser automation platforms.

- **Focus Areas:** Scalable JVM architectures, resilient API gateways, headless browser telemetry, and compile-time contract enforcement.
- **Background:** Scaled retail platforms to 150K+ DAU at **Reflexis Systems (Zebra Technologies)**; independent consultant for enterprise systems, ERP automation, and database tuning.
- **Availability:** Open for Senior Full-Stack, Backend, and Platform Automation roles (Remote / Hybrid: Bangalore, NCR).

---

### 🛠️ Core Competencies & Tech Stack

| Domain | Stack & Tools |
| :--- | :--- |
| **Backend & Architecture** | Java 21, Spring Boot 3, Microservices, RESTful APIs, JPA / Hibernate, Node.js |
| **Databases & Cache** | PostgreSQL, MySQL, IBM DB2, Redis, SQLite, HikariCP |
| **Frontend & UI** | Next.js (15/16), React, TypeScript, Tailwind CSS, Vite |
| **Automation & Systems** | Playwright, Chrome Extensions (MV3), Headless Daemons, Google Skia (Skija) |
| **Infrastructure & CI/CD** | Docker, AWS (EC2, S3), Jenkins, Git, Linux |

---

### 🚀 Production Systems & Flagship Work

#### 🎨 [PracharFlow](https://prachar.shivambhaipatel.com) — *Deterministic Canvas Rendering Engine*
*Low-latency server-side layout and font rendering engine.*
- Built with **Java 21 / Spring Boot 3** on top of **Google Skia (via Skija)**, replacing stochastic generative diffusion models with deterministic rendering.
- Delivers **<150ms** layout compilation for complex Devanagari and Gujarati scripts with **zero GPU overhead**, ensuring 100% font shaping and brand logo accuracy.

#### 🤖 [Workflow Studio](https://github.com/ShivamBhaiPatel) — *Multi-Agent Control Plane*
*Distributed task orchestration engine for autonomous developer agents.*
- Decoupled execution runtime into an isolated headless Node.js engine (`@workflow-studio/core`) backed by an explicit **SQLite task DAG**.
- Enforced strict compile-time boundaries via `tsconfig` to eliminate UI coupling.
- Implemented **Kahn's algorithm** for topological dependency sorting and monotonic fencing tokens to prevent concurrent worker state drift.

#### 🛒 [DealDekho](https://dealdekho.com) — *Multi-Marketplace Price Intelligence*
*Real-time product price aggregator across Amazon, Flipkart, and Croma.*
- Built with **Next.js**, **PostgreSQL**, **Redis**, and automated telemetry via custom browser tooling to avoid brittle anti-bot scraping overhead.

---

### 📐 Architectural Principles & Trade-Offs

- **Compile-Time Boundaries over Runtime Discipline:** Enforce boundaries at the type-checker level (e.g., scoping `@workflow-studio/core` strictly to Node types so accidental UI imports fail at build time).
- **State Verification over False Greens:** In automation, an interaction step does not succeed when an element is clicked—it succeeds when the target state mutation (e.g., modal dismiss, network response) is validated.
- **Deterministic Canvas over Generative Hallucination:** When pixel-accurate typography, logo placement, and latency (<150ms) are non-negotiable, choose mathematical canvas layout over generative AI models.
- **Upstream Aggregation over Adversarial Scraping:** Pair upstream aggregator APIs with verified client-side telemetry rather than maintaining fragile direct scrapers against marketplace bot guards.

---

### 💼 Career Snapshot

* **Independent Software Consultant** *(Apr 2024 – Present)*
  * **FirstCron Services Pvt Ltd (Product: SyntraFlow)**: Collaborated with the engineering team to build the core workflow recording and replay engine for Oracle Fusion ERP. Designed the mechanism to record user step scripts and execute deterministic, automated runs across 50+ business entities, helping cut overall regression cycles by 40%.
  * **SamMegh Technologies**: Diagnosed database bottlenecks, tuned HikariCP connection pools, and eliminated N+1 queries, reducing end-to-end API response latency from ~800ms to <300ms.
* **Software Engineer — Reflexis Systems (Zebra Technologies)** *(Nov 2021 – Mar 2024)*
  * Maintained high-throughput retail workforce management platforms serving 150K+ daily active users across 400+ stores under sub-100ms SLAs.
  * Performed memory leak analysis via Eclipse MAT; optimized G1GC parameters to increase peak transaction throughput by 30%.
  * Modernized Jenkins pipelines, reducing deployment turnaround from 14 days to under 48 hours.

---

<div align="center">
  <a href="https://shivambhaipatel.com/"><b>Explore Live Demos & Architecture Breakdowns on shivambhaipatel.com ↗</b></a>
  <br /><br />
  <img src="https://komarev.com/ghpvc/?username=shivambhaipatel&style=flat-square&color=0077B5" alt="Profile Views" />
</div>
