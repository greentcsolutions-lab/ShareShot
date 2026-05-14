# ShareShot 📸

**Instant screenshot sharing. No sign-up. No backend. Just drop and share.**

Live demo: [https://yourusername.github.io/screenshot-share](https://yourusername.github.io/screenshot-share)

## ✨ Features

- Drag & drop or click to upload screenshots
- Instant shareable link via ImgBB
- Clean, dark mobile-friendly design
- One single HTML file — no build step
- Works entirely in the browser
- Hosted for free on GitHub Pages

## 🚀 How to Use

1. Visit the site
2. Drop a screenshot (PNG, JPG, GIF) or click to browse
3. Wait 2–3 seconds while it uploads
4. Copy the direct link and share it anywhere

Anyone with the link can view the image. No accounts required.

## 🛠️ Deploy in 2 Minutes

1. Fork or clone this repo
2. Go to **Settings → Pages**
3. Set source to `Deploy from a branch` → `main` → `/ (root)`
4. Click **Save**
5. Your site will be live at `https://yourusername.github.io/screenshot-share` in under a minute

## 🔑 ImgBB Setup (Required)

This project uses [ImgBB](https://imgbb.com/) as a free image host.

1. Go to [ImgBB](https://imgbb.com/)
2. Sign up (or login with Google)
3. Visit [API page](https://api.imgbb.com/)
4. Copy your **API key**
5. Open `index.html` and replace the placeholder key:

```js
// Change this line:
https://api.imgbb.com/1/upload?key=YOUR_REAL_API_KEY_HERE
