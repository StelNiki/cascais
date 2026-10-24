# Cascais

A small, responsive information site about Cascais, Portugal. It uses plain HTML and CSS, so there is no build step or package installation.

## Preview locally

Open `index.html` in a browser.

## Publish with GitHub Pages

The workflow in `.github/workflows/pages.yml` deploys the site whenever changes are pushed to `main`.

1. Push this project to the `main` branch of `StelNiki/cascais`.
2. In the repository, open **Settings → Pages** and set the build and deployment source to **GitHub Actions**.
3. Open the **Actions** tab and wait for **Deploy static site to GitHub Pages** to finish.
4. The published address will be shown in the workflow's `github-pages` environment and in **Settings → Pages**.

For the user site/repository `StelNiki/cascais`, the expected address is `https://stelniki.github.io/cascais/`.

## Extend the site

Add content as semantic sections in `index.html` and use `styles.css` for presentation. If the site later needs interactive features or a content workflow, a framework or static-site generator can be introduced without requiring one for this starting version.
