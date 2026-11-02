# Applied Linguistics Zemi website

Static course site for the 2-year zemi. No build step: plain HTML pages sharing one stylesheet.

## Pages

| File | Page |
| --- | --- |
| `index.html` | Home: how the zemi works and the Year 1 milestone list |
| `year1.html` | Year 1 week-by-week schedule (Spring and Fall, 12 classes each) and main deadlines |
| `summary-guide.html` | Guide to completing Worksheet 5A |
| `research-log.html` | How to set up and fill the Google Sheets research log |
| `presentation.html` | Spring presentation structure and rubric |
| `ground-rules.html` | Ground rules (English and Japanese) |
| `assets/style.css` | Shared styles (light and dark mode, print) |
| `files/Worksheet_5A.docx` | Downloadable weekly summary sheet |

## Editing

- The navigation bar is repeated at the top of every page. When you add a page, add its link to the `site-nav` block in each file.
- Milestone ticks on the home page are saved in each student's browser only (localStorage). They are a personal reminder, not a record.
- The ground rules page still has a placeholder for the contact method: search for `[contact method`.

## Publishing on GitHub Pages

1. Create a GitHub repository and push this folder to it.
2. In the repository, open **Settings → Pages**.
3. Under **Build and deployment**, choose **Deploy from a branch**, select `main` and `/ (root)`, and save.
4. The site will appear at `https://<your-username>.github.io/<repository-name>/`.
