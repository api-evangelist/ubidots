# Ubidots (ubidots)

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
