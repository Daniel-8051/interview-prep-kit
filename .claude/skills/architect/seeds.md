# Scenario seeds

One-liners the architect expands into a full prompt. Tagged by flavour. Not exhaustive — the architect may generate its own, but must not repeat one already in history.md.

- [data-heavy] Design a system to ingest and store clickstream events from 50k sites, queryable for analytics within minutes.
- [data-heavy] Design a metrics/monitoring backend that ingests time-series from 100k hosts at 10s resolution.
- [latency] Design a service returning personalised feed ranking in under 100ms at p99.
- [latency] Design an ad-bidding service that must respond within a 50ms budget.
- [high-write] Design a webhook delivery system for 10k merchants guaranteeing ordered, at-least-once delivery per merchant.
- [high-write] Design a ride-location ingestion service tracking 500k active drivers updating every 3s.
- [consistency] Design an inventory system for a flash sale where overselling is unacceptable.
- [consistency] Design a distributed counter for limited-stock ticket sales across regions.
- [read-heavy] Design a URL shortener at 10k reads per write, global.
- [read-heavy] Design the read path for a social profile page hit 1M times a minute.
- [real-time] Design a collaborative document editor with presence and conflict resolution.
- [real-time] Design a live-updating sports-score fan-out to 5M concurrent clients.
- [scale-shift] Design a notification service (email/push/SMS) with per-user preferences and dedup.
- [scale-shift] Design a rate limiter usable as a shared service across 200 internal teams.
