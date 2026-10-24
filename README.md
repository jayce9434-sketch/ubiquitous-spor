# Ring Duplication — Collision Chaos Edition

A flat, GitHub Pages-ready browser simulation.

## Features
- Circular ring and mounted hoop
- Balls duplicate every time they cleanly pass through the hoop
- Live ball counter and hoop-pass rate
- No artificial ball-count cap
- Real ball-vs-ball collisions with equal-mass momentum transfer
- Spatial-hash broadphase for much better collision performance than naive O(n²) checks
- Ball collision sounds, ring impact sounds, and duplication sounds
- Intentionally chaotic layered audio; only final peak limiting remains
- Touch/mouse controls and mobile-safe interaction
- No external libraries or assets

## Run
Open `index.html`, or upload `index.html` and this README to the root of a GitHub Pages repository.

## Controls
- Tap/click inside the ring: add a ball
- Space: add a ball
- R: reset
- Gear button: simulation controls
