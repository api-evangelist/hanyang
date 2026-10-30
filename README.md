# Hanyang University

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

Hanyang University is a private research university in Seoul and Ansan (ERICA), South Korea, ROR https://ror.org/046865y68. Unusually for this cohort it operates a genuine, institution-built API programme rather than a set of vendor tenancies: the HYU Open API Developer Center at api.hanyang.ac.kr publishes REST endpoints returning XML or JSON across twelve service categories (academic records, campus life, administration, research, careers, library, alumni giving, volunteering and more), backed by its own OAuth 2.0 authorization server, Android and iOS SDKs, an API console, a developer community and a full published error-code table. The catch is that the API catalogue itself is member-only: /api/search.page renders an empty template to anonymous visitors and app keys are issued only after manual administrator approval, so no endpoint list, scope list or machine-readable contract is publicly enumerable. The one openly callable institution-operated API is the OAI-PMH 2.0 interface on Hanyang's own DSpace repository at repository.hanyang.ac.kr, which answers Identify, ListMetadataFormats and ListSets correctly but returned noRecordsMatch to every harvest request probed. Its research-output and thesis surfaces are vendor tenancies (ScholarWorks/Bwise, KERIS dCollection), it registers DOIs through eight institute-level Crossref memberships rather than centrally, and it publishes no SAML identity-provider metadata to KAFE or eduGAIN while eleven of its Korean peers do.

**Areas:** Education · Higher Education · University · South Korea · Seoul · Research Repository · OAI-PMH · Authentication · OpenAPI · Identity Federation

## Hanyang University on APIs.io

Everything profiled for Hanyang University is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/hanyang/](https://apis.io/providers/hanyang/)** — or go straight to one of the APIs or properties below.

### APIs (7)

- [Hanyang University Open API Developer Center](https://apis.io/apis/hanyang/developer-center/) — Hanyang University's own Open API platform, built and run by the university rather than bought from a vendor. REST endpoints under…
- [Hanyang University Open API SDKs](https://apis.io/apis/hanyang/sdk/) — Software development kits published by the Hanyang University Developer Center for building against the Open APIs — Android and iOS SDKs and server-side…
- [Hanyang ScholarWorks (research-output tenancy)](https://apis.io/apis/hanyang/scholarworks/) — Hanyang University's current research information system and research-output portal, run as a tenancy on the Bwise ScholarWorks platform, one instance per…
- [Hanyang dCollection (thesis and dissertation tenancy)](https://apis.io/apis/hanyang/dcollection/) — Online submission and access for Hanyang University theses and dissertations, hosted on the KERIS dCollection platform. Recorded as a relationship only; no…
- [Crossref DOI registration (institute-level memberships)](https://apis.io/apis/hanyang/crossref/) — Hanyang registers DOIs through Crossref at the research-institute level rather than centrally. Members and prefixes verified on 2026-09-01: Hanyang…
- [ROR registration](https://apis.io/apis/hanyang/ror/) — Research Organization Registry identifier for Hanyang University, the stable machine-readable identity other systems resolve the institution by.
- [Hanyang University OAI PMH API](https://apis.io/apis/hanyang/hanyang-oai-pmh-api/) — Open Archives Initiative Protocol for Metadata Harvesting 2.0

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### JSON-LD (1)

Linked-data contexts for the provider's vocabulary.

- [Hanyang Context](https://apis.io/jsonld/hanyang/hanyang-context/)

#### Security (2)

Authentication, trust centre, and vulnerability disclosure.

- [Hanyang Domain Security](https://apis.io/security/hanyang/hanyang-domain-security/)
- [Hanyang Open Api Authentication](https://apis.io/security/hanyang/hanyang-open-api-authentication/)

#### Plans and pricing (1)

Published plans, tiers and prices.

- [Hanyang Plans Pricing](https://apis.io/plans/hanyang/hanyang-plans-pricing/)

#### Rate limits (1)

Published request limits.

- [Hanyang Rate Limits](https://apis.io/rate-limits/hanyang/hanyang-rate-limits/)

#### FinOps (1)

What the API costs to run, by operation.

- [Hanyang Finops](https://apis.io/finops/hanyang/hanyang-finops/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Website](https://www.hanyang.ac.kr/web/eng)
- [Documentation](https://api.hanyang.ac.kr/develop/guide.page)
- [Blog](https://blog.naver.com/hanyang-univ)
- [Terms of service](https://api.hanyang.ac.kr/member/join_step01.page)
- [Privacy policy](https://portal.hanyang.ac.kr/PiopAct/piopMainDaepyoWeb.do)

## API Evangelist rating

**Kin Score 27.7** — thin · rubric 0.24.0 · scored 2026-10-17

| Facet | Score |
|---|---|
| Discoverability | 57.1 |
| Contract quality | 22.0 |
| Contract governance | 0.0 |
| Operational transparency | 7.9 |
| Developer ergonomics | 33.3 |
| Access clarity | 39.5 |

**Agent readiness 20.1** — agent-aware

| Agent-readiness dimension | Result |
|---|---|
| Spec Presence | yes |
| Agentic Access | — |
| Reversibility Documented | na |
| MCP Server | — |
| Auth Clarity | bearer (partial credit) |
| Idempotency | na |
| Error Semantics | — |
| OpenAPI Examples | documented (partial credit) |
| Rate Limit Signal | derived (partial credit) |
| Event Surface Described | — |
| Agent Skills | — |
| Well Known Catalog | — |
| Consent Identity | — |
| Agent Card | — |
| Dry Run Mode | na |
| Delegated Identity | — |
| Protected Resource Metadata | — |
| Dynamic Client Registration | — |
| Agentic Commerce | — |

**Regulatory alignment 24.5** — Education & Research

The rubric is published at [github.com/api-evangelist/kin-score](https://github.com/api-evangelist/kin-score). The per-check breakdown behind these numbers — which checks were earned, partial or missed — along with score history and how this provider compares to its peers, is available at [apis.io/providers/hanyang/](https://apis.io/providers/hanyang/).

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for Hanyang University: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/hanyang/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).
