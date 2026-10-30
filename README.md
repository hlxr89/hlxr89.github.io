# hlxr89.github.io

Personal academic website of Xinrui (Henry) Li, served by GitHub Pages from the `main` branch.

Plain HTML/CSS, no build step. Layout adapted from
[Jon Barron's website template](https://github.com/jonbarron/jonbarron_website).

- `index.html` — the whole site (bio, research, publications, teaching)
- `stylesheet.css` — Barron's stylesheet plus a few responsive rules
- `images/` — profile photo (`henry.jpg`) and paper figures; `semanteq_fig1.tex` is the TikZ source of the SemantEq figure (Figure 1 of the paper, re-laid out vertically), compiled with `pdflatex` and cropped to PNG
- `data/` — CV and other downloadable files
- `.nojekyll` — tells GitHub Pages to serve the files as-is

To add a paper, copy one `<tr>` block in the "papers" table of `index.html`
and edit the title, authors, venue, links and one-paragraph summary.
