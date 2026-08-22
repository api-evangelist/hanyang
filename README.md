# Hanyang University (hanyang)

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
> **Not from the company, and here with a question?** You are welcome here — we would rather be the
> front line and point you the right way than have a good report go nowhere. What this repository
> can answer is narrow, though, so it is worth knowing who you are actually looking for:
>
> - **A question about how the API works, an account, billing, or a bug in the service** — that is
>   the company's own support, not us. We profile this API; we do not operate it and cannot see
>   your account.
> - **A bug in an open-source project we only catalog** — file it on that project's own repository.
>   This has happened with a real and correct bug report that reached us instead of the people who
>   could fix it, which helped nobody.
> - **Anything about this listing itself** — the description, the tags, the rating, a missing or
>   wrong artifact — is ours. Open an issue here.
> - **Not sure, or something general about API Evangelist or APIs.io** — open an issue on the
>   [APIs.io Inbox](https://github.com/api-search/inbox) and we will route it.
>
> **This repository contains no software, and we will never ask you to download anything.** There is
> no build, release, installer, or binary here — only text and machine-readable API descriptions, so
> there is nothing here that can be "corrupt" or need "repairing". Any issue, comment, or email
> claiming otherwise and offering a download link is not from us and is hostile. Do not follow the
> link; it is a lure. Report it to GitHub and, if you like, tell us at
> [info@apievangelist.com](mailto:info@apievangelist.com) so we can take it down.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

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
