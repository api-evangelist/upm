# Universiti Putra Malaysia (upm)

Universiti Putra Malaysia (UPM) is a Malaysian public research university in Serdang, Selangor (formerly Universiti Pertanian Malaysia), ranked #148 in the QS World University Rankings 2025. UPM has no central, publicly documented developer portal, but it operates standards-based scholarly and identity infrastructure that is machine-readable and verifiable: an EPrints OAI-PMH repository interface and a Shibboleth SAML identity provider.

- APIs.json: https://raw.githubusercontent.com/api-evangelist/upm/refs/heads/main/apis.yml
- Run with Naftiko: https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=upm-api-evangelist&utm_content=repo

## Type

- Index
- Consumer
- 3rd-Party

## Tags

Education, Higher Education, University, Research, Open Access, Institutional Repository, Identity, Malaysia

## APIs

- **PSAS Institutional Repository OAI-PMH** — OAI-PMH 2.0 metadata harvesting for the UPM Institutional Repository (EPrints). Base URL: `http://psasir.upm.edu.my/cgi/oai2`. Docs: http://psasir.upm.edu.my/information.html
- **UPM Shibboleth SAML 2.0 Identity Provider** — Federated SSO identity provider publishing SAML 2.0 metadata (scope `upm.edu.my`). Docs: https://idf.upm.edu.my/idp/shibboleth

## Plans

- [plans/upm-plans-pricing.yml](plans/upm-plans-pricing.yml)

## Rate Limits

- [rate-limits/upm-rate-limits.yml](rate-limits/upm-rate-limits.yml)

## FinOps

- [finops/upm-finops.yml](finops/upm-finops.yml)

## Timestamps

- Created: 2026-06-03
- Modified: 2026-06-03

## Common Properties

- Website: https://upm.edu.my/
- LinkedIn: https://www.linkedin.com/school/universiti-putra-malaysia/
- Library: https://lib.upm.edu.my/
- Repository: http://psasir.upm.edu.my/
- Authentication: https://idf.upm.edu.my/idp/shibboleth
- Review: [review.yml](review.yml)

## Notes

All cataloged endpoints were probed and verified live on 2026-06-03. The OAI-PMH endpoint returned a valid `Identify` response and six metadata formats; the Shibboleth IdP returned valid SAML metadata. No public, documented general-purpose API or developer portal was found. Student/staff systems (study portal, SIMS, Putra MOOC) are gated behind UPM-ID SSO or resolve to internal hosts and are not openly documented. No official UPM GitHub organization was confirmed. No endpoints were fabricated.

## Maintainers

- Kin Lane — kin@apievangelist.com
