# Eman Musheer

**Aspiring AI Engineer & Data Science Student**

I build end-to-end AI and data systems for real-world problems, from collecting and validating data to evaluating models, deploying APIs and documenting the results honestly. My interests are multilingual AI, grounded generation, smart infrastructure and responsible machine learning.

---

## Featured Projects

### [Dalil AI · دليل](https://github.com/emanmusheer2008-glitch/dalil-ai) — Bilingual Grounded AI for Saudi Public-Service Information
**Status: Completed** · Python · FastAPI · Gemini API · scikit-learn · Arabic NLP

A deployed Arabic–English AI system that retrieves verified public-service evidence, generates grounded explanations, validates every response and links users back to the official source.

- **910** official public-service records from **11** Saudi government sources, with full provenance
- Multilingual hybrid retrieval with **action-aware reranking** (issue / renew / cancel / replace / inquire)
- **Grounded Gemini synthesis** with automatic **evidence validation**: citations, numbers and links are checked against the official text
- Partial answers, safe refusal, deterministic fallback and conversational follow-ups
- Held-out evaluation: Top-1 76.7% · Top-3 86.7% · MRR 0.829 · 93.0% confident-answer precision · **174 tests**
- FastAPI production backend on a lightweight runtime (~0.3 GB RAM, no PyTorch)

**[Live Web App](https://dalil-ai-production-tqj1.bolt.host/#/)** · **[Live API](https://emanmusheer2008.pythonanywhere.com)** · **[API Docs](https://emanmusheer2008.pythonanywhere.com/docs)** · **[Repository](https://github.com/emanmusheer2008-glitch/dalil-ai)**

---

### [WaterGuard AI Saudi](https://github.com/emanmusheer2008-glitch/waterguard-ai-saudi) — ML Water-Loss Decision Support for Smart Water Networks
**Status: Completed** · Python · scikit-learn · pandas · FastAPI · Streamlit

A machine-learning decision-support system that analyses hydraulic time-series data, scores water-loss risk, explains each alert and suggests where to inspect first. It is a Saudi-focused prototype evaluated on international benchmark data.

- Evaluated on the **BattLeDIM L-Town** international leakage-detection benchmark (not Saudi utility data)
- **60 engineered features**, chronological train / validation / test split, Random Forest
- Held-out test: **Precision 94.24%** · **ROC-AUC 0.9501** · **PR-AUC 0.8806** (threshold chosen on validation only)
- Risk alerts, alert explanations, sensor inspection guidance, CSV/XLSX analysis and exports
- FastAPI inference API and interactive web and Streamlit interfaces · **95 tests**

**[Live Web App](https://waterguard-ai-produc-qien.bolt.host)** · **[Live API Docs](https://waterguard-ai-saudi-production.up.railway.app/docs)** · **[Repository](https://github.com/emanmusheer2008-glitch/waterguard-ai-saudi)**

---

## Other Projects

| Project | Summary |
|---|---|
| [Gulf Electricity Transition Tracker](https://github.com/emanmusheer2008-glitch/gulf-electricity-transition) | Data analysis of how the six GCC countries' electricity mix is changing, with a check of Saudi and UAE clean-energy targets. Python · pandas · matplotlib · open data (CC BY 4.0) |

## Competitions & Applied Work

| Competition | Role and work |
|---|---|
| **NASA International Space Apps Challenge 2026** | **Team Lead, OrbitFlame AI.** Challenge: *Flame in Freefall*: AI-powered exploration and visualisation of microgravity combustion research. |
| **TrafficFlowBench 2026, IEEE Big Data Cup** | Built a multi-task traffic-data pipeline (state reconstruction, queue forecasting, origin–destination / path-flow estimation); verified public leaderboard score **0.47045**. |

## Selected Credentials

- **Microsoft Applied Skills:** Develop a Generative AI Chat App Using the Microsoft Foundry SDK
- **OpenAI Academy:** Design and Build Agentic Systems
- **One Million AI Prompters:** Dubai Centre for AI / Dubai Future Foundation

## Technical Skills

| Area | Tools and methods |
|---|---|
| Programming & data | Python, pandas, NumPy, Jupyter, Git & GitHub |
| Machine learning | scikit-learn, Random Forest, time-series feature engineering, model evaluation, threshold selection |
| AI & NLP | multilingual information retrieval, RAG / grounded generation, Gemini API, Arabic text processing |
| Backend & deployment | FastAPI, REST APIs, Streamlit, PythonAnywhere, Railway |
| Practice | automated testing (pytest), reproducible evaluation, technical documentation, responsible AI |

## Interests

Arabic NLP · AI Engineering · Data Science · Grounded & Responsible AI · Smart Infrastructure · Sustainability

## Contact

- **Email:** [eman.musheer2008@gmail.com](mailto:eman.musheer2008@gmail.com)
- **LinkedIn:** [linkedin.com/in/eman-musheer](https://www.linkedin.com/in/eman-musheer)

---

<sub>Each repository documents its methodology, evaluation, limitations and how to run it.</sub>
