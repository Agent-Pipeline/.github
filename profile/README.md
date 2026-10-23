# Agent Pipeline

> Operational data systems, reporting pipelines, and business intelligence tooling built for reliable decision support.

Agent Pipeline is a collection of production repositories focused on data engineering, automation, reporting, and operational analytics. The organization brings together ETL workflows, reusable services, internal applications, and scheduled data products that support internal teams and downstream reporting needs.

## What we build

- Data pipelines and scheduled delivery workflows
- ETL and ELT processes for reporting and integration
- Shared services for core business logic and data processing
- Operational dashboards and internal applications
- Reporting feeds and data distribution solutions

## Repository portfolio

### Core data pipelines

- [simplified-all-agent-report-pipeline](https://github.com/Agent-Pipeline/simplified-all-agent-report-pipeline) — Daily reporting pipeline delivering the S-AAR to Files.com from Snowflake.
- [integrity-downline-permissions-pipeline](https://github.com/Agent-Pipeline/integrity-downline-permissions-pipeline) — RTS reporting pipeline that helps ensure permissions are accurately reflected across systems.
- [expiring-taxpayer-pipeline](https://github.com/Agent-Pipeline/expiring-taxpayer-pipeline) — Weekly reporting pipeline for tracking missing or expiring W9s and sending updates to HubSpot.
- [unified-health-call-center-reporting](https://github.com/Agent-Pipeline/unified-health-call-center-reporting) — Scheduled Windows task workflow that collects, validates, and consolidates Health reports from shared inboxes.

### Services and platform logic

- [db-flow-service](https://github.com/Agent-Pipeline/db-flow-service) — Core carrier-processing logic and business-critical data pipeline orchestration for Agent Pipeline BI dashboards.
- [data-freshness-reporting-service](https://github.com/Agent-Pipeline/data-freshness-reporting-service) — Service that distributes data freshness reporting to agencies that request it.
- [data-consolidation-feeds](https://github.com/Agent-Pipeline/data-consolidation-feeds) — Aggregates and distributes unique carrier reporting feeds.

### Reporting and application layers

- [comparison-reporting-app](https://github.com/Agent-Pipeline/comparison-reporting-app) — Production application used for comparison report generation.
- [bi-callcenter-etl](https://github.com/Agent-Pipeline/bi-callcenter-etl) — ETL process supporting the Call Center Dashboard.

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
