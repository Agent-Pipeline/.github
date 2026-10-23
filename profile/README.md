# Agent Pipeline

> Operational data systems, reporting pipelines, and business intelligence tooling built for reliable decision support.

Agent Pipeline is a collection of production repositories focused on data engineering, automation, reporting, and operational analytics. The organization brings together ETL workflows, reusable services, and business-facing reporting tools designed to support dependable operational decision-making.

## What we build

- Data pipelines and scheduled delivery workflows
- ETL and ELT processes for reporting and integration
- Shared services for core business logic and data processing
- Operational dashboards and internal applications
- Reporting feeds and data distribution solutions

## Repository portfolio

### Core data pipelines

- [Daily reporting pipeline](https://github.com/Agent-Pipeline/simplified-all-agent-report-pipeline) — Delivers the S-AAR output to Files.com from Snowflake.
- [RTS reporting pipeline](https://github.com/Agent-Pipeline/integrity-downline-permissions-pipeline) — Helps ensure permissions are accurately reflected across downstream systems.
- [Weekly compliance reporting pipeline](https://github.com/Agent-Pipeline/expiring-taxpayer-pipeline) — Tracks missing or expiring W9s and sends updates to HubSpot.
- [Health reporting workflow](https://github.com/Agent-Pipeline/unified-health-call-center-reporting) — Collects, validates, and consolidates health reporting data from shared inbox sources.

### Services and platform logic

- [Core processing service](https://github.com/Agent-Pipeline/db-flow-service) — Houses core carrier-processing logic and orchestrates critical data pipeline workflows.
- [Data freshness reporting service](https://github.com/Agent-Pipeline/data-freshness-reporting-service) — Distributes data freshness reporting to agencies that request it.
- [Consolidated reporting feeds](https://github.com/Agent-Pipeline/data-consolidation-feeds) — Aggregates and distributes unique carrier reporting feeds.

### Reporting and application layers

- [Comparison reporting application](https://github.com/Agent-Pipeline/comparison-reporting-app) — Supports production report generation for comparison-based analysis.
- [Call center reporting ETL](https://github.com/Agent-Pipeline/bi-callcenter-etl) — Powers ETL processing for the Call Center Dashboard.

## Focus areas

### Data engineering
Automating ingestion, transformation, and delivery of business-critical data across reporting pipelines and operational workflows.

### Reporting and analytics
Supporting dashboards, downstream file delivery, and operational reporting for internal stakeholders and business partners.

### Quality and governance
Providing validation, monitoring, and structured processing patterns to improve data trust and operational reliability.

### Reusable platform capabilities
Building services and shared logic that can be reused across multiple reporting and automation use cases.

## Engineering standards

- Production-ready automation over manual execution
- Clear data validation and monitoring at key handoff points
- Repository documentation that explains purpose, inputs, outputs, and dependencies
- Pull request review and collaborative change management
- Semantic commit conventions for maintainable history and clearer release tracking

## Repository conventions

Our repositories are organized around clear operational themes and naming patterns, including:

- `-pipeline` for scheduled data movement and delivery workflows
- `-etl` for extraction and transformation processes
- `-service` for shared business logic and orchestration
- `-app` for application-layer tooling and reporting experiences
- `-feeds` for reporting distribution and feed-based integrations

## Explore the org

Browse the repositories above to see the breadth of the Agent Pipeline ecosystem, from data movement and processing to operational reporting and business-facing applications.

---

Built to support reliable data workflows, accountable reporting, and operational insight at scale.
