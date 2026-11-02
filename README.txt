# Liedermappe – PWA

Upload all files and folders in this package to the root of the GitHub repository, replacing `index.html`.

Files:
- `index.html`: current Liedermappe interface
- `manifest.webmanifest`: installable-app metadata
- `sw.js`: caches the app shell; Supabase API calls remain network-only
- `icons/`: app icons

After upload, wait for GitHub Pages to finish deploying.

Install:
- Android (Chrome): open the GitHub Pages URL, browser menu ⋮ → "Install app" or "Add to Home screen".
- iPhone (Safari): open the URL, Share → "Add to Home Screen".

The app shell can open offline after first successful load, but searching requires an internet connection.
