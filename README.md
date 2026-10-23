# Fabián Castaño

**Engineering Manager · Odoo Expert · Agentic Engineer**

15+ years building business software, 8+ of them on Odoo (v13–v20, Community and Enterprise). Today I build AI agents that operate real business systems — ERPs, CRMs, websites — and the governance that keeps them safe to run in production.

Those agents work on live customer data every day, at the companies I work with and at DonPedroFactura.Com, my software factory for Odoo in Latin America. That is why I care as much about what an agent *cannot* do as about what it can.

📄 [Résumé (English)](CV.md) · [Hoja de vida (Español)](CV.es.md)

---

## Featured

### [odoo-mcp-governed](https://github.com/fabiancasta/odoo-mcp-governed)
An MCP server that lets AI agents work inside Odoo — with every tool call policy-checked, risk-scored and recorded in a tamper-evident audit log before it can touch the ERP.

- **Policy:** default deny; separate read / write / delete gates; a denylist no allowlist can override; production profiles read-only by default.
- **Behavioural detection:** 8 detectors (delete bursts, mass reads, allowlist probing, privilege drift…) feeding a decayed per-agent risk score → allow, flag, throttle or block.
- **Forensics:** hash-chained, HMAC-sealed audit log; editing or deleting a single past event is detected and located.
- **Engineering:** MCP protocol implemented from scratch (stdio + HTTP), 18 tools, admin panel with zero JavaScript, hardened Docker, 215 tests — key security tests mutation-checked.

---

## How I work with AI agents

I build *with* agents as well as *for* them. Most of my code is written in pair with Claude (Claude Code); commits that were co-authored are labelled as such. My job in that loop is the part that does not delegate well: deciding what must never happen, writing the tests that prove it cannot, and checking — by breaking the code on purpose — that those tests actually fail when the protection is removed.

**Stack:** Python · Odoo 13–20 · Model Context Protocol · Claude API / Claude Code · LangChain / LangGraph · FastAPI · PostgreSQL · Docker · Linux

📍 Medellín, Colombia · 💼 [LinkedIn](https://www.linkedin.com/in/fabian-castano/) · 🌐 [posdonpedro.com](https://posdonpedro.com)
