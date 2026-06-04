# Hanyang University (hanyang)

Hanyang University is a private research university in Seoul and Ansan, South Korea, ranked #162 in the QS World University Rankings 2025. It operates an official API Developer Center at [api.hanyang.ac.kr](https://api.hanyang.ac.kr/develop/start.page) that publishes REST-style Open APIs (XML/JSON) with OAuth authentication, Android/iOS SDKs, an API testing console, and a developer community. This repository catalogs that public developer/API footprint as an [APIs.json](https://apisjson.org) provider profile.

- APIs.json: https://raw.githubusercontent.com/api-evangelist/hanyang/refs/heads/main/apis.yml
- Run it with Naftiko: https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=hanyang-api-evangelist&utm_content=repo

## Type

- **Type:** Index
- **Position:** Consumer
- **Access:** 3rd-Party

## Tags

Education, Higher Education, University, South Korea, Seoul, Open API, OAuth

## APIs

- **Hanyang University Open API Developer Center** — REST Open APIs (XML/JSON), Public and Private (authenticated) classes, OAuth-based. Docs: https://api.hanyang.ac.kr/develop/start.page
- **Hanyang University Open API SDKs** — Android, iOS, and server-side (ASP) SDKs for building against the Open APIs. Docs: https://api.hanyang.ac.kr/develop/sdk_asp.page

Endpoint access requires developer registration and HY-in/OAuth login; individual endpoints and Private (personal-data) APIs are gated and not publicly enumerable.

## Plans, Rate Limits, and FinOps

- Plans / Pricing: [plans/hanyang-plans-pricing.yml](plans/hanyang-plans-pricing.yml)
- Rate Limits: [rate-limits/hanyang-rate-limits.yml](rate-limits/hanyang-rate-limits.yml)
- FinOps: [finops/hanyang-finops.yml](finops/hanyang-finops.yml)

## Timestamps

- Created: 2026-06-03
- Modified: 2026-06-03

## Common Properties

- Website: https://www.hanyang.ac.kr/web/eng
- Developer Portal: https://api.hanyang.ac.kr/develop/start.page
- Authentication (OAuth): https://api.hanyang.ac.kr/oauth/login
- LinkedIn: https://www.linkedin.com/company/hanyang-university

## Notes

- The API Developer Center landing and SDK pages return HTTP 200 and are publicly readable; the actual Open API endpoints (base path `https://api.hanyang.ac.kr/rs/`) are gated behind developer registration and OAuth, so specific endpoints are not listed here.
- No official university-wide GitHub organization was found — only research labs and student projects (e.g., HYU-NLP, hyuabot, BusHanyang). No GitHub common pointer is therefore claimed.
- The official English homepage returns 403 to automated probes but is the confirmed official site.
- No endpoints were fabricated; only verified, publicly reachable URLs are recorded. See [review.yml](review.yml).

## Maintainers

- Kin Lane — kin@apievangelist.com
