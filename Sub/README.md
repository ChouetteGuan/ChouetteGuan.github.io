# Sub/

This folder is intended to host small standalone sub-sites served from `Sub/`.

Examples included:

- `blog/` — tiny blog-style page
- `portfolio/` — simple portfolio listing
- `project/` — single-project showcase

How to add a new subsite:

1. Create a new folder under `Sub/`, e.g. `Sub/my-site/`.
2. Add an `index.html` (and any assets) inside that folder.
3. Link to your subsite from the main site (`index.html`) or from `Sub/index.html`.
4. Optionally add styles to `subsite.css` or your own stylesheet.

Notes:
- Paths are relative to the subsite folder; use `../` to refer to files in `Sub/`.
- If you publish on GitHub Pages, the subfolders will be available as `https://<user>.github.io/<repo>/Sub/<subfolder>/`.
