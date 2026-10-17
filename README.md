# Ninefold

A Sudoku game in a single HTML file. Play the classic 9×9 grid, or a 3×3×3 **Cube** mode where every one of the nine slices across all three axes must hold 1–9.

## Features

- **Classic 9×9**, **Cube 3×3×3** and **Cube 4×4×4** modes (the 4×4×4 uses digits 1–16), four difficulty levels, unique-solution puzzles.
- **True 3D cube**: drag to turn it freely about its core, pinch or scroll to zoom, snap buttons for each side, a **Level** button to remove tilt, and an optional lock that freezes rotation while a cell is selected. The hidden centre cell has its own **Core** tile.
- Cube also available as **Flat** and **Stack** views.
- **Flat net**: a read-only view of your own cube folded and unfolded in 2D. It never reveals the solution.
- Sound on/off (header speaker or `M`): a chime for a right digit, a low buzz for a wrong one, synthesised in the browser. It never reveals more than the board does.
- **Fill notes** is a timed peek: it shows every legal candidate for 3 seconds, a limited number of times per puzzle (set per level, counted on the button). Your own notes are never touched.
- Notes, hints, undo/redo, last-cell auto-fill, mistake highlighting, puzzle codes, stats, light and dark themes.
- No dependencies and no tracking. Progress is saved in your browser's `localStorage`.

## Play

Open `index.html` in a browser, or use the GitHub Pages link for this repo. Fonts load from Google Fonts and fall back to system fonts offline.

## Licence

No licence specified yet; all rights reserved by the author until one is added.
