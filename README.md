# ApiQuiz.com — Single-Page Landing (Domain for Sale)

A fast, conversion-focused landing page to sell the premium domain: `ApiQuiz.com`.

- Price: $850 (Buy Now)
- Buy link: https://www.godaddy.com/en/domainsearch/find?domainToCheck=apiquiz.com
- Contact: ahmad0abdulmajid@gmail.com

## Files

- `index.html` — Single file with inline CSS/JS, SEO meta, Open Graph, Product JSON-LD, micro-interactions, and analytics hooks.
- `assets/apiquiz-banner.svg` — 1200x630 OG-friendly banner with gradient + wordmark used in hero and metadata.

## Features

- Clear, persuasive copy tailored to tech + edtech buyers
- Above-the-fold dual CTAs (Buy Now + Email Seller)
- Value props, use cases, market context, features, social proof, FAQ
- Sticky CTA bar appears on scroll
- Subtle fade-in on scroll and crisp hover states
- AA contrast, semantic HTML, keyboard/focus support
- Lightweight: no external libraries, inline critical CSS, lazy assets
- Minimal analytics: pushes CTA click events to `window.dataLayer`

## Run locally

Just open `index.html` in your browser.

Optionally serve via a simple static server for correct absolute paths.

## A/B testing (content variants)

You can switch the hero headline and primary CTA label via URL parameters:

- `?variant=a` → "Secure ApiQuiz.com Today — Premium .COM for Tech & EdTech ($850)"
- `?variant=b` → "ApiQuiz.com: Your Next Developer Learning Brand — Buy Now for $850"
- `?variant=c` → "Build on ApiQuiz.com — Short, Brandable, and Ready to Scale ($850)"

CTA label variants for all Buy buttons:

- `?cta=1` → "Buy Now — $850" (default)
- `?cta=2` → "Own ApiQuiz.com Today"
- `?cta=3` → "Secure This Domain"

You can combine them, e.g.: `index.html?variant=b&cta=3`

## Customize

- Canonical URL: update `<link rel="canonical" href="https://apiquiz.com/" />` in `<head>` after deployment if needed.
- Theme colors: tweak CSS variables at the top of `<style>`.
- Analytics: send `window.dataLayer` events to your analytics destination, or replace with your tracking solution.

## Deploy

Any static hosting works:

- GitHub Pages
- Netlify / Vercel (drop-in)
- Cloudflare Pages
- S3 + CloudFront / Azure Static Web Apps / Firebase Hosting

Ensure the `assets/` folder is deployed alongside `index.html`.

## License

This landing page content and assets are provided for the purpose of selling the domain `ApiQuiz.com`. You may modify and use them for this sale. Logos are generic/non-trademark and may be adapted.
