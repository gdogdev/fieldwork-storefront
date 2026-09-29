# Fieldwork

A fictional outdoor goods storefront, built with React, TypeScript, Vite, Tailwind CSS v4, and shadcn-style accessible Button and Dialog components using Radix UI.

## Run locally

```sh
npm install
npm run dev -- --port 5173
```

Open http://localhost:5173.

## Checks

```sh
npm run build
npx playwright test
```

Browser tests use an installed Google Chrome and expect the dev server to be running.

Includes category filters, product details, a persistent shopping bag, quantity controls, shipping calculations, a demo checkout, field notes, and a newsletter form. Checkout and newsletter are demonstrations; no payment or email service is connected. Product photos are illustrative.

Photography: Unsplash. Images are stored locally in `public/`. Fonts: DM Sans and Manrope via Google Fonts, with system fallbacks.
