<div align="center">

# Yethikrishna R

**Building infrastructure that makes AI agents useful.**

[![GitHub](https://img.shields.io/badge/GitHub-yethikrishna-181717?style=flat-square&logo=github)](https://github.com/yethikrishna)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-yethikrishna-0077B5?style=flat-square&logo=linkedin)](https://www.linkedin.com/in/yethikrishna-r-313530201/)

</div>

---

## What I Build

I don't build tutorials. I build **production-scale systems** — the kind that process real work, handle edge cases, and run non-stop. Currently operating a 24-agent autonomous engineering org that ships code to two active projects every hour.

---

## Featured Projects

### 🔥 [The Forge](https://github.com/yethikrishna/the-forge) — AI Agent Orchestration Platform

A unified runtime for building, deploying, and managing AI agents at scale. Written in Go from scratch.

```
182K+ lines of Go  •  232 internal packages  •  164 CLI commands  •  283 commits
```

**What it does:**
- **Agent Client Protocol (ACP)** — standardized SDK for any AI agent
- **Multi-model routing** — route requests across providers with cost optimization
- **Sandboxed execution** — httpjail-based network isolation per agent
- **Pipeline engine** — compose agents into DAG workflows
- **242+ commands** — everything from `forge serve` to `forge orchestrate` to `forge cost`

**Why it matters:** This isn't a wrapper around LangChain. It's a ground-up orchestration platform that treats agents as first-class infrastructure — with audit trails, cost tracking, replay, and governance built in.

**Tech:** Go, Cobra CLI, gRPC, Docker, WireGuard tunnels, CRDT-based state sync

---

### 🌐 [Project Anvil](https://github.com/yethikrishna/project-anvil) — Federated Alphabet Ecosystem

A complete self-hosted alternative to Google's core productivity suite, unified under single sign-on.

```
6 apps  •  Drive • Docs • YouTube • Maps • Search • Gmail  •  SSO via Keycloak
```

**What it does:**
- **Google Drive clone** — S3/MinIO storage, materialized path directories, share links
- **Google Docs clone** — Tiptap editor + Yjs CRDT + Hocuspocus WebSocket for real-time collab
- **YouTube clone** — Redux-cached video search with debounced autocomplete
- **Google Maps clone** — MapLibre GL + OpenMapTiles + OSRM routing + WebGL rendering
- **Google Search clone** — Meilisearch-powered full-text + vector search
- **Gmail clone** — Stalwart JMAP mail server with modern client

**Why it matters:** This proves you can build a privacy-first, self-hosted productivity suite that doesn't sacrifice the features people actually use. One auth system, six apps, zero Google dependency.

**Tech:** Next.js 16, React 19, TypeScript, Tiptap, Yjs, MapLibre, Meilisearch, Keycloak, MinIO, PostgreSQL, Redis, Docker Compose

---

### 🧠 [KARMA](https://github.com/yethikrishna/karma-platform) — Causal Decision Intelligence

Build causal graphs, run counterfactual reasoning, and make better decisions. Not just correlation — causation.

**Tech:** Python, causal inference, graph algorithms

---

## How I Work

I run an **autonomous AI engineering org** — 24 specialized agents across 5 LLM providers (Claude, Grok, GLM-5.1, Bedrock) working in coordinated shifts:

```
CEO → CTOs → Coders, Architects, QA, R&D
         ↕
Intelligence Dept (Signal Scanner, Deep Analyst, Source Tracker, Curator)
         ↕
Operations (Security, Release, Docs, Cost Ops, BizDev, Janitor)
```

These agents read real-time signals from X, Hacker News, GitHub trending, and npm releases — then write production code, run tests, and ship. Every commit is tested. Every release is gated. This isn't a demo — it's a real engineering pipeline that runs 24/7.

---

## By The Numbers

| Metric | Value |
|--------|-------|
| Total lines of production code | **200K+** |
| Active projects | **2** (the-forge, project-anvil) |
| Internal packages built | **232+** |
| CLI commands implemented | **164+** |
| Autonomous AI agents in org | **24** |
| LLM providers integrated | **5** |
| Real-time collab apps built | **6** (Drive, Docs, YouTube, Maps, Search, Gmail) |

---

## Tech Stack

**Languages:** Go, TypeScript, Python, Rust

**Frontend:** React, Next.js, Tiptap, MapLibre, Tailwind CSS, Redux

**Backend:** Go (Chi/Cobra), Node.js (Express/Fastify), Hocuspocus, gRPC

**Data:** PostgreSQL, Redis, MinIO (S3), Meilisearch, Keycloak

**Infra:** Docker, WireGuard, AWS, GitHub Actions, CRDT (Yjs)

**AI/ML:** Multi-provider LLM routing, RAG, vector search, causal inference, agent orchestration

---

## Philosophy

> Ship working systems, not slide decks.

Every project in my profile compiles. Every feature has tests. Every architecture decision is documented. I believe the best resume is code that runs.

---

<div align="center">

**[→ See The Forge in action](https://github.com/yethikrishna/the-forge)**  •  **[→ Explore Project Anvil](https://github.com/yethikrishna/project-anvil)**

<img src="https://komarev.com/ghpvc/?username=yethikrishna&color=blue&style=flat-square" alt="Profile views">

</div>
