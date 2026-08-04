# Ubidots (ubidots)

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

Ubidots is an Industrial AIoT platform designed for OEMs, system integrators, and engineering firms that need to ingest, visualize, and act on device telemetry at scale. The platform exposes a REST API (v1.6 and v2) and an MQTT API for sending and retrieving time-series data from IoT sensors and devices. Developers can manage devices, variables, dashboards, organizations, and event-triggered alerts programmatically, while serverless UbiFunctions enable custom processing logic without managing infrastructure. Authentication uses short-lived or persistent tokens passed via the `X-Auth-Token` header or URL parameter, and throughput is gated per plan from 6 dots per second (Professional) up to 1,000 dots per second on private Enterprise deployments.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/ubidots/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/ubidots/refs/heads/main/apis.yml)

**Powered by Naftiko Fleet:** [https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=ubidots-api-evangelist&utm_content=repo](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=ubidots-api-evangelist&utm_content=repo)

---

## Tags

IoT, Internet of Things, Telemetry, Time Series, MQTT, REST, Dashboards, Device Management, Analytics, Industrial IoT, AIoT

---

## APIs

| Name | Description | Docs |
|------|-------------|------|
| Ubidots Data API v1.6 | REST endpoints for device telemetry ingestion and retrieval | [Docs](https://docs.ubidots.com/v1.6/reference/http) |
| Ubidots Data API v2 | Advanced filtering, bulk operations, device provisioning | [Docs](https://docs.ubidots.com/reference/welcome) |
| Ubidots MQTT API | Lightweight MQTT-based telemetry ingestion for constrained devices | [Docs](https://help.ubidots.com/en/collections/356495-developer-guides) |

---

## Plans, Rate Limits, and FinOps

| Resource | File | Details |
|----------|------|---------|
| Plans & Pricing | [plans/ubidots-plans-pricing.yml](plans/ubidots-plans-pricing.yml) | STEM (free), Professional ($99/mo), Industrial (custom), Enterprise (custom) |
| Rate Limits | [rate-limits/ubidots-rate-limits.yml](rate-limits/ubidots-rate-limits.yml) | 4 req/s per token; 6–1,000 dots/s account-level by plan; 429 on throttle |
| FinOps | [finops/ubidots-finops.yml](finops/ubidots-finops.yml) | Subscription + metered overages for devices, dots, executions, and alerts |

---

## Timestamps

- **Created:** 2026-06-12
- **Modified:** 2026-06-12

---

## Common Properties

| Type | URL |
|------|-----|
| Website | https://ubidots.com |
| Documentation | https://docs.ubidots.com |
| GitHub Organization | https://github.com/ubidots |
| LinkedIn | https://www.linkedin.com/company/ubidots |
| X (Twitter) | https://x.com/ubidots |
| Blog | https://ubidots.com/blog |
| Changelog | https://docs.ubidots.com/changelog |
| Pricing | https://ubidots.com/pricing |
| Status Page | https://status.ubidots.com |
| Help Center | https://help.ubidots.com |

---

## Maintainers

- **Kin Lane** — [kin@apievangelist.com](mailto:kin@apievangelist.com)
