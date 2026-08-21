# Welcome to Rig

**Rig is the local runtime context engine for AI coding agents.**

A Mac app that runs your projects — ports, env, git, databases, logs — and a Cloud layer for the fleet. Agents talk to Rig through MCP on the machine. You stay in charge of what is running.

<p>
  <a href="https://userig.app"><strong>userig.app</strong></a>
  ·
  <a href="https://userig.app/download">Download</a>
  ·
  <a href="https://userig.app/docs">Docs</a>
  ·
  <a href="https://community.userig.app">Community</a>
  ·
  <a href="https://status.userig.app">Status</a>
  ·
  <a href="mailto:help@tickets.userig.app">help@tickets.userig.app</a>
</p>

Public beta. Built by [Rich Harrington Ltd](https://userig.app). Source of the product lives in [`Rig-local/rig`](https://github.com/Rig-local/rig) on the `beta` branch.

---

## About the company

Rig is made by **Rich Harrington Ltd** — a small UK company. There is no big team behind the curtain. Support, shipping, and the forum are the same people who write the product.

| | |
|---|---|
| Site | [userig.app](https://userig.app) |
| Technical support | [help@tickets.userig.app](mailto:help@tickets.userig.app) |
| Everything else | [hello@userig.app](mailto:hello@userig.app) — press, partnerships, privacy |
| GitHub org | [Rig-local](https://github.com/Rig-local) |
| Product repo | [Rig-local/rig](https://github.com/Rig-local/rig) |
| Legal | Rich Harrington Ltd |

We would rather a quiet Mac app that actually boots your stack than another dashboard that pretends to.

---

## About the app

Install Rig on a Mac. Open a folder. Rig finds scripts, Procfiles, Docker Compose, Valet, PHP — and starts the right things on the right ports. It keeps a board of what is running, whose port it is, and what the logs say.

**Local first.** Unsigned, you still get projects, start/stop, logs, ports, lanes, env, sessions, the MCP hub, local databases, LAN share, and Sparkle updates. Cloud is optional: sign in when you want another Mac, a team seat, Continuity, Mesh, or a Live Link.

**Agents get a hub, not a pasted terminal.** MCP runs inside the Mac app. The agent lists projects, reads logs, starts and stops — with a token and a scope you set in Connections.

Two release tracks, independent of each other:

| Track | What it is |
|-------|------------|
| **Mac** | Sparkle-signed DMG. Check for Updates in the app. |
| **Cloud** | `api.userig.app` and the site. Version on `/changelog` and `/health`. |

Download: [userig.app/download](https://userig.app/download)

---

## What’s in the product

### Mac app

The thing you install. Menu bar, project board, command palette (⌘K), env lanes, git, managed Postgres/Redis, crash diagnose, local HTTPS, phone companion on the LAN.

Guides: [Install](https://userig.app/docs/install) · [First 10 minutes](https://userig.app/docs/first-10-minutes) · [Ports and crashes](https://userig.app/docs/ports-crashes)

### Cloud

Sign in on the Mac. Devices register themselves. Catalog is names, git URLs, and which Mac owns a project — **never the source tree**. Account dashboard: [api.userig.app/account/dashboard](https://api.userig.app/account/dashboard)

Guides: [Cloud](https://userig.app/docs/c/cloud) · [What syncs](https://userig.app/docs/sync-what-syncs)

### Mesh

Your Macs on a private network. Enroll, tags, rules (*Macs tagged X can reach Y on Z*), wake a sleeping Mac (needs a second machine on that LAN to relay), screen in. A team seat is **not** mesh access.

[userig.app/mesh](https://userig.app/mesh) · [Mesh docs](https://userig.app/docs/mesh)

### MCP (local) and ACP (cloud)

| | Who it’s for |
|---|---|
| **MCP** | Cursor, Claude Code, Codex, Copilot, Zed’s neighbours that speak MCP. Hub in Connections, usually `http://127.0.0.1:47823/mcp`. |
| **ACP** | Editors that speak Agent Client Protocol (Zed, JetBrains). Cloud service at [acp.userig.app](https://acp.userig.app). |

[MCP](https://userig.app/docs/mcp) · [ACP](https://userig.app/docs/acp) · [ACP vs MCP](https://userig.app/docs/acp-vs-mcp)

### Live Links and LAN share

QR on the office Wi‑Fi, or a branded `https://userig.app/live/{slug}` for a client. Opt-in, password optional, expires. Source stays on the Mac.

[Live Link](https://userig.app/docs/live-link)

### Continuity

Encrypted backup of **Rig setup** (projects registry, prefs, MCP, ciphertext vaults) — not repos, not `.env` plaintext. Recovery key is shown once.

[Continuity](https://userig.app/docs/continuity-scheduled)

### Teams

Invite by email. Members see shared catalog; they still need git for source. Owners manage roles (`member` / `viewer`).

[Team invites](https://userig.app/docs/team-invites)

### Gauge

A sibling Mac app — sensors and fans, same visual language, not a screen inside Rig. Optional privileged helper for fan speed.

### Rig Mail

We send transactional mail ourselves ([mail.userig.app](https://mail.userig.app)) over a Postmark-compatible API. Sign-up, reset, device linked, mesh, billing receipts. Marketing/waitlist stays on a separate broadcast provider. You do not log into Rig Mail as a customer.

### Control Room

Staff panel at [control.userig.app](https://control.userig.app). People, money, comms, product, system — tickets, flags, email templates, forum moderation. Not a customer product. Sign-in is Rig [SSO](https://github.com/Rig-local/rig/wiki/SSO) with 2FA required.

---

## How we talk to the rest of the stack

| Host | What it is |
|------|------------|
| [userig.app](https://userig.app) | Site, docs, changelog, Live Links, Sparkle appcast |
| [api.userig.app](https://api.userig.app) | Auth, fleet, mesh, billing, account dashboard |
| [community.userig.app](https://community.userig.app) | Forum — What’s shipping, What’s up next, Bugs, ideas |
| [help.userig.app](https://help.userig.app) | Tickets (agent console). Customers open tickets from Support / the form below |
| [status.userig.app](https://status.userig.app) | Public status |
| [acp.userig.app](https://acp.userig.app) | Cloud ACP |

One Rig account. Community and helpdesk agents use **Continue with Rig**. Contributor map: [wiki — Surfaces](https://github.com/Rig-local/rig/wiki/Surfaces) · [SSO](https://github.com/Rig-local/rig/wiki/SSO) · [API](https://github.com/Rig-local/rig/wiki/API)

---

## How to get help

Work top to bottom. You will get a faster answer.

1. **Docs** — [userig.app/docs](https://userig.app/docs)  
   Search, or start at [How to get help](https://userig.app/docs/get-help) and [Troubleshooting](https://userig.app/docs/troubleshooting).
2. **Status** — [status.userig.app](https://status.userig.app)  
   If Cloud or mail is down, we already know.
3. **Community** — [community.userig.app](https://community.userig.app)  
   What’s shipping, ideas, and peer help. Sign in with Rig.
4. **A ticket** — email **[help@tickets.userig.app](mailto:help@tickets.userig.app)**, or use the [Support form](https://api.userig.app/support?source=github) / **Help** in the Mac app and account dashboard.  
   Include: Mac version (`Rig → About`), Cloud version if relevant, what you did, what you expected, logs or a diagnostics bundle ([how](https://userig.app/docs/diagnostics-bundle)).

That mailbox is technical support. Press, partnerships, and privacy stay at [hello@userig.app](mailto:hello@userig.app). There is no separate enterprise hotline.

---

## How to log a bug

1. Check [status](https://status.userig.app) and search [docs](https://userig.app/docs) / [Bugs on the forum](https://community.userig.app).
2. **Preferred:** open a topic on the forum **Bugs** board (sign in with Rig). That is what we triage.
3. **Email:** [help@tickets.userig.app](mailto:help@tickets.userig.app) — same inbox as the support form.
4. **Also fine:** a GitHub issue on [`Rig-local/rig`](https://github.com/Rig-local/rig/issues).

A useful report has:

- Rig version (Mac *and* Cloud if both are involved)
- macOS version and Apple Silicon vs Intel
- Steps to reproduce, or “happened once, here is the log”
- Whether MCP / Mesh / Continuity / Live Link was in play
- Redacted logs or a diagnostics bundle — not a screenshot of a black window

Security findings: see [SECURITY.md](https://github.com/Rig-local/rig/blob/beta/docs/SECURITY.md) in the product repo, or email [hello@userig.app](mailto:hello@userig.app). Please do not file a public issue for an unreleased RCE.

Feature ideas: forum **ideas**, not a bug ticket.

---

## Contributing / reading the code

The monorepo is public. Default branch is **`beta`**.

- [Handover](https://github.com/Rig-local/rig/wiki/Handover) — start here
- [Architecture](https://github.com/Rig-local/rig/wiki/Architecture)
- [Local setup](https://github.com/Rig-local/rig/wiki/Local-Setup)
- Full wiki: [github.com/Rig-local/rig/wiki](https://github.com/Rig-local/rig/wiki)

UK English in anything a human sees. Do not rename Control Room to “admin”. Do not put vendor mesh names in product copy.

---

## Changelog and releases

- Product changelog: [userig.app/changelog](https://userig.app/changelog)
- Mac GitHub Releases: [Rig-local/rig/releases](https://github.com/Rig-local/rig/releases)
- Forum **What’s shipping** / **What’s up next** track the live `releases.json`

---

<p align="center">
  <a href="https://userig.app/download">Download Rig</a>
  ·
  <a href="https://userig.app/docs">Read the docs</a>
  ·
  <a href="https://community.userig.app">Join the community</a>
</p>
