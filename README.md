# Meticulous Tech Website

Official company website for **Meticulous Tech**.

## Approved brand direction

- **Tagline:** Build Meticulously, Launch Smartly
- **Short description:** Meticulous Tech builds AI-powered software, websites, and digital solutions for modern businesses and users.
- **Primary CTA:** Contact Us

## Version 1 scope

This repository contains the initial static company website for Meticulous Tech with:

- Homepage
- Products / initiatives section
- Services section
- Contact section
- "Coming Soon" presentation for early-stage products

## Deployment target

- **Hosting:** Cloudflare Pages
- **Initial domain:** `www.meticulous-tech.com`

## Local preview

Because this is a static site, you can preview it by opening `index.html` directly in a browser.

For a local server:

```bash
python -m http.server 8000
```

Then open `http://localhost:8000`.

## Repository workflow

- `main` should be protected
- No direct pushes to `main`
- Use pull requests for all changes
- Production merges happen only after CEO approval

## File structure

- `index.html` – main homepage
- `styles.css` – site styling
- `scripts/site.js` – mobile menu + small interactions
- `docs/` – process, deployment, content, and approval documentation

## Logo note

Add the final company logo asset to `assets/` and update the header/footer image references if needed.

## Recommended first commits

1. `docs: add repository governance and deployment documentation`
2. `feat: add initial static homepage for Meticulous Tech`
3. `chore: prepare repository for Cloudflare Pages deployment`
