# Afro.tools

> AI-ready infrastructure for African APIs.

Afro.tools is an open registry of structured, verified API specs
for African providers. Each spec is machine-readable, executable,
and consumed directly by AI coding agents via MCP.

---

## What's in this registry

Every spec contains three things:

- `schema.json` — machine-readable description of the API capability
- `canonical_example.ts` — executable TypeScript integration pattern
- `gotchas[]` — what the official docs don't tell you

---

## Use with your AI coding agent

**MCP server** — works with any MCP-compatible client:
Claude Code, Cursor, VS Code Copilot, Windsurf, and more.
```json
{
  "mcpServers": {
    "afrotools": {
      "type": "http",
      "url": "https://mcp.afro.tools/mcp"
    }
  }
}
```

**Claude Code plugin** — one-command install with auto-activation:
```bash
/plugin marketplace add afrotools/afrotools
/plugin install afrotools
```

**SKILL.md** — compatible with Claude Code, Cursor, Gemini CLI,
Codex, and other agents that support the skill format.
The skills are in `plugin/skills/` and can be used standalone.

---

## Repositories

| Repo | Description |
|---|---|
| [afrotools](https://github.com/afrotools/afrotools) | Registry — specs + plugin |
| [examples](https://github.com/afrotools/examples) | Working Next.js examples |
| mcp *(private)* | MCP server — Streamable HTTP |
| core *(private)* | Landing page + infrastructure |

---

## Providers

| Provider | Category | Status |
|---|---|---|
| Paycard | Payment | ✅ Verified |
| LengoPay | Payment | ✅ Verified |
| Wave | Payment | 📋 Planned |
| Djomy | Payment | 📋 Planned |
| Bictorys | Payment | 📋 Planned |
| NimbaSMS | SMS | 📋 Planned |

---

## Contribute

Want to add a provider? See
[CONTRIBUTING.md](https://github.com/afrotools/afrotools/blob/main/CONTRIBUTING.md).

---

[afro.tools](https://afro.tools) · Apache 2.0
