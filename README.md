# National Yang Ming Chiao Tung University (nycu)

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

National Yang Ming Chiao Tung University (NYCU) is a public research university in Taiwan, formed in 2021 from the merger of National Yang-Ming University and National Chiao Tung University, and ranked #219 in the QS World University Rankings 2025. This repository catalogs NYCU's public developer and API footprint as an [APIs.json](https://apisjson.org) profile.

- APIs.json: <https://raw.githubusercontent.com/api-evangelist/nycu/refs/heads/main/apis.yml>
- Run with Naftiko: <https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=nycu-api-evangelist&utm_content=repo>

## Type

- **Type:** Index
- **Position:** Consumer
- **Access:** 3rd-Party

## Tags

Education, Higher Education, University, Taiwan, Identity, OAuth, Research Data, Open Data, Library

## APIs

- **NYCU OAuth / Single Sign-On API** — OAuth 2.0 (RFC 6749) authorization-code service for third-party apps to authenticate NYCU users and retrieve consented data (profile / name / status scopes). Docs: <https://id.nycu.edu.tw/docs/> · Register an app: <https://id.nycu.edu.tw/apply/app>
- **NYCU Dataverse Repository API** — Standard Dataverse Project (v5.10.1) Native and Search REST APIs over the NYCU research-data repository. Base: `https://dataverse.lib.nycu.edu.tw/api` · Docs: <https://guides.dataverse.org/en/5.10.1/api/>
- **NYCU Dataverse OAI-PMH Endpoint** — OAI-PMH 2.0 metadata-harvesting endpoint for the research-data repository. Base: `https://dataverse.lib.nycu.edu.tw/oai`

## Plans / Rate Limits / FinOps

- Plans & Pricing: [plans/nycu-plans-pricing.yml](plans/nycu-plans-pricing.yml)
- Rate Limits: [rate-limits/nycu-rate-limits.yml](rate-limits/nycu-rate-limits.yml)
- FinOps: [finops/nycu-finops.yml](finops/nycu-finops.yml)

## Timestamps

- Created: 2026-06-03
- Modified: 2026-06-03

## Common Properties

- Website: <https://www.nycu.edu.tw/>
- Developer Portal: <https://id.nycu.edu.tw/docs/>
- LinkedIn: <https://www.linkedin.com/school/nycu/>
- Review: [review.yml](review.yml)

## Notes

All cataloged APIs were verified live on 2026-06-03. The OAuth service docs and authorization endpoint, the Dataverse `api/info/version` endpoint (returning v5.10.1), and the OAI-PMH `verb=Identify` endpoint all returned HTTP 200. No official institution-wide GitHub organization was found — only individual research-lab orgs (e.g. ARG-NCTU, NYCU-NLP-Lab) — so none is listed. Course/timetable/SIS and campus-portal systems are gated behind institutional SSO and are not openly documented. The official website returns 403 and the LinkedIn page returns 999 to automated clients; both are standard bot-blocking responses and the sites exist. No endpoints were fabricated.

## Maintainers

- Kin Lane — <kin@apievangelist.com>
