# Auren Legal Site

This folder contains a free static website for Auren legal and support pages.

Live URLs expected by the iOS app:

- `https://auren.app/privacy/`
- `https://auren.app/terms/`
- `https://auren.app/support/`

## Free Cloudflare Pages Deploy

1. Create a GitHub repository named `auren-legal`.
2. Upload everything in this `AurenLegalSite` folder.
3. Go to Cloudflare Dashboard.
4. Open **Workers & Pages**.
5. Click **Create application**.
6. Choose **Pages**.
7. Connect the GitHub repository.
8. Build settings:
   - Framework preset: `None`
   - Build command: leave blank
   - Build output directory: `public`
9. Deploy.
10. Add custom domain:
    - `auren.app`
    - Cloudflare will connect it because your domain is already on Cloudflare.

## App Store Connect URLs

Use these:

- Privacy Policy URL: `https://auren.app/privacy/`
- Support URL: `https://auren.app/support/`
- Marketing URL: `https://auren.app/`

## Legal Note

These pages are practical App Store-ready starter documents, not formal legal advice. Have a lawyer review them before Auren handles significant revenue, banking integrations, or users outside your local market at scale.
