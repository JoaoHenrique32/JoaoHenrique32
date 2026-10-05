<div align="center">

# Hi, I'm João Henrique 👋

**Aspiring Data Engineer & AI Developer** · Python · PySpark · Data Pipelines · GenAI · IoT
Building data-driven systems — from sensors and APIs to pipelines, dashboards and AI agents.

[![LinkedIn](https://img.shields.io/badge/LINKEDIN-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/joão-henrique526b11278)
[![Gmail](https://img.shields.io/badge/GMAIL-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:SEU-EMAIL)
[![GitHub](https://img.shields.io/badge/GITHUB-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/JoaoHenrique32)

🟢 **Actively looking for internship opportunities in Data Engineering and AI**

</div>

---

## About Me

I'm a Computer Science student with hands-on experience building **data pipelines, AI applications, REST APIs and IoT systems**. I like projects that cover the whole path of data: capturing it at the source, moving and transforming it reliably, and turning it into answers — through dashboards, analytics or AI agents.

My goal is to build a career in **Data Engineering** and **Artificial Intelligence**.

- 🎯 Focus: **Data Engineering · GenAI / RAG · Computer Vision · IoT**
- 🛠️ Recent work: Medallion pipeline on Databricks, Text-to-SQL agent, RAG assistant, facial-recognition smart lock
- 📍 Brazil · Open to remote

---

## Tech Stack

**Languages**

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=postgresql&logoColor=white)
![C++](https://img.shields.io/badge/C++-00599C?style=flat-square&logo=cplusplus&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)

**Data Engineering**

![PySpark](https://img.shields.io/badge/PySpark-E25A1C?style=flat-square&logo=apachespark&logoColor=white)
![Databricks](https://img.shields.io/badge/Databricks-FF3621?style=flat-square&logo=databricks&logoColor=white)
![SQLite](https://img.shields.io/badge/SQLite-003B57?style=flat-square&logo=sqlite&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![MQTT](https://img.shields.io/badge/MQTT-660066?style=flat-square&logo=mqtt&logoColor=white)

**AI & Computer Vision**

![LLMs](https://img.shields.io/badge/LLMs_&_RAG-412991?style=flat-square&logo=openai&logoColor=white)
![Gemini](https://img.shields.io/badge/Gemini_API-8E75B2?style=flat-square&logo=googlegemini&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikitlearn&logoColor=white)
![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?style=flat-square&logo=opencv&logoColor=white)
![MediaPipe](https://img.shields.io/badge/MediaPipe-0097A7?style=flat-square&logo=google&logoColor=white)
![DeepFace](https://img.shields.io/badge/DeepFace-1F6FEB?style=flat-square)

**Backend & Frontend**

![Flask](https://img.shields.io/badge/Flask-000000?style=flat-square&logo=flask&logoColor=white)
![Django](https://img.shields.io/badge/Django-092E20?style=flat-square&logo=django&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![React](https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB)
![Tailwind](https://img.shields.io/badge/Tailwind-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white)

**IoT & Tools**

![Arduino](https://img.shields.io/badge/NodeMCU_/_Arduino-00979D?style=flat-square&logo=arduino&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)
![Pytest](https://img.shields.io/badge/Pytest-0A9EDC?style=flat-square&logo=pytest&logoColor=white)

---

## Featured Projects

### 🎬 [CineData Analytics — Medallion Pipeline](https://github.com/JoaoHenrique32/projeto-cinedata-analytics)
Data engineering pipeline that builds a cinematographic catalog using the **Medallion Architecture** (Bronze → Silver → Gold) on **Databricks**, enriched with exchange-rate data from the Brazilian Central Bank API.

- **Bronze:** raw ingestion into append-only Delta tables, preserving full history
- **Silver:** data cleaning, resilient type casting, time-series imputation with window functions, handling of inconsistent delimiters
- **Gold:** star schema for BI analytics **and** a RAG-ready document table for LLMs
- Orchestrated with Databricks Workflows (DAG), focused on fault tolerance, idempotency and governance
- **Stack:** PySpark · Delta Lake · Unity Catalog · Databricks Workflows · Python

### 🤖 [CineData Text-to-SQL Agent](https://github.com/JoaoHenrique32/rocketlab-cinedata-agent)
AI agent that turns **business questions in Portuguese into SQL**, runs them against a read-only database and returns the answer with the premises, result table and the executed query.

- Multi-layer SQL safety: regex checks, AST validation with `sqlglot`, read-only engine mode and timeouts
- Response caching and daily quota control to minimize API calls
- Business rules embedded in the prompt (data-quality decisions)
- **14/14 correct answers** against the official test cases
- **Stack:** Python · LLM via OpenRouter · SQLite · sqlglot · pytest

### 🧠 [Corporate Assistant with RAG](https://github.com/JoaoHenrique32/desafio-tecnico-moura)
Intelligent assistant that answers questions about company documents using **Retrieval-Augmented Generation**, grounding every answer in the retrieved sources to avoid hallucinations.

- TF-IDF cosine-similarity retrieval over `.md`/`.txt` documents
- Constrained generation with Google Gemini, citing sources
- Audit log of questions, answers and sources in SQLite; exposed as a REST API
- **Stack:** Python · Flask · Gemini API · scikit-learn · SQLite

### 🚪 [SmartLock IA — Facial Recognition Door Lock](https://github.com/JoaoHenrique32/full_smartlock)
Complete IoT access-control system: a camera recognizes registered faces and releases the door in real time, with an admin app to approve new registrations. Runs fully local, without cloud dependencies.

- **Hardware:** NodeMCU ESP8266 + relay, programmed in C++ (PlatformIO)
- **AI engine:** DeepFace (VGG-Face) + OpenCV
- **Messaging:** MQTT broker (EMQX in Docker) secured with **mutual TLS**
- **Backend:** Python/Django · **Admin app:** Flutter with real-time notifications

### 🕶️ [AR/VR + Computer Vision — Real People as 3D Avatars](https://github.com/JoaoHenrique32/ar-vr-cv-projeto)
Real-time pipeline: camera → face detection → 2D-to-3D mapping → WebSocket broadcast → avatars rendered in the browser or a VR headset.

- Multi-face detection with stable identity tracking across frames
- Smooth interpolation and graceful handling of lost detections
- **Stack:** Python · Flask-SocketIO · OpenCV · MediaPipe · Three.js · A-Frame/WebXR

### 🗑️ Smart Trash Bin — Real-Time Fill-Level Dashboard
IoT trash bin that **measures the fill level** with sensors and **sends the data to a dashboard** for monitoring.

- End-to-end flow: **sensor → transmission → storage → visualization**
- **Skills:** IoT · Sensors · Data ingestion · Dashboards

### 🔐 [Sample Flask Auth](https://github.com/JoaoHenrique32/sample-flask-auth)
Authentication API connected to a database, containerized with Docker Compose.

- **Stack:** Python · Flask · Docker · relational database

> 💡 More projects: [Cinebox](https://github.com/JoaoHenrique32/cinebox-rocketlab2026-2) (FastAPI + React catalog of 95k+ films) · [Task Flask CRUD](https://github.com/JoaoHenrique32/task-flask-crud) · [Daily Diet](https://github.com/JoaoHenrique32/daily-diet)

---

## What I'm Working Towards

- 🔄 Building reliable **ETL/ELT pipelines** and lakehouse architectures
- 🗄️ Data modeling, orchestration and data quality
- 🤖 Applying **GenAI, RAG and agents** on top of well-modeled data
- 👁️ Using **Computer Vision** and IoT data in real-world systems

---

## GitHub Stats

<div align="center">


![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=JoaoHenrique32&layout=compact&theme=github_dark&hide_border=true)

</div>

---

<div align="center">

📫 **Let's connect!** Open to opportunities in **Data Engineering** and **AI**.

</div>
