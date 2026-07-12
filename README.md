# The Solution Architect

A Jekyll blog on solution architecture and enterprise architecture, hosted on GitHub Pages.

## Local preview

```
bundle install
bundle exec jekyll serve
```

Then open http://localhost:4000.

## Adding a post

Add a new file to `_posts/` named `YYYY-MM-DD-slug.md` with front matter:

```
---
layout: post
title: "Post Title"
date: YYYY-MM-DD HH:MM:SS +0100
categories: [tag1, tag2]
---

Post body in Markdown.
```

Push to `main` and GitHub Pages rebuilds the site automatically — no separate deploy step.
