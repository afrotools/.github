# Afro.tools

> Integrate Wave, Paycard, or Orange Money in under an hour.
> Your AI agent generates correct code on the first try.

Afro.tools is an open-source registry of African API specs —
machine-readable, verified against live APIs, consumed directly
by AI agents via MCP.

---

## Get started in 30 seconds

**Claude Code — plugin (recommended)**
```bash
/plugin marketplace add afrotools/afrotools
/plugin install afrotools
```

**Cursor / Windsurf / VS Code Copilot**
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

---

## Providers

| Provider | Category | Country | Capabilities | Status |
|----------|----------|---------|--------------|--------|
| Paycard | payment | 🇬🇳 | 3 | ✅ AI Ready |
| Djomy | payment | 🇬🇳 | 7 | 4 verified · 3 ready |
| LengoPay | payment | 🇬🇳 | 8 | 2 verified · 6 ready |
| Wave | payment | 🇸🇳 🇨🇮 🇲🇱 +8 | 12 | 📋 Ready |
| NimbaSMS | sms | 🇬🇳 | 11 | 📋 Ready |
| Bictorys | payment | — | — | 🗓 Planned |

**Legend:** ✅ AI Ready = all capabilities `verified` · X verified · Y ready = awaiting production validation · 📋 Ready = spec validated · 🗓 Planned = specs coming soon

---

## Repos

| Repo | Description |
|------|-------------|
| [afrotools/afrotools](https://github.com/afrotools/afrotools) | Registry — specs + Claude Code plugin |
| [afrotools/examples](https://github.com/afrotools/examples) | Real examples — validate the specs |
| `mcp` *(private)* | MCP server — Streamable HTTP |
| `core` *(private)* | Landing page + infrastructure |

---

[afro.tools](https://afro.tools) · [ATSS Standard](https://afro.tools/standard) · Apache 2.0
