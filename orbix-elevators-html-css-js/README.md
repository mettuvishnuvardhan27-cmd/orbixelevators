# Orbix Elevators — HTML, CSS & JavaScript

A static, responsive multi-page frontend. No React, Next.js, Tailwind, build step, database, API, or server-side code is required.

## Run locally

Open `index.html` in a browser, or use VS Code's Live Server extension for local development.

## Pages included

- `index.html` — Home
- `about.html`
- `products.html` and `products/oe-100x.html`, `products/oe-200x.html`, `products/oe-300x.html`
- `services.html` and individual service pages in `services/`
- `projects.html` and individual concept pages in `projects/`
- `contact.html`

## Before publishing

1. Open `script.js`.
2. Find `const ORBIX_WHATSAPP_NUMBER=''` and replace the empty value with the business's confirmed WhatsApp number in international digits, without `+`, spaces, or punctuation (for India, include `91` before the number).
3. Confirm business details, contact information, legal requirements, and all model claims before publishing. The current site does not invent an address or technical specifications.
4. Product and project visuals are concept images based on the supplied brochure; do not represent them as verified completed installations.

## Deploy to Vercel

1. Upload this folder to a GitHub repository.
2. In Vercel, select **Add New → Project** and import that repository.
3. Set Framework Preset to **Other**. No build command is needed; use the project root as the root directory.
4. Deploy. All links use root-relative paths and work on the deployed domain.

The contact form prepares an enquiry and opens WhatsApp. It does not store submissions. No database is included because this is a frontend-only website.


## Updated logo-glow version
Open the extracted `orbix-elevators-html-css-js` folder itself in VS Code (File → Open Folder), then run `index.html` with Live Server. Do not open the parent folder, because Live Server must serve this folder as the project root. Image and navigation URLs are now resolved relative to this project so they also work when hosted in a subfolder. The Orbix logo is a subtle centered background watermark across every page, with soft champagne/olive glow and glass surfaces; the existing palette and fonts are preserved.
