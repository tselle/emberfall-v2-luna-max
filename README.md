# Emberfall: The Emberwild Saga

A self-contained, offline-friendly fantasy RPG inspired by late-1980s party-based adventure games. Open `index.html` in a recent browser to play; no install, build step, server, account, or network connection is required. For LAN play, run `python3 -m http.server 8000` from this directory and open `http://localhost:8000`.

This is an **unofficial, non-commercial fan project**. It is not endorsed by, affiliated with, or a licensed product of any tabletop or computer-game publisher.

## Play

- Choose a chapter or one of fifty seeded expeditions, then assemble up to six adventurers.
- Explore town and dungeon maps in first person, travel the wilderness, and fight on a tactical isometric board.
- Use the command bar or keyboard: **W/↑** forward, **S/↓** back, **A/←** and **D/→** turn, **Q/E** strafe, **F** search, **R** camp. In the wilderness, **W/A/S/D** move north/west/south/east and **Q/E/Z/C** move diagonally.
- **P** opens the party drawer; **1–6** open character sheets; **M** map; **J** journal; **B** bestiary; **Esc** menu. In combat, click a tile to move, an enemy to attack, and use the action bar to cast, use items, end a turn, or flee.
- Report finished commissions at a hall, rest at an inn or camp, and train eligible adventurers. Saves are stored locally in browser storage on the current device and origin.

Keyboard controls are optional: the on-screen command bar and touch pad support touch-only play. Use the ✥ control to cycle the pad's placement.

## Files

- `index.html` — static shell and ordered classic scripts
- `css/style.css` — responsive interface
- `js/` — rules, content, generated adventures, rendering, UI, combat, exploration and saves
- `emberfall-astra-max.md` — reconstruction specification
- `LICENSE` — MIT License

The artwork is procedural Canvas 2D drawing; no external assets or fonts are loaded.
