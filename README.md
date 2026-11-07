# 3120Final — GitHub Pages project site

A static, single-link site for **ECGR 3120: Magnetically Steered Cardiac Ablation**, designed with a bold monochrome editorial aesthetic.

## The three views

1. **Directions** — project summary, five milestones, original handout, and deliverables.
2. **Presentation** — keyboard-controlled slide deck and reserved YouTube video space.
3. **Technical report** — accessible research summaries, full existing Milestone 1–3 PDFs, and a PDF viewer.

The site is an early-stage showcase. Milestones 4 and 5 and the final video are NOT completed; placeholders are deliberately labeled. Current example results are illustrative, and the professor's official acceptance tests have not been run.

## Deploy to GitHub Pages

1. On GitHub create or open the repository named **3120Final**.
2. Upload the **contents** of this folder (not the outer folder), including `index.html`, `styles.css`, `script.js`, `assets/`, and `reports/`.
3. Commit the files to the `main` branch.
4. Open **Settings → Pages**. Under *Build and deployment*, select **Deploy from a branch**, `main`, and **/(root)**. Save.
5. Your site should be available at `https://YOUR-GITHUB-USERNAME.github.io/3120Final/` once Pages publishes. Repository names are case-sensitive in URLs.

This uses only HTML, CSS, and JavaScript. No npm or build step is necessary. Open `index.html` to preview locally; PDF embeds may behave more reliably when served over HTTP.

## When the project is complete

- Add final technical report and the one-page recommendation into `reports/`, and link them from the report tab.
- Replace the current summary slides with final presentation slides. Current slide definitions are in `script.js` under `const slides`.
- Add a YouTube video ID to `const VIDEO_ID` in `script.js` to embed the walkthrough directly under the deck.
- Update Milestones 4–5's statuses on the directions page and replace the future sections in the report view.
- Review all student/team names, citations, test status, and numbers prior to publishing.

## Important

Public GitHub Pages sites expose their uploaded reports and source files. Before publishing, verify your professor allows public sharing of project materials. If not, keep source files private and share only course-authorized content. A private repository does not automatically imply a private Pages site.
