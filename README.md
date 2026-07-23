# GB Bank (gb-bank)

GB Bank Limited is a UK challenger bank headquartered in Middlesbrough with a London office in Mayfair. It secured its full UK banking licence in 2022 and is authorised by the Prudential Regulation Authority and regulated by the Financial Conduct Authority and the PRA (Financial Services Register number 850286). GB Bank funds SME regional property developers and investors with development finance, buy-to-let and bridging loans, funded by FSCS-protected retail savings accounts (fixed-rate bonds, notice accounts, easy access) and a GB Bank mobile app.

As a small, non-CMA9 FCA-authorised bank focused on savings and secured lending, GB Bank does not operate a public developer portal or a documented UK Open Banking (OBIE / PSD2) API surface. The Open Banking API families below are represented as the shared industry standard an FCA-authorised ASPSP conforms to, and are **unverified** for GB Bank pending a confirmed developer portal or Open Data endpoint. The harvested OpenAPI/Swagger documents are the **shared OBIE standard specifications**, not GB Bank proprietary contracts.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/gb-bank/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/gb-bank/refs/heads/main/apis.yml)

## Tags

- Financial Services
- Banking
- Open Banking
- PSD2
- OBIE
- United Kingdom
- Payments
- Account Information
- Savings
- Property Finance
- SME Lending
- Fintech

## Timestamps

- **Created:** 2026-07-23
- **Modified:** 2026-07-23

## APIs

### GB Bank Open Data API

UK Open Banking Open Data API (OBIE standard, v1.3) — the public, unauthenticated reference-data surface for ATMs, Branches, Personal Current Accounts, Business Current Accounts, Unsecured SME Loans and Commercial Credit Cards. Represented as the shared OBIE Open Data Standard; unverified for GB Bank (no live Open Data endpoint confirmed on a gbbank.co.uk host).

- **Human URL:** [https://github.com/OpenBankingUK/opendata-api-docs-pub](https://github.com/OpenBankingUK/opendata-api-docs-pub)

#### Tags

- Open Data
- ATMs
- Branches
- Reference Data
- Unauthenticated

#### Properties

- [OpenAPI](openapi/uk-open-banking-open-data-api-openapi.json) — shared OBIE Open Data Standard (Swagger 2.0)
- [Documentation](https://github.com/OpenBankingUK/opendata-api-docs-pub)
- [API Reference](https://github.com/OpenBankingUK/opendata-api-spec-compiled)

### GB Bank Account and Transaction Information API (AIS)

UK Open Banking Read/Write Account & Transaction Information API (AISP) — the OBIE standard for account, balance, transaction and statement data with customer consent. FAPI-secured (OAuth2/OIDC, mTLS, PSD2 SCA). Unverified for GB Bank.

- **Human URL:** [https://github.com/OpenBankingUK/read-write-api-specs](https://github.com/OpenBankingUK/read-write-api-specs)

#### Tags

- Account Information
- Transactions
- AISP
- FAPI

#### Properties

- [OpenAPI](openapi/uk-open-banking-account-info-api-openapi.yaml) — shared OBIE Read/Write Standard
- [Documentation](https://standards.openbanking.org.uk/)
- [API Reference](https://github.com/OpenBankingUK/read-write-api-specs)

### GB Bank Payment Initiation API (PIS)

UK Open Banking Read/Write Payment Initiation API (PISP) — the OBIE standard for initiating domestic, scheduled, standing-order, international and file payments with customer consent. FAPI-secured. Unverified for GB Bank.

- **Human URL:** [https://github.com/OpenBankingUK/read-write-api-specs](https://github.com/OpenBankingUK/read-write-api-specs)

#### Tags

- Payment Initiation
- Payments
- PISP
- FAPI

#### Properties

- [OpenAPI](openapi/uk-open-banking-payment-initiation-api-openapi.yaml) — shared OBIE Read/Write Standard
- [Documentation](https://standards.openbanking.org.uk/)
- [API Reference](https://github.com/OpenBankingUK/read-write-api-specs)

### GB Bank Confirmation of Funds API (CBPII)

UK Open Banking Read/Write Confirmation of Funds API (CBPII) — the OBIE standard for confirming whether funds are available on a payment account with customer consent. FAPI-secured. Unverified for GB Bank.

- **Human URL:** [https://github.com/OpenBankingUK/read-write-api-specs](https://github.com/OpenBankingUK/read-write-api-specs)

#### Tags

- Confirmation of Funds
- CBPII
- FAPI

#### Properties

- [OpenAPI](openapi/uk-open-banking-confirmation-of-funds-api-openapi.yaml) — shared OBIE Read/Write Standard
- [Documentation](https://standards.openbanking.org.uk/)
- [API Reference](https://github.com/OpenBankingUK/read-write-api-specs)

## Common Properties

- [Website](https://www.gbbank.co.uk/)
- [Savings](https://www.gbbank.co.uk/savings)
- [Mobile App](https://www.gbbank.co.uk/gb-bank-mobile-app)
- [Support](https://www.gbbank.co.uk/help-and-support/faqs)
- [Blog / News](https://www.gbbank.co.uk/news)
- [Terms of Service](https://www.gbbank.co.uk/terms)
- [Privacy Policy](https://www.gbbank.co.uk/privacy-policy)
- [LinkedIn](https://www.linkedin.com/company/thegbb)
- [UK Open Banking Open Data Standard](https://github.com/OpenBankingUK/opendata-api-spec-compiled)
- [UK Open Banking Read/Write API Standard](https://standards.openbanking.org.uk/)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
