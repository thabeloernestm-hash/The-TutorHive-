# 🐝 The Tutorhive • STEM & Math Lit Learning Portal

> **CAPS FET Phase (Grade 10–12)** interactive educational web app covering Mathematics, Physical Sciences, and Mathematical Literacy. Built with offline study capability, step-by-step solvers, downloadable revision packs, and a timed exam simulation engine with South African CAPS achievement rating scales.

---

## 🚀 Instant Deployment to GitHub Pages (2 Minutes)

This repository is ready to deploy directly on **GitHub Pages** for free HTTPS hosting.

### Method A: Web Browser Upload (No Git Installation Needed)
1. Go to [github.com](https://github.com) and click **New Repository**.
2. Name your repository (e.g., `the-tutorhive` or `tutorhive`).
3. Set the repository to **Public** and click **Create repository**.
4. In your new repository page, click **Add file** -> **Upload files**.
5. Drag and drop all the files from this folder:
   - `index.html` (The complete application)
   - `manifest.json` (PWA mobile configuration)
   - `sw.js` (Offline service worker)
   - `icon-192.png` & `icon-512.png` (App launcher icons)
6. Click **Commit changes**.
7. Go to **Settings** (tab at the top) -> **Pages** (on the left menu).
8. Under **Branch**, select `main` (or `master`) and folder `/(root)`, then click **Save**.
9. Wait 60 seconds. Your live app URL will be:
   `https://<your-github-username>.github.io/<your-repository-name>/`

### Method B: Git Command Line
```bash
git init
git add .
git commit -m "Deploy The Tutorhive CAPS Learning Portal"
git branch -M main
git remote add origin https://github.com/<your-username>/<your-repo-name>.git
git push -u origin main
```
Then enable GitHub Pages under **Settings -> Pages**.

---

## 📱 Installing as an App (PWA)

Once hosted on GitHub Pages:
- **On Android**: Open the link in Google Chrome, tap the `...` menu, and select **Add to Home screen** or **Install app**.
- **On iPhone / iPad**: Open in Safari, tap the **Share** button, and select **Add to Home Screen**.
- **On PC / Mac**: Click the **Install** icon in Chrome/Edge address bar.

---

## 🔒 Secret Back-End Administrator Hive
- For privacy, the visible "Switch to Educator Mode" button is removed.
- **Hidden Gesture**: Tap or click the golden 🐝 bee logo in the top-left corner **5 times in rapid succession** (or long-press for 2.5 seconds on mobile).
- **Security PIN**: `216045`
- In Back-End mode, educators can edit concepts, add custom formulas, upload study materials, and export/import curriculum backups.

---

## 📦 Next Step: Publishing to Google Play Store & iOS App Store
Once your GitHub Pages link is live (e.g. `https://username.github.io/tutorhive`):
1. Visit **[PWABuilder.com](https://www.pwabuilder.com/)**.
2. Paste your live GitHub Pages URL and click **Start**.
3. PWABuilder tests your PWA manifest, service worker, and icons (already pre-configured 100%).
4. Click **Package for Stores** -> **Android** to download an `.aab` / `.apk` ready for Google Play Console.
5. Click **iOS** to generate the Xcode wrapper project for Apple App Store.
