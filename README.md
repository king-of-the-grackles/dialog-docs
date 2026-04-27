<p align="center">
  <img src="logo/dark.png" alt="Dialog" width="200" />
</p>

<h3 align="center">10x your product team. Not your headcount.</h3>

<p align="center">
  Deploy AI agents that run research, monitor competitors, and surface insights continuously.<br/>
  Your team makes better decisions. Dialog does the legwork.
</p>

<p align="center">
  <a href="https://docs.dialog.tools">Documentation</a> &nbsp;&middot;&nbsp;
  <a href="https://app.dialog.tools">Get Started</a> &nbsp;&middot;&nbsp;
  <a href="https://dialog.tools">Website</a>
</p>

---

## What is Dialog?

Dialog is an AI agent platform that gives product teams a parallel workforce of specialized assistants. Each agent has its own persistent workspace, access to 74+ connected tools, and memory that builds over time.

- **Start with a Chief of Staff** — Every account begins with a default agent. Add specialized presets (Social Media Manager, Product Analytics Agent) or build custom personas as you scale
- **74+ tools connected** — Research across Reddit, social media, web, Gmail, Slack, Jira, Linear, Notion, and more
- **Persistent workspace** — Every link saved, every research note, every task tracked across sessions
- **Multi-channel delivery** — Get briefings via Telegram or Slack today (Discord and WhatsApp coming soon)
- **Custom skills & scheduling** — Teach your agents reusable workflows and automate recurring research

## What people use Dialog for

| Use Case | Example |
|---|---|
| **Competitive intelligence** | Monitor competitor positioning, pricing changes, and product launches |
| **Research** | Deep-dive any topic across Reddit, social media, and the web with sourced citations |
| **Content creation** | Ideate LinkedIn posts, draft marketing copy, iterate on messaging |
| **Saving & organizing** | Send links to your agent — it scrapes, enriches, tags, and files them |
| **Scheduled briefings** | Set up daily or weekly monitoring pushed to you automatically |
| **Task management** | Track to-dos, milestones, and action items conversationally |

## Documentation

This repo contains the source for [docs.dialog.tools](https://docs.dialog.tools). The docs cover:

- **Getting Started** — Account creation, quickstart, first query
- **Core Concepts** — Agents, memory & workspace, tools, skills, scheduling, channels
- **Features** — Research chat, Reddit feeds, real-time streaming, session management
- **Guides** — Effective queries, content creation, Telegram delivery, billing, and more
- **Support** — FAQ and troubleshooting

## Quick start

1. Sign up at [app.dialog.tools](https://app.dialog.tools) — free, no credit card required
2. Start chatting with your default agent
3. Try: *"What are people saying about [competitor] on Reddit?"*

See the full [Quickstart Guide](https://docs.dialog.tools/quickstart) for more.

## Development

This documentation site is built with [Mintlify](https://mintlify.com).

### Running locally

```bash
# Install the Mintlify CLI
npm i -g mintlify

# Start the dev server
mintlify dev
```

The site will be available at `http://localhost:3000`.

### Project structure

```
├── introduction.mdx          # Landing page
├── quickstart.mdx             # Quick start guide
├── getting-started/           # Onboarding flow
├── core-concepts/             # Architecture & system design
│   ├── agents/
│   ├── memory/
│   └── tools/
├── features/                  # Feature descriptions
├── guides/                    # How-to guides
├── support/                   # FAQ & troubleshooting
├── logo/                      # Brand assets
└── docs.json                  # Site configuration
```

### Contributing

1. Create a branch for your changes
2. Run `mintlify dev` to preview locally
3. Submit a pull request

## License

Copyright Dialog. All rights reserved.
