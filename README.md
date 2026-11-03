# Neon Block Puzzle

A neon-styled block puzzle game that runs in the browser as a single HTML file. No installs, no build step, no external libraries.

## How to Play

1. Drag a piece from the tray at the bottom onto the 8x8 board.
2. Fill a complete row or column to clear it.
3. Clear several lines with one piece for bigger combos and bonus points.
4. When none of the remaining pieces fit on the board, the game is over.

Pieces cannot be rotated, so plan your placements carefully. When all three pieces in the tray are placed, a new set appears.

## Scoring

- Every placed block earns 1 point.
- Each cleared line earns a bonus of 10 x lines x lines, so clearing 2 lines at once scores far more than clearing 2 separately.
- Clearing more than one line at once triggers a COMBO popup.
- Your high score is saved in the browser (localStorage) and persists between visits.

## Features

- Canvas-rendered glowing blocks with particle bursts, screen shake and flash effects
- Mouse and touch support (touch drags lift the piece above your finger so it stays visible)
- Live placement preview showing where the piece will land
- Responsive layout that scales to desktop and mobile screens
- Automatic high score saving
- Game over screen with a restart button
- Reduced-motion support for UI transitions

## Run Locally

Open `block-puzzle.html` in any modern browser. That's all.

## Deploy

Upload the HTML file to any static host, for example:

- GitHub Pages
- Netlify (drag and drop)
- Vercel
- Any web server

If you host it as `index.html`, it will load at the root URL.

## Tech

- HTML5 Canvas 2D
- Vanilla JavaScript (ES6+), no dependencies
- CSS with glassmorphism-style panels

## Browser Support

Works in current versions of Chrome, Edge, Firefox and Safari, on desktop and mobile.

## License

Free to use and modify..
