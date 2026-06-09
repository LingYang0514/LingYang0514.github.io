# Ling Yang

Personal academic website for Ling Yang, built with [Jekyll](https://jekyllrb.com/) and the [al-folio](https://github.com/alshedivat/al-folio) theme.

## Local Development

Install Ruby dependencies:

```sh
bundle install
```

Run the site locally:

```sh
bundle exec jekyll serve
```

The site is published through GitHub Actions from the `main` branch.

## Content

- `_pages/about.md`: homepage profile and research summary
- `_bibliography/papers.bib`: publications
- `_news/`: homepage news items
- `_data/cv.yml`: CV page data
- `_data/socials.yml`: social links

## Theme

This repository uses al-folio v1 through the `al_folio_core` and related `al_*` Ruby gems. Site-owned content lives in `_pages`, `_data`, `_news`, `_bibliography`, `assets/img`, and `assets/json`.

For future al-folio upgrades, update the Ruby dependencies and run:

```sh
bundle exec al-folio upgrade audit
bundle exec al-folio upgrade overrides audit
```
