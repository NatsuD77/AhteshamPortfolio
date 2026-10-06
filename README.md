# Ahtesham Portfolio — Live

Live deployment repository for the Ahtesham Ul Haq portfolio website.

## Live site

https://natsud77.github.io/AhteshamPortfolio/

## Purpose

This repository contains the built/static files served by GitHub Pages for the **live portfolio**.

The source code is maintained separately in:

- **Source repository:** `NatsuD77/AhteshamWebPage`
- **Production source branch:** `main`

The source repository builds the Vue/Vite application and deploys the generated `dist/` output here.

## Deployment flow

```text
AhteshamWebPage (main)
        │
        │ GitHub Actions
        ▼
AhteshamPortfolio (main)
        │
        ▼
GitHub Pages
        │
        ▼
Live portfolio
```

## Important

- This is a **deployment/output repository**, not the primary development repository.
- Make website changes in `AhteshamWebPage`, then merge them into `main) after testing.
- Avoid manually editing generated site files here unless there is a specific deployment/recovery reason.
- The live site should represent the production `main` branch of the source repository.

## Backup

Production source backups are kept as branches in the source repository when needed.

## Development

For source code, component changes, content updates, and local development, use:

`NatsuD77/AhteshamWebPage`
