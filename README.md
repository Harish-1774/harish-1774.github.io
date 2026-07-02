# harish.github.io

Personal portfolio site hosted on [GitHub Pages](https://pages.github.com/).

## Local preview

Open `index.html` in your browser, or run a simple local server:

```bash
python3 -m http.server 8000
```

Then visit `http://localhost:8000`.

## Deploy to GitHub Pages

This repo is set up as a **user site** (`username.github.io`), so the site is served from the repository root.

1. Push this repository to `https://github.com/Harish-1774/harish.github.io`
2. On GitHub, go to **Settings → Pages**
3. Under **Build and deployment**, set **Source** to **Deploy from a branch**
4. Choose branch `main` and folder `/ (root)`
5. Save — your site will be live at `https://harish-1774.github.io` after a minute or two

## Project structure

```
.
├── index.html      # Main page
├── css/style.css   # Styles
├── js/main.js      # Small interactions
├── assets/         # Images and other static files
└── .nojekyll       # Skip Jekyll processing for plain static files
```

## Customize

- Edit copy and links in `index.html`
- Update colors and layout in `css/style.css`
- Add images to `assets/` and reference them from HTML
