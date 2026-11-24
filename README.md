# Kerala Chakkala Service Society (KCS) Website

Official website repository for Kerala Chakkala Service Society, Thiruvananthapuram.

## Features
- Society activities, history, and objectives
- Community announcements and event details
- Integrated photo and video gallery
- Leadership roster and contact details
- Custom interactive 404 fallback page (`404.html`)

---

## 🚀 Deployment Instructions

### 1. Hosting on GitHub Pages
This repository is pre-configured with `.nojekyll`, root `index.html`, and `404.html`.

#### Option A: Automatic via GitHub Actions (Recommended)
1. Go to your repository on GitHub: **[TK9157/kcssociety](https://github.com/TK9157/kcssociety)**.
2. Click **Settings** → **Pages**.
3. Under **Build and deployment** → **Source**, select **GitHub Actions**.
4. Pushes to `main` will automatically trigger `.github/workflows/deploy.yml` and publish your site!

#### Option B: Deploy from Branch
1. Go to **Settings** → **Pages**.
2. Under **Build and deployment** → **Source**, select **Deploy from a branch**.
3. Under **Branch**, select `main` and folder `/ (root)`.
4. Click **Save**.

Your site will be live at:
`https://tk9157.github.io/kcssociety/`

---

### 2. Hosting on Vercel
This repository includes `vercel.json` for automated routing, clean URLs, and custom 404 handling.

1. Go to [vercel.com/new](https://vercel.com/new).
2. Connect your GitHub account and import **`TK9157/kcssociety`**.
3. Keep the default settings:
   - **Framework Preset**: Other
   - **Root Directory**: `./`
4. Click **Deploy**.

Vercel will build and assign you a production URL (e.g., `https://kcssociety.vercel.app`).
