# Riskified

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

Riskified (NYSE RSKD) is an Israeli ecommerce risk-management platform that uses machine learning and a global merchant intelligence network to make sub-second decisions across the entire shopper journey. Its Chargeback Guarantee, Adaptive Checkout, Account Secure, Policy Protect, and Dispute Resolve products are exposed through a REST + webhook API surface at developers.riskified.com, covering pre-auth and post-auth order review, 3DS / PSD2 optimization, account integrity (login, password reset, customer create/update), claim adjudication for refund and return abuse, and an OTP service. Authentication is HMAC-SHA256 over the request body. Official SDKs ship for PHP, Java, and .NET, with iOS, Android, React Native, and Unity Beacon SDKs for device intelligence, plus first-party integrations for Shopify, Magento/Adobe Commerce, Salesforce Commerce Cloud, SAP Commerce / Hybris, commercetools, VTEX, Adyen, Braintree, PayPal, and Stripe.

**Areas:** Fraud Prevention · Chargebacks · E-Commerce · Payments · Risk Management · Machine Learning · Account Takeover · Policy Abuse · 3D · PSD2 · Returns

## Riskified on APIs.io

Everything profiled for Riskified is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/riskified/](https://apis.io/providers/riskified/)** — or go straight to one of the APIs or properties below.

### APIs (16)

- [Riskified Chargeback Guarantee API](https://apis.io/apis/riskified/riskified-chargeback-guarantee-api/) — Submit orders to Riskified for fraud and chargeback risk evaluation, in either a pre-authorization (Decide / Decision) or post-authorization (Submit /…
- [Riskified Adaptive Checkout API](https://apis.io/apis/riskified/riskified-adaptive-checkout-api/) — Recommend the optimal authentication path at checkout — friction-free, CVV, 3DS, or PSD2 exemption — to maximize approval rates while remaining…
- [Riskified Account Secure API](https://apis.io/apis/riskified/riskified-account-secure-api/) — Protect non-purchase customer journeys against account takeover, synthetic identity, and credential abuse. Submit Login, Reset Password, Customer Create,…
- [Riskified Policy Protect API](https://apis.io/apis/riskified/riskified-policy-protect-api/) — Detect and prevent refund, return, and promotional abuse. Submit refund and return claims for adjudication (claim_create), retrieve Riskified's decision…
- [Riskified OTP API](https://apis.io/apis/riskified/riskified-otp-api/) — Initiate a one-time password challenge as a step-up verification mechanism for high-risk login, password reset, or account modification events. Pairs with…
- [Riskified Beacon (Device Intelligence) SDK](https://apis.io/apis/riskified/riskified-beacon-sdk-api/) — Collect device, browser, and behavioral telemetry from the shopper's session and feed it into Riskified's risk models. The Beacon is delivered as a…
- [Riskified Chargeback Gateway Integration (CGI) API](https://apis.io/apis/riskified/riskified-chargeback-gateway-integration-api/) — Connect Riskified directly to a payment gateway (Adyen, Braintree, PayPal, Shopify Payments, Stripe) so chargeback notifications and evidence flow into the…
- [Riskified Automation Endpoints API](https://apis.io/apis/riskified/riskified-automation-endpoints-api/) — Operations for managing order lifecycle (cancel, refund, fulfill, chargeback)
- [Riskified Customer Actions API](https://apis.io/apis/riskified/riskified-customer-actions-api/) — Operations related to customer activity, including login, password resets, customer verification attempts, and customer-merchant contact events.
- [Riskified Customer Management API](https://apis.io/apis/riskified/riskified-customer-management-api/) — Operations related to account management, including customer creation and updates.
- [Riskified Order Pre-Auth Review and PSD2/3DS/CVV Recommendations API](https://apis.io/apis/riskified/riskified-order-pre-auth-review-and-psd2-3ds-cvv-recommendations-api/) — Riskified's PSD2 Optimization product, which is complementary to our Chargeback Guarantee product, is designed to minimize the friction associated with SCA…
- [Riskified OTP Recover (Sync flow) API](https://apis.io/apis/riskified/riskified-otp-recover-sync-flow-api/) — Operations for initiating and verifying one-time password recovery requests.
- [Riskified Post-Authorization Flow API](https://apis.io/apis/riskified/riskified-post-authorization-flow-api/) — Operations that allow you to send orders to Riskified for fraud review after payment authorization
- [Riskified Pre-Authorization Flow API](https://apis.io/apis/riskified/riskified-pre-authorization-flow-api/) — Operations that allow you to send orders to Riskified for fraud review before payment authorization
- [Riskified Refunds API](https://apis.io/apis/riskified/riskified-refunds-api/) — The Refunds API from Riskified — 2 operation(s) for refunds.
- [Riskified Returns API](https://apis.io/apis/riskified/riskified-returns-api/) — The Returns API from Riskified — 1 operation(s) for returns.

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### AsyncAPI (1)

Event-driven and webhook contracts.

- [Riskified Webhooks](https://apis.io/asyncapis/riskified/riskified-webhooks/)

#### MCP servers (1)

Model Context Protocol servers that expose the API to agents.

- [riskified-mcp.yml](https://apis.io/servers/riskified/riskified-mcp-yml/)

#### Agentic access (1)

Which operations an agent can call, which act, and which need a human in the loop.

- [Riskified Agentic Access](https://apis.io/agentic-access/riskified/riskified-agentic-access/)

#### JSON Schema (25)

The data models the API reads and writes.

- [adaptive_checkout_3ds_declined](https://apis.io/schemas/riskified/riskified-adaptive-checkout-3ds-declined/)
- [adaptive_checkout_psd2_approved](https://apis.io/schemas/riskified/riskified-adaptive-checkout-psd2-approved/)
- [advise_3ds_response](https://apis.io/schemas/riskified/riskified-advise-3ds-response/)
- [advise_cvv_response](https://apis.io/schemas/riskified/riskified-advise-cvv-response/)
- [advise_psd2_response](https://apis.io/schemas/riskified/riskified-advise-psd2-response/)
- [Cancel_Response](https://apis.io/schemas/riskified/riskified-cancel-response/)
- [chargeback_response](https://apis.io/schemas/riskified/riskified-chargeback-response/)
- [Claim_Create_Response_Approve](https://apis.io/schemas/riskified/riskified-claim-create-response-approve/)
- [Claim_Create_Response_Captured](https://apis.io/schemas/riskified/riskified-claim-create-response-captured/)
- [Claim_Create_Response_Decline](https://apis.io/schemas/riskified/riskified-claim-create-response-decline/)
- [Claim_Create_Response_Excluded](https://apis.io/schemas/riskified/riskified-claim-create-response-excluded/)
- [Claim_Create_Response_Review](https://apis.io/schemas/riskified/riskified-claim-create-response-review/)
- [ClaimDecisionRequest](https://apis.io/schemas/riskified/riskified-claim-decision-request/)
- [customer_create](https://apis.io/schemas/riskified/riskified-customer-create/)
- [customer_create_response](https://apis.io/schemas/riskified/riskified-customer-create-response/)
- [customer_update](https://apis.io/schemas/riskified/riskified-customer-update/)
- [decide_response_approve](https://apis.io/schemas/riskified/riskified-decide-response-approve/)
- [decide_response_decline](https://apis.io/schemas/riskified/riskified-decide-response-decline/)
- [login_action](https://apis.io/schemas/riskified/riskified-login-action/)
- [login_action_response](https://apis.io/schemas/riskified/riskified-login-action-response/)
- [OtpInitiateRequest](https://apis.io/schemas/riskified/riskified-otp-initiate-request/)
- [OtpInitiateResponse](https://apis.io/schemas/riskified/riskified-otp-initiate-response/)
- [refund_response](https://apis.io/schemas/riskified/riskified-refund-response/)
- [reset_password_action](https://apis.io/schemas/riskified/riskified-reset-password-action/)
- [submit_response_submitted](https://apis.io/schemas/riskified/riskified-submit-response-submitted/)

#### JSON-LD (1)

Linked-data contexts for the provider's vocabulary.

- [Riskified Context](https://apis.io/jsonld/riskified/riskified-context/)

#### Governance rules (1)

Spectral rulesets for the provider's contracts.

- [Riskified API Rules](https://apis.io/rules/riskified/riskified-rules/)

#### Security (2)

Authentication, trust centre, and vulnerability disclosure.

- [Riskified Domain Security](https://apis.io/security/riskified/riskified-domain-security/)
- [Riskified Trust Center](https://apis.io/security/riskified/riskified-trust-center/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Website](https://www.riskified.com/)
- [Documentation](https://developers.riskified.com/reference/api-environments)
- [Getting started](https://developers.riskified.com/docs/api-integration-guide)
- [API reference](https://developers.riskified.com/reference)
- [Pricing](https://www.riskified.com/pricing)
- [Support](https://support.riskified.com/hc/en-us?_gl=1*h5db4w*_gcl_au*NTY1ODg5MDI2LjE3ODEyNzE2ODkuLS4tLjE3ODQzMTI0MzAuNjY5OTE5ODU0LjE3ODQ3NDQ4MTAuMTc4NDc1MDQ4MQ..*_ga*MTM0Mzk3ODAyNy4xNzgxMjcxNjkz*_ga_L8RV3KLX8W*czE3ODQ3Mzg2NTQkbzc4JGcxJHQxNzg0NzUzMTM1JGo0MyRsMCRoMTM2NzU4NzA1Ng..)
- [Changelog](https://github.com/Riskified/apiref-changelog)
- [Blog](https://www.riskified.com/blog/)
- [Compliance](https://security.riskified.com/)
- [Terms of service](https://www.riskified.com/terms)
- [Privacy policy](https://www.riskified.com/privacy-policy)
- [GitHub](https://github.com/Riskified)
- [Status](https://status.riskified.com)

## API Evangelist rating

**Kin Score 61.6** — strong · rubric 0.25.0 · scored 2026-10-23

| Facet | Score |
|---|---|
| Discoverability | 71.4 |
| Contract quality | 73.0 |
| Contract governance | 22.0 |
| Operational transparency | 55.3 |
| Developer ergonomics | 73.8 |
| Access clarity | 60.5 |

**Agent readiness 47.1** — agent-ready (gated down from agent-native)

| Agent-readiness dimension | Result |
|---|---|
| Spec Presence | yes |
| Agentic Access | derived (partial credit) |
| Reversibility Documented | documented (partial credit) |
| MCP Server | — |
| Auth Clarity | served (partial credit) |
| Idempotency | — |
| Error Semantics | verified |
| OpenAPI Examples | verified |
| Rate Limit Signal | — |
| Event Surface Described | yes |
| Agent Skills | — |
| Well Known Catalog | — |
| Consent Identity | — |
| Agent Card | — |
| Dry Run Mode | — |
| Delegated Identity | served (partial credit) |
| Protected Resource Metadata | verified |
| Dynamic Client Registration | — |
| Agentic Commerce | — |
| Pagination Ratio | na |
| Operation Distinctiveness | distinct |

**Regulatory alignment 22.2** — Banking & Open Finance

The rubric is published at [github.com/api-evangelist/kin-score](https://github.com/api-evangelist/kin-score). The per-check breakdown behind these numbers — which checks were earned, partial or missed — along with score history and how this provider compares to its peers, is available at [apis.io/providers/riskified/](https://apis.io/providers/riskified/).

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for Riskified: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/riskified/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).
