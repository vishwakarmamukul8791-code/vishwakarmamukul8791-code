<h1 align="center">Hi, I'm Mukul 👋</h1>
<p align="center">Product Engineer – AI/ML at TCS · Building RAG &amp; LLM systems · Open to AI / ML Engineer roles</p>

<p align="center">
  <a href="https://portfolio-r6c8-seven.vercel.app" target="_blank"><img src="https://img.shields.io/badge/Portfolio-2F6F5E?style=for-the-badge" alt="Portfolio"/></a>
  <a href="https://www.linkedin.com/in/mukul-s-8s677" target="_blank"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/></a>
  <a href="mailto:mmukul8791@gmail.com"><img src="https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Gmail"/></a>
</p>
<p align="center"><sub>mmukul8791@gmail.com</sub></p>

<br>

## About Me

Product Engineer working in AI/ML at Tata Consultancy Services with 1+ year of industry experience building applied AI/ML systems. Currently focused on Generative AI, retrieval-augmented generation (RAG), LLM-backed applications, retrieval systems, and production-grade backend engineering.

## Tech Stack

**Languages**

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=for-the-badge&logo=postgresql&logoColor=white)

**Backend & APIs**

![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white)
![Flask](https://img.shields.io/badge/Flask-000000?style=for-the-badge&logo=flask&logoColor=white)

**AI / ML / LLMs**

![Generative AI](https://img.shields.io/badge/Generative_AI-4B275F?style=for-the-badge)
![RAG](https://img.shields.io/badge/RAG-4B275F?style=for-the-badge)
![LLMs](https://img.shields.io/badge/LLMs-4B275F?style=for-the-badge)
![FAISS](https://img.shields.io/badge/FAISS-4B275F?style=for-the-badge)
![BM25](https://img.shields.io/badge/BM25-4B275F?style=for-the-badge)
![Hybrid Retrieval](https://img.shields.io/badge/Hybrid_Retrieval-4B275F?style=for-the-badge)
![Gemini](https://img.shields.io/badge/Gemini-8E75B2?style=for-the-badge&logo=googlegemini&logoColor=white)

**Model Adaptation**

![SLMs](https://img.shields.io/badge/SLMs-4B275F?style=for-the-badge)
![Fine-tuning](https://img.shields.io/badge/Fine--tuning-4B275F?style=for-the-badge)
![LoRA](https://img.shields.io/badge/LoRA-4B275F?style=for-the-badge)
![PEFT](https://img.shields.io/badge/PEFT-4B275F?style=for-the-badge)

**Databases & Persistence**

![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)
![Supabase](https://img.shields.io/badge/Supabase-3FCF8E?style=for-the-badge&logo=supabase&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white)

**Frontend**

![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)

**Tooling**

![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=for-the-badge&logo=githubactions&logoColor=white)

## How I Work

- Design for failure, not just the happy path — e.g. confidence-gated generation that abstains instead of guessing when evidence is weak
- Validate retrieval and generation quality with offline evaluation, not just manual spot-checks
- Care about state consistency and safe writes in systems with persistent data
- Ship with CI: tests, linting, and builds run automatically on every change

## Featured Project — ResolveIQ

[![CI](https://github.com/vishwakarmamukul8791-code/resolveiq-platform/actions/workflows/ci.yml/badge.svg)](https://github.com/vishwakarmamukul8791-code/resolveiq-platform/actions/workflows/ci.yml)

A production-oriented full-stack RAG platform for investigating IT incidents against enterprise knowledge, built to fail safely rather than answer confidently on weak evidence.

- Hybrid retrieval combining BM25 (lexical) and FAISS (semantic), fused with Reciprocal Rank Fusion, with optional cross-encoder reranking
- Confidence-gated generation with Gemini: weak evidence triggers safe abstention instead of a guessed answer, with grounded citations on every response
- JWT-authenticated, role-based access with an admin dashboard covering documents, engineers, and system health
- Offline retrieval evaluation harness and production-focused retrieval quality checks
- Persistent application data using Supabase PostgreSQL instead of relying on ephemeral Render filesystem storage
- FastAPI + React 19, deployed on Vercel (frontend) and Render (backend), containerized with Docker
- CI pipeline covering backend tests, frontend lint/build, and Docker image validation

<p align="center">
  <img src="https://github.com/vishwakarmamukul8791-code/resolveiq-platform/raw/main/docs/screenshots/resolveiq-rag-answer.png" width="700" alt="ResolveIQ answering an incident question with grounded citations">
</p>

<p>
  <a href="https://resolveiq-five.vercel.app" target="_blank"><img src="https://img.shields.io/badge/Live_Demo-000000?style=for-the-badge&logo=vercel&logoColor=white" alt="Live Demo"/></a>
  <a href="https://github.com/vishwakarmamukul8791-code/resolveiq-platform" target="_blank"><img src="https://img.shields.io/badge/Repository-181717?style=for-the-badge&logo=github&logoColor=white" alt="Repository"/></a>
</p>

## Currently Building — QueryForge

A natural-language-to-SQL system focused on adapting small language models for reliable structured query generation using supervised fine-tuning, LoRA/PEFT, schema understanding, and SQL validation.

- Natural-language-to-SQL generation
- Small Language Models (SLMs)
- Supervised Fine-Tuning (SFT)
- LoRA-based parameter-efficient fine-tuning
- PEFT
- Database schema understanding
- Spider dataset processing
- Structured SQL generation and validation

<p>
  <a href="https://github.com/vishwakarmamukul8791-code/queryforge-slm" target="_blank"><img src="https://img.shields.io/badge/Repository-181717?style=for-the-badge&logo=github&logoColor=white" alt="Repository"/></a>
  <img src="https://img.shields.io/badge/Status-In_Progress-B8860B?style=for-the-badge" alt="In Progress"/>
</p>

## What I'm Looking For

I want to keep building AI systems that know their limits — not just impressive demos, but LLM applications and retrieval infrastructure that hold up in production. Open to AI / ML Engineer roles where that's the bar.

## Let's Connect

<p>
  <a href="https://portfolio-r6c8-seven.vercel.app" target="_blank"><img src="https://img.shields.io/badge/Portfolio-2F6F5E?style=for-the-badge" alt="Portfolio"/></a>

  <a href="https://www.linkedin.com/in/mukul-s-8s677" target="_blank"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/></a>

  <a href="mailto:mmukul8791@gmail.com"><img src="https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Gmail"/></a>
</p>