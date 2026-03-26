# Brandevour

An **agentic AI-powered sales & marketing system** designed to go beyond content generation — enabling intelligent campaign strategy, automated execution, and real-world sales simulation.

---

## 🚀 What is Brandevour?

Brandevour is built around a simple idea:

> AI shouldn’t just generate content — it should **strategize, evaluate, and execute marketing decisions.**

The system combines **multi-agent orchestration**, **automation workflows**, and **voice-enabled interaction** to simulate real sales and marketing processes end-to-end.

---

## ⚡ Core Features

### 🧠 Agentic Marketing & Sales System
- Multi-agent workflows orchestrated using **LangGraph**
- Agents collaborate to **plan, iterate, and evaluate** campaigns
- Moves from single-response AI → **decision-driven pipelines**

---

### 📢 Campaign Generation & Execution
- Generates **structured marketing campaigns**
- Iteratively refines scripts until optimized
- Platform-aware content generation for:
  - Instagram
  - LinkedIn

---

### 🤝 Autonomous Posting (Human-in-the-Loop)
- End-to-end workflow:
  **Strategy → Content → Iteration → Approval → Publishing**
- Automated posting to **Instagram & LinkedIn**
- Includes **human-in-the-loop approval** before publishing

---

### 🎯 Lead Intelligence
- AI-driven **lead scoring with reasoning**
- Helps prioritize high-value prospects
- Simulates real-world sales decision-making

---

### 🦈 Voice-Enabled Shark Tank Mode
- Interactive pitch simulation powered by **Sarvam AI**
- Features:
  - Real-time **voice interaction**
  - AI-generated objections & questions
  - Natural banter and pressure scenarios
- Outputs:
  - 💰 Investment verdict (Invest / Reject)
  - 📊 Structured feedback on pitch quality

---

### 🎙️ Voice Interaction Layer
- Voice-based input for seamless interaction
- Enables conversational workflows
- Powered by **Sarvam AI**

---

## 🧩 Architecture Overview

Brandevour follows a **multi-agent, workflow-driven architecture**:

- **Agent Orchestration**: LangGraph  
- **Automation Pipelines**: n8n  
- **LLMs**: Open-source models  
- **Voice Layer**: Sarvam AI  
- **Frontend**: Next.js (TypeScript)  
- **Backend**: Python (Flask/FastAPI)  

---

## 📋 Project Structure

```

Brandeuver/
├── Backend/
│   ├── integrated_brandeuver.py
│   └── **init**.py
├── marketing-frontend/
│   ├── app/
│   │   ├── dashboard/
│   │   │   ├── campaigns/
│   │   │   ├── instagram/
│   │   │   ├── leads/
│   │   │   ├── pitch/
│   │   │   └── pitch-lab/
│   │   ├── globals.css
│   │   ├── layout.tsx
│   │   └── page.tsx
│   ├── components/
│   ├── hooks/
│   └── lib/
├── requirements.txt
├── Procfile
├── render.yaml
└── Scripts:
├── app.py
├── main.py
├── pitch_generator.py
├── linkedin_campaign.py
└── voice_input.py

````

---

## 🛠️ Tech Stack

### Frontend
- Next.js (TypeScript)
- Tailwind CSS

### Backend
- Python (Flask / FastAPI)

### AI & Automation
- LangGraph (multi-agent orchestration)
- n8n (workflow automation)
- Open-source LLMs
- Sarvam AI (voice interaction)

---

## 🚀 Getting Started

### Backend
```bash
python -m venv mvenv
# Activate environment
# Windows:
mvenv\Scripts\activate
# macOS/Linux:
source mvenv/bin/activate

pip install -r requirements.txt
python Backend/integrated_brandeuver.py
````

### Frontend

```bash
cd marketing-frontend
npm install
npm run dev
```

---

## 🌐 Deployment

* Configured for deployment on **Render**
* See `render.yaml` and `Procfile` for setup

---

## 🏆 Achievement

🥇 **1st Place – GENAI FORGE Hackathon (VNR VJIET)**
Built among 300+ participants in collaboration with **SmartBridge & NASSCOM**


