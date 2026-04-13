# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Overview

Personal website for **alexnuttinck.dev** built with [Hugo](https://gohugo.io/) and the [Toha v4 theme](https://github.com/hugo-toha/toha). Deployed to GitHub Pages via a GitHub Actions workflow on push to `master`.

## Common Commands

```bash
# Local development server
hugo server

# Production build (matches CI)
hugo --gc --minify

# Update Hugo modules
hugo mod tidy

# After cloning or module changes
hugo mod tidy && hugo mod npm pack && npm install
```

## Architecture

### Content

All blog posts live under `content/posts/`. The main series is **"Adventures in Uptime"** — a numbered sequence of humorous DevOps/sysadmin anecdotes with comic panel images.

- Story files: `content/posts/[N]-[slug].md`
- Story images: `content/posts/adventures-in-uptime/[N]-[slug].png`
- Series index: `content/posts/adventures-in-uptime.md`

### Front Matter Pattern for Stories

```yaml
---
title: "Human Readable Title"
date: YYYY-MM-DDTHH:MM:SS+02:00
hero: images/blog/adventures-in-uptime/banner.png
description: "Adventures in Uptime N - Title"
theme: Toha
menu:
  sidebar:
    name: "N - Title"
    identifier: kebab-case-slug
    parent: adventures-in-uptime
    weight: N+1
---
```

Image embed inside post body:
```
{{< img src="/posts/adventures-in-uptime/[N]-[slug].png" title="..." >}}
```

### Site Data

Structured YAML files under `data/en/` drive the CV/portfolio sections (author, education, experiences, projects, skills, publications). These map to the Toha theme's section components.

### Theme & Styling

- The Toha theme is loaded as a Hugo Go module (not a local submodule) — do not edit theme files directly.
- Frontend assets (Bootstrap 5, KaTeX, FontAwesome, Fuse.js) come from `node_modules` mounted via Hugo's module mounts in `config.yaml`.
- Custom template overrides go in `layouts/`, custom styles in `assets/`.

### Deployment

- GitHub Actions (`.github/workflows/publish.yml`) builds on push to `master` and pushes to `gh-pages` branch.
- CNAME: `alexnuttinck.dev`
- Netlify config (`netlify.toml`) is present for deploy previews but GitHub Pages is the primary host.
