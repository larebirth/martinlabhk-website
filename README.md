# Martin Lab HK — Landing Page V0.1

Official personal-brand landing page for **martinlabhk.com**. Hong Kong Traditional Chinese, professional instructor and AI / IT Solution Consultant positioning.

## Design

Six sections within one page: Hero, About, Services, Portfolio, Process and Contact. Navy/purple technology theme. Real portrait and real contact details are still pending; placeholder is intentionally visible rather than inventing personal information. Portfolio statuses explicitly distinguish demos, in-progress work and planning. Licensing Knowledge Advisor is identified as a non-official demo.

## Hosting

This repository was created through the **Cloudflare Workers Astro starter** and is connected to the existing Worker `martinlabhk-website`. Do NOT create another Pages project. The build and deployment should run through Workers Builds using existing Astro 5 package-lock:

- Production branch: `main`
- Build command: `npm run build`
- Deploy command: `npx wrangler deploy`
- Asset binding: `ASSETS`
- Cloudflare Worker configuration: `wrangler.json`
- Cloudflare custom domain: `martinlabhk.com`
- workers.dev: enabled for fallback testing

## Local checks

```bash
npm ci
npm run build
npm run preview
```

## Pre-launch / next iteration

- Replace the silhouette with Martin's own approved headshot.
- Add verified contact details and genuine booking links.
- Confirm that the public portfolio descriptions match permissions and project status.
- Test production deployment URL, SSL, domain, responsive layout, and links.

Existing VPS apps and subdomain DNS records must not be altered when updating this landing page.
