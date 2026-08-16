# Simple GitHub Pages Personal Website

This is a plain HTML/CSS website. No build tools are required.

## 1. Publish it with GitHub Pages

1. Create a GitHub repository. The simplest user-site name is `YOUR_USERNAME.github.io`.
2. Upload all files from this folder to the repository root.
3. Open **Settings → Pages**.
4. Under **Build and deployment**, select **Deploy from a branch**.
5. Select `main` and `/(root)`, then save.
6. Visit `https://YOUR_USERNAME.github.io`.

## 2. Change your name and text

Open each `.html` file in GitHub and click the pencil/edit button.
Search for `Your Name`, your placeholder university, email, GitHub URL, and other placeholder text.
Edit it and click **Commit changes**.

## 3. Change the profile photo

Option A — easiest:

1. Upload your photo to `assets/images/`, for example `profile.jpg`.
2. In `index.html`, find:

```html
<img class="profile-photo" src="assets/images/profile.svg" alt="Your Name">
```

3. Change it to:

```html
<img class="profile-photo" src="assets/images/profile.jpg" alt="Your Name">
```

You can use JPG, PNG, or WebP.

## 4. Add a research image

Upload the image to `assets/images/`, for example `radar.jpg`, and add this where you want it:

```html
<img src="assets/images/radar.jpg" alt="Research figure" style="max-width:100%;">
```

## 5. Update your CV

Upload your PDF as:

`assets/cv/cv.pdf`

The CV page will then link to it automatically.

## 6. Add a new page

Example: add `teaching.html`.

1. Copy `research.html` and rename the copy to `teaching.html`.
2. Change the page title and body content.
3. In the navigation section of EVERY page, add:

```html
<a href="teaching.html">Teaching</a>
```

After committing, the new page will be available at `/teaching.html`.

## 7. Remove a page

Delete the HTML file and remove its navigation link from the other pages.

## 8. Change fonts, colors, spacing, and layout

Edit:

`assets/css/style.css`

At the top, these variables control the main appearance:

```css
:root {
  --bg: #ffffff;
  --text: #1f2937;
  --muted: #6b7280;
  --line: #e5e7eb;
  --accent: #1d4ed8;
}
```

For example, change `--accent` to change the link color.

## 9. Use your own domain

In GitHub, open **Settings → Pages → Custom domain**, enter your domain, and save it. Then configure the DNS records at your domain provider according to GitHub Pages' current custom-domain documentation. Enable **Enforce HTTPS** after DNS validation succeeds.

## 10. Normal editing workflow

For small changes you do not need Git on your computer:

1. Open the repository on GitHub.
2. Click a file.
3. Click Edit (pencil icon).
4. Make the change.
5. Click Commit changes.

GitHub Pages will publish the new version automatically.
