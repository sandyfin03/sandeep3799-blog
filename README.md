# Personal Academic Blog — GitHub Pages (Minimal Mistakes)

This repository contains a **free, good-looking academic website** for a PhD Research Scholar at **IIT (ISM) Dhanbad**, built on **GitHub Pages** with the **Minimal Mistakes** Jekyll theme.  
It includes pages for **About, Research, Publications, Teaching, and Blog**.

## Quick Deploy

1. Create a new GitHub repository (public), e.g. `sandeep-blog`.
2. Download this zip and extract its contents. Drag-drop everything into the new repo.
3. Go to **Settings → Pages**:
   - **Source**: `Deploy from a branch`
   - **Branch**: `main` → `/ (root)` → **Save**
4. Your site will appear at `https://<your-username>.github.io/<repo-name>/` in a minute or two.

## Customize
- Edit `_config.yml` for your name, description, social links, Google Scholar, etc.
- Replace the `assets/img/profile.jpg` with your photo (keep same name for auto-usage).
- Add blog posts in `_posts/` (filename format: `YYYY-MM-DD-title.md`).
- Add publications in `_data/publications.yml`.

## Local preview (optional)
If you want to develop locally:
```bash
# Ruby and Bundler required
bundle install
bundle exec jekyll serve
```
Open http://127.0.0.1:4000
