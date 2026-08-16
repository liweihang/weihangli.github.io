# Weihang (Leo) Li — GitHub Pages Personal Website

A simple static academic/personal website built with plain HTML + CSS. There is no framework, build step, database, or server to maintain.

## Included in this packet

- Real profile photo
- DroneSAR system photo
- Compressed DroneSAR demo video suitable for GitHub Pages
- Soil-moisture map
- SNOOPI mission image
- Research and publication pages
- Dedicated **Experience** page
- Qualcomm, Samsung, and Micron internship sections with company logos
- Current PDF CV at `assets/cv/cv.pdf`

Finance-related material is intentionally excluded.

---

## 1. Publish on GitHub Pages

1. Create a GitHub repository. The simplest personal-site name is `YOUR_USERNAME.github.io`.
2. Upload **the contents of this folder** to the repository root. `index.html` should be at the top level.
3. Open **Settings → Pages**.
4. Under **Build and deployment**, select **Deploy from a branch**.
5. Select branch `main` and folder `/(root)`, then save.
6. Visit `https://YOUR_USERNAME.github.io`.

---

## 2. Main pages

- `index.html` — homepage, featured projects, industry-experience cards, demo video, recent news
- `research.html` — DroneSAR, soil moisture, SoOp/SNOOPI, navigation/sensor fusion, current applied research
- `experience.html` — Qualcomm, Samsung Semiconductor, and Micron internships
- `publications.html` — selected papers/conference work
- `cv.html` — web CV with downloadable PDF

---

## 3. Media files

Current media is under:

- `assets/images/profile.jpg`
- `assets/images/dronesar-system.jpg`
- `assets/images/dronesar-demo-poster.jpg`
- `assets/images/soil-moisture-map.png`
- `assets/images/snoopi-mission.png`
- `assets/images/qualcomm-logo.svg`
- `assets/images/samsung-logo.webp`
- `assets/images/micron-logo.webp`
- `assets/media/DroneSAR_Demo_web.mp4`

To replace an image later, overwrite it with the same filename or change the corresponding `src="..."` path in the HTML.

---

## 4. Update internship / company experience

Edit `experience.html` for the detailed entries. The homepage contains shorter versions inside the **Industry Experience** section.

The public descriptions intentionally avoid proprietary implementation details.

---

## 5. Update the PDF CV

The current CV is already included at:

`assets/cv/cv.pdf`

To update it later, simply replace that file with a newer PDF using the same filename. The **Download PDF CV** button will continue working automatically.

---

## 6. Add/update a publication

In `publications.html`, copy an existing publication `<article>` block, paste it into the correct year, and edit the title, authors, venue, and link.

---

## 7. Change colors/layout

Open `assets/css/style.css`. The main palette is at the top under `:root`.

`--accent` controls the gold/brown highlight color.

---

## 8. Normal update workflow

For small changes you do not need Git installed locally:

1. Open the repository on GitHub.
2. Click the file you want to change.
3. Click the pencil/edit icon.
4. Make the edit.
5. Click **Commit changes**.
6. GitHub Pages will automatically republish the site.
