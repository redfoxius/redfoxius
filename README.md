# Hi, I'm Oleksander 👋

Backend developer focused on data infrastructure — **Go, Elasticsearch, Kafka, SQL**.
I build products end-to-end: from data model and architecture to deployment on my own infrastructure.
Based in Ukraine.

<!-- 📖 **Portfolio:** https://redfoxius.github.io — uncomment once the case-study site is live -->

## Open source

| Project | What it is | Stack | Links |
|---|---|---|---|
| **claude-memory** | Shared, curated semantic memory for Claude Code: a single Go binary with an MCP server and a prompt hook that injects relevant facts within an 800 ms budget. Facts go through a candidate → active lifecycle with similarity-based dedup, strict namespaces, staleness checks against git, and ingest from merged PRs (GitHub, GitLab, Azure DevOps). Retrieval is hybrid (vector + full-text, RRF) and measured by an eval harness. | Go · PostgreSQL + pgvector · Ollama (bge-m3) · MCP | [code](https://github.com/redfoxius/claude-memory) · [docs](https://redfoxius.github.io/claude-memory/) |
| **Dev Digest** | Local-first AI pull-request review studio. Started from a course starter template by [Ivan Lapa](https://github.com/ai-agentic-engineering-neo/dev-digest); I extended it with 150+ commits: intent layer, Smart Diff, PR Brief and Risk Brief, Blast Radius impact map, an MCP server, Conventions Extractor, agent skills, Onboarding Generator, an eval pipeline with dashboards, and evals wired into CI. | TypeScript · Fastify · Next.js 15 · Drizzle · PostgreSQL + pgvector · LLM APIs | [code](https://github.com/redfoxius/dev-digest) |

## Products

Source code is private; architecture and code walkthrough available on request.

| Project | What it is | Stack | Links |
|---|---|---|---|
| **zbc.wtf** | Browser multiplayer FPS. Go platform monolith (auth, matchmaking, shop, market and trading, chat, friends, quests, moderation, feature flags, admin panel with RBAC) and Go match servers with an authoritative simulation; a TypeScript twin of the simulation for client prediction, kept in sync by shared test vectors run in both languages in CI. | Go · TypeScript · React · Three.js · MongoDB · Redis · Prometheus | [live](https://zbc.wtf) |
| **Komirne** | SaaS for landlords: utility bills, tariffs and tenant balances; meter readings recognized from photos; Telegram bot for owners and tenants. | Go · PostgreSQL · htmx · Claude API · Telegram Bot API | [live](https://komirne.app) |
| **Vervechka** | Platform for Ukrainian private schools (primary school first, then kindergarten and development centre): a day view for parents, contracts and billing, class journal, holiday camp, Telegram and Google Drive integration. Design stage: architecture with an instance per school, and a PostgreSQL schema (99 tables) covered by scenario tests. | Go · PostgreSQL · React / React Native (planned) | — |

## Tech

**Languages:** Go, TypeScript, SQL
**Data:** PostgreSQL (incl. pgvector), Elasticsearch, Kafka, MongoDB, Redis
**Infra:** Docker, Caddy, Tailscale, self-hosted (Mac Mini), VPS, GitHub Actions, Prometheus
**AI:** LLM integration (Claude API, OpenRouter), local models (Ollama), MCP servers, evals

## Contact

- Email: redfoxius@gmail.com
- LinkedIn: [oleksandr-kolomoiets](https://www.linkedin.com/in/oleksandr-kolomoiets)
- Telegram: [@redfoxius](https://t.me/redfoxius)
