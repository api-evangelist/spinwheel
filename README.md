# Spinwheel (spinwheel)

Spinwheel is an embedded credit and debt data platform. Its REST API and drop-in modules connect a consumer (via SMS, KBA, phone, or network token), pull an Equifax-backed debt profile across credit cards, student, auto, home, and personal loans, refresh real-time liability balances and payoff quotes, and originate bank-account-funded payments - all surfaced to partners as user-scoped endpoints and webhook events.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/spinwheel/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/spinwheel/refs/heads/main/apis.yml)

## Tags

- Fintech
- Credit Data
- Debt
- Liabilities
- Payments
- Embedded Finance

## Timestamps

- **Created:** 2026-06-20
- **Modified:** 2026-06-20

## APIs

### Spinwheel Credit Data API

Orders an Equifax-backed debt profile for a connected user and retrieves the resulting credit report (including a PDF report), surfacing the user's tradelines and credit data for downstream debt and payment workflows.

- **Human URL:** [https://docs.spinwheel.io/reference/order-equifax-report](https://docs.spinwheel.io/reference/order-equifax-report)
- **Base URL:** `https://api.spinwheel.io/v1`

#### Tags

- Credit Data
- Debt Profile
- Equifax
- Credit Report

#### Properties

- [Documentation](https://docs.spinwheel.io/docs/getting-started-1)
- [API Reference](https://docs.spinwheel.io/reference/order-equifax-report)
- [OpenAPI](openapi/spinwheel-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/spinwheel.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/spinwheel.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Spinwheel Liabilities & Debt API

Requests and polls real-time liability data (balances, rates, payoff quotes) across credit cards, student, auto, home, personal, and miscellaneous liabilities, with patch-level updates and recurring debt-profile refresh subscriptions.

- **Human URL:** [https://docs.spinwheel.io/docs/user-connect](https://docs.spinwheel.io/docs/user-connect)
- **Base URL:** `https://api.spinwheel.io/v1`

#### Tags

- Liabilities
- Loans
- Refresh
- Payoff Quote

#### Properties

- [Documentation](https://docs.spinwheel.io/docs/user-connect)
- [API Reference](https://docs.spinwheel.io/reference/create-subscription)
- [OpenAPI](openapi/spinwheel-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/spinwheel.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/spinwheel.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Spinwheel Payments API

Creates and manages bank-account-funded payment requests, payers, and transactions, letting partners originate payments toward a connected user's liabilities and reconcile their status.

- **Human URL:** [https://docs.spinwheel.io/docs/payments-process](https://docs.spinwheel.io/docs/payments-process)
- **Base URL:** `https://api.spinwheel.io/v1`

#### Tags

- Payments
- Bank Accounts
- Transactions
- ACH

#### Properties

- [Documentation](https://docs.spinwheel.io/docs/payments-process)
- [API Reference](https://docs.spinwheel.io/reference/create-subscription)
- [OpenAPI](openapi/spinwheel-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/spinwheel.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/spinwheel.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Spinwheel Users & Modules API

Connects and manages the user that is the foundation of every Spinwheel workflow - via SMS OTP, knowledge-based authentication (KBA), pre-verified phone, user profile, or a partner network token - plus the drop-in modules that render these flows.

- **Human URL:** [https://docs.spinwheel.io/docs/user-connect](https://docs.spinwheel.io/docs/user-connect)
- **Base URL:** `https://api.spinwheel.io/v1`

#### Tags

- Users
- Connect
- SMS
- KBA
- Modules

#### Properties

- [Documentation](https://docs.spinwheel.io/docs/user-connect)
- [API Reference](https://docs.spinwheel.io/docs)
- [OpenAPI](openapi/spinwheel-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/spinwheel.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/spinwheel.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Spinwheel Webhooks API

Registers and manages webhook endpoints and headers, delivering event notifications such as subscription, credit-profile transaction, refresh, payment, refinance, bank-account-lookup, and payoff-quote status changes.

- **Human URL:** [https://docs.spinwheel.io/docs/webhooks](https://docs.spinwheel.io/docs/webhooks)
- **Base URL:** `https://api.spinwheel.io/v1`

#### Tags

- Webhooks
- Events
- Notifications

#### Properties

- [Documentation](https://docs.spinwheel.io/docs/webhooks)
- [API Reference](https://docs.spinwheel.io/docs/webhooks)
- [OpenAPI](openapi/spinwheel-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/spinwheel.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/spinwheel.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [LinkedIn](https://www.linkedin.com/company/spinwheel)
- [Website](https://www.spinwheel.io)
- [Documentation](https://docs.spinwheel.io)
- [Plans](plans/spinwheel-plans-pricing.yml)
- [Rate Limits](rate-limits/spinwheel-rate-limits.yml)
- [Fin Ops](finops/spinwheel-finops.yml)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
