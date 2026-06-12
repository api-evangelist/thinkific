# Thinkific (thinkific)

Thinkific is an online course creation and delivery platform that enables creators and businesses to build, market, and sell courses, communities, and digital products. The Thinkific Admin REST API provides programmatic access to site data including courses, enrollments, users, products, orders, bundles, and groups. The Webhooks API (v2) delivers real-time event notifications for user actions, payment events, product changes, and lead captures. API access is available on the Grow plan and above, with higher rate limits available to Plus customers.

**APIs.json:** https://raw.githubusercontent.com/api-evangelist/thinkific/refs/heads/main/apis.yml

**Naftiko:** https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=thinkific-api-evangelist&utm_content=repo

## Tags

- Online Courses
- E-Learning
- LMS
- Course Creation
- Enrollments
- Users
- Education
- Digital Products
- Webhooks

## APIs

### Thinkific Admin REST API

The Thinkific Admin REST API exposes endpoints for managing courses, enrollments, users, products, orders, bundles, groups, and site data. Authentication is via API key or OAuth. The base URL is `https://api.thinkific.com/api/public/v1`.

- **Documentation:** https://developers.thinkific.com/api/api-documentation
- **Base URL:** https://api.thinkific.com/api/public/v1

### Thinkific Webhooks API

The Thinkific Webhooks API (v2) provides real-time event-driven notifications for site events including user creation, enrollment changes, order processing, product updates, lead captures, payment events, and user deletions. Webhooks can be created programmatically using an API key.

- **Documentation:** https://developers.thinkific.com/api/webhooks-api/
- **Base URL:** https://api.thinkific.com/api/v2

## Plans / Rate Limits / FinOps

- **Plans:** [plans/thinkific-plans-pricing.yml](plans/thinkific-plans-pricing.yml) — Four tiers: Start ($99/mo), Grow ($199/mo, API access), Expand ($499/mo), and Plus (custom enterprise). API and webhook access requires the Grow plan or above.
- **Rate Limits:** [rate-limits/thinkific-rate-limits.yml](rate-limits/thinkific-rate-limits.yml) — 120 requests/minute, 10 concurrent in-flight requests. HTTP 429 on limit exceeded with RateLimit-Reset header. Higher limits for Plus customers.
- **FinOps:** [finops/thinkific-finops.yml](finops/thinkific-finops.yml) — Subscription model with annual discounts of 25-33%. Optional up-to-5% per-transaction surcharge when using external Stripe instead of Thinkific Payments.

## Timestamps

- **Created:** 2026-06-12
- **Modified:** 2026-06-12

## Common Properties

| Type | URL |
|------|-----|
| Website | https://www.thinkific.com |
| Documentation | https://developers.thinkific.com/api/api-documentation |
| Getting Started | https://support.thinkific.dev/hc/en-us/articles/4422684433815-Getting-Started-with-Thinkific |
| GitHub Organization | https://github.com/thinkific |
| LinkedIn | https://www.linkedin.com/company/thinkific/ |
| Blog | https://www.thinkific.com/blog/ |
| Changelog | https://developers.thinkific.com/changelog |
| Pricing | https://www.thinkific.com/pricing/ |
| Status Page | https://status.thinkific.com/ |
| X (Twitter) | https://x.com/thinkific |

## Maintainers

**Kin Lane** — kin@apievangelist.com
