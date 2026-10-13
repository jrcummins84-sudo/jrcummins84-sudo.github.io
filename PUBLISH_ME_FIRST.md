# Publish me first

This site is functionally ready to publish. I intentionally did not guess two user-owned public values.

## 1. Add your confirmed public contact route
Open `contact.html`. Replace the public-note paragraph with your preferred LinkedIn or email button once you confirm which address you want public.

Recommended HTML:
`<a class="button fill" href="YOUR-LINKEDIN-OR-MAILTO">Contact Josh</a>`

## 2. Add the live portfolio domain
Replace every `https://YOUR-DOMAIN.example/` occurrence in `sitemap.xml` and `robots.txt` with the final domain.

## Public-release cleanup already applied
- Learner-list screenshot is not included.
- Reporting visuals use sanitized crops that remove other employee names and unnecessary editor/footer details.
- Metrics are presented as October 2026 snapshots.
- ECHO pages include a public-use caveat.
- All internal links were audited.

## Deployment
Upload this entire folder to any static host (Netlify, Cloudflare Pages, GitHub Pages, etc.). No build step is required.
