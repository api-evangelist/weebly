# Weebly

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
