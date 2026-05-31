# 🏙️ SmartSpace — The AI Real Estate Companion

> India's first unified AI-powered real estate platform. 12 specialised agents. One seamless experience.

[![Status](https://img.shields.io/badge/Status-Beta-00E5FF?style=flat-square)](https://github.com/SumitSonitechti/SmartSpace-The-AI-Real-Estate-Companion)
[![RERA](https://img.shields.io/badge/RERA-Compliant-00E676?style=flat-square)](#)
[![Made in India](https://img.shields.io/badge/Made%20in-India%20🇮🇳-FF9933?style=flat-square)](#)
[![License](https://img.shields.io/badge/License-MIT-BB86FC?style=flat-square)](LICENSE)

---

## ✨ Overview

SmartSpace combines **conversational AI**, **multimodal understanding** (images + voice in Hindi & English), **spatial intelligence**, and **predictive market analytics** into one platform built specifically for the Indian real estate market.

**Live Demo →** [GitHub Pages](https://sumitsonitechti.github.io/SmartSpace-The-AI-Real-Estate-Companion/)

---

## 🤖 The 12 AI Agents

| Agent | Role | Status |
|-------|------|--------|
| **Zara** | Conversational Core — Hindi + English voice, Hinglish NLP | ✅ Live |
| **Veda** | Market Intelligence — price forecasting, heatmaps, CMA | ✅ Live |
| **Arjun** | Commute & Location — isochrone mapping, multi-modal transit | ✅ Live |
| **Drishti** | Computer Vision — room detection, condition scoring | ✅ Live |
| **Kavya** | Listing Generator — 90-second AI listings from photos + voice | ✅ Live |
| **Neha** | Lifestyle Matchmaking — neighbourhood scoring, school ratings | ✅ Live |
| **Rishi** | Finance & EMI — live rates from 12+ banks, stamp duty calc | ✅ Live |
| **Siddhi** | Data Pipeline — 50K+ listings/day, deduplication, RERA sync | ✅ Live |
| **Vikram** | Legal & RERA Compliance — document review, red flag alerts | ◐ Beta |
| **Priya** | Rental Intelligence — yield estimation, agreement drafting | ◐ Beta |
| **Kiran** | Virtual Tours — 360° tours, AR staging, visit scheduling | ◐ Beta |
| **Aditya** | Investment Analytics — IRR modelling, infra impact forecast | 🔜 Q3 2026 |

---

## 🚀 Features

- 🎙️ **Voice Search** in Hindi, English & Hinglish (Sarvam AI)
- 🗺️ **City-Wide Price Heatmaps** with 5-year trend timelines
- 🏢 **Office-Home Matchmaking** with real commute calculations
- 📸 **90-Second AI Listings** from photos + voice notes
- ⚖️ **RERA Compliance** verification on every listing
- 💰 **Live EMI Calculator** across 12+ banks
- 🕶️ **Virtual Tours** with AI narration in Hindi/English
- 📈 **Investment ROI** modelling and price forecasting

---

## 🛠️ Tech Stack

### Frontend
- **Next.js 14** (React 18, SSR)
- **Tailwind CSS** + shadcn/ui
- **React-Leaflet** / Google Maps React
- **Recharts** for analytics visualization

### Backend
- **FastAPI** (Python) microservices
- **PostgreSQL** + PostGIS (geospatial)
- **Elasticsearch** (property search)
- **Pinecone** (semantic vector search)
- **Redis** (caching + sessions)
- **TimescaleDB** (price history)

### AI / ML
- **GPT-4 Turbo** — reasoning & NLP
- **Claude 3.5** — document analysis
- **Sarvam AI Bulbul V3** — Hindi TTS/ASR
- **YOLOv8** (custom) — computer vision
- **XGBoost + Neural Net** — AVM (property valuation)
- **Facebook Prophet** — price time-series forecasting

### Maps & Location
- **Google Maps Platform** — Distance Matrix, Directions, Places
- **PostGIS + QGIS** — advanced spatial queries
- **xMap.ai** — location intelligence & demographics

### Infrastructure
- **Google Cloud Platform** (Cloud Run, Cloud Storage, CDN)
- **Firebase Auth** (Phone OTP + JWT)
- **GitHub Actions** (CI/CD)
- **DataDog** (monitoring)

---

## 📁 Project Structure

```
SmartSpace-The-AI-Real-Estate-Companion/
├── index.html              # Main website (single-file, production-ready)
├── README.md               # This file
├── LICENSE                 # MIT License
├── .github/
│   └── workflows/
│       └── deploy.yml      # GitHub Pages auto-deploy
└── assets/                 # (future) images, icons, fonts
```

---

## 🏃 Quick Start

This repository currently ships as a **single-file HTML application** — no build step required.

```bash
# Clone the repository
git clone https://github.com/SumitSonitechti/SmartSpace-The-AI-Real-Estate-Companion.git
cd SmartSpace-The-AI-Real-Estate-Companion

# Open locally
open index.html
# or
npx serve .
```

---

## 🗺️ Roadmap

| Phase | Timeline | Status |
|-------|----------|--------|
| Phase 1 — Core MVP (search, maps, auth, data pipeline) | Q1 2026 | ✅ Done |
| Phase 2 — AI Voice & Listing Engine | Q2 2026 | 🔵 In Progress |
| Phase 3 — Spatial Intelligence Suite | Q3 2026 | ⏳ Upcoming |
| Phase 4 — Investment & Commercial RE | Q4 2026 | ⏳ Planned |
| Phase 5 — 3D Tours, AR, International Expansion | 2027 | 🔭 Vision |

---

## 💰 Pricing

| Plan | Price | Best For |
|------|-------|----------|
| Free | ₹0/mo | Casual browsers |
| Premium Buyer | ₹999/mo | Active homebuyers |
| Agent Pro | ₹9,999/mo | Real estate agents |
| Enterprise | Custom | Brokerages & developers |

---

## 🤝 Contributing

Contributions, issues, and feature requests are welcome!

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

---

## 📄 License

This project is licensed under the MIT License — see the [LICENSE](LICENSE) file for details.

---

## 📬 Contact

**SmartSpace Technologies Pvt. Ltd.**  
Bengaluru, Karnataka, India

- 🌐 Website: [smartspace.in](https://smartspace.in)
- 📧 Email: hello@smartspace.in
- 🐦 Twitter: [@SmartSpaceIN](https://twitter.com)
- 💼 LinkedIn: [SmartSpace](https://linkedin.com)

---

<p align="center">Built with ❤️ in India 🇮🇳</p>
