# Butterfly — Digital Products Storefront

A single-file landing page that sells digital products. No build step. No dependencies. Deploy to GitHub Pages in two minutes.

## What's in it

- **Hero** with one headline, one CTA, and trust signals (instant download, no subscription, 30-day guarantee)
- **Product grid** — three cards, each with a benefit-first pitch, crossed-out price, and buy button
- **Before/after** transformation block
- **Social proof** section (placeholders ready to swap for real testimonials)
- **FAQ** — six questions that kill the objections buyers actually have
- **Final CTA** and footer

## How to customize

1. Open `index.html` and find the `products` array in the `<script>` tag at the bottom.
2. Edit each object's `name`, `benefit`, `description`, `price`, `oldPrice`, `link`, and `badge`.
3. Replace `https://YOUR-PAYMENT-LINK-HERE` with your real Gumroad, Lemon Squeezy, or Stripe Payment Link URL.
4. Swap the placeholder testimonials with real ones as you collect them.
5. Change the footer email from `hello@example.com` to yours.

## How to deploy (GitHub Pages)

1. Push this repo to GitHub.
2. Go to Settings → Pages → Source: Deploy from branch `main`, folder `/ (root)`.
3. Your storefront is live at `https://YOUR-USERNAME.github.io/butterfly`.

## How to connect payments

- **Gumroad**: Create a product, copy the share link, paste it as the `link` value.
- **Lemon Squeezy**: Create a product, copy the checkout URL.
- **Stripe Payment Links**: Create a payment link in the Stripe dashboard, copy the URL.

No backend needed. The page is static HTML/CSS/JS — it just points at your payment provider.

## Design rules baked in

- Dark theme, high contrast, mobile-first
- System fonts only (fast load, no external requests)
- One page, one job: get the visitor to click a buy button
- Pricing psychology: crossed-out prices, a "POPULAR" badge, a guarantee line

## The honest part

A page doesn't print money. A page with traffic, a clear offer, and a reason to buy does. This storefront handles the offer and the reason. Your job is getting people to the page.
