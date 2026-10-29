# AramisAuto

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

Aramisauto is the French retail brand of Aramis Group (Euronext Paris: ARAMI, majority-owned by Stellantis), founded in 2001 by Nicolas Chartier and Guillaume Paoli. It sells used, 0km and new cars online as a mandataire, reconditions vehicles in its own refurbishing centres, runs a trade-in service ("reprise") that pays within 24 hours, and arranges financing (crédit, LOA, LLD) through Cetelem, Socram, PSA Banque, Lizauto and Opteven. Aramisauto operates no public developer programme: there is no portal, no OpenAPI and no SDK. What it does publish is machine-readable and first-party — ten JSON Schema 2020-12 contracts at schemas.aramis.group covering the vehicle catalog (search request/response, the multi-language ingest model, the single-language read model served from "the preheated cache for the APIs", and the search-index projection) plus the four-stage collect/map/filter/enrich configuration contracts third-party marketplace sellers are onboarded with — and an llms.txt at the site root. Its API vhost, api.aramisauto.com, answers every anonymous request with an HTTP 403 demanding a WSSE (WS-Security UsernameToken) credential.

**Areas:** Company · Consumer · Automotive · E-Commerce · Used Cars · Vehicle Data · Marketplace · Retail · Auto Finance · France · JSON Schema

## AramisAuto on APIs.io

Everything profiled for AramisAuto is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/aramisauto/](https://apis.io/providers/aramisauto/)** — or go straight to one of the APIs or properties below.

### APIs (1)

- [Aramisauto Vehicle Catalog Contracts](https://apis.io/apis/aramisauto/aramisauto-vehicle-catalog-contracts/) — Aramis Group publishes the machine-readable contracts behind the Aramisauto vehicle catalog as ten JSON Schema 2020-12 documents at…

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### JSON Schema (10)

The data models the API reads and writes.

- [Aramisauto Catalog Base.Schema](https://apis.io/schemas/aramisauto/aramisauto-catalog-base.schema/)
- [Aramisauto Catalog Search Request.Schema](https://apis.io/schemas/aramisauto/aramisauto-catalog-search-request.schema/)
- [Aramisauto Catalog Search Response.Schema](https://apis.io/schemas/aramisauto/aramisauto-catalog-search-response.schema/)
- [Aramisauto Catalog Vehicle Multi Language Input.Schema](https://apis.io/schemas/aramisauto/aramisauto-catalog-vehicle-multi-language-input.schema/)
- [Aramisauto Catalog Vehicle Single Language Output.Schema](https://apis.io/schemas/aramisauto/aramisauto-catalog-vehicle-single-language-output.schema/)
- [Aramisauto Catalog Vehicle Single Language Searchable Data.Schema](https://apis.io/schemas/aramisauto/aramisauto-catalog-vehicle-single-language-searchable-data.schema/)
- [Aramisauto Marketplace Collect.Schema](https://apis.io/schemas/aramisauto/aramisauto-marketplace-collect.schema/)
- [Aramisauto Marketplace Enrich.Schema](https://apis.io/schemas/aramisauto/aramisauto-marketplace-enrich.schema/)
- [Aramisauto Marketplace Filter.Schema](https://apis.io/schemas/aramisauto/aramisauto-marketplace-filter.schema/)
- [Aramisauto Marketplace Map.Schema](https://apis.io/schemas/aramisauto/aramisauto-marketplace-map.schema/)

#### Examples (5)

Example requests and responses.

- [Aramisauto Catalog Search Request](https://apis.io/examples/aramisauto/aramisauto-catalog-search-request/)
- [Aramisauto Catalog Search Response](https://apis.io/examples/aramisauto/aramisauto-catalog-search-response/)
- [Aramisauto Catalog Vehicle Multi Language Input](https://apis.io/examples/aramisauto/aramisauto-catalog-vehicle-multi-language-input/)
- [Aramisauto Catalog Vehicle Single Language Output](https://apis.io/examples/aramisauto/aramisauto-catalog-vehicle-single-language-output/)
- [Aramisauto Catalog Vehicle Single Language Searchable Data](https://apis.io/examples/aramisauto/aramisauto-catalog-vehicle-single-language-searchable-data/)

#### Security (2)

Authentication, trust centre, and vulnerability disclosure.

- [Aramisauto Authentication](https://apis.io/security/aramisauto/aramisauto-authentication/)
- [Aramisauto Domain Security](https://apis.io/security/aramisauto/aramisauto-domain-security/)

#### Plans and pricing (1)

Published plans, tiers and prices.

- [Aramisauto Plans Pricing](https://apis.io/plans/aramisauto/aramisauto-plans-pricing/)

#### Rate limits (1)

Published request limits.

- [Aramisauto Rate Limits](https://apis.io/rate-limits/aramisauto/aramisauto-rate-limits/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Website](https://www.aramisauto.com/)
- [Support](https://www.aramisauto.com/aide/faq)
- [Blog](https://www.aramisauto.com/guide-pratique/)
- [Terms of service](https://www.aramisauto.com/mentions-legales/)
- [Privacy policy](https://www.aramisauto.com/mentions-legales/politique-de-protection-des-donnees/)
- [GitHub](https://github.com/ARAMISAUTO)

## API Evangelist rating

**Kin Score 18.4** — emerging · rubric 0.24.0 · scored 2026-10-17

| Facet | Score |
|---|---|
| Discoverability | 73.2 |
| Contract quality | 14.5 |
| Contract governance | 8.3 |
| Operational transparency | 2.6 |
| Developer ergonomics | 7.1 |
| Access clarity | 21.1 |

**Agent readiness 3.8** — human-only

| Agent-readiness dimension | Result |
|---|---|
| Spec Presence | — |
| Agentic Access | — |
| Reversibility Documented | — |
| MCP Server | — |
| Auth Clarity | — |
| Idempotency | — |
| Error Semantics | — |
| OpenAPI Examples | documented (partial credit) |
| Rate Limit Signal | documented (partial credit) |
| Event Surface Described | — |
| Agent Skills | — |
| Well Known Catalog | — |
| Consent Identity | — |
| Agent Card | — |
| Dry Run Mode | — |
| Delegated Identity | — |
| Protected Resource Metadata | — |
| Dynamic Client Registration | — |
| Agentic Commerce | — |

**Regulatory alignment 18.6** — Horizontal (data, software, accessibility, platform)

The rubric is published at [github.com/api-evangelist/kin-score](https://github.com/api-evangelist/kin-score). The per-check breakdown behind these numbers — which checks were earned, partial or missed — along with score history and how this provider compares to its peers, is available at [apis.io/providers/aramisauto/](https://apis.io/providers/aramisauto/).

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for AramisAuto: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/aramisauto/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).
