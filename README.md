# Junction Church — Preaching Backgrounds

A static site with 64 preaching backgrounds for the main screen. Each one can be downloaded as a 1920×1200 PNG.

## Preview locally

Just open `index.html` in a browser. No build step.

## Deploy to GitHub Pages

1. Create a new GitHub repo (e.g. `preaching-backgrounds`).
2. Upload **all files in this folder** to the repo root (or to a `/docs` folder).
3. In the repo, go to **Settings → Pages**.
4. Source: **Deploy from a branch** · Branch: **main** · Folder: **/ (root)** (or `/docs` if you used that).
5. Save. Your site will be live at `https://<your-username>.github.io/<repo-name>/` in ~1 minute.

## Files

- `index.html` — the gallery page
- `patina.css` — all background styles (film grain, textures, blends)

## Using a background

Hover any card and click **↓ PNG**, or click a card to open it full size and hit **↓ Download PNG**. Files are named `jc-bg-01-ember.png` and so on.

## Notes on export

- PNG exports happen in-browser at 1920×1200 using `html-to-image`.
- Some browsers render SVG turbulence / blend modes slightly differently — Chrome gives the closest match to what you see on screen.
- If an export looks flat, retry — cache warmup sometimes needed on the first render.
