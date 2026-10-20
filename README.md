# Portfolio site (Jekyll, GitHub Pages)

## Install
1. In your repo, keep the `_posts` folder. Delete the old `index.markdown`, `about.markdown`, `404.html` (if from Minima) and the old `_config.yml` and `Gemfile`.
2. Copy everything from this folder into the repo root.
3. Commit and push. GitHub Pages rebuilds in about a minute.

## Preview locally (optional)
    bundle install
    bundle exec jekyll serve
Then open http://localhost:4000/gameplayguru/

## Edit
- Name, email, links: `_config.yml`
- Home page headline, code snippet: `index.html`
- Section names and blurbs (also the nav): `_data/sections.yml`
- Colors, fonts, spacing: `assets/css/style.scss` (variables at the top)
- About page: `about.md`

## Add content
- Python project: new file in `_python/`
- Docs sample: new file in `_docs_samples/`
- Misc: new file in `_misc/`
- Writing: new file in `_posts/` named `YYYY-MM-DD-title.md`

Each file needs front matter:

    ---
    title: My project
    summary: One sentence shown on the section page.
    ---

## Optional
Rename the repo to `syedkingbook.github.io` for a root URL, then set `baseurl: ""` in `_config.yml`.
