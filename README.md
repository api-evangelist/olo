# Olo

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

**Areas:** Food Service · Restaurant · Online Ordering · Delivery · Point-of-Sale · Hospitality · Payments · Loyalty · Marketing

## Olo on APIs.io

Everything profiled for Olo is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/olo/](https://apis.io/providers/olo/)** — or go straight to one of the APIs or properties below.

### APIs (15)

- [Olo Dispatch API](https://apis.io/apis/olo/olo-dispatch/) — The Olo Dispatch API orchestrates direct delivery for restaurants by routing orders to a network of delivery service providers (DSPs) such as DoorDash…
- [Olo POS Interface (OloCloud)](https://apis.io/apis/olo/olo-pos-interface/) — The Olo POS Interface Specification (commonly OloCloud) is the contract POS vendors implement to make their point-of-sale system natively integrable with…
- [Omnivore POS API](https://apis.io/apis/olo/olo-omnivore/) — Omnivore (acquired by Olo in 2019) is a universal POS API that abstracts 12+ point-of-sale systems behind a single REST surface, handling 5.6M API calls per…
- [Olo Pay API](https://apis.io/apis/olo/olo-pay/) — Olo Pay is the platform's embedded payments solution, providing PCI-compliant card capture, tokenization, Apple Pay / Google Pay digital wallet acceptance,…
- [Olo Network API](https://apis.io/apis/olo/olo-network/) — The Olo Network is a second-party ordering ecosystem that exposes participating restaurant brands' menus and ordering surfaces to high-intent guest channels…
- [Olo Marketing & Guest Data Platform API](https://apis.io/apis/olo/olo-marketing/) — Olo Marketing and the Guest Data Platform (GDP) unify first-party guest data captured across ordering, payments, loyalty, host, and sentiment signals into a…
- [Olo Host API](https://apis.io/apis/olo/olo-host/) — Olo Host (acquired from Wisely) provides reservations, waitlist, table management, and host-stand workflows for restaurants. The Host API exposes…
- [Olo Sentiment API](https://apis.io/apis/olo/olo-sentiment/) — Olo Sentiment aggregates guest feedback signals - post-order surveys, public reviews (Google, Yelp), and social mentions - and exposes them through a…
- [Olo Webhooks](https://apis.io/apis/olo/olo-webhooks/) — Olo exposes outbound webhooks that fire on order lifecycle events (placed, confirmed, ready, completed, refunded), gift-card activity, loyalty accrual /…
- [Olo Accounts API](https://apis.io/apis/olo/olo-accounts-api/) — Loyalty account creation and lookup
- [Olo Accruals API](https://apis.io/apis/olo/olo-accruals-api/) — Loyalty point accrual and void
- [Olo Brand API](https://apis.io/apis/olo/olo-brand-api/) — Brand-level configuration and metadata
- [Olo Promotions API](https://apis.io/apis/olo/olo-promotions-api/) — Validation and redemption of coupons and loyalty rewards
- [Olo Rails API](https://apis.io/apis/olo/olo-rails-api/) — Marketplace Rails partner export and order injection operations
- [Olo Users API](https://apis.io/apis/olo/olo-users-api/) — Guest account lookups

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### AsyncAPI (1)

Event-driven and webhook contracts.

- [Olo Webhooks](https://apis.io/asyncapis/olo/olo-webhooks-asyncapi/)

#### Event channels (4)

Individual events and webhooks the provider emits.

- [/webhooks/gift-cards](https://apis.io/channels/olo/webhooks-gift-cards/)
- [/webhooks/loyalty](https://apis.io/channels/olo/webhooks-loyalty/)
- [/webhooks/orders](https://apis.io/channels/olo/webhooks-orders/)
- [/webhooks/tenders](https://apis.io/channels/olo/webhooks-tenders/)

#### GraphQL (1)

GraphQL schemas.

- [Moved to /providers/olo/](https://apis.io/graphqls/olo/olo-graphql/)

#### MCP servers (1)

Model Context Protocol servers that expose the API to agents.

- [olo](https://apis.io/servers/olo/olo/)

#### Agentic access (1)

Which operations an agent can call, which act, and which need a human in the loop.

- [Olo Agentic Access](https://apis.io/agentic-access/olo/olo-agentic-access/)

#### JSON Schema (2)

The data models the API reads and writes.

- [Olo Promotions Account](https://apis.io/schemas/olo/olo-promotions-account/)
- [Olo Promotions Request](https://apis.io/schemas/olo/olo-promotions-request/)

#### JSON Structure (1)

Data models expressed in JSON Structure.

- [Olo Promotions Structure](https://apis.io/json-structure/olo/olo-promotions-structure/)

#### JSON-LD (1)

Linked-data contexts for the provider's vocabulary.

- [Olo Context](https://apis.io/jsonld/olo/olo-context/)

#### Vocabulary (1)

The provider's domain terms, defined.

- [Olo Vocabulary](https://apis.io/vocabularies/olo/olo-vocabulary/)

#### Examples (4)

Example requests and responses.

- [Olo Ordering Check User Exists Example](https://apis.io/examples/olo/olo-ordering-check-user-exists-example/)
- [Olo Ordering Create Basket Example](https://apis.io/examples/olo/olo-ordering-create-basket-example/)
- [Olo Promotions Account Example](https://apis.io/examples/olo/olo-promotions-account-example/)
- [Olo Promotions Validate Example](https://apis.io/examples/olo/olo-promotions-validate-example/)

#### Collections (14)

Postman and Open Collection request collections.

- [Olo Ordering Accounts API](https://apis.io/collections/olo/open-olo-accounts-api/)
- [Olo Ordering Accounts Accruals API](https://apis.io/collections/olo/open-olo-accruals-api/)
- [Olo Ordering Accounts Brand API](https://apis.io/collections/olo/open-olo-brand-api/)
- [Olo Ordering API](https://apis.io/collections/olo/open-olo-ordering/)
- [Olo Promotions API](https://apis.io/collections/olo/open-olo-promotions/)
- [Olo Ordering Accounts Promotions API](https://apis.io/collections/olo/open-olo-promotions-api/)
- [Olo Ordering Accounts Rails API](https://apis.io/collections/olo/open-olo-rails-api/)
- [Olo Ordering Accounts Users API](https://apis.io/collections/olo/open-olo-users-api/)
- [Olo Ordering Accounts API](https://apis.io/collections/olo/postman-olo-accounts-api/)
- [Olo Ordering Accounts Accruals API](https://apis.io/collections/olo/postman-olo-accruals-api/)
- [Olo Ordering Accounts Brand API](https://apis.io/collections/olo/postman-olo-brand-api/)
- [Olo Ordering Accounts Promotions API](https://apis.io/collections/olo/postman-olo-promotions-api/)
- [Olo Ordering Accounts Rails API](https://apis.io/collections/olo/postman-olo-rails-api/)
- [Olo Ordering Accounts Users API](https://apis.io/collections/olo/postman-olo-users-api/)

#### Governance rules (3)

Spectral rulesets for the provider's contracts.

- [Olo — asyncapi rules](https://apis.io/rules/olo/olo-asyncapi-spectral-rules/)
- [Olo — jsonschema rules](https://apis.io/rules/olo/olo-jsonschema-spectral-rules/)
- [Olo API Rules](https://apis.io/rules/olo/olo-spectral-rules/)

#### Security (3)

Authentication, trust centre, and vulnerability disclosure.

- [Olo Authentication](https://apis.io/security/olo/olo-authentication/)
- [Olo Domain Security](https://apis.io/security/olo/olo-domain-security/)
- [Olo Trust Center](https://apis.io/security/olo/olo-trust-center/)

#### Plans and pricing (1)

Published plans, tiers and prices.

- [Olo Plans Pricing](https://apis.io/plans/olo/olo-plans-pricing/)

#### Rate limits (1)

Published request limits.

- [Olo Rate Limits](https://apis.io/rate-limits/olo/olo-rate-limits/)

#### FinOps (1)

What the API costs to run, by operation.

- [Olo Finops](https://apis.io/finops/olo/olo-finops/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Website](https://www.olo.com/)
- [Documentation](https://developer.olo.com/)
- [Support](https://olosupport.zendesk.com/hc/en-us)
- [Blog](https://www.olo.com/blog)
- [Security](https://www.olo.com/security/)
- [Trust centre](https://trust.olo.com/)
- [Terms of service](https://www.olo.com/api-usage-terms/)
- [Privacy policy](https://www.olo.com/privacy-policy/)
- [GitHub](https://github.com/ololabs)
- [Status](https://status.olo.com/)

## API Evangelist rating

**Kin Score 52.7** — developing · rubric 0.25.0 · scored 2026-10-23

| Facet | Score |
|---|---|
| Discoverability | 60.0 |
| Contract quality | 70.7 |
| Contract governance | 27.3 |
| Operational transparency | 42.1 |
| Developer ergonomics | 56.0 |
| Access clarity | 43.4 |

**Agent readiness 31.0** — agent-ready

| Agent-readiness dimension | Result |
|---|---|
| Spec Presence | yes |
| Agentic Access | derived (partial credit) |
| Reversibility Documented | documented (partial credit) |
| MCP Server | verified |
| Auth Clarity | bearer (partial credit) |
| Idempotency | — |
| Error Semantics | — |
| OpenAPI Examples | documented (partial credit) |
| Rate Limit Signal | derived (partial credit) |
| Event Surface Described | derived (partial credit) |
| Agent Skills | — |
| Well Known Catalog | — |
| Consent Identity | — |
| Agent Card | — |
| Dry Run Mode | — |
| Delegated Identity | — |
| Protected Resource Metadata | — |
| Dynamic Client Registration | — |
| Agentic Commerce | — |
| Pagination Ratio | — |
| Operation Distinctiveness | distinct |

**Regulatory alignment 26.8** — Payments

The rubric is published at [github.com/api-evangelist/kin-score](https://github.com/api-evangelist/kin-score). The per-check breakdown behind these numbers — which checks were earned, partial or missed — along with score history and how this provider compares to its peers, is available at [apis.io/providers/olo/](https://apis.io/providers/olo/).

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for Olo: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/olo/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).
