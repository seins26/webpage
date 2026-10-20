# CCP 2026 Fall Midterm Exam Clock

Static exam-room clock for GitHub Pages.

## Features
- Live 24-hour clock with seconds (HH:MM:SS)
- SeoulNotice webfont with Apple/system fallback
- Clock is black before 15:15:00
- Clock turns orange from 15:15:00 through 15:19:59
- Clock turns red from 15:20:00 onward
- English and Korean examination-room instructions
- Responsive layout for iPad/Safari

## Publish with GitHub Pages
1. Create a GitHub repository (for example: `exam-clock`).
2. Upload `index.html` and `.nojekyll` to the repository root.
3. Open Settings > Pages.
4. Under Build and deployment, choose `Deploy from a branch`.
5. Select branch `main` and folder `/(root)`, then Save.
6. Open the Pages URL shown by GitHub.

For a project repository named `exam-clock`, the usual URL is:
`https://YOUR-USERNAME.github.io/exam-clock/`

## Font
SeoulNotice is loaded as a webfont from the Noonnu/projectnoonnu CDN. If it cannot load, the page falls back to the Apple/system sans-serif font.
