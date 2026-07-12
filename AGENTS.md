# Repository Instructions

## Setup

No build is required for the current static site.

```bash
python -m http.server 8000
```

## Key areas

- `index.html`: primary one-page company experience.
- `css/style.css`: custom design layer.
- Bootstrap files: responsive grid and components.
- `js/filter.init.js`: project filtering.
- `js/mklb.js`: lightbox behavior.
- Swiper files: carousel support.
- `js/app.js`: shared page interactions.

## Change rules

- Preserve the CSS, JS, and image folder structure.
- Replace placeholder company, team, project, and contact information before public use.
- Keep filter labels aligned with project categories.
- Remove dead links instead of leaving `javascript:void(0)` controls.
- Avoid editing minified vendor files directly.
- Record vendor versions and licenses when dependencies change.

## Verification

1. Load the page without console or network errors.
2. Test navbar, project filters, lightbox, Swiper, and back-to-top.
3. Check every CTA, email, phone, and footer link.
4. Review desktop and mobile layouts.
5. Verify keyboard access, form labels, focus, contrast, and alt text.
6. Validate metadata and structured data before deployment.

## Do not

- Do not present placeholder projects or team members as real.
- Do not claim newsletter subscription works without a backend.
- Do not edit vendor bundles as application source.
- Do not present the repository thumbnail as a runtime screenshot.