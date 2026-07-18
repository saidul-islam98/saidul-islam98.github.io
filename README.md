# Mohammed Saidul Islam — Portfolio

Source for [saidul-islam98.github.io](https://saidul-islam98.github.io), an industry-focused machine learning portfolio built with Jekyll.

## Content sources

Public claims should remain grounded in the current resume and publication export:

- `../resources/Saidul_ML_Resume_ATS.pdf`
- `../resources/citations.csv`
- `_bibliography/papers.bib`

The two `citations.csv` records about composting and avian microbiology are name collisions and are intentionally excluded. Update `assets/pdf/resume.pdf` and the compatibility URL `assets/pdf/cv.pdf` together whenever the resume changes.

## Main content

- `_pages/about.md` — homepage, bio, expertise, selected work, and highlights
- `_pages/work.md` — industry-oriented technical case studies
- `_pages/experience.md` — employment, education, skills, and service
- `_pages/publications.md` and `_bibliography/papers.bib` — research record
- `_news/` — recent updates
- `_sass/_portfolio.scss` — portfolio-specific visual system

## Local validation

Use Ruby 3.3.5 and Node 24 (recorded in `.ruby-version` and `.nvmrc`). A reproducible Docker build is:

```bash
docker run --rm --user "$(id -u):$(id -g)" \
  -e HOME=/tmp \
  -e BUNDLE_PATH=/site/vendor/bundle \
  -e JEKYLL_ENV=production \
  -v "$PWD:/site" -w /site ruby:3.3.5 \
  bash -c 'bundle install && bundle exec jekyll build'
```

Then run:

```bash
npm ci
npm run format:check
npm audit
npm run css:purge
```

GitHub Actions also builds the site, checks formatting and internal links, and deploys only the saved production artifact to GitHub Pages.

## Attribution

The site is based on the open-source [al-folio](https://github.com/alshedivat/al-folio) Jekyll theme and retains its MIT license.
