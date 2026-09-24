# test-media — DELETE BEFORE LAUNCH

Temporary test file for the RAIH vertical video section (preview only):

- `raih-reel-test.mp4` — 720×1280, H.264 High, 30 fps, 8 s, ~0.6 MB, faststart, no audio.
- `raih-reel-test.webp` — its first frame (poster).

Made from RAIH's own handoff image (`real-scooter-road.webp`, slow zoom), so no third-party licence.
Production videos will be hosted on Bunny.net. Before launch: delete this folder, remove the
test defaults in `src/views/components/home/raih-reels.twig`, and the `test-media` exception in
`scripts/sync-assets.mjs` (raih-theme).
