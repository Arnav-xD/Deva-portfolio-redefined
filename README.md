# Arnav Deva Portfolio

Complete source for the portfolio created in ChatGPT Sites. This is a static HTML and CSS website, with no framework, npm dependencies, backend, or build step.

## Files

- `index.html`: all portfolio content, navigation, metadata, and contact links.
- `style.css`: layout, colors, typography, and mobile styles.
- `.gitignore`: common local files to keep out of Git.

The favicon is embedded in the HTML. Fonts load from Google Fonts with local fallback fonts. There are no missing image assets or JavaScript files.

## Preview locally

Open `index.html` in your browser, or use VS Code Live Server. If Python is installed, run `python -m http.server 8000` from this folder and open http://localhost:8000.

## Customize

1. Edit text and links in `index.html`. Sections have IDs `home`, `work`, `experience`, `about`, and `contact`.
2. Change the CSS variables at the start of `style.css` to adjust the theme. `--accent` controls the lime highlight; `--bg` controls the background.
3. Update typography in the Google Fonts import and the font-family rules.
4. Duplicate an existing project article to add a project. Keep section IDs unique and match navigation anchor links.
5. Check desktop and mobile layouts after changes. Responsive rules are at the end of `style.css`.

## Put it on GitHub

Create a repository in your own account. Upload the contents of this folder to its root, or use GitHub Desktop to add the folder as a local repository and publish it.

## Hosting

Any static web host can serve these files directly. There is no build command and the public directory is the repository root.

This export contains the complete website source. ChatGPT Sites-specific project metadata and Git credentials are intentionally excluded. Changes to this GitHub copy do not automatically update the existing ChatGPT Sites deployment.
