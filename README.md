# IronLog — Personal iPhone Gym Tracker

## Files
- `index.html`: the app
- `manifest.json`: installable web-app metadata
- `sw.js`: offline cache
- `icon-192.png`, `icon-512.png`: app icons

## Quick preview
Open `index.html` in a modern desktop browser. For the installable/offline PWA features, serve these files over HTTPS (or localhost).

## Install on iPhone
1. Upload all files preserving the folder structure to an HTTPS static host (for example, a GitHub Pages site or Netlify).
2. Open the published HTTPS URL in Safari on your iPhone.
3. Tap Share, then Add to Home Screen. If offered, enable Open as Web App, then tap Add.
4. Launch IronLog from the Home Screen. Open it once while online so the service worker can cache the app; after that the shell is available offline.

## Data persistence and limitations
Workout data is stored in localStorage in the browser on that device. It is not synced to iCloud or other devices. Clearing Safari website data can delete it. Use More → Data & settings → Export regularly to download a JSON backup. Restore using Import.
This is a starter personal tracker, not a medically validated training plan. Use safe form and suitable loads.
