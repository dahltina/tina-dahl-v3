# Tina Dahl — Portfolio v1

Astro starter matching the approved dark portfolio direction.

## Run locally
1. Install Node 20+
2. `npm install`
3. `npm run dev`

## Before publishing
- Put `BTBjorvika-Regular.woff2` in `public/fonts/`.
- Replace `hello@example.com` in Header/About.
- Add hero files: `public/video/hero-desktop.mp4` and `hero-mobile.mp4`.
- Add Villa Maia films as `maia-film-01.mp4` and `maia-film-02.mp4`.
- Replace placeholder JPGs with final exports.
- Change `site` in `astro.config.mjs` to the final domain.

## Projects
Edit `src/data/projects.js`. The first five slots are already set up: Villa Maia, Studio Forma, The Fig Lobby, Suom, and Chiang Mai Stay. Project detail pages can follow `src/pages/projects/villa-maia.astro`.

## Netlify
Connect the GitHub repo to Netlify. Build command: `npm run build`; publish directory: `dist`. `netlify.toml` already contains this.
