# Ghoul Duel 👻

A single-file, zero-dependency remake of the gameplay from Google's 2018 "Great Ghoul Duel" Halloween Doodle — pixel art, sound, and code all built from scratch. You play as the only human on a team of ghosts against a rival team of bots.

**Play it:** open `index.html` in any modern browser. No build step, no server, no dependencies.

## How to play

- **Move:** WASD / arrow keys, or hold the mouse to fly toward the cursor
- **P** to pause · **M** to mute
- Collect **spirit flames** scattered around the map — they trail behind you
- Fly through a **rival's trail** to steal their flames (and guard your own!)
- **Bank** your flames by carrying them back to your team's base
- Most flames banked in **2:00** wins

### Team unlocks

Banking flames earns your whole team upgrades:

| Flames banked | Unlock |
|---|---|
| 15 | ⚡ Speed boost |
| 35 | 👁️ Night vision (bigger view through the fog) |
| 60 | 🧲 Magnetism (nearby flames drift toward you) |

## Features

- 4v4 match: you + 3 bot teammates vs 4 rival bots, each with their own collect/chase/return AI
- Procedurally generated symmetric maps (validated with BFS so every match is fully traversable)
- Fog of war centered on your team
- All pixel art drawn procedurally on canvas, including a custom 5×5 bitmap font
- All sound synthesized at runtime with the Web Audio API — no audio files
- Respects `prefers-reduced-motion`

## Tech

One HTML file, vanilla JavaScript, `<canvas>` 2D. That's it.

## Disclaimer

This is an original fan tribute to the *gameplay* of Google's 2018 "Great Ghoul Duel" Halloween Doodle. All art, code, and sound in this project are original — nothing was taken from the Doodle itself. This project is not affiliated with or endorsed by Google.

## License

[MIT](LICENSE)
