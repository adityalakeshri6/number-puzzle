# 2048 - Number Puzzle

A browser version of the classic 2048 sliding tile puzzle. Merge matching
numbers to build up to 2048 (and beyond, if you keep going after you hit it).

## Play it

Open `index.html` in any browser, or check the live link if it's up on
GitHub Pages.

**Controls:**
- Arrow keys (desktop)
- Swipe / click-drag on the board
- On-screen arrow buttons (works everywhere, including trackpads)

Your best score is saved in the browser so it sticks around between visits.

## Files

```
number-puzzle/
├── index.html      -> the whole game, HTML/CSS/JS in one file
├── README.md
├── LICENSE
└── .gitignore
```

There's no build step or dependencies - it's a single static file, so it
deploys straight to GitHub Pages with nothing else needed.

## How it works

Each swipe/press slides every tile as far as it can go in that direction,
merging equal tiles that collide (2+2 becomes 4, and so on). A new tile
(2 or 4) spawns in a random empty cell after every move that actually
changes the board. Game ends when the grid is full and no more merges
are possible in any direction.

## License

MIT, see LICENSE file.
