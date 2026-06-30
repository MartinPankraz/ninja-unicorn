# Copilot instructions for this repository

This repository publishes blog content with GitHub Pages using Jekyll.

## Branch and publishing model

- Create and update blog posts on the `pages` branch.
- Store posts in the `_posts/` folder.
- A push to `pages` triggers the Jekyll build pipeline.
- The generated site output is published from the `gh-pages` branch.

## Working conventions

- For new articles, add files under `_posts/` on `pages` using Jekyll post naming conventions.
- Treat `gh-pages` as generated output; do not author source blog content there.
- Keep edits focused on blog source content and related metadata/front matter.
