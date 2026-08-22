# Spinwheel (spinwheel)

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
