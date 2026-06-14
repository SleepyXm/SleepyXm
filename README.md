# Mikayel

**Software Engineer · CS · Graduating 2026**

Building systems that hold up under load — real-time platforms, developer tooling, and infrastructure that doesn't need babysitting.

---

## What I'm Building

**LIDE — Live Integrated Development Environment** &nbsp;&nbsp;`Python` `FastAPI` `Next.js` `PostgreSQL`

Create or import a project, get it containerised with its own domain, and edit it live — frontend, backend, or database. The environment surfaces the running project's endpoints, functions, pages, and database schema in real time via AST parsing, regex, and filesystem traversal. Includes an endpoint test generator that builds test data from existing function signatures, a component generation tool, and a design editor — schema management and UI preview all in one place. Evaluating a Tauri port for distribution given runtime constraints.

&nbsp;

**Synapse — Multi-Model AI Platform** &nbsp;&nbsp;`Go` `Next.js` `PostgreSQL` `AWS EC2`

BYOK platform with streamed side-by-side response comparison and timing across multiple Hugging Face models simultaneously. Conversational memory built on LLM-generated compression before PostgreSQL storage — context persists across sessions without unbounded growth. Custom web search tool built from scratch to give open-source models agentic behaviour without needing fine-tuned support. Deployed on EC2 via a self-built GitHub webhook CI/CD pipeline: pull → deps → restart → failure alerts.

&nbsp;

**Inframap — Real-Time Infrastructure Monitor**

Real-time server monitoring with predictive failure detection, designed to trigger self-healing before anything actually goes down.

---

## Also On Here

**Real-Time Trading Platform** &nbsp;&nbsp;`Go` `Python` `Next.js` `PostgreSQL` `Redis`

Fanout WebSocket architecture sustaining **10,000 concurrent users** at **56–74ms p99 latency** under load, verified via K6. Batched execution pipeline via Redis + bulk PostgreSQL inserts hits **500 executions/sec with zero failures** across 15,000 events. Stochastic price simulation using Brownian motion anchored to live market data. Delivers 3,000 points of OHLCV history on connection via parallel fanout without touching the live feed. Session-scoped auth model strips identity verification from the execution hot path entirely.

&nbsp;

**CI/CD Pipeline Tool** &nbsp;&nbsp;`Nginx` `Bash` `Linux`

Deploy projects to AWS, Azure, or bare Linux machines without the manual setup. Handles prerequisite installation, hosting configuration, and domain management via Nginx as a reverse proxy. Attaches a GitHub webhook to any repo so pushes automatically propagate to the live environment — no manual pulls, no SSH sessions.

**Job Aggregator & CV Analyser** &nbsp;&nbsp;`Python` `React` `PostgreSQL`

Scrapes 100+ job postings per search with deduplication logic, LLM-powered resume tailoring per job description.

**Custom Claude Code + Gemini CLI** — my own implementations of both.

**LLM Experimentation Platform** — test and compare open-source models side by side.

CTFs and bug bounty on the side. 51 repos. Commits most days.

---

## Tech

![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffaa54)
![Go](https://img.shields.io/badge/Go-00ADD8?logo=Go&logoColor=white&style=for-the-badge)
![Rust](https://img.shields.io/badge/Rust-ff7357?style=for-the-badge&logo=rust&logoColor=ff7357&labelColor=171c21)
![TypeScript](https://img.shields.io/badge/typescript-%23007ACC.svg?style=for-the-badge&logo=typescript&logoColor=white)
![React](https://img.shields.io/badge/react-%2320232a.svg?style=for-the-badge&logo=react&logoColor=%2361DAFB)
![NextJS](https://img.shields.io/badge/next.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white)
![TailwindCSS](https://img.shields.io/badge/tailwindcss-%2338B2AC.svg?style=for-the-badge&logo=tailwind-css&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-1C59FF?style=for-the-badge&logo=docker&logoColor=1C59FF&labelColor=171C21)

---

![Stats](https://github-readme-stats.vercel.app/api?username=SleepyXm&count_private=false&show_icons=true&bg_color=252838&title_color=58a6ff&text_color=c9d1d9&icon_color=58a6ff&hide_border=true)

---

Open to internships, grad roles, and freelance from June 2026. &nbsp;👾
