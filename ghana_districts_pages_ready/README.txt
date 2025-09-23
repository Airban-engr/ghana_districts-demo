# Ghana Districts – GitHub Pages Ready

This bundle ships with CTA buttons, SEO, social preview, analytics hooks, search, filter, labels, and region colors.

## 1) Put data in place
- Export GeoJSON as `ghana_districts_simplified.geojson`
- Place it in the `data/` folder.

## 2) Customize
- In `index.html` replace:
  - `__YOUR_EMAIL__` with your email
  - `__YOUR_WHATSAPP__` with your number (e.g., 233XXXXXXXXX)
  - `G-XXXXXXX` with your **GA4 ID** (optional)
  - `__PAGES_URL__` (two places) with your GitHub Pages URL

## 3) Run locally
```
python -m http.server 8080
# open http://localhost:8080
```

## 4) Deploy to GitHub Pages
- Create a repo, put `index.html` + `data/` + `preview.png` in root
- Settings → Pages → Source: main → /(root) → Save

## 5) Shareable links
Append parameters to focus a view:
`?region=Ashanti&d=Kumasi`
