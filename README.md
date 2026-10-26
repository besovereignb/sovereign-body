# Sovereign Body™ — Six-image homepage

Static GitHub Pages site: HTML + CSS, no JavaScript or third-party libraries.

## Deploy
1. Upload `index.html` and `styles.css` into the repository root.
2. Upload all six `.webp` files to the `assets/` folder.
3. Commit the changes. GitHub Pages will deploy automatically.
4. Check desktop/mobile views and inspect the image crop on narrow screens.

## Slide sequence (8 seconds each; 48-second cycle)
1. `runner-man.webp`
2. `runner-woman.webp`
3. `gardener-kneeling.webp`
4. `half-kneeling-reach.webp`
5. `high-shelf-reach.webp`
6. `volleyball-airborne.webp`

Crossfade duration: ~1.6 seconds. Motion-reduction settings display the first image only.

## Image export
Images retain the original 16:9-ish source dimensions and are encoded as WebP quality 85.
The CSS uses `background-size: cover` so some crop on portrait devices is expected.

## Deployment note
Do not remove repository files such as `CNAME` or `.nojekyll`, if present.
This package does not require any changes to GoDaddy or Zoho DNS.
