# Markerloop

Engineering team from Almaty, Kazakhstan. We build marketplaces, e-commerce, fintech and ticketing products end to end: architecture, backend, web, mobile, payments and integrations.

The repositories here are **showcase slices** of systems we have shipped to production. Each one isolates a single hard part of a real product, with tests, CI and a short write-up of the design decisions.

| Repository | What it shows | Stack |
|---|---|---|
| [marketplace-split-payments](https://github.com/Markerloop-Team/marketplace-split-payments) | One checkout split across many sellers: commission, double-entry ledger, payouts, partial refunds | Go, PostgreSQL, Kafka |
| [pim-bulk-import](https://github.com/Markerloop-Team/pim-bulk-import) | Bulk catalogue import from Excel with per-category attribute validation | Python, FastAPI, PostgreSQL |
| [ticketing-seat-hold](https://github.com/Markerloop-Team/ticketing-seat-hold) | Seat map, 15-minute seat hold, QR tickets and entry validation | Django, Celery, Vue 3 |

**Products behind them:** a B2C marketplace inside a banking ecosystem (Alatau City Market, ex-Jmart), a wholesale B2B marketplace, a travel booking app, theatre ticketing ([vteatre.kz](https://vteatre.kz)), an event platform for Kazakhstan's national postal operator ([demoday.kz](https://demoday.kz)).

Portfolio with case studies: [markerloop.notion.site/Portfolio](https://markerloop.notion.site/Portfolio-3b1c38e36647810c84efc624f5d91f74) · Site: [markerloop.com](https://markerloop.com)
