# Powerz On static site — v1.1

Production-ready, no-framework one-page site for Powerz On.

Version 1.1 removes numbered card and process motifs in favor of a more natural editorial presentation.

## Files

- `index.html` — semantic page structure and copy
- `styles.css` — responsive layout, local fonts, accessibility states, and brand styling
- `assets/fonts/` — only the three font files used by the site
- `assets/images/` — exact supplied Powerz Blue logo and supplied review-resolution ad image
- `screenshots/` — verified full-page desktop and mobile captures
- `ASSET-INVENTORY.md` — source asset inspection record

No JavaScript or runtime dependencies are used.

## Local preview

From this directory:

```powershell
python -m http.server 4173 --bind 127.0.0.1
```

Then open `http://127.0.0.1:4173/`.

## Deployment

Upload the contents of this directory to any static host while preserving the relative paths. Set `index.html` as the site entry point. The site does not require a build step, server-side runtime, database, or form endpoint.

### Deployment blocker

`trainwithpowerz.com` is registered and DNS-hosted in a Cloudflare account that is not currently accessible. Deployment and DNS changes are therefore blocked until access to that Cloudflare account is restored.

No deployment or DNS changes were made as part of this build.
