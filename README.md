# Naresh

**Backend engineer in Bangalore.** I build open-source infrastructure in .NET, and tools that make AI coding sessions cheaper to run.

[![Follow @nrzz](https://img.shields.io/badge/Follow-%40nrzz-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/nrzz)
[![Email](https://img.shields.io/badge/Email-nareshprabu18%40gmail.com-0A7ACA?style=flat-square)](mailto:nareshprabu18@gmail.com)

## What I'm building

### [claude-code-handover](https://github.com/nrzz/claude-code-handover)

Short Claude Code sessions that pick up where the last one stopped. A handover file loads by itself in every new session, decisions are logged the moment they are made, and what earlier sessions said is recalled automatically.

It came out of an audit of five weeks of my own usage (1,840 requests): 61% of the cost was cache re-writes, and 42 of the 55 full re-writes happened because I came back to an old chat after more than an hour. The audit scripts are in the repo, so you can run the same numbers on your own sessions.

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
- Tried the handover workflow on your own Claude Code setup? I would like to hear what your audit numbers look like: open an issue on [claude-code-handover](https://github.com/nrzz/claude-code-handover/issues).
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
