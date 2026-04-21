# Cloudflare Pages Deployment Guide

## Recommended setup

- Repository: `meticulous-tech-website`
- Hosting: Cloudflare Pages
- Initial public hostname: `www.meticulous-tech.com`

## Deploy from GitHub

1. Push this repository to GitHub.
2. In Cloudflare, go to **Workers & Pages**.
3. Click **Create**.
4. Choose **Pages**.
5. Connect to Git.
6. Select the GitHub repository.
7. Framework preset: **None**
8. Build command: leave blank
9. Build output directory: `/`
10. Save and deploy.

## Custom domain setup

After the Pages project is live:

1. Open the project in Cloudflare Pages.
2. Go to **Custom domains**.
3. Add `www.meticulous-tech.com`.
4. If DNS is not fully on Cloudflare, create the required CNAME at the registrar/DNS provider.

Typical CNAME pattern:

- Host: `www`
- Target: `<project-name>.pages.dev`

## Future root-domain redirect

After `www` is working, add a redirect from:

- `meticulous-tech.com` → `https://www.meticulous-tech.com`

## Notes

Because this is a static site, no build tooling is required for version 1.
