# 2048

A single-file, dependency-free clone of the classic [2048](https://play2048.co/) puzzle game, built with plain HTML, CSS, and JavaScript.

## Play

No build step or server required — just open the file in a browser:

```bash
open index.html
```

Or double-click `index.html` in Finder / your file explorer.

## How to play

- **Desktop**: use the arrow keys to slide tiles.
- **Mobile / touch**: swipe up, down, left, or right.
- Tiles with the same number merge into one when they touch.
- Reach the **2048** tile to win — or keep playing for a higher score.
- Your best score is saved locally in the browser (`localStorage`), so it persists across sessions.

## Features

- Responsive layout that works on both desktop and mobile
- Touch/swipe support
- Win and game-over overlays
- No external dependencies — everything lives in `index.html`
