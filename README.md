# École Normale Supérieure de Lyon (ens-lyon)

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

École Normale Supérieure de Lyon (ENS de Lyon) is a French public grande école and research university, ranked #187 in the QS World University Rankings 2025. This repository catalogs its public, machine-readable developer/API footprint as an [APIs.json](https://apisjson.org) profile. ENS de Lyon runs no public developer portal, publishes no OpenAPI and issues no API keys. What it does operate is standards-based identity infrastructure — a self-hosted Shibboleth Identity Provider registered by RENATER in the Fédération Éducation-Recherche and exported to eduGAIN, an Apereo CAS single sign-on service, and a Microsoft Entra ID tenant. Its scholarly record is machine-readable only as a named collection on **HAL**, the national open archive operated by CCSD/CNRS: that data is ENS de Lyon's, the platform and the contract are HAL's, so those surfaces are recorded as tenancies. Every surface below carries an `x-operator` saying who actually runs it.

- APIs.json: https://raw.githubusercontent.com/api-evangelist/ens-lyon/refs/heads/main/apis.yml
- Run with Naftiko: https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=ens-lyon-api-evangelist&utm_content=repo

## Type

- **Type:** Index
- **Position:** Consumer
- **Access:** 3rd-Party

## Tags

University, Higher Education, Education, France, Grande École, Identity Federation, Shibboleth, SAML, Research Repository, Open Access, OAI-PMH, Research Computing

## APIs

Each entry carries an operator: `institution` (ENS de Lyon runs it), `federation` (shared metadata
carrying ENS de Lyon's own identity), `tenant` (ENS de Lyon's data on someone else's platform),
`registry` (a registry ENS de Lyon is registered in).

- **ENS de Lyon Shibboleth Identity Provider** — `institution`. SAML 2.0 metadata, scope `ens-lyon.fr`, on ENS de Lyon's own 140.77.0.0/16 allocation. Base: `https://idp.ens-lyon.fr/idp/shibboleth`
- **RENATER Fédération Éducation-Recherche entity** — `federation`. Signed metadata for that IdP, exported to eduGAIN, REFEDS Research & Scholarship. Base: `https://mdq.federation.renater.fr/fer/entities/https%3A%2F%2Fidp.ens-lyon.fr%2Fidp%2Fshibboleth`
- **ENS de Lyon Microsoft Entra ID tenant** — `federation`. Tenant `c30cf67d-aee4-44f6-8f1b-12f4935b7d2c`, live OIDC discovery + SAML federation metadata. Microsoft's host, ENS de Lyon's tenant.
- **ENS de Lyon CAS single sign-on** — `institution`. Apereo CAS 3.0 on `cas.ens-lyon.fr`. Base: `https://cas.ens-lyon.fr/cas/`
- **HAL OAI-PMH — ens-lyon collection** — `tenant`. Docs: https://api.archives-ouvertes.fr/docs/oai — Base: `https://api.archives-ouvertes.fr/oai/ens-lyon`
- **HAL Search API — ens-lyon collection** — `tenant`. 106,836 records on 2026-09-01. Docs: https://api.archives-ouvertes.fr/docs/search — Base: `https://api.archives-ouvertes.fr/search/ens-lyon/`
- **ROR registry record** — `registry`. https://ror.org/04zmssz18
- **Crossref Funder Registry entry** — `registry`. https://doi.org/10.13039/501100018692

Removed in the 2026-09-01 re-profile: HAL's generic Reference (Référentiels) and SWORD deposit APIs.
Both are HAL's own contracts on a shared national host with no ENS de Lyon scope, so crediting them
to the institution overstated its footprint. HAL's data for ENS de Lyon is still recorded, as a tenancy.

## Artifacts

- Authentication & federated identity: [authentication/ens-lyon-authentication.yml](authentication/ens-lyon-authentication.yml)
- Education-regime standard conformance: [conformance/ens-lyon-domain-standards.yml](conformance/ens-lyon-domain-standards.yml)

## Plans / Rate Limits / FinOps

- Plans & Pricing: [plans/ens-lyon-plans-pricing.yml](plans/ens-lyon-plans-pricing.yml)
- Rate Limits: [rate-limits/ens-lyon-rate-limits.yml](rate-limits/ens-lyon-rate-limits.yml)
- FinOps: [finops/ens-lyon-finops.yml](finops/ens-lyon-finops.yml)

## Timestamps

- Created: 2026-06-03
- Modified: 2026-09-01

## Common Properties

- Website: https://www.ens-lyon.fr/
- Terms / Mentions légales: https://www.ens-lyon.fr/acces/mentions-legales
- Support: https://www.ens-lyon.fr/contact
- LinkedIn: https://fr.linkedin.com/school/ens-lyon/
- Identity Federation: https://services.renater.fr/federation/
- Research Repository (HAL-ENS-LYON): https://ens-lyon.hal.science
- Research Computing (PSMN): https://www.ens-lyon.fr/PSMN/
- Review: [review.yml](review.yml)

## Notes

Re-profiled 2026-09-01 under the API Evangelist university pipeline, which settles **who operates
each surface** before saving anything.

The HAL endpoints are operated by CCSD/CNRS on the shared national host `api.archives-ouvertes.fr`
— the OAI-PMH `Identify` response names the repository as HAL, the repositoryIdentifier as
`hal.archives-ouvertes.fr` and the admin contact as `contact@archives-ouvertes.fr`. They are scoped
to ENS de Lyon's `ens-lyon` collection, so the relationship is real and is recorded as a tenancy;
HAL's specification is not saved under this institution.

The real institution-operated find here is federated identity: `idp.ens-lyon.fr` serves a valid SAML
2.0 EntityDescriptor with scope `ens-lyon.fr`, and RENATER's MDQ returns the signed copy in both the
`fer` and `edugain` namespaces. `cas.ens-lyon.fr` answers the CAS 3.0 protocol.

The `github.com/ENS-Lyon` organisation pointer was **removed**: the org has zero public repositories,
no name, no URL and no verified domain, so it cannot be attributed to the institution. The
`api.archives-ouvertes.fr/docs` "Developer Portal" pointer was also removed — those are HAL's docs,
not ENS de Lyon's.

No course catalog, SIS, timetable, library discovery API or open-data portal was found:
`api.ens-lyon.fr`, `data.ens-lyon.fr` and `developer.ens-lyon.fr` do not resolve. `ens-lyon.hal.science`
and `books.openedition.org` return HTTP 200 carrying an Anubis bot-mitigation challenge rather than
content. `www.ens-lyon.fr` returns 404 for `llms.txt`, `sitemap.xml` and `.well-known/security.txt`,
and serves a 77KB soft-404 body, so status codes were read rather than page presence. LinkedIn
returns 999 (anti-bot) but exists in-browser. ENS de Lyon holds no DataCite membership and no
Crossref depositor membership. Nothing was fabricated.

## Maintainers

- Kin Lane — kin@apievangelist.com
