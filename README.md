# Saeyeon Wordbook

A single-page English word book with American pronunciation, made to be added to
a phone or tablet home screen and opened like an app.

**Live:** https://k42242835-hue.github.io/YonyYony-Word-book/

- `index.html` — the whole app (no build step, no dependencies to install)
- `manifest.webmanifest` — makes the home-screen icon open without a browser bar
- `sw.js` — service worker that keeps the app opening when the connection is weak
- `icon-192.png`, `icon-512.png`, `icon-maskable-512.png`, `apple-touch-icon.png` — app icons

To add it on a phone: open the live link in Chrome (Android) or Safari (iOS), then
**Add to Home screen** from the browser menu (on iOS, the Share sheet).
