# taemincho.github.io

Personal website, built with [al-folio](https://github.com/alshedivat/al-folio) (Jekyll).

## Editing content

- **About**: `_pages/about.md` (bio, photo, contact info)
- **CV / career**: `_data/cv.yml` (education, experience, skills)
- **Publications**: `_bibliography/papers.bib` (BibTeX entries, auto-rendered on `/publications/`)
- **Blog posts**: add files to `_posts/` as `YYYY-MM-DD-title.md`
- **News/announcements**: add files to `_news/`
- **Projects**: add files to `_projects/`
- **Site settings** (name, social links, etc.): `_config.yml` and `_data/socials.yml`

## Running locally

Requires Ruby, Bundler, and Node.

```bash
bundle install
npm install
bundle exec jekyll serve
```

Then open http://localhost:4000.

## Deploying

Pushing to `main` triggers `.github/workflows/deploy.yml`, which builds the site and pushes it to the `gh-pages` branch. In the repo's **Settings → Pages**, set the source to deploy from the `gh-pages` branch.
