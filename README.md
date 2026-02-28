# MUSYAK Construction Group - Frontend

Official static website frontend for MUSYAK Construction Group.

## Overview

This project is a single-page website built with:
- HTML5
- Tailwind CSS (Play CDN)
- Local image and video assets

Main file:
- `index.html`

## Local Preview

Open directly:
- Double-click `index.html`

Or run a local server (recommended):

```powershell
python -m http.server 8000
```

Then open:
- `http://localhost:8000`

## Project Structure

- `index.html` - Main website page
- `Logo.jfif` and `*.jfif` files - Project images
- `*.mp4` files - Media videos
- `Pictures/` - Additional image assets

## Deployment

### GitHub Pages

1. Push this folder to a GitHub repository.
2. In GitHub: `Settings` -> `Pages`.
3. Under Source, choose `Deploy from a branch`.
4. Select branch `main` and folder `/ (root)`.
5. Save and wait for the live URL.

### Netlify

1. Go to Netlify and choose `Add new site` -> `Import from Git`.
2. Connect your GitHub repository.
3. Build command: leave empty.
4. Publish directory: `.` (root).
5. Deploy site.

## Notes

- The contact form currently uses `mailto:` (opens the visitor's email app).
- For production contact handling, connect a backend, Netlify Forms, or Formspree.
- Tailwind is loaded by CDN for simplicity. For larger projects, a local Tailwind build is recommended.
