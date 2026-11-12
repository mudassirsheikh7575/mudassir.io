# mudassir.io — Portfolio

A static, single-page portfolio. No build step and no dependencies: every file the site needs is in this folder, fonts included.

## Files

| File | What it is |
|---|---|
| `index.html` | The whole site: markup, styles and scripts in one file |
| `avatar.jpg` | Profile photo (240×240) |
| `favicon.png` | Browser tab icon (64×64) |
| `apple-touch-icon.png` | Home-screen icon and social share image (180×180) |
| `fonts/Inter-Regular.woff`, `fonts/Inter-Medium.woff` | Font for all text |
| `fonts/Inter-LICENSE.txt` | Font licence (SIL Open Font License, free for commercial use) |

## Preview locally

Double-click `index.html` to open it in a browser, or run a local server:

```
cd mudassir-portfolio
python3 -m http.server 8000
```

Then visit http://localhost:8000.

## Deploy to mudassir.io

Upload the whole folder as-is to any static host (Netlify, Vercel, Cloudflare Pages, GitHub Pages), then point the `mudassir.io` domain at it. Keep the folder structure unchanged so the `fonts/` paths keep working.

## Before going live: replace these

1. **WhatsApp**: the Quick chat button opens a chat with +971 52 637 1292 (`wa.me/971526371292`).
2. **Projects**: Recent Projects links to Tensorlake, Metricra and Black Jays. Logos are inline SVG so they switch colour with dark mode.
3. **Social share image**: `apple-touch-icon.png` is used as the link preview. For a richer preview, add a 1200×630 `og-image.jpg` and update the `og:image` line.

Contact email throughout: `hello@mudassir.io`.

## Credits

WhatsApp icon: [Font Awesome Free](https://fontawesome.com/license/free), CC BY 4.0.
