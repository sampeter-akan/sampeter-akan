# Samuel Peter

**DevOps & Cloud Engineer | Critical Infrastructure & Reliability**

With over 20+ years as Principal Manager in critical national infrastructure at the Transmission Company of Nigeria, I bring deep expertise in high-reliability systems, operational excellence, and secure environments.

I am currently pursuing an **MSc in DevOps & Cloud Computing** at IU International University of Applied Sciences, with strong results:

- DevOps – **96% (Distinction)**
- Advanced Research Methods – **90% (Distinction)**
- Cloud Computing Project – **84% (Good)**

My GitHub showcases practical CI/CD pipelines, cloud-native ML deployment, infrastructure automation, and domain-driven projects such as **GridPulse 330** (an interactive SCADA/EMS-style contingency simulation for 330 kV transmission systems).

📂 **[View Personal Portfolio Website](https://samuelpeter.dev)**

---

## 💼 Featured Projects

### ⚡GridPulse 330 — DevOps Power Grid Telemetry & Contingency Architecture

[![Live Demo](https://img.shields.io/badge/Demo-gridpulse--330.vercel.app-00DC82?style=for-the-badge&logo=vercel&logoColor=white)](https://gridpulse-330app-szws.vercel.app/)
[![GitHub Repo](https://img.shields.io/badge/Repository-sampeter--akan%2Fgridpulse--330app-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/sampeter-akan/gridpulse-330app)
[![Tech Stack](https://img.shields.io/badge/Stack-React_19_|_TypeScript_|_Tailwind_CSS_v4_|_Vite_8-3178C6?style=for-the-badge&logo=typescript&logoColor=white)](https://github.com/sampeter-akan/gridpulse-330app)

<p align="center">
  <img src="https://raw.githubusercontent.com/sampeter-akan/gridpulse-330app/main/gridpulse-330app.png" alt="GridPulse 330 Architecture" width="100%" />
</p>

An enterprise-grade **SCADA/EMS Telemetry & Contingency Console** designed for National Control Center (NCC) power dispatchers, bridging meteorological forecasting with real-time electrical grid stability.

#### 🎯 Problem Solved
Bulk 330 kV Extra-High-Voltage (EHV) networks face sudden catastrophic collapse during severe convective storms:
- **Turbine Rotor Overspeed ($f > 51.00\text{ Hz}$):** Sudden industrial load rejections cause mechanical torque to exceed electrical load, accelerating synchronous rotors past statutory ceilings.
- **The Ferranti Effect ($V > 340.0\text{ kV}$):** Long, lightly loaded bulk transmission links accumulate massive shunt capacitive charging ($Q_{\text{charging}}$), producing destructive overvoltage surges.

#### 🛠️ Key Capabilities & Engineering Highlights
- 📡 **Doppler Radar Horizon Integration:** Anticipates atmospheric storm fronts and lightning threats in real-time, predicting physical line trips before they occur.
- 🚨 **Statutory Dual-Threshold Engine:** Triggers instantaneous visual and acoustic alarms when 330 kV bus voltages ($>340\text{ kV}$) or grid frequencies ($>51.00\text{ Hz}$) breach safety limits.
- ⚡ **Double-Circuit Corridor Protection:** Monitors transmission lines (e.g., Ikeja West – Oshogbo) with ANSI 87L differential protection and dynamic $N-1$ thermal transfer modeling.
- 🎛️ **Closed-Loop Dispatch Playbook:** Instant operator restoration controls — switch in **150 MVAR Shunt Reactors**, ramp generation down (**-400 MW**), and execute synchrocheck auto-reclose.
- 📜 **Sub-Second SCADA Sequence of Events (SOE):** Immutable event audit stream capturing transient waveforms, relay activations, and operator commands for root-cause analysis (RCA).

#### 🧰 Tech Stack
- **Frontend & UI:** React 19, TypeScript, Tailwind CSS v4, Lucide Icons
- **Tooling & Build:** Vite 8, Bun / Node.js
- **Mathematical Modeling:** Swing equations, Ferranti capacitance derivations, governor droop simulation
- **Deployment:** Vercel Edge CI/CD Pipeline

👉 ***[Explore Live Production Console](https://gridpulse-330app-szws.vercel.app/)*** • ***[View Codebase & Architecture Docs](https://github.com/sampeter-akan/gridpulse-330app)***

---

### 🎮 VAULT FIVE — Real-Time Multiplayer Game | Cloud-Native Systems & DevOps

**Handshake AI Skills Studio × OpenAI Multiplayer Game Challenge**

[![Play Live Game](https://img.shields.io/badge/PLAY-LIVE_GAME-00C853?style=for-the-badge&logo=vercel&logoColor=white)](https://vault-five-umber.vercel.app/)
[![GitHub Repository](https://img.shields.io/badge/GitHub-Source_Code-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/sampeter-akan/vault-five)
[![Project Documentation](https://img.shields.io/badge/Docs-Architecture_%26_Operations-0078D4?style=for-the-badge&logo=readthedocs&logoColor=white)](https://github.com/sampeter-akan/vault-five#architecture)

[![CI](https://github.com/sampeter-akan/vault-five/actions/workflows/ci.yml/badge.svg)](https://github.com/sampeter-akan/vault-five/actions/workflows/ci.yml)
[![Production Health](https://github.com/sampeter-akan/vault-five/actions/workflows/production-health.yml/badge.svg)](https://github.com/sampeter-akan/vault-five/actions/workflows/production-health.yml)

[![React](https://img.shields.io/badge/React_19-20232A?style=flat-square&logo=react&logoColor=61DAFB)](https://react.dev/)
[![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)](https://www.typescriptlang.org/)
[![Vite](https://img.shields.io/badge/Vite_6-646CFF?style=flat-square&logo=vite&logoColor=white)](https://vite.dev/)
[![Supabase](https://img.shields.io/badge/Supabase-3FCF8E?style=flat-square&logo=supabase&logoColor=white)](https://supabase.com/)
[![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)](https://www.postgresql.org/)
[![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white)](https://github.com/sampeter-akan/vault-five/actions)
[![Vercel](https://img.shields.io/badge/Vercel-000000?style=flat-square&logo=vercel&logoColor=white)](https://vercel.com/)

> **Project overview:** VAULT FIVE is a deployed, browser-based multiplayer vault-cracking game demonstrating real-time state synchronization, server-authoritative game logic, identity-aware authorization, serverless architecture, and DevOps automation.
>
> Players create or join private rooms using a four-character code, compete through three timed rounds, earn points, and attempt to unlock a fictional **$1,000,000 jackpot**. The jackpot is strictly an in-game reward with no real cash value, wagering, or payout.

#### 🖥️ Interactive Game Experience

<p align="center">
  <a href="https://vault-five-umber.vercel.app/">
    <img src="https://raw.githubusercontent.com/sampeter-akan/vault-five/main/docs/images/vault-five-landing-page.png" alt="VAULT FIVE multiplayer game landing page" width="85%" />
  </a>
</p>

<p align="center">
  <em>Figure 1 — Responsive landing page for hosting or joining multiplayer rooms. Click the image to launch the live game.</em>
</p>

<p align="center">
  <img src="https://raw.githubusercontent.com/sampeter-akan/vault-five/main/docs/images/vault-five-the-rules.png" alt="VAULT FIVE game rules and player onboarding" width="75%" />
</p>

<p align="center">
  <em>Figure 2 — Player instructions and timed round structure.</em>
</p>

<p align="center">
  <img src="https://raw.githubusercontent.com/sampeter-akan/vault-five/main/docs/images/vault-five-cracked-vault.png" alt="VAULT FIVE winning screen and leaderboard" width="85%" />
</p>

<p align="center">
  <em>Figure 3 — Successful vault unlock, winner announcement, and final leaderboard.</em>
</p>

#### 🎯 Engineering Challenge

The central engineering problem was coordinating independent browser sessions without allowing each client to determine its own game state.

The solution combines **Supabase Realtime communication**, persistent PostgreSQL state, and a **server-authoritative Edge Function** that validates player actions, manages rounds, calculates scores, and determines the winner.

This separates user-interface rendering from trusted game-state transitions.

#### 🚀 Core Features

- 🎮 **Real-Time Multiplayer:** Create and join private game rooms across different browsers and devices.
- 🔐 **Invisible Authentication:** Supabase anonymous authentication enables gameplay without a visible registration process.
- ⏱️ **Synchronized Rounds:** Server-managed deadlines coordinate Discover, Deduce, and Final Vault.
- 🏆 **Fair Scoring:** Server-side answer verification, score calculation, winner selection, and leaderboard generation.
- 📡 **Realtime Updates:** WebSocket-based broadcasts, complemented by authoritative state polling to recover from missed updates.
- 🔄 **Replay:** Players can restart the experience after completing a game.
- 📱 **Responsive Interface:** Browser-based gameplay without a separate installation.

#### 🏗️ Cloud Architecture

| Layer | Technology | Engineering Responsibility |
|---|---|---|
| Frontend | React 19, TypeScript, Vite 6 | Responsive gameplay and state rendering |
| Hosting | Vercel | Static frontend deployment |
| Identity | Supabase Auth | Anonymous player sessions and JWT identity |
| Backend | Supabase Edge Functions | Authoritative game logic and validation |
| Realtime | Supabase Realtime | WebSocket-based state notifications |
| Persistence | PostgreSQL | Rooms, players, rounds, submissions, and scores |
| Authorization | JWT checks and PostgreSQL RLS | Room-scoped access and data protection |
| CI | GitHub Actions | Static checks, automated tests, and production build |
| Operations | GitHub Actions synthetic checks | Production endpoint verification and retained results |

📐 **[Explore Architecture, State Lifecycle & Security Design](https://github.com/sampeter-akan/vault-five#architecture)**

#### ⚙️ DevOps, CI/CD & Production Reliability

**✅ Continuous Integration**

The GitHub Actions CI workflow runs on pull requests and pushes to `main`:

- Reproducible dependency installation using `npm ci`
- TypeScript static checks
- Automated architectural smoke tests
- Production Vite build verification

[![View CI Pipeline](https://img.shields.io/badge/View-CI_Pipeline-2088FF?style=for-the-badge&logo=githubactions&logoColor=white)](https://github.com/sampeter-akan/vault-five/actions/workflows/ci.yml)

**✅ Production Synthetic Monitoring**

A separate GitHub Actions workflow runs scheduled, non-mutating production checks every hour and supports manual execution.

It verifies:
- The deployed frontend returns HTTP `200`.
- The protected game API rejects unauthenticated access with HTTP `401`.
- Probe durations and results are recorded.
- Synthetic result artifacts are retained for 14 days.

The initial manually triggered production health workflow passed both checks.

These probes verify specific endpoint behaviors; they are **not** a substitute for authenticated end-to-end gameplay testing, latency percentiles, or a formal availability SLO.

[![View Production Health](https://img.shields.io/badge/View-Production_Health-00897B?style=for-the-badge&logo=githubactions&logoColor=white)](https://github.com/sampeter-akan/vault-five/actions/workflows/production-health.yml)

**✅ Deployment & Operations**

- GitHub-integrated Vercel deployment
- Environment-variable and backend-secret separation
- Production troubleshooting using Vercel and Supabase logs
- Documented release checks, incident triage, and rollback considerations

[![Operations Runbook](https://img.shields.io/badge/Read-Operations_Runbook-455A64?style=for-the-badge&logo=markdown&logoColor=white)](https://github.com/sampeter-akan/vault-five/blob/main/docs/OPERATIONS.md)

#### 🛡️ Security & Reliability Engineering

- **Server-authoritative state:** Clients submit actions, not trusted scores or victory declarations.
- **Identity-aware access:** JWT validation and room membership checks enforce API permissions.
- **Row Level Security:** PostgreSQL policies support protected data access.
- **Secret isolation:** Vault combination and service credentials are kept outside the frontend.
- **State recovery:** Periodic authoritative state reads help clients recover when Realtime notifications are missed.
- **Incident-driven improvements:** Multiplayer testing exposed authentication, synchronization, feedback, and winner-attribution issues that were investigated and corrected.

#### 📚 Engineering Lessons

VAULT FIVE reinforced several important principles:

1. **Distributed state must have a trusted authority.** Browser clients cannot independently decide round outcomes.
2. **Realtime delivery needs a recovery mechanism.** Broadcast notifications are complemented by state reconciliation.
3. **Security boundaries must be explicit.** Authentication, authorization, validation, and secrets belong in trusted backend services.
4. **Deployment is only one part of delivery.** Automated checks, incident investigation, and operational documentation improve maintainability.
5. **Reliability claims require evidence.** Production probes, multiplayer walkthroughs, and architectural tests serve different verification purposes.

#### 🔭 Future Engineering Enhancements

- 📊 API request latency distributions and error-rate dashboards
- 🔔 Automated failure notifications and alert routing
- 🧪 Multi-client load testing and concurrency verification
- 🛡️ Abuse protection, rate limiting, and further security hardening
- 🔄 Automated release gating and isolated staging environments

*These are planned improvements, not currently verified production capabilities.*

#### 🧑‍💻 Skills Demonstrated

**Real-Time Systems • Distributed State Management • Cloud-Native Development • Serverless Architecture • TypeScript • PostgreSQL • WebSockets • CI/CD • GitHub Actions • Production Monitoring • Security Engineering • Incident Response • Reliability Engineering**

<p align="center">
  <a href="https://vault-five-umber.vercel.app/">
    <img src="https://img.shields.io/badge/🎮_PLAY-VAULT_FIVE-00C853?style=for-the-badge&logo=vercel&logoColor=white" alt="Play VAULT FIVE" />
  </a>
  <a href="https://github.com/sampeter-akan/vault-five">
    <img src="https://img.shields.io/badge/💻_EXPLORE-SOURCE_CODE-181717?style=for-the-badge&logo=github&logoColor=white" alt="Explore VAULT FIVE source" />
  </a>
</p>

👉 **[Play VAULT FIVE](https://vault-five-umber.vercel.app/)** • **[View Complete Engineering Case Study](https://github.com/sampeter-akan/vault-five)**

---

### 🎬 Movies API — Microservices Research & Development Project
**MSc DevOps & Cloud Computing Coursework**

I designed and developed a **contract-first microservices-based Movies API** to demonstrate end-to-end API engineering, automated testing, and reproducible performance evaluation.

**Key Highlights:**
- OpenAPI v3 contract-first design with full CRUD, RBAC, and error handling
- Comprehensive testing (unit, integration, contract) + k6 load testing
- GitHub Actions CI/CD pipeline with reproducible artifacts
- Performance baselines (P50 < 100ms, P95 < 500ms)

**Skills Demonstrated:** Microservices architecture, OpenAPI, performance engineering, CI/CD, technical documentation.

📂 **[View Repository](https://github.com/sampeter-akan/movies-api)**

---

### 🚀 Credit Loan Calculator — Enterprise CI/CD Pipeline
**MSc DevOps Module | Grade: 96% (Distinction)**

I built a full-stack web application with a complete enterprise-grade CI/CD pipeline.

**Key Highlights:**
- Automated build, test, and deploy using Jenkins, Maven, Selenium, JUnit, and GitHub Actions
- Security scanning with Dependabot and structured logging
- Agile/Scrum methodology with Jira + GitHub Copilot

**Skills Demonstrated:** CI/CD orchestration, automated testing, security practices, DevOps tooling.

📂 **[View Repository](https://github.com/sampeter-akan/credit-loan-calculator)**

---

### 🎓📶 Advanced Research Methods — Distinguished Research Proposal
🔐 **An Empirical Study of IEEE 802.11 & WPA3 Adoption Gaps and Feature Prioritization in Campus & Public Wi-Fi Hotspots**

**MSc Course | Grade: 90% (Distinction)**

I designed an empirical research proposal to deliver **evidence-based prioritization** of IEEE 802.11 features and WPA3 capabilities for dense, multi-AP environments.

**Research Scope:**
- ⚡ Performance benchmarking in high-density scenarios
- 🚶 Roaming & handover resilience for latency-sensitive applications
- 🛡️ Security evaluation — WPA2-to-WPA3 migration and management frame protection

**Key Deliverable:** Prioritized deployment roadmap for secure cloud-edge networking and zero-trust access.

📂 **[View Repository](https://github.com/sampeter-akan/empirical_research_proposal_paper)**  
📄 **[Full PDF Proposal](https://github.com/sampeter-akan/empirical_research_proposal_paper/blob/main/docs/DLMARM01-01-ARM2.pdf)**

---

### ☁️ HomeStayGrid ML Recommender Feed — AWS Cloud ML Deployment
**MSc Cloud Computing Project | Grade: 84% (Good / 2.0)**

I designed and deployed a **cloud-native ML recommender system** for power grid operations. The prototype analyzes grid assets and generates prioritized risk-based maintenance recommendations to support predictive reliability management.

**Built With:**
- Python 3.11, scikit-learn, pandas, joblib
- FastAPI (REST API for real-time recommendations)
- Docker
- AWS (ECR, S3, Elastic Beanstalk, EC2, IAM, CloudWatch)

**Key Highlights:**
- Trained tabular ML model for outage risk ranking and maintenance prioritization
- Developed and exposed a `/recommend` REST API endpoint
- Containerized and deployed the service to AWS Elastic Beanstalk
- Comprehensive documentation and operational considerations

**Why this project matters:** It bridges my 20+ years of grid operations experience with modern cloud and machine learning technologies.

📂 **[View Repository](https://github.com/sampeter-akan/homestaygrid_ml_recommender_feed)**  
📄 **[Project Report](https://github.com/sampeter-akan/homestaygrid_ml_recommender_feed/blob/main/docs/Task2_Project_Report_HomeStayGrid.md)**

---

## 🎓 Education

- **MSc DevOps & Cloud Computing** – IU International University of Applied Sciences, Germany (Ongoing)  
  Current GPA: **80.5%**

- **BSc (Hons) Computing & IT** – University of Derby, UK (2020)  
  **First Class Honours**

---

## 📈 Professional Journey

**Principal Manager – Grid System Operations**  
Transmission Company of Nigeria (19+ years)

- Managed high-voltage transmission networks with **99.9%+ reliability**
- Led 24/7 grid operations, incident response, and emergency management
- Oversaw Energy Management Systems (EMS) and NERC compliance
- Currently focused on modernizing traditional infrastructure with cloud, DevOps, and AI/ML solutions

---

## 📫 Contact Me

- **Email:** samuelakanimo@hotmail.com
- **LinkedIn:** [linkedin.com/in/samuel-peter-5117223b](https://www.linkedin.com/in/samuel-peter-5117223b)

**Let’s connect** if you’re building resilient, secure, and intelligent systems where operational excellence meets modern cloud and automation.
