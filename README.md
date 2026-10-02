# 3D Runner Game

A fast-paced 3D endless runner game built with **Three.js**, playable entirely in the browser — no install, no build step.

## Features

- 3D endless runner with smooth forward motion and obstacle dodging
- Lateral movement controls for precise steering
- Score tracking with animated SVG score overlay
- Restart support — jump back in instantly after a crash
- Sound effects for a more immersive run
- Fullscreen responsive canvas, works on desktop and mobile viewports

## Tech Stack

- HTML5 / CSS3 / JavaScript (single-file game)
- [Three.js](https://threejs.org/) (v0.146.0 via CDN) for 3D rendering

## Quick Start

1. Clone the repo:
   ```bash
   git clone https://github.com/girishlade111/3D-runner-game.git
   cd 3D-runner-game
   ```
2. Open `index.html` directly in a browser, or serve it locally:
   ```bash
   npx serve .
   ```
3. Use the on-screen instructions / arrow keys to steer, dodge obstacles, and chase a high score.

## Project Structure

```
3D-runner-game/
├── index.html        # The full game (playable)
├── 3D runner.html    # Original game file
├── LICENSE
└── README.md
```

## Deploy Notes

Static site with zero build requirements — the game runs from `index.html` and pulls Three.js from a CDN. Deployed via GitHub Pages from the `main` branch.

## License

See [LICENSE](LICENSE).

---

Built by Girish Lade — https://ladestack.in
