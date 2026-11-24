# WordForge — Multi Word Solver

A local-first, desktop-style word puzzle workspace. Open `index.html` in a modern browser; no build step, backend, account, or API key is required.

## Features
- Draggable floating tool windows; minimize, maximize, close, and desktop resizing.
- Dark/light theme toggle.
- Multi Word Solver: letter inventory, wildcard `?`, 3–12 letter length range, score sorting.
- Anagram Finder: exact-letter anagrams.
- Missing Letter Solver: `?` matches one letter.
- Word Length Filter: browse words by exact length.
- Scrabble-style letter scoring.
- Import/export a custom `.txt` dictionary (one word per line).

## Run
1. Extract the ZIP.
2. Open `index.html` in Chrome, Firefox, or Edge.
3. Open tools from the left rail or the desktop shortcuts.

## Dictionary coverage
The included built-in list is a compact starter dictionary for demonstrating and using the app. It is **not exhaustive** and should not be treated as an official tournament word authority. Import a larger trusted English word list using Dictionary Manager for broader coverage. Imported words remain in memory for the current browser session; export them if you want to keep a copy.

## Notes
- Word lists and solving run locally in your browser.
- Scrabble scores use standard English tile values; board bonuses and blank tiles are not applied.
- Google Fonts is optional; if offline, the app falls back to system sans-serif/monospace fonts.
