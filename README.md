<h1 align="center">Hi, I'm Mukul 👋</h1>

<p align="center">
  <strong>AI/ML Product Engineer building reliable RAG, retrieval, and model-adaptation systems.</strong>
</p>

<p align="center">
  Product Engineer — AI/ML at TCS · 1+ year of industry experience · Gurugram, India
</p>

<p align="center">
  <a href="https://portfolio-r6c8-seven.vercel.app"><img src="https://img.shields.io/badge/Portfolio-2F705E?style=for-the-badge" alt="Portfolio"></a>
  <a href="https://resolveiq-five.vercel.app"><img src="https://img.shields.io/badge/ResolveIQ_Live-15221F?style=for-the-badge&logo=vercel&logoColor=white" alt="ResolveIQ live application"></a>
  <a href="https://www.linkedin.com/in/mukul-s-8s677"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"></a>
  <a href="mailto:mmukul8791@gmail.com"><img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"></a>
</p>

---

## I build AI systems that know their limits

I work across retrieval pipelines, LLM applications, model-assisted workflows, evaluation, backend APIs, and production deployment. My focus is not just generating fluent output—it is building systems that retrieve the right evidence, expose their evidence path through citations, and fail safely when the evidence is weak.

Currently open to **AI Engineer, ML Engineer, and Generative AI Engineer** opportunities at product-focused teams.

## Engineering focus

| Applied AI | Retrieval & Evaluation | Model Adaptation | Product Engineering |
|---|---|---|---|
| RAG, LLM applications, Gemini | BM25, pgvector, FAISS, RRF, reranking | SLMs, SFT, LoRA, QLoRA, PEFT | Python, FastAPI, PostgreSQL, React, Docker, CI/CD |

## Featured work

### ResolveIQ — Production RAG Incident Resolution

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
  <img src="https://github.com/vishwakarmamukul8791-code/resolveiq-platform/raw/main/docs/screenshots/resolveiq-rag-answer.png" width="760" alt="ResolveIQ grounded RAG answer with citations">
</p>

<p>
  <a href="https://resolveiq-five.vercel.app"><img src="https://img.shields.io/badge/Try_Live_Product-000000?style=for-the-badge&logo=vercel&logoColor=white" alt="Try ResolveIQ"></a>
  <a href="https://github.com/vishwakarmamukul8791-code/resolveiq-platform"><img src="https://img.shields.io/badge/View_Repository-181717?style=for-the-badge&logo=github&logoColor=white" alt="ResolveIQ repository"></a>
</p>

### QueryForge — Safe Text-to-SQL with a Fine-Tuned SLM

![Status](https://img.shields.io/badge/status-building_in_public-B8860B)

An in-progress natural-language-to-SQL system focused on adapting a small language model for correct, measurable, and safe generation on previously unseen database schemas.

**Build direction**

- Spider dataset auditing, schema parsing, and schema-aware training examples
- Qwen2.5-Coder 1.5B with QLoRA-based parameter-efficient fine-tuning
- Read-only SQL enforcement and SQLGlot AST validation
- Exact-match and execution-based evaluation instead of syntax-only scoring
- Row limits, timeouts, and schema-level access controls before execution

<p>
  <a href="https://github.com/vishwakarmamukul8791-code/queryforge-slm"><img src="https://img.shields.io/badge/Follow_the_Build-181717?style=for-the-badge&logo=github&logoColor=white" alt="QueryForge repository"></a>
</p>

## How I engineer

- **Grounded by design:** evidence, citations, and safe abstention are system requirements
- **Measured, not assumed:** retrieval quality and failure cases are evaluated before trusting output
- **Owned end to end:** data, APIs, security, persistence, deployment, and user experience all matter
- **Built to evolve:** clear boundaries, tests, CI, and documented trade-offs keep systems maintainable

## Core toolkit

`Python` · `Java` · `SQL` · `FastAPI` · `React` · `PostgreSQL` · `Supabase` · `Docker` · `GitHub Actions`

`RAG` · `LLMs` · `SLMs` · `BM25` · `pgvector` · `FAISS` · `RRF` · `Fine-tuning` · `LoRA / QLoRA` · `PEFT`

---

<p align="center">
  <strong>Interested in reliable AI systems and product engineering?</strong><br>
  <a href="https://portfolio-r6c8-seven.vercel.app">Portfolio</a> ·
  <a href="https://www.linkedin.com/in/mukul-s-8s677">LinkedIn</a> ·
  <a href="https://leetcode.com/u/Mukul863024/">LeetCode</a> ·
  <a href="mailto:mmukul8791@gmail.com">Email</a>
</p>
