# Weebly

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
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

Weebly (a Square company) is a website and e-commerce builder providing REST APIs for managing sites, pages, products, orders, customers, blog posts, and custom form submissions. The platform serves over 50 million websites worldwide.

## Developer Resources

- **Developer Center**: https://www.weebly.com/developer/
- **API Documentation**: https://dev.weebly.com/
- **GitHub Organization**: https://github.com/weebly
- **Pricing**: https://www.weebly.com/pricing
- **Status Page**: https://weebly.statuspage.io
- **Blog**: https://www.weebly.com/blog

## API Overview

The Weebly REST API uses OAuth 2.0 authentication and JSON data exchange. The base URL for Cloud API calls is `https://api.weeblycloud.com`. Key API resource groups include:

- **Sites** - Create and manage Weebly sites
- **Pages** - Manage individual pages within a site
- **Blog** - Manage blog posts and comments
- **Products** - Create and manage store product catalogs
- **Orders** - Access order details, billing transactions, and shipments
- **Customers** - Manage customer profiles
- **Coupons** - Create and manage discount codes
- **Categories** - Organize store products
- **Forms** - Access form submissions

**Rate Limit**: 5,000 API calls per hour per access token.

## Note on Developer Program

Since February 2020, Weebly has paused new developer account registrations and app submissions following its acquisition by Square. Existing developer integrations continue to be supported.

## Profiles

- [apis.yml](apis.yml) - APIs.json 0.19 provider profile
- [plans/weebly-plans-pricing.yml](plans/weebly-plans-pricing.yml) - Subscription plan details
- [rate-limits/weebly-rate-limits.yml](rate-limits/weebly-rate-limits.yml) - API rate limit specifications
- [finops/weebly-finops.yml](finops/weebly-finops.yml) - Financial operations guidance
