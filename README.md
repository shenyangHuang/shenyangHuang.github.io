# shenyangHuang.github.io

Shenyang Huang's personal academic homepage — a Jekyll static site published with GitHub Pages at
[shenyanghuang.github.io](https://shenyanghuang.github.io).

## Pages

- `index.html` — bio, news, publications, lecture slides, teaching, services, awards and mentorship
- `rg.html` — [Temporal Graph Learning (TGL) Reading Group](https://shenyanghuang.github.io/rg.html):
  upcoming and past talks, organizers, and links to Zoom, Slack and YouTube

## Local preview

Requires Ruby and Bundler:

```bash
bundle exec jekyll serve
```

Then open <http://localhost:4000>.

## Deployment

Automatic — pushing to `master` triggers GitHub Pages to rebuild and publish the site.

## Layout

Hand-authored HTML; no framework, build pipeline or package manager.

- `_config.yml` — Jekyll config (theme and site title)
- `css/plain-style.css` — primary custom stylesheet
- `css/`, `js/` — Bootstrap 3 and jQuery, vendored locally
- `images/` — photos used across both pages
