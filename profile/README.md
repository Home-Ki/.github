# HomeKi

> **Self-hosted, modular home automation — full control, no cloud lock-in.**

HomeKi builds **HomeOS**: a Raspberry Pi gateway you reach anywhere via a Cloudflare
Tunnel — no open ports, no forced accounts, no tracking. Your home, your data, your rules.

## Principles

- 🔒 **Security by default** — JWT + mTLS, least privilege, non-negotiable.
- 🧩 **Everything is an optional container** — if one feature is down, the core keeps running.
- 🪶 **Simplicity over scale** — SQLite, in-memory maps, deliberate choices.
- 🛰️ **Reachable everywhere** — fast on your home network, seamless from anywhere.

## The system

| Component | What it does |
|---|---|
| **Gateway** | API gateway & stable core (Go) — service registry, smart proxy, JWT/mTLS auth |
| **Notify** | Real-time WebSocket push notifications (Go) |
| **Dashboard** | Admin UI (Vue 3 + TypeScript) |
| **App** | Native multi-platform user app (Flutter) |
| **Docs** | Architecture, concepts and design decisions |

## Status

🟢 **Core stable** · 🟡 apps & ecosystem in active development

---

<sub><strong>HomeKi</strong> — your home, your rules.</sub>
