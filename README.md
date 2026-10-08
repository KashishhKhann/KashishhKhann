# Hi, I'm Kashish

AI/ML engineer in Dublin building LLM-powered tools that hold up in production: RAG and knowledge-graph pipelines, explainable triage systems, and the APIs and messaging around them. MSc in Artificial Intelligence (Dublin Business School).

![Python](https://img.shields.io/badge/Python-3572A5?style=flat&logo=python&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat&logo=fastapi&logoColor=white)
![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=flat&logo=streamlit&logoColor=white)
![Twilio](https://img.shields.io/badge/Twilio-F22F46?style=flat&logo=twilio&logoColor=white)
![LLMs](https://img.shields.io/badge/LLMs-000000?style=flat&logo=openai&logoColor=white)
![RAG](https://img.shields.io/badge/RAG-10a37f?style=flat&logoColor=white)
![FAISS](https://img.shields.io/badge/FAISS-4B32C3?style=flat&logoColor=white)
![Neo4j](https://img.shields.io/badge/Neo4j-018bff?style=flat&logo=neo4j&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-4DB33D?style=flat&logo=mongodb&logoColor=white)
![SQLite](https://img.shields.io/badge/SQLite-003B57?style=flat&logo=sqlite&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat&logo=githubactions&logoColor=white)
![Julia](https://img.shields.io/badge/Julia-9558B2?style=flat&logo=julia&logoColor=white)

## Featured: [Hearthline](https://github.com/KashishhKhann/Hearthline)

**AI-assisted inbox triage for property managers.** Every resident message (email, web form, SMS, WhatsApp) is scored, routed and answered on the resident's own channel, and anything dangerous reaches a human within minutes.

[![CI](https://github.com/KashishhKhann/Hearthline/actions/workflows/ci.yml/badge.svg)](https://github.com/KashishhKhann/Hearthline/actions/workflows/ci.yml)

<a href="https://github.com/KashishhKhann/Hearthline"><img src="https://raw.githubusercontent.com/KashishhKhann/Hearthline/main/docs/images/dashboard.png" alt="Hearthline dashboard" width="720"></a>

What's new since the hackathon version:

- **Explainable triage:** a 0 to 100 urgency score with a written reason for every point, and three tiers (human / AI draft / auto-reply). The LLM writes the text; rules decide urgency, so a model can never make a leak "not urgent".
- **Twilio integration:** residents text or WhatsApp in; critical issues text the on-call manager (`Reply ACK 3F9A2C`), and if nobody answers in 10 minutes the next person gets a phone call. Signed webhooks, STOP handling and consent-aware replies.
- **FastAPI + SQLite backend** with contractor dispatch by SMS, SendGrid email in and out, and optional Twilio Verify login codes.
- **Hardened:** fixed keyword bugs that sent 35 of 92 threads to the wrong tier, closed an XSS hole, added rate limiting, prompt-injection fencing and a dry-run mode.
- **150 tests, CI on every push, Docker**, an evaluation tool for precision / recall per tier, and a README with nine architecture and flow diagrams.

## What else I'm building

| Project | What it is |
| --- | --- |
| **[medical-rag-system](https://github.com/KashishhKhann/medical-rag-system)** | End-to-end medical RAG pipeline with FAISS, Neo4j knowledge graphs and BioClinicalBERT over clinical notes |
| **[LLM-Trace-and-Cost-Studio](https://github.com/KashishhKhann/LLM-Trace-and-Cost-Studio)** | Tracing and cost tracking for LLM calls: FastAPI, Streamlit, SQLite, Docker |
| **[MiniBioBERT](https://github.com/KashishhKhann/MiniBioBERT)** | A compact BioBERT-style biomedical language model in Julia |
| **[Leafy](https://github.com/KashishhKhann/Leafy)** | AI-based virtual personal assistant |

## Stats

<p align="center">
<img src="https://github-readme-stats.vercel.app/api?username=KashishhKhann&show_icons=true&theme=dark&hide_border=true&bg_color=0d1117&title_color=58a6ff&icon_color=58a6ff&text_color=c9d1d9" height="160" alt="GitHub stats" />
<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=KashishhKhann&layout=compact&theme=dark&hide_border=true&bg_color=0d1117&title_color=58a6ff&text_color=c9d1d9" height="160" alt="Top languages" />
</p>

## Links

- Portfolio: [portfolio-two-jade-63.vercel.app](https://portfolio-two-jade-63.vercel.app/)
- LinkedIn: [kashish-khan-ai](https://www.linkedin.com/in/kashish-khan-ai/)
- Open to junior AI/ML engineering roles in Ireland, and to collaborating on GraphRAG and LLM tooling projects. Reach out on LinkedIn.
