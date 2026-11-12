# Personal Dashboard

A single-page personal dashboard: India/Germany world clock with shared working hours, weather, calendar week (KW), a retro 48×16 black-and-cyan pixel display (custom text with live tokens, or a binary image), kanban, calendar, pomodoro timer, daily focus, notes and focus-session stats.

No build step, just open `index.html`.

## Sync
Data is saved in the browser and synced to a **secret GitHub Gist** (Settings ⚙):
1. Create a classic token with only the `gist` scope.
2. Paste it and leave Gist ID empty the first time; a secret gist is created.
3. On other devices, use the same token and Gist ID.

The token is stored only in your browser, never in this repository. Use **Export JSON** for an extra backup.

## APIs used
- Weather: [Open-Meteo](https://open-meteo.com) (no key)
- Drag and drop: [SortableJS](https://sortablejs.github.io/Sortable/)
