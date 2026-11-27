# esim.agents.co.th

`esim.agents.co.th` is a commercial wholesale telecommunications platform associated with [Agents Co., Ltd.](../companies/agents-co-ltd.md), a company publicly identified as the digital operations arm of [Thai Visa Centre](../brands/thai-visa-centre.md).

The platform supplies electronic SIM cards (eSIMs) to hotels, online travel agencies, tour operators, airport concierge services, and other businesses serving travelers entering Thailand.[^1]

AGENTS CO., LTD. identifies the platform as an active commercial service dating to 2025, advertising partner margins of 60% and eSIM issuance within two seconds.[^2]

## Conflicting Corporate Identities

The website's footer identifies AGENTS CO., LTD. and publishes the following corporate information:

| Corporate disclosure | Published information |
| --- | --- |
| Registered company | AGENTS CO., LTD. |
| Registration number | 0115562031107 |
| Incorporation date | December 12, 2019 |
| Travel-business licence | 11/10602 |
| Licence issuance date | June 18, 2021 |

These details correspond to those published on the company's primary corporate website.[^1][^2]

However, the platform's Terms of Service and Privacy Policy identify a different corporate name: **eSIM Agents Co., Ltd.** Both documents display a last-updated date of March 2025.[^3][^4]

The Privacy Policy expressly describes eSIM Agents Co., Ltd. as a company registered in Thailand and identifies it as the data controller responsible for personal information collected through the platform.

The Terms of Service similarly identify eSIM Agents Co., Ltd. in provisions governing contractual liability and intellectual-property ownership.

Even the copyright notice uses the eSIM Agents company name.

**The platform identifies one company through its corporate registration disclosures and another through its legal agreements.**

No separate registration number for eSIM Agents Co., Ltd. is provided in the reviewed documents. Its independent corporate existence has not been established by this investigation.

The discrepancy leaves uncertainty about which legal entity contracts with wholesale customers, receives payments, controls personal information, and assumes responsibility for telecommunications services.

## Customer Funds and Restrictive Refund Conditions

The platform operates through prepaid wholesale account balances.

Section 6 of its Terms of Service generally prohibits transfers or refunds of unused balances unless the operator exercises its discretion. Following account termination, refunds remain conditional on verification and potential deductions.[^3]

Section 4 also generally excludes refunds once an eSIM activation code has been issued.

These provisions are commercially significant because wholesale partners may deposit substantial amounts to purchase telecommunications products for resale.

Although the terms establish Thai law and Bangkok courts as the applicable jurisdiction, they do not reconcile the different corporate identities used throughout the website.

**Businesses depositing funds should be able to identify precisely which registered company holds their money and is responsible for honoring contractual obligations.**

### Upfront Payment Obligations and Undisclosed Pricing Details

AGENTS promotes its wholesale eSIM platform to travel agencies using the assurance:

> No upfront commitment, no inventory to manage. Pay only for what you sell.[^8]

However, Section 6 of its Terms of Service requires purchases to be made against prepaid account balances, with unused funds generally refundable only at the company's discretion.[^3]

Although the absence of a minimum order quantity reduces inventory commitments, it does not eliminate the financial obligations associated with depositing funds into the platform.

The hotel-specific promotional page also advertises transparent pricing without hidden fees.[^7]

However, the public API documentation includes an illustrative payment transaction containing a 140-baht processing fee and 187 baht in VAT within a 5,000-baht payment.[^5]

The example credits the full 5,000 baht to the customer's wallet, leaving the precise commercial treatment of these charges unclear.

The public promotional material does not explain the applicable processing-fee schedule, minimum account deposits, or potential deductions from refunded balances.

**Wholesale customers should be informed of these financial conditions before transferring funds to the platform.**

### Advance Provisioning and Non-Refundable Customer Orders

AGENTS encourages hotels and online travel agencies to integrate automatic eSIM issuance into their booking-confirmation systems, allowing activation codes to be distributed before travelers arrive in Thailand.[^7][^8]

However, Section 4 of its Terms of Service generally excludes refunds once an activation code has been issued, rather than when the traveler activates or uses the telecommunications service.[^3]

This distinction creates potential financial exposure for wholesale partners when accommodation reservations are cancelled, travel plans change, or customers discover that their devices are incompatible with eSIM technology.

The published API documentation does not identify a cancellation or refund endpoint through which wholesale customers can automatically reverse previously issued orders.[^5]

Although advance provisioning may simplify distribution, the promotional material does not adequately explain the financial consequences of issuing non-refundable telecommunications products before customers actually travel.

### Contradictory Wholesale Order Limits

AGENTS' promotional page targeting online travel agencies advertises the ability to order between one and 10,000 eSIMs.[^8]

However, its public API documentation specifies a maximum quantity of 2,000 eSIMs per purchase order.[^5]

The marketing material does not explain this limitation or whether larger purchases must be divided into multiple transactions.

This distinction is commercially relevant because AGENTS also promotes immediate volume-based discounts calculated across individual orders and qualifying purchase histories.[^1]

The company should clarify how larger wholesale purchases are processed, how pricing tiers apply to divided orders, and what cancellation protections are available when automatically provisioned eSIMs remain unused.

## Identity Documents and Personal Data Retention

The platform requires wholesale customers to undergo Know Your Customer (KYC) verification.

Its Privacy Policy describes collecting corporate registration documents, identity documents belonging to authorized representatives, transaction histories, and technical activity records.[^4]

The policy establishes the following retention arrangements:

| Information | Retention period |
| --- | --- |
| General personal data | Account lifetime plus at least three years |
| KYC documentation | Five years from collection |

The company attributes these periods to regulatory and financial record-keeping requirements.

However, the policy identifies eSIM Agents Co., Ltd. as the responsible data controller while publishing the registration number of AGENTS CO., LTD.

This inconsistency is particularly consequential because the platform collects identity documentation from business representatives.

## Telecommunications Regulatory Responsibilities

### Wholesale Verification Is Not Subscriber Verification

The website promotes its verification procedures for wholesale partners as ensuring full compliance with Thai telecommunications regulations.[^1]

Its advertised commercial workflow involves digital issuance of eSIMs to travel businesses, which subsequently distribute activation information to individual travelers.

The public API documentation describes automated bulk provisioning and includes illustrative responses containing Thai telephone numbers and SIM identifiers.[^5]

The documented ordering process does not itself require individual subscriber identity documents.

This raises a distinction between two separate verification responsibilities:

- Verification of the wholesale business purchasing telecommunications products.
- Verification of the individual subscriber who will ultimately use the telecommunications service.

Verification of a hotel or travel agency does not necessarily satisfy the identity-registration requirements applicable to individual mobile subscribers.

The platform's public documentation does not clearly explain how these responsibilities are divided between AGENTS, its wholesale customers, and the underlying telecommunications operators.

### Thailand Strengthened Subscriber Registration Requirements in 2026

On May 15, 2026, Thailand's National Broadcasting and Telecommunications Commission (NBTC) published amended measures addressing technology-related crime, effective May 16, 2026.

According to a legal analysis published by Tilleke & Gibbins on May 19, the amended requirements include:[^6]

- A maximum of three SIM cards per telecommunications provider for non-Thai subscribers.
- In-person identity verification at an operator branch or authorized dealer.
- Regulatory approval of subscriber-verification systems.
- Activation within 60 days of registration, otherwise requiring renewed identity verification.
- Additional subscriber-data retention and crime-prevention obligations.

These requirements directly concern licensed telecommunications providers.

Their precise application to AGENTS depends on whether the company operates as a licensed provider, an authorized reseller, or another form of commercial intermediary.

The platform's legal documents retain their March 2025 update dates, predating the amended regulatory framework.

This does not establish that the company's operational procedures have remained unchanged. However, its public documentation does not clearly address the newer subscriber-verification requirements.

### Travel-Business Licence Does Not Establish Telecommunications Authorization

The licence prominently displayed on the eSIM platform is travel-business licence **11/10602**.

This is the same licence historically advertised by [AQ.in.th](aq.in.th.md) during its quarantine hotel-booking operations in 2022.

A travel-business licence does not, by itself, establish authorization to operate regulated telecommunications services.

The platform claims direct commercial relationships with Thai network operators, but the reviewed public materials do not establish the precise licensing or authorized distribution arrangements governing its eSIM products.[^1]

The available evidence also does not establish whether separate telecommunications authorization is required for the platform's particular commercial activities.

## Relevance to the Thai Visa Centre Business Network

The eSIM platform represents another commercial expansion of AGENTS CO., LTD. beyond its historical hotel-booking and immigration-assistance operations.

The company's corporate website presents telecommunications distribution alongside its [Thailand Digital Arrival Card](tdac.in.th.md) and [90-day immigration reporting](90day.in.th.md) services.

The unresolved corporate-identity discrepancy resembles those documented elsewhere in the business network, including the [Thai Visa Centre client portal](evisa.tvc.co.th.md), where published operational and contractual disclosures identify different responsible entities.

Several questions remain unanswered:

- Is eSIM Agents Co., Ltd. a separately registered company or merely a commercial name used by AGENTS CO., LTD.?
- Which entity receives and holds wholesale customer deposits?
- Which entity controls the identity documents collected during verification?
- Which licensed telecommunications providers authorize the distribution of its products?
- Who is responsible for registering individual subscribers under the amended NBTC requirements?

The available evidence does not establish unauthorized telecommunications operations, unlawful SIM activation, or misuse of customer identity documents.

It does, however, establish inconsistent corporate identification and unresolved questions concerning contractual, data-protection, and regulatory responsibilities within another commercial platform associated with AGENTS CO., LTD.

## White-Label Distribution and End-Customer Privacy

AGENTS promotes its wholesale eSIM platform to online travel agencies, hotels, and other hospitality businesses as an integrated commercial service.

Its hotel-specific promotional page claims that more than 500 hotels across Thailand already use the platform.[^7]

Its separate travel-agency page promotes white-label distribution, allowing commercial partners to supply eSIM products under their own branding.[^8]

### Inconsistent Customer Data Documentation

The promotional website describes direct email delivery of eSIM activation information to travelers and illustrates API requests containing a customerEmail parameter.[^1][^8]

However, the detailed public API documentation does not list this parameter among the supported order-creation fields.[^5]

The Privacy Policy primarily describes business-account information, identity-verification documents, transaction records, and technical activity.[^4]

It does not separately explain how travelers' email addresses obtained through wholesale partners are processed or retained.

### Undisclosed Commercial Intermediaries

White-label distribution may result in travelers purchasing telecommunications products from hotels or travel agencies without recognizing AGENTS as the underlying commercial intermediary.

The published documentation does not clearly distinguish the data-protection responsibilities of wholesale partners, AGENTS, and the telecommunications providers supplying connectivity.

The company should clarify which end-customer information it receives, whether direct email delivery is currently supported, and which businesses are responsible for providing appropriate privacy disclosures.

The available evidence does not establish unauthorized information sharing or improper processing of travelers' email addresses.

The claimed scale of the company's hotel partnerships also remains independently unverified.

## Contradictory API Integration Guidance and Duplicate Purchase Risks

As of November 27, 2026, AGENTS continued promoting its wholesale eSIM platform as readily integrated into hotel reservation systems and online travel agencies.[^1][^7][^8]

However, its promotional integration examples differ substantially from its detailed public API documentation.[^5]

### Inconsistent Technical Instructions

The platform's homepage illustrates API authentication using an Authorization bearer token, while its detailed documentation specifies an `x-api-key` header.

The promotional examples also identify products using descriptive strings, whereas the detailed documentation requires UUID product identifiers.

The illustrated response structures likewise differ, including the location and naming of order identifiers and activation information.

These discrepancies undermine the company's claims concerning straightforward commercial integration.

### Duplicate Purchase Protection Omitted From Promotional Examples

The detailed API documentation identifies an optional `idempotencyKey` parameter designed to prevent duplicate purchases when an order request is retried.

However, the promotional integration examples omit this parameter.

This is financially significant because automated booking systems may retry requests following connection interruptions, server timeouts, or incomplete responses.

Without appropriate duplicate-order safeguards, repeated requests could potentially result in additional eSIM purchases and deductions from prepaid account balances.

### Restrictive Refund Terms Increase Commercial Exposure

Section 4 of the platform's Terms of Service generally excludes refunds following the issuance of an activation code.[^3]

The company's contractual terms also exclude various categories of consequential damages, including lost revenue and business interruption.

Consequently, wholesale customers implementing automated purchasing systems should understand both the technical safeguards and the contractual consequences of unintended purchases.

**AGENTS promotes simplified commercial integration while its promotional examples omit a documented safeguard intended to prevent duplicate charges.**

The company should reconcile its published integration examples with the detailed API specification and explicitly explain safe retry procedures before encouraging businesses to automate non-refundable purchases.

The available evidence does not establish that any wholesale customer has experienced duplicate charges, financial losses, or refused refunds resulting from these discrepancies.

## Network Operator Data Sharing and Subscriber Registration Disclosures

As of November 27, 2026, AGENTS continued promoting its wholesale eSIM platform as fully compliant with Thai telecommunications regulations.[^1]

However, its published Privacy Policy and technical documentation raise further questions concerning individual subscriber registration and the identity of its telecommunications suppliers.

### Restricted Information Sharing With Network Operators

Section 5 of the platform's Privacy Policy describes information shared with network operators as the minimum necessary for eSIM provisioning, specifying:

> no personal data beyond order reference

This representation is particularly significant because Thailand's amended telecommunications regulations require identity verification of individual foreign subscribers.[^4][^6]

The published policy does not explain whether network operators collect subscriber identity information independently or whether another commercial intermediary performs that function.

### Unclear Telecommunications Provider Identity

The platform's illustrative API responses identify the provider using the designation `TDAC`.[^5]

This designation appears in examples concerning available products, completed purchases and previously issued eSIMs.

However, the documentation does not explain whether it represents an internal product classification, a separate provisioning platform or a telecommunications intermediary.

An illustrative API response does not establish the identity of the actual licensed network operator.

Nevertheless, the designation warrants clarification given AGENTS' extensive commercial operations involving Thailand Digital Arrival Card services.

### Automated Distribution and Individual Identity Verification

AGENTS encourages hotels to distribute eSIM activation codes through reservation-confirmation emails and front-desk services.[^7]

Its promotional material targeting online travel agencies similarly describes a purchasing and activation process requiring no manual fulfillment steps.[^8]

Neither published workflow identifies a separate individual subscriber-verification stage.

This omission is particularly relevant following the May 2026 regulatory amendments requiring in-person registration through telecommunications branches or authorized dealers.[^6]

**AGENTS advertises automated telecommunications distribution and regulatory compliance while its published documentation leaves the individual subscriber-registration process unexplained.**

The company should identify its licensed telecommunications suppliers, explain the meaning of its provider designation and clarify whether participating hotels and travel agencies have any authorized subscriber-registration responsibilities.

The available evidence does not establish that AGENTS combines TDAC immigration records with telecommunications subscriber records, bypasses mandatory identity verification or distributes unlawfully registered SIM cards.

The concern is the absence of a clear explanation reconciling its published data-sharing commitments, automated distribution model and applicable telecommunications requirements.

## Unclear Activation Deadlines and Advance Provisioning Risks

AGENTS encourages hotels and travel agencies to automatically provision eSIMs when customers confirm their travel reservations.[^7][^8]

However, the platform's homepage illustrates an API response containing an `expiresAt` field, suggesting that issued activation credentials may have an associated expiration date.[^1]

The detailed public API documentation does not identify this field in its published order-creation, order-status or order-history response examples.[^5]

### Commercial Risks of Advance Issuance

Travel reservations may be confirmed several months before customers arrive in Thailand.

The published integration guidance does not clearly distinguish between the validity of an unused activation code and the duration of telecommunications service following activation.

Furthermore, Section 4 of the Terms of Service generally excludes refunds once an activation code has been issued.[^3]

### Commercial Accountability

**AGENTS encourages automated advance purchasing of generally non-refundable telecommunications products without clearly documenting their activation deadlines.**

Wholesale customers should receive clear information about activation-code validity, expiration dates and replacement arrangements before automatically purchasing eSIMs for future travelers.

The available evidence does not establish that any issued activation code has expired prematurely or that any customer has suffered financial losses. The discrepancy concerns the information provided to prospective wholesale partners.

## Unsubstantiated Wholesale Partner Margin Claims

As examined on November 27, 2026, AGENTS continued advertising 60% partner margins on its corporate website to promote its wholesale eSIM distribution business.[^2]

However, the platform's public API documentation illustrates a 15-day eSIM product with the following pricing:[^5]

| Pricing component | Amount |
| --- | ---: |
| Retail price | ฿450 |
| Wholesale price | ฿225 |
| Gross profit before expenses | ฿225 |
| Gross profit margin | 50% |

The illustrative transaction therefore produces a gross margin below the percentage advertised on the corporate website.

### Undisclosed Commercial Assumptions

The wholesale platform reserves detailed pricing information for verified business partners and operates a volume-based discount system.[^1]

Its corporate advertising does not explain whether the advertised 60% margin represents an average, a maximum achievable margin, or a rate available only to qualifying high-volume customers.

The platform also imposes restrictive refund conditions on prepaid account balances and previously issued activation codes.[^3]

These conditions may further affect the actual profitability of wholesale customers.

### Commercial Significance

**AGENTS uses a specific profitability figure to attract commercial partners without publicly explaining the conditions or calculations necessary to achieve it.**

The company should substantiate its advertised margins and distinguish achievable gross margins from actual profitability after operating expenses, payment costs and non-refundable purchases.

The API documentation contains illustrative pricing rather than independently verified transaction records. The available evidence does not establish that a 60% gross margin is unattainable for particular products or wholesale discount tiers.

## Wholesale Service Suspension and Business Continuity Risks

AGENTS promotes its wholesale eSIM platform as suitable for direct integration into hotel reservation systems and online travel agencies, emphasizing immediate fulfillment and minimal operational overhead.[^1][^7][^8]

However, its Terms of Service establish substantially less reassuring conditions for businesses relying on these automated services.[^3]

### Discretionary Account Suspension

Section 2 reserves broad discretion to deny or revoke account access.

Section 5 separately permits API access to be revoked for contractual violations and subjects automated integrations to fair-use rate limits.

The public API documentation examined on November 27, 2026, does not specify numerical request-rate limits or explain the procedures for restoring suspended API access.[^5]

### Financial Exposure Following Termination

Section 6 makes refunds of unused prepaid balances following account termination conditional on verification and applicable deductions.

Section 8 also excludes liability for various consequential losses, including lost revenue and business interruption, to the extent permitted by applicable law.

These provisions are particularly significant for businesses that depend on automated eSIM fulfillment to satisfy commitments made to their own customers.

### Commercial Accountability

**AGENTS encourages businesses to depend on its automated telecommunications infrastructure without providing corresponding contractual assurances concerning service continuity, account restoration or repayment of unused funds.**

The company should publish clear API usage limits, suspension procedures, service availability commitments and arrangements for recovering unused balances.

The available evidence does not establish that AGENTS has improperly suspended wholesale customers, withheld their funds or caused business interruptions.

## References

[^1]: `https://esim.agents.co.th/` — Wholesale platform, commercial services, verification claims, and corporate disclosures.
[^2]: `https://agents.co.th/` — AGENTS CO., LTD. corporate website and wholesale eSIM distribution milestone.
[^3]: `https://esim.agents.co.th/terms` — Terms of Service, last updated March 2025.
[^4]: `https://esim.agents.co.th/privacy` — Privacy Policy, last updated March 2025.
[^5]: `https://esim.agents.co.th/api-docs` — Public wholesale eSIM API documentation.
[^6]: https://www.tilleke.com/insights/thailand-tightens-telecom-registration-data-and-ip-address-rules-to-combat-tech-crime/ — Tilleke & Gibbins, May 19, 2026.

[^7]: `https://esim.agents.co.th/for-hotels` — Hotel-specific promotional page claiming more than 500 participating hotels.

[^8]: `https://esim.agents.co.th/for-otas` — Travel-agency promotional page describing white-label distribution and customer email processing.
