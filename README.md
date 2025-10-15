# KB/DB Training Plan — Hostable PWA

This folder contains a small installable web app (PWA) that you can host anywhere (Netlify, GitHub Pages, Vercel, Cloudflare Pages, etc).

## Files
- `index.html` — the app
- `manifest.webmanifest` — PWA metadata
- `service-worker.js` — offline caching
- `icons/` — app icons
- `200.html` — fallback page for static hosts

## Quick Deploy Options

### 1) **Netlify (no account required)**
- Go to https://app.netlify.com/drop
- Drag & drop the **entire folder** here.
- After it uploads, copy the site URL.
- Open the URL on your iPhone in Safari → Share → **Add to Home Screen**.

### 2) **GitHub Pages**
- Create a new repo → upload all files at the repo root.
- Settings → Pages → Build from **main** / **root**.
- Visit `https://<your-username>.github.io/<repo>/` on iPhone → Share → **Add to Home Screen**.

### 3) **Vercel**
- Create a new project → "Framework: Other".
- Import this folder → Deploy.
- Open the deployment URL on iPhone → Share → **Add to Home Screen**.

### 4) **Cloudflare Pages**
- Create a new project → Upload the folder → Deploy.
- Open the Pages URL on iPhone → Share → **Add to Home Screen**.

## Notes
- If you update files later, you may need to refresh the service worker:
  - On iPhone: open the app → pull to refresh twice.
- The app works fully **offline** after the first load.