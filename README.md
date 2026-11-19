# 🛡️ CypherLog — Multi-Branch Security Monitoring & AI Incident Response

> **A real-time Security Operations Center (SOC) command dashboard featuring AI-powered threat triage, blockchain-anchored log verification, and cross-branch attack correlation.**

CypherLog is an enterprise security intelligence platform designed for monitoring distributed branch office networks. It aggregates real-time system and authentication telemetry, correlates multi-vector attacks across remote locations, automatically groups raw alerts into prioritized security incidents with SLA countdowns, and provides blockchain-backed immutable audit logs for regulatory compliance.

---

## 📖 About the Project

### 🎯 Problem Statement
Distributed enterprises with dozens of remote branch offices (banks, retail chains, logistics hubs) face severe security visibility blind spots. Branch networks generate overwhelming volumes of disconnected log noise, making it difficult for centralized SOC teams to detect coordinated low-and-slow attacks, verify that audit trails haven't been tampered with locally, and respond before critical SLAs lapse.

### 💡 The Solution
CypherLog unifies distributed branch telemetry into a centralized, reactive SOC command center. The platform automatically groups low-level telemetry into actionable security incidents, leverages AI reasoning to generate executive threat briefings and remediation runbooks, detects cross-branch attack campaigns executing simultaneously across geographically dispersed sites, and cryptographically anchors every log entry onto an immutable private blockchain ledger for tamper-evident chain-of-custody.

### 🌟 Core Value Proposition
- **Cross-Branch Threat Correlation**: Identifies distributed brute-force and credential stuffing campaigns targeting multiple branch locations at once.
- **AI-Powered Incident Response**: Instant LLM-driven incident analysis, severity classification, and one-click mitigation checklists.
- **Blockchain-Anchored Integrity**: Cryptographic SHA-256 block-chaining ensures audit logs cannot be altered, overwritten, or deleted by attackers.
- **Real-Time SOC Observability**: Live SVG geospatial branch topology, active telemetry feeds, and sub-minute SLA response tracking.

---

## ✨ Features

- 🗺️ **Live Distributed Branch Network Map** — Real-time interactive map visualizing remote branch infrastructure, log ingestion velocity, and localized threat levels.
- 🤖 **AI-Powered Incident Response & Triage** — LLM-driven incident summarization, threat analysis, risk scoring, and automated mitigation runbook generation.
- 🔗 **Blockchain-Anchored Tamper-Proof Audit Trail** — Cryptographic hashing and private ledger verification guaranteeing chain-of-custody for every security log and administrative action.
- ⚡ **Cross-Branch Threat Correlation** — Multi-tenant correlation engine detecting coordinated attacks (e.g., credential stuffing, distributed brute-force) across multiple branch locations simultaneously.
- ⏱️ **Real-Time SLA Tracking** — Live countdown timers tracking MTTR (Mean Time to Respond) and MTTA (Mean Time to Acknowledge) per severity tier.
- 📊 **Interactive Telemetry Visualizations** — Time-series threat distribution, attack severity heatmaps, and metric breakdowns powered by Recharts.
- 👥 **Role-Based Access Control (RBAC)** — Tailored views and permission gates for Security Analyst, SOC Admin, and External Compliance Auditor.
- 📑 **One-Click Compliance Reporting** — Instant export of audit-ready compliance summaries and chain-of-custody records.

---

## 🛠️ Tech Stack

| Layer | Technology |
|---|---|
| **Frontend Framework** | React 18 + Vite 5 |
| **Styling & Icons** | Tailwind CSS + Lucide React |
| **Data Visualization** | Recharts v2 |
| **Cloud & Deployment** | Firebase (Hosting & Analytics) |
| **Cryptographic Hashing** | SHA-256 private ledger simulation |

---

## 📁 Folder Structure

```
CypherLog/
├── src/
│   ├── App.jsx                 # Core SOC command center & telemetry views
│   └── main.jsx                # React application entrypoint
├── public/                     # Static assets, branding, and icons
├── .env.example                # Sample environment configuration
├── firebase.json               # Firebase deployment configuration
├── package.json                # Dependencies and npm scripts
├── vite.config.js              # Vite configuration
└── README.md                   # Project documentation
```

---

## 🚀 How to Install and Run

### Prerequisites
- [Node.js](https://nodejs.org/) (v18+) & `npm`

### 1. Clone the Repository
```bash
git clone https://github.com/karthiban3333-maker/CypherLog.git
cd CypherLog
```

### 2. Install Dependencies
```bash
npm install
```

### 3. Configure Environment Variables
```bash
cp .env.example .env
```

### 4. Start Development Server
```bash
npm run dev
```
Open `http://localhost:5173` in your browser.

### 5. Build for Production
```bash
npm run build
npm run preview
```

### 6. Deploy to Firebase Hosting
```bash
npm run build
npx firebase deploy --only hosting
```

---

## 📸 Screenshots

> _Add screenshots here._

---

## 📄 License

This project is private and proprietary. All rights reserved.

---

## 👨‍💻 Author

**Karthiban A** — [Kode Prime](https://github.com/karthiban3333-maker)
