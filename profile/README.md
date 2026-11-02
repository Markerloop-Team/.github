# Markerloop

Engineering team from Almaty, Kazakhstan. We build marketplaces, e-commerce, fintech and ticketing products end to end: architecture, backend, web, mobile, payments and integrations.

The repositories here are **showcase slices** of systems we have shipped to production. Each one isolates a single hard part of a real product, with tests, CI and a short write-up of the design decisions.

| Repository | What it shows | Stack |
|---|---|---|
| [marketplace-split-payments](https://github.com/Markerloop-Team/marketplace-split-payments) | One checkout split across many sellers: commission, double-entry ledger, payouts, partial refunds | Go, PostgreSQL, Kafka |
| [pim-bulk-import](https://github.com/Markerloop-Team/pim-bulk-import) | Bulk catalogue import from Excel with per-category attribute validation | Python, FastAPI, PostgreSQL |
| [ticketing-seat-hold](https://github.com/Markerloop-Team/ticketing-seat-hold) | Seat map, 15-minute seat hold, QR tickets and entry validation | Django, Celery, Vue 3 |

## Markerloop platform

Our own product: a shared backend and site builder where an AI agent builds and publishes sites through MCP. Go microservices behind one gateway; each repo is a source snapshot with tests and a design write-up.

| Repository | Role |
|---|---|
| [mcp-service](https://github.com/Markerloop-Team/mcp-service) | MCP server: 36 tools an AI agent uses to build and publish sites |
| [auth-service](https://github.com/Markerloop-Team/auth-service) | Sessions, workspace tokens, OAuth 2.1 for MCP clients |
| [gw-service](https://github.com/Markerloop-Team/gw-service) | API gateway: routing, permission checks, workspace binding |
| [pages-service](https://github.com/Markerloop-Team/pages-service) | Routes, pages, components, themes, immutable publishing |
| [collections-service](https://github.com/Markerloop-Team/collections-service) | Workspaces, roles, CMS collections, public data API |
| [files-service](https://github.com/Markerloop-Team/files-service) | Uploads, dedup, quotas, usage index, garbage collection |
| [user-service](https://github.com/Markerloop-Team/user-service) | Users and RBAC |
| [dictionary-service](https://github.com/Markerloop-Team/dictionary-service) | Translations and reference data |
| [go-sdk](https://github.com/Markerloop-Team/go-sdk) | Shared Go SDK: JWT, middleware, response envelope |
| [dev-cli](https://github.com/Markerloop-Team/dev-cli) | Developer CLI |
| [markerloop-landing](https://github.com/Markerloop-Team/markerloop-landing) | markerloop.com (Astro) |

Live demos of products we shipped: [showroom.markerloop.com](https://showroom.markerloop.com)

**Products behind them:** a B2C marketplace inside a banking ecosystem (Alatau City Market, ex-Jmart), a wholesale B2B marketplace, a travel booking app, theatre ticketing ([vteatre.kz](https://vteatre.kz)), an event platform for Kazakhstan's national postal operator ([demoday.kz](https://demoday.kz)).

Portfolio with case studies: [markerloop.notion.site/Portfolio](https://markerloop.notion.site/Portfolio-3b1c38e36647810c84efc624f5d91f74) · Site: [markerloop.com](https://markerloop.com)
