# Forward Pickleball Coaching Blog

A Jekyll site for Forward Pickleball Coaching's website and blog.

## Structure

- `_config.yml` — site settings and navigation
- `_layouts/` — `default` (site chrome) and `post` (blog post) templates
- `_includes/` — shared header/footer partials
- `_posts/` — blog posts (Markdown, filename `YYYY-MM-DD-title.md`)
- `assets/css/style.css` — site styling
- `index.html`, `blog.html`, `about.md`, `coaching.md`, `contact.md` — main pages

## Running locally

```bash
bundle install
bundle exec jekyll serve
```

Then open http://localhost:4000.

## Adding a new blog post

Create a file in `_posts/` named `YYYY-MM-DD-your-title.md` with front matter:

```markdown
---
title: "Your Post Title"
category: Strategy
author: Coach Team
---

Post content here...
```

This site is ready to deploy on GitHub Pages (Jekyll is built in natively —
no extra build step required).
