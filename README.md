# Riskified (riskified)

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

Riskified (NYSE RSKD) is an Israeli ecommerce risk-management platform headquartered in Tel Aviv, with a US office in New York. Its AI-powered platform uses machine learning, identity intelligence, and a global merchant network to make sub-second decisions across the entire shopper journey, from account creation through checkout to claims and chargeback recovery. The developer portal at developers.riskified.com exposes five product APIs — Chargeback Guarantee, Adaptive Checkout, Account Secure, Policy Protect, and Dispute Resolve (via Chargeback Gateway Integration) — alongside an OTP service and multi-platform Beacon SDK for device intelligence. Authentication is HMAC-SHA256 over the request body, with first-party SDKs for PHP, Java, and .NET and integrations for Shopify, Magento, Salesforce Commerce Cloud, SAP Commerce, commercetools, VTEX, Adyen, Braintree, PayPal, and Stripe.

**URL:** [Visit APIs.json](https://raw.githubusercontent.com/api-evangelist/riskified/refs/heads/main/apis.yml)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

## Tags

 - Fraud, Fraud Prevention, Chargebacks, Ecommerce, Payments, Risk, Machine Learning, Account Takeover, Policy Abuse, 3DS, PSD2, Returns

## Timestamps

- **Created:** 2026-05-25
- **Modified:** 2026-05-25

## APIs

### Riskified Chargeback Guarantee API
Submit orders for fraud and chargeback risk evaluation through pre-authorization (Decide / Decision) or post-authorization (Submit / Decide) flows. Returns APPROVED, DECLINED, or SUBMITTED, with approved orders financially guaranteed against fraudulent chargebacks. Cancel, Fulfill, Refund, Chargeback, and Checkout Denied endpoints keep order lifecycle state in sync.

**Human URL:** [https://developers.riskified.com/reference/post-auth-flow-decide](https://developers.riskified.com/reference/post-auth-flow-decide)

**Base URL:** `https://wh.riskified.com/`

### Riskified Adaptive Checkout API
Recommend the optimal authentication path at checkout — friction-free, CVV, 3DS, or PSD2 exemption — to maximize approval rates while remaining SCA-compliant. Advise returns a recommendation; Decide commits to a Riskified-guaranteed outcome. Covers both regulated (PSD2/SCA) and non-regulated geographies.

**Human URL:** [https://developers.riskified.com/reference/advise](https://developers.riskified.com/reference/advise)

**Base URL:** `https://api.riskified.com/`

### Riskified Account Secure API
Protect non-purchase customer journeys against account takeover, synthetic identity, and credential abuse. Submit Login, Reset Password, Customer Create, and Customer Update events and receive a real-time decision so merchants can step up authentication, block, or allow.

**Human URL:** [https://developers.riskified.com/reference/login](https://developers.riskified.com/reference/login)

**Base URL:** `https://api.riskified.com/`

### Riskified Policy Protect API
Detect and prevent refund, return, and promotional abuse. Submit refund and return claims for adjudication (`claim_create`), retrieve Riskified's decision (`claim_decision`), and update in-flight returns (`claim_update`). Supports both original-flow and replacement-flow review patterns.

**Human URL:** [https://developers.riskified.com/reference/refunds-claim_create](https://developers.riskified.com/reference/refunds-claim_create)

**Base URL:** `https://api.riskified.com/`

### Riskified OTP API
Initiate a one-time password challenge as a step-up verification mechanism for high-risk login, password reset, or account modification events. Pairs with the Account Secure API to mediate friction adaptively.

**Human URL:** [https://developers.riskified.com/reference/otp-initiate](https://developers.riskified.com/reference/otp-initiate)

**Base URL:** `https://otp.self-veri.com/recover/v1/otp/`

### Riskified Beacon (Device Intelligence) SDK
Collect device, browser, and behavioral telemetry from the shopper's session and feed it into Riskified's risk models. Delivered as a JavaScript snippet for web and as iOS, Android, React Native, and Unity SDKs. Required for accurate decisioning across all Riskified products.

**Human URL:** [https://developers.riskified.com/reference/beacon-sdks](https://developers.riskified.com/reference/beacon-sdks)

### Riskified Chargeback Gateway Integration (CGI) API
Connect Riskified directly to a payment gateway (Adyen, Braintree, PayPal, Shopify Payments, Stripe) so chargeback notifications and evidence flow into Dispute Resolve without merchant glue code. Powers automated chargeback representment and recovery.

**Human URL:** [https://developers.riskified.com/docs/chargeback-gateway-integration-cgi-overview](https://developers.riskified.com/docs/chargeback-gateway-integration-cgi-overview)

## Common Properties

- [Portal — riskified.com](https://www.riskified.com)
- [Portal — Developer Portal](https://developers.riskified.com/)
- [APIReference](https://developers.riskified.com/reference)
- [GettingStarted — API Integration Guide](https://developers.riskified.com/docs/api-integration-guide)
- [Authentication](https://developers.riskified.com/reference/api-authentication)
- [Documentation — API Environments](https://developers.riskified.com/reference/api-environments)
- [Documentation — API Overview](https://developers.riskified.com/reference/api-overview)
- [Documentation — HTTP Responses](https://developers.riskified.com/reference/http-responses)
- [Documentation — Notifications](https://developers.riskified.com/reference/notifications)
- [Documentation — Retries](https://developers.riskified.com/reference/retries)
- [Documentation — Integrated Platforms](https://developers.riskified.com/reference/integrated-platforms)
- [Documentation — Integration Hub Guide](https://developers.riskified.com/docs/integration-hub-guide)
- [Documentation — Integration Timeline](https://developers.riskified.com/docs/integration-timeline)
- [Documentation — SSO](https://developers.riskified.com/docs/sso)
- [Documentation — llms.txt](https://developers.riskified.com/llms.txt)
- [AboutUs](https://www.riskified.com/about)
- [Blog](https://www.riskified.com/blog/)
- [PressReleases — Newsroom](https://www.riskified.com/press/)
- [CaseStudies — Customers](https://www.riskified.com/customers/)
- [Library — Resources](https://www.riskified.com/resources/)
- [Careers](https://www.riskified.com/careers/)
- [Contact — Sales](https://www.riskified.com/contact)
- [Pricing](https://www.riskified.com/pricing)
- [TermsOfService](https://www.riskified.com/terms)
- [PrivacyPolicy](https://www.riskified.com/privacy-policy)
- [StatusPage](https://status.riskified.com)
- [InvestorRelations — NYSE RSKD](https://ir.riskified.com)
- [ProductInformation — Adaptive Checkout](https://www.riskified.com/adaptive-checkout/)
- [ProductInformation — Chargeback Guarantee](https://www.riskified.com/chargeback-guarantee/)
- [ProductInformation — Account Secure](https://www.riskified.com/account-secure/)
- [ProductInformation — Policy Protect](https://www.riskified.com/policy-protect/)
- [ProductInformation — Dispute Resolve](https://www.riskified.com/chargeback-guarantee/dispute-resolve/)
- [LinkedIn](https://www.linkedin.com/company/riskified)
- [Facebook](https://www.facebook.com/RiskifiedInc)
- [Instagram](https://www.instagram.com/riskified/)
- [GitHubOrganization](https://github.com/Riskified)
- [SDK — PHP (Packagist)](https://packagist.org/packages/riskified/php_sdk)
- [SDK — Java (Maven Central)](https://central.sonatype.com/artifact/com.riskified/riskified-sdk)
- [SDK — .NET (NuGet)](https://www.nuget.org/packages/Riskified.SDK)
- [SDK — PHP on GitHub](https://github.com/Riskified/php_sdk)
- [SDK — Java on GitHub](https://github.com/Riskified/java_sdk)
- [SDK — .NET on GitHub](https://github.com/Riskified/sdk_net)
- [SDK — iOS Beacon](https://github.com/Riskified/riskified_ios_sdk)
- [Samples — API Examples](https://github.com/Riskified/api_examples)
- [Integrations — Magento 1](https://github.com/Riskified/magento)
- [Integrations — Magento 2](https://github.com/Riskified/magento2)
- [Integrations — Magento 2 (refactor)](https://github.com/Riskified/magento2new)
- [Integrations — Magento Deco](https://github.com/Riskified/magento-deco)
- [Integrations — PrestaShop](https://github.com/Riskified/PrestaShop-modules)
- [Integrations — Shopify](https://developers.riskified.com/docs/shopify-integration)
- [Integrations — Salesforce Commerce Cloud](https://developers.riskified.com/docs/sfcc)
- [Integrations — SAP Commerce / Hybris](https://developers.riskified.com/docs/sap-commerce-hybris)
- [Integrations — commercetools](https://developers.riskified.com/docs/commercetools)
- [Integrations — VTEX](https://developers.riskified.com/docs/vtex)
- [ChangeLog — apiref-changelog](https://github.com/Riskified/apiref-changelog)

## Maintainers

**FN:** Kin Lane

**Email:** info@apievangelist.com
