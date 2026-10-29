# École Normale Supérieure de Lyon

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

École Normale Supérieure de Lyon (ENS de Lyon) is a French public grande école and research university, one of the four Écoles normales supérieures, ranked #187 in the QS World University Rankings 2025. It operates no public developer portal, publishes no OpenAPI, issues no API keys and runs no documented open-API programme — api.ens-lyon.fr, data.ens-lyon.fr and developer.ens-lyon.fr do not resolve — and this profile says so rather than padding the gap. What ENS de Lyon does operate, and what is recorded here, is standards-based identity and scholarly infrastructure. It self-hosts a Shibboleth Identity Provider on its own domain (idp.ens-lyon.fr, scope ens-lyon.fr, on the school's own 140.77.0.0/16 allocation), registered by RENATER in the Fédération Éducation-Recherche, carrying the REFEDS Research & Scholarship entity category and exported to eduGAIN; it runs an Apereo CAS single sign-on service at cas.ens-lyon.fr that answers the CAS 3.0 protocol; and it holds a Microsoft Entra ID tenant with live OIDC discovery. Its research output is machine-readable only as the ens-lyon collection on HAL, the national open archive operated by CCSD/CNRS — 106,836 records, harvestable over OAI-PMH and Solr search at api.archives-ouvertes.fr. That data is ENS de Lyon's; the platform, the contract and the admin contact (contact@archives-ouvertes.fr) are HAL's, so those surfaces are recorded as tenancies and HAL's generic reference and SWORD APIs are deliberately not claimed here. The school is registered in ROR and in the Crossref Funder Registry; it holds no DataCite membership and no Crossref depositor membership of its own.

**Areas:** University · Higher Education · Education · France · Grande École · Identity Federation · Shibboleth · SAML · Research Repository · Open Access · OAI-PMH · Research Computing

## École Normale Supérieure de Lyon on APIs.io

Everything profiled for École Normale Supérieure de Lyon is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/ens-lyon/](https://apis.io/providers/ens-lyon/)** — or go straight to one of the APIs or properties below.

### APIs (8)

- [ENS de Lyon Shibboleth Identity Provider (SAML 2.0 metadata)](https://apis.io/apis/ens-lyon/shibboleth-idp/) — ENS de Lyon self-hosts its Shibboleth Identity Provider on its own registrable domain. The entityID is https://idp.ens-lyon.fr/idp/shibboleth, the asserted…
- [RENATER Fédération Éducation-Recherche entity (ENS de Lyon IdP)](https://apis.io/apis/ens-lyon/renater-fer-entity/) — ENS de Lyon's Identity Provider as registered by RENATER, France's national research and education network, in the Fédération Éducation-Recherche and…
- [ENS de Lyon Microsoft Entra ID tenant (OIDC + SAML metadata)](https://apis.io/apis/ens-lyon/entra-id-tenant/) — The Entra ID tenant behind ens-lyon.fr accounts, resolved from the domain hint: c30cf67d-aee4-44f6-8f1b-12f4935b7d2c, region scope EU. OIDC discovery and…
- [ENS de Lyon CAS single sign-on (Apereo CAS 3.0 protocol)](https://apis.io/apis/ens-lyon/cas-sso/) — Apereo CAS service running on ENS de Lyon's own host cas.ens-lyon.fr (140.77.51.3). The CAS 3.0 validation endpoint /cas/p3/serviceValidate answers…
- [HAL OAI-PMH — ens-lyon collection](https://apis.io/apis/ens-lyon/hal-oai-pmh/) — OAI-PMH 2.0 harvesting endpoint scoped to ENS de Lyon's named collection on HAL, the French national open archive operated by CCSD (CNRS). The Identify…
- [HAL Search API — ens-lyon collection](https://apis.io/apis/ens-lyon/hal-search/) — HAL's Solr-backed search API scoped to the ENS de Lyon collection. A probe of /search/ens-lyon/?q=*:*&wt=json returned numFound 106,836 on 2026-09-01, which…
- [ROR registry record (04zmssz18)](https://apis.io/apis/ens-lyon/ror-record/) — ENS de Lyon's record in the Research Organization Registry, https://ror.org/04zmssz18, typed education and funder, carrying ISNI 0000 0001 2175 9188, GRID…
- [Crossref Funder Registry entry (501100018692)](https://apis.io/apis/ens-lyon/crossref-funder/) — ENS de Lyon is registered in the Crossref Open Funder Registry as https://doi.org/10.13039/501100018692, name "École Normale Supérieure de Lyon", location…

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### JSON-LD (1)

Linked-data contexts for the provider's vocabulary.

- [Ens Lyon Context](https://apis.io/jsonld/ens-lyon/ens-lyon-context/)

#### Security (2)

Authentication, trust centre, and vulnerability disclosure.

- [Ens Lyon Authentication](https://apis.io/security/ens-lyon/ens-lyon-authentication/)
- [Ens Lyon Domain Security](https://apis.io/security/ens-lyon/ens-lyon-domain-security/)

#### Plans and pricing (1)

Published plans, tiers and prices.

- [Ens Lyon Plans Pricing](https://apis.io/plans/ens-lyon/ens-lyon-plans-pricing/)

#### Rate limits (1)

Published request limits.

- [Ens Lyon Rate Limits](https://apis.io/rate-limits/ens-lyon/ens-lyon-rate-limits/)

#### FinOps (1)

What the API costs to run, by operation.

- [Ens Lyon Finops](https://apis.io/finops/ens-lyon/ens-lyon-finops/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Website](https://www.ens-lyon.fr/)
- [Support](https://www.ens-lyon.fr/contact)
- [Terms of service](https://www.ens-lyon.fr/acces/mentions-legales)

## API Evangelist rating

**Kin Score 20.1** — emerging · rubric 0.24.0 · scored 2026-10-17

| Facet | Score |
|---|---|
| Discoverability | 71.4 |
| Contract quality | 14.3 |
| Contract governance | 0.0 |
| Operational transparency | 5.3 |
| Developer ergonomics | 26.2 |
| Access clarity | 15.8 |

**Agent readiness 3.1** — human-only

| Agent-readiness dimension | Result |
|---|---|
| Spec Presence | — |
| Agentic Access | — |
| Reversibility Documented | — |
| MCP Server | — |
| Auth Clarity | bearer (partial credit) |
| Idempotency | — |
| Error Semantics | — |
| OpenAPI Examples | — |
| Rate Limit Signal | derived (partial credit) |
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

**Regulatory alignment 20.6** — Education & Research

The rubric is published at [github.com/api-evangelist/kin-score](https://github.com/api-evangelist/kin-score). The per-check breakdown behind these numbers — which checks were earned, partial or missed — along with score history and how this provider compares to its peers, is available at [apis.io/providers/ens-lyon/](https://apis.io/providers/ens-lyon/).

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for École Normale Supérieure de Lyon: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/ens-lyon/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).
