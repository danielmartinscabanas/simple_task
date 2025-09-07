# SimpleTask: Minimal Client‑Side Checklist

SimpleTask is a tiny, no‑frills checklist you can open and use instantly.

## Objective:

- A very minimal client‑side checklist. No backend, no API calls, no accounts. It’s just a simple task manager you can use without friction. Data is kept locally in your browser (localStorage) and never leaves your device.

## Why it exists

- Created by Daniel Cabanas, frustrated by the lack of truly simple, free checklists that don’t store or use your data without need or consent.

## Features

- Add tasks (press Enter), mark done/undone, remove tasks.
- Two sections: “Do” and “Done” (Done section hides when empty).
- Live drag‑and‑drop reordering in the “Do” section; order is persisted.
- Export tasks as a URL for fast sync; opening the URL on another device imports the tasks and redirects back to the app.
- Light/Dark theme toggle.
- Mobile‑friendly sizing; 100% client‑side — no servers or endpoints.
- Installable PWA on mobile/desktop with offline support.

## Usage

- Open `https://danielmartinscabanas.github.io/simple_task/` in your browser and start typing. Use the header buttons to toggle theme or export.
- To sync: click Export to get a shareable URL. Open that URL on another device; it will load the tasks and route back to the app automatically.

## PWA

- The app includes a `manifest.webmanifest` and a `sw.js` service worker. When hosted at `https://danielmartinscabanas.github.io/simple_task/`, modern browsers will offer “Install app”.
- The service worker caches core assets for offline use. After making changes, bump `CACHE_NAME` in `sw.js` to force an update.

## License

- Free forever and for all.

I hope you enjoy it as much as I do!
