# KOHO (koho)

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

KOHO is a Canadian financial-technology company (neobank) founded in 2014 by Daniel Eberhard and headquartered in Vancouver, British Columbia, serving more than 2.5 million Canadians through a mobile-first money app. KOHO is not a chartered bank; it issues a KOHO Mastercard prepaid card through KOHO Financial Inc. and places customer balances in trust with CDIC-member institutions (its longstanding banking partner is Peoples Trust Company), while offering high-interest savings, cash back, credit building, Cover cash advances, and Pay Later. The company is in the final stages of pursuing a federal Schedule I banking licence and, in May 2026, joined the Interac e-Transfer network directly as a Participant.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/koho/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/koho/refs/heads/main/apis.yml)

## Tags

- Financial Services
- Banking
- Canada
- Fintech
- Neobank
- Payments
- Interac
- Data Aggregation
- Consumer-Driven Banking

## Timestamps

- **Created:** 2026-07-23
- **Modified:** 2026-07-23

## APIs

KOHO exposes no first-party public developer API and operates no developer portal (`developer.koho.ca` does not resolve). This is the honest and common posture for a Canadian consumer neobank: Canada's federal Consumer-Driven Banking (open-banking) framework — legislated via Budget 2024 / the Fall Economic Statement 2024 and overseen by the Financial Consumer Agency of Canada (FCAC) — is not yet operational, so data access remains voluntary and fragmented.

Consumer account and transaction data from KOHO is reachable today only through third-party data aggregators — **Plaid** and **Flinks** (the Canadian, National Bank–owned aggregator) — rather than a direct API. KOHO documents no downloadable OpenAPI/Swagger specification, no FDX participation, and no US Section 1033-style posture (a US construct that does not apply to this Canadian entity).

On the payments rails, KOHO joined **Interac e-Transfer** directly as a Participant in May 2026 under Interac's broadened access for Payment Service Providers (PSPs), but this is a network participation, not a published KOHO API.

## Common Properties

- [Website](https://www.koho.ca/)
- [LinkedIn](https://www.linkedin.com/company/koho)
- [Terms of Service](https://www.koho.ca/legal/)
- [Privacy Policy](https://www.koho.ca/legal/)
- [Support](https://www.koho.ca/contact/)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
