# Tanggal Tua Production Visual Assets

Save the three generated production assets directly into this folder (`public/assets/`):

1. `logo.jpg` (or `logo.png`) — Standalone Tanggal Tua logo lockup on pure white
2. `title-keyart.jpg` — Full-bleed 9:16 Kosan Gang Kancil twilight key art backdrop
3. `app-icon.jpg` (or `app-icon.png`) — Full-bleed 1:1 Magic Com App Store icon

Once saved, reload `npm run dev` — the Splash screen, Title screen, favicon, and Apple Touch Icon will automatically upgrade to the illustrated assets (with zero broken-image fallback if any file is omitted).

Optional: Run `python3 scripts/prep-assets.py` to generate a cropped transparent `logo.png` and resized `512x512` / `180x180` / `64x64` PNG icons.
