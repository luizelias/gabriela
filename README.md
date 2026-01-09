# Otica Vezari (Site Estático)

## Project Overview — Image & Assets Handling (Important)

The project must include an `assets/images/` folder where you can manually place the logo and product photos. All images in the website should reference this folder. The layout includes a placeholder logo at the top that you can replace with your own logo file later.

This site is fully static and must work when hosted on GitHub Pages.

- Only HTML, CSS, and optional JavaScript
- No backend, no Node, no build step
- Main entry file is `index.html` at the repository root
- All paths must be relative (no absolute `/` paths)

## Recommended structure

```
/ (repo root)
  ├── index.html
  ├── style.css
  ├── script.js          (optional)
  └── assets/
       └── images/
```

## Image rules

All images must be stored inside `assets/images/` and referenced like:

```html
<img src="assets/images/logo.jpg" alt="Otica Vezari logo">
```

Do not use absolute paths like `/assets/images/logo.jpg`.
