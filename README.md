<h1 align="center">Hi, I'm Mukul 👋</h1>

<p align="center">
  <strong>AI/ML Engineer building RAG applications, agent workflows, and Python automation.</strong>
</p>

<p align="center">
  Product Engineer — AI/ML at TCS · 1+ year of industry experience · Gurugram, India
</p>

<p align="center">
  <a href="https://portfolio-r6c8-seven.vercel.app"><img src="https://img.shields.io/badge/Portfolio-2F705E?style=for-the-badge" alt="Portfolio"></a>
  <a href="https://www.linkedin.com/in/mukul-s-8s677"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"></a>
  <a href="mailto:mmukul8791@gmail.com"><img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"></a>
</p>

---

## About me

I'm an AI/ML engineer at TCS, where I've built an NLP-based defect similarity search application and Python automation for XML-to-Excel and conditional XML/Excel generation.

My personal projects explore RAG for incident resolution, agent workflows with human approval, and scheduled report automation. I focus on retrieval quality, clear execution boundaries, input validation, and understandable results.

Currently open to **AI Engineer, ML Engineer, and Generative AI Engineer** opportunities at product-focused teams.

## Featured work

### ResolveIQ — AI-Powered Incident Resolution Platform

[![CI](https://github.com/vishwakarmamukul8791-code/resolveiq-platform/actions/workflows/ci.yml/badge.svg)](https://github.com/vishwakarmamukul8791-code/resolveiq-platform/actions/workflows/ci.yml)
![Status](https://img.shields.io/badge/status-live-2F705E)

A full-stack incident-resolution platform that helps support engineers investigate enterprise knowledge without trusting weak retrieval or unsupported model output.

**What I engineered**

- Hybrid retrieval using BM25 with pgvector in production and FAISS locally, fused through Reciprocal Rank Fusion
- Retrieval-aware confidence gating that safely abstains when evidence is insufficient
- Source-grounded Gemini answers with document, page, and location citations
- JWT authentication, role-based authorization, engineer workflows, and protected admin operations
- Durable PostgreSQL, pgvector, and private Storage persistence through Supabase
- FastAPI backend, React frontend, Docker deployment, and GitHub Actions validation

**Why it is production-minded**

- Out-of-domain questions return low confidence with no misleading sources
- Accounts, sessions, history, documents, chunks, and embeddings survive backend redeploys
- CI validates backend tests, frontend lint/build, and the production Docker image

<p align="center">
  <img src="https://github.com/vishwakarmamukul8791-code/resolveiq-platform/raw/main/docs/screenshots/resolveiq-support-rag.png" width="760" alt="ResolveIQ grounded RAG answer with citations">
</p>

<p>
  <a href="https://resolveiq-five.vercel.app"><img src="https://img.shields.io/badge/Try_Live_Product-000000?style=for-the-badge&logo=vercel&logoColor=white" alt="Try ResolveIQ"></a>
  <a href="https://github.com/vishwakarmamukul8791-code/resolveiq-platform"><img src="https://img.shields.io/badge/View_Repository-181717?style=for-the-badge&logo=github&logoColor=white" alt="ResolveIQ repository"></a>
</p>

### PayPilot AI — Agentic Payment Orchestration Sandbox

A full-stack, simulated payment application that turns natural-language requests into controlled workflows. It uses fake money; backend policy checks retain authority over every payment.

**What I built**

- LangGraph orchestration with explicit workflow state and human-in-the-loop approval
- Optional Gemini intent parsing with a deterministic parser for supported payment requests
- Execution-time revalidation of balances, limits, destinations, and approval requirements
- Idempotency keys, transactional ledger updates, and paired debit/credit entries for internal transfers
- Session-isolated accounts, payees, bills, and visible agent decision traces

**Stack:** Python, FastAPI, LangGraph, React, SQLAlchemy, SQLite / PostgreSQL, Pytest.

[View PayPilot AI repository](https://github.com/vishwakarmamukul8791-code/paypilot-ai) · [Architecture](https://github.com/vishwakarmamukul8791-code/paypilot-ai/blob/main/docs/ARCHITECTURE.md)

### ReportFlow — Scheduled Report Automation

A full-stack application that fetches public JSON API data on a schedule, transforms it with pandas, and generates downloadable Excel or PDF reports.

**What I built**

- Cron-based scheduling with APScheduler, retry/backoff, and run history
- JSON data transformation and Excel/PDF report generation
- Optional email delivery and Slack notifications
- JWT authentication and per-user isolation for jobs, runs, and report downloads
- URL and IP validation, response-size limits, and output escaping to reduce ingestion and report-generation risks

**Stack:** Python, FastAPI, pandas, APScheduler, React, PostgreSQL, Alembic, Docker.

[View ReportFlow repository](https://github.com/vishwakarmamukul8791-code/reportflow)

## How I engineer

- **Grounded by design:** evidence, citations, and safe abstention are system requirements
- **Measured, not assumed:** retrieval quality and failure cases are evaluated before trusting output
- **End-to-end development:** connect data processing, APIs, persistence, and user interfaces
- **Built to evolve:** clear boundaries, tests, CI, and documented trade-offs keep systems maintainable

## Core toolkit

`Python` · `Java` · `SQL` · `FastAPI` · `React` · `PostgreSQL` · `Supabase` · `Docker` · `GitHub Actions`

`RAG` · `Gemini` · `LangGraph` · `BM25` · `pgvector` · `FAISS` · `RRF` · `pandas` · `Pytest`

---

<p align="center">
  <strong>Interested in reliable AI systems and product engineering?</strong><br>
  <a href="https://portfolio-r6c8-seven.vercel.app">Portfolio</a> ·
  <a href="https://www.linkedin.com/in/mukul-s-8s677">LinkedIn</a> ·
  <a href="https://leetcode.com/u/Mukul863024/">LeetCode</a> ·
  <a href="mailto:mmukul8791@gmail.com">Email</a>
</p>

