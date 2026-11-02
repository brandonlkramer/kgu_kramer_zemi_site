# Kramer Zemi website

Static course site for the 2-year zemi. No build step: plain HTML pages sharing one stylesheet.

## Visible pages (current cohort, Fall 2026 from Week 5)

| File | Page |
| --- | --- |
| `index.html` | Home: how the zemi works and the Fall milestones (Weeks 5–12) |
| `fall.html` | Fall schedule, Weeks 5–12, and main deadlines |
| `summary-guide.html` | Guide to completing Worksheet 5A |
| `research-log.html` | How to set up and fill the Google Sheets research log |
| `ground-rules.html` | Ground rules (English and Japanese) |
| `assets/style.css` | Shared styles (light and dark mode, print) |
| `files/Worksheet_5A.pdf` | Downloadable weekly summary sheet |

## Hidden pages (kept for future cohorts)

These files are still published but nothing links to them, so students will not find them through the site.

| File | Page |
| --- | --- |
| `index-full.html` | Home page with the full Year 1 milestones (Spring and Fall, 24 milestones) |
| `year1.html` | Full Year 1 schedule: Spring and Fall, 12 classes each |
| `presentation.html` | Spring presentation, “My Research Starting Point” |

To switch to the full Year 1 version for a new cohort: rename `index-full.html` to `index.html`, and in every page's `site-nav` block replace the Fall schedule link with links to `year1.html` and `presentation.html`.

## Editing

- The navigation bar is repeated at the top of every page. When you add a page, add its link to the `site-nav` block in each file.
- Milestone ticks on the home page are saved in each student's browser only (localStorage). They are a personal reminder, not a record.

## Publishing on GitHub Pages

1. Create a GitHub repository and push this folder to it.
2. In the repository, open **Settings → Pages**.
3. Under **Build and deployment**, choose **Deploy from a branch**, select `main` and `/ (root)`, and save.
4. The site will appear at `https://<your-username>.github.io/<repository-name>/`.

Note: hidden pages are not private. Anyone who guesses the file name can open them.
