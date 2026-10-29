# Superwall

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

Superwall is a remote paywall platform for mobile apps, offering AI‑powered monetization tools that let developers build, A/B test, and optimize in‑app paywalls and subscription experiences without shipping an app update. It provides SDKs for iOS, Android, and Web, along with analytics, audience targeting, and flexible pricing plans to help apps grow revenue.

**Areas:** Company · Monetization · Mobile · SDK · Payments · Analytics

## Superwall on APIs.io

Everything profiled for Superwall is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/superwall/](https://apis.io/providers/superwall/)** — or go straight to one of the APIs or properties below.

### APIs (42)

- [Superwall App Store Connect Configurations V2 API](https://apis.io/apis/superwall/superwall-app-store-connect-configurations-v2-api/) — CRUD for organization-scoped App Store Connect API key configurations. Pairs with the transparent proxy at `/app-store-connect/proxy/:team_id/*`.
- [Superwall App User Erasures V2 API](https://apis.io/apis/superwall/superwall-app-user-erasures-v2-api/) — Request, track and cancel the erasure of an end user's data (GDPR Art. 17).
- [Superwall Application Webapp Origins V2 API](https://apis.io/apis/superwall/superwall-application-webapp-origins-v2-api/) — Manage the browser-origin allowlist used to authorize WEBAPP checkout for an application.
- [Superwall Assets V2 API](https://apis.io/apis/superwall/superwall-assets-v2-api/) — Manage media assets (images and videos) for reuse across paywalls.
- [Superwall Audit Logs V2 API](https://apis.io/apis/superwall/superwall-audit-logs-v2-api/) — Query the V2 API audit log. Each entry records one served request: the caller, endpoint, outcome, and any auth/authz failure. Scoped to an organization.
- [Superwall Campaigns V2 API](https://apis.io/apis/superwall/superwall-campaigns-v2-api/) — Manage campaigns, placements, and audiences. A Campaign controls when and to whom paywalls are displayed. Campaigns are scoped to a specific application…
- [Superwall Chart Annotations API](https://apis.io/apis/superwall/superwall-chart-annotations-api/) — Annotations mark what happened on an application's timeline, such as a release, a feature by the App Store or a marketing campaign. Every time-series chart…
- [Superwall Charts V2 API](https://apis.io/apis/superwall/superwall-charts-v2-api/) — Query chart data for analytics and reporting. Includes revenue metrics, subscription data, user analytics, and paywall performance. Chart data is read-only;…
- [Superwall CLI Agent V2 API](https://apis.io/apis/superwall/superwall-cli-agent-v2-api/) — Hosted, spend-capped AI inference for the Superwall CLI when no local coding agent is available.
- [Superwall Custom Store Events API](https://apis.io/apis/superwall/superwall-custom-store-events-api/) — Report subscription lifecycle events from a custom store's own billing system.
- [Superwall Custom Stores API](https://apis.io/apis/superwall/superwall-custom-stores-api/) — Manage the custom stores of a project: stores that sell through the customer's own checkout.
- [Superwall Demand Score V2 API](https://apis.io/apis/superwall/superwall-demand-score-v2-api/) — Demand Score analytics used by the dashboard. Requires charts:read scope.
- [Superwall Entitlements V2 API](https://apis.io/apis/superwall/superwall-entitlements-v2-api/) — Manage entitlements and manual grants. An Entitlement represents a feature or capability that can be unlocked for users through product purchases or manual…
- [Superwall Events V2 API](https://apis.io/apis/superwall/superwall-events-v2-api/) — View event logs and retry failed event deliveries. Events represent messages sent to webhook endpoints.
- [Superwall Google Play V2 API](https://apis.io/apis/superwall/superwall-google-play-v2-api/) — Configure an application's Google Play service-account credentials and Real-Time Developer Notification delivery.
- [Superwall Grants V2 API](https://apis.io/apis/superwall/superwall-grants-v2-api/) — Query manual entitlement grants by device or user.
- [Superwall Imports API](https://apis.io/apis/superwall/superwall-imports-api/) — Bulk import of users, aliases, attributes and subscription history into the subscriptions source of truth.
- [Superwall Integration Event Names (Service) API](https://apis.io/apis/superwall/superwall-integration-event-names-service-api/) — Custom event names for one project/integration pair, read by integration-router on the webhook ingestion path. Authenticated with the internal service token…
- [Superwall Me V2 API](https://apis.io/apis/superwall/superwall-me-v2-api/) — User-centric endpoints. These endpoints only require user authentication and do not require organization context.
- [Superwall Onboarding V2 API](https://apis.io/apis/superwall/superwall-onboarding-v2-api/) — Onboarding milestone state for an application. Read-only; aggregates SDK events, product, and paywall signals for the dashboard quickstart guide.
- [Superwall Organization Access V2 API](https://apis.io/apis/superwall/superwall-organization-access-v2-api/) — Manage dashboard member project access and organization API key project restrictions.
- [Superwall Organizations V2 API](https://apis.io/apis/superwall/superwall-organizations-v2-api/) — Manage organization settings.
- [Superwall Paywall Resolver (Public) API](https://apis.io/apis/superwall/superwall-paywall-resolver-public-api/) — Resolve a numeric paywall id to its identifier. Authenticated with a preview capability (sat_ or API-minted pvt_) from the debugger deep link, sent as…
- [Superwall Paywall Templates (Public) API](https://apis.io/apis/superwall/superwall-paywall-templates-public-api/) — Browse the global paywall template catalog. This endpoint is public and returns only globally-available templates.
- [Superwall Paywalls V2 API](https://apis.io/apis/superwall/superwall-paywalls-v2-api/) — Manage paywalls and paywall templates. A Paywall is a monetization screen shown to users. Paywalls are scoped to a specific application (per-platform) since…
- [Superwall Products V2 API](https://apis.io/apis/superwall/superwall-products-v2-api/) — Manage products (in-app purchases and subscriptions). A Product represents a purchasable item shown on paywalls. Products are scoped to a project…
- [Superwall Project Transfers V2 API](https://apis.io/apis/superwall/superwall-project-transfers-v2-api/) — The Project Transfers V2 API from Superwall — 6 operation(s) for project transfers v2.
- [Superwall Projects V2 API](https://apis.io/apis/superwall/superwall-projects-v2-api/) — Manage projects for cross-platform app grouping. A Project groups multiple Applications (one per platform) for unified management.
- [Superwall Query V2 API](https://apis.io/apis/superwall/superwall-query-v2-api/) — Proxy ClickHouse queries scoped to an organization. Compatible with the clickhouse-client CLI via --url flag.
- [Superwall Retention Configurations V2 API](https://apis.io/apis/superwall/superwall-retention-configurations-v2-api/) — Manage retention configurations used by the realtime worker. Configurations are stored in Superwall and are not synced to Apple default-message APIs.
- [Superwall Retention Default Messages V2 API](https://apis.io/apis/superwall/superwall-retention-default-messages-v2-api/) — Manage Apple default message mappings by environment, product, and locale.
- [Superwall Retention Messages V2 API](https://apis.io/apis/superwall/superwall-retention-messages-v2-api/) — Manage retention messages for Apple subscription win-back. Messages are stored locally and uploaded to Apple for review.
- [Superwall Retention Messaging Onboarding V2 API](https://apis.io/apis/superwall/superwall-retention-messaging-onboarding-v2-api/) — Dashboard onboarding actions for Apple retention messaging setup.
- [Superwall Retention Campaigns V2 API](https://apis.io/apis/superwall/superwall-retentioncampaignsv2-api/) — The retentionCampaignsV2 API from Superwall — 7 operation(s) for retentioncampaignsv2.
- [Superwall RevenueCat V1 (compatible) API](https://apis.io/apis/superwall/superwall-revenuecat-v1-compatible-api/) — RevenueCat v1 API-compatible, read-only subscriber view backed by the subscription source of truth: the subscriber object with its entitlements,…
- [Superwall RevenueCat V2 (compatible) API](https://apis.io/apis/superwall/superwall-revenuecat-v2-compatible-api/) — RevenueCat v2 API-compatible, read-only customer views backed by the subscription source of truth: the customer object, their subscriptions, active…
- [Superwall Surveys V2 API](https://apis.io/apis/superwall/superwall-surveys-v2-api/) — Manage surveys shown to users after paywall interactions. Surveys collect user feedback such as why they chose not to subscribe. Surveys are scoped to a…
- [Superwall Users V2 API](https://apis.io/apis/superwall/superwall-users-v2-api/) — Manage users, user attributes, events, and diagnostics for an application.
- [Superwall Users V3 API](https://apis.io/apis/superwall/superwall-users-v3-api/) — Alias-aware user subscriptions, aliases, and synced attributes sourced from the subscriptions store.
- [Superwall Web2App Integrations V2 API](https://apis.io/apis/superwall/superwall-web2app-integrations-v2-api/) — Manage head script integrations for web2app paywall pages. Supports Facebook Pixel, Google Tag Manager, Console Logger, and custom scripts.
- [Superwall Webhooks V2 API](https://apis.io/apis/superwall/superwall-webhooks-v2-api/) — Manage webhook endpoints for receiving real-time event notifications. Delivery formats use dedicated Svix applications: `superwall` (default) and…
- [Superwall WorkOS Organization Admin API](https://apis.io/apis/superwall/superwall-workos-organization-admin-api/) — Mint WorkOS Admin Portal links for organization administrators to self-configure SSO, Directory Sync, audit log streaming, and domain verification.

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### Agentic access (1)

Which operations an agent can call, which act, and which need a human in the loop.

- [Superwall Agentic Access](https://apis.io/agentic-access/superwall/superwall-agentic-access/)

#### JSON Schema (6)

The data models the API reads and writes.

- [AuditLogEntryWithActor](https://apis.io/schemas/superwall/superwall-audit-log-entry-with-actor/)
- [AuditLogList](https://apis.io/schemas/superwall/superwall-audit-log-list/)
- [CustomStoreEvent](https://apis.io/schemas/superwall/superwall-custom-store-event/)
- [DoctorReport](https://apis.io/schemas/superwall/superwall-doctor-report/)
- [Rule Conditions](https://apis.io/schemas/superwall/superwall-rule-conditions/)
- [Rule Conditions](https://apis.io/schemas/superwall/superwall-rule-conditions-1/)

#### JSON-LD (1)

Linked-data contexts for the provider's vocabulary.

- [Superwall Context](https://apis.io/jsonld/superwall/superwall-context/)

#### Governance rules (1)

Spectral rulesets for the provider's contracts.

- [Superwall API Rules](https://apis.io/rules/superwall/superwall-rules/)

#### Security (2)

Authentication, trust centre, and vulnerability disclosure.

- [Superwall Authentication](https://apis.io/security/superwall/superwall-authentication/)
- [Superwall Domain Security](https://apis.io/security/superwall/superwall-domain-security/)

#### Plans and pricing (1)

Published plans, tiers and prices.

- [Superwall Plans Pricing](https://apis.io/plans/superwall/superwall-plans-pricing/)

#### Rate limits (1)

Published request limits.

- [Superwall Rate Limits](https://apis.io/rate-limits/superwall/superwall-rate-limits/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Website](https://superwall.com/)
- [Documentation](https://superwall.com/docs/)
- [Getting started](https://superwall.com/case-studies/rizz-god)
- [API reference](https://superwall.com/docs/)
- [Pricing](https://superwall.com/pricing)
- [Sign up](https://superwall.com/signup)
- [Support](https://superwall.com/docs/support)
- [Blog](https://superwall.com/blog)
- [Terms of service](https://superwall.com/legal/terms-of-service)
- [Privacy policy](https://superwall.com/legal/privacy-policy)
- [GitHub](https://github.com/superwall)
- [Status](https://status.superwall.com/)

## API Evangelist rating

**Kin Score 67.1** — exemplar · rubric 0.25.0 · scored 2026-10-28

| Facet | Score |
|---|---|
| Discoverability | 66.1 |
| Contract quality | 58.0 |
| Contract governance | 79.1 |
| Operational transparency | 44.7 |
| Developer ergonomics | 77.9 |
| Access clarity | 73.2 |

**Agent readiness 40.6** — agent-ready (gated down from agent-native)

| Agent-readiness dimension | Result |
|---|---|
| Spec Presence | yes |
| Agentic Access | unknown |
| Reversibility Documented | — |
| MCP Server | documented (partial credit) |
| Auth Clarity | bearer (partial credit) |
| Idempotency | — |
| Error Semantics | derived (partial credit) |
| OpenAPI Examples | partial |
| Rate Limit Signal | documented (partial credit) |
| Event Surface Described | unknown |
| Agent Skills | unknown |
| Well Known Catalog | yes |
| Consent Identity | — |
| Agent Card | — |
| Dry Run Mode | — |
| Delegated Identity | — |
| Protected Resource Metadata | — |
| Dynamic Client Registration | — |
| Agentic Commerce | — |
| Pagination Ratio | — |
| Operation Distinctiveness | distinct |

**Regulatory alignment 22.3** — Payments

The rubric is published at [github.com/api-evangelist/kin-score](https://github.com/api-evangelist/kin-score). The per-check breakdown behind these numbers — which checks were earned, partial or missed — along with score history and how this provider compares to its peers, is available at [apis.io/providers/superwall/](https://apis.io/providers/superwall/).

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for Superwall: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/superwall/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).
