# Prism Overhead Doors — Landing Page

One-page, high-conversion site targeting homeowners within 50 miles of **Durand, MI**. Optimized for Netlify Forms, local SEO, and fast loads.

## Files
- `index.html` — Landing page with testimonials, FAQs, LocalBusiness + FAQ JSON-LD, and **Netlify form** (`name="lead"`).
- `thanks.html` — Confirmation page.
- `_redirects` — Forces www → root.
- `netlify.toml` — Security headers & caching.
- `robots.txt`, `sitemap.xml` — SEO hygiene.
- `images/prism-logo.png`, `images/og-prism-overhead-doors.jpg` — placeholders; replace with real assets.

## Deploy on Netlify (GitHub)
1. Push this folder to a GitHub repository.
2. In Netlify: **Add new site → Import from Git** → choose your repo.
3. Build settings:
   - **Build command:** *(leave blank)*
   - **Publish directory:** `/`
4. Click **Deploy site**.

## Netlify Forms
This repo uses **Netlify Forms** out of the box.
- Form name: `lead`
- Submissions: Netlify dashboard → **Forms → lead** → set email notifications.

## Custom Domain
In Netlify → **Site settings → Domain management** → add `prismoverheaddoors.com`. Follow DNS prompts. SSL via Let’s Encrypt is automatic.

## Analytics (optional)
Add your GA4 tag in `index.html` where indicated and keep the `generate_lead` event hook.
