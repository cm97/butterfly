# Butterfly — Claude Code Instructions

You are working on the Butterfly project (cm97/butterfly). The goal: turn this repo into a **revenue-worthy digital products storefront** that makes the owner's digital products worth buying.

## Context

- The owner (cm97) sells digital products: Notion templates, ebooks, mini-SaaS tools. Solo, no employees, no capital.
- The current `index.html` is a joke page (a candle that "prints" fake money). It is NOT the product. Do not expand the joke.
- The real product is a **landing page + storefront** for the digital products, built so visitors have a reason to buy.

## What to build

Replace/upgrade `index.html` into a single-file, self-contained landing page (no build step, no dependencies, works on GitHub Pages) with ALL of the following:

### 1. Hero section
- One clear headline: what the buyer gets and why it matters NOW.
- One subheadline: the specific pain it solves.
- One primary CTA button (e.g. "Get it now" / "Buy").
- Trust signals: "Instant download", "No subscription", "Built by a solo creator".

### 2. Product grid
- Cards for each digital product. Each card: name, one-line benefit, price, and a CTA.
- Use placeholder product data the owner can edit (name, description, price, download link).
- Make it easy to add/remove products by editing one array in the `<script>`.

### 3. Social proof section
- Testimonials (placeholder, clearly marked as examples the owner should replace with real ones).
- A "results" or "before/after" block showing the transformation the product delivers.

### 4. FAQ section
- 5+ questions buyers actually ask: refunds, file formats, how delivery works, whether it needs a subscription, support.
- Answers should reduce friction and build trust.

### 5. Pricing psychology
- Show an "original" crossed-out price next to the real price on at least one product.
- One recommended/popular badge on a middle-tier option.
- A guarantee line (e.g. "30-day money-back guarantee").

### 6. Footer
- Contact email, copyright, and a one-line honest disclaimer.

## Design rules

- Dark theme, high contrast, readable on mobile.
- Fast: no external fonts beyond system stacks, no images required (use CSS/emoji/SVG).
- Accessible: buttons have labels, contrast is sufficient.
- One page, one job: get the visitor to click a buy/download button.

## What NOT to do

- Do not add the candle/money-printer joke to the storefront.
- Do not add analytics, tracking pixels, or third-party scripts.
- Do not invent real testimonials or fake customer names — use clearly labeled placeholders.
- Do not add a backend, database, or payment processing. Keep it static HTML/CSS/JS. Payment links (Gumroad, Lemon Squeezy, Stripe Payment Links) should be placeholder URLs the owner fills in.

## Success criteria

- `index.html` opens in any browser and looks like a professional digital products storefront.
- All placeholder content is in ONE editable data structure in the script.
- The page answers "why should I buy this?" within 5 seconds of landing.
- README.md is updated with: how to customize products, how to deploy to GitHub Pages, and how to connect a real payment link.
