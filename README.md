# Rotor (Ne-fero) + Magneti — 3D Vizualizacija Koncepta

**Live demo:** [pavlovic-bojan.github.io/rotor](https://pavlovic-bojan.github.io/rotor/)

Interaktivna 3D vizualizacija koncepta **rotor od ne-fero materijala sa magnetima ugrađenim u zidu**, izrađena pomoću Three.js.

## Koncept

Prednji presek mašine (od spolja ka unutra):

- **Stator** — spoljašnji prsten sa namotajima na unutrašnjoj strani
- **Faradejjev kavez** — jedan prsten koji izoluje rotor od statora
- **Rotor** — pun cilindar od ne-fero materijala
- **Magneti** — ugrađeni u zidu rotora (naizmenično N/S)
- **Osovina** — centralna osovina

Ne-fero materijal rotora eliminiše reluktantne gubitke. Faradejjev kavez blokira parazitske struje i obezbeđuje čist magnetni signal između statora i rotora.

## Legenda

| Element | Komponenta |
| --- | --- |
| Sivi cilindar (spolja) | Stator — namotaji unutra |
| Zeleni prsten | Faradejjev kavez |
| Bež/tan cilindar | Rotor — ne-fero materijal |
| Plavi i bakarnasti blokovi | Magneti u zidu rotora (N/S) |
| Narandžaste strelice | Linije magnetnog polja |

## Kontrole

- **Pauza / Pokreni** — pauzira ili nastavlja animaciju
- **3D / Bočni / Prednji presek** — menja ugao kamere
- **Explode** — razdvaja komponente radi boljeg pregleda
- **Presek** — prikazuje poprečni presek sistema
- **Brzina** — kontroliše brzinu rotacije
- **Magnetno polje** — uključuje/isključuje vizualizaciju linija polja
- **Miš** — prevuci za rotaciju, scroll za zoom

## Tech Stack

- [Three.js r128](https://threejs.org/)
- Vanilla HTML/CSS/JS — bez build alata, pokreće se direktno u browseru
- Font: [Satoshi](https://www.fontshare.com/)

## Deployment

Projekat se automatski deplojuje na GitHub Pages na svaki push na `main` granu.

---

© Nenad Djokić 2026 — Developed by [Bojan Pavlović](https://www.linkedin.com/in/pavlovicbojan-dev/)
