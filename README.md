# Dual Rotor — 3D Vizualizacija Koncepta

**Live demo:** [pavlovic-bojan.github.io/dual-rotor](https://pavlovic-bojan.github.io/dual-rotor/)

Interaktivna 3D vizualizacija koncepta **dual rotor sistema sa Faradejevim kavezom**, izrađena u Three.js.

## Koncept

Rotor nije jedna aktivna površina — podjeljen je na dve zone:

- **Unutrašnja zona** — cilja unutrašnji stator, može raditi kao elektromotor
- **Spoljašnja zona** — cilja spoljašnji stator, može raditi kao generator
- **Faradejev kavez / magnetni prekid** — zaštitni pojas između zona koji blokuje uticaj jednog statora na drugi

Ova arhitektura omogućava da unutrašnji i spoljašnji stator rade u različitim režimima istovremeno, sa mehanički i elektromagnetno izolovanim zonama.

## Legenda

| Boja / element | Komponenta |
| --- | --- |
| Tamno sivi deo | Unutrašnji rotor |
| Srebrni omotač | Spoljašnji rotor |
| Zeleni pojas | Faradejev kavez / izolacija |
| Bakarnasti prstenovi | Aktivne zone prema statorima |
| Plave strelice | Magnetno polje unutrašnjeg statora |
| Narandžaste strelice | Magnetno polje spoljašnjeg statora |

## Kontrole

- **Pauza / Pokreni** — pauzira ili nastavlja animaciju
- **3D / Bočni / Prednji** — menja ugao pogleda
- **Explode** — rastavlja komponente za bolji pregled
- **Presek** — prikazuje poprečni presek sistema
- **Brzina** — kontroliše brzinu rotacije
- **Magnetno polje** — prikazuje / skriva vizualizaciju magnetnih linija
- **Miš** — drag za rotaciju, scroll za zoom

## Tehnologije

- [Three.js r128](https://threejs.org/)
- Vanilla HTML/CSS/JS — bez build toolova, radi direktno iz browsera
- Font: [Satoshi](https://www.fontshare.com/)

## Deploy

Projekat se automatski deployuje na GitHub Pages pri svakom push-u na `main` granu, ili ručno pokretanjem GitHub Actions workflow-a.

---

© Bojan Pavlović 2026 — [LinkedIn](https://www.linkedin.com/in/pavlovicbojan-dev/)