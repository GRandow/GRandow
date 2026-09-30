# Gabriel Randow

**Shopify developer, full stack** — six years on Shopify, four of them at a US agency shipping Shopify Plus stores and their integrations for DTC brands. I work on both sides of the platform: headless storefronts on the Storefront and Customer Account APIs, and custom apps that connect a store to the systems it depends on — Admin GraphQL API, webhooks, back-office integrations.

![Shopify](https://img.shields.io/badge/Shopify-Admin%20%26%20Storefront%20APIs-96BF48?logo=shopify&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?logo=typescript&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-5FA04E?logo=nodedotjs&logoColor=white)
![React](https://img.shields.io/badge/React-61DAFB?logo=react&logoColor=black)
![GraphQL](https://img.shields.io/badge/GraphQL-E10098?logo=graphql&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?logo=postgresql&logoColor=white)
![Prisma](https://img.shields.io/badge/Prisma-2D3748?logo=prisma&logoColor=white)
![Vite](https://img.shields.io/badge/Vite-646CFF?logo=vite&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-2088FF?logo=githubactions&logoColor=white)

## Selected projects

- **[luma-commission-bridge](https://github.com/GRandow/luma-commission-bridge)** — custom app for direct-sales brands: `orders/paid` webhooks (HMAC-verified, idempotent by webhook id, queued with retries), distributors as metaobjects, the commission written back to the order, and a sync to a commission engine with idempotency keys and a rehearsable failure mode. TypeScript · React Router · Prisma/Postgres · Polaris · unit-tested, CI on every push.
- **[luma-shopify-storefront](https://github.com/GRandow/luma-shopify-storefront)** — headless storefront on the Storefront, Cart and Customer Account APIs (OAuth 2.0 + PKCE), with referral attribution for direct sales. React 19 · TypeScript · Vite · TanStack Query · unit-tested, CI. [Live demo](https://grandow.github.io/luma-shopify-storefront/)
- **[ecommerce-product-carousel](https://github.com/GRandow/ecommerce-product-carousel)** — dependency-free product carousel for e-commerce pages, vanilla JS + Tailwind. [Live demo](https://grandow.github.io/ecommerce-product-carousel/)

<p align="center">
  <img src="commission-bridge-dashboard.png" alt="The commission bridge dashboard inside the Shopify admin: paid orders attributed to distributors, commissions calculated and synced to the engine" width="900">
</p>
<p align="center"><sub>The commission bridge inside the Shopify admin: each paid order attributed, calculated at the distributor's rate and synced to the engine.</sub></p>

Next up: a Checkout UI extension and a Shopify Function for distributor pricing, inside the commission bridge.

## Certifications

11 official Shopify certifications, including Development Fundamentals, Liquid Storefronts and Headless for Developers.

## Contact

[LinkedIn](https://www.linkedin.com/in/gabriel-randow/) · Brazil (UTC−3) · used to working with North American teams
