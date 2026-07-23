# KOHO (koho)

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
