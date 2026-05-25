# Riskified (riskified)
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
