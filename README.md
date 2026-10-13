# Arnav Deva — Portfolio

A personal portfolio built with **HTML and CSS**, with no framework, npm dependencies, backend, or build step.

[View portfolio](https://deva-arnav-portfolio.vercel.app)

## What's included

The single page contains selected projects, research experience, an about section, education, skills, and contact links. Navigation uses in-page anchors.

## View locally

Open `index.html` in a browser, or serve the repository directory with Python:

```bash
python -m http.server 8000
```

Then open [localhost:8000](http://localhost:8000).

## Read and edit the source

| File | Contents |
| --- | --- |
| [index.html](index.html) | Portfolio content, navigation, metadata, and contact links |
| [style.css](style.css) | Layout, colors, typography, and mobile styles |
| [.gitignore](.gitignore) | Local files excluded from Git |

The favicon is embedded in the HTML. Fonts load from Google Fonts with local fallback fonts. There are no separate JavaScript files or required image assets.

To update the portfolio, edit the text and links in `index.html`. Use `style.css` for visual changes. The site can be served directly as static files.
