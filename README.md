# binjiezhang.github.io

Personal homepage of **Binjie Zhang (张斌杰)** — Ph.D. candidate at [Show Lab](https://sites.google.com/view/showlab), National University of Singapore.

Live at [https://binjiezhang.github.io](https://binjiezhang.github.io).

Built with the [al-folio](https://github.com/alshedivat/al-folio) Jekyll theme.

## Local development

```bash
# One-time setup (needs Ruby 3.x)
bundle install

# Serve locally at http://127.0.0.1:4000
bundle exec jekyll serve
```

## Content

| File / folder                 | What it controls                                           |
| ----------------------------- | ---------------------------------------------------------- |
| `_pages/about.md`             | Home page (bio)                                            |
| `_bibliography/papers.bib`    | Publications                                               |
| `_projects/`                  | Selected projects                                          |
| `_news/`                      | News items on the home page                                |
| `_data/cv.yml`                | CV page content                                            |
| `_data/socials.yml`           | Social icons and CV PDF path                               |
| `_config.yml`                 | Site-wide config (name, URL, footer, scholar, theme)       |
| `assets/img/prof_pic.jpg`     | Profile photo                                              |
| `assets/pdf/binjie_cv.pdf`    | Downloadable CV PDF                                        |

Deployment is handled by `.github/workflows/deploy.yml` on push to `master`.
