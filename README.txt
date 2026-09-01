TRAVEL COMPARATOR — PWA

Included:
- index.html: your existing application, PWA-enabled
- manifest.webmanifest: install metadata
- sw.js: offline cache/service worker
- icons/: iPhone/PWA icons

IPHONE INSTALLATION
1. Upload this folder to an HTTPS web host.
2. Open the HTTPS address in Safari on your iPhone.
3. Tap Share.
4. Tap Add to Home Screen.
5. Tap Add.

IMPORTANT
- Opening index.html directly with file:// is not enough for a real PWA.
- HTTPS is required for service workers/PWA behavior (localhost is an exception for development).
- Your existing localStorage data remains local to the browser/device.
