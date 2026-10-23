# Manchester Signal website

Static site for manchestersignal.co.uk. Published by Terradeed Ltd, trading as TerraDeed Labs.
No build step, no external scripts, fonts or trackers. Hosted on GitHub Pages from this public repo.

## Files
- `index.html`: landing page
- `privacy.html`: privacy notice (DRAFT, needs professional review)
- `styles.css`, `logo.svg`
- `CNAME`: custom domain

## Before going live (Alex approves each step)
1. Paste the Kit double opt-in form embed in place of the placeholder in `index.html`.
2. Fill the privacy notice [CHECK] items: company number, registered office, ICO fee number, Kit settings.
3. Switch contact email to hello@manchestersignal.co.uk once the alias is tested.
4. Remove both "DRAFT" banners and the `noindex` meta tag in `index.html`.
5. DNS at IONOS: follow `dns-setup.md` step 7 (Alex only).
6. Tick Enforce HTTPS in Settings, Pages once available.

Rule: the consent line in `index.html` must match `privacy.html`. Change both together.
