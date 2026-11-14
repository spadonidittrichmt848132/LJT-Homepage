# LJT-Homepage

Personal homepage of **Junteng Liu**, first-year PhD candidate at the HKUST NLP Group, Hong Kong University of Science and Technology.

Built with the [Academic Pages](https://github.com/academicpages/academicpages.github.io) Jekyll template (a fork of [Minimal Mistakes](https://mmistakes.github.io/minimal-mistakes/)) and deployed to GitHub Pages via GitHub Actions.

## Site structure

- `_config.yml` — site-wide settings and author profile (sidebar).
- `_data/navigation.yml` — header navigation (About, Publications).
- `_pages/about.md` — home page: biography, research interests, education, research experience, publications, awards, and contact information.
- `_pages/publications.html` — publications listing.
- `_publications/` — one Markdown file per publication.

The site is rebuilt and deployed automatically on every push to `master` (see `.github/workflows/jekyll.yml`).
