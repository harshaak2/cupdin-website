# Cupdin Website

Marketing site and legal pages for **Cupdin**, a cafe-visit social app.

Static HTML, no build step — visual system matches the app's own design tokens
(`#FAF5EE` cream, `#2E211A` espresso, `#C1592A` terracotta, `#7C8F6B` sage,
`#D9A441` gold; Manrope + JetBrains Mono).

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

## To do before app store submission

- Swap the placeholder "Get it on Play Store / App Store" buttons for the
  official store badge assets once listing URLs exist.
- Replace placeholder stats in the landing page hero/strip sections with real
  numbers, or remove them.
- Confirm the `hello@cupdin.com` contact address is live before submitting
  store listings (both stores link to the privacy policy from the listing).
