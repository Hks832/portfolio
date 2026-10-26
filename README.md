# Hamza Khan — Portfolio

A responsive portfolio built with plain HTML, CSS, and JavaScript. No framework, package installation, or build step is required.

## Edit the portfolio

- `index.html`: hero text, overview, education, contact links, page title, and description.
- `script.js`: the skills, projects, and experience arrays; navigation and copy-email behavior.
- `style.css`: colors (the `:root` variables), fonts, spacing, and mobile layout.
- `Hamza_Khan_Resume.pdf`: replace this file to update the downloadable résumé, keeping the filename.

The GitHub and LinkedIn links currently follow the supplied résumé. Update those links in index.html if you want to use a different account.

## Preview locally

Run `python -m http.server 8000` from this folder, then open http://localhost:8000.

## Publish without a ChatGPT URL

In repository Settings → Pages, set Source to **Deploy from a branch**, choose **main** and **/ (root)**, and Save.

After GitHub Pages finishes deploying, the expected address is https://hks832.github.io/portfolio/ . This address is not live until Pages is enabled and deployment succeeds. Future commits to main will update that site.

Google Fonts supplies the typefaces; fallback fonts are defined in the stylesheet.
