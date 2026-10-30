# Forcepoint

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

Forcepoint is a data-first cybersecurity vendor whose platform spans Data Loss Prevention (DLP), Security Service Edge / SASE (Forcepoint ONE and Data Security Cloud | SSE), Next-Generation Firewall (NGFW), and web, email, and data security. For developers and security engineers Forcepoint exposes several product REST APIs — DLP policy management, SSE Config/Log/IP and SCIM 2.0 provisioning, the NGFW Security Management Center (SMC) API, and an Appliance management API — documented on help.forcepoint.com. Auth varies by product: OAuth 2.0 bearer tokens for SSE, API-key clients for the NGFW SMC, and basic/session auth for DLP and appliances. Forcepoint publishes official automation tooling including the fp-NGFW-SMC-python SDK (PyPI), Ansible modules, and a Terraform provider, and runs a public status portal and trust center (SOC 2, ISO 27001/27017/27018, CSA STAR, FIPS 140, GDPR).

**Areas:** Company · Cybersecurity · Security · Data Loss Prevention · SASE · Security Service Edge · Firewall · Data Security · Cloud Security

## Forcepoint on APIs.io

Everything profiled for Forcepoint is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/forcepoint/](https://apis.io/providers/forcepoint/)** — or go straight to one of the APIs or properties below.

### APIs (4)

- [Forcepoint Data Security Cloud | SSE REST API](https://apis.io/apis/forcepoint/forcepoint-data-security-cloud-sse-rest-api/) — Config, Log export, and IP APIs plus SCIM 2.0 user/group provisioning for Forcepoint ONE / Data Security Cloud (SSE). OAuth 2.0 bearer authentication with…
- [Forcepoint DLP REST API](https://apis.io/apis/forcepoint/forcepoint-dlp-rest-api/) — REST API for Forcepoint Data Loss Prevention policy management; JSON over HTTP(S).
- [Forcepoint NGFW SMC API](https://apis.io/apis/forcepoint/forcepoint-ngfw-smc-api/) — RESTful Security Management Center (SMC) API for Forcepoint Next-Generation Firewall — engines, network elements, and policy automation (JSON/XML). API-key…
- [Forcepoint Appliance REST API](https://apis.io/apis/forcepoint/forcepoint-appliance-rest-api/) — REST API for managing Forcepoint appliances (basic auth over HTTP(S)).

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### Governance rules (1)

Spectral rulesets for the provider's contracts.

- [Forcepoint API Rules](https://apis.io/rules/forcepoint/forcepoint-rules/)

#### Security (3)

Authentication, trust centre, and vulnerability disclosure.

- [Forcepoint Authentication](https://apis.io/security/forcepoint/forcepoint-authentication/)
- [Forcepoint Domain Security](https://apis.io/security/forcepoint/forcepoint-domain-security/)
- [Forcepoint Trust Center](https://apis.io/security/forcepoint/forcepoint-trust-center/)

#### Plans and pricing (1)

Published plans, tiers and prices.

- [Forcepoint Plans Pricing](https://apis.io/plans/forcepoint/forcepoint-plans-pricing/)

#### Rate limits (1)

Published request limits.

- [Forcepoint Rate Limits](https://apis.io/rate-limits/forcepoint/forcepoint-rate-limits/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Website](https://forcepoint.com)
- [Documentation](https://help.forcepoint.com/)
- [Getting started](https://help.forcepoint.com/fpone/Interoperability/Getting_started_guide/index.html)
- [API reference](https://help.forcepoint.com/dlp/90/restapi/index.html)
- [Pricing](https://www.forcepoint.com/form/pricing-request)
- [Support](https://support.forcepoint.com/)
- [Blog](https://www.forcepoint.com/blog)
- [Security](https://www.forcepoint.com/security/cloud)
- [Compliance](https://trust.forcepoint.com/)
- [Terms of service](https://www.forcepoint.com/legal/website-terms-and-conditions)
- [Privacy policy](https://www.forcepoint.com/company/privacy-policy)
- [GitHub](https://github.com/Forcepoint)
- [Status](https://status.forcepoint.com/)

## API Evangelist rating

**Kin Score 58.9** — strong · rubric 0.24.0 · scored 2026-10-20

| Facet | Score |
|---|---|
| Discoverability | 80.4 |
| Contract quality | 39.8 |
| Contract governance | 80.9 |
| Operational transparency | 28.9 |
| Developer ergonomics | 66.0 |
| Access clarity | 60.5 |

**Agent readiness 43.4** — agent-ready (gated down from agent-native)

| Agent-readiness dimension | Result |
|---|---|
| Spec Presence | yes |
| Agentic Access | — |
| Reversibility Documented | — |
| MCP Server | documented (partial credit) |
| Auth Clarity | served (partial credit) |
| Idempotency | — |
| Error Semantics | — |
| OpenAPI Examples | — |
| Rate Limit Signal | documented (partial credit) |
| Event Surface Described | — |
| Agent Skills | unknown |
| Well Known Catalog | yes |
| Consent Identity | — |
| Agent Card | — |
| Dry Run Mode | — |
| Delegated Identity | served (partial credit) |
| Protected Resource Metadata | verified |
| Dynamic Client Registration | yes |
| Agentic Commerce | — |

**Regulatory alignment 29.4** — Horizontal (data, software, accessibility, platform)

The rubric is published at [github.com/api-evangelist/kin-score](https://github.com/api-evangelist/kin-score). The per-check breakdown behind these numbers — which checks were earned, partial or missed — along with score history and how this provider compares to its peers, is available at [apis.io/providers/forcepoint/](https://apis.io/providers/forcepoint/).

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for Forcepoint: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/forcepoint/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).
