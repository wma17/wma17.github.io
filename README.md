# Wang Ma Homepage (Static)

This repository now serves a **pure static** homepage via GitHub Pages.

## Structure
- `index.html`: live homepage entry.
- `homepage_preview.html`: local preview/editing copy.
- `images/`: images and QR code assets.
- `_pages/`: PDF files (kept for stable external links), e.g. `/_pages/CV.pdf`.
- `.nojekyll`: disables Jekyll build on GitHub Pages.

## Publish
Push to `main` and GitHub Pages will serve `index.html` directly.

## Notes
- Jekyll/theme build files were removed intentionally.
- Keep PDF paths under `/_pages/` unchanged to avoid breaking existing references.
