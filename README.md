# ⛽ FuelLog

**Company Vehicle Fuel Bill Tracker — PWA**

A mobile-first Progressive Web App to track monthly fuel expenses, attach receipts, and export professional PDF reports.

-----

## ✨ Features

- ⃁ Saudi Riyal (SAR) currency
- Add fuel bills with date, amount, fuel type, notes & receipt photo
- Tap any bill to **edit** — change anything including attaching a forgotten receipt
- Monthly total with bill count
- **History** — all past months with totals
- **Export PDF** — professional report with signature section
- Works **offline** (PWA)
- Installs on iPhone / Android home screen like a native app
- Data saved locally on your device

-----

## 📱 Install on iPhone

1. Open the app link in **Safari**
1. Tap the **Share** button (box with arrow)
1. Tap **“Add to Home Screen”**
1. Tap **Add**

The app will appear on your home screen like a native app, full screen with no browser UI.

-----

## 🚀 Deploy on GitHub Pages

### Step 1 — Create a GitHub repository

1. Go to [github.com](https://github.com) and sign in
1. Click **New repository**
1. Name it `fuellog` (or anything you like)
1. Set it to **Public**
1. Click **Create repository**

### Step 2 — Upload files

Upload all these files to your repository:

```
fuellog/
├── index.html
├── manifest.json
├── sw.js
├── README.md
└── icons/
    ├── icon-180.png
    ├── icon-192.png
    └── icon-512.png
```

You can drag and drop them directly on GitHub.

### Step 3 — Enable GitHub Pages

1. Go to your repository **Settings**
1. Click **Pages** in the left sidebar
1. Under **Source**, select **Deploy from a branch**
1. Choose **main** branch, **/ (root)** folder
1. Click **Save**

### Step 4 — Access your app

Your app will be live at:

```
https://YOUR-USERNAME.github.io/fuellog/
```

It usually takes 1–2 minutes to go live after enabling Pages.

-----

## 📁 File Structure

|File           |Purpose                           |
|---------------|----------------------------------|
|`index.html`   |The entire app (HTML + CSS + JS)  |
|`manifest.json`|PWA metadata (name, icons, colors)|
|`sw.js`        |Service worker (offline support)  |
|`icons/`       |App icons for home screen         |

-----

## 🛠 Tech Stack

- Vanilla HTML / CSS / JavaScript
- jsPDF (PDF generation)
- localStorage (data storage)
- PWA (Service Worker + Web App Manifest)
- Hosted on GitHub Pages (free)

-----

Made with ❤️ for field teams in Saudi Arabia
