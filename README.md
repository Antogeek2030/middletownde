# Water Heater Repair Concord CA — Astro Site

Static Astro site for **waterheaterrepairconcordca.com**, optimized for Cloudflare Pages.

## Features
- Responsive, mobile-first design
- Teal + orange color theme (changed from source blue)
- OpenStreetMap embed pinpointing 2175 Commerce Ave, Concord, CA 94520
- SEO: meta tags, canonical, JSON-LD LocalBusiness schema, sitemap, robots.txt
- Fast static build for Google indexing
- Cloudflare Pages ready (static output, no adapter needed)

## Phone number
Placeholder: **(925) 555-0199** — replace in `src/pages/index.astro` (search for `9255550199` and `555-0199`).

## Deploy to Cloudflare Pages
1. Push this folder to a GitHub/GitLab repo.
2. In Cloudflare Dashboard → Workers & Pages → Create → Connect to Git.
3. Build settings:
   - **Framework preset:** Astro
   - **Build command:** `npm run build`
   - **Build output directory:** `dist`
4. Add custom domain `waterheaterrepairconcordca.com`.
5. Submit `https://waterheaterrepairconcordca.com/sitemap-index.xml` in Google Search Console.

## Local development
```bash
npm install
npm run dev
```

## Build
```bash
npm run build
```
Output is in `dist/`.

## Notes
- Site is fully static (`output: 'static'` by default) — ideal for Pages and SEO.
- `@astrojs/sitemap` generates `/sitemap-index.xml` at build time.
- `public/robots.txt` points crawlers to the sitemap.
