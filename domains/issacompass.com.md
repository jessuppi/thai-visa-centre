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

## References

[^1]: `https://www.issacompass.com/`
[^2]: https://builtwith.com/issacompass.com
[^3]: https://w3techs.com/sites/info/issacompass.com
[^4]: `https://tvc.co.th/`
[^5]: `https://agents.co.th/`
[^6]: `https://90day.in.th/`
[^7]: `https://tdac.agents.co.th/`
