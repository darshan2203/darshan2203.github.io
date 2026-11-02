# darshan2203.github.io

Personal site of Darshan Sonagara, served by GitHub Pages at https://darshan2203.github.io.

It is a plain static site. GitHub Pages serves these files as they are, with no build step to configure.

## Files

| Path | What it is |
|---|---|
| `index.html` | The whole page: sidebar, about, news, selected work, publications, talks, experience, education |
| `assets/css/style.css` | All styling, including dark mode |
| `assets/img/darshan-portrait.jpg` | Sidebar photo (440 × 550 portrait) |
| `assets/img/darshan.jpg` | Square photo used for link previews and search results |
| `cv/index.html` | The CV page (darshan2203.github.io/cv/) |
| `cv/Darshan_Sonagara_CV.pdf` | The downloadable CV, printed from the CV page |
| `assets/css/cv.css` | CV page styling, including the print layout used for the PDF |

## Common updates

- **Citation count:** edit the line under the Publications heading in `index.html` (`331 citations on Google Scholar (Oct 2026)`). Update the per-paper counts in Publications and Selected work at the same time.
- **News item:** copy one `<li class="row compact">` line at the top of the News list and edit the date and text. Move the oldest visible item into the "Earlier news" list when there are more than five.
- **New paper:** copy one `<li class="pub">` block in Publications and edit it. Newest goes first.
- **New project:** copy one `<article class="card">` block in Selected work.
- **CV:** edit `cv/index.html`, then regenerate `cv/Darshan_Sonagara_CV.pdf` by printing that page (Chrome, US Letter, print styles from `cv.css`) so the web CV and the PDF always match. Keep the file name so links keep working.

When you change `style.css`, also bump the `?v=` value on its link in `index.html`, so browsers load the new stylesheet.

After editing, commit to `main`. The live site updates within a minute or two.

## Keep consistent

Titles, dates and numbers on this site must match the immigration petition materials and the CV. Do not add internal Target or Goldman Sachs metrics, system names or revenue figures. Describe the patent filing as a "provisional patent application".
