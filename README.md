# zc-zhang.github.io

Personal homepage of Zhicheng (Charlie) Zhang, built with [al-folio](https://github.com/alshedivat/al-folio).

## Where to edit

| What | File |
| --- | --- |
| Name, site URL, settings | `_config.yml` |
| Home page (bio, photo caption, address) | `_pages/about.md` |
| Profile photo | `assets/img/prof_pic.jpg` |
| News items | `_news/YYYY-MM-DD.md` (one file per item) |
| Publications | `_bibliography/papers.bib` (`selected = {true}` shows it on the home page) |
| Talks | `_pages/talks.md` |
| Projects / funding | `_pages/projects.md` |
| CV page | `_pages/cv.md`; PDF files live in `files/` |
| Email / ORCID / GitHub / Scholar icons | `_data/socials.yml` |
| Coauthor links | `_data/coauthors.yml` |

Every push to `main` is built by GitHub Actions (`.github/workflows/deploy.yml`) and published to the `gh-pages` branch.
