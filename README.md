# D-Sewhuk Personal Dashboard

A dark, minimal personal productivity dashboard hosted via GitHub Pages. Built with plain HTML, CSS, and JavaScript — no frameworks, no backend, no dependencies.

## Live Site

[https://d-sewhuk.github.io/-D-Sewhuk.github.io/](https://d-sewhuk.github.io/-D-Sewhuk.github.io/)

## Features

- **Ambient Clock** — Live time updated every second with a greeting that changes based on time of day (morning / afternoon / evening)
- **Ambient Background** — Full-screen background that subtly shifts color temperature throughout the day (dawn, day, dusk, night)
- **Weather Widget** — Current temperature and conditions via the [Open-Meteo API](https://open-meteo.com/) using browser geolocation (no API key required)
- **Notes** — Multi-tab notepad with auto-save to `localStorage`
- **Gym Tracker** — GitHub-style activity heatmap for the past year, personal records (PR) table with editable lifts, and current/longest streak counters
- **Calendar** — Monthly calendar view with click-to-add events, month navigation, all stored in `localStorage`
- **Daily To-Do** — Task checklist that automatically resets each new day
- **Word of the Day** — Rotates daily through a curated list of interesting words with definitions and examples

## Tech Stack

| Layer | Details |
|---|---|
| Frontend | HTML5, CSS3, Vanilla JavaScript |
| Storage | `localStorage` (fully offline except weather) |
| Weather API | [Open-Meteo](https://open-meteo.com/) — free, no key needed |
| Hosting | GitHub Pages |
| Font | [Space Grotesk](https://fonts.google.com/specimen/Space+Grotesk) via Google Fonts |

## Local Development

No build step required. Just open the file directly in your browser:

```bash
# Clone the repo
git clone https://github.com/D-Sewhuk/-D-Sewhuk.github.io.git

# Open in browser
open index.html
```

Or serve it locally:

```bash
npx serve .
```

## Deployment

Pushes to `main` automatically deploy via GitHub Pages.

```bash
git add .
git commit -m "your message"
git push
```

---

Built by [D-Sewhuk](https://github.com/D-Sewhuk)
