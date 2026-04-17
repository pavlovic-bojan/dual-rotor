# Single Rotor, Dual Magnet Sets — 3D Concept Visualization

**Live demo:** [pavlovic-bojan.github.io/dual-rotor](https://pavlovic-bojan.github.io/dual-rotor/)

Interactive 3D visualization of a **single rotor with two magnet sets and two Faraday cages**, built with Three.js.

## Concept

One rotor carries two independent sets of magnets:

- **Inner magnet set** — targets the inner stator, can operate as an electric motor
- **Outer magnet set** — targets the outer stator, can operate as a generator
- **Two Faraday cages** — isolate the active zones and block electromagnetic interference between stators

This architecture allows both stators to operate in different modes simultaneously on the same rotor, with electromagnetically isolated zones.

## Legend

| Element | Component |
| --- | --- |
| Dark grey part | Rotor — inner magnet set |
| Silver shell | Rotor — outer magnet set |
| Green bands | Two Faraday cages / isolation |
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