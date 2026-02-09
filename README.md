## Hi, I'm Ross 👋

I build high-performance systems at the intersection of databases, real-time data, and developer tooling. Most of my work is in Rust and PostgreSQL.

### What I'm working on

- **[Postrust](https://github.com/rosssaunders/postrust)** — an **async-native PostgreSQL-compatible SQL engine** written from scratch in Rust. Unlike traditional embedded databases, Postrust treats network data sources as first-class SQL primitives: `http_get()`, `http_json()`, and WebSocket streams are built into the query engine, not bolted on top. The entire engine is async — from expression evaluation through to query execution — meaning you can fetch, join, and analyse live API data in pure SQL without Python glue or ETL pipelines. Supports window functions, CTEs, JSON/JSONB, 50+ built-in functions, and runs in the browser via WASM. [Try it live →](https://rosssaunders.github.io/postrust)

- **[ccrxt](https://github.com/rosssaunders/ccrxt)** — a Rust library for low-latency access to cryptocurrency exchange APIs. REST, WebSocket, strict rate limiting, designed for HFT. Supports major venues including Binance, Coinbase, Kraken, Deribit, and more.

- **[pg_deribit](https://github.com/rosssaunders/pg_deribit)** — query the Deribit crypto derivatives API directly from PostgreSQL. Built on [Omnigres](https://omnigres.com).

- **[coincise](https://github.com/rosssaunders/coincise)** — LLM-friendly versions of crypto exchange API documentation. Making exchange APIs accessible to AI coding assistants.

### Developer tools

- **[distillery](https://github.com/rosssaunders/distillery)** — distill PR diffs into reviewable narratives, built for the AI code review era
- **[pr-copilot](https://github.com/rosssaunders/pr-copilot)** — interactive PR review agent powered by the GitHub Copilot SDK

### Background

I've spent years building low-latency trading systems and have a deep interest in database internals — which is why I'm building a Postgres-compatible SQL engine from scratch. I believe the best way to understand something is to build it. With Postrust, I'm exploring what happens when you make a SQL engine async-native: suddenly APIs, WebSockets, and live data feeds become queryable without leaving SQL.
