# ✨ Tool Enchantment — Pastel Automation Suite

> A beautiful pastel-themed hub to access all automation tools instantly from one place.

![Pastel Automation Suite](https://img.shields.io/badge/theme-pastel%20anime-e879f9?style=for-the-badge&logo=sparkles)
![Tools](https://img.shields.io/badge/tools-10%20modules-a855f7?style=for-the-badge)
![GitHub Pages](https://img.shields.io/badge/deployed-GitHub%20Pages-7c3aed?style=for-the-badge&logo=github)

---

## 🌸 Preview

A soft lavender & peach animated landing page with floating sparkles, pastel bubbles, and interactive tool cards — each linking directly to its automation tool.

---

## 🛠️ Tools Included

| # | Tool | Description |
|---|------|-------------|
| 01 | **LS Data Formatter** | Format raw original data into LS-ready format |
| 02 | **Zoom Attendee Sorting** | Sort and organize Zoom attendee lists |
| 03 | **Refund Analysis** | Analyze chat logs and process refund data |
| 04 | **YTJ File Maker** | Analyze and build YTJ output files |
| 05 | **MAIN DATA Maker** | Split and build batch data sets |
| 06 | **Save Chat Analyzer** | Analyze and extract insights from saved chats |
| 07 | **Exotic Data Sorting** | Sort and clean EM data with precision |
| 08 | **Custom Zoom Payment** | Generate custom Zoom payment links |
| 09 | **Transcript Summarizer** | Summarize workshop transcripts automatically |
| 10 | **Certificate Generator** | Generate participant certificates in bulk |

---

## 🚀 Deploy to GitHub Pages

### Step 1 — Create a new repository

Go to [github.com/new](https://github.com/new) and create a repository named:

```
automation-hub
```

Or any name you prefer.

### Step 2 — Upload the file

Add `index.html` to the root of your repository.

```bash
git init
git add index.html
git commit -m "✨ initial: pastel automation hub"
git branch -M main
git remote add origin https://github.com/YOUR_USERNAME/automation-hub.git
git push -u origin main
```

### Step 3 — Enable GitHub Pages

1. Go to your repository on GitHub
2. Click **Settings** → **Pages**
3. Under **Source**, select `main` branch and `/ (root)`
4. Click **Save**

Your site will be live at:

```
https://YOUR_USERNAME.github.io/automation-hub/
```

---

## 🎨 Theme Details

| Property | Value |
|----------|-------|
| Color palette | Lavender · Peach · Pastel pink · Soft purple |
| Font | Nunito (Google Fonts) |
| Icons | Tabler Icons (webfont CDN) |
| Animations | Floating bubbles, sparkle twinkle, card hover lift, wand wave |
| Background | Soft `#fdf6ff` with floating hearts and sparkles |

---

## 📁 File Structure

```
automation-hub/
├── index.html      ← entire app (single file, no build needed)
└── README.md       ← this file
```

No dependencies to install. No build step. Just open `index.html` or deploy.

---

## ✏️ Adding a New Tool

Open `index.html` and find the `tools` array in the `<script>` section. Add a new entry:

```js
{
  name:   "Your Tool Name",
  desc:   "Short description",
  url:    "https://your-tool-url.com",
  icon:   "ti-icon-name",         // any Tabler icon name
  hue:    "#fde8f5",              // card background color (light pastel)
  accent: "#b832c8",              // icon & text accent color
  dot:    "#e879f9"               // bottom dot decoration color
}
```

Browse all available icons at [tabler.io/icons](https://tabler.io/icons).

---

## 📜 License

MIT — free to use, modify, and share.

---

<p align="center">
  Made with ✨ · Pastel Automation Suite · 自動化ツール
</p>
