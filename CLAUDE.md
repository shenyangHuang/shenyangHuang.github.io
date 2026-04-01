# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Overview

This is Shenyang Huang's personal academic homepage, a Jekyll-based static site deployed via GitHub Pages. It consists of two main pages:
- `index.html` — Personal portfolio with bio, news, publications, and teaching
- `rg.html` — Temporal Graph Learning (TGL) Reading Group page with upcoming/past talks and organizer info

## Local Development

To preview the site locally (requires Ruby/Bundler):

```bash
bundle exec jekyll serve
```

Then open `http://localhost:4000`.

Deployment is automatic — pushing to `master` triggers GitHub Pages to rebuild and publish.

## Architecture

**Static HTML site** — no framework, build pipeline, or package manager. All pages are hand-authored HTML files.

- `_config.yml` — Jekyll config (minimal: just theme `jekyll-theme-minimal` and site title)
- `css/plain-style.css` — Primary custom stylesheet (typography, colors, layout)
- `css/scrolling-nav.css` — Smooth anchor scroll styles
- `js/scrolling-nav.js` — Scroll-to-anchor behavior
- Bootstrap 3 + jQuery are bundled locally in `css/` and `js/`

## Key Content Areas

**`rg.html`** is the most actively maintained file (~3500 lines). It contains:
- Upcoming talk schedule (speaker, date, title, abstract, bio)
- Past talks organized by semester
- Organizer cards with photos from `images/`
- Links to Zoom, Slack, YouTube, email signup

When adding new talks, follow the existing card structure in the "Upcoming Talks" section and move talks to the appropriate past semester section when they're done.
