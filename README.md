# Bharat Rail: Pune–Darbhanga Express

A playable prototype of an Indian Railways game: drive train 11033 in a WAP-7 from Pune to Darbhanga and look after twelve coaches of passengers.

**Play:** https://diwagraphy.github.io/bharat-rail/

## Install on your phone
1. Open the link above in Chrome on Android.
2. Tap ⋮ → **Install app** (or **Add to Home screen**).
3. Bharat Rail opens full-screen in landscape and works offline after the first load.

## What's inside
- `index.html` — the whole game (Three.js 3D world, driving physics, crew and coach simulation, station announcements).
- `lib/` — Three.js r149 and its glTF loader (MIT licence, see `lib/THREE-LICENSE.txt`).
- `fonts/` — Barlow Condensed, Hind, Yatra One, DotGothic16 (SIL Open Font Licence).
- `sw.js`, `manifest.webmanifest`, `icons/` — offline cache and home-screen app setup. Bump `VERSION` in `sw.js` when you change files so phones pick up the update.
