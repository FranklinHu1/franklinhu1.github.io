# franklinhu1.github.io

Personal website for Frank Hu, published with [Jekyll](https://jekyllrb.com/)
on [GitHub Pages](https://pages.github.com/) at
**https://franklinhu1.github.io**.

## Editing

- `index.md` — home page
- `about.md` — about page
- `publications.md` — publication list
- `repositories.md` — selected public code
- `cv.md` — CV page, embedding `assets/HuFrankCV.pdf`
- `_config.yml` — site-wide settings (title, theme, plugins)

`assets/HuFrankCV.pdf` is built from the
[hu-frank-cv](https://github.com/FranklinHu1/hu-frank-cv) repository
(`main.tex`); regenerate and copy it here when the CV changes.

Any push to `main` triggers GitHub Pages to rebuild and publish the site.

## Local preview

Requires Ruby + Bundler:

```bash
bundle install          # first time only
bundle exec jekyll serve # serves at http://localhost:4000
```
