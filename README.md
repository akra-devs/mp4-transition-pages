# mp4-transition-pages

Public product page for
[CallFilm](https://akra.kr/mp4-transition-pages/), an Android app
that turns call recordings into locally rendered MP4 archives.

The Flutter source stays in the private `RefinedStone/mp4-transition`
repository. This public repository contains only the product page, approved
store artwork, and the GitHub Pages deployment workflow.

Current public status:

- App version: `1.0.0`
- Android build: `1`
- Distribution: Android market download planned
- Direct APK downloads: not provided

## Repository layout

- `site/`: static product page and public artwork
- `design-system/`: page-specific visual conventions
- `.github/workflows/deploy-pages.yml`: GitHub Pages deployment

## Local preview

```bash
python3 -m http.server 4173 --directory site
```

Then open <http://127.0.0.1:4173/>.

The `main` branch is deployed with GitHub Actions. When the Google Play listing
is public, replace the planned-download status with the official store URL.
