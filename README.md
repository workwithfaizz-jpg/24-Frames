# 24 Frames Studio — website

Static site, no build step. Upload the whole folder.

## Option A — Netlify Drop (fastest, ~1 min)
1. Open https://app.netlify.com/drop and log in.
2. Drag this whole `24frames-site` folder onto the page.
3. Netlify gives you a live link. Site settings → change site name (e.g. 24frames-studio.netlify.app) or add your own domain.

## Option B — GitHub Pages (free)
1. github.com → New repository → name it `24frames` (Public) → Create.
2. "uploading an existing file" → drag ALL files from this folder (index.html, .mp4, .jpg) → Commit.
3. Settings → Pages → Source: Deploy from a branch → Branch: main / (root) → Save.
4. After 1–2 min the site is live at https://<your-username>.github.io/24frames/

Custom domain (e.g. 24frames.in): buy it, then add it in Netlify Domain settings or GitHub Pages → Custom domain and follow the DNS steps shown there.
