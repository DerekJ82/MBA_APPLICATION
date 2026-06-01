# TELUS MBA Video Application — Derek Johnson

This folder contains the video submission package for the TELUS MBA in Strategic Leadership (Gustavson School of Business, Cohort 7).

---

## Files

| File | Purpose |
|------|---------|
| `slides.html` | Full-screen 6-slide presentation — display this while recording on camera |
| `index.html` | GitHub Pages landing page — this is the URL you share with the committee |
| `style.css` | TELUS branding shared between both pages |
| `config.js` | Paste your YouTube URL here after recording |
| `README.md` | This file |

---

## 5-Step Submission Guide

### Step 1 — Open the slides and record your video

1. Open `slides.html` in Chrome (double-click the file, or drag it into Chrome).
2. Press **F11** to go full-screen.
3. Navigate between slides using **← →** arrow keys or clicking.
4. Start a Google Meet, enable recording, and present the slides by sharing your screen. Deliver the script to camera.
5. Aim for ~2 minutes. The script runs ~280 words.
6. End the meeting — Google Meet will save the recording to your Drive automatically.

**Slide timing guide:**
- Slide 0 — Title card (hold 5–10 seconds before you begin)
- Slide 1 (0:00–0:25) — Introduction
- Slide 2 (0:25–0:50) — Innovation & Tech Impact
- Slide 3 (0:50–1:35) — People-First Leadership (counters animate automatically)
- Slide 4 (1:35–2:00) — Closing Gaps & The Why
- Slide 5 — Outro (hold 5–10 seconds)

---

### Step 2 — Get your Google Meet recording link from Drive

Google Meet recordings save automatically to Google Drive when the meeting ends.

1. Open [drive.google.com](https://drive.google.com) and find the recording (it lands in **My Drive → Meet Recordings**).
2. Right-click the file → **Share** → **Change** → set to **"Anyone with the link"** → **Viewer**.
3. Click **Copy link**. The URL looks like:
   `https://drive.google.com/file/d/XXXXXXXXXXX/view?usp=sharing`

---

### Step 3 — Add your Drive URL to config.js

Open `config.js` in any text editor and paste your Google Drive sharing URL:

```js
window.videoConfig = {
  driveUrl: "https://drive.google.com/file/d/XXXXXXXXXXX/view?usp=sharing"
};
```

Save the file.

---

### Step 4 — Push this folder to GitHub

If you don't have a GitHub account, create one at [github.com](https://github.com) (free).

**Option A — Using GitHub Desktop (recommended, no command line):**
1. Download and install [GitHub Desktop](https://desktop.github.com/).
2. Click **File → New Repository**.
   - Name: `telus-mba-application`
   - Local path: point to the `video-slides` folder
3. Click **Publish repository** → set it to **Public**.

**Option B — Using the GitHub website:**
1. Go to [github.com/new](https://github.com/new).
2. Name the repo `telus-mba-application`, set it to **Public**, click **Create repository**.
3. Upload all files from this `video-slides` folder using the **Add file → Upload files** button.
4. Commit.

---

### Step 5 — Enable GitHub Pages and share your URL

1. In your GitHub repo, click **Settings** (top tab).
2. Scroll to **Pages** in the left sidebar.
3. Under **Source**, select:
   - Branch: **main**
   - Folder: **/ (root)**
4. Click **Save**.
5. Wait ~60 seconds, then refresh. GitHub will display your live URL:
   `https://YOUR-USERNAME.github.io/telus-mba-application/`

**This is the URL you submit to the TELUS MBA committee.**

Anyone with the URL can view the page — no GitHub account or TELUS login required.

---

## Troubleshooting

| Issue | Fix |
|-------|-----|
| Slides don't animate | Open in Chrome (not Edge/Safari/Firefox for best results) |
| Video not showing on landing page | Check that `config.js` has a valid Google Drive URL and that the file is shared as "Anyone with the link can view" |
| GitHub Pages shows 404 | Wait 2–3 minutes after enabling Pages and hard-refresh (Ctrl+Shift+R) |
| eNPS counter doesn't flip | Navigate away from slide 3 and back — it animates once per page load |

---

*Generated as part of the DJ MBA Application Marathon project.*
