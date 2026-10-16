# Rig

One app runs your local projects. Processes, ports, logs, env, and databases stay on the machine. Your source code stays there too.

It is on **Mac** and **Windows**. **UseRig** on iPhone is the companion for machines you have paired. Optional Cloud is for the fleet — another machine, a team, Mesh, a Live Link — not a remote IDE.

Coding agents talk to Rig through MCP. The public one is [api.userig.app/mcp](https://api.userig.app/mcp). The full hub stays on the machine when the app is open. You set what they can see and do.

Made in England. The company is **RigLabs Corp**.

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
</p>

---

## Company

| | |
|---|---|
| Company | RigLabs Corp |
| Address | 1007 N Orange St. 4th Floor Suite #6227, Wilmington, Delaware 19801, United States |
| Support | [help@tickets.userig.app](mailto:help@tickets.userig.app) |
| Press, partnerships, privacy | [hello@userig.app](mailto:hello@userig.app) |

---

## Get it

Current builds are on [userig.app/download](https://userig.app/download). Mac updates itself. Windows is a public x64 beta with its own version. iPhone is on the same page.

[Changelog](https://userig.app/changelog)

---

## What you can do with it

- Start, stop, and watch the processes in a project, with the logs and ports in one place.
- Keep Postgres, Redis, env, and git next to that project.
- Let an agent read health and logs, and restart something, without a pasted terminal.
- Sign in when you want Cloud: devices, teams, Continuity backups of your Rig setup (not the repo), Mesh between your machines, or a Live Link for a client.
- Open the fleet from UseRig on iPhone. Mesh only reaches machines you paired.

Local use is free in beta. Mesh is the paid line. Plans are on [userig.app/pricing](https://userig.app/pricing).

---

## Public MCP

One plugin for the agents. Repo: [Rig-local/rig-plugin](https://github.com/Rig-local/rig-plugin). Endpoint: `https://api.userig.app/mcp`. The agent signs in in the browser. Docs: [userig.app/docs/mcp](https://userig.app/docs/mcp).

| Agent | Plugin |
|---|---|
| Claude | [Claude plugin](https://github.com/Rig-local/rig-plugin/tree/main/.claude-plugin) |
| ChatGPT and Codex | [Codex plugin](https://github.com/Rig-local/rig-plugin/tree/main/.codex-plugin) |
| Cursor | [Cursor plugin](https://github.com/Rig-local/rig-plugin/tree/main/.cursor-plugin) |
| Gemini | [Gemini extension](https://github.com/Rig-local/rig-plugin/blob/main/gemini-extension.json) |
| Copilot | Same MCP URL in VS Code |
| Grok | [Grok plugin](https://github.com/Rig-local/rig-plugin/tree/main/.grok-plugin) |

Cloud MCP can list projects, read health and ports, and start, stop, or restart after you confirm. Live logs and the rest of the hub need the app open and linked on that machine.


---

## Help

1. [Docs](https://userig.app/docs) — start at [How to get help](https://userig.app/docs/get-help).
2. [Status](https://status.userig.app) — if Cloud or mail is down, we already know.
3. [Community](https://community.userig.app) — what’s shipping, ideas, and bugs. Sign in with Rig.
4. [help@tickets.userig.app](mailto:help@tickets.userig.app) or the [support form](https://api.userig.app/support?source=github).

Include the app version, Mac or Windows, what you did, and what you expected. Security findings go to [hello@userig.app](mailto:hello@userig.app).

