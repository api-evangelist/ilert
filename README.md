# ilert

<!-- API-EVANGELIST-PROVENANCE:BEGIN -->
> ### About this repository
>
> **This is not our API.** This repository is an independent, third-party profile of a company's
> **publicly available** API surface, maintained by [API Evangelist](https://apievangelist.com).
> API Evangelist does not operate, host, resell, or support this company's APIs, and is not
> affiliated with or endorsed by the company unless stated on the profile.
>
> **Where the information came from.** Everything here is assembled from material a member of the
> public can reach with a browser and no credentials — the company's own website, developer portal
> and documentation, the specifications it publishes for public use (OpenAPI, AsyncAPI, JSON Schema,
> `apis.json`, `llms.txt` and similar), its public repositories, and its public status, pricing and
> changelog pages. **Nothing here is obtained by breaching a system, defeating an access control, or
> using credentials of any kind.**
>
> **The rating is an independent assessment.** The Kin Score and Agent Readiness rating are
> independently calculated scores of a company's *public* API artifacts, produced by API Evangelist
> against a published rubric. They are not certifications, endorsements, security assessments, or
> audits, and they score published artifacts — not the quality, safety, or security of the software.
>
> **Corrections, re-scores, and removal are free.** No partnership, contract, or purchase is
> required, and you do not need to justify the request.
>
> - **Something wrong?** Open an issue on this repository, or email
>   [info@apievangelist.com](mailto:info@apievangelist.com).
> - **Published something new?** Ask for a re-score and we will re-run the rating.
> - **Want the listing taken down?** Say so and we will honor it. The profile is reduced to your
>   company name, a factual description, and a link to your own site, and the company is recorded as
>   **unrated** — never scored zero for having asked.
>
> **Response times.** Acknowledgement within **one business day**; removal or restriction within
> **two business days**; corrections and re-scores within **five business days**.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

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
