KEYLIGHT PWA

Package contents:
- index.html: Keylight application
- manifest.webmanifest: install metadata and icon declarations
- sw.js: service worker for app-shell caching and same-origin static assets
- icons/icon-192.png: 192px app icon
- icons/icon-512.png: 512px app icon
- icons/apple-touch-icon.png: iOS Home Screen icon

PUBLISHING
Upload the contents of this folder to the root of a GitHub Pages site or another HTTPS static host. Open the HTTPS URL in a supported browser and choose Install/Add to Home Screen.

OFFLINE NOTES
The app shell is cached after the first successful load. Salamander piano samples are fetched from Tone.js and cached by the app when first downloaded; they are not bundled in this ZIP. Web MIDI availability depends on browser/device support.
