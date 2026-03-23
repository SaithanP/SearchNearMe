# 📍 NearBy RADAR

> Find places around you — restaurants, cafés, pharmacies, hospitals and more — powered by OpenStreetMap.

![NearBy RADAR](https://img.shields.io/badge/PWA-ready-3dd6f5?style=flat-square) ![License](https://img.shields.io/badge/license-MIT-green?style=flat-square) ![Deploy](https://img.shields.io/badge/deploy-Netlify-00C7B7?style=flat-square)

---

## ✨ Features

- 🗺️ Real-time map with your current location (Leaflet + OpenStreetMap)
- 🔍 Search 15 place types: restaurants, cafés, bars, hospitals, ATMs, and more
- 📏 Adjustable search radius — meters, km, or miles
- 🧭 One-tap navigation to Google Maps
- 📱 PWA — installable on iOS & Android
- 🌙 Dark mode UI

## 🚀 Deploy to Netlify

1. Fork or clone this repo
2. Go to [netlify.com](https://netlify.com) → **Add new site** → **Import from GitHub**
3. Select this repo — no build settings needed
4. Click **Deploy** ✅

Or drag the folder directly into Netlify's manual deploy page.

## 📁 File Structure

```
nearby-radar/
├── index.html      # Main app (single-file)
├── manifest.json   # PWA manifest
├── sw.js           # Service worker (offline support)
└── README.md
```

> **Note:** PWA icons (`icon-192.png`, `icon-512.png`) are referenced in `manifest.json`.  
> Add your own or remove the `icons` field to skip them.

## 🛠️ Tech Stack

- [Leaflet.js](https://leafletjs.com/) — interactive maps
- [OpenStreetMap](https://www.openstreetmap.org/) — free map tiles
- [Overpass API](https://overpass-api.de/) — place search
- Vanilla HTML / CSS / JS — no framework, no build step

## 📜 License

MIT — free to use and modify.
