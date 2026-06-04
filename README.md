# École Normale Supérieure de Lyon (ens-lyon)

École Normale Supérieure de Lyon (ENS de Lyon) is a French public research and higher-education institution, ranked #187 in the QS World University Rankings 2025. This repository catalogs its public, machine-readable developer/API footprint as an [APIs.json](https://apisjson.org) profile. ENS de Lyon does not run a dedicated, branded developer portal; its principal verifiable API surface is its open-access institutional repository, **HAL-ENS-LYON**, exposed through the national HAL platform's documented APIs.

- APIs.json: https://raw.githubusercontent.com/api-evangelist/ens-lyon/refs/heads/main/apis.yml
- Run with Naftiko: https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=ens-lyon-api-evangelist&utm_content=repo

## Type

- **Type:** Index
- **Position:** Consumer
- **Access:** 3rd-Party

## Tags

Education, Higher Education, University, France, Open Access, Research, Institutional Repository, OAI-PMH

## APIs

- **HAL-ENS-LYON OAI-PMH** — OAI-PMH 2.0 harvesting endpoint scoped to the ens-lyon collection. Docs: https://api.archives-ouvertes.fr/docs/oai — Base: `https://api.archives-ouvertes.fr/oai/ens-lyon`
- **HAL Search API (ens-lyon collection)** — REST/Solr search over ENS de Lyon publications. Docs: https://api.archives-ouvertes.fr/docs/search — Base: `https://api.archives-ouvertes.fr/search/ens-lyon/`
- **HAL Reference (Référentiels) API** — Controlled vocabularies and authorities (authors, structures, journals). Docs: https://api.archives-ouvertes.fr/docs/ref — Base: `https://api.archives-ouvertes.fr/ref/`
- **HAL SWORD Deposit API** — Authenticated programmatic deposit into HAL. Docs: https://api.archives-ouvertes.fr/docs/sword — Base: `https://api.archives-ouvertes.fr/sword/`

## Plans / Rate Limits / FinOps

- Plans & Pricing: [plans/ens-lyon-plans-pricing.yml](plans/ens-lyon-plans-pricing.yml)
- Rate Limits: [rate-limits/ens-lyon-rate-limits.yml](rate-limits/ens-lyon-rate-limits.yml)
- FinOps: [finops/ens-lyon-finops.yml](finops/ens-lyon-finops.yml)

## Timestamps

- Created: 2026-06-03
- Modified: 2026-06-03

## Common Properties

- Website: https://www.ens-lyon.fr/
- Developer Portal (HAL APIs): https://api.archives-ouvertes.fr/docs
- GitHub: https://github.com/ens-lyon
- LinkedIn: https://fr.linkedin.com/school/ens-lyon/
- Repository (HAL-ENS-LYON): https://ens-lyon.hal.science
- Review: [review.yml](review.yml)

## Notes

The HAL APIs are operated by the national HAL / CCSD infrastructure (api.archives-ouvertes.fr), scoped to the ENS de Lyon `ens-lyon` collection — they are not branded ENS de Lyon endpoints. The OAI-PMH `Identify` and Search endpoints were verified live (HTTP 200) on 2026-06-03. The official GitHub org (github.com/ens-lyon) loads but currently publishes no public repositories. The LinkedIn school page returns HTTP 999 (LinkedIn anti-bot) but exists in-browser. No course/catalog/SIS, library Alma/Primo, or other branded institutional API was found publicly documented, and none were fabricated.

## Maintainers

- Kin Lane — kin@apievangelist.com
