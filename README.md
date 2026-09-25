# 🚀 Enterprise Simulation Engine

> **Simulate. Analyze. Decide.** — Run thousands of business simulations for pricing, staffing, investments, logistics, and expansion before real-world execution.

![Status](https://img.shields.io/badge/status-active-success)
![Python](https://img.shields.io/badge/python-3.11-blue)
![React](https://img.shields.io/badge/react-18-61dafb)
![FastAPI](https://img.shields.io/badge/FastAPI-0.109-009688)
![License](https://img.shields.io/badge/license-MIT-green)

---

## 🎯 Overview

**Enterprise Simulation Engine** is an AI-powered decision-support platform that allows businesses to simulate complex scenarios before committing real-world resources. Using **Monte Carlo Simulation** and **Reinforcement Learning**, it delivers data-backed insights for critical business decisions.

Whether you're a **startup founder** deciding on pricing, an **HR manager** planning staffing, or a **CFO** evaluating investments — this engine gives you **confidence through simulation**.

### 💡 Powered By

- 🎲 **Monte Carlo Simulation** — probability distributions for uncertain outcomes
- 🧠 **Reinforcement Learning** — optimal strategy discovery via Q-Learning
- 🤖 **Google Gemini API** — natural language to structured scenarios
- ⚡ **FastAPI** — blazing-fast async backend
- 🎨 **React + TailwindCSS** — modern, responsive UI

---

## ✨ Features

### 🎲 Monte Carlo Simulation Engine
- Run 10,000+ parallel simulations in seconds
- Get profit distributions, confidence intervals, best/worst case scenarios
- Visualize risk with histograms and percentile charts

### 🧠 Reinforcement Learning Engine
- Q-Learning based decision optimizer
- Learns optimal pricing/staffing/investment policy over episodes
- Training curve visualization with convergence tracking

### 🤖 Natural Language Scenarios
- Describe your business scenario in plain English or Hindi
- Gemini API converts it to structured parameters
- Instant simulation trigger without manual config

### 📊 Five Business Scenario Templates

| Scenario | Use Case |
|----------|----------|
| 💰 **Pricing** | Find optimal price point for maximum profit |
| 👥 **Staffing** | Balance team size vs. productivity vs. cost |
| 📈 **Investment** | Predict ROI for marketing, R&D, or capex |
| 🚚 **Logistics** | Optimize delivery time vs. operational cost |
| 🌍 **Expansion** | Evaluate new market/city entry viability |

### 📈 Rich Visualizations
- Profit distribution curves (histogram + KDE)
- Monte Carlo percentile bands
- RL training convergence graph
- Multi-scenario comparison charts
- Confidence interval visualization

### 💬 Interactive Chat Interface
- Talk to the simulator in natural language
- Get AI-powered recommendations instantly
- Persistent conversation history

---

## 🛠️ Tech Stack

### Backend
![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat&logo=fastapi&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat&logo=numpy&logoColor=white)
![SQLAlchemy](https://img.shields.io/badge/SQLAlchemy-D71F00?style=flat)
![SQLite](https://img.shields.io/badge/SQLite-003B57?style=flat&logo=sqlite&logoColor=white)

| Tech | Purpose |
|------|---------|
| **FastAPI** | Async REST API framework |
| **NumPy** | Vectorized simulation math |
| **SQLAlchemy** | ORM for SQLite database |
| **Google Gemini API** | Natural language understanding |
| **Pydantic** | Data validation & serialization |
| **Uvicorn** | ASGI server |

### Frontend
![React](https://img.shields.io/badge/React-61DAFB?style=flat&logo=react&logoColor=black)
![Vite](https://img.shields.io/badge/Vite-646CFF?style=flat&logo=vite&logoColor=white)
![Tailwind](https://img.shields.io/badge/Tailwind-06B6D4?style=flat&logo=tailwindcss&logoColor=white)
![Recharts](https://img.shields.io/badge/Recharts-22B5BF?style=flat)

| Tech | Purpose |
|------|---------|
| **React 18** | UI library |
| **Vite** | Lightning-fast build tool |
| **TailwindCSS** | Utility-first styling |
| **Recharts** | Beautiful data visualization |
| **React Router** | Client-side routing |
| **Axios** | HTTP client |

### Database
- **SQLite** — lightweight, zero-config (perfect for practice & demo)
- Easily swappable with PostgreSQL for production use

---

## 🚀 Quick Start

### Prerequisites
- **Python** 3.11 or higher
- **Node.js** 18 or higher
- **Gemini API Key** — [Get it free here](https://aistudio.google.com/app/apikey)

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/vishakha2121/enterprise-simulation-engine.git
cd enterprise-simulation-engine

cd backend
python -m venv venv

# Windows
venv\Scripts\activate

# macOS/Linux
source venv/bin/activate

pip install -r requirements.txt
cp .env.example .env
# Add your GEMINI_API_KEY inside .env

uvicorn app.main:app --reload

cd frontend
npm install
cp .env.example .env
npm run dev