SMART EXPENSE TRACKER — iPhone + Computer

This is an offline-first Progressive Web App (PWA).
It stores data locally in IndexedDB on each device.

IMPORTANT:
- To install on iPhone Home Screen, the app must be hosted on an HTTPS website.
- Open the HTTPS address in Safari, tap Share, then Add to Home Screen.
- Open it once while online so the app files are cached. It can then work offline.
- Each device has its own local database. Offline devices cannot sync directly.
- To transfer data, use Backup & Device Transfer: Export backup on one device, then Import backup on the other.
- Import merges expense records by unique ID; it does not delete existing records.

For testing on a computer, serve this folder through a local web server:
  python -m http.server 8000
Then open http://localhost:8000
For full PWA installation/service worker support on phones, deploy to HTTPS hosting.
