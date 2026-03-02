# Slade Networks Site

## Before starting any task
Always run `git pull origin main` from the main repo root before creating worktrees or making changes, to ensure the local branch is not behind origin.

## Project structure
- **SSG**: Eleventy (11ty) with Nunjucks templates
- **Pages**: `src/*.njk`
- **Shared layout**: `src/_includes/base.njk` — nav, footer, and scripts live here
- **Styles**: `src/assets/styles.css`
- **Assets**: `src/assets/`
- **Deploy**: GitHub Actions → GitHub Pages via `.github/workflows/deploy.yml`
