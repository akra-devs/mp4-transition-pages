# mp4-transition-pages

Public product page for
[CallFilm](https://akra.kr/mp4-transition-pages/), an Android app
that turns call recordings into locally rendered MP4 archives with on-device
AI captions.

The Flutter source stays in the private `RefinedStone/mp4-transition`
repository. This public repository contains only the product page, approved
store artwork, public policy and support documents, a synthetic reviewer
fixture, and the GitHub Pages deployment workflow.

Current public status:

- App version: `1.0.0`
- Android build: `1`
- Distribution: Android market download planned
- Direct APK downloads: not provided

## Repository layout

- `site/`: static product page and public artwork
- `site/privacy/`: public privacy policy
- `site/support/`: public support FAQ and inquiry route
- `site/assets/Review_Tone_20260715_120000.wav`: synthetic Google Play
  reviewer fixture; no voice or personal data
- `design-system/`: page-specific visual conventions
- `.github/workflows/deploy-pages.yml`: GitHub Pages deployment

Public release resources:

- Privacy policy:
  <https://akra.kr/mp4-transition-pages/privacy/>
- Support:
  <https://akra.kr/mp4-transition-pages/support/>
- Reviewer fixture:
  <https://akra.kr/mp4-transition-pages/assets/Review_Tone_20260715_120000.wav>

## Local preview

```bash
python3 -m http.server 4173 --directory site
```

Then open <http://127.0.0.1:4173/>.

The `main` branch is deployed with GitHub Actions. When the Google Play listing
is public, replace the planned-download status with the official store URL.
