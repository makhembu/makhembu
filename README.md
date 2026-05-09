## Brian Makhembu

Engineer building AI systems, edge infrastructure, and cybersecurity tooling at the intersection of LLMs, streaming media, and African fintech.

---

### Cybersecurity Portfolio

| Project | Description | Stack |
|---------|-------------|-------|
| [iris](https://github.com/makhembu/iris) | Threat intelligence aggregation & IOC correlation platform. Ingests feeds (OTX, URLhaus, PhishTank), scores confidence, generates alerts | Hono, better-sqlite3, Cloudflare Workers |
| [sentry](https://github.com/makhembu/sentry) | Detection rule engine — YAML rules, IOC matching, findings management. Sigma-inspired | TypeScript, YAML, Hono |
| [phishkit](https://github.com/makhembu/phishkit) | Phishing analysis pipeline — URL pattern analysis, DOM inspection, LLM-assisted assessment | Hono, Zen/Gemini API, TypeScript |
| [packetwatch](https://github.com/makhembu/packetwatch) | Network anomaly detection — behavioral baselines, z-score detection, edge-collected metrics | TypeScript, statistics (mean/stddev) |
| [trace](https://github.com/makhembu/trace) | Incident timeline correlation — connects IOC alerts, detection findings, phishing reports, and network anomalies into unified timelines | Hono, multi-source API ingestion |
| [nexus](https://github.com/makhembu/nexus) | Unified dashboard and API gateway — proxy router, aggregated health, AI analytics endpoints for the full ecosystem | Hono, Tailwind, structured JSON |

**How they connect:** iris collects IOCs → sentry applies detection rules → phishkit analyzes phishing URLs → packetwatch monitors network baselines → trace correlates into incident timelines → nexus serves the dashboard and AI gateway.

→ [Full ecosystem guide with startup sequence and end-to-end demo](https://github.com/makhembu/iris/blob/master/ECOSYSTEM.md)

---

### Other Projects

| Project | Description | Stack |
|---------|-------------|-------|
| [Jmano-Apparels](https://github.com/makhembu/Jmano-Apparels) | Production e-commerce with AI copilot and admin dashboard | React, Supabase, Gemini, PayPal |
| [tasku](https://github.com/makhembu/tasku) | AI-powered CLI task manager with natural language input | TypeScript, Gemini API |
| [sokoni](https://github.com/makhembu/sokoni) | African market data API — commodity prices and exchange rates | Hono, TypeScript, Cloudflare Workers |
| [fundi](https://github.com/makhembu/fundi) | AI code review bot for GitHub PRs | TypeScript, Gemini, GitHub API |
| [watu](https://github.com/makhembu/watu) | AI-powered CV screening with fit scoring | Next.js, Gemini, Tailwind CSS |
| [playa](https://github.com/makhembu/playa) | Lightweight HLS proxy with subtitle injection | TypeScript, Express, HLS |
| [mpesa-ultimate-daraja-guide](https://github.com/makhembu/mpesa-ultimate-daraja-guide) | Developer-first docs for Safaricom's M-Pesa Daraja API | Markdown, curl, Node.js |
| [autonomous](https://github.com/makhembu/autonomous) | Desktop AI agent with Gemini + Playwright browser automation | TypeScript, Electron, Playwright |
| [coldreach-ai](https://github.com/makhembu/coldreach-ai) | AI cold outreach SaaS — personalized email campaigns at scale | Next.js, FastAPI, Celery, PostgreSQL |
| [research-agent](https://github.com/makhembu/research-agent) | AI research agent with Playwright, BullMQ, Redis queue architecture | Next.js, BullMQ, Redis, Playwright |
| [polymarket-trading](https://github.com/makhembu/polymarket-trading) | Prediction market trading bot, CLI, and MCP server | Rust, CLOB API, TypeScript |
| [kenya-tenders-api](https://github.com/makhembu/kenya-tenders-api) | AI-powered government tender intelligence with webhooks and alerts | Cloudflare Workers, KV, cron |

---

### What I Build

- **AI Systems** — LLM-powered agents for hiring, research, outreach, task management, code review, and threat analysis
- **Cybersecurity** — Threat intel aggregation, detection rules, phishing analysis, anomaly detection, incident correlation, unified dashboard
- **Edge Infrastructure** — Cloudflare Workers, HLS streaming proxies, and serverless APIs
- **Developer Tooling** — CLI tools, bots, SDKs, MCP servers, and API documentation
- **Fintech** — M-Pesa Daraja integration, payment systems, market data, government procurement

---

*"Build things that work in the real world."*
