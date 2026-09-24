# HTP MMS Maintenance App — GitHub Pages Ready (v2)

## Files (sab ek hi folder me — `icons/` folder ab nahi hai)
Ye **saari** files repo ke root me upload karo (phone se bhi ek saath select karke upload ho jayengi):

- `index.html` — poori app
- `manifest.json` — PWA/install settings
- `service-worker.js` — offline + latest-file update
- `icon-192.png`, `icon-512.png`, `icon-maskable-512.png` — app icons
- `.nojekyll` — optional (hidden file hai, na dikhe to chhod sakte ho)

Purane repo me `icons/` folder ho to use delete kar sakte ho (ab zaroori nahi).

## GitHub Pages
1. Repository → **Settings → Pages**
2. Source: **Deploy from a branch** → Branch: **main**, folder **/(root)** → Save
3. 1–2 minute baad **Visit site** wala `https://…github.io/…` link Chrome me kholo.
   (`github.com/.../blob/main/index.html` wala link mat kholo — us se install nahi hota.)

## Phone me install
Chrome me app ka https link kholo → app ke andar **📲 Install App** dabao (ya Chrome ⋮ menu → **Install app**).
Agar install na ho, **📲 Install App** dabane par app khud batayega ki kaunsi file repo me missing hai.

## Google Sheet
Backend (Apps Script) is package me nahi hai — alag file **Google-Sheet-Backend-Setup.md** me code + steps hain.
Naya `/exec` URL app me **⚙️ URL** (Admin role) se daalo — `index.html` edit karne ki zaroorat nahi.
