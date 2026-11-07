# ZELLER — Celebrate You

A premium, editorial-style static website prototype for ZELLER, built around the ZELLER brand palette and its visual identity.

## Preview locally

The site is a single self-contained HTML file. Open `index.html` in a modern browser, or run:

```bash
python3 -m http.server 8000
```

Then visit http://localhost:8000.

## Assets and media

- The ZELLER wordmark, crystal imagery and animated GIF fallback visuals are embedded directly inside `index.html`.
- There is no separate assets folder to move or upload.
- Chandelier MP4 footage is streamed from Pexels and needs an internet connection. The embedded animated GIF visuals remain visible if a video source does not load or autoplay is blocked.
- Images, logos and GIF fallbacks do not depend on relative file paths.

## Deploy

### GitHub Pages
1. Open the repository Settings.
2. Go to Pages.
3. Choose **Deploy from a branch**.
4. Select `main` and `/ (root)`, then save.

### Vercel
Import this repository and select **Other** as the framework preset. Set the output directory to `.` (repository root).

## Prototype notes

Product names, specifications and project descriptions are illustrative placeholders. Enquiry and newsletter interactions are demonstration-only and are not connected to a CRM. Replace concept content and remote footage with approved ZELLER catalogue information and licensed brand films before production.
