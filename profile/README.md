# Afro.tools

> Intègre Wave, Paycard ou Orange Money en moins d'une heure.
> Ton agent IA génère le code correct du premier coup.

Afro.tools est un registre open source de specs d'APIs africaines —
machine-readable, vérifiées contre les APIs réelles, consommées
directement par les agents IA via MCP.

---

## Démarrer en 30 secondes

**Claude Code — plugin (recommandé)**
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

| Provider | Catégorie | Pays | Capabilities | Statut |
|----------|-----------|------|-------------|--------|
| Paycard | payment | 🇬🇳 | 3 | ✅ AI Ready |
| Djomy | payment | 🇬🇳 | 7 | 4 verified · 3 ready |
| LengoPay | payment | 🇬🇳 | 8 | 2 verified · 6 ready |
| Wave | payment | 🇸🇳 🇨🇮 🇲🇱 +8 | 12 | 📋 Ready |
| NimbaSMS | sms | 🇬🇳 | 11 | 📋 Ready |
| Bictorys | payment | — | — | 🗓 Planifié |

**Légende :** ✅ AI Ready = toutes les capabilities `verified` · X verified · Y ready = en attente de validation en prod · 📋 Ready = spec validée · 🗓 Planifié = specs à venir

---

## Repos

| Repo | Description |
|------|-------------|
| [afrotools/afrotools](https://github.com/afrotools/afrotools) | Registry — specs + plugin Claude Code |
| [afrotools/examples](https://github.com/afrotools/examples) | Exemples réels — valident les specs |
| `mcp` *(privé)* | Serveur MCP — Streamable HTTP |
| `core` *(privé)* | Landing page + infrastructure |

---

[afro.tools](https://afro.tools) · [Standard ATSS](https://afro.tools/standard) · Apache 2.0
