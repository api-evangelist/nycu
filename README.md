# National Yang Ming Chiao Tung University (nycu)

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
