# drivax.github.io

Portfolio website for Alexandre Lalance, published with GitHub Pages.

## GitHub Pages Setup

This repository is configured to be served directly from the repository root on the `main` branch.

In the GitHub repository settings:

1. Open `Settings`.
2. Open `Pages`.
3. Set `Build and deployment` to `Deploy from a branch`.
4. Select branch `main` and folder `/(root)`.
5. Save.

The public URL is:

- `https://drivax.github.io/`

## Structure

- `index.html`: main page entry point used by GitHub Pages
- `_config.yml`: Jekyll and site metadata configuration
- `docs/about.md`: About page content and featured projects
- `docs/resume.md`: resume content loaded into the page
- `docs/styles.css`: site styling
- `docs/script.js`: theme, navigation and markdown loading logic
- `docs/Alexandre_LALANCE_CV.pdf`: downloadable PDF CV

## How It Works

The root `index.html` loads the markdown content from the `docs/` folder in the browser:

- `docs/about.md` populates the About and Projects content
- `docs/resume.md` populates the Resume section
- `docs/styles.css` and `docs/script.js` provide the UI and interactions

This setup keeps GitHub Pages simple while preserving editable markdown content for the main sections.

## Local Preview

You can preview the site with any static file server from the repository root.

Examples:

```powershell
python -m http.server 8000
```

Then open:

- `http://localhost:8000/`

## Updating Content

- Edit `docs/about.md` to update the About, Projects and Contact sections.
- Edit `docs/resume.md` to update the Resume section.
- Edit `docs/styles.css` to adjust the visual design.
- Edit `docs/script.js` if you need to change navigation, markdown loading or interactions.