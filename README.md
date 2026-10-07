# Aditya Vikram Mahendru

**Software Engineering Intern · Full Stack Developer · Machine Learning Engineer**

Hyderabad, Telangana, India · B.Tech Computer Science Engineering, Woxsen University (2024-2028)

<p align="left">
  <a href="mailto:jobs.aditya.vikram.mahendru@gmail.com">
    <img src="https://img.shields.io/badge/Email-jobs.aditya.vikram.mahendru%40gmail.com-red?style=flat-square&logo=gmail&logoColor=white" alt="Email">
  </a>
  <a href="https://www.linkedin.com/in/aditya-vikram-mahendru/">
    <img src="https://img.shields.io/badge/LinkedIn-Aditya%20Vikram%20Mahendru-0A66C2?style=flat-square&logo=linkedin&logoColor=white" alt="LinkedIn">
  </a>
  <a href="https://adityavikram.dev">
    <img src="https://img.shields.io/badge/Portfolio-adityavikram.dev-000000?style=flat-square&logo=firefox&logoColor=white" alt="Portfolio">
  </a>
  <a href="https://adityavikramdev.substack.com">
    <img src="https://img.shields.io/badge/Substack-adityavikramdev-FF6719?style=flat-square&logo=substack&logoColor=white" alt="Substack">
  </a>
</p>

---

## About

I'm a **software engineering intern** based in **Hyderabad, India**, working across backend engineering, machine learning systems, and full-stack web development. I build open source tools in Rust, ML systems in Python, and production web platforms in TypeScript.

I'm currently a **Forward Deployed ML Intern at iGlobus**, where I work on DPDP compliance with US client teams: readiness assessments and PII discovery over databases, logs, tickets, and backups. I also founded **LexContra**, a corporate law practice where I build the content and review tooling in-house, and I run a web development agency on retainer.

Previously I was an **AI Engineering Intern at Symboynt**, building Python backend services, REST APIs, and RAG pipelines that integrate LLMs, SQL, and cloud infrastructure, including multi-agent systems with LangGraph and LangChain. Before that I was a **Software Engineering Intern at the Woxsen AI Research Centre**, shipping production ERP systems for 6,000+ users.

I maintain **featrs**, a Polars-native feature engineering library for Rust (67 stars), and I write about engineering and machine learning at [adityavikram.dev](https://adityavikram.dev) and on [Substack](https://adityavikramdev.substack.com).

**Open to Software Engineering Intern, Backend, and ML Engineering roles in Hyderabad and remote.**

---

## Experience

| Role | Organization | Period | Focus |
|---|---|---|---|
| Forward Deployed ML Intern | iGlobus Corporate Consulting | Aug 2026 - Present | DPDP compliance, PII discovery, ML classification over client data |
| Founder | LexContra | 2025 - Present | Corporate law practice, in-house content and review tooling |
| AI Engineering Intern | Symboynt | May 2026 - Jul 2026 | Python backends, REST APIs, RAG pipelines, LangGraph/LangChain, Kubernetes CI/CD |
| Technical Secretary | Woxsen Student Council | Mar 2025 - Mar 2026 | Campus-wide digital transformation, 6 projects, 4 internal tools, 600+ students |
| Software Engineering Intern | Woxsen AI Research Centre | Jan 2025 - Aug 2025 | Production ERP for 6,000+ users, Flask REST APIs, PostgreSQL, Docker, GitHub Actions |

---

## Selected Engineering Projects

### [featrs](https://github.com/featrs/featrs) - Feature Engineering for Rust

Polars-native feature engineering library with scikit-learn inspired transforms. `fit`/`transform` API, pipelines, `ColumnTransformer`, `FeatureUnion`, and `AutoScaler`, which picks a scaling strategy per column from the column's own statistics.

`Rust` `Polars` `Machine Learning` · 67 stars · [crates.io](https://crates.io/crates/featrs) · [write-up](https://adityavikram.dev/blog/featrs-scikit-learn-for-rust)

### [aiter-commerce](https://github.com/DeathSurfing/aiter-commerce) - Agent-Buyable Commerce

Rust-first agentic commerce backend. Makes any merchant catalog buyable by AI agents: RFC 9421 Ed25519 signed requests, per-agent spend caps, integer minor units for money, append-only audit log, and Razorpay webhook reconciliation that fails closed.

`Rust` `Axum` `PostgreSQL` `Razorpay` `Ed25519` · [write-up](https://adityavikram.dev/blog/making-a-merchant-agent-buyable)

### [pre-mortem](https://github.com/DeathSurfing/pre-mortem) - Decision Reviewer

Memory-backed reviewer for business decisions. Cites your own past decisions by id, says `no_precedent` instead of guessing, and lets the history grow from use. Built on Hindsight for memory with a Postgres + pgvector prompt store.

`Python` `FastAPI` `PostgreSQL` `pgvector` `Next.js` · [live demo](https://premortem.lexcontra.com/) · [write-up](https://adityavikram.dev/blog/pre-mortem-refuses-to-answer)

### [kronos-vs-alphazerobeta](https://github.com/DeathSurfing/kronos-vs-alphazerobeta) - Financial ML Benchmark

Controlled, leakage-free benchmark of a financial foundation model against a CNN-GRU recurrent-PPO portfolio agent on the S&P 500. 22 non-overlapping walk-forward folds, 2014-2024, identical universe, costs, and constraints, with bootstrap confidence intervals and a documented reproduction gap.

`Python` `PyTorch` `Reinforcement Learning` `Quant` · [write-up](https://adityavikram.dev/blog/kronos-vs-alphazerobeta)

### [autofeat](https://github.com/DeathSurfing/autofeat) - Feature Engineering CLI

Interactive AI-powered feature engineering CLI in Rust.

`Rust` `CLI`

### [CNN From Scratch](https://github.com/DeathSurfing/CNN-From-Scratch)

Convolutional neural network in Rust with no ML frameworks, forward and backward propagation built from linear algebra only.

`Rust` `Deep Learning` `Linear Algebra`

---

## Machine Learning & Research

- **Financial RL reproduction** - Reimplemented a recurrent PPO portfolio agent with walk-forward validation, reporting Sharpe, benchmark correlation, and max drawdown rather than a single headline number. Published as an open benchmark with generated tables.
- **PII discovery over unstructured data** - Found personal data clients did not know they held by running rules plus ML classification over databases, logs, tickets, and backups.
- **DPDP compliance work** - Readiness assessments and product controls for US client teams, turning data-protection obligations into working product behaviour.

---

## Technical Stack

**Languages** - Rust, Python, TypeScript, JavaScript, SQL, C++, HTML/CSS

**Backend** - Axum, FastAPI, Flask, Node.js, REST APIs, PostgreSQL, MongoDB, Redis, Convex

**AI / ML** - PyTorch, scikit-learn, Pandas, Polars, RAG, LangGraph, LangChain, NLP, MLOps

**Frontend** - Next.js, React, Tailwind CSS, TypeScript

**DevOps / Infrastructure** - Docker, Kubernetes, K3s, Proxmox, MetalLB, Nginx, GitHub Actions, CI/CD, Linux

**Payments / Auth** - Razorpay, Stripe, WorkOS, Ed25519 request signing, RFC 9421

---

## Writing

I write about performance engineering, machine learning, and building software.

- [How I Cut My Portfolio's JavaScript by 35% and Its Images by 914 KB](https://adityavikram.dev/blog/portfolio-performance-audit)
- [Kronos vs AlphaZeroBeta: Benchmarking a Forecast Model Against a Decision Model](https://adityavikram.dev/blog/kronos-vs-alphazerobeta)
- [featrs: Bringing scikit-learn's Feature Engineering to Rust and Polars](https://adityavikram.dev/blog/featrs-scikit-learn-for-rust)
- [Making a Merchant Agent-Buyable: Money-Safe Commerce in Rust](https://adityavikram.dev/blog/making-a-merchant-agent-buyable)
- [I built a decision reviewer that refuses to answer, and that was the hard part](https://adityavikram.dev/blog/pre-mortem-refuses-to-answer)

All posts: [adityavikram.dev/blog](https://adityavikram.dev/blog) · [RSS](https://adityavikram.dev/feed.xml) · [Substack](https://adityavikramdev.substack.com)

---

## Education

**Woxsen University** - B.Tech Computer Science Engineering, 2024-2028 · Hyderabad, India

---

## Contact

- **Email** - jobs.aditya.vikram.mahendru@gmail.com
- **Portfolio** - [adityavikram.dev](https://adityavikram.dev)
- **LinkedIn** - [aditya-vikram-mahendru](https://www.linkedin.com/in/aditya-vikram-mahendru/)
- **Location** - Hyderabad, Telangana, India
