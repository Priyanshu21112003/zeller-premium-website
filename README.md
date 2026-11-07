# ZELLER — Celebrate You

Premium editorial website prototype. Static build: deploy the repository root as the site root.

## Preview locally
Run `python3 -m http.server 8000` from the repository root, then open http://localhost:8000.

## Assets
All brand images, ZELLER wordmark and animated GIF fallbacks are stored in `assets/`. Keep the `assets/` folder beside `index.html`; do not deploy the HTML file on its own.

HD MP4 chandelier footage streams from Pexels and needs internet access. When it cannot play, local animated GIF fallbacks remain available. Product names/specifications and enquiry/newsletter interactions are prototype content, not production catalogue/CRM integrations.

## Deploy
Use GitHub Pages or Vercel with the repository root (`.`) as the static output directory.