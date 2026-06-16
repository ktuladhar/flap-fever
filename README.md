# 3D Super Bird

A pretty, playable, web-based 3D arcade flapping game. It reimagines the classic tap-to-fly gameplay in a polished 3D scene with smooth controls, attractive lighting, and a browser-first experience.

## Live demo

**[Play 3D Super Bird →](https://ktuladhar.github.io/3d-super-bird/)**

Open the link in a modern browser with WebGL enabled. No install required.

> If the page is not live yet, enable GitHub Pages once: repo **Settings → Pages → Build and deployment → Source: GitHub Actions**, then re-run the [Deploy to GitHub Pages](https://github.com/ktuladhar/3d-super-bird/actions/workflows/deploy-pages.yml) workflow.

## Getting started

1. Open `index.html` in a modern browser (Chrome, Edge, Firefox, or Safari).
2. Make sure you have an internet connection — the game loads Three.js from a CDN.
3. WebGL must be enabled (it is on by default in most browsers).

You can double-click the file to open it locally, or serve the folder with any static file server if you prefer.

## How to play

**Goal:** Guide the bird through the gaps in the green pipes without hitting the pipes, the ground, or the ceiling. Each pipe you pass adds one point. The game speeds up as your score increases.

### Controls


| Input          | Action |
| -------------- | ------ |
| Tap or click   | Flap   |
| Space, ↑, or W | Flap   |


### Game flow

1. **Title screen** — The bird bobs in place. Tap, click, or press Space to start.
2. **Playing** — Keep flapping to stay airborne and fly through each gap. Your score appears at the top of the screen.
3. **Game over** — After a crash, your score and session best are shown. Tap or click again to play again.

### Tips

- Short, well-timed flaps work better than mashing the button.
- The bird tilts with its movement — use that as a cue for when to flap next.
- Your best score is kept in memory for the current session and resets when you reload the page.

