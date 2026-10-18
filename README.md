# Naresh

**Backend engineer in Bangalore.** I build .NET infrastructure that stays up, and tools that keep AI coding agents cheap, safe and predictable, for Claude Code, Codex, Gemini CLI, Copilot CLI and Cursor. Powered by filter coffee and a grudge against cache re-writes.

[![Follow @nrzz](https://img.shields.io/github/followers/nrzz?style=flat-square&logo=github&logoColor=white&label=Follow%20%40nrzz&color=181717)](https://github.com/nrzz?tab=followers)
[![Email](https://img.shields.io/badge/Email-nareshprabu18%40gmail.com-0A7ACA?style=flat-square)](mailto:nareshprabu18@gmail.com)

## What I'm building

### Tools for every coding agent

Claude Code, Codex CLI, Gemini CLI, GitHub Copilot CLI and Cursor each have their own hooks, configuration files and quirks. These tools read what each agent actually reads and put every claim to the real binary, at zero tokens.

| Tool | What it does |
|:-----|:-------------|
| **[everyhook](https://github.com/nrzz/everyhook)** | Write a hook once, run it in every coding agent: one contract, an adapter per agent, install and uninstall into each agent's configuration, and a bench that puts the hook to the JSON each real agent sends |
| **[codex-config-doctor](https://github.com/nrzz/codex-config-doctor)** | What Codex CLI will actually do with your configuration: every layer and the merged result with the source of each key, the AGENTS.md files against their 32 KiB cap, rules, hooks, MCP servers and the Windows sandbox, linted and checked against the real binary |

### [Claude Code toolkit](https://github.com/nrzz/claude-code-toolkit)

Nineteen small, open-source tools that make Claude Code cheaper, safer and easier to share. No dependencies, few or no tokens, one plugin marketplace, and an end-to-end test that installs all nineteen from GitHub on Windows, macOS and Linux. [Website](https://nrzz.github.io/claude-code-toolkit/).

| Tool | What it does |
|:-----|:-------------|
| **[claude-code-handover](https://github.com/nrzz/claude-code-handover)** | Short sessions that pick up where the last one stopped: a handover file, a decisions log and automatic recall |
| **[claude-code-team-sync](https://github.com/nrzz/claude-code-team-sync)** | Share sessions, notes and team context with coworkers through git, synced in the background |
| **[claude-code-glow](https://github.com/nrzz/claude-code-glow)** | 14 themes for the whole interface, a status line with a context meter, and a live HUD |
| **[claude-code-guardrails](https://github.com/nrzz/claude-code-guardrails)** | Stops `rm -rf /`, force pushes, secrets in commits and `.env` edits, at zero tokens per allowed call |
| **[claude-code-notify](https://github.com/nrzz/claude-code-notify)** | A ping when Claude needs you or finishes: terminal, desktop, phone, Slack, Discord or Teams |
| **[claude-cost-guard](https://github.com/nrzz/claude-cost-guard)** | Daily and weekly budgets with zero-token warnings and an optional hard stop |
| **[claude-md-doctor](https://github.com/nrzz/claude-md-doctor)** | What your CLAUDE.md costs in every session, and the fixes that save the most |
| **[claude-code-starter-kits](https://github.com/nrzz/claude-code-starter-kits)** | A lean, safe `.claude/` for .NET, Node, Python, Go, Flutter or Java in one command |
| **[claude-session-replay](https://github.com/nrzz/claude-session-replay)** | Search every past session, and export one as a self-contained HTML replay |
| **[claude-chat-ferry](https://github.com/nrzz/claude-chat-ferry)** | Continue a Cursor or Antigravity chat in Claude Code, or hand a Claude Code session to them |
| **[claude-session-tidy](https://github.com/nrzz/claude-session-tidy)** | Delete, keep and restore your sessions before the 30-day cleanup removes them |
| **[claude-permission-doctor](https://github.com/nrzz/claude-permission-doctor)** | See why a permission prompt appeared, drop dead rules and add the ones you keep approving by hand |
| **[claude-hook-bench](https://github.com/nrzz/claude-hook-bench)** | Run every hook with the exact JSON Claude Code sends, and see whether it blocks, allows, adds context or fails |
| **[claude-relocate](https://github.com/nrzz/claude-relocate)** | Move Claude Code's config folder to another drive or the XDG folders, with `CLAUDE_CONFIG_DIR` set for every shell and an undo |
| **[claude-settings-doctor](https://github.com/nrzz/claude-settings-doctor)** | A commented `settings.jsonc` that builds `settings.json`, the merged settings with their source, and a lint that finds what Claude Code ignores in silence |
| **[claude-automode-doctor](https://github.com/nrzz/claude-automode-doctor)** | What auto mode and its classifier decided, read from your transcripts, which refusals were the service rather than your settings, and a lint of the `autoMode` settings |
| **[claude-mcp-check](https://github.com/nrzz/claude-mcp-check)** | Every MCP server Claude Code would load and from which file, started the way Claude Code starts it, with what its tools cost in context |
| **[claude-sandbox-doctor](https://github.com/nrzz/claude-sandbox-doctor)** | Whether Claude Code's Bash sandbox can work on your machine, why a command ran inside it or outside it, and the sandbox settings that never take effect |
| **[claude-windows-doctor](https://github.com/nrzz/claude-windows-doctor)** | On Windows: which shell the Bash tool gets and why, every `claude` on the machine, and the setup problems behind common Windows issues |

Set them up in one click: this opens a local setup page with the recommended tools already switched on.

```bash
npx -y github:nrzz/claude-code-toolkit
```

It started with an audit of five weeks of my own usage (1,840 requests): 61% of the cost was cache re-writes, and 42 of the 55 full re-writes happened because I came back to an old chat after a break of 55 minutes or more. [claude-code-handover](https://github.com/nrzz/claude-code-handover) fixes that, and its audit scripts let you run the same numbers on your own sessions.

Ideas for the next tool are welcome in the [toolkit discussions](https://github.com/nrzz/claude-code-toolkit/discussions); follow to see releases land.

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
- Use a coding agent? Every repo has issues labelled good first issue, and ideas for new tools are welcome in [toolkit discussions](https://github.com/nrzz/claude-code-toolkit/discussions). I would also like to hear what your handover audit numbers look like: [share them here](https://github.com/nrzz/claude-code-handover/discussions/4).
- Want to contribute? Start with a repo's contributing guide and roadmap, then open an issue so we can scope it together.
- Found a project useful? A star helps other people find it, and following keeps you posted on releases.

## Working with

`C#` · `.NET` · `TypeScript` · `Python` · `Go` · `Dart / Flutter` · `PostgreSQL` · `ClickHouse` · `Docker` · `Kubernetes` · and whatever the next bug demands

## Connect

- GitHub: [@nrzz](https://github.com/nrzz)
- Email: [nareshprabu18@gmail.com](mailto:nareshprabu18@gmail.com)
- Location: Bangalore, India
- Open to collaboration, and available for work on .NET backends, observability and messaging.

---

*Breaking things on my machine so they don't break on yours.*
