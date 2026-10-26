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

National Yang Ming Chiao Tung University (NYCU) is a public research university in Hsinchu and Taipei, Taiwan, formed in 2021 from the merger of National Yang-Ming University and National Chiao Tung University. This repository catalogs NYCU's public developer and API footprint as an [APIs.json](https://apisjson.org) profile.

- APIs.json: <https://raw.githubusercontent.com/api-evangelist/nycu/refs/heads/main/apis.yml>
- Run with Naftiko: <https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=nycu-api-evangelist&utm_content=repo>

## Type

- **Type:** Index (`x-type: university`, `x-category: Public Research University`)
- **Position:** Consumer
- **Access:** 3rd-Party

## Tags

Education, Higher Education, University, Taiwan, Identity, Authentication, Single Sign-On, Research Data, Institutional Repository, Library, Metadata

## Who operates what

A university is a federation of buyers, not a producer, so every surface below carries an
`x-operator` saying who runs the thing it describes — which is rarely the same answer as who the
data belongs to.

### Institution-operated

- **NYCU OAuth API** — the university's own OAuth 2.0 (RFC 6749) authorization server, run by the
  Information Technology Service Center. Six documented endpoints; the `profile` scope is open to
  registered developers, `name` and `status` require institutional approval. This is the one
  contract in this repo NYCU actually engineered. Docs: <https://id.nycu.edu.tw/docs/> · Register:
  <https://id.nycu.edu.tw/apply/app> · Terms: <https://id.nycu.edu.tw/policy/> · OpenAPI:
  [openapi/nycu-oauth-api-openapi.yml](openapi/nycu-oauth-api-openapi.yml) (derived from NYCU's own
  documentation — NYCU publishes no machine-readable description and no discovery document).
- **NYCU Dataverse OAI-PMH endpoint** — `https://dataverse.lib.nycu.edu.tw/oai`, verified with
  `verb=Identify`.
- **NYCU institutional repository OAI-PMH endpoint** — `https://ir.lib.nycu.edu.tw/server/oai/request`,
  content back to 2014, verified with `verb=Identify`.

### Tenant relationships (real institutional facts; the contract is not NYCU's)

- **NYCU Dataverse** — a self-hosted Dataverse Project v5.10.1 deployment, 290 datasets on DOI
  prefix 10.57770. The REST contract is the Dataverse Project's.
- **NYCU institutional repository (機構典藏)** — a self-hosted DSpace 11 deployment. The REST
  contract is DSpace's.
- **NYCU library discovery** — an Ex Libris Primo tenancy, view code `886UST_NYCU`.

### Registry memberships

- **DataCite** — NYCU is a direct member in its own name (provider `gtfe`) and operates the
  repository client `gtfe.kagikv`, "NYCU Research Data Service", prefix 10.57770.
- **ROR** — <https://ror.org/00se2k293>.

## Artifacts

- OpenAPI: [openapi/nycu-oauth-api-openapi.yml](openapi/nycu-oauth-api-openapi.yml) · pristine copy in [openapi/_original/](openapi/_original/)
- Authentication: [authentication/nycu-authentication.yml](authentication/nycu-authentication.yml)
- Scopes: [scopes/nycu-scopes.yml](scopes/nycu-scopes.yml)
- Errors: [errors/nycu-errors.yml](errors/nycu-errors.yml)
- Lifecycle: [lifecycle/nycu-lifecycle.yml](lifecycle/nycu-lifecycle.yml)
- Conformance: [conformance/nycu-conformance.yml](conformance/nycu-conformance.yml)
- Rules: [rules/nycu-rules.yml](rules/nycu-rules.yml)
- JSON Schema: [json-schema/](json-schema/) · Examples: [examples/](examples/)
- Plans & Pricing: [plans/nycu-plans-pricing.yml](plans/nycu-plans-pricing.yml)
- Rate Limits: [rate-limits/nycu-rate-limits.yml](rate-limits/nycu-rate-limits.yml)
- FinOps: [finops/nycu-finops.yml](finops/nycu-finops.yml)
- Provenance manifest: [provenance.yml](provenance.yml)

## Timestamps

- Created: 2026-06-03
- Modified: 2026-09-01

## Common Properties

- Website: <https://www.nycu.edu.tw/nycu/en/index>
- Developer Portal: <https://id.nycu.edu.tw/docs/>
- GitHub: <https://github.com/NYCU-OAuth> · Support: <https://github.com/NYCU-OAuth/issue-report>
- AI policy: NYCU's generative-AI statement and guidelines, Office of Academic Ethics and Research Integrity
- LinkedIn: <https://www.linkedin.com/school/nycu/>
- Review: [review.yml](review.yml)

## Correction, 2026-09-01

This profile previously held **23 OpenAPIs** attributed to NYCU. They were per-tag splits of **one
document** — the Dataverse Project v5.10.1 machine-generated description captured from
`dataverse.lib.nycu.edu.tw/openapi` — and they credited the Dataverse Project's engineering to the
university. All 23, the pristine original, 47 derived collections and every derived schema,
structure, example, ruleset, vocabulary, JSON-LD context, capability map and agentic-access file
were removed. The repository, the DSpace deployment and the Primo tenancy are kept as **tenant
relationships**, and the DataCite and ROR registrations as **registry memberships**, because those
are real facts about the institution even where the contract is not theirs. The apis.yml entries
also pointed all 23 Dataverse specs at `https://id.nycu.edu.tw` — the SSO host, not the repository
host — which was a second, separate defect.

**This correction lowers NYCU's score, and that is the pipeline working.** What remains is smaller
and true.

## Notes

Hunted and not found on 2026-09-01: a developer portal (`developer.nycu.edu.tw`, `api.nycu.edu.tw` —
no DNS), an open-data portal (`data.nycu.edu.tw`, `opendata.nycu.edu.tw` — no DNS), a course or
timetable API (`timetable.nycu.edu.tw` and `course.nycu.edu.tw` are human web applications, the
latter behind reCAPTCHA and Big5-encoded), a Shibboleth or SAML IdP (`idp.`/`sso.`/`shibboleth.nycu.edu.tw`
— no DNS; `id.nycu.edu.tw/saml/metadata` 404), an OAuth or OpenID Connect discovery document (both
well-known paths 404), a Crossref membership (0 results), and any ORCID integration. No official
institution-wide GitHub organization exists — only research-lab orgs — but `github.com/NYCU-OAuth`
is the OAuth service's own org and is listed. Searched in Traditional Chinese as well as English;
the OAuth documentation, the terms of service and the university's generative-AI guidelines are all
Chinese-first surfaces. The LinkedIn page returns 999 and DataCite Commons returns 429 to automated
clients; both are bot challenges, not dead links. No endpoints were fabricated.

## Maintainers

- Kin Lane — <kin@apievangelist.com>
