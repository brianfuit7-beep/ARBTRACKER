# Arb Tracker

Arbitrage betting profit tracker — mobile-optimized PWA.

## Deploy to Vercel (5 minutes)

### 1. Push to GitHub
```bash
git init
git add .
git commit -m "init arb tracker"
git remote add origin https://github.com/YOUR_USERNAME/arb-tracker.git
git push -u origin main
```

### 2. Deploy on Vercel
1. Go to [vercel.com](https://vercel.com) and sign in with GitHub
2. Click **Add New → Project**
3. Import your `arb-tracker` repo
4. Click **Deploy** — no settings needed, it just works

### 3. Add icons (optional but recommended)
Drop two PNG files in the project root:
- `icon-192.png` — 192×192px
- `icon-512.png` — 512×512px

Use any image (screenshot of the app, a logo, etc). Without them the PWA still works, just uses a default icon.

---

## Install on your phone

Once deployed to Vercel:

**iPhone (Safari):**
1. Open your Vercel URL in Safari
2. Tap the Share button → **Add to Home Screen**
3. Tap Add — it'll appear as a full-screen app

**Android (Chrome):**
1. Open your Vercel URL in Chrome
2. Tap the menu → **Add to Home screen**
3. Tap Add

---

## Data storage
Data is saved to `localStorage` in your browser — it stays on your device and persists between sessions. No account or backend needed.
