# Blue Fall

A 3D endless downhill ball-rolling game in one HTML file (three.js), with a VHS / neon synthwave look and a soundtrack generated live in the browser.

**Play:** open `index.html` in a browser (needs internet the first time, for fonts and the 3D library).

## What's here

| Path | What it is |
|---|---|
| `index.html` | The game. |
| `src/bluefall-source.html` | The same game without the `<html>/<head>` wrapper; the file changes are made on. |
| `songs/` | The built-in soundtrack rendered to MP3, plus "Deep Space Drive", an original long-form track. |
| `tools/` | Song renderers: `render.js` (all game songs), `render_one.js` (a single song). |
| `CONTINUE_HERE.md` | Every feature, how the code is organised, and how to keep working on it. |

## Features at a glance

- Endless mode (Endless, Time Attack, Chaos, Zen) and 8 levels, each with its own world, rules and song
- Momentum steering, jumps, boost pads, combos, 30+ trap types, trippy colour zones
- Showcase mode (can't die, drives itself), your own music per level
- Coins, cases with ball skins, trails and track colours, promo codes

All music here is original and made with the game's own sound engine.
