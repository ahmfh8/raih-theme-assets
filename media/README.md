# media — RAIH default images (kept OUTSIDE the Salla theme package)

Compressed WebP (quality 75) from the handoff originals:
- `raih/hero-*-1600w.webp` (desktop) and `-800w.webp` (phone): hero slides, light and dark.
- `raih/category-*-400w.webp`: category tiles.

They are the defaults of the image fields in the theme editor (hero `slide_N_light/dark`, categories
`cat_N_image`), linked through jsDelivr with a fixed commit. Replacing an image in the editor uploads it
to Salla's CDN instead. Keep this folder (and the repo public) while any default is still in use.
