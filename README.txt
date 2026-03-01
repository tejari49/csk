# CSK PWA (GitHub Pages)

Upload these files to your GitHub repo (the folder that GitHub Pages serves):

- index.html
- manifest.webmanifest
- service-worker.js
- icons/

Notes:
- Paths are relative (./...) so it works under https://<user>.github.io/<repo>/
- If you change service-worker.js later, bump CACHE_NAME (e.g., csk-pwa-v2) so phones update.

Test:
- Open site in Chrome (Android)
- "Add to Home screen"
