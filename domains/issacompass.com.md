# issacompass.com

`issacompass.com` is a commercial Thai visa services website whose technical infrastructure bears notable similarities to websites associated with [Thai Visa Centre](../brands/thai-visa-centre.md).[^1]

On November 7, 2026, **Jesse Nickles** examined the websites' publicly accessible HTML, JavaScript assets, and HTTP response headers. The examination found that `issacompass.com` uses **React and Next.js**,[^2][^3] the same core technology stack found on [`tvc.co.th`](tvc.co.th.md), [`agents.co.th`](agents.co.th.md), [`90day.in.th`](90day.in.th.md), and [`tdac.agents.co.th`](tdac.agents.co.th.md). Issa Compass uses an older Next.js Pages Router architecture deployed through Vercel, while the Thai Visa Centre-associated websites use newer Turbopack-based Next.js builds behind Cloudflare.[^4][^5][^6][^7]

**This level of technical sophistication is unusual for the visa agency industry**, where businesses commonly operate relatively simple websites built with WordPress, Wix, or other off-the-shelf content management systems and website builders. Maintaining custom React and Next.js applications requires substantially more development expertise and infrastructure than a typical visa agency website. The presence of closely related technology stacks across these otherwise separate visa-service websites is therefore a noteworthy technical similarity.

## Technical fingerprints

The November 7, 2026 examination compared three types of publicly accessible technical evidence:

- **HTML markup:** Framework and routing indicators embedded in the websites' rendered pages.
- **JavaScript assets:** Next.js bundle structures and build-system characteristics.
- **HTTP response headers:** Information identifying the hosting platform and content delivery infrastructure.

The examination identified React and Next.js Pages Router on `issacompass.com`, with deployment through Vercel. The four comparison websites used Next.js builds associated with Turbopack and were delivered through Cloudflare.

These findings establish similarities in the underlying application frameworks, alongside differences in their build architectures and deployment infrastructure.

## Technical comparison

| Website | Framework | Architecture | Hosting / CDN |
|---|---|---|---|
| `issacompass.com` | React / Next.js | Pages Router | Vercel |
| [`tvc.co.th`](tvc.co.th.md) | React / Next.js | Turbopack-based | Cloudflare |
| [`agents.co.th`](agents.co.th.md) | React / Next.js | Turbopack-based | Cloudflare |
| [`90day.in.th`](90day.in.th.md) | React / Next.js | Turbopack-based | Cloudflare |
| [`tdac.agents.co.th`](tdac.agents.co.th.md) | React / Next.js | Turbopack-based | Cloudflare |

All five websites were identified as using Next.js, although `issacompass.com` differed from the others in its routing architecture and deployment platform.

The comparison provides a baseline for examining more distinctive technical evidence, including shared JavaScript assets, analytics identifiers, API endpoints, and other implementation details that could reveal connections between the websites.

## Related companies

**Issa Compass is an unregistered trade name** used to market commercial Thai visa application services, particularly to Destination Thailand Visa (DTV) applicants. The brand is associated with two separately registered corporate entities in Singapore and Thailand.

| Company | Country | Relationship |
|---|---|---|
| [Issara Platforms Pte. Ltd.](../companies/issara-platforms-pte-ltd.md) | Singapore | Singaporean company identified as a corporate entity behind the Issa Compass brand. |
| [Issa Systems Co., Ltd.](../companies/issa-systems-co-ltd.md) | Thailand | Thai company identified as a corporate entity behind the Issa Compass brand and its local operations. |

The two companies are legally distinct. Their respective responsibilities, ownership structures, and financial relationships require further documentation.

## Related people

Several individuals have been publicly associated with Issa Compass through its founding, management, and marketing activities.

| Person | Relationship |
|---|---|
| [Priscilla Yeung](../people/priscilla-yeung.md) | Singaporean co-founder of Issa Compass, previously employed in corporate strategy at foodpanda and Boston Consulting Group. |
| [Andrei-Nicusor Covalescu](../people/andrei-nicusor-covalescu.md) | Joined Issa Compass as Head of Marketing in August 2025, following Titiksha Tolia's departure. |
| [Titiksha Tolia](../people/titiksha-tolia.md) | Former marketing executive associated with Issa Compass from February 2024 until August 2025, publicly introduced as Head of Marketing. |

These individuals' documented roles provide context for the brand's management, marketing, and operational history.

## Reported connections to Thai Visa Centre

Jesse Nickles alleges that the unregistered Issa Compass trade name and [Thai Visa Centre](../brands/thai-visa-centre.md), another unregistered trade name used to advertise Thai immigration services, have overlapping personnel and promotional activities.

According to Nickles, social-media accounts associated with these operations have promoted both brands through fabricated customer testimonials and recommendations, particularly in online communities discussing Thailand's Destination Thailand Visa (DTV).

These alleged connections extend beyond the React and Next.js similarities documented above. The investigation is examining whether the two brands share personnel, management, marketing infrastructure, or other operational resources despite publicly presenting themselves as separate visa-service businesses.

## Money-Back Guarantee Subject to Post-Payment Eligibility Decisions

Issa Compass prominently advertises a money-back guarantee as a central advantage of its paid visa-application services.

Its homepage promises to refund the company's service fee when it files a pre-qualified application that is subsequently rejected by government authorities.[^1]

The website also describes every Full Service application as being pre-qualified before submission.

However, the company's Terms of Service, last updated November 13, 2026, establish additional conditions that substantially limit this protection.[^8]

**Customers can pay for a plan advertised with a money-back guarantee before learning whether Issa Compass will actually grant them that protection.**

If the company subsequently determines that their case does not qualify, the contract may permit it to retain the payment as service credit rather than issue a cash refund.

### The Public Promise

Issa Compass presents its refund guarantee alongside its document-review and professional application services.

The homepage emphasizes that applications undergo eligibility checks before formal submission.[^1]

For customers considering a paid service, this creates an important expectation: the agency will assess the application before filing it, and qualifying customers will receive their service fees back if the government refuses approval.

The website distinguishes between its free self-service option and paid Full Service assistance.

The money-back guarantee is presented as a feature of the latter.

However, **pre-qualification for a visa application and qualification for the company's refund guarantee are separate decisions under its contractual terms**.

That distinction is not immediately apparent from the homepage's promotional explanation.

### The Guarantee Is Not Automatically Included

Section 7.3 of the Terms of Service states that refund protection applies only to purchased plans expressly identifying the guarantee as an included feature.[^8]

A customer purchasing another plan receives no equivalent contractual protection against visa refusal.

Even where a plan advertises the guarantee, coverage is conditional.

For purchases covered by Section 7.3.7, the company's legal team must separately confirm that the individual application qualifies.

The terms explicitly establish that **purchasing a plan containing the guarantee does not itself establish that the customer's case is covered**.

The company therefore distinguishes between two stages:

1. Selling a plan that advertises refund protection.
2. Subsequently determining whether a particular customer's application qualifies for that protection.

This distinction becomes commercially significant when payments are collected before the second decision.

### Customers Can Pay Before Coverage Is Confirmed

Section 7.3.7(f) directly addresses customers who pay before receiving confirmation of guarantee eligibility.

If Issa Compass subsequently decides that the application does not qualify, the terms state that the customer cannot obtain an ordinary service-fee refund under the guarantee.[^8]

The contract instead provides alternative arrangements.

Customers can proceed with another recommended visa, continue without refund protection, or discontinue the application.

However, discontinuing does not necessarily entitle the customer to recover their money.

Under Section 7.3.7(c)(iii), Issa Compass retains service fees as credit toward another visa service.

That credit remains available for **12 months from the customer's first payment**.

The separately defined Initial Assessment Fee remains non-refundable.

**A customer who pays for a plan expecting refund protection may discover that the protection does not apply, decline to proceed, and receive service credit rather than their money back.**

These provisions apply to plans whose first payment occurred on or after November 14, 2026, subject to the other contractual conditions.

They should not be retroactively attributed to earlier purchases.

### The Company Can Withhold the Reason for Denial

The contract creates another transparency concern.

Section 7.3.7(b) allows the company's legal team to determine that an application does not qualify for the guarantee.

Where the reason is straightforward, the terms say that the company will explain it.

However, the same provision allows Issa Compass to withhold detailed reasoning when disclosure would reveal its internal methods or professional know-how.[^8]

In those circumstances, customers may receive only a general explanation that the decision resulted from the legal team's assessment.

**The company reserves discretion to deny refund protection without necessarily disclosing the specific criteria that caused the customer's case to fail its internal assessment.**

This does not establish that Issa Compass makes arbitrary decisions.

It establishes that the published contract permits important eligibility decisions to be based on criteria customers may not be able to examine or independently challenge.

That discretion becomes more consequential when the customer has already paid.

### Refund Exclusions Extend Beyond Visa Eligibility

The Terms of Service impose additional conditions that can eliminate refund protection even after a customer has been accepted into the guarantee.

These include:

- Failure to attend a requested embassy interview.
- Failure to provide additional documents reasonably obtainable by the applicant.
- Leaving the application country while the visa is being processed.
- Failure to maintain qualifying funds in the same bank account.
- Undisclosed previous visa refusals or relevant immigration history.
- Criminal convictions.
- Certain passport problems.
- Independently submitting an application under a plan requiring the agency to handle submission.

Some of these restrictions address legitimate problems that an immigration adviser cannot control.

However, others require customers to maintain particular circumstances throughout a government process whose duration and additional documentary requests may be unpredictable.

The published guarantee therefore protects a narrower group of unsuccessful applications than the homepage's simplified description might suggest.

**A government refusal does not automatically trigger a refund merely because Issa Compass prepared or submitted the application.**

### Government Policy Changes Can Eliminate Cash Refund Options

The company's Terms of Service also address changes to immigration rules after a customer purchases a plan.

Under Section 7.3.5, changes to government eligibility requirements or available application routes do not count as visa refusals for guarantee purposes.[^8]

The company may instead attempt to arrange an alternative application route.

If no alternative route remains available, its contractual remedy is to refund government charges not yet paid and provide a 12-month credit for its own service fees.

The Initial Assessment Fee remains non-refundable.

This arrangement places part of the commercial risk of regulatory changes on the customer.

That is significant for a company advertising expertise in changing immigration requirements.

**Even when an application cannot proceed because the government eliminates the available route, the customer may be offered credit toward another service rather than a cash refund of the original service fee.**

The provision does not establish that the company caused the regulatory problem.

It establishes the limited contractual remedy offered when the service originally purchased becomes unavailable.

### Refund Protection Changed During 2026

The terms distinguish between several purchase dates.

For eligible plans purchased on or before August 28, 2026, the contract preserves an earlier guarantee under which customers could choose between a broader refund, including government fees, and a further application without an additional service fee.

For purchases beginning August 29, the guarantee generally became limited to the agency's service fee, excluding government and embassy charges.

For applicable purchases beginning November 14, the additional legal-assessment and service-credit provisions took effect.

These distinctions matter because customers purchasing an apparently similar service at different times may possess materially different refund rights.

**The company's money-back promise has not operated under one uniform set of contractual conditions throughout 2026.**

Any assessment of a customer's refund entitlement must therefore consider the date of the first payment and the version of the guarantee applicable at that time.

### Professional Review Does Not Establish Guaranteed Protection

Issa Compass markets document verification, eligibility screening, and professional assistance as reasons to trust its application service.

Those activities may genuinely reduce avoidable mistakes.

However, the contract separately states that immigration decisions remain with government authorities and cannot be guaranteed.[^8]

That disclaimer is reasonable.

The issue is the distinction between guaranteeing government approval, which the company cannot do, and guaranteeing a contractual refund, which it can define and administer.

**The agency advertises financial reassurance against an unsuccessful application while reserving substantial discretion over whether that reassurance applies to the individual customer.**

Customers should be able to establish their precise refund rights before making a non-refundable payment.

### Questions About Consumer Transparency

Issa Compass should clarify whether it confirms money-back eligibility before customers pay the Initial Assessment Fee.

It should also explain whether customers are prominently informed that a plan advertised with a guarantee can later be declared ineligible for that guarantee.

Further questions include:

1. What objective criteria determine guarantee eligibility?
2. Can a customer obtain a written explanation when coverage is refused?
3. How many paying customers have been denied coverage after purchase?
4. How often are service credits issued instead of cash refunds?
5. What happens to unused credits after the 12-month period?
6. Are customers informed of the applicable contractual version before their first payment?

The available evidence does not establish that Issa Compass has improperly refused a refund or violated consumer-protection law.

Nor does it establish that the company conceals these provisions from customers during the payment process.

**What is established is that its published contract permits customers to pay for plans advertising refund protection before the company confirms that their particular case qualifies, with potentially limited cash-refund rights if coverage is subsequently denied.**

That is a material qualification to the money-back guarantee prominently promoted on the website.

### Relevance to the Thai Visa Centre Investigation

The broader investigation examines reported connections between Issa Compass and Thai Visa Centre, including disputed claims about overlapping personnel, marketing activity, and technical infrastructure.

Those alleged connections remain unverified.

The contractual findings documented here stand independently of any conclusion about common ownership or management.

They establish how Issa Compass markets immigration-assistance services and allocates financial risk between itself and paying customers.

They also provide a concrete basis for comparing its commercial practices with the refund policies and processing assurances published by Thai Visa Centre and other immigration-service businesses.

**The central issue is the gap between a prominently advertised money-back guarantee and contractual provisions allowing the company to withhold coverage after payment, retain non-refundable assessment fees, and substitute time-limited service credit for cash refunds.**

That discrepancy warrants clearer disclosure before customers commit money to a visa application.

## References

[^1]: `https://www.issacompass.com/`
[^2]: https://builtwith.com/issacompass.com
[^3]: https://w3techs.com/sites/info/issacompass.com
[^4]: `https://tvc.co.th/`
[^5]: `https://agents.co.th/`
[^6]: `https://90day.in.th/`
[^7]: `https://tdac.agents.co.th/`

[^8]: `https://www.issacompass.com/terms` — Terms of Service, last updated November 13, 2026, particularly Sections 7.3–7.3.7.
