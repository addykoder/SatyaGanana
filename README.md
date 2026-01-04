# 🇮🇳 CensusOne: Digital Census & Beneficiary Verification System
> **Theme:** Hack4Delhi | **Track:** Smart Governance / Open Innovation

![Build Status](https://img.shields.io/badge/Build-Passing-brightgreen)
![Platform](https://img.shields.io/badge/Platform-PWA%20%7C%20Web-blue)
![Compliance](https://img.shields.io/badge/Compliance-DPDP%20Act%202023-orange)
![License](https://img.shields.io/badge/License-MIT-green)

---

## 🚨 The Problem
Traditional census methods in India suffer from three critical failures:
1.  **Data Latency:** It takes years to digitize and analyze manual records.
2.  **Ghost Beneficiaries:** Lack of real-time validation leads to resource leakage.
3.  **Low Trust:** Centralized databases are opaque and prone to manipulation.

## 💡 The Solution: CensusOne
**CensusOne** is an offline-first PWA (Progressive Web App) designed for field enumerators and government administrators. It unifies **AI-driven anomaly detection** with a **Blockchain-simulated ledger** to ensure that every record is unique, verified, and immutable.

### 🌟 Key Features
* **📱 Offline-First Enumerator PWA:** Works in low-network zones; syncs when online.
* **🤖 AI Verification Layer:** Instantly flags inconsistencies (e.g., age vs. photo mismatch, duplicate entries) using Python-based logic.
* **🔗 Immutable Audit Trail:** Every verification step is hashed and stored (simulating a private blockchain ledger) to prevent data tampering.
* **📍 Geo-Fencing:** Auto-tags household locations to prevent fake bulk entries from a single location.
* **📊 Live Authority Dashboard:** Real-time heatmaps of population density and verification status.

---

## 🏗️ System Architecture
We utilize a 5-Layer approach to ensure data integrity from collection to analytics.

*(Paste the screenshot of your Mermaid Architecture Diagram here)*

### 🛠️ Tech Stack
| Component | Technology | Description |
| :--- | :--- | :--- |
| **Frontend** | React.js + Vite | Lightweight PWA for enumerators |
| **Styling** | Tailwind CSS | Rapid, responsive UI |
| **Backend** | Node.js + Express | API handling and business logic |
| **Database** | MongoDB | Primary data storage (Ledger simulation) |
| **AI Engine** | Python (Flask/FastAPI) | Anomaly detection & consistency checks |
| **Security** | JWT + AES-256 | Data encryption & Role-based access |

---

## 🚀 Getting Started (Local Setup)

To run the prototype locally, follow these steps:

### Prerequisites
* Node.js (v18+)
* MongoDB (Local or Atlas URL)
* Python (3.9+)

### Installation
1. **Clone the repository**
   ```bash
   git clone [https://github.com/yourusername/census-one.git](https://github.com/yourusername/census-one.git)
   cd census-one
