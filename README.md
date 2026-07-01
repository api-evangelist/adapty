# Adapty (adapty)

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
