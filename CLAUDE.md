# Personal Website — Claude Notes

## Site overview
Static HTML/CSS personal academic site for Anastasiia Morozova (PhD student, UCSB Economics).
Files: `index.html`, `styles.css`, `0.jpg` (headshot), `CV_AM-2.pdf` (CV).

## How to get content right from the live site

**Always fetch the live Google Site before editing content sections.**
The live site is: https://sites.google.com/view/anastasiia-morozova/home

When rebuilding or updating sections, make two fetches:
1. One for overall layout/structure.
2. One targeted fetch asking for the **exact, word-for-word text** of the specific sections you're updating (working papers, teaching, work experience, etc).

Do NOT guess or paraphrase content. The live site has:
- Full course codes and names for Teaching Experience (e.g. "ECON 157 – Behavioral Economics")
- All 5 bullet points for IMF Work Experience
- arxiv link for working paper: https://arxiv.org/pdf/2502.00195
- Full author list for working paper: Andrew Caplin, Daniel Martin, Philip Marx, Anastasiia Morozova, Leshan Xu

## CV file
The CV is `CV_AM-2.pdf` in the repo root. The Download CV nav link points to it locally (`href="CV_AM-2.pdf"`). Do NOT link to Google Drive.

## Git / GitHub setup
- The `.git` at the HOME directory level (`/Users/anastasiiamorozova/`) is NOT this repo's git. Always use `git -C /Users/anastasiiamorozova/Downloads/personal-website` or cd into the folder first.
- GitHub account: `a-morozova`
- Target: GitHub Pages from `main` branch root.

## Design
- Light theme (white background, dark text) — do not revert to dark theme
- Fonts: Playfair Display (headings) + Open Sans (body) via Google Fonts
- Max content width: 800px centered
- Sticky top nav with "More" dropdown linking to page sections
