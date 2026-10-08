# Butterfly — Revenue-Ready Digital Products Storefront

A single-file landing page engineered to convert visitors into buyers. No build step. No dependencies. Deploy to GitHub Pages in two minutes.

## What's in it

- **Sticky nav** with logo and CTA
- **Hero** — outcome-first headline, pain-point subheadline, primary CTA, trust-signal row
- **Product grid** — benefit-first cards with crossed-out prices, a POPULAR badge, and buy buttons
- **Before/after** transformation block (the emotional core)
- **Social proof** — three testimonial slots (placeholders, clearly marked)
- **FAQ** — six objection-killing answers using native `<details>` elements
- **Final CTA** — reframes price against the value of the visitor's time
- **Footer** — copyright, contact, legal links, honest disclaimer

## How to customize

1. Open `index.html` and find the `products` array in the `<script>` tag at the bottom.
2. Edit each object's fields: `name`, `benefit`, `description`, `price`, `oldPrice`, `link`, `badge`.
3. Replace `https://YOUR-PAYMENT-LINK-HERE` with your real payment URL (Gumroad, Lemon Squeezy, or Stripe Payment Link).
4. Swap placeholder testimonials with real ones as you collect them.
5. Update the footer email.

## How to deploy (GitHub Pages)

1. This repo is already on GitHub.
2. Settings → Pages → Source: branch `main`, folder `/ (root)`.
3. Live at `https://cm97.github.io/butterfly`.

## How to connect payments

- **Gumroad**: create a product → copy the share link → paste as `link`.
- **Lemon Squeezy**: create a product → copy the checkout URL → paste as `link`.
- **Stripe Payment Links**: dashboard → Payment Links → create → copy URL → paste as `link`.

No backend. The page is static; it points at your payment provider.

## The honest math

A page doesn't print money. Traffic + a clear offer + a reason to buy does. This storefront is the offer and the reason. Getting visitors to the page is the next job — SEO, content, or paid ads — and that's where the real leverage is.

## For Claude Code

See `CLAUDE.md` in this repo. It contains the full build spec: section order, copy rules, design rules, conversion patterns, and a success checklist. Paste it as your starting instruction and it will rebuild or refine this page to spec.
