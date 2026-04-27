# Dual-Rotor Motor — Vizualizacija Koncepta

**Live demo:** [pavlovic-bojan.github.io/rotor](https://pavlovic-bojan.github.io/rotor/)

Interaktivna 3D vizualizacija koncepta **dual-rotor elektromotora sa dva Faradejeva kaveza**, izrađena pomoću Three.js.

## Koncept

Motor koristi dva koncentrična rotora od ne-fero materijala smeštena unutar jednog fiksnog statora. Svaki rotor nosi set naizmeničnih N/S magneta i izolovan je sopstvenim Faradejevim kavezom. Oba rotora su mehanički spojena na istu osovinu — momenti sile se sabiraju.

### Raspored slojeva — od spolja ka unutra

| Sloj | Element | Status |
|---|---|---|
| r = 2.02 | Stator — cilindrični okvir | fiksno |
| r = 1.94 | Namotaji — bakarni, 24 kom. | fiksno |
| r = 1.16 | Spoljašnji Faradejjev kavez | fiksno |
| r = 1.50 | Spoljašnja ne-fero ljuska | rotira |
| r = 1.35 | Spoljašnji magneti — 14 kom. N/S | rotira |
| r = 1.16 | Spoljašnji Faradejjev kavez | fiksno |
| r = 0.86 | Unutrašnja ne-fero ljuska | rotira |
| r = 0.70 | Unutrašnji magneti — 14 kom. N/S | rotira |
| r = 0.50 | Unutrašnji Faradejjev kavez | fiksno |
| r = 0.22 | Osovina | rotira |

### Zašto ne-fero materijal?

Ne-fero materijal rotora eliminiše reluktantne gubitke koji nastaju u ferromagnetnim jezgrima. Magnetni fluks prolazi direktno do magneta bez dodatnih gubitaka u materijalu.

### Uloga Faradejevih kaveza

Svaki kavez je električki provodna ljuska koja blokira visokofrekventne indukovane struje između susjednih slojeva. Spoljašnji kavez štiti spoljašnji rotor od elektromagnetnih smetnji statora; unutrašnji odvaja dva rotorska sloja i štiti unutrašnji rotor od uticaja spoljašnjeg.

## Legenda

| Boja / Element | Komponenta |
|---|---|
| Sivi cilindar (spolja) | Stator |
| Bakarne kocke uz stator | Namotaji — fiksno |
| Zeleni prsten (spolja, r=1.16) | Spoljašnji Faradejjev kavez |
| Bež ljuska + plavi/bakar blokovi (sp.) | Spoljašnji rotor + N/S magneti |
| Zeleni prsten (unutra, r=0.50) | Unutrašnji Faradejjev kavez |
| Bež ljuska + plavi/bakar blokovi (un.) | Unutrašnji rotor + N/S magneti |
| Siva osovina | Zajednička osovina |
| Narandžaste strelice | Linije magnetnog polja |

## Kontrole

- **Pauza / Pokreni** — pauzira ili nastavlja animaciju rotora
- **3D / Bočni / Prednji presek** — menja ugao kamere
- **Explode** — razdvaja sve slojeve duž ose radi pregleda
- **Presek** — prikazuje poprečni presek sistema (uklanja 1/4 materijala)
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
