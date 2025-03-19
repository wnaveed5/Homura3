# Hydrogen template: Skeleton

Hydrogen is Shopify's stack for headless commerce. Hydrogen is designed to dovetail with [Remix](https://remix.run/), Shopify's full stack web framework. This template contains a **minimal setup** of components, queries and tooling to get started with Hydrogen.

[Check out Hydrogen docs](https://shopify.dev/custom-storefronts/hydrogen)
[Get familiar with Remix](https://remix.run/docs/en/v1)

## What's included

- Remix
- Hydrogen
- Oxygen
- Vite
- Shopify CLI
- ESLint
- Prettier
- GraphQL generator
- TypeScript and JavaScript flavors
- Minimal setup of components and routes

## Getting started

**Requirements:**

- Node.js version 18.0.0 or higher

```bash
npm create @shopify/hydrogen@latest
```

## Building for production

```bash
npm run build
```

## Local development

```bash
npm run dev
```

## Setup for using Customer Account API (`/account` section)

Follow step 1 and 2 of <https://shopify.dev/docs/custom-storefronts/building-with-the-customer-account-api/hydrogen#step-1-set-up-a-public-domain-for-local-development>

# Homura

This is a Shopify site with a design inspired by Homer.com.

## Design Features

- Minimalist black header with large "homura®" logo
- Clean navigation with Menu, Search, and Cart options
- Full-screen video banner on homepage (desktop and mobile versions)
- Responsive design adapting to different screen sizes

## Video Files

To complete the setup, add your video files to the `public/videos` directory:
- `desktop-banner.mp4` - for desktop displays
- `mobile-banner.mp4` - for mobile displays

## Development

This project uses Hydrogen, Shopify's React-based framework.

```bash
# Install dependencies
npm install

# Start development server
npm run dev
```

## Customization

- Header: Modify `app/components/Header.jsx` 
- Homepage: Modify `app/routes/_index.jsx`
- Styling: Modify `app/styles/app.css`
