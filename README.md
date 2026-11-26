# 🎨 Kai Poster Lab — Generative Poster Maker

**Try it live → [hprince01.github.io/projects/poster-lab](https://hprince01.github.io/projects/poster-lab/)**

A creative-coding tool that **draws posters from code**. Pick a style and a palette, shuffle, add your own text and export a high-resolution PNG. Every poster comes from a **seeded random generator**, so the same seed always gives the same poster, and a link can share it exactly.

## Features
- **5 styles:** Orbits · Hills (Rwanda’s thousand hills) · Imigongo (Rwandan geometric art) · Flow field · Bauhaus
- **5 palettes:** Kai Violet, Umucyo, Kivu Dusk, Neon Night, Paper Mono
- **3 formats:** 4:5, 1:1, 9:16 (stories)
- Density and complexity sliders, custom title and subtitle, film grain, border, animation
- **Export:** 2160 px PNG (e.g. 2160×2700)
- **Copy link:** the URL stores every setting, so it reopens the exact poster
- History strip of recent posters; keyboard shortcuts (Space shuffle, S save, 1–5 styles)

## Built with
- Vanilla **JavaScript** + **HTML Canvas 2D**
- Seeded PRNG (mulberry32) and gradient **Perlin-style noise**, written from scratch
- No libraries, no build step

## Run it
Open `index.html` in a browser.

---
Designed & coded by **Prince Hirwa Rutagengwa · [Kai Labs](https://hprince01.github.io/)** — Kigali, Rwanda.
