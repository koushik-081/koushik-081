<img src="https://capsule-render.vercel.app/api?type=waving&height=180&color=0:5b2a86,50:a83279,100:ff9f1c&text=Koushik%20Saraswathula&fontColor=ffffff&fontSize=42&fontAlignY=35&desc=chai-powered%20backend%20%26%20AI%20engineer&descAlignY=55&animation=fadeIn" width="100%" alt="Koushik Saraswathula"/>

<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=500&size=20&pause=1200&color=FF9F1C&center=true&vCenter=true&width=600&lines=Debugging+since+chai+went+cold...;Building+RAG+agents+that+cite+their+sources;Tracking+where+my+salary+goes+(bad+news);Teaching+webcams+to+recognise+faces;Checking+if+the+air+is+still+bad+(it+is)" alt="Typing intro"/>
</p>

# Hi, I'm Koushik 👋

Backend & AI engineer. I build things that run on *your* device: no cloud, no tracking, no "please sign in to continue".

**What I've been up to:**

- 💸 **Built an app to find out where my salary goes.** Bad news. [SplitPocket](https://github.com/koushik-081/SplitPocket) reads my bank SMS and UPI notifications, files every rupee into an envelope, and splits the Goa trip bill so my friends can't pretend they forgot. *Kotlin · Jetpack Compose · Room*
- 🧠 **Taught an AI to stop making things up.** [Kosh](https://github.com/koushik-081/kosh) answers from your PDFs, repos and YouTube videos, and cites the exact page, line or timestamp. If it can't find proof, it says "I don't know". Rare, even among humans. *LangGraph · pgvector · Ollama*
- 👀 **Gave a webcam trust issues.** [Face Recognition](https://github.com/koushik-081/face-recognisation) names whoever walks in. Version 1 used SIFT and was right 63.9% of the time, basically a coin with confidence. Version 2 uses ArcFace and actually knows who you are. *InsightFace · ONNX · FastAPI*
- 🌫️ **Built a bot that tells me the air is bad.** In India. Groundbreaking. [AQI Reflex Agent](https://github.com/koushik-081/aqi-reflex-agent) pulls live sensor data and does the official CPCB maths so you can sigh with accuracy. *Python · OpenAQ*

**Fun facts:** all of it was built on a CPU-only laptop · my expense app has no internet permission (it can't leak what it can't send) · I've lost more arguments to the Android Gradle plugin than to people.

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

## 🐍 My contributions, being eaten

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/koushik-081/koushik-081/output/snake-dark.svg"/>
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/koushik-081/koushik-081/output/snake.svg"/>
  <img alt="Snake eating my contribution graph" src="https://raw.githubusercontent.com/koushik-081/koushik-081/output/snake.svg"/>
</picture>

---

## 📫 Reach me

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?logo=linkedin&logoColor=white)](https://www.linkedin.com/in/saraswathulakoushik)


<img src="https://capsule-render.vercel.app/api?type=waving&height=100&section=footer&color=0:ff9f1c,50:a83279,100:5b2a86" width="100%" alt=""/>
