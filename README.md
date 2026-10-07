# Alicia Martín — personal website

Static site: open `index.html` in a browser to preview it locally.

## Publish with GitHub Pages
1. Create a new repository on GitHub (e.g. `alicia-martin.github.io` for the address https://alicia-martin.github.io, or any name for https://alicia-martin.github.io/<name>/).
2. Upload everything in this folder (`index.html`, `assets/`, `.nojekyll`, `README.md`).
3. Settings → Pages → Build and deployment → Source: "Deploy from a branch", Branch: `main`, folder `/ (root)` → Save.
4. Wait a minute; the URL appears at the top of the Pages settings.

## Editing
- Text: search for it in `index.html` and type over it.
- Photo: replace `assets/photo.jpg` (keep the name). `assets/photo-bw.jpg` is the black-and-white alternative.
- CV: replace `assets/Alicia_Martin_CV.pdf` and the page images `assets/cv-page-1.jpg`, `assets/cv-page-2.jpg`.

Note: GitHub Pages sites are public to anyone with the link (even from a private repo, which needs a paid plan).
Search engines can index the site. To hide it, add `<meta name="robots" content="noindex, nofollow">` inside `<head>`.
