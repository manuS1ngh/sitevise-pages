# Sitevise — Public Website

Static HTML website hosted on GitHub Pages for App Store requirements.

## Pages

| URL | File |
|---|---|
| `https://manus1ngh.github.io/sitevise-pages/` | `index.html` |
| `https://manus1ngh.github.io/sitevise-pages/privacy/` | `privacy/index.html` |
| `https://manus1ngh.github.io/sitevise-pages/support/` | `support/index.html` |

## Deployment

1. The public repository `manuS1ngh/sitevise-pages` already exists at GitHub.
2. Run from this directory:
   ```
   git init
   git branch -M main
   git add .
   git commit -m "Initial site"
   git remote add origin https://github.com/manuS1ngh/sitevise-pages.git
   git push -u origin main
   ```
3. In the repo: **Settings → Pages → Source: Deploy from branch → main → / (root) → Save**.
4. The site is live within 60 seconds.

## Important

- This is a separate public repository containing only static website files.
- Do NOT push to the private Sitevise application repository (`manuS1ngh/sitevise`).
- Do not publish until the privacy policy is reviewed and approved.
