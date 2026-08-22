# Adapty (adapty)

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

Adapty is a mobile in-app subscription platform for iOS, Android, Flutter, React Native, and Unity apps. Its core is a client SDK for paywalls, A/B testing, remote config, and server-side receipt validation, backed by a supporting Server-Side REST API for programmatically managing profiles, purchases and transactions, access levels (entitlements), and paywalls, plus webhooks and integrations for streaming subscription events to downstream analytics and marketing tools.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/adapty/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/adapty/refs/heads/main/apis.yml)

## Tags

- Mobile
- Subscriptions
- In-App Purchases
- Paywalls
- Analytics

## Timestamps

- **Created:** 2026-07-01
- **Modified:** 2026-07-01

## APIs

### Adapty Server-Side Profiles API

Programmatically get, create, update, and delete end-user profiles, addressing customers by Adapty profile ID or your own customer user ID and reading their access levels, subscriptions, and non-subscriptions.

- **Human URL:** [https://adapty.io/docs/getting-started-with-server-side-api](https://adapty.io/docs/getting-started-with-server-side-api)
- **Base URL:** `https://api.adapty.io/api/v2/server-side-api`

#### Tags

- Profiles
- Customers
- Server-Side

#### Properties

- [Documentation](https://adapty.io/docs/getting-started-with-server-side-api)
- [API Reference](https://adapty.io/docs/server-side-api-specs)
- [OpenAPI](openapi/adapty-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/adapty.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/adapty.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Adapty Server-Side Purchases & Transactions API

Record transactions against a profile and validate Stripe purchases, granting the resulting access level and importing the customer's transaction history into Adapty for server-side (Stripe, web, and store) billing flows.

- **Human URL:** [https://adapty.io/docs/server-side-api-specs](https://adapty.io/docs/server-side-api-specs)
- **Base URL:** `https://api.adapty.io/api/v2/server-side-api`

#### Tags

- Purchases
- Transactions
- Receipt Validation

#### Properties

- [Documentation](https://adapty.io/docs/server-side-api-specs)
- [API Reference](https://adapty.io/docs/server-side-api-objects)
- [OpenAPI](openapi/adapty-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/adapty.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/adapty.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Adapty Server-Side Access Levels API

Grant and revoke access levels (entitlements) for a profile directly, without requiring a transaction, to unlock or remove paid features for promotions, support flows, and cross-platform entitlement syncing.

- **Human URL:** [https://adapty.io/docs/access-level](https://adapty.io/docs/access-level)
- **Base URL:** `https://api.adapty.io/api/v2/server-side-api`

#### Tags

- Access Levels
- Entitlements
- Server-Side

#### Properties

- [Documentation](https://adapty.io/docs/access-level)
- [API Reference](https://adapty.io/docs/server-side-api-specs)
- [OpenAPI](openapi/adapty-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/adapty.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/adapty.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Adapty Server-Side Paywalls & Products API

Fetch a single paywall, list paywalls, and update paywall configuration server-side, retrieving the products and remote-config payload a client would otherwise resolve through the SDK.

- **Human URL:** [https://adapty.io/docs/paywalls](https://adapty.io/docs/paywalls)
- **Base URL:** `https://api.adapty.io/api/v2/server-side-api`

#### Tags

- Paywalls
- Products
- Remote Config

#### Properties

- [Documentation](https://adapty.io/docs/paywalls)
- [API Reference](https://adapty.io/docs/server-side-api-specs)
- [OpenAPI](openapi/adapty-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/adapty.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/adapty.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Adapty Server-Side Integrations API

Attach third-party integration identifiers (analytics, attribution, and marketing tool IDs such as AppsFlyer, Amplitude, and Adjust) to an Adapty profile so subscription events can be reconciled across the customer's stack.

- **Human URL:** [https://adapty.io/docs/getting-started-with-server-side-api](https://adapty.io/docs/getting-started-with-server-side-api)
- **Base URL:** `https://api.adapty.io/api/v2/server-side-api`

#### Tags

- Integrations
- Identifiers
- Attribution

#### Properties

- [Documentation](https://adapty.io/docs/getting-started-with-server-side-api)
- [API Reference](https://adapty.io/docs/server-side-api-specs)
- [OpenAPI](openapi/adapty-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/adapty.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/adapty.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Adapty Webhooks

Outbound webhooks that POST subscription lifecycle events (trial start, subscription started, renewed, billing issue, refund, access-level granted/revoked) to your endpoint in near real time for downstream analytics and messaging.

- **Human URL:** [https://adapty.io/docs/webhook](https://adapty.io/docs/webhook)
- **Base URL:** `https://api.adapty.io/api/v2/server-side-api`

#### Tags

- Webhooks
- Events
- Subscription Lifecycle

#### Properties

- [Documentation](https://adapty.io/docs/webhook)
- [API Reference](https://adapty.io/docs/events)

## Common Properties

- [GitHub Organization](https://github.com/adaptyteam)
- [LinkedIn](https://www.linkedin.com/company/adapty-io)
- [Website](https://adapty.io/)
- [Documentation](https://adapty.io/docs)
- [Plans](plans/adapty-plans-pricing.yml)
- [Rate Limits](rate-limits/adapty-rate-limits.yml)
- [Fin Ops](finops/adapty-finops.yml)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
