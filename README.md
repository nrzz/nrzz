# Naresh

**Backend engineer in Bangalore.** I build open-source infrastructure in .NET, and tools that make AI coding sessions cheaper to run.

[![Follow @nrzz](https://img.shields.io/badge/Follow-%40nrzz-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/nrzz)
[![Email](https://img.shields.io/badge/Email-nareshprabu18%40gmail.com-0A7ACA?style=flat-square)](mailto:nareshprabu18@gmail.com)

## What I'm building

### [Claude Code toolkit](https://github.com/nrzz/claude-code-toolkit)

Nine small, open-source tools that make Claude Code cheaper, safer and easier to share. No dependencies, few or no tokens, one plugin marketplace, and an end-to-end test that installs all nine from GitHub on Windows, macOS and Linux. [Website](https://nrzz.github.io/claude-code-toolkit/).

| Tool | What it does |
|:-----|:-------------|
| **[claude-code-handover](https://github.com/nrzz/claude-code-handover)** | Short sessions that pick up where the last one stopped: a handover file, a decisions log and automatic recall |
| **[claude-code-team-sync](https://github.com/nrzz/claude-code-team-sync)** | Share sessions, notes and team context with coworkers through git, synced in the background |
| **[claude-code-glow](https://github.com/nrzz/claude-code-glow)** | 15 themes for the whole interface, a status line with a context meter, and a live HUD |
| **[claude-code-guardrails](https://github.com/nrzz/claude-code-guardrails)** | Stops `rm -rf /`, force pushes, secrets in commits and `.env` edits, at zero tokens per allowed call |
| **[claude-code-notify](https://github.com/nrzz/claude-code-notify)** | A ping when Claude needs you or finishes: terminal, desktop, phone, Slack, Discord or Teams |
| **[claude-cost-guard](https://github.com/nrzz/claude-cost-guard)** | Daily and weekly budgets with zero-token warnings and an optional hard stop |
| **[claude-md-doctor](https://github.com/nrzz/claude-md-doctor)** | What your CLAUDE.md costs in every session, and the fixes that save the most |
| **[claude-code-starter-kits](https://github.com/nrzz/claude-code-starter-kits)** | A lean, safe `.claude/` for .NET, Node, Python, Go, Flutter or Java in one command |
| **[claude-session-replay](https://github.com/nrzz/claude-session-replay)** | Search every past session, and export one as a self-contained HTML replay |

Set them up in one click: this opens a local setup page with the recommended tools already switched on.

```bash
npx -y github:nrzz/claude-code-toolkit
```

It started with an audit of five weeks of my own usage (1,840 requests): 61% of the cost was cache re-writes, and 42 of the 55 full re-writes happened because I came back to an old chat after more than an hour. [claude-code-handover](https://github.com/nrzz/claude-code-handover) fixes that, and its audit scripts let you run the same numbers on your own sessions.

### [Sentinel](https://github.com/nrzz/Sentinel)

Self-hosted observability platform for logs, metrics, traces, alerts and incidents. One deployment instead of five tools: a .NET 10 API and workers, ClickHouse for telemetry, PostgreSQL for metadata, live log streaming, alert rules, incident timelines and a React UI.

### [EventMesh](https://github.com/nrzz/EventMesh)

One messaging API for .NET that runs on RabbitMQ, Kafka, Redis Streams, Azure Service Bus, AWS SQS, Google Pub/Sub or NATS JetStream, so switching brokers does not mean rewriting business logic. CloudEvents envelope, transactional outbox, idempotent inbox, retries and sagas. MIT licensed, broker adapters in beta.

## Also

| Project | What it is |
|:--------|:-----------|
| **[pulsedeck](https://github.com/nrzz/pulsedeck)** | Desktop widget dashboard for Windows and Linux: system vitals, network, markets, news and more |
| **[open-torrent](https://github.com/nrzz/open-torrent)** | Free, ad-free BitTorrent client for Android, Windows and Linux (libtorrent + Flutter) |
| **[finagent](https://github.com/nrzz/finagent)** | Self-hosted AI finance agent for stocks, mutual funds, F&O and crypto, paper trading by default |
| **[web3-portfolio-hub](https://github.com/nrzz/web3-portfolio-hub)** | Web3 portfolio dashboard with multi-wallet tracking (Go + React) |

## Collaborate

Sentinel and EventMesh are at the stage where outside eyes change the most: a bug report from a real deployment, a broker EventMesh does not cover yet, a dashboard Sentinel should ship by default.

- Run self-hosted observability or event-driven .NET services? Tell me what is missing in [Sentinel discussions](https://github.com/nrzz/Sentinel/discussions) or [EventMesh discussions](https://github.com/nrzz/EventMesh/discussions).
- Use Claude Code? Every toolkit repo has issues labelled good first issue, and ideas for new tools are welcome in [toolkit discussions](https://github.com/nrzz/claude-code-toolkit/discussions). I would also like to hear what your handover audit numbers look like.
- Want to contribute? Start with a repo's contributing guide and roadmap, then open an issue so we can scope it together.
- Found a project useful? A star helps other people find it, and following keeps you posted on releases.

## Working with

`C#` · `.NET` · `TypeScript` · `Python` · `Go` · `Dart / Flutter` · `PostgreSQL` · `ClickHouse` · `Docker` · `Kubernetes`

## Connect

- GitHub: [@nrzz](https://github.com/nrzz)
- Email: [nareshprabu18@gmail.com](mailto:nareshprabu18@gmail.com)
- Location: Bangalore, India
- Open to collaboration, and available for work on .NET backends, observability and messaging.

---

*Building tools that make distributed systems easier to run and reason about.*
