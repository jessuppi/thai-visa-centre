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

However, the company's Terms of Service, previously dated November 13, 2026 and updated November 24, 2026, establish additional conditions that substantially limit this protection.[^8]

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

### Issa Compass's Refund Terms Contradict Its Own Consumer Advice

Issa Compass's article *Document Pre-Checks, Money-Back Guarantees, and Expert Support: What to Demand From Any Thailand Visa Platform Before You Apply*, published April 8, 2026, was previously recorded as updated October 17 and now identifies November 14, 2026 as its latest update.[^12]

The article advises prospective visa customers to evaluate the credibility of refund guarantees. Its comparison table classifies a service-credit-only remedy as weak and reimbursement of the service fee as strong. It also criticizes excessively restrictive conditions and emphasizes transparent eligibility criteria.

**The company's own contractual arrangements provide the type of service-credit remedy that its consumer guide warns against.**

| Consumer guide's standard | Contractual qualification |
| --- | --- |
| Cash reimbursement rather than credit alone | Section 7.3.7 permits time-limited credit when coverage is denied after payment and the customer chooses not to apply. |
| Government refusal of a pre-qualified application as the trigger | Purchasing a plan advertising the guarantee does not establish individual coverage; a separate legal-team decision is required. |
| Transparent conditions | Section 7.3.7(b) permits the company to withhold specific reasons for a negative assessment to protect its internal methods. |

The guide does disclose that the company's guarantee concerns pre-qualified applications filed by Issa Compass, excludes government charges, and is subject to its terms.[^12]

However, it does not explain the distinct financial risk of paying before the company confirms coverage. The guarantee for a covered application refused by the government and the remedy available when the company itself denies eligibility are different contractual mechanisms.

Under Section 7.3.7(c)–(f), a customer who does not proceed following a negative eligibility assessment generally receives a 12-month credit for service fees and the Initial Assessment Fee, with unpaid government charges returned. The assessment fee cannot be recovered in cash under those options. If the customer fails to communicate a choice within 30 days of notice, the contract automatically treats the customer as having chosen not to apply.[^8]

The credit is not necessarily lost in full: if used for a cheaper alternative service, the terms allow reimbursement of the difference, excluding the assessment fee. The provisions also remain subject to applicable law.

Thailand Privilege (Thailand Elite) applications are expressly excluded from Section 7.3.7 and instead follow the separate deposit arrangement in Section 7.3.6. Earlier purchases before November 14 are likewise outside Section 7.3.7.[^8]

**The inconsistency is not that every covered visa refusal results in service credit. It is that the company promotes cash-refund protection as a mark of credibility without explaining in this consumer guide that a paying customer can subsequently be denied that protection and receive the weaker remedy it criticizes.**

Both the consumer comparison and these contractual restrictions remained published when checked on November 24, 2026. The corresponding finding is also documented in the [Issa Compass brand investigation](../brands/issa-compass.md).

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

### Published DTV Guide Still Promises Refunds the Current Contract Excludes

Issa Compass's refund-policy inconsistencies extend beyond the restrictions contained in its Terms of Service.

Its article *Thailand DTV Visa 2026: Requirements, Documents and How to Apply* continues advertising a broader financial guarantee than the company currently provides to new customers.[^9]

The guide was published on March 26, 2026, and identifies August 18, 2026, as its last update.

Under its discussion of DTV costs, the article promises:

> a full refund covering both the government fee and the service fee

The same assurance appears again in its FAQ addressing rejected DTV applications.

The guide estimates ordinary government application charges at approximately 13,000 baht and lists Issa Compass's Full Service fee at 10,000 baht.

Consequently, the difference between the advertised protection and the current contractual guarantee can represent a substantial proportion of the customer's total application expenditure.

**An applicant reading the still-published guide could reasonably expect Issa Compass to reimburse government application charges that its newer contract expressly excludes.**

#### The Contract Changed on August 29, 2026

The company's Terms of Service establish an important historical distinction.[^8]

For qualifying purchases made on or before August 28, 2026, customers retain the refund protection applicable when they paid.

That earlier arrangement included an option to recover both the company's service fee and government application fees following an eligible refusal.

However, Section 7.3 explicitly changed the arrangement for purchases beginning August 29, 2026.

Under the newer terms:

- The guarantee covers the agency's service fee only.
- Government visa fees are excluded.
- Embassy and other third-party charges are excluded.
- Certain partner fees may be covered only when expressly included in the customer's package or payment confirmation.
- Additional eligibility requirements and exclusions apply.

The distinction is not retroactive.

Customers whose first payment preceded the cutoff retain the contractual version applicable to their purchase.

**The problem is that the company's older DTV guide continues presenting the pre-August refund arrangement as a current service benefit without identifying the August 29 cutoff.**

The article does not explain that new customers receive narrower protection.

#### Newer Articles Contradict the Older Guide

Issa Compass's October 2026 guide *Do You Need a DTV Visa Agent? How to Choose One* provides a different explanation.[^10]

Its service comparison identifies the money-back guarantee as a conditional benefit of Full Service applications.

It explicitly explains that agency service fees may be refunded following an eligible refusal, but government and embassy charges are not covered.

Another article, *How Issa Compass Prepares Your Thai Visa Application Before It Ever Reaches the Embassy*, updated September 30, 2026, likewise excludes government charges from its guarantee.[^11]

The discrepancy therefore exists across three company publications.

| Issa Compass publication | Refund representation |
|---|---|
| DTV requirements guide, updated August 18 | Government and service fees covered |
| Application-preparation guide, updated September 30 | Service fee covered, government fee excluded |
| DTV agent-selection guide, updated October 18 | Service fee covered, government fee excluded |
| Current Terms of Service | Service-fee-only guarantee for eligible purchases from August 29 onward |

These differences cannot be explained simply as alternative refund arrangements for different visa categories.

All three articles discuss Issa Compass's DTV application assistance.

The older DTV guide does not identify itself as an archived explanation of terms available before August 29.

**Issa Compass's own website gives prospective DTV customers materially different answers about whether the company will reimburse government fees if their application fails.**

#### Government Non-Refundability Does Not Resolve the Contradiction

Thai embassies generally do not refund visa application fees when an application is refused.

However, that does not prevent a private company from voluntarily reimbursing those charges through a commercial guarantee.

Issa Compass's earlier contract expressly offered that additional financial protection.

The subsequent contractual change removed it for new purchases.

Therefore, simply reminding applicants that government fees are nonrefundable does not explain the difference.

The relevant question is whether **Issa Compass itself** promises to reimburse the customer's government expenditure.

Its older guide says yes.

Its current contract says no for qualifying purchases made from August 29 onward.

The distinction is commercially significant because the government fee may exceed the agency's service fee.

#### The Missing Correction

Issa Compass should update its DTV requirements guide to identify the guarantee applicable to new purchases.

It should also clearly distinguish historical refund entitlements from current contractual protection.

Customers should not need to compare several articles and a lengthy legal agreement to discover whether government application charges are included.

The company should clarify whether customers purchasing services after August 28, 2026, were shown the older refund promise during the payment process.

The available evidence does not establish that the company has refused to honor a valid historical guarantee or that particular customers suffered financial losses.

It also does not establish whether affected customers received individualized disclosures correcting the outdated article.

**What is established is that Issa Compass continues publishing an explicit promise to refund government application fees despite having removed that protection from the contractual guarantee offered to new customers.**

This reinforces the broader finding that the company's prominently marketed financial assurances require careful examination against the actual terms applicable at the time of payment.

**A visa-service company advertising refund protection should not leave an obsolete, more generous promise on its public website after adopting contractual terms that provide materially narrower coverage.**

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

## Thailand Privilege Deposit and Conditional Refund Arrangements

Issa Compass advertises Thailand Privilege applications without a separate agency service fee, identifying itself as a registered Individual Sales Agent of Thailand Privilege Card Co., Ltd.[^13]

However, Section 7.3.6 of its Terms of Service establishes a separate financial arrangement requiring customers to pay a **5,000-baht deposit** before application preparation and submission.[^8]

### Circumstances Resulting in Deposit Forfeiture

The contractual conditions distinguish several possible outcomes:

| Customer outcome | Deposit treatment |
| --- | --- |
| Membership approved and paid | Refundable |
| Membership application refused | Refundable |
| Customer voluntarily withdraws | Non-refundable |
| Requested documents not supplied within 30 days | Non-refundable |
| Membership payment deadline missed | Non-refundable |

The company treats certain missed deadlines as decisions not to proceed, even without an explicit cancellation request from the customer.

### Full Refund Advertising Versus Processing Deductions

Issa Compass's October 2026 Thailand Privilege guide explicitly acknowledges the deposit and describes eligible refunds as being returned in full.[^14]

However, Section 7.3.6(d) permits deductions for bank or card-processing charges and specifies a refund-processing period of up to 30 business days.[^8]

The guide does not explain these deductions.

### Incomplete Disclosure on the Main Sales Page

The retrieved Thailand Privilege sales page repeatedly emphasizes the absence of separate Issa service fees without explaining the mandatory deposit, forfeiture conditions, or refund-processing deductions.[^13]

Although the deposit is disclosed elsewhere in the company's published materials, it represents a financial commitment that prospective customers should understand before beginning an application.

A deposit is not necessarily equivalent to a service fee. Nevertheless, when forfeited, it becomes a financial cost to the customer.

The available evidence does not establish that Issa Compass improperly retained any particular customer's deposit or failed to disclose these conditions during checkout.

**The discrepancy concerns the completeness of the company's promotional disclosures, particularly where apparently fee-free assistance involves a payment that customers may subsequently lose.**

## Incorrect Work-Permit Eligibility and Foreign Employment Penalties

Issa Compass's published guide to obtaining a Thai work visa contains material inaccuracies concerning employment eligibility and penalties for unauthorized employment.[^15]

### Incorrect Exclusion of LTR Visa Holders

The guide repeatedly claims that only holders of the Highly-Skilled Professional category of the Long-Term Resident (LTR) visa can obtain Thai work permits.

However, Thailand's Board of Investment explicitly identifies the following eligibility arrangements:[^16]

| LTR category | Eligible to apply for a work permit |
| --- | --- |
| Wealthy Global Citizen | Yes |
| Wealthy Pensioner | Yes |
| Highly-Skilled Professional | Yes |
| Dependent | Yes |
| Work-from-Thailand Professional | No |

Eligibility remains subject to the relevant employment requirements and continued compliance with the conditions of the applicant's LTR category.

Issa Compass therefore incorrectly excludes three categories of LTR visa holders from work-permit eligibility.

This error resembles the misleading employment-rights comparisons separately documented in the investigation of [ltr.in.th](ltr.in.th.md).

### Incorrect Penalties for Unauthorized Employment

The same guide states that working without a valid work permit carries a maximum fine of 100,000 baht.[^15]

However, official Thai government guidance distinguishes the penalties applicable to foreign workers from those applicable to their employers.[^17]

| Offender | Applicable fine |
| --- | --- |
| Foreign worker without required authorization | 5,000–50,000 baht |
| Employer unlawfully employing a foreign worker | 10,000–100,000 baht per worker |

Foreign workers may also face deportation, while employers committing repeated violations face additional penalties.

The guide incorrectly attributes the employer's ordinary maximum financial penalty to the foreign worker.

### Commercial Significance

These inaccuracies appear within a publication promoting Issa Compass's paid visa and work-permit assistance.

The company simultaneously advertises specialist immigration expertise and automated document verification against government requirements.

Incorrectly excluding otherwise eligible visa categories could influence customers' choice of immigration services, while overstating financial penalties could unnecessarily increase anxiety about employment compliance.

The available evidence does not establish deliberate misrepresentation or financial losses suffered by individual customers.

**Nevertheless, the company's published professional guidance contains specific errors that can be verified against readily accessible government documentation.**

## Contradictory 90-Day Reporting and Re-Entry Permit Guidance

Issa Compass's dedicated 90-day reporting guide, originally published April 8, 2026, and updated November 14, 2026, contains several misleading statements concerning Thailand's immigration reporting requirements.[^18]

### Incorrect Reporting Deadline After International Travel

The article initially states that the reporting obligation applies regardless of whether foreigners have departed and re-entered Thailand during the relevant period.

It subsequently acknowledges that international travel resets the reporting deadline, but introduces an unsupported exception suggesting that travelers holding re-entry permits may retain their previous reporting deadlines.

The Royal Thai Embassy in Moscow explicitly confirms that the reporting period restarts upon arrival following international travel.[^19]

Issa Compass's separate November 4, 2026 visa-run guide correctly explains this requirement without introducing an exception for re-entry permit holders.[^20]

### Incorrect Generalization About Re-Entry Permits

The dedicated reporting guide also presents re-entry permits as mandatory for long-stay visa holders traveling temporarily outside Thailand.

However, visas with valid multiple-entry privileges, including the Destination Thailand Visa, generally permit additional entries without purchasing separate re-entry permits.[^21]

Issa Compass's own visa comparison guide correctly acknowledges this distinction.[^22]

### Incorrect Reporting Requirements for LTR Visa Holders

The reporting guide identifies quarterly address reporting as a key legal requirement for Long-Term Resident visa holders.

However, Thailand's Board of Investment expressly confirms that LTR visa holders submit an annual TM95 report instead of quarterly TM47 reports.[^23]

The company's separate visa comparison guide correctly identifies the annual reporting requirement.

### Commercial Significance

These contradictions appear in an article promoting Issa Compass's immigration compliance tools, deadline tracking, and professional assistance.

Incorrect reporting deadlines could generate unnecessary appointments or purchases of reporting assistance, while inaccurate re-entry permit guidance could result in avoidable government charges.

The available evidence does not establish that Issa Compass's automated reminder system reproduces these errors or that individual customers incurred unnecessary expenses.

Nevertheless, its dedicated professional guidance contradicts both official government instructions and information published elsewhere on its own website.

## Incorrect TM30 Accommodation Reporting Deadline

Issa Compass's guide to residential rental contracts and housing rights expressly denies the existence of a 24-hour deadline for TM30 accommodation reporting.[^24]

The article states:

> there is no specific 24-hour deadline.

However, Section 38 of Thailand's Immigration Act B.E. 2522 (1979) requires the responsible accommodation provider to notify immigration authorities within 24 hours of a foreign national taking up residence, where the reporting obligation applies.[^25]

Thailand's official government information portal explicitly confirms this statutory deadline.

### Contradictory Guidance Across Multiple Publications

Issa Compass's immigration forms glossary, marked as checked on November 13, 2026, correctly identifies the 24-hour reporting requirement.[^26]

However, its document preparation guide, updated October 17, 2026, describes TM30 submission as occurring on or after the entry date without specifying the statutory deadline.[^27]

Its newly published November 2026 business visa extension guide repeats this incomplete instruction.[^28]

The company therefore maintains several incompatible or incomplete explanations of the same immigration obligation.

### Commercial Significance

The housing guide encourages foreign tenants to explain TM30 requirements to prospective landlords, despite incorrectly describing the applicable reporting deadline.

This could result in accommodation providers relying on inaccurate professional guidance when fulfilling their statutory obligations.

The available evidence does not establish that any landlord incurred a penalty because of Issa Compass's advice.

Nevertheless, the company's categorical denial of the 24-hour deadline directly contradicts published government guidance and its own immigration glossary.

## Contradictory Permanent Residency Guidance

In an article updated October 18, 2026, Issa Compass immigration consultant Monica Thet Htar describes the LTR visa as transforming Thailand from a temporary base into "a permanent residency."[^29]

The same article advertises Issa Compass's 35,000-baht LTR endorsement assistance fee.

However, in a separate article updated October 20, 2026, immigration consultant Kat Hewett expressly acknowledges that the LTR visa does not grant permanent resident status under Thai immigration law.[^30]

### Official Immigration Requirements

Thailand's Board of Investment confirms that LTR holders initially receive five years of authorized stay and must reconfirm their eligibility to obtain the remaining five years.[^31]

The Immigration Bureau's permanent residence application guidelines establish separate eligibility requirements, including a qualifying history of annual non-immigrant visa extensions for at least three consecutive years under the ordinary quota-based application procedure.[^32]

Issa Compass's own permanent residency guide correctly acknowledges these requirements.[^33]

### Commercial Significance

Although the digital nomad article may use permanent residency colloquially to describe long-term stability, the terminology is misleading in the context of professional immigration guidance.

Customers pursuing indefinite residence should understand the distinction between renewable immigration permission and legally recognized permanent resident status before purchasing expensive application assistance.

The available evidence does not establish that customers were promised formal permanent residency through individual consultations.

## Contradictory Marriage Visa Financial Requirements

Issa Compass publishes conflicting explanations of the financial requirements applicable to marriage-based immigration extensions.

### Incorrect Bank Deposit Maintenance Period

In her marriage visa cost guide, updated November 14, 2026, immigration consultant Kat Hewett identifies a three-month bank deposit maintenance requirement.[^34]

A separate guide by immigration consultant Ana Liangsupree, updated October 18, 2026, distinguishes between a two-month requirement for initial annual extensions and three months for subsequent renewals.[^35]

However, the Immigration Bureau's published extension criteria specify a two-month maintenance period for the qualifying 400,000-baht deposit, without establishing a longer period for subsequent annual renewals.[^36][^37]

Liangsupree additionally states that applicants must maintain the entire 400,000-baht balance throughout the year. This additional restriction is not established by the reviewed government criteria.

### Contradictory Foreign Income Eligibility

Hewett's November guide expressly excludes overseas earnings from the 40,000-baht monthly income alternative, restricting eligibility to individuals working legally in Thailand.

Liangsupree's October guide, however, expressly identifies foreign income supported by embassy certification as an eligible alternative.

The Immigration Bureau's published criteria establish an average monthly income threshold without restricting qualifying income exclusively to Thai employment.

Individual applicants may encounter different documentary requirements depending on their nationality and immigration office.

Nevertheless, Issa Compass's categorical exclusion of overseas income contradicts its own published guidance.

### Commercial Significance

Liangsupree's article advertises annual extension and renewal assistance costing 10,000 baht, excluding government fees.

Prospective customers relying on these articles could unnecessarily restrict access to their savings or incorrectly conclude that their overseas income makes them ineligible.

The available evidence does not establish that individual customers were rejected by Issa Compass on these grounds.

## Contradictory Retirement Visa Financial Requirements

Issa Compass publishes inconsistent explanations of the financial conditions governing retirement-based extensions of stay.

### Incorrect Deposit Maintenance Period

Immigration consultant Kat Hewett's retirement visa comparison guide, updated October 17, 2026, states that applicants must maintain 800,000 baht in their Thai bank accounts for three months before each annual renewal.[^38]

However, Uttaradit Immigration's official published criteria specify a two-month period before application, followed by three months after approval and a minimum balance of 400,000 baht thereafter.[^39]

Issa Compass's separate retirement cost guide contradicts itself by identifying both two-month and three-month pre-renewal requirements within consecutive paragraphs.[^40]

### Overstating Combined Income and Savings Requirements

Hewett's retirement comparison guide and her guide for American applicants identify a combination of 400,000 baht in savings and 40,000 baht in monthly income.[^38][^41]

This combination amounts to 880,000 baht over a year.

However, the Immigration Bureau's published criteria establish a combined annual income and bank deposit threshold of 800,000 baht, subject to applicable deposit-maintenance conditions.[^39]

The official criteria do not prescribe Hewett's particular combination as the exclusive qualifying arrangement.

A more recent guide attributed to immigration consultant Nic Bunpamee, updated November 13, 2026, correctly identifies the combined 800,000-baht threshold.[^42]

### Commercial Significance

Prospective retirement applicants relying on the company's inconsistent guidance could unnecessarily restrict access to their savings or incorrectly assess their financial eligibility.

The available evidence does not establish that individual immigration offices accept every possible combination of savings and income, or that customers suffered financial losses because of these articles.

Nevertheless, the company's published guidance should distinguish national eligibility criteria from local administrative practices.

## Incorrect LTR Dependent Application Procedures

In her guide to LTR dependent visas, updated November 14, 2026, Issa Compass immigration consultant Kat Hewett instructs families to obtain primary applicant approval before submitting dependent applications.[^43]

The article's FAQ explicitly denies that dependents can apply before the primary applicant is approved.

However, the Board of Investment's official application instructions establish a different procedure:[^44]

- The primary applicant initiates an application and obtains a document number.
- Each dependent creates a separate account and submits an application.
- The primary applicant approves the linking request through their account.

This procedure permits linked applications before the government completes its qualification assessment.

The article therefore conflates application submission with final visa eligibility and issuance.

### Commercial Significance

The same article promotes Issa Compass's real-time verification system as capable of checking dependent applications against current embassy requirements.

However, its instructions concerning application sequencing contradict the government agency responsible for administering LTR qualification endorsements.

Families following the company's guidance could unnecessarily delay dependent applications while awaiting the primary applicant's approval.

The available evidence does not establish that Issa Compass actually delays dependent applications or that customers have experienced adverse immigration outcomes as a result.

## DTV Partner Packages and Unsubstantiated Pre-Approval Claims

Issa Compass operates a commercial network of Muay Thai gyms and Thai cooking schools selling bundled Destination Thailand Visa application packages.

Its published sales page lists 13 packages, with individual course fees ranging from US$725 to US$2,172 or more, alongside an additional US$299 visa-service fee.[^45]

In an article originally published on April 15, 2026, immigration consultant Kat Hewett describes these partner memberships as pre-approved qualifying activities.[^46]

The article further claims that documentation supplied by its partner institutions has been validated through thousands of previous applications.

However, neither publication identifies the government authority responsible for granting the claimed pre-approval or provides corresponding approval records.

### Institutional Licensing and Government Approval

Official guidance published by the Royal Thai Embassy in Bucharest, updated November 15, 2026, identifies supporting documentation relevant to activity-based DTV applications:[^47]

- Muay Thai institutions: documentation issued by the Sports Authority of Thailand or Ministry of Tourism and Sports.
- Culinary institutions: relevant school licences, business licences, or corporate registration documents.

The Royal Thai Embassy in London separately identifies institutional registration, authorization to operate courses, and a minimum activity duration of six months in its November 24, 2026 guidance.[^48]

**A commercially selected training provider is not necessarily a government-approved DTV provider, and previous successful applications do not establish blanket approval of future applications.**

Issa Compass's general disclaimer correctly acknowledges that government authorities retain responsibility for visa decisions. Nevertheless, its specific institutional pre-approval claims are not accompanied by documentary evidence establishing their scope.

### Inconsistent Course Refund Protection

The company's published package listings also distinguish between courses displaying an Issa Guarantee badge and those without one.[^45]

Examples of packages displayed without that badge include:

| Partner institution | Course fee |
| --- | ---: |
| Phuket King | US$725 |
| Bangkok Thai Cooking Academy (9 months) | US$760 |
| Dang Muay Thai Gym | US$901 |
| Bangkok Thai Cooking Academy (12 months) | US$1,065 |

Each package additionally carries a US$299 Full Service fee.

Section 7.3.1 of Issa Compass's Terms of Service establishes that partner course fees qualify for reimbursement only when the purchased package or payment confirmation expressly includes that protection.[^49]

Section 7.3.4 separately subjects course refunds following voluntary withdrawal to the relevant provider's cancellation policy.

Consequently, purchasing an all-inclusive DTV package does not automatically establish that its entire commercial cost is covered by the advertised money-back guarantee.

### Commercial Accountability

The course fee represents a substantial portion of the customer's expenditure and can considerably exceed the immigration-service fee itself.

Issa Compass should identify the documentary basis for its institutional pre-approval claims and prominently distinguish refundable course packages from those governed exclusively by individual training providers' cancellation policies.

## Misleading Financial Requirements for Retirement Visa Dependents

In a family immigration guide updated November 14, 2026, Issa Compass immigration consultant Nic Bunpamee claims that each dependent of a Non-Immigrant O retirement visa holder must demonstrate an additional 800,000 baht in savings.[^50]

According to this interpretation, a retired foreign national relocating with a dependent spouse and child would require 2.4 million baht if relying on the bank-deposit method.

### Conflicting Official Immigration Requirements

Thailand's Immigration Bureau establishes separate criteria for retirement extensions and extensions granted to family members of foreign nationals temporarily residing in Thailand.

Clause 2.20 expressly includes family members of foreigners granted retirement extensions under Clause 2.22.[^51][^52]

The published dependent-extension criteria concern qualifying immigration status, evidence of family relationships, marital status, and applicable age restrictions.

They do not establish an additional 800,000-baht deposit requirement for each dependent.

### Initial Visa Applications Versus Extensions of Stay

Issa Compass also fails to adequately distinguish between initial visa applications submitted overseas and subsequent extensions obtained within Thailand.

The Royal Thai Embassy in Kuala Lumpur expressly states that its retirement visa does not qualify accompanying family members for a Non-O dependent visa.[^53]

This restriction concerns the embassy's visa issuance procedures rather than the separate dependent-extension provisions administered by Thailand's Immigration Bureau.

### Commercial Significance

Issa Compass promotes paid family immigration assistance alongside its published eligibility guidance.

Its explanation substantially exaggerates the financial requirements applicable to the ordinary retirement dependent-extension route while overlooking important differences between consular visa issuance and domestic immigration procedures.

**Prospective customers could incorrectly conclude that relocating with their family requires hundreds of thousands of baht in additional savings for each dependent.**

## Contradictory Foreign-Income Taxation and Remittance Guidance

In a tax residency guide published on July 17, 2026, Issa Compass immigration consultant Kat Hewett incorrectly describes Thailand's foreign-income taxation rules as applying regardless of when the income was earned.[^54]

The article specifically states:

> Income earned in 2023 (or any prior year) and remitted in 2026 is still assessable in 2026 under current guidance.

This assertion directly contradicts the Thai Revenue Department's published guidance.

### Official Revenue Department Exemptions

The Revenue Department's publication *How Do Foreigners Living in Thailand Pay Tax?* explains two important circumstances in which subsequently remitted foreign income is not subject to Thai taxation:[^55]

- Foreign-sourced income earned before January 1, 2024.
- Foreign-sourced income earned during a year in which the individual was not a Thai tax resident.

The department distinguishes the taxpayer's residency during the year income was earned from the subsequent year in which that income is transferred to Thailand.

Issa Compass's July article fails to adequately distinguish these circumstances.

**The incorrect article directly cites the Revenue Department document that contradicts its own conclusions.**

### Contradictory Guidance From Another Issa Compass Consultant

On November 4, 2026, Issa Compass published another tax residency guide authored by immigration consultant Ana Liangsupree and updated on November 13.[^56]

This second publication correctly explains both exemptions.

However, it also directs readers to Hewett's earlier article for a more detailed explanation of the 180-day residency rule.

The company therefore simultaneously publishes contradictory explanations of the same taxation requirements and links readers between them.

### Commercial Financial Services Referrals

The newer article promotes Max Foresight, an Issa Compass commercial partner providing wealth-management services to expatriates.

It also encourages readers to purchase immigration assistance through Issa Compass.

Although the article acknowledges that Issa Compass does not provide professional tax or investment advice, the company's publications make substantive representations concerning taxation that could influence customers' financial and relocation decisions.

### Commercial Significance

The incorrect taxation guidance could cause foreign residents to unnecessarily delay transferring savings into Thailand, misunderstand their tax liabilities, or make inappropriate financial arrangements.

Both versions of the guidance remained publicly accessible when examined on November 26, 2026.

**Issa Compass's contradictory publications demonstrate deficiencies in the accuracy and consistency of its financial information, despite its marketing of professionally reviewed immigration assistance.**

## Prohibiting Customer Review of Prepared Immigration Applications

Issa Compass's Terms of Service, last updated November 24, 2026, expressly prohibit customers using its assisted-submission services from inspecting or approving application materials prepared on their behalf before submission to immigration authorities.[^8]

Section 6.8(a) states that customers cannot:

> view, review, comment on or approve the application forms, cover letters, declarations or other materials

This restriction extends beyond the protection of proprietary internal assessment methods and includes documents submitted to government authorities on behalf of individual applicants.

### Contradictory Consumer Advice

In a separate educational article concerning incorrect e-visa submissions, Issa Compass advises applicants to inspect generated application documents, verify their personal information and identify errors before final submission.[^57]

The article emphasizes that inaccurate submissions can result in rejection, additional applications and the loss of non-refundable government fees.

However, the company's contractual restrictions prevent its assisted-submission customers from independently performing these same checks on materials prepared by Issa Compass.

### Refund Restrictions and Customer Responsibility

Section 6.8(e) expressly establishes that customers' inability to inspect or approve submission materials does not constitute grounds for a refund.

Section 6.6 separately places responsibility on customers for the accuracy and completeness of information and documents they provide.

Although these provisions address different responsibilities, their combined effect raises legitimate concerns about applicants' ability to identify errors introduced during application preparation.

### Commercial Accountability

**Issa Compass advises applicants to verify immigration documents before submission while contractually denying its assisted-submission customers that same opportunity.**

The company should distinguish confidential internal working materials from government-facing applications and provide customers with a meaningful opportunity to verify declarations submitted in their names.

The contractual restriction does not apply to self-submission plans and expressly preserves applicable statutory data protection rights.

The available evidence does not establish that Issa Compass has submitted inaccurate or unauthorized declarations on behalf of particular customers.

## Inconsistent Data Retention and Storage Assurances

On July 1, 2026, Issa Compass published an educational article examining the privacy practices of commercial immigration services, subsequently updated on September 30, 2026.[^58]

The article repeatedly promises automatic deletion of uploaded customer documents once two conditions have been satisfied:

- The customer's visa has been issued.
- The customer has left Thailand.

However, the company's Privacy Policy, effective August 23, 2026, establishes broader retention arrangements.[^59]

### Unclear Automatic Deletion Conditions

Section 6 of the Privacy Policy permits personal-data retention for service delivery, payments, refunds, guarantee administration, taxation, disputes and other legal obligations.

It does not expressly establish the automatic deletion trigger advertised in the educational article.

The article also fails to explain what happens to uploaded documents belonging to customers whose visa applications are rejected, withdrawn or never submitted.

In these circumstances, the visa-issuance condition necessary to trigger automatic deletion may never be satisfied.

### Conflicting Data Storage Representations

Issa Compass's security page states:

> Your data is stored exclusively on Google Cloud Platform's Singapore data center

However, its Privacy Policy describes Singapore as the primary storage location rather than an exclusive one and acknowledges that certain service providers process information internationally.[^59][^60]

The policy also confirms that its Thai operating company maintains physical customer files.

These arrangements are not necessarily incompatible with secure digital hosting, but the security page does not clearly explain the narrower scope of its exclusive-storage assurance.

### Commercial Accountability

**Issa Compass advises prospective immigration customers to scrutinize competing providers' privacy and retention practices while publishing its own unreconciled data-deletion and storage assurances.**

The company should clarify retention periods for unsuccessful applications, identify exceptions to automatic document deletion and distinguish its primary digital infrastructure from other physical and international processing arrangements.

The available evidence does not establish that Issa Compass has improperly retained customer documents, transferred information unlawfully or experienced a data breach.

## References

[^1]: `https://www.issacompass.com/`
[^2]: https://builtwith.com/issacompass.com
[^3]: https://w3techs.com/sites/info/issacompass.com
[^4]: `https://tvc.co.th/`
[^5]: `https://agents.co.th/`
[^6]: `https://90day.in.th/`
[^7]: `https://tdac.agents.co.th/`

[^8]: `https://www.issacompass.com/terms` — Terms of Service, previously recorded November 13, 2026; updated November 24, 2026 and accessed that day, particularly Sections 7.3–7.3.7.

[^9]: `https://www.issacompass.com/insights/dtv-visa-thailand` — *Thailand DTV Visa 2026: Requirements, Documents and How to Apply*, updated August 18, 2026.
[^10]: `https://www.issacompass.com/insights/do-you-need-a-dtv-visa-agent-how-to-choose-one` — Updated October 18, 2026.
[^11]: `https://www.issacompass.com/insights/how-issa-compass-prepares-your-thai-visa-application-before-it-ever-reaches-the-` — Updated September 30, 2026.
[^12]: `https://www.issacompass.com/insights/document-pre-checks-approval-guarantees-and-expert-support-what-to-demand-from-a` — *Document Pre-Checks, Money-Back Guarantees, and Expert Support: What to Demand From Any Thailand Visa Platform Before You Apply*, published April 8, 2026, updated November 14, 2026; accessed November 24, 2026.

[^13]: `https://www.issacompass.com/visas/thailand-privilege-visa` — Thailand Privilege sales page, displaying a September 2026 verification date; retrieved November 25, 2026.

[^14]: `https://www.issacompass.com/insights/thailand-elite-visa-2026-cost-tiers-and-is-thailand-privilege-worth-it` — Thailand Privilege guide, updated October 18, 2026.

[^15]: `https://www.issacompass.com/insights/what-are-the-requirements-for-getting-a-work-visa-in-thailand` — Issa Compass work-visa requirements guide, retrieved November 25, 2026.

[^16]: https://ltr.boi.go.th/page/faq.html — Thailand Board of Investment, official LTR work-permit eligibility guidance.

[^17]: https://thailand.go.th/visit-thailand-detail/007_016 — Thai government guidance concerning penalties for unauthorized foreign employment, January 15, 2023.

[^18]: `https://www.issacompass.com/insights/understanding-the-90-day-reporting-rule-in-thailand`

[^19]: https://moscow.thaiembassy.org/en/publicservice/89981-notification-of-staying-in-the-kingdom-over-90-days-(online)

[^20]: `https://www.issacompass.com/insights/do-visa-runs-still-work-in-thailand-2026`

[^21]: https://london.thaiembassy.org/en/page/after-e-visa-approval

[^22]: `https://www.issacompass.com/insights/what-each-thai-visa-lets-you-do`

[^23]: https://ltr.boi.go.th/page/faq.html

[^24]: `https://www.issacompass.com/insights/thailand-long-term-rental-contracts-lease-agreements-and-housing-rights-for-expa`

[^25]: https://thailand.go.th/issue-focus-detail/001_01_060?hl=en — Official government guidance concerning Section 38 of the Immigration Act.

[^26]: `https://www.issacompass.com/insights/thai-immigration-forms-and-terms-glossary`

[^27]: `https://www.issacompass.com/insights/building-a-thai-visa-document-folder-system-what-to-keep-scan-and-carry-to-every`

[^28]: `https://www.issacompass.com/insights/non-b-thai-visa-diy-turning-your-90-day-entry-into-a-one-year-extension`

[^29]: `https://www.issacompass.com/insights/ltr-visa-digital-nomad` — Monica Thet Htar, updated October 18, 2026.

[^30]: `https://www.issacompass.com/insights/ltr-vs-dtv-visa-thailand-which-is-better-for-working-professionals` — Kat Hewett, updated October 20, 2026.

[^31]: https://ltr.boi.go.th/page/faq.html — Official LTR stay-permit conditions.

[^32]: https://chiangsaen.immigration.go.th/wp-content/uploads/2025/03/2.2คำแนะนำอังกฤษ-2567.pdf — Immigration Bureau permanent residence application guidelines, Section 1.1.

[^33]: `https://www.issacompass.com/insights/how-to-apply-for-permanent-residency-in-thailand` — Issa Compass permanent residency guide.

[^34]: `https://www.issacompass.com/insights/thailand-marriage-visa-cost-guide-financial-requirements-government-fees-and-wha` — Kat Hewett, updated November 14, 2026.

[^35]: `https://www.issacompass.com/insights/thai-marriage-visa-requirements-2026` — Ana Liangsupree, updated October 18, 2026.

[^36]: https://www.thailand.go.th/issue-focus-detail/001_01_124-2 — Official government guidance concerning extensions for foreign family members of Thai nationals.

[^37]: https://phitsanulok.immigration.go.th/คู่มือการให้บริการประชาชน/ — Immigration Bureau public handbook, Section 18.

[^38]: `https://www.issacompass.com/insights/best-retirement-visas-for-thailand-which-option-is-right-for-you` — Kat Hewett, updated October 17, 2026.

[^39]: https://uttaradit.immigration.go.th/การขออยู่ต่อ-2/ — Official retirement extension criteria, Section 22.

[^40]: `https://www.issacompass.com/insights/non-immigrant-o-visa-for-retirees-full-cost-breakdown-including-bank-requirement`

[^41]: `https://www.issacompass.com/insights/americans-moving-to-thailand` — Kat Hewett, updated November 4, 2026.

[^42]: `https://www.issacompass.com/insights/retiring-in-thailand-visas-healthcare-and-costs` — Nic Bunpamee, updated November 13, 2026.

[^43]: `https://www.issacompass.com/insights/ltr-visa-dependents-bringing-your-spouse-and-children-to-thailand` — Kat Hewett, updated November 14, 2026.

[^44]: https://ltr.boi.go.th/ — Official BOI application process, particularly the instructions for linking dependent applications.

[^45]: `https://www.issacompass.com/thailand-visas` — Commercial DTV partner package listings, pricing, and guarantee badges, examined November 26, 2026.

[^46]: `https://www.issacompass.com/insights/the-dtv-partner-package-explained-how-issa-compass-bundles-your-visa-with-muay-t` — Kat Hewett, published April 15, 2026, updated October 12, 2026.

[^47]: https://bucharest.thaiembassy.org/en/page/destination-thailand-visa-dtv — Official DTV requirements, updated November 15, 2026.

[^48]: https://london.thaiembassy.org/en/page/dtv-for-soft-power-activities — Official DTV soft-power activity requirements, updated November 24, 2026.

[^49]: `https://www.issacompass.com/terms` — Terms of Service, Sections 7.3.1 and 7.3.4, concerning partner course refunds.

[^50]: `https://www.issacompass.com/insights/can-a-spouse-or-dependent-join-you-in-thailand-visa-eligibility-rules-for-famili` — Nic Bunpamee, published April 29, 2026, updated November 14, 2026.

[^51]: https://lamphun.immigration.go.th/คู่มือการให้บริการประชาชน/ — Immigration Bureau public handbook, Section 20.

[^52]: https://phitsanulok.immigration.go.th/คู่มือการให้บริการประชาชน/ — Official immigration extension criteria, Sections 20 and 22.

[^53]: https://kualalumpur.thaiembassy.org/en/publicservice/non-immigrant-visa-o-for-retirement — Royal Thai Embassy, Kuala Lumpur, updated July 17, 2026.

[^54]: `https://www.issacompass.com/insights/thailand-tax-residency-explained-the-180-day-rule-and-how-foreign-income-is-actu` — Kat Hewett, published July 17, 2026.

[^55]: https://www.rd.go.th/fileadmin/user_upload/lorkhor/newspr/2024/FOREIGNERS_PAY_TAX2024.pdf — Thai Revenue Department, *How Do Foreigners Living in Thailand Pay Tax?*, particularly pages 2–4.

[^56]: `https://www.issacompass.com/insights/thailand-tax-residency-and-money-for-new-arrivals` — Ana Liangsupree, published November 4, 2026, updated November 13, 2026.

[^57]: https://www.issacompass.com/insights/what-happens-if-you-submit-the-wrong-file-format-on-a-thailand-e-visa-portal — Issa Compass consumer guidance concerning application verification and submission errors, reviewed November 27, 2026.

[^58]: https://www.issacompass.com/insights/what-happens-to-your-personal-data-after-you-submit-it-to-a-thailand-visa-servic — Kat Hewett, published July 1, 2026, updated September 30, 2026.

[^59]: https://www.issacompass.com/privacy — Privacy Policy, effective August 23, 2026, particularly Sections 1, 5 and 6.

[^60]: https://www.issacompass.com/security — Commercial security and data-storage assurances.

All three sources were examined on November 27, 2026.
