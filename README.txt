MAYMONA PWA

Included:
- index.html: your Maymona page, based on the uploaded browser.html
- bg3.png, icon.png, search-icon.png: your original assets
- manifest.webmanifest: app name, icons, and standalone display settings
- service-worker.js: caches the app shell for offline loading
- icons/: 192px and 512px PWA icon sizes made from your supplied icon

INSTALL ON ANDROID
1. Upload the contents of this folder to a web host that serves HTTPS.
   (PWA installation and service workers require HTTPS, except localhost.)
2. Open the hosted site in Chrome on Android.
3. Open Chrome menu (⋮) and choose "Install app" or "Add to Home screen".
4. Confirm. Maymona will appear in the app list with its own icon and name.

LOCAL TESTING
You can serve this folder from localhost using a local development server.
Opening index.html directly as a file will not enable service-worker/PWA installation.

SEARCH
Searches continue to use Google and require an internet connection.
The app shell and visual assets are cached for offline opening after the first successful visit.
