# 🎬 Reel Thumbnail Maker

A simple, browser-based tool to create eye-catching **Instagram Reel / YouTube Shorts thumbnails (1080 × 1920)** for government job updates — no Photoshop or Canva needed.

🔗 **Live site:** https://your-project-name.vercel.app

---

## ✨ Features

### Design
- **Header** with a striped background and custom colours
- **Logo card**: use an image (with crop and shift) or type the organisation name (Hindi supported)
- **Card styles**: white, yellow or transparent, with an optional border
- **Tag, pills and caption** with one-click presets (e.g. `CENTRAL GOVT JOB`, `FRESHERS CAN APPLY`)
- **Last date inserter**: pick a date and it adds `LAST DATE : 12 OCTOBER`
- **Divider line** with adjustable thickness and colour

### Headline layouts
- **Salary**: `MONTHLY SALARY` + big amount (e.g. `₹50,000`)
- **Hook / urgency**: two bold lines (e.g. `PERMANENT VACANCY` / `NO INTERVIEW`)
- **Role**: post name over two lines (e.g. `TRAINEE` / `RECRUITMENT`)
- Size slider and ALL CAPS toggle

### Photo
- Upload a photo or **grab a frame directly from a video**
- Zoom, shift and mirror (flip left/right)
- Brightness, contrast and saturation
- **Readability gradient** so text stays clear on any background

### Workflow
- **Style templates**: 5 built-in themes, plus save your own
- **Logo library**: save logos once, reuse them anytime
- **Preview overlays**: Instagram safe zones and profile grid crops (1:1 and 3:4)
- **Download PNG** in full 1080 × 1920 resolution
- Click or drag-and-drop images straight onto the preview

---

## 🚀 How to use

1. Open the live site.
2. Upload your photo (or a video and pick a frame).
3. Upload the organisation logo, or switch the logo card to **Text**.
4. Fill in the tag, headline, pills and caption — or tap the preset chips.
5. Adjust colours and apply a template if you like.
6. Click **Download PNG**.

---

## 🛠 Tech

- Plain **HTML, CSS and JavaScript** in a single `index.html` file
- Drawing with the **HTML Canvas API**
- Fonts: **Anton**, **Poppins** and **Noto Sans Devanagari** (Google Fonts)
- Hosted on **Vercel**

No installation, no build step and no backend.

---

## 💻 Run locally

1. Download or clone this repository.
2. Double-click `index.html` to open it in Chrome or Safari.

---

## 📝 Notes

- Saved templates and logos are stored in **your browser only** (localStorage). They won't show on other devices, and clearing browser data removes them.
- Some videos (especially **HEVC / H.265** from iPhones) may not load in every browser. Export them as **MP4 (H.264)** or upload a screenshot instead.
- Instagram safe zones shown in the overlay are **approximate**.
- Only use logos you have the right to use.

---

## 📄 License

Free to use for personal and educational purposes.
