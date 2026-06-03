# Olo (olo)
Olo is a leading on-demand commerce platform powering the digital experience for restaurant brands, serving approximately 750+ enterprise and emerging chains across 90,000+ restaurant locations. The Olo platform combines online ordering, delivery dispatch, marketplace integration (Rails), payments (Olo Pay), guest data (GDP / Marketing), loyalty, and POS connectivity (Omnivore) into a single restaurant commerce stack. Developers and certified Olo Connect partners build against the Ordering API (custom order injection), Rails API (third-party marketplace order delivery), Dispatch API (delivery orchestration), the POS Interface (OloCloud) for direct POS integrations, the Omnivore API (multi-POS abstraction), the Olo Pay SDKs (iOS, Android, Flutter, Digital Wallets), and a webhook surface that fires order, loyalty, gift-card, and tender events. APIs use signature-based request authorization (HMAC) for ordering/rails plus webhook signature validation; sample code is published for C#, Java, PHP, Ruby, JavaScript, and Python. Olo (NYSE - OLO) is headquartered in New York City and went public in March 2021.

**URL:** [https://www.olo.com/](https://www.olo.com/)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

## Tags

 - Food Service, Restaurants, Online Ordering, Delivery, Point of Sale, Hospitality, Payments, Loyalty, Marketing

## Timestamps

- **Created:** 2026-05-25
- **Modified:** 2026-06-03

## APIs

### Olo Ordering API
The Olo Ordering API is the platform's flagship order-injection surface, enabling certified partner apps, branded restaurant clients, and white-label storefronts to push custom orders, baskets, and payment authorizations into Olo's network of 90,000+ restaurant locations.

**Human URL:** [https://developer.olo.com/](https://developer.olo.com/)

#### Tags

 - Ordering, Baskets, Menus, Restaurants

#### Properties

- [DeveloperPortal](https://developer.olo.com/)
- [Authentication](https://github.com/ololabs/dev-support-code-samples)
- [CodeExamples](https://github.com/ololabs/dev-support-code-samples)
- [OpenAPI](openapi/olo-ordering-openapi.yml)
- [Example - Check User Exists](examples/olo-ordering-check-user-exists-example.json)
- [Example - Create Basket](examples/olo-ordering-create-basket-example.json)
- [NaftikoCapability - Brand](capabilities/ordering-brand.yaml)
- [NaftikoCapability - Users](capabilities/ordering-users.yaml)
- [NaftikoCapability - Rails](capabilities/ordering-rails.yaml)

### Olo Rails API
Olo Rails is the marketplace-delivery integration surface, accepting orders originated on third-party delivery marketplaces (DoorDash, Uber Eats, Grubhub, Google, and 25+ other channels) and injecting them into the restaurant's POS through Olo.

**Human URL:** [https://www.olo.com/products/rails](https://www.olo.com/products/rails)

#### Tags

 - Rails, Marketplace, Delivery, Order Injection

#### Properties

- [Documentation](https://www.olo.com/products/rails)
- [Authentication](https://github.com/ololabs/dev-support-code-samples)
- [CodeExamples](https://github.com/ololabs/dev-support-code-samples)
- [OpenAPI](openapi/olo-ordering-openapi.yml)
- [Example - Create Basket](examples/olo-ordering-create-basket-example.json)
- [NaftikoCapability - Rails](capabilities/ordering-rails.yaml)

### Olo Dispatch API
The Olo Dispatch API orchestrates direct delivery for restaurants by routing orders to a network of delivery service providers (DSPs) such as DoorDash Drive, Uber Direct, Postmates, and Relay.

**Human URL:** [https://www.olo.com/products/dispatch](https://www.olo.com/products/dispatch)

#### Tags

 - Dispatch, Delivery, Logistics, Last Mile

#### Properties

- [Documentation](https://www.olo.com/products/dispatch)
- [StatusPage](https://status.olo.com/)

### Olo POS Interface (OloCloud)
The Olo POS Interface Specification (commonly OloCloud) is the contract POS vendors implement to make their point-of-sale system natively integrable with Olo's ordering platform.

**Human URL:** [https://olosupport.zendesk.com/hc/en-us/articles/115002761943-Olo-POS-Interface-Specification-aka-OloCloud](https://olosupport.zendesk.com/hc/en-us/articles/115002761943-Olo-POS-Interface-Specification-aka-OloCloud)

#### Tags

 - POS, Point of Sale, Integration, Menus

#### Properties

- [Documentation](https://olosupport.zendesk.com/hc/en-us/articles/115002761943-Olo-POS-Interface-Specification-aka-OloCloud)

### Omnivore POS API
Omnivore (acquired by Olo in 2019) is a universal POS API that abstracts 12+ point-of-sale systems behind a single REST surface, handling 5.6M API calls per day across 23,000+ restaurant locations.

**Human URL:** [https://www.olo.com/omnivoreapi](https://www.olo.com/omnivoreapi)

#### Tags

 - POS, Omnivore, Tickets, Multi-POS

#### Properties

- [Documentation](https://www.olo.com/omnivoreapi)
- [Login](https://panel.omnivore.io/login)

### Olo Pay API
Olo Pay is the platform's embedded payments solution, providing PCI-compliant card capture, tokenization, Apple Pay / Google Pay digital wallet acceptance, network tokenization, fraud prevention, and chargeback handling for restaurant brands.

**Human URL:** [https://www.olo.com/products/pay](https://www.olo.com/products/pay)

#### Tags

 - Payments, Pay, PCI, Digital Wallets

#### Properties

- [Documentation](https://www.olo.com/products/pay)
- [SDK - iOS](https://github.com/ololabs/olo-pay-ios-sdk-releases)
- [SDK - Android](https://github.com/ololabs/olo-pay-android-sdk-releases)
- [SDK - Flutter](https://github.com/ololabs/olo-pay-flutter-sdk-releases)
- [SDK - Digital Wallets iOS](https://github.com/ololabs/pay-digitalwallets-ios-sdk-releases)
- [SDK - Digital Wallets Android](https://github.com/ololabs/pay-digitalwallets-android-sdk-releases)
- [SDK - Digital Wallets Flutter](https://github.com/ololabs/pay-digitalwallets-flutter-sdk-releases)

### Olo Network API
The Olo Network is a second-party ordering ecosystem that exposes participating restaurant brands' menus and ordering surfaces to high-intent guest channels (super-apps, wallets, voice agents, AI assistants).

**Human URL:** [https://www.olo.com/network](https://www.olo.com/network)

#### Tags

 - Network, Second-Party, Distribution, Channels

#### Properties

- [Documentation](https://www.olo.com/network)

### Olo Marketing & Guest Data Platform API
Olo Marketing and the Guest Data Platform (GDP) unify first-party guest data captured across ordering, payments, loyalty, host, and sentiment signals into a single guest profile that powers segmentation, lifecycle campaigns, and personalization.

**Human URL:** [https://www.olo.com/products/marketing](https://www.olo.com/products/marketing)

#### Tags

 - Marketing, Guest Data Platform, GDP, Segmentation, Personalization

#### Properties

- [Documentation](https://www.olo.com/products/marketing)

### Olo Loyalty API
Olo Loyalty (formerly OloEngage) lets restaurant brands run rewards programs that are tightly bound to the Ordering and POS surfaces.

**Human URL:** [https://www.olo.com/products/olo-loyalty](https://www.olo.com/products/olo-loyalty)

#### Tags

 - Loyalty, Rewards, SSO, Engagement

#### Properties

- [Documentation](https://www.olo.com/products/olo-loyalty)
- [OpenAPI](openapi/olo-promotions-openapi.yml)
- [SDK](https://github.com/ololabs/promotions-sdk)
- [Example - Validate Promotions](examples/olo-promotions-validate-example.json)
- [Example - Account](examples/olo-promotions-account-example.json)
- [JSONSchema - Account](json-schema/olo-promotions-account-schema.json)
- [JSONSchema - Promotions Request](json-schema/olo-promotions-request-schema.json)
- [JSONStructure - Promotions](json-structure/olo-promotions-structure.json)
- [NaftikoCapability - Accounts](capabilities/promotions-accounts.yaml)
- [NaftikoCapability - Promotions](capabilities/promotions-promotions.yaml)
- [NaftikoCapability - Accruals](capabilities/promotions-accruals.yaml)

### Olo Host API
Olo Host (acquired from Wisely) provides reservations, waitlist, table management, and host-stand workflows for restaurants.

**Human URL:** [https://www.olo.com/products/host](https://www.olo.com/products/host)

#### Tags

 - Host, Reservations, Waitlist, Dine-In

#### Properties

- [Documentation](https://www.olo.com/products/host)

### Olo Sentiment API
Olo Sentiment aggregates guest feedback signals - post-order surveys, public reviews (Google, Yelp), and social mentions - and exposes them through a sentiment API used for reputation management dashboards and automated guest recovery workflows.

**Human URL:** [https://www.olo.com/products/sentiment](https://www.olo.com/products/sentiment)

#### Tags

 - Sentiment, Reviews, Reputation, Feedback

#### Properties

- [Documentation](https://www.olo.com/products/sentiment)

### Olo Webhooks
Olo exposes outbound webhooks that fire on order lifecycle events (placed, confirmed, ready, completed, refunded), gift-card activity, loyalty accrual / redemption, tender events, and marketplace status changes.

**Human URL:** [https://github.com/ololabs/dev-support-code-samples](https://github.com/ololabs/dev-support-code-samples)

#### Tags

 - Webhooks, Events, Notifications

#### Properties

- [Documentation](https://github.com/ololabs/dev-support-code-samples)
- [CodeExamples](https://github.com/ololabs/dev-support-code-samples)
- [AsyncAPI](asyncapi/olo-webhooks-asyncapi.yml)

## Common Properties

- [Portal](https://www.olo.com/)
- [DeveloperPortal](https://developer.olo.com/)
- [SignUp](https://developer.olo.com/Account/Register)
- [Login](https://developer.olo.com/Account/Login)
- [Partners](https://partners.olo.com/)
- [TermsOfService](https://www.olo.com/api-usage-terms/)
- [PrivacyPolicy](https://www.olo.com/privacy-policy/)
- [StatusPage](https://status.olo.com/)
- [Support](https://olosupport.zendesk.com/hc/en-us)
- [Blog](https://www.olo.com/blog)
- [GitHubOrganization](https://github.com/ololabs)
- [GitHubRepository - Dev Support Code Samples](https://github.com/ololabs/dev-support-code-samples)
- [GitHubRepository - Promotions SDK](https://github.com/ololabs/promotions-sdk)
- [GitHubRepository - Serve GTM Templates](https://github.com/ololabs/olo-serve-gtm-templates)
- [SpectralRules](rules/olo-spectral-rules.yml)
- [LinkedIn](https://www.linkedin.com/company/olo)
- [X](https://twitter.com/olo)
- [YouTube](https://www.youtube.com/@OloRestaurantTech)
- [Security](https://www.olo.com/security/)
- [TrustCenter](https://trust.olo.com/)
- [CodeExamples](https://github.com/ololabs/dev-support-code-samples)
- [Plans](plans/olo-plans-pricing.yml)
- [RateLimits](rate-limits/olo-rate-limits.yml)
- [Vocabulary](vocabulary/olo-vocabulary.yaml)
- [JSONLD](json-ld/olo-context.jsonld)

## Features

| Name | Description |
|------|-------------|
| Direct Online Ordering | White-label web, mobile, and kiosk ordering surfaces backed by the Olo Ordering API for 800+ enterprise restaurant brands. |
| Rails Marketplace Integration | Bidirectional integration with DoorDash, Uber Eats, Grubhub, Google, and 25+ marketplaces for menu sync and order injection. |
| Dispatch Direct Delivery | Multi-DSP delivery orchestration across DoorDash Drive, Uber Direct, Postmates, and Relay with quote-and-tender routing. |
| Olo Network (Second-Party Distribution) | Curated ordering distribution to super-apps, voice agents, and AI assistants while restaurants retain the guest relationship. |
| Omnivore Universal POS API | Single REST interface abstracting 12+ POS systems (Aloha, PAR Brink, Micros, POSitouch, etc.) for partner integrations. |
| Olo Pay Embedded Payments | PCI-compliant card capture, network tokenization, Apple Pay / Google Pay, and fraud prevention via native iOS, Android, and Flutter SDKs. |
| Guest Data Platform (GDP) | Unified first-party guest profile combining ordering, payments, loyalty, host, and sentiment signals. |
| Olo Marketing | Lifecycle campaigns and personalization driven by GDP audiences and integrations with Attentive, Infobip, and email providers. |
| Olo Loyalty | Native loyalty plus integrations with Punchh, Paytronix, and Thanx with loyalty SSO bound to ordering and POS. |
| Olo Host | Reservations, waitlist, and table management (formerly Wisely) feeding GDP for unified guest profiles. |
| Sentiment and Reputation | Aggregated post-order surveys, public review monitoring, and automated guest recovery workflows. |
| Catering+ | Catering order management with capacity controls, lead times, and large-order workflows on top of the Ordering API. |
| Switchboard | Digitized phone-order capture that routes voice orders into Olo Ordering and the POS Interface. |
| Serve and Olo Accounts | Front-end ordering kit and passwordless guest checkout that reduce friction across guest channels. |
| Sync (Local Listings) | Local listing management across Google, Yelp, and search surfaces tied to restaurant store data. |
| Webhooks for Order and Loyalty Events | Outbound HMAC-signed webhooks for order lifecycle, loyalty, gift-card, and tender events. |
| Sandbox Environment | Dedicated sandbox issued through the Olo Developer Portal for partner certification and integration testing. |
| Olo Connect Partner Program | Tiered (Standard, Gold, Platinum) partner program governing certification, co-marketing, and integration distribution. |

## Use Cases

| Name | Description |
|------|-------------|
| Branded Direct Ordering for Enterprise Restaurant Chains | Power web, app, kiosk, and voice ordering for chains like Five Guys, P.F. Chang's, Portillo's, and First Watch. |
| Marketplace Order Injection | Inject DoorDash, Uber Eats, and Grubhub orders into the restaurant POS via Rails without manual tablet workflows. |
| Restaurant-Operated Direct Delivery | Dispatch routes direct-delivery orders to DSPs without operators running their own fleet. |
| POS Partner Integrations via Omnivore | Loyalty, payroll, KDS, and analytics vendors integrate against Omnivore once and reach 12+ POS systems. |
| Loyalty and Gift Card Programs | Tie accrual / redemption directly to checkout via Olo Loyalty and webhooks. |
| Guest Data Activation | Build first-party audiences in GDP and activate them through Olo Marketing, Attentive SMS, and email ESPs. |
| Catering and Large-Order Channels | Manage catering capacity, lead times, and corporate accounts with Catering+ on top of Ordering API. |
| Voice and AI Assistant Order Channels | Olo Network distributes ordering capabilities into voice, super-app, and AI assistant surfaces. |
| Reservations and Hospitality | Run host stand, waitlist, and reservation flows via Olo Host while feeding the same guest profile. |
| Reputation and Guest Recovery | Aggregate sentiment signals and trigger automated recovery workflows after negative experiences. |

## Integrations

| Name | Description |
|------|-------------|
| DoorDash | Marketplace ordering via Rails and direct delivery via Dispatch. |
| Uber Eats | Marketplace integration via Rails and Uber Direct via Dispatch. |
| Grubhub | Marketplace order injection via Rails. |
| Google | Order with Google integration and Sync local listings. |
| Toast | POS interoperability for shared restaurant brands. |
| NCR Aloha | POS Interface and Omnivore-supported point-of-sale. |
| PAR Brink | POS Interface and Omnivore-supported point-of-sale. |
| Oracle Micros Simphony | POS Interface support for Simphony and SimphonyCloud. |
| POSitouch | POS Interface and Omnivore-supported point-of-sale. |
| 7shifts | Labor scheduling integration consuming Olo restaurant and order data. |
| Attentive | SMS marketing activation driven by GDP audiences. |
| Infobip | Conversational messaging integration for marketing and order updates. |
| Punchh | Third-party loyalty engine integrated via Olo Loyalty. |
| Paytronix | Loyalty and gift-card integration via Olo Loyalty. |
| Thanx | Loyalty engine integration. |
| Apple Pay | Digital wallet acceptance via Olo Pay SDKs. |
| Google Pay | Digital wallet acceptance via Olo Pay SDKs. |

## Solutions

| Name | Description |
|------|-------------|
| Increase Orders | Ordering, Serve, Dispatch, Rails, Catering+, Loyalty, Order with Google, Switchboard, and Olo Network. |
| Streamline Operations | Olo Pay, Host, and Sync to streamline payments, reservations, and local listings. |
| Improve Guest Experiences | Marketing, GDP, Sentiment, and Olo Accounts for unified, personalized guest journeys. |

## SDKs

- [Olo Pay iOS SDK](https://github.com/ololabs/olo-pay-ios-sdk-releases)
- [Olo Pay Android SDK](https://github.com/ololabs/olo-pay-android-sdk-releases)
- [Olo Pay Flutter SDK](https://github.com/ololabs/olo-pay-flutter-sdk-releases)
- [Digital Wallets iOS SDK](https://github.com/ololabs/pay-digitalwallets-ios-sdk-releases)
- [Digital Wallets Android SDK](https://github.com/ololabs/pay-digitalwallets-android-sdk-releases)
- [Digital Wallets Flutter SDK](https://github.com/ololabs/pay-digitalwallets-flutter-sdk-releases)
- [Olo Developer Support Code Samples](https://github.com/ololabs/dev-support-code-samples)

## Plans

- [Olo Plans and Pricing](plans/olo-plans-pricing.yml) - Brand contract, Olo Pay, Omnivore partner access, and the Olo Connect Partner Program tiers (all sales-led / non-public list pricing).

## Rate Limits

- [Olo Rate Limits](rate-limits/olo-rate-limits.yml) - Per-credential limits documented inside the gated developer portal and partner agreements; aggregate platform scale (e.g., Omnivore at 5.6M calls/day across 23k+ locations) referenced as public signal.

## FinOps

- [Olo FinOps Shape](finops/olo-finops.yml) - Subscription + per-order transaction + Olo Pay take-rate model aligned with the FinOps Foundation Framework and FOCUS 1.3.

## Vocabulary

- [Olo Vocabulary](vocabulary/olo-vocabulary.yaml) - Unified taxonomy mapping the Ordering, Rails, Dispatch, POS Interface, Omnivore, Pay, Marketing / GDP, Loyalty, Host, Sentiment, Network, and Webhooks surfaces.

## JSON-LD

- [Olo Linked Data Context](json-ld/olo-context.jsonld) - Cross-surface JSON-LD context aligning Olo concepts (Basket, Order, Menu, MenuItem, Restaurant, GuestProfile, Audience, Campaign, LoyaltyAccount, Reservation, WebhookEvent, etc.) with schema.org and dcterms.

## Artifacts

Machine-readable API specifications organized by format. All artifacts are generated only from genuinely documented surfaces — Olo's official open-source SDKs and code samples — never fabricated. The Ordering/Rails/Promotions surfaces below come from `github.com/ololabs/dev-support-code-samples` (signature-auth samples with real paths) and `github.com/ololabs/promotions-sdk` (the Olo Promotions Specification models). Dispatch, Marketing/GDP, Host, Sentiment, Network, Omnivore, and the POS Interface remain gated behind the Olo Developer Portal and partner certification, so no specs are generated for them.

### OpenAPI

- [Olo Ordering API](openapi/olo-ordering-openapi.yml) — Brand, Users, and Rails operations sourced from Olo's signature-authorization code samples.
- [Olo Promotions API](openapi/olo-promotions-openapi.yml) — The Olo Promotions Specification (accounts, validate, redeem, accrue, void) modeled from the official Promotions SDK.

### AsyncAPI

- [Olo Webhooks](asyncapi/olo-webhooks-asyncapi.yml) — HMAC-signed order, loyalty, gift-card, and tender webhook events.

### JSON Schema

- [Promotions Account](json-schema/olo-promotions-account-schema.json)
- [Promotions Request](json-schema/olo-promotions-request-schema.json)

### JSON Structure

- [Promotions Entities](json-structure/olo-promotions-structure.json)

### Examples

- [Promotions — Validate Promotions](examples/olo-promotions-validate-example.json)
- [Promotions — Account](examples/olo-promotions-account-example.json)
- [Ordering — Create Basket](examples/olo-ordering-create-basket-example.json)
- [Ordering — Check User Exists](examples/olo-ordering-check-user-exists-example.json)

## Capabilities

Self-contained Naftiko capabilities, one per business surface (OpenAPI tag), each with inline REST and MCP exposers.

| Capability | API | Operations |
|------------|-----|-----------|
| [Promotions — Accounts](capabilities/promotions-accounts.yaml) | Olo Promotions | 3 |
| [Promotions — Promotions](capabilities/promotions-promotions.yaml) | Olo Promotions | 3 |
| [Promotions — Accruals](capabilities/promotions-accruals.yaml) | Olo Promotions | 2 |
| [Ordering — Brand](capabilities/ordering-brand.yaml) | Olo Ordering | 1 |
| [Ordering — Users](capabilities/ordering-users.yaml) | Olo Ordering | 1 |
| [Ordering — Rails](capabilities/ordering-rails.yaml) | Olo Ordering / Rails | 2 |

## Rules

- [Olo Spectral Ruleset](rules/olo-spectral-rules.yml) — 31 rules across 13 categories enforcing Olo's signature-auth, versioned-path, camelCase operationId, and Title Case tag conventions.

## Notes

MCP servers and Claude Code skills: none are published by Olo (checked the ololabs GitHub org, the MCP registry, and package registries) — no Tools properties were fabricated. Dispatch's DSP reference (dispatch-dsp.readme.io) advertises an OpenAPI spec but does not expose fetchable paths publicly, so no Dispatch spec was generated.

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
