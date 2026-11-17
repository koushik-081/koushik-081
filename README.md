# Hi, I'm Koushik 👋

Backend & AI engineer who also ships Android apps. I build things that run on your own device, with no cloud, no tracking, and your data staying with you.

- 📱 Built **SplitPocket**, a full offline budgeting and bill-splitting app for Android, from an empty project to a signed release in 30+ commits
- 🧠 Building **Kosh**, an agentic RAG system that answers from your documents with clickable citations, running entirely on a local LLM
- 👁️ Built real-time **face recognition** in the browser with ArcFace, benchmarked against a classical SIFT baseline
- 🌱 Interested in: local-first AI, LLM agents and evaluation, and apps built for how India actually pays (UPI)

---

## ⭐ Featured

### 📱 [SplitPocket](https://github.com/koushik-081/SplitPocket): offline budgeting for how money moves in India

<p>
<img src="https://raw.githubusercontent.com/koushik-081/SplitPocket/main/docs/screenshots/home.png" width="200" alt="Home screen">&nbsp;
<img src="https://raw.githubusercontent.com/koushik-081/SplitPocket/main/docs/screenshots/group-split.png" width="200" alt="Group split">&nbsp;
<img src="https://raw.githubusercontent.com/koushik-081/SplitPocket/main/docs/screenshots/insights.png" width="200" alt="Insights">
</p>

Envelope budgeting and Splitwise-style bill splitting in one Android app, with **no internet permission at all**.

- **Auto-captures spending** from bank SMS *and* payment-app notifications (GPay, PhonePe, Paytm, CRED…), catching the small UPI payments banks never send an SMS for, with de-duplication across sources
- **Scan any UPI QR and pay** through your UPI app, with the expense filed into the right envelope automatically
- **Split bills** with people and groups (equal, exact or percentage), settle up, and send WhatsApp reminders
- **Upcoming bills and subscriptions** detected from repeating payments, plus a monthly recap, insights, a home-screen widget and PDF export
- **AES-256-GCM encrypted backups**, biometric app lock, and a signed release build

`Kotlin` `Jetpack Compose` `Material 3` `Room` `Biometric` `ML Kit code scanner`

---

### 🧠 [Kosh](https://github.com/koushik-081/kosh): agentic RAG that cites its sources

Ask questions across PDFs, web pages, GitHub repos and YouTube videos, and get answers that cite the exact page, line or timestamp.

- **LangGraph agent** that grades what it retrieved, rewrites the query when nothing helps, and refuses instead of guessing
- **Hybrid search** (pgvector + Postgres full-text, merged with Reciprocal Rank Fusion) plus cross-encoder reranking
- **Self-check** of every answer sentence against the sources, prompt-injection guard, and PII masking (Aadhaar, PAN, cards)
- **Measured, not guessed:** a 34-question evaluation compares the agent against plain RAG
- Runs on a **CPU-only laptop** with Ollama, so nothing leaves the machine

`Python` `LangGraph` `FastAPI` `PostgreSQL + pgvector` `Ollama` `Streamlit` `Phoenix`

---

### 👁️ [Face Recognition](https://github.com/koushik-081/face-recognisation): ArcFace in the browser

Point a webcam at someone; it names them and logs the time. Started as a SIFT keypoint experiment, which reached only **63.9% accuracy** on LFW because 439 of 1000 pairs had zero matches. Rebuilt on ArcFace embeddings to fix identity matching at the root.

`Python` `InsightFace` `ONNX Runtime` `FastAPI` `JavaScript`

---

### 🌫️ [AQI Reflex Agent](https://github.com/koushik-081/aqi-reflex-agent)

A classic simple-reflex AI agent that reads live pollutant data from OpenAQ sensors, computes AQI with India's CPCB formula, and classifies air quality.

`Python` `OpenAQ API`

---

## 🛠 Tech I work with

**Languages:** 
![Python](https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white)
![Kotlin](https://img.shields.io/badge/Kotlin-7F52FF?logo=kotlin&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript&logoColor=black)
![SQL](https://img.shields.io/badge/SQL-336791?logo=postgresql&logoColor=white)

**AI / ML:** 
![LangGraph](https://img.shields.io/badge/LangGraph-1C3C3C?logo=langchain&logoColor=white)
![Ollama](https://img.shields.io/badge/Ollama-000000?logo=ollama&logoColor=white)
![ONNX](https://img.shields.io/badge/ONNX%20Runtime-005CED?logo=onnx&logoColor=white)
![RAG](https://img.shields.io/badge/RAG-pgvector-4169E1)

**Backend:** 
![FastAPI](https://img.shields.io/badge/FastAPI-009688?logo=fastapi&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?logo=postgresql&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?logo=docker&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?logo=linux&logoColor=black)

**Android:** 
![Jetpack Compose](https://img.shields.io/badge/Jetpack%20Compose-4285F4?logo=jetpackcompose&logoColor=white)
![Room](https://img.shields.io/badge/Room-3DDC84?logo=android&logoColor=white)
![Material 3](https://img.shields.io/badge/Material%203-757575?logo=materialdesign&logoColor=white)

---

## 📫 Reach me

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?logo=linkedin&logoColor=white)](https://www.linkedin.com/in/saraswathulakoushik)
