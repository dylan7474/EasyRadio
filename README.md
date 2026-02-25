# EasyRadio

EasyRadio is a lightweight, fullscreen web radio player designed for simple, high-contrast listening.
It is implemented as a single static HTML page, with touch-friendly swipe navigation between categories and stations.

## What the application is

- A static, browser-based internet radio app.
- Focused on accessibility and readability with large text and high contrast colors.
- Organized into categories (Music, News, Science, Tech), each containing curated streaming stations.
- Optimized for simple interaction on touch devices and kiosks.

## Basic controls

- **Tap the large center button** to play or pause the current station.
- **Swipe left / right** to switch between categories.
- **Swipe up / down** to move between stations inside the current category.
- **Watch the status text** to see whether a station is loading, playing, paused, or has errors.
- **Use pagination dots** at the bottom/right as orientation hints for current category and station.

## Build and run instructions

EasyRadio is a static site and does not require a build step.

### Run locally

1. Clone the repository.
2. Open `index.html` directly in a modern browser, **or** serve the folder with a lightweight static server:

```bash
python3 -m http.server 8080
```

Then browse to:

```text
http://localhost:8080
```

### Deploy

The repository includes a `deploy.sh` helper script for deployment workflows.

## Short roadmap

- Add a simple station configuration file so station lists can be edited without touching core logic.
- Add optional favorites/presets for faster station access.
- Add a lightweight "now playing" metadata display when streams expose track information.
- Add keyboard navigation shortcuts for desktop accessibility.
- Add basic automated checks for HTML/CSS/JS formatting and regressions.
