# ethlau.github.io

Personal website of Erwin T. Lau, built with the [al-folio](https://github.com/alshedivat/al-folio) Jekyll template and deployed to GitHub Pages by `.github/workflows/deploy.yml`.

## Where things live

| To change | Edit |
| --- | --- |
| Name, site description, theme settings | `_config.yml` |
| About page (home) | `_pages/about.md`, photo in `assets/img/prof_pic.png` |
| Research page | `_pages/research.md` |
| Publications | `_bibliography/papers.bib` (add `selected = {true}` to show a paper on the home page) |
| CV page | `_data/cv.yml`; the PDF is `files/CV.pdf` |
| News items on the home page | one file per item in `_news/` |
| Social links (email, Scholar, ORCID, GitHub, X) | `_data/socials.yml` |
| Journal badge colors | `_data/venues.yml` |

## Adding a paper

Export a BibTeX entry (for example from NASA ADS), paste it into `_bibliography/papers.bib`, and add an `arxiv = {XXXX.XXXXX}` field to get an arXiv button. Refereed papers use `@article`, submitted or in-preparation papers use `@unpublished`, and proceedings, chapters and white papers use `@misc`.

## Previewing locally

```bash
bundle install
bundle exec jekyll serve
```

Then open http://localhost:4000. See the [al-folio documentation](https://github.com/alshedivat/al-folio/tree/main/docs) for more options.
