# 3120Final — GitHub Pages website (v2)

This version fixes broken images and PDF links on the deployed GitHub repository by using the actual **root-level file layout**.

## Publish the fix

Upload the **contents** of this directory directly to the root of `dboyarsk-git/3120Final` on the `main` branch. In particular, replace `index.html` and `script.js` with these updated versions. Do not create an extra `3120Final-v2` folder in the repository.

All PNG and PDF files belong at the root alongside `index.html`, exactly as they currently are in the public repository. You do not have to reupload these if they are unchanged.

The homepage is `https://dboyarsk-git.github.io/3120Final/`.

Examples of corrected links:
- `m1_field.png`
- `m1_axis.png`
- `Milestone1_Report.pdf`
- `PROJECT_HANDOUT.pdf`

After committing, allow the Pages deployment to finish and hard-reload your browser (Cmd+Shift+R).

## Site structure

- Section 1: Directions
- Section 2: Presentation (with future video section)
- Section 3: Technical reports and embedded PDF viewer

Milestones 4–5 remain clearly indicated as future work. Simulation values from Milestones 1–3 are illustrative. Do not assume the professor's official acceptance tests have passed.

## IMPORTANT

This repository is public. Confirm course permission before publishing the professor's handout or project materials.


## Version 3 — slide image layout
The slides with simulation figures now allocate an explicit flexible image row inside the 16:9 stage, and use `object-fit: contain`. This prevents images from spilling below the bottom slide bar at typical desktop and mobile sizes. Upload the contents of this folder to the repository root; `index.html` includes versioned asset URLs to refresh browser caches.


## v4 change
The original PROJECT_HANDOUT.pdf is embedded on page 1 (Directions) with an open-in-new-tab link; it has been removed from the page 3 Technical Report PDF selector. All milestone reports remain on page 3.

## Version 5 — References page

Fourth navigation page contains original project handout and Milestone 1–4 PDFs with clickable reference cards, selector and in-page preview. Milestone 5 stays a placeholder. PDFs remain in the repository root for GitHub Pages.
