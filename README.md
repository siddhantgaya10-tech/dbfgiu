# Balumafia — Premium Natural Sand Demo Store

A responsive, original Indian e-commerce storefront for **one product only**:
**Premium Natural Sand**. Every card and variant uses the supplied product image;
there are no unrelated categories or products.

## Included pack variants

| Pack | Price |
| --- | ---: |
| 1 kg | ₹99 |
| 5 kg | ₹399 |
| 10 kg | ₹699 |
| 25 kg | ₹1,499 |
| 50 kg | ₹2,499 |

The product page also includes the requested selectable bulk-quantity options:
250 kg, 800 kg, 710 kg, 300 kg, and 200 kg. The same image remains in use and
prices update automatically when one is selected.

## Features

- Balumafia original blue-and-white brand system; no copied e-commerce branding.
- One homepage with search, login demo, cart, navigation, hero, five pack cards.
- One product detail route, quantity selection, live price update, Add to Cart / Buy Now.
- Persistent LocalStorage cart supporting multiple pack/quantity lines.
- Cart item subtotal, free/paid delivery rule, and total amount.
- Complete **demo-only** checkout: delivery address, payment selection, order summary,
  order-complete confirmation. No payment integration or real charge is possible.
- Responsive desktop, tablet, and mobile layout with mobile bottom navigation.

## Run locally

```bash
npm install
npm run build
# serve ./dist with any static server
```

The project is React + TypeScript and includes `tailwind.config.js` design tokens
for a Tailwind pipeline. It also ships a lightweight compiled local stylesheet so
the supplied `dist/` demo renders offline with no CDN or external asset dependency.

## Validation

The included browser smoke check verifies five product cards/images, bulk variant
selection, cart insertion, checkout completion, and mobile navigation.
