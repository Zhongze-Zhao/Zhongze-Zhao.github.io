# Zhongze Zhao — Academic Portfolio

A responsive, English-language academic portfolio built with plain HTML, CSS, and JavaScript. No build tools, dependencies, or external assets are required.

## Live site URL

After publishing: **https://Zhongze-Zhao.github.io/**

## Publish to GitHub Pages

1. Log in to GitHub as `zzz84402816-lab`.
2. Create a **public** repository named **`Zhongze-Zhao.github.io`** (exact spelling). Do not initialize it with a README if you plan to push this folder using the commands below.
3. In a terminal, navigate to this extracted folder and run:

   ```bash
   git init
   git add .
   git commit -m "Launch academic portfolio"
   git branch -M main
   git remote add origin https://github.com/zzz84402816-lab/zzz84402816-lab.github.io.git
   git push -u origin main
   ```

   You will need Git installed and GitHub authentication configured. Alternatively, use GitHub's **Add file → Upload files** feature to upload the **contents** of this folder (including `index.html` at the repository root).
4. In your repository, open **Settings → Pages**. Under **Build and deployment**, select **Deploy from a branch**, choose `main` and `/(root)`, then save.
5. Open **https://Zhongze-Zhao.github.io/** after the deployment completes. It may take several minutes.

## Preview locally

Open `index.html` in a browser. All styles, scripts, and illustrations are local, so no server is required for a basic preview. For a local development server, run `python -m http.server 8000` in this folder and visit `http://localhost:8000`.

## Customize before sharing

- Replace all `[bracketed placeholders]` in `index.html` and `assets/CV-placeholder.html`.
- **Education:** provide accurate start/end dates and prior institution.
- **Research Experience:** add only verified roles, supervisors, projects, and outcomes.
- **Projects:** the two example cards are illustrative placeholders, not claims of completed work. Replace descriptions and add genuine repository/paper links.
- **Publications:** add citations only when published or available as preprints.
- **Contact:** replace email and optional Google Scholar / LinkedIn placeholders. Do not publish private contact information you do not want public.
- **CV:** save your actual PDF as `assets/Zhongze_Zhao_CV.pdf`, then replace BOTH instances of `assets/CV-placeholder.html` in `index.html` with `assets/Zhongze_Zhao_CV.pdf` and change the CV button text if desired.
- **Profile photo:** not included by default; add an image if desired.
- The phrase “Open to research collaborations” is generic website copy; remove if it does not reflect your current preferences.

## File structure

```
index.html
README.md
.nojekyll
assets/
  style.css
  main.js
  favicon.svg
  CV-placeholder.html
```

## Notes

- Designed for mobile and desktop; mobile navigation is keyboard-accessible.
- Uses no third-party analytics, fonts, or external JavaScript.
- GitHub Pages hosts static websites; this project does not require a backend.
