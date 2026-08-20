# Guozhong Li — Personal Website

Source for [guozhong-li.github.io](https://guozhong-li.github.io), built with Jekyll and deployed by GitHub Pages.

## Content

- `_pages/about.md` — homepage
- `_pages/publications.md` — publications
- `_pages/service.md` — academic service
- `_pages/teaching.md` — teaching
- `_config.yml` — site metadata and author links
- `images/` — profile and institution images

## Local preview

```bash
bundle install
bundle exec jekyll serve
```

The current layout is based on AcademicPages. Theme internals live in `_layouts`, `_includes`, `_sass`, and `assets`; keep those directories together until the site is migrated to a simpler design.
