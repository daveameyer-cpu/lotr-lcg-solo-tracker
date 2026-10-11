# LOTR LCG Solo Tracker — installable app package

This folder contains a PWA-ready version of the tracker. It can be installed on Android and iPhone once it is hosted at an HTTPS address.

## Important
- Do not open `index.html` directly from your computer and expect installation/offline features to work. Service workers require localhost or HTTPS.
- Tracker data is stored locally in the browser/app on each device. This package does not automatically sync data between devices.
- Keep using the tracker's Export save feature to make backups.

## Quickest way to use it
1. Upload the contents of this folder to an HTTPS static host (for example, GitHub Pages or Netlify).
2. Open the published HTTPS URL on your phone.
3. Android: in Chrome, open the browser menu and choose **Install app** or **Add to Home screen**.
4. iPhone: open the URL in Safari, tap **Share**, then choose **Add to Home Screen**.

## Included files
- `index.html` — the tracker
- `manifest.webmanifest` — app name, display mode, colors and icons
- `service-worker.js` — caches the app shell for offline use after the first successful load
- PNG icons for app launchers and iOS home screen
