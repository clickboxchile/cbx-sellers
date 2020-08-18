
<div align="center">
  <h1>Clickbox</h1>
  (https://static.wixstatic.com/media/3ee851_6e04bd5b6af6405497a30e93d8f812d4~mv2.png/v1/fill/w_424,h_324,al_c,q_85,usm_0.66_1.00_0.01/e-commerce2.webp)
</div>

<div align="center">
  <strong>Seller-centric e-commerce platform</strong>
</div>

## What makes Saleor special?

Clickbox Platform is based on Saleor, open source e-commerce platform that has served high-volume companies from branches like publishing and apparel since 2012. Based on Python and Django, the latest major update introduces a modular front end powered by a GraphQL API and written with React and TypeScript.

## Features

- **PWA**: End users can shop offline for better sales and shopping experiences
- **GraphQL API**: Access all data from any web or mobile client using the latest technology
- **Headless commerce**: Build mobile apps, customize storefronts and externalize processes
- **UX and UI**: Designed for a user experience that rivals even the top commercial platforms
- **Dashboard**: Administrators have total control of users, processes, and products
- **Orders**: A comprehensive system for orders, dispatch, and refunds
- **Cart**: Advanced payment and tax options, with full control over discounts and promotions
- **Payments**: Flexible API architecture allows integration of any payment method. It comes with Braintree support out of the box.
- **Geo-adaptive**: Automatic localized pricing. Over 20 local languages. Localized checkout experience by country.
- **SEO**: Packed with features that get stores to a wider audience
- **Cloud**: Optimized for deployments using Docker
- **Analytics**: Server-side Google Analytics to report e-commerce metrics without affecting privacy


## Installation

Saleor requires Python 3.8, Node.js 10.0+, PostgreSQL and OS-specific dependency tools.

[See the Saleor docs](https://docs.saleor.io/docs/developer/installation) for step-by-step installation and deployment instructions.

Note:
The `master` branch is the development version of Saleor and it may be unstable. To use the latest stable version, download it from the [Releases](https://github.com/mirumee/saleor/releases/) page or switch to a release tag.

The current stable version is 2.10 and you should use this version for all three components:

- Saleor: https://github.com/mirumee/saleor/releases/tag/2.10.2
- Dashboard: https://github.com/mirumee/saleor-dashboard/releases/tag/2.10.0
- Storefront: https://github.com/mirumee/saleor-storefront/releases/tag/2.10.3

## Documentation

Saleor documentation is available here: [docs.saleor.io](https://docs.saleor.io)

To contribute, please see the [`mirumee/saleor-docs` repository](https://github.com/mirumee/saleor-docs/).

## Saleor Platform

The easiest way to run all components of Saleor (API, storefront and dashboard) together on your local machine is to use the [saleor-platform](https://github.com/mirumee/saleor-platform) project. Go to that repository for instructions on how to use it.

[View saleor-platform](https://github.com/mirumee/saleor-platform)

## Storefront

For PWA, single-page storefront go to the [saleor-storefront](https://github.com/mirumee/saleor-storefront) repository.

[View storefront demo](https://pwa.saleor.io/)

## Dashboard

For dashboard go to the [saleor-dashboard](https://github.com/mirumee/saleor-dashboard) repository.

[View dashboard demo](https://pwa.saleor.io/dashboard/)

## Demo

Want to see Saleor in action?

[View Storefront](https://pwa.saleor.io/) | [View Dashboard (admin area)](https://pwa.saleor.io/dashboard/)

Or launch the demo on a free Heroku instance.

[![Deploy](https://www.herokucdn.com/deploy/button.svg)](https://heroku.com/deploy)

Login credentials: `admin@example.com`/`admin`

## Contributing

We love your contributions and do our best to provide you with mentorship and support. If you are looking for an issue to tackle, take a look at issues labeled [`Help Wanted`](https://github.com/mirumee/saleor/issues?q=is%3Aopen+is%3Aissue+label%3A%22help+wanted%22).

If nothing grabs your attention, check [our roadmap](https://github.com/mirumee/saleor/projects/12) or come up with your feature. Just drop us a line or [open an issue](https://github.com/mirumee/saleor/issues/new) and we’ll work out how to handle it.

Get more details in our [Contributing Guide](https://docs.saleor.io/docs/developer/community/contributing).

## Legacy views

If you're interested in using the old version of Saleor, go the [legacy-views](https://github.com/mirumee/legacy-views) repository. It contains the 2.9.0 release, which includes Django-based views and HTML templates of Storefront 1.0 and Dashboard 1.0. Note: this version of Saleor is no longer officially maintained.

## License

Disclaimer: Everything you see here is open and free to use as long as you comply with the [license](https://github.com/mirumee/saleor/blob/master/LICENSE). There are no hidden charges. We promise to do our best to fix bugs and improve the code.

Some situations do call for extra code; we can cover exotic use cases or build you a custom e-commerce appliance.
