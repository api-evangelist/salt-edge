# Salt Edge (salt-edge)

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
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

Salt Edge is a global open-banking aggregator providing account information, payment initiation, data enrichment, merchant identification, AML transaction monitoring, and open-banking compliance solutions across 5,000+ banks. The Salt Edge API exposes Account Information (AIS) and Payment Initiation (PIS) services plus add-on Data Enrichment and AML endpoints under a single REST surface.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/salt-edge/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/salt-edge/refs/heads/main/apis.yml)

## Tags

- Fintech
- Open Banking
- PSD2
- Aggregator
- Global
- AISP
- PISP
- Compliance
- AML

## Timestamps

- **Created:** 2026-05-08
- **Modified:** 2026-05-08

## APIs

### Salt Edge Account Information API

REST API for retrieving end-user accounts, transactions, balances, and identity across 5,000+ banks worldwide.

- **Human URL:** [https://docs.saltedge.com/account_information/v5/](https://docs.saltedge.com/account_information/v5/)
- **Base URL:** `https://www.saltedge.com/api/v5`

#### Tags

- PSD2
- AISP
- Account Information
- Aggregation

#### Properties

- [Documentation](https://docs.saltedge.com/account_information/v5/)
- [Postman Collection](collections/salt-edge.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/salt-edge.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Salt Edge Payment Initiation API

Initiate single, recurring, and bulk SEPA / domestic payments via PSD2 PISP.

- **Human URL:** [https://docs.saltedge.com/payment_initiation/v5/](https://docs.saltedge.com/payment_initiation/v5/)
- **Base URL:** `https://www.saltedge.com/api/v5/payments`

#### Tags

- PSD2
- PISP
- Payment Initiation

#### Properties

- [Documentation](https://docs.saltedge.com/payment_initiation/v5/)
- [Postman Collection](collections/salt-edge.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/salt-edge.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Salt Edge Partners (Compliance Solution) API

APIs for banks adopting open banking - exposes their data to TPPs through Salt Edge's compliance gateway.

- **Human URL:** [https://docs.saltedge.com/compliance_solution/](https://docs.saltedge.com/compliance_solution/)
- **Base URL:** `https://www.saltedge.com/api/partners/v1`

#### Tags

- Compliance
- Open Banking Compliance
- SaaS

#### Properties

- [Documentation](https://docs.saltedge.com/compliance_solution/)
- [Postman Collection](collections/salt-edge.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/salt-edge.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Salt Edge Data Enrichment API

Categorize and enrich transactions, identify merchants, and surface financial insights.

- **Human URL:** [https://docs.saltedge.com/data_enrichment/](https://docs.saltedge.com/data_enrichment/)
- **Base URL:** `https://www.saltedge.com/api/data_enrichment/v1`

#### Tags

- Data Enrichment
- Categorization
- Merchant

#### Properties

- [Documentation](https://docs.saltedge.com/data_enrichment/)
- [Postman Collection](collections/salt-edge.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/salt-edge.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [GitHub Organization](https://github.com/saltedge)
- [LinkedIn](https://www.linkedin.com/company/salt-edge)
- [Portal](https://www.saltedge.com/)
- [Documentation](https://docs.saltedge.com/)
- [Pricing](https://www.saltedge.com/pricing)
- [Plans](plans/salt-edge-plans-pricing.yml)
- [Rate Limits](rate-limits/salt-edge-rate-limits.yml)
- [Fin Ops](finops/salt-edge-finops.yml)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
