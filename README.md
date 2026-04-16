# Dual Rotor — 3D Concept Visualization

**Live demo:** [pavlovic-bojan.github.io/dual-rotor](https://pavlovic-bojan.github.io/dual-rotor/)

Interactive 3D visualization of a **dual rotor system with a Faraday cage**, built with Three.js.

## Concept

The rotor is not a single active surface — it is split into two zones:

- **Inner zone** — targets the inner stator, can operate as an electric motor
- **Outer zone** — targets the outer stator, can operate as a generator
- **Faraday cage / magnetic break** — a protective barrier between the zones that blocks the influence of one stator on the other

This architecture allows the inner and outer stators to operate in different modes simultaneously, with mechanically and electromagnetically isolated zones.

## Legend

| Element | Component |
| --- | --- |
| Dark grey part | Inner rotor |
| Silver shell | Outer rotor |
| Green band | Faraday cage / isolation |
| Copper rings | Active zones facing the stators |
| Blue arrows | Inner stator magnetic field |
| Orange arrows | Outer stator magnetic field |

## Controls

- **Pause / Start** — pauses or resumes the animation
- **3D / Side / Front** — changes the camera angle
- **Explode** — separates components for a better view
- **Cross-section** — shows a cross-sectional cut of the system
- **Speed** — controls the rotation speed
- **Magnetic field** — toggles the magnetic field line visualization
- **Mouse** — drag to rotate, scroll to zoom

## Tech Stack

- [Three.js r128](https://threejs.org/)
- Vanilla HTML/CSS/JS — no build tools, runs directly in the browser
- Font: [Satoshi](https://www.fontshare.com/)

## Deployment

The project is automatically deployed to GitHub Pages on every push to the `main` branch, or manually via the GitHub Actions workflow.

---

© Bojan Pavlović 2026 — [LinkedIn](https://www.linkedin.com/in/pavlovicbojan-dev/)