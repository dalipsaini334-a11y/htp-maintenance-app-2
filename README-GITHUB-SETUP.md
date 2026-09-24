# HTP MMS Maintenance App — GitHub Pages Ready

## Upload
Upload the **contents of this folder** to the root of your GitHub repository:

- `index.html` — complete fixed HTP MMS app
- `manifest.json` — PWA configuration
- `service-worker.js` — PWA/offline shell
- `.nojekyll`
- `icons/icon-192.png`
- `icons/icon-512.png`

## GitHub Pages
1. Open the repository.
2. Go to **Settings → Pages**.
3. Source: **Deploy from a branch**.
4. Branch: **main** and folder **/(root)**.
5. Save.
6. Open **Visit site** after GitHub finishes publishing.

## Important
The Google Apps Script backend is NOT included in this frontend package. Keep the deployed Apps Script Web App URL configured in `index.html`.

For Android/PWA installation, open the **published GitHub Pages HTTPS URL** in Chrome. Do not open the GitHub `blob/main/index.html` URL.
