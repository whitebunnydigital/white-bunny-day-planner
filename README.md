# White Bunny Morning

A calm, iOS-style morning ritual app. It walks you through the Rapid Planning Method (RPM)
across Health, Work and Life — one question at a time — then hands back a tickable plan and
a shareable card. Type or speak your answers. Three warm themes (Latte / Sage / Blush).

## This folder is a ready-to-deploy static web app (PWA)

    index.html              the whole app (self-contained, works offline)
    manifest.webmanifest    installable app metadata
    service-worker.js       offline caching
    icons/                  home-screen app icons

## Deploy

Any static host works — no build step. Pick one:

**GitHub Pages**
1. Push this folder to a repo.
2. Settings → Pages → Source: your branch, folder `/ (root)` (or `/webapp` if nested).
3. Open the published `https://…` URL.

**Netlify (fastest):** drag this folder onto https://app.netlify.com/drop

**Vercel:** `vercel deploy` in this folder, or import the repo.

> Install & offline require **HTTPS** (all three hosts give you that free).
> Opening the file directly from disk won't register the service worker.

## Add to iPhone Home Screen

Open the deployed URL in **Safari** → Share → **Add to Home Screen**.
It launches full-screen with the bunny icon, no browser chrome.
