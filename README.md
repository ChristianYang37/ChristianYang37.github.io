# ChristianYang37.github.io

Source for Chiwun (Christian) Yang's academic homepage at [christianyang37.github.io](https://christianyang37.github.io/).

## Content map

- `_pages/about.md` — biography, research areas, publications, education, experience, and service
- `_config.yml` — site metadata and profile links
- `_data/navigation.yml` — top navigation
- `assets/css/main.scss` — theme imports and homepage-specific styles
- `images/` — profile, icon, and social-preview assets

The `/Blogs/` link points to a separately maintained Hugo blog hosted under the same GitHub Pages domain.

## Local preview

```bash
bundle install
bundle exec jekyll serve --livereload
```

Then open `http://127.0.0.1:4000/`.

## Update checklist

1. Verify current roles, dates, and programme status before editing biography or experience.
2. Link peer-reviewed papers to official proceedings when available; use arXiv for preprints.
3. Keep unpublished projects, planned experiments, and unverified performance claims off the public site.
4. Run `bundle exec jekyll build` and inspect the generated links before publishing.
5. Update the `Last updated` line in `_pages/about.md` after a meaningful content change.

This site is based on [AcadHomepage](https://github.com/RayeRen/acad-homepage.github.io), which incorporates Minimal Mistakes and Academic Pages components under their respective licenses.
