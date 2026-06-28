# Train — Calisthenics Session Logger

A mobile-first PWA for logging daily training sessions. Works fully offline once installed.

## Files

- `index.html` — the app
- `manifest.json` — PWA manifest (enables install prompt)
- `sw.js` — service worker (enables offline use)
- `icon.svg` — home screen icon

## How to host on GitHub Pages (free, 3 minutes)

1. Go to **github.com** → sign in or create a free account
2. Click **New repository** → name it `train-app` → set to **Public** → click **Create repository**
3. Click **Add file → Upload files** → drag all 4 files in → click **Commit changes**
4. Go to **Settings → Pages** → under Source select **Deploy from branch → main → / (root)** → click **Save**
5. Wait ~60 seconds → your app is live at:
   `https://YOUR-USERNAME.github.io/train-app`

## Install on Android

1. Open `https://YOUR-USERNAME.github.io/train-app` in **Chrome**
2. Tap the three-dot menu → **Add to Home Screen** (or look for an install banner)
3. Tap **Install** → the app appears on your home screen
4. Open it once while online — after that it works fully offline

## Install on iPhone

1. Open the URL in **Safari** (must be Safari, not Chrome)
2. Tap the **Share** button (box with arrow) → **Add to Home Screen**
3. Tap **Add**

## Notes

- All session data is stored locally on your device
- Clearing browser data/site data will wipe history — export regularly if needed
- The service worker caches everything including Google Fonts on first load
