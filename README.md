# National Yang Ming Chiao Tung University

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

National Yang Ming Chiao Tung University (NYCU) is a public research university in Hsinchu and Taipei, Taiwan, formed in 2021 from the merger of National Yang-Ming University and National Chiao Tung University. Its programmable footprint is small but genuinely its own in one place: the NYCU OAuth service at id.nycu.edu.tw, an OAuth 2.0 (RFC 6749) authorization server run by the university's Information Technology Service Center that lets approved applications authenticate NYCU single sign-on users and read three consented identity attributes. It is documented publicly, in Chinese and English, with its own terms of service and issue tracker, and it is the only contract in this repo NYCU actually engineered. Everything else is a relationship rather than an interface the university wrote. NYCU self-hosts a Dataverse research-data repository and a DSpace institutional repository on its own network, and both expose an anonymous OAI-PMH 2.0 harvesting endpoint that is institution-operated — but the REST contracts underneath them belong to the Dataverse Project and DSpace, not to NYCU. Library discovery is an Ex Libris Primo tenancy. NYCU is a DataCite direct member in its own name, minting DOIs on prefix 10.57770 through its "NYCU Research Data Service" repository, and is registered in ROR. There is no central developer portal, no open-data portal, no course or timetable API, no OpenID Connect discovery document, and no publicly discoverable Shibboleth or SAML identity provider. The course registration and timetable systems are human web applications behind institutional login.

**Areas:** Education · Higher Education · University · Taiwan · Identity · Authentication · SSO · Research Data · Institutional Repository · Library · Metadata · OAI-PMH

## National Yang Ming Chiao Tung University on APIs.io

Everything profiled for National Yang Ming Chiao Tung University is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/nycu/](https://apis.io/providers/nycu/)** — or go straight to one of the APIs or properties below.

### APIs (9)

- [NYCU Dataverse OAI-PMH Endpoint](https://apis.io/apis/nycu/dataverse-oai-pmh/) — Anonymous OAI-PMH 2.0 metadata-harvesting endpoint over the NYCU Dataverse research-data repository ("NYCU Dataverse Dataverse OAI Archive"). Verified with…
- [NYCU Institutional Repository OAI-PMH Endpoint](https://apis.io/apis/nycu/ir-oai-pmh/) — Anonymous OAI-PMH 2.0 harvesting endpoint over the NYCU institutional repository (國立陽明交通大學機構典藏), running back to 2014. Verified with verb=Identify on…
- [NYCU Dataverse (Dataverse Project deployment)](https://apis.io/apis/nycu/dataverse/) — NYCU Dataverse, the university library's research-data repository — a self-hosted deployment of Dataverse Project v5.10.1 holding 290 published datasets…
- [NYCU Institutional Repository (DSpace deployment)](https://apis.io/apis/nycu/institutional-repository/) — 國立陽明交通大學機構典藏 — the NYCU institutional repository, a self-hosted DSpace 11 deployment with content back to 2014. Its DSpace REST API at /server/api answers…
- [NYCU Library Discovery (Ex Libris Primo tenancy)](https://apis.io/apis/nycu/primo/) — NYCU's library discovery layer, an Ex Libris Primo tenancy. Recorded as a real institutional relationship. No Ex Libris contract is saved under this…
- [DataCite Membership — NYCU Research Data Service](https://apis.io/apis/nycu/datacite/) — NYCU is a DataCite direct member in its own name — provider gtfe — and operates the DataCite repository client gtfe.kagikv, "NYCU Research Data Service",…
- [ROR Registration](https://apis.io/apis/nycu/ror/) — NYCU's entry in the Research Organization Registry, ROR ID 00se2k293 — the canonical machine-readable identifier for the institution as an organization, and…
- [National Yang Ming Chiao Tung University Profile API](https://apis.io/apis/nycu/nycu-profile-api/) — Consented NYCU user identity attributes.
- [National Yang Ming Chiao Tung University O Auth API](https://apis.io/apis/nycu/nycu-oauth-api/) — OAuth 2.0 authorization-code endpoints.

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### JSON Schema (4)

The data models the API reads and writes.

- [Moved to /providers/nycu/](https://apis.io/schemas/nycu/nycu-dataset/)
- [NYCU OAuth Profile](https://apis.io/schemas/nycu/nycu-oauth-profile/)
- [NYCU OAuth Token Response](https://apis.io/schemas/nycu/nycu-oauth-token/)
- [Moved to /providers/nycu/](https://apis.io/schemas/nycu/nycu-search-result/)

#### JSON Structure (2)

Data models expressed in JSON Structure.

- [Moved to /providers/nycu/](https://apis.io/json-structure/nycu/nycu-dataset-structure/)
- [Moved to /providers/nycu/](https://apis.io/json-structure/nycu/nycu-search-result-structure/)

#### JSON-LD (1)

Linked-data contexts for the provider's vocabulary.

- [Moved to /providers/nycu/](https://apis.io/jsonld/nycu/nycu-context/)

#### Vocabulary (1)

The provider's domain terms, defined.

- [NYCU Dataverse API Vocabulary](https://apis.io/vocabularies/nycu/nycu-vocabulary/)

#### Examples (4)

Example requests and responses.

- [Moved to /providers/nycu/](https://apis.io/examples/nycu/nycu-info-version-example/)
- [Nycu Oauth Profile Example](https://apis.io/examples/nycu/nycu-oauth-profile-example/)
- [Nycu Oauth Token Example](https://apis.io/examples/nycu/nycu-oauth-token-example/)
- [Moved to /providers/nycu/](https://apis.io/examples/nycu/nycu-search-example/)

#### Collections (23)

Postman and Open Collection request collections.

- [Moved to /providers/nycu/](https://apis.io/collections/nycu/open-nycu-access-api/)
- [Moved to /providers/nycu/](https://apis.io/collections/nycu/open-nycu-admin-api/)
- [Moved to /providers/nycu/](https://apis.io/collections/nycu/open-nycu-batch-api/)
- [Moved to /providers/nycu/](https://apis.io/collections/nycu/open-nycu-builtin-users-api/)
- [Moved to /providers/nycu/](https://apis.io/collections/nycu/open-nycu-datasets-api/)
- [Moved to /providers/nycu/](https://apis.io/collections/nycu/open-nycu-datatags-api/)
- [Moved to /providers/nycu/](https://apis.io/collections/nycu/open-nycu-dataverses-api/)
- [Moved to /providers/nycu/](https://apis.io/collections/nycu/open-nycu-edit-api/)
- [Moved to /providers/nycu/](https://apis.io/collections/nycu/open-nycu-files-api/)
- [Moved to /providers/nycu/](https://apis.io/collections/nycu/open-nycu-harvest-api/)
- [Moved to /providers/nycu/](https://apis.io/collections/nycu/open-nycu-info-api/)
- [Moved to /providers/nycu/](https://apis.io/collections/nycu/open-nycu-ingest-api/)
- [Moved to /providers/nycu/](https://apis.io/collections/nycu/open-nycu-licenses-api/)
- [Moved to /providers/nycu/](https://apis.io/collections/nycu/open-nycu-mail-api/)
- [Moved to /providers/nycu/](https://apis.io/collections/nycu/open-nycu-meta-api/)
- [Moved to /providers/nycu/](https://apis.io/collections/nycu/open-nycu-metadatablocks-api/)
- [Moved to /providers/nycu/](https://apis.io/collections/nycu/open-nycu-mydata-api/)
- [Moved to /providers/nycu/](https://apis.io/collections/nycu/open-nycu-notifications-api/)
- [Moved to /providers/nycu/](https://apis.io/collections/nycu/open-nycu-pids-api/)
- [Moved to /providers/nycu/](https://apis.io/collections/nycu/open-nycu-roles-api/)
- [Moved to /providers/nycu/](https://apis.io/collections/nycu/open-nycu-search-api/)
- [Moved to /providers/nycu/](https://apis.io/collections/nycu/open-nycu-users-api/)
- [Moved to /providers/nycu/](https://apis.io/collections/nycu/open-nycu-workflows-api/)

#### Governance rules (2)

Spectral rulesets for the provider's contracts.

- [Moved to /providers/nycu/](https://apis.io/rules/nycu/nycu-jsonschema-spectral-rules/)
- [National Yang Ming Chiao Tung University API Rules](https://apis.io/rules/nycu/nycu-rules/)

#### Security (2)

Authentication, trust centre, and vulnerability disclosure.

- [Nycu Authentication](https://apis.io/security/nycu/nycu-authentication/)
- [Nycu Domain Security](https://apis.io/security/nycu/nycu-domain-security/)

#### OAuth scopes (1)

The permissions the API asks for.

- [Nycu Scopes](https://apis.io/scopes/nycu/nycu-scopes/)

#### Plans and pricing (1)

Published plans, tiers and prices.

- [Nycu Plans Pricing](https://apis.io/plans/nycu/nycu-plans-pricing/)

#### Rate limits (1)

Published request limits.

- [Nycu Rate Limits](https://apis.io/rate-limits/nycu/nycu-rate-limits/)

#### FinOps (1)

What the API costs to run, by operation.

- [Nycu Finops](https://apis.io/finops/nycu/nycu-finops/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Website](https://www.nycu.edu.tw/nycu/ch/index)
- [Documentation](https://id.nycu.edu.tw/docs/)
- [API reference](https://id.nycu.edu.tw/docs/)
- [Support](https://github.com/NYCU-OAuth/issue-report)
- [Terms of service](https://id.nycu.edu.tw/policy/)
- [GitHub](https://github.com/NYCU-OAuth)

## API Evangelist rating

**Kin Score 28.8** — thin · rubric 0.24.0 · scored 2026-10-17

| Facet | Score |
|---|---|
| Discoverability | 66.1 |
| Contract quality | 19.1 |
| Contract governance | 7.6 |
| Operational transparency | 7.9 |
| Developer ergonomics | 42.9 |
| Access clarity | 28.9 |

**Agent readiness 23.7** — agent-aware

| Agent-readiness dimension | Result |
|---|---|
| Spec Presence | yes |
| Agentic Access | — |
| Reversibility Documented | — |
| MCP Server | — |
| Auth Clarity | negotiable (partial credit) |
| Idempotency | — |
| Error Semantics | — |
| OpenAPI Examples | partial |
| Rate Limit Signal | derived (partial credit) |
| Event Surface Described | — |
| Agent Skills | — |
| Well Known Catalog | — |
| Consent Identity | — |
| Agent Card | — |
| Dry Run Mode | — |
| Delegated Identity | documented (partial credit) |
| Protected Resource Metadata | — |
| Dynamic Client Registration | — |
| Agentic Commerce | — |

**Regulatory alignment 30.4** — Education & Research

The rubric is published at [github.com/api-evangelist/kin-score](https://github.com/api-evangelist/kin-score). The per-check breakdown behind these numbers — which checks were earned, partial or missed — along with score history and how this provider compares to its peers, is available at [apis.io/providers/nycu/](https://apis.io/providers/nycu/).

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for National Yang Ming Chiao Tung University: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/nycu/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).
