# thesis-page

The public page of my Master's thesis, *Goal Generation for World Models*, served by GitHub Pages at
https://tobygitt.github.io/thesis-page/ once Pages is switched on.

## Editing

- All text is in `index.html`. Each section starts with a comment, e.g. `<!-- 2 · Step 1, decompose -->`.
- Numbers that change live only in "Where it stands". When they change, update the date there, in the line below the
  title and in the colophon at the end.
- Styles are in `style.css`, images and clips in `assets/`, fonts in `fonts/` (SIL Open Font License, see the
  `OFL-*.txt` files).

## Preview

Run `python3 -m http.server 8000` in this folder and open http://localhost:8000 (VS Code forwards the port).

## Publishing

Commit and push to `main`. With Pages on (Settings → Pages → Deploy from a branch → `main`, `/ (root)`), the site
updates about a minute later.
