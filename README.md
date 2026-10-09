# s89ne.github.io

Personal website of Sofiane Ezzehi, served by GitHub Pages at https://s89ne.github.io/.

Plain static site: no build step, no Jekyll theme (`.nojekyll` tells GitHub Pages to serve the files as they are).

## Pages

| URL | File |
|---|---|
| https://s89ne.github.io/ | `index.html` (About, research interests, latest preprint) |
| /cv/ | `cv/index.html` (short CV + link to the PDF) |
| /teaching/ | `teaching/index.html` |
| /publications/ | `publications/index.html` |
| /events/ | `events/index.html` (talks, posters, schools, organisation) |

Shared files: `assets/css/style.css` (colors, fonts, layout), `assets/img/Sofiane_Ezzehi_Photo.png`,
`assets/CV_Sofiane_Ezzehi.pdf`, `favicon.svg`.

## Common updates

- **New paper:** in `publications/index.html`, copy an `<li class="entry">` block, paste it above the existing one, edit it.
- **New talk or poster:** same in `events/index.html` (most recent first).
- **New CV:** overwrite `assets/CV_Sofiane_Ezzehi.pdf` with a file of the same name.
- **Sidebar, menu or footer:** they are repeated at the top and bottom of each of the 5 pages, so make the same change in all 5 files.

## Preview locally

In this folder, run `python3 -m http.server`, then open http://localhost:8000 in a browser (Ctrl+C in the terminal to stop).
