# digitalpowder.io

Company landing page for Digital Powder — makers of **MySkiSwap** and **ConsignGear**.

It's a single static page (`index.html` + `favicon.svg`) with no build step. Open `index.html` in a browser to preview.

## Hosting (Cloudflare Pages)

1. Cloudflare dashboard → **Workers & Pages** → **Create** → **Pages** → **Connect to Git**, and pick this repo.
2. Framework preset: **None**. Build command: leave empty. Build output directory: `/`.
3. Deploy. Every push to the production branch redeploys automatically.
4. **Custom domains** → add `digitalpowder.io` (and `www.digitalpowder.io`).

## Waitlist form (Formspree)

The ConsignGear waitlist posts to Formspree. In `index.html`, replace `YOUR_FORM_ID` in the form's `action` with your Formspree form ID. Signups are emailed to you and listed in the Formspree dashboard.

## Before launch

- Set the Formspree form ID (see above).
- ~~MySkiSwap URL~~ — set to `https://app.myskiswap.com`.
- ~~Contact email~~ — set to `info@myskiswap.com`.
- Review the About section copy so it matches your story.
