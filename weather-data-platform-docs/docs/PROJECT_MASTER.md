# Project master

## Objective
Progress from strong mid-level to senior data engineer through a solo, production-inspired project. Learning and engineering reasoning take precedence over optimization and feature count.

## Scope
Collect weather observations and forecasts, preferably European, with historical data where available. Prefer live or near-live ingestion; frequent scheduled collection is an acceptable fallback. Expose curated data through a REST API. Weather prediction using ML is optional and belongs at the end.

## Constraints
- Six months, 8–10 hours weekly (approximately 208–260 hours over 26 weeks).
- Develop locally and deploy to a dedicated Linux VM; distribution and deployment workflow remain undecided.
- Free/open-source first; discuss paid dependencies before adoption.
- Docker Compose, containerized services, independently deployable microservices where justified.
- PostgreSQL medallion layers: separate bronze, silver and gold databases on one instance as the initial design to evaluate.
- Start with one environment; introduce additional environments later.
- Grafana and Prometheus introduced together. Pytest and Flyway introduced later. Other tools require justification.
- Public portfolio: no secrets, private host details, proprietary data or unverified claims.

## Learning approach
Make a simple solution work, then examine assumptions, scaling, failure conditions and verification. Use requirements-only assignments, independent research, design reviews and technical interviews at the midpoint and end of each section. No Agile ceremonies; high-level monthly tasks with assignments added as needed. Mentor provides no implementation code unless explicitly requested. Incident drills initially disclose symptoms and root cause; later disclose symptoms only.

## Success criteria
A reproducible platform with documented data contracts, replay and idempotency, measurable freshness and quality, monitoring, recovery drills, tests, migration discipline and a defensible architecture. Evidence of learning matters more than adding tools.

## Open decisions
Weather provider and licensing; Linux distribution; collection cadence; data model and retention; Kafka topology; service boundaries; orchestration requirements; resource budgets; SLO targets; API contract; CI/CD and environment promotion. Record decisions as ADRs before treating them as settled.

See [roadmap](ROADMAP.md), [architecture](ARCHITECTURE.md) and [mentoring prompt](PROJECT_PROMPT.md).
