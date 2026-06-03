# 🏠 CLASS B MONITORING — Inventory System

A dark-themed, browser-based inventory management system for roofing sheet stock. No server required — runs entirely in the browser using `localStorage`.

---

## 📁 File Structure

```
/
├── index.html        ← Main HTML (entry point)
├── css/
│   └── style.css     ← All styles
├── js/
│   └── app.js        ← All JavaScript & data
└── README.md
```

---

## 🚀 Deploy to GitHub Pages (Free Hosting)

### Step 1 — Create a GitHub Repository
1. Go to [github.com](https://github.com) and sign in
2. Click **"New"** (top left) → name it e.g. `class-b-monitoring`
3. Set it to **Public** → click **"Create repository"**

### Step 2 — Upload the Files
1. In your new repo, click **"uploading an existing file"** (or drag & drop)
2. Upload all files **keeping the folder structure**:
   - `index.html`
   - `css/style.css`
   - `js/app.js`
3. Click **"Commit changes"**

### Step 3 — Enable GitHub Pages
1. Go to your repo → **Settings** tab
2. Scroll down to **"Pages"** (left sidebar)
3. Under **Source**, select **"Deploy from a branch"**
4. Choose branch: `main` / folder: `/ (root)`
5. Click **Save**

### Step 4 — Access Your Site
After ~60 seconds your site will be live at:
```
https://<your-username>.github.io/<repo-name>/
```

---

## ✨ Features

| Tab | Description |
|-----|-------------|
| **Dashboard** | Stats overview, low stock alerts, recent transactions |
| **💜 Sale** | Record sales with stock & zero-qty filters |
| **▼ Stock Out** | Record stock-out transactions by size |
| **Inventory** | Full inventory with IN button, search & filters |
| **Log** | Full transaction history (IN / OUT / SALE) |
| **Summary** | Stock totals per item with CSV export |

### Filters available on Sale & Summary pages
- **✔ With Stock** — show only items that have stock
- **✖ Zero Qty** — show only items with no stock

---

## 💾 Data Storage

All data is saved in the browser's `localStorage` under the key `roofstock_v2`. Data persists across page refreshes on the same device and browser. It is **not** synced between devices.

---

## 📦 Item Categories

- Corrugated (0.26 / 0.30)
- Ribtype (0.28 / 0.32 / 0.52)
- Multi Rib (0.28 / 0.32 / 0.52)
- Plain 3×8 & 4×8 (0.26 / 0.30)
- Custom categories (add via **＋ Add Item**)

Sizes tracked: **8ft · 10ft · 12ft · 14ft**
