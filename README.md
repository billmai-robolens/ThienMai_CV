# Portfolio site

Static site with no build step. Upload this whole folder as-is to any static host (GitHub Pages, Netlify, Vercel, Cloudflare Pages).

- `index.html`: home page
- Project pages, chained by their "Next" links: `warman.html` → `so101.html` → `husky.html` → `fire-rescue.html` → `pixel-camera.html` → back to Warman
- `styles.css`: all styles (colours, fonts, layout); follows the visitor's light/dark setting
- `images/`: project photos

Before going live:
- Add `resume.pdf` to this folder (the Résumé nav link points to it).
- In `index.html`, replace the `href="#"` on the LinkedIn and GitHub links.

Fonts load from Google Fonts, so the pages need an internet connection to look right.
