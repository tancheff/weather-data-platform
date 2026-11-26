# Six-month roadmap

Proposed sequencing; adjust after each review. Every section has midpoint and final technical interviews. Assignments are introduced as needed.

## Month 1: Foundations and first ingestion

**Focus:** Linux, Git, Docker/Compose, provider research, Python ingestion, PostgreSQL bronze.

**Exit evidence:** Reproducible deployment; sample records; source contract and licensing; restart test.

**Assessment:** Explain design choices, demonstrate evidence and identify remaining risks.

## Month 2: Event-driven ingestion

**Focus:** Kafka producers/consumers, partitions, offsets, delivery semantics, replay.

**Exit evidence:** Demonstrate duplicate handling, restart recovery and measured throughput.

**Assessment:** Explain design choices, demonstrate evidence and identify remaining risks.

## Month 3: Data modelling and orchestration

**Focus:** Silver/gold transformations, SQL, Airflow if justified, data quality.

**Exit evidence:** Document grain, lineage, backfill, idempotency and freshness checks.

**Assessment:** Explain design choices, demonstrate evidence and identify remaining risks.

## Month 4: Observability and serving

**Focus:** Grafana and Prometheus together, REST API, service health.

**Exit evidence:** Dashboard, actionable alert, API contract and controlled incident drill.

**Assessment:** Explain design choices, demonstrate evidence and identify remaining risks.

## Month 5: Reliability and delivery

**Focus:** Pytest, Flyway, CI/CD, environment separation, security, backup and recovery.

**Exit evidence:** Tests, migration rehearsal, restore verification and release procedure.

**Assessment:** Explain design choices, demonstrate evidence and identify remaining risks.

## Month 6: Production readiness and portfolio

**Focus:** Load tests, blind incidents, trade-off review, documentation; optional ML.

**Exit evidence:** Measured limits, postmortem, final architecture review and interview.

**Assessment:** Explain design choices, demonstrate evidence and identify remaining risks.
