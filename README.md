# Omnaad Studio website

Single-page site for Omnaad Studio, an ambience design studio for restaurants, cafés and bars in Pune. Content follows the Omnaad founders' guide.

- `public/` is everything that gets published. The home page (`index.html`) shows short highlights, Apple style, and each "Learn more" opens a detail page: `new-space-plan.html`, `reach-audit.html`, `festive-and-events.html`, `how-we-work.html`, `approach.html`. Shared styles are in `styles.css`; the header, menu, contact section and footer are repeated on every page, so change them on all six.
- Hosting: Cloudflare Workers static assets (free), set up in `wrangler.jsonc`, the same way as the Design Shala and Office Interio sites. Connect this repo in Cloudflare Workers Builds and every push to `main` deploys automatically.
- Content in [BRACKETS] is placeholder: email, phone, WhatsApp number and Instagram handle in the contact section.

## Design

Dark, Apple-like restraint: near-black #050506, text #F5F5F7, champagne gold #C9A877 as the only accent, the logo's red dot #C2262C on small markers. Inter Tight for headings, Inter for body. Logo and favicon come from the Omnaad symbol (`public/logo.svg`, `public/favicon.svg`).
