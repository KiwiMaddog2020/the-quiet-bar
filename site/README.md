# Website

Static site: one HTML file, no build step, no monthly cost. The only external dependency is Cormorant Garamond from Google Fonts; to self-host it later, download the woff2 files and swap the `<link>` for `@font-face` rules.

Local preview: `python3 -m http.server 8642 --directory site` then open http://localhost:8642.

## Working name

Built with **The Quiet Bar** as placeholder. To change: edit the `BRAND` const in the `<script>` at the bottom of [index.html](index.html), plus the `<title>`, meta description, and the contact email. Everything with class `brand` updates from the const.

## Deploy (pick one, both free)

**Cloudflare Pages** (recommended — also gives free DNS for the .ca domain):
1. Push this `site/` folder to a GitHub repo (or use direct upload at dash.cloudflare.com → Workers & Pages).
2. Connect the repo, set the build output directory to `site/` (no build command).
3. Add the custom domain (e.g., thequietbar.ca) in the Pages project → Custom domains.

**GitHub Pages:** repo → Settings → Pages → deploy from branch, folder `/site`. Add a `CNAME` file containing the domain.

## Payments

Each Buy button reads `data-payment-link` from its markup. Until a URL is pasted in, buttons show "Coming soon."

**Recommended: Square payment links** (free, and the same Square account runs the market card reader with unified inventory):
1. squareup.com → sign up (business account, needs bank details — the business owner should do this step, not Claude).
2. Items → create The Original / The Coconut / The Quiet Trio with prices.
3. Online Checkout → create a payment link per item (enable shipping address collection).
4. Paste each URL into the matching `data-payment-link=""` in index.html and redeploy.

Stripe Payment Links work identically (dashboard.stripe.com → Payment Links) at the same 2.9% + $0.30 if you'd rather build on Stripe.

## Before launch checklist

- [ ] Real product photos into the three `.photo` placeholders
- [ ] Final brand name + domain + email
- [ ] Payment links live and test-purchased
- [ ] Market schedule section filled in
- [ ] Footer: full business mailing address (required on cosmetic labels anyway; consistency helps trust)
- [ ] Shipping prices set inside Square/Stripe checkout (flat-rate boxes via Canada Post Small Packet work well for 1-3 bars)
