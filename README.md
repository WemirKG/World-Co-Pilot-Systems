# World-Co-Pilot-Systems
# Co-Pilot System (GitHub Pages)

This repository hosts a static multi-page landing site for the Co-Pilot System.

## 1) Add the site files
Ensure these files are in the repository root:

- index.html
- how-it-works.html
- privacy.html
- educators.html
- creators.html
- business.html
- get-access.html
- thank-you.html
- support.html
- styles.css
- script.js

## 2) Enable GitHub Pages
1. Go to **Settings** in this repository
2. Click **Pages**
3. Under **Build and deployment**:
   - Source: **Deploy from a branch**
   - Branch: **main**
   - Folder: **/(root)**
4. Click **Save**

GitHub will provide your live site URL (example):
https://YOUR-USERNAME.github.io/REPO-NAME/

## 3) Update the email form redirect
Open `get-access.html` and find:

```html
<input type="hidden" name="_next" value="https://YOUR-GITHUB-PAGES-URL/thank-you.html">
