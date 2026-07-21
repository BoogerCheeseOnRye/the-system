# THE SYSTEM

A 3D orbital mechanics / solar system simulation built with Three.js. Start in low Earth orbit and fly to the stars.

## Controls

| Key | Action |
|---|---|
| W/S | Prograde / retrograde thrust |
| A/D | Radial in / out |
| Q/E | Normal / anti-normal (up/down) |
| Shift | Increase throttle +5% |
| Ctrl | Decrease throttle -5% |
| Space | Toggle full throttle |
| Drag | Look around |
| R | Roadster orbital view |
| Tab | Cycle focus objects (after Alcubierre tech) |
| Escape | Close panels / Exit roadster view |
| = / - | Speed up / slow down time |
| B | Build panel |
| T | Research panel |
| L | Launch panel |

Burn **prograde** (W) to raise orbit. Reach **escape velocity** to leave Earth's SOI and fly to other planets.

## Features

- **Orbital mechanics** — patched-conic gravity, elliptical orbits, periapsis/apoapsis, SOI transitions
- **Real star catalog** — 2,000 brightest naked-eye stars from the BSC5P catalog at actual 3D positions with real colors and magnitudes
- **Constellation lines** — auto-generated from angular proximity (visible as blue connecting lines)
- **Procedural textures** — Mercury (cratered), Venus (cloud swirls), Earth (land/ocean/ice/clouds), Mars (red with poles), Jupiter (bands + Great Red Spot), Saturn (bands), Uranus, Neptune, Pluto
- 10 planets with orbiting moons
- 27 nearby star systems with exoplanets
- 60,000-star spiral galaxy + 15,000 halo stars + globular clusters + nebula clouds
- 5,000 Starlink satellites, ISS, Hubble, GEO/GPS sats orbiting Earth
- Tesla Roadster (low-poly) in heliocentric orbit — press R for orbital camera
- Resource gathering (fly near glowing orbs), building, research, rocket launch mechanics
- Animated favicon (pulsing sun + orbiting planets)
- Procedural ambient audio + proximity-based planet tones

## How to run

Open `index.html` in any modern browser (serves locally, no build step). Requires Three.js loaded from CDN.

`bsc5p_3d_min.json` is the Bright Star Catalog 5th Edition — 9,000 stars with 3D positions, colors, and luminosities. Loaded via fetch at startup.
