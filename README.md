<h1 align="center">Hi, I'm Abhishek Kalagurki</h1>

<h3 align="center">
  Software Engineer | C++ | Systems | Backend Development
</h3>

<p align="center">
  E&amp;E Undergraduate at NITK Surathkal
</p>

<p align="center">
  <a href="https://leetcode.com/u/ab-kg/">
    <img src="https://img.shields.io/badge/LeetCode-1500%2B%20Solved-orange?style=for-the-badge&logo=leetcode&logoColor=white" />
  </a>
  <a href="https://codeforces.com/profile/ab-kg">
    <img src="https://img.shields.io/badge/Codeforces-Profile-blue?style=for-the-badge&logo=codeforces&logoColor=white" />
  </a>
  <a href="https://www.linkedin.com/in/abhishek-s-kalagurki-48ab39345/">
    <img src="https://img.shields.io/badge/LinkedIn-Connect-blue?style=for-the-badge&logo=linkedin&logoColor=white" />
  </a>
  <a href="https://drive.google.com/file/d/118nXYQV5EqKscw71mrZcDQhSoPbSNU7M/view?usp=sharing">
    <img src="https://img.shields.io/badge/Resume-View-red?style=for-the-badge&logo=googledrive&logoColor=white" />
  </a>
</p>

---

## About Me

E&amp;E undergraduate at NITK Surathkal, working mostly in C++, Python, and backend engineering.

- Solved **1,500+ problems** on LeetCode, focused on data structures and algorithms.
- Interested in systems programming, operating systems, and computer architecture.
- Most of my project work sits at the intersection of LLM orchestration and retrieval — building agents that cite their sources rather than hallucinate them.
- Enjoy working close to the metal: C++, networking, MQTT, threading.

## Tech Stack

<p align="center">
  <img src="https://skillicons.dev/icons?i=cpp,c,python,js,ts,fastapi,flask,react,postgres,docker,git,linux" />
</p>

**Languages** C/C++ · Python · JavaScript · TypeScript · SQL
**Backend** FastAPI · Flask · LangGraph · LangChain · SQLAlchemy · Alembic
**Frontend** React · Vanilla JS · Vite
**Databases** PostgreSQL · MongoDB Atlas
**Tools** Docker · Git · CMake · MQTT

---

## Featured Projects

### [Fieldnotes — AI Research Agent](https://github.com/ab-kg/RESEARCH-AGENT)

[![Live Demo](https://img.shields.io/badge/demo-Live%20on%20Railway-success?style=for-the-badge)](https://research-agent2-production.up.railway.app/)

*Python · TypeScript · LangGraph · FastAPI · React · PostgreSQL · Docker · Railway*

Turns a question into a source-linked briefing, where every factual claim is traceable to a numbered source.

- Built a four-stage LangGraph state machine (`plan → search → assess → write`) with a bounded conditional loop that guarantees termination and caps each run at **2–3 LLM calls**.
- Designed retrieval grounding and **prompt-injection defenses**: evidence is passed to the model explicitly marked as untrusted data, with inline `[S1]–[S8]` citation IDs the writer must reuse rather than fabricate.
- Containerized a **multi-stage Docker build** where Node compiles the React/TypeScript frontend and Python serves it alongside the API on a single origin — eliminating CORS preflights and a second web service.
- Deployed to **Railway** with automated GitHub deploys, fail-fast configuration validation, and database connection-wait logic.
- Implemented JWT + Argon2 authentication and PostgreSQL persistence for user accounts and research history via FastAPI, SQLAlchemy 2.0, and Alembic.

### [Legal Agent — Hybrid GraphRAG](https://github.com/ab-kg/LEGAL-AI)

*Python · JavaScript · FastAPI · MongoDB Atlas · Gemini · Groq · SentenceTransformers*

Grounded contract analysis combining vector search with an extracted Knowledge Graph.

- Designed a hybrid retrieval architecture combining **SentenceTransformers vector search** with a dynamically extracted Knowledge Graph, so answers cite both similar passages and connected entities.
- Architected a FastAPI backend using **Gemini** for structured Knowledge Graph extraction and **Groq** for low-latency conversational Q&A.
- Engineered a PDF ingestion pipeline for chunking, embedding generation, and indexing of vectors and graph relationships in MongoDB Atlas.
- Built a Vanilla JS frontend with multi-session chat, Chart.js contract-classification dashboards, and Vis.js graph visualization.

### [Autonomous Fan System](https://github.com/ab-kg/CNProject)

*Python · Flask · Threading · MQTT · SSE*

An IoT ceiling fan driven by an explainable AI policy engine.

- Built a publish-subscribe message broker with REST APIs and **Server-Sent Events** for real-time telemetry.
- Built an AI decision engine with temperature modeling, occupancy detection, and explainable scoring.
- Delivered a Flask dashboard with live telemetry, fan controls, and AI-or-manual mode switching, plus an offline simulation console requiring no external broker.

---

## LeetCode

<p align="center">
  <a href="https://leetcode.com/u/ab-kg/">
    <img src="https://leetcard.jacoblin.cool/ab-kg?theme=dark&font=Baloo&ext=heatmap" alt="LeetCode Stats" />
  </a>
</p>

<p align="center">
  <b>1500+ Problems Solved</b>
</p>

<p align="center">
  <a href="https://leetcode.com/u/ab-kg/">View LeetCode Profile</a>
</p>

---

## Connect With Me

<p align="center">
  <a href="mailto:abhishekkalagurki@gmail.com">Email</a> •
  <a href="https://leetcode.com/u/ab-kg/">LeetCode</a> •
  <a href="https://codeforces.com/profile/ab-kg">Codeforces</a> •
  <a href="https://www.linkedin.com/in/abhishek-s-kalagurki-48ab39345/">LinkedIn</a> •
  <a href="https://github.com/ab-kg">GitHub</a>
</p>

<p align="center">
  <i>Always learning. Always building.</i>
</p>
