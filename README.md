# Olo (olo)

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

Olo is a leading on-demand commerce platform powering the digital experience for restaurant brands, serving approximately 750+ enterprise and emerging chains across 90,000+ restaurant locations. The Olo platform combines online ordering, delivery dispatch, marketplace integration (Rails), payments (Olo Pay), guest data (GDP / Marketing), loyalty, and POS connectivity (Omnivore) into a single restaurant commerce stack. Developers and certified Olo Connect partners build against the Ordering API (custom order injection), Rails API (third-party marketplace order delivery), Dispatch API (delivery orchestration), the POS Interface (OloCloud) for direct POS integrations, the Omnivore API (multi-POS abstraction), the Olo Pay SDKs (iOS, Android, Flutter, Digital Wallets), and a webhook surface that fires order, loyalty, gift-card, and tender events. APIs use signature-based request authorization (HMAC) for ordering/rails plus webhook signature validation; sample code is published for C#, Java, PHP, Ruby, JavaScript, and Python. Olo (NYSE - OLO) is headquartered in New York City and went public in March 2021.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/olo/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/olo/refs/heads/main/apis.yml)

## Scope

- **Type:** Index
- **Position:** Consumer
- **Access:** 3rd-Party

## Tags

- Food Service
- Restaurants
- Online Ordering
- Delivery
- Point of Sale
- Hospitality
- Payments
- Loyalty
- Marketing

## Timestamps

- **Created:** 2026-05-25
- **Modified:** 2026-06-03

## APIs

### Olo Ordering API

The Olo Ordering API is the platform's flagship order-injection surface, enabling certified partner apps, branded restaurant clients, and white-label storefronts to push custom orders, baskets, and payment authorizations into Olo's network of 90,000+ restaurant locations. The API covers menu retrieval, basket construction, basket validation, fulfillment options (pickup, curbside, dine-in, delivery), gift cards, coupons, loyalty redemption, and order submission. Requests are signed with HMAC-based signature authorization; sandbox credentials are issued through the Olo Developer Portal after partner certification.

- **Human URL:** [https://developer.olo.com/](https://developer.olo.com/)

#### Tags

- Ordering
- Baskets
- Menus
- Restaurants

#### Properties

- [Developer Portal](https://developer.olo.com/)
- [Authentication](https://github.com/ololabs/dev-support-code-samples)
- [Code Examples](https://github.com/ololabs/dev-support-code-samples)
- [OpenAPI](openapi/olo-ordering-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/olo-ordering.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/olo-ordering.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Example](examples/olo-ordering-check-user-exists-example.json)
- [Example](examples/olo-ordering-create-basket-example.json)

### Olo Rails API

Olo Rails is the marketplace-delivery integration surface, accepting orders originated on third-party delivery marketplaces (DoorDash, Uber Eats, Grubhub, Google, and 25+ other channels) and injecting them into the restaurant's POS through Olo. Rails normalizes menu mapping, modifier translation, fulfillment timing, and tax/tender handling across marketplaces. Partners authenticate with Rails-specific signature authorization that differs from the Ordering API signature scheme.

- **Human URL:** [https://www.olo.com/products/rails](https://www.olo.com/products/rails)

#### Tags

- Rails
- Marketplace
- Delivery
- Order Injection

#### Properties

- [Documentation](https://www.olo.com/products/rails)
- [Authentication](https://github.com/ololabs/dev-support-code-samples)
- [Code Examples](https://github.com/ololabs/dev-support-code-samples)
- [OpenAPI](openapi/olo-ordering-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/olo-ordering.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/olo-ordering.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Example](examples/olo-ordering-create-basket-example.json)

### Olo Dispatch API

The Olo Dispatch API orchestrates direct delivery for restaurants by routing orders to a network of delivery service providers (DSPs) such as DoorDash Drive, Uber Direct, Postmates, and Relay. Dispatch handles quote retrieval, driver assignment, status callbacks, fee calculation, and tipping. Restaurants use Dispatch to power their own branded delivery without operating a fleet.

- **Human URL:** [https://www.olo.com/products/dispatch](https://www.olo.com/products/dispatch)

#### Tags

- Dispatch
- Delivery
- Logistics
- Last Mile

#### Properties

- [Documentation](https://www.olo.com/products/dispatch)
- [Status Page](https://status.olo.com/)
- [Postman Collection](collections/olo-ordering.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/olo-ordering.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/olo-promotions.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/olo-promotions.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Olo POS Interface (OloCloud)

The Olo POS Interface Specification (commonly OloCloud) is the contract POS vendors implement to make their point-of-sale system natively integrable with Olo's ordering platform. The interface defines menu synchronization, order injection, store hours, store status (eighty-sixing), and tender configuration that the POS must accept and respond to. Certified POS systems include NCR Aloha, PAR Brink, Oracle Micros Simphony, POSitouch, Squirrel, and others.

- **Human URL:** [https://olosupport.zendesk.com/hc/en-us/articles/115002761943-Olo-POS-Interface-Specification-aka-OloCloud](https://olosupport.zendesk.com/hc/en-us/articles/115002761943-Olo-POS-Interface-Specification-aka-OloCloud)

#### Tags

- POS
- Point of Sale
- Integration
- Menus

#### Properties

- [Documentation](https://olosupport.zendesk.com/hc/en-us/articles/115002761943-Olo-POS-Interface-Specification-aka-OloCloud)
- [Postman Collection](collections/olo-ordering.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/olo-ordering.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/olo-promotions.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/olo-promotions.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Omnivore POS API

Omnivore (acquired by Olo in 2019) is a universal POS API that abstracts 12+ point-of-sale systems behind a single REST surface, handling 5.6M API calls per day across 23,000+ restaurant locations. Endpoints cover tickets, menus, employees, tenders, modifiers, discounts, and location data. Supported POS systems include NCR Aloha, PAR Brink, Dinerware, Micros Simphony, Micros 3700, POSitouch, Squirrel, XPIENT, Maitre'D, NCR Cloud Connect, Simphony FE, and SimphonyCloud.

- **Human URL:** [https://www.olo.com/omnivoreapi](https://www.olo.com/omnivoreapi)

#### Tags

- POS
- Omnivore
- Tickets
- Multi-POS

#### Properties

- [Documentation](https://www.olo.com/omnivoreapi)
- [Login](https://panel.omnivore.io/login)
- [Postman Collection](collections/olo-ordering.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/olo-ordering.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/olo-promotions.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/olo-promotions.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Olo Pay API

Olo Pay is the platform's embedded payments solution, providing PCI-compliant card capture, tokenization, Apple Pay / Google Pay digital wallet acceptance, network tokenization, fraud prevention, and chargeback handling for restaurant brands. Developers integrate via native SDKs (iOS, Android, Flutter) and a Digital Wallets SDK that complements the Olo Ordering API checkout flow. Olo Pay is also offered as Borderless Payments for cross-border transactions.

- **Human URL:** [https://www.olo.com/products/pay](https://www.olo.com/products/pay)

#### Tags

- Payments
- Pay
- PCI
- Digital Wallets

#### Properties

- [Documentation](https://www.olo.com/products/pay)
- [SDK](https://github.com/ololabs/olo-pay-ios-sdk-releases)
- [SDK](https://github.com/ololabs/olo-pay-android-sdk-releases)
- [SDK](https://github.com/ololabs/olo-pay-flutter-sdk-releases)
- [SDK](https://github.com/ololabs/pay-digitalwallets-ios-sdk-releases)
- [SDK](https://github.com/ololabs/pay-digitalwallets-android-sdk-releases)
- [SDK](https://github.com/ololabs/pay-digitalwallets-flutter-sdk-releases)
- [Postman Collection](collections/olo-ordering.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/olo-ordering.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/olo-promotions.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/olo-promotions.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Olo Network API

The Olo Network is a second-party ordering ecosystem that exposes participating restaurant brands' menus and ordering surfaces to high-intent guest channels (super-apps, wallets, voice agents, AI assistants) while keeping the restaurant in control of the guest relationship. Network API access lets approved channel partners discover stores, fetch menus, build baskets, and submit orders that flow through the same Ordering / POS Interface pipeline.

- **Human URL:** [https://www.olo.com/network](https://www.olo.com/network)

#### Tags

- Network
- Second-Party
- Distribution
- Channels

#### Properties

- [Documentation](https://www.olo.com/network)
- [Postman Collection](collections/olo-ordering.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/olo-ordering.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/olo-promotions.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/olo-promotions.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Olo Marketing & Guest Data Platform API

Olo Marketing and the Guest Data Platform (GDP) unify first-party guest data captured across ordering, payments, loyalty, host, and sentiment signals into a single guest profile that powers segmentation, lifecycle campaigns, and personalization. The Marketing surface exposes segments, campaigns, audiences, events, and webhooks used by ESPs, SMS providers (Attentive, Infobip), and loyalty engines to engage guests at scale.

- **Human URL:** [https://www.olo.com/products/marketing](https://www.olo.com/products/marketing)

#### Tags

- Marketing
- Guest Data Platform
- GDP
- Segmentation
- Personalization

#### Properties

- [Documentation](https://www.olo.com/products/marketing)
- [Postman Collection](collections/olo-ordering.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/olo-ordering.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/olo-promotions.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/olo-promotions.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Olo Loyalty API

Olo Loyalty (formerly OloEngage) lets restaurant brands run rewards programs that are tightly bound to the Ordering and POS surfaces - accrual, redemption, tier evaluation, and single-sign-on flow through the Loyalty API and matching loyalty SSO endpoints exposed on the developer portal. Integrates with third-party loyalty engines (Punchh, Paytronix, Thanx) as well as Olo's native loyalty product.

- **Human URL:** [https://www.olo.com/products/olo-loyalty](https://www.olo.com/products/olo-loyalty)

#### Tags

- Loyalty
- Rewards
- SSO
- Engagement

#### Properties

- [Documentation](https://www.olo.com/products/olo-loyalty)
- [OpenAPI](openapi/olo-promotions-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/olo-promotions.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/olo-promotions.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [SDK](https://github.com/ololabs/promotions-sdk)
- [Example](examples/olo-promotions-validate-example.json)
- [Example](examples/olo-promotions-account-example.json)
- [JSON Schema](json-schema/olo-promotions-account-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/olo-promotions-request-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Structure](json-structure/olo-promotions-structure.json)

### Olo Host API

Olo Host (acquired from Wisely) provides reservations, waitlist, table management, and host-stand workflows for restaurants. The Host API exposes reservation creation, waitlist updates, table state, and guest tagging, integrating with the Guest Data Platform so dine-in behavior enriches the same guest profile used in ordering and marketing.

- **Human URL:** [https://www.olo.com/products/host](https://www.olo.com/products/host)

#### Tags

- Host
- Reservations
- Waitlist
- Dine-In

#### Properties

- [Documentation](https://www.olo.com/products/host)
- [Postman Collection](collections/olo-ordering.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/olo-ordering.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/olo-promotions.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/olo-promotions.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Olo Sentiment API

Olo Sentiment aggregates guest feedback signals - post-order surveys, public reviews (Google, Yelp), and social mentions - and exposes them through a sentiment API used for reputation management dashboards and automated guest recovery workflows.

- **Human URL:** [https://www.olo.com/products/sentiment](https://www.olo.com/products/sentiment)

#### Tags

- Sentiment
- Reviews
- Reputation
- Feedback

#### Properties

- [Documentation](https://www.olo.com/products/sentiment)
- [Postman Collection](collections/olo-ordering.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/olo-ordering.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/olo-promotions.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/olo-promotions.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Olo Webhooks

Olo exposes outbound webhooks that fire on order lifecycle events (placed, confirmed, ready, completed, refunded), gift-card activity, loyalty accrual / redemption, tender events, and marketplace status changes. Webhooks are HMAC-signed; reference signature-validation samples are published in C#, Java, PHP, Ruby, JavaScript, and Python in the ololabs/dev-support-code-samples repository.

- **Human URL:** [https://github.com/ololabs/dev-support-code-samples](https://github.com/ololabs/dev-support-code-samples)

#### Tags

- Webhooks
- Events
- Notifications

#### Properties

- [Documentation](https://github.com/ololabs/dev-support-code-samples)
- [Code Examples](https://github.com/ololabs/dev-support-code-samples)
- [AsyncAPI](asyncapi/olo-webhooks-asyncapi.yml) — [AsyncAPI Specification](https://www.asyncapi.com/docs/reference/specification/latest)
- [Postman Collection](collections/olo-ordering.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/olo-ordering.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/olo-promotions.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/olo-promotions.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [Portal](https://www.olo.com/)
- [Developer Portal](https://developer.olo.com/)
- [Sign Up](https://developer.olo.com/Account/Register)
- [Login](https://developer.olo.com/Account/Login)
- [Documentation](https://developer.olo.com/)
- [Partners](https://partners.olo.com/)
- [Terms of Service](https://www.olo.com/api-usage-terms/)
- [Privacy Policy](https://www.olo.com/privacy-policy/)
- [Status Page](https://status.olo.com/)
- [Support](https://olosupport.zendesk.com/hc/en-us)
- [Knowledge Center](https://olosupport.zendesk.com/hc/en-us)
- [Blog](https://www.olo.com/blog)
- [GitHub Organization](https://github.com/ololabs)
- [GitHub Repository](https://github.com/ololabs/dev-support-code-samples)
- [GitHub Repository](https://github.com/ololabs/promotions-sdk)
- [GitHub Repository](https://github.com/ololabs/olo-serve-gtm-templates)
- [Spectral Rules](rules/olo-spectral-rules.yml)
- [LinkedIn](https://www.linkedin.com/company/olo)
- [X (Twitter)](https://twitter.com/olo)
- [YouTube](https://www.youtube.com/@OloRestaurantTech)
- [Security](https://www.olo.com/security/)
- [Trust Center](https://trust.olo.com/)
- [Code Examples](https://github.com/ololabs/dev-support-code-samples)
- [SDK](https://github.com/ololabs/olo-pay-ios-sdk-releases)
- [SDK](https://github.com/ololabs/olo-pay-android-sdk-releases)
- [SDK](https://github.com/ololabs/olo-pay-flutter-sdk-releases)
- [SDK](https://github.com/ololabs/pay-digitalwallets-ios-sdk-releases)
- [SDK](https://github.com/ololabs/pay-digitalwallets-android-sdk-releases)
- [SDK](https://github.com/ololabs/pay-digitalwallets-flutter-sdk-releases)
- [Plans](plans/olo-plans-pricing.yml)
- [Rate Limits](rate-limits/olo-rate-limits.yml)
- [Vocabulary](vocabulary/olo-vocabulary.yaml)
- [JSON-LD](json-ld/olo-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)
- [Features](undefined)
- [Use Cases](undefined)
- [Integrations](undefined)
- [Solutions](undefined)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
