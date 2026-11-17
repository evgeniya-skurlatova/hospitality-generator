# Hospitality Landing Page Generator

AI-powered landing page brief generator for boutique hotels, villas & resorts.

## What it does

Fill in a short form about your property and get a complete landing page brief in under 10 minutes:

- **Page structure** — 7–9 sections with layout hints
- **Copywriting** — headlines, body copy, and CTAs for each section
- **SEO block** — title, meta description, H1, keywords, schema type
- **Image recommendations** — specific photo direction for each section

## Live demo

[hospitality-generator.vercel.app](https://hospitality-generator.vercel.app/)

## Setup

1. Clone or download this repository
2. Open `index.html` in any browser — no build step required
3. Enter your [OpenAI API key](https://platform.openai.com/api-keys) in the form
4. Fill in your property details and click **Generate**

The API key stays in your browser only and is never stored or shared.

## Pricing tiers

| Plan | Price | Generations |
|---|---|---|
| Free | $0 | 3 total |
| Starter | $19/mo | 30/month |
| Pro | $49/mo | Unlimited + PDF export |
| Agency | $99/mo | Unlimited + white-label |

Payments via [Lemon Squeezy](https://lemonsqueezy.com).

## Tech stack

- Vanilla HTML / CSS / JavaScript — zero dependencies
- OpenAI API (GPT-4o-mini)
- localStorage for usage tracking and license key activation
- Deployed on Vercel

## Deployment

Push `index.html` to any static host. Vercel, Netlify, and GitHub Pages all work out of the box.

## License

MIT
