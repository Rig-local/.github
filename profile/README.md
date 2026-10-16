# Welcome to Rig

**Rig is the local runtime context engine for AI coding agents.**

A desktop app that runs your projects — ports, env, git, databases, logs — and an optional Cloud layer for the fleet. Agents talk to Rig through MCP on the machine. You stay in charge of what is running.

Made in England. Shipped by [RigLabs Corp](https://userig.app).

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

---

## About the company

Rig is **made in England**. The company is **RigLabs Corp**.

Support, shipping, and the forum are the same people who write the product. There is no big team behind the curtain.

| | |
|---|---|
| Site | [userig.app](https://userig.app) |
| Company | RigLabs Corp |
| Address | 1007 N Orange St. 4th Floor Suite #6227, Wilmington, Delaware 19801, United States |
| Technical support | [help@tickets.userig.app](mailto:help@tickets.userig.app) |
| Everything else | [hello@userig.app](mailto:hello@userig.app) — press, partnerships, privacy |
| GitHub org | [Rig-local](https://github.com/Rig-local) |

We would rather a quiet app that actually boots your stack than another dashboard that pretends to.

---

## About the app

Open a folder. Rig finds scripts, Procfiles, Docker Compose, Valet, PHP — and starts the right things on the right ports. It keeps a board of what is running, whose port it is, and what the logs say.

**Local first.** Without an account you still get projects, start/stop, logs, ports, lanes, env, the MCP hub, local databases, and updates. Cloud is optional: sign in when you want another machine, a team seat, Continuity, Mesh, or a Live Link.

**Agents get a hub, not a pasted terminal.** MCP runs inside the app. The agent lists projects, reads logs, starts and stops — with a token and a scope you set in Connections.

Current builds are on the website, not an old GitHub Release. Mac updates arrive through Sparkle. Windows has its own beta track.

| Track | What it is |
|-------|------------|
| **Mac** | Signed DMG for Apple Silicon and Intel. Check for Updates in the app. |
| **Windows** | Public x64 beta. Same product idea, its own version. |
| **iPhone** | UseRig — fleet, projects, and the Macs you have paired. |
| **Cloud** | api.userig.app and the site. Version on [/changelog](https://userig.app/changelog) and `/health`. |

**[Download Rig](https://userig.app/download)** · **[Changelog](https://userig.app/changelog)**

---

## What’s in the product

### Desktop app

The thing you install. Menu bar, project board, command palette (⌘K), env lanes, git, managed Postgres/Redis, crash diagnose, local HTTPS.

Guides: [Install](https://userig.app/docs/install) · [First 10 minutes](https://userig.app/docs/first-10-minutes) · [Ports and crashes](https://userig.app/docs/ports-crashes)

### iPhone

UseRig is the pocket companion: the fleet, projects, and Mesh only to Macs you paired. It is not a public VPN.

[Rig for iPhone](https://userig.app/iphone)

### Cloud

Sign in on the desktop. Devices register themselves. The catalog is names, git URLs, and which machine owns a project — **never the source tree**. Account dashboard: [api.userig.app/account/dashboard](https://api.userig.app/account/dashboard)

Guides: [Cloud](https://userig.app/docs/c/cloud) · [What syncs](https://userig.app/docs/sync-what-syncs)

### Mesh

Your machines on a private network. Enroll, tags, rules (*machines tagged X can reach Y on Z*), wake a sleeping Mac (needs a second machine on that LAN to relay), screen in. A team seat is **not** mesh access.

[userig.app/mesh](https://userig.app/mesh) · [Mesh docs](https://userig.app/docs/mesh)

### MCP (local) and ACP (cloud)

| | Who it’s for |
|---|---|
| **MCP** | Cursor, Claude Code, Codex, Copilot, and other editors that speak MCP. Hub in Connections, usually `http://127.0.0.1:47823/mcp`. |
| **ACP** | Editors that speak Agent Client Protocol (Zed, JetBrains). Cloud service at [acp.userig.app](https://acp.userig.app). |

[MCP](https://userig.app/docs/mcp) · [ACP](https://userig.app/docs/acp) · [ACP vs MCP](https://userig.app/docs/acp-vs-mcp)

### Live Links and LAN share

QR on the office Wi‑Fi, or a branded `https://userig.app/live/{slug}` for a client. Opt-in, password optional, expires. Source stays on the machine.

[Live Link](https://userig.app/docs/live-link)

### Continuity

Encrypted backup of **Rig setup** (projects registry, prefs, MCP, ciphertext vaults) — not repos, not `.env` plaintext. The recovery key is shown once.

[Continuity](https://userig.app/docs/continuity-scheduled)

### Teams

Invite by email. Members see the shared catalog; they still need git for source. Owners manage roles (`member` / `viewer`).

[Team invites](https://userig.app/docs/team-invites)

### Gauge

A sibling Mac app — sensors and fans, same visual language, not a screen inside Rig.

[Download Gauge](https://userig.app/download/gauge)

### Rig Mail

We send transactional mail ourselves ([mail.userig.app](https://mail.userig.app)). Sign-up, reset, device linked, mesh, billing receipts. You do not log into Rig Mail as a customer.

### Control Room

Staff panel at [control.userig.app](https://control.userig.app). People, money, comms, product, system. Not a customer product. Sign-in is Rig SSO with 2FA required.

---

## How we talk to the rest of the stack

| Host | What it is |
|------|------------|
| [userig.app](https://userig.app) | Site, docs, changelog, Live Links, Mac updates |
| [api.userig.app](https://api.userig.app) | Auth, fleet, mesh, billing, account dashboard |
| [community.userig.app](https://community.userig.app) | Forum — What’s shipping, What’s up next, Bugs, ideas |
| [help.userig.app](https://help.userig.app) | Tickets. Customers open them from Support or the form below |
| [status.userig.app](https://status.userig.app) | Public status |
| [acp.userig.app](https://acp.userig.app) | Cloud ACP |

One Rig account. Community uses **Continue with Rig**.

---

## How to get help

Work top to bottom. You will get a faster answer.

1. **Docs** — [userig.app/docs](https://userig.app/docs)  
   Search, or start at [How to get help](https://userig.app/docs/get-help) and [Troubleshooting](https://userig.app/docs/troubleshooting).
2. **Status** — [status.userig.app](https://status.userig.app)  
   If Cloud or mail is down, we already know.
3. **Community** — [community.userig.app](https://community.userig.app)  
   What’s shipping, ideas, and peer help. Sign in with Rig.
4. **A ticket** — email **[help@tickets.userig.app](mailto:help@tickets.userig.app)**, or use the [Support form](https://api.userig.app/support?source=github) / **Help** in the app and account dashboard.  
   Include: app version (`Rig → About`), Cloud version if relevant, what you did, what you expected, logs or a diagnostics bundle ([how](https://userig.app/docs/diagnostics-bundle)).

That mailbox is technical support. Press, partnerships, and privacy stay at [hello@userig.app](mailto:hello@userig.app).

---

## How to log a bug

1. Check [status](https://status.userig.app) and search [docs](https://userig.app/docs) / [Bugs on the forum](https://community.userig.app).
2. **Preferred:** open a topic on the forum **Bugs** board (sign in with Rig). That is what we triage.
3. **Email:** [help@tickets.userig.app](mailto:help@tickets.userig.app) — same inbox as the support form.

A useful report has:

- Rig version (desktop *and* Cloud if both are involved)
- macOS or Windows version, and Apple Silicon vs Intel where it matters
- Steps to reproduce, or “happened once, here is the log”
- Whether MCP / Mesh / Continuity / Live Link was in play
- Redacted logs or a diagnostics bundle — not a screenshot of a black window

Security findings: email [hello@userig.app](mailto:hello@userig.app). Please do not file a public post for an unreleased vulnerability.

Feature ideas: forum **ideas**, not a bug ticket.

---

## Changelog and releases

- Product changelog: [userig.app/changelog](https://userig.app/changelog)
- Downloads: [userig.app/download](https://userig.app/download)
- Forum **What’s shipping** / **What’s up next** track the live `releases.json`

Public plugin (Cloud MCP and skills for coding agents): [Rig-local/rig-plugin](https://github.com/Rig-local/rig-plugin)

---

<p align="center">
  <a href="https://userig.app/download">Download Rig</a>
  ·
  <a href="https://userig.app/docs">Read the docs</a>
  ·
  <a href="https://community.userig.app">Join the community</a>
</p>
