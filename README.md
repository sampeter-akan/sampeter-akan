# Samuel Peter

**DevOps & Cloud | Infrastructure Engineer**

With over **19 years** as Principal Manager in critical national infrastructure at the Transmission Company of Nigeria, I bring deep expertise in high-reliability systems, operational excellence, and secure network environments.

I am currently pursuing an **MSc in DevOps & Cloud Computing** at IU International University of Applied Sciences, where I have achieved strong results:

- **DevOps** – **96% (Distinction)**
- **Advanced Research Methods** – **90% (Distinction)**
- **Cloud Computing Project** – **84% (Good)**

My GitHub showcases practical CI/CD mastery, cloud-native ML deployment, and evidence-based research on wireless security as well and infrastructure modernization.

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

**Why this project matters:** It bridges my 19+ years of grid operations experience with modern cloud and machine learning technologies.

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
