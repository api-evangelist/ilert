# ilert

ilert is an AI-first incident management and on-call alerting platform that helps IT and DevOps teams manage alert sources, on-call schedules, escalation policies, incidents, and notification routing. The platform provides a comprehensive REST API for programmatic access to all platform resources.

## Overview

- **Website:** https://www.ilert.com/
- **Documentation:** https://docs.ilert.com/developer-docs
- **API Reference:** https://docs.ilert.com/developer-docs/rest-api/api-reference
- **GitHub Org:** https://github.com/iLert
- **Status Page:** https://status.ilert.com/
- **Blog:** https://www.ilert.com/blog
- **Pricing:** https://www.ilert.com/pricing
- **LinkedIn:** https://www.linkedin.com/company/ilert-alerting/
- **X:** https://twitter.com/ilerthq

## API

The ilert REST API base URL is `https://api.ilert.com`. Authentication uses Bearer token API keys generated in the ilert web application. The API covers 35+ resource categories including:

- Alerts and Alert Sources
- Escalation Policies
- On-Call Schedules
- Heartbeat Monitors
- Status Pages
- Event Flows and Call Flows
- Incidents and Incident Templates
- Services and Service Outages
- Metrics and Metric Data Sources
- Connectors and Integrations
- Teams, Users, and Contacts
- Deployment Pipelines and Deployment Events
- Reports

## SDKs and Tools

- **Go SDK:** https://github.com/iLert/ilert-go
- **JavaScript/TypeScript SDK:** https://github.com/iLert/ilert-js
- **Rust SDK:** https://github.com/iLert/ilert-rust
- **Terraform Provider:** https://github.com/iLert/terraform-provider-ilert
- **ilagent CLI:** https://github.com/iLert/ilagent
- **MCP Server:** https://github.com/iLert/mcp-ilert
- **Kubernetes Agent:** https://github.com/iLert/ilert-kube-agent
- **GitHub Action:** https://github.com/iLert/ilert-deployment-events-action

## Pricing

| Plan | Price | Users |
|------|-------|-------|
| Free | EUR 0/month | Up to 5 |
| Pro | EUR 24/user/month | Min 3 |
| Scale | EUR 49/user/month | Min 3 |
| Enterprise | Custom | Min 3 |

Annual billing provides a 20% discount. 14-day free trial available.

## Repository Contents

- `apis.yml` — APIs.json 0.19 provider profile
- `plans/ilert-plans-pricing.yml` — API Commons Plans 0.1 pricing details
- `rate-limits/ilert-rate-limits.yml` — API Commons Rate Limits 0.1
- `finops/ilert-finops.yml` — FinOps Framework 1.0 cost optimization guidance

## Maintainer

**Kin Lane** — kin@apievangelist.com
