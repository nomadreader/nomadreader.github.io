# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Overview

This is a GitHub Pages static site repository for `nomadreader.github.io`, licensed under [CC BY-NC 4.0](https://creativecommons.org/licenses/by-nc/4.0/) (non-commercial use only).

The site is served at `https://nomadreader.github.io` via GitHub Pages from the `main` branch.

## GitHub Pages

GitHub Pages supports static HTML/CSS/JS directly, or Jekyll for template-based static site generation. If this project uses Jekyll:
- `_config.yml` — site configuration
- `_posts/` — blog posts (Markdown, named `YYYY-MM-DD-title.md`)
- `_layouts/` and `_includes/` — templates
- `Gemfile` — Ruby dependencies; run `bundle install` then `bundle exec jekyll serve` to preview locally at `http://localhost:4000`

If it's plain static HTML, open `index.html` directly in a browser or use any local HTTP server (e.g., `python3 -m http.server`).

## License

All content is CC BY-NC 4.0 — attribution required, no commercial use.
