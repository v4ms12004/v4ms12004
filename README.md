<div align="center">

# Vamsi Doddapaneni

**CS Graduate · University of Kansas · May 2026**

*AI/ML · Full-Stack · Real-Time Systems · Cybersecurity*

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/v4ms12004)
[![Email](https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:NeerajVamsiDoddapaneni@gmail.com)
[![Devpost](https://img.shields.io/badge/Devpost-003E54?style=for-the-badge&logo=devpost&logoColor=white)](https://devpost.com/vamsi-d-2004)

</div>

---

## 👋 About Me

I'm a Computer Science graduate from the University of Kansas (GPA: 3.60) with concentrations in **AI/ML** and **Cybersecurity**. I build things that work under real constraints tight deadlines, imbalanced datasets, cross-platform quirks, and live production environments.

My work spans ML research pipelines, real-time voice infrastructure, full-stack web apps, and blockchain systems. Two of my recent projects won awards at competitive events.

---

## 🏆 Award-Winning Projects

### 🚨 [CCAD AI - Emergency Dispatch Intelligence Platform](https://devpost.com/software/firstresponse-ai-4us081)
**🥇 MLH Best Use of ElevenLabs - HackKU 2026**

> AI-powered 911 dispatch platform built in 24 hours. Replaces manual dispatch workflows with real-time AI incident structuring, live P2P voice between field units, and a tactical command dashboard.

**What I built:**
- **Backend** - FastAPI + SQLite with incident CRUD, zone management, AI suggestion flow, and a dispatch parser that converts spoken 911 calls into structured incident records via Google Gemini 1.5 Flash
- **WebRTC Mesh Voice** - P2P audio between all units with glare avoidance (lexicographic unit ID comparison), pre-attached muted mic pattern for zero-latency PTT, and dual-pipeline audio capture (WebRTC + MediaRecorder off the same `getUserMedia` stream)
- **Frontend** - Next.js 16 + React 19 + Tailwind 4 with 5 role-based interfaces, Zustand session persistence, React Query server state, and a Leaflet tactical map with AI-suggested hazard zones
- **Cross-platform** - iOS Safari transcription fallback, autoplay unlock workflow, mobile MIME handling (`audio/mp4` vs WebM Opus), self-signed HTTPS cert for iPhone PTT testing

`FastAPI` `Next.js 16` `React 19` `WebRTC` `Gemini API` `ElevenLabs` `SQLite` `Zustand` `Leaflet.js` `Tailwind CSS`

---

### 📊 [Financial Fraud Detection - ML Research](https://github.com/v4ms12004/financial-fraud-detection-ml)
**🥉 3rd Place - KDSCon 2026 Poster Presentation, Kansas State University**
*Sponsored by the KDSC Industry Advisory Board · Community Data Labs*

> Solo semester-long research project building a production-grade fraud detection framework on the PaySim dataset (6M+ transactions, 0.13% fraud rate).

**Results:**
| Metric | Score |
|--------|-------|
| AUPRC | **0.9988** |
| Recall | **100%** - all 1,654 fraud cases caught |
| Precision | **98.2%** - only 30 false alarms on 123,580 test transactions |

**Key contributions:**
- Leakage-safe temporal XGBoost pipeline with TimeSeriesSplit cross-validation and 15+ behavioral panel features engineered from past-only account history
- Discovered a **generalizability threshold collapse at 30% training window** - Random Forest's perfect AUPRC (1.0000) shown to reflect simulator overfitting, a substantive research finding
- Built an interactive results dashboard (Chart.js + vanilla JS) with animated feature importance visualizations, deployed to GitHub Pages
- Presented research poster at KDSCon Spring 2026 at Kansas State University

`Python` `XGBoost` `scikit-learn` `Pandas` `NumPy` `Matplotlib` `Chart.js` `GitHub Pages`

---

## 🔧 Other Projects

### 🛡️ [PhishGuard AI - Email Phishing Detection Platform](https://github.com/v4ms12004/PhishGuard-AI)
Full-stack phishing detection platform classifying email text and URLs in real-time using TF-IDF + Logistic Regression. Features Supabase-backed authentication, persistent scan history dashboard, and cloud deployment on Render + Vercel.

`FastAPI` `React` `scikit-learn` `Supabase` `Postgres` `Vercel` `Render`

### ⛓️ [BlockBadge - Dual-Chain Decentralized Credentialing](https://devpost.com/software/block-badge-0lkzud)
Dual-chain dApp replacing paper certificates with tamper-proof on-chain credentials. ERC-721 NFT badges on Ethereum Sepolia + BLK token micro-payments on the XRP Ledger, with metadata permanently stored on IPFS.

`Solidity` `ERC-721` `Hardhat` `ethers.js` `xrpl.js` `IPFS` `Pinata` `Ethereum Sepolia`

---

## 🛠️ Skills

**Languages**
`Python` `Java` `JavaScript/TypeScript` `SQL` `C/C++` `C#`

**AI/ML**
`XGBoost` `scikit-learn` `TensorFlow` `PyTorch` `Pandas` `NumPy` `Matplotlib` `Gemini API`

**Web & Frameworks**
`React` `Next.js` `FastAPI` `Flask` `Tailwind CSS` `WebRTC` `WebSockets` `Zustand` `React Query` `Supabase` `Docker`

**Cybersecurity & Systems**
`Wireshark` `Kali Linux` `Network Security` `Secure Coding` `SMTP/IMAP` `Android Reverse Engineering`

**Tools**
`Git/GitHub` `Linux/Unix` `Leaflet.js` `Chart.js` `Hardhat` `ElevenLabs API`

---

## 📚 Education

**University of Kansas** - B.S. Computer Science, GPA: 3.60/4.00 *(Expected May 2026)*
Concentrations: Artificial Intelligence & Machine Learning · Certificate in Cybersecurity
Dean's List: Fall 2023, Fall 2025

---

<div align="center">

*Open to full-time SWE / ML roles*

</div>