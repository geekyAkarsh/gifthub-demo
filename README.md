# Gifthub — Corporate Gifting Demo

A standalone, client-facing static prototype for a multi-tenant corporate gifting platform.

## Demo roles

- **Superadmin** — tenant onboarding, master catalogue, cross-tenant orders, procurement, reports and settings.
- **Company HR Admin** — employee directory, credit allocation, gift assortment, company orders and reports.
- **Employee** — gift store, wallet, redemption, order history and delivery addresses.
- **Operations** — order queue, procurement, stock, shipping and delivery.

## Deploy

This repository includes a GitHub Actions workflow at `.github/workflows/deploy.yml`. Once GitHub Pages is configured to use **GitHub Actions**, every push to `main` publishes the site.

Repository: https://github.com/geekyAkarsh/gifthub-demo

## Important demo notes

This is a front-end prototype. Data and interactions are held in browser memory and reset on refresh. No authentication, backend, payment processing, email, supplier integration or real shipment is connected. All people, orders and company details are illustrative sample data.
