To any person who believes vibecoded apps are lame, don't worry, I plan to turn this into a human-coded project whenever possible. This is just a school project.
# TESTRIS

TESTRIS is a Tetris clone with a dark neon aesthetic, built to feel fast and satisfying. It's got all the modern stuff — hold, combos, ghost piece, a 7-bag randomiser — wrapped in a UI inspired by TETR.IO.

This was assigned to me by my IT professor as a school project to put on my resume — so here it is.

> **Heads up — this is the offline release.** TESTRIS is meant to be played online at **[i still have to add the link]**, right in your browser, no download needed. This version is here if you want to play without an internet connection, run it locally, or poke around the source code.

---

## How to Play

If you're here for the offline version: download `testris.html`, double-click it, and you're in. No setup.

### Controls

These are the defaults. Everything is rebindable in Settings if you don't like them.

| Key | Action |
|-----|--------|
| `A` | Move left |
| `D` | Move right |
| `K` | Rotate counter-clockwise |
| `L` | Rotate clockwise |
| `S` | Soft drop |
| `Space` | Hard drop (instant lock + bonus points) |
| `W` | Hold / swap piece |

---

## What's in the Game

**Gameplay**
- Classic 10×20 grid with all 7 tetrominoes
- 7-bag randomiser, so you'll never go too long without the piece you need
- See the next 3 pieces coming up, and hold one in reserve for later
- Progressive gravity — things get faster as you level up
- Combo system with an animated meter on the side when you chain clears
- Clear 4 lines at once and you get a proper TETRIS flash

**Screens & UI**
- Home screen with an animated falling-blocks background
- Pick your starting level (1–15) before each game
- 3-2-1-GO! countdown to kick things off
- When you top out, the board dramatically cracks in half and flies off screen before showing your final score

**Settings**
- Rebind any control — if a key conflicts with one already in use, they swap automatically
- Volume and zoom sliders, because not everyone has the same screen or ears

**Audio**
- Every sound effect is synthesised on the fly using the Web Audio API — no audio files at all
- 
