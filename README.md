# Cupdin Website

Marketing site and legal pages for **Cupdin**, a cafe-visit social app.

Static HTML, no build step — visual system matches the app's own design tokens
(`CafeSocial/src/theme/tokens.ts`: cream `#FAF5EE`, ink `#2B211A`,
terracotta `#A94A22` / `#C1592A`; Fraunces + Manrope).

## Pages

| File | Purpose |
|---|---|
| `index.html` | Landing page |
| `privacy.html` | Privacy Policy |
| `terms.html` | Terms & Conditions |

## Local preview

No build tooling required — open `index.html` directly in a browser, or serve
the folder:

```bash
npx serve .
```

## Deploying

Any static host works (GitHub Pages, Netlify, Vercel, Cloudflare Pages). For
GitHub Pages: push to a repo, enable Pages on the `main` branch root, and
`index.html` will serve at the repo's Pages URL automatically.

## Before publishing

- `index.html` describes version 1.1: publish it when that version is in the stores.
- Remove `hidden` from the two Google Play badges once the Android listing is live.
- Do not add visit, cafe or rating counts to the site.
