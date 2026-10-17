# VCOP Product Demo

**Live 3D product demo for VCOP Pte Ltd — Valued Committed Office Partners**

▶ **Open the demo:** https://tzuchi-singapore.github.io/VCOP-Product-Customisable-Demo/

An interactive, browser-based 3D showcase that brings two VCOP furniture designs to life, built directly from the original design blueprints. It runs on any modern phone, tablet or computer — no app or plug-in needed.

---

## Products

### 1. BLOCKS Smart Lockset — Demo Kit
4 locker compartments + 1 tech compartment · 600 W × 450 D × 468 H mm

- Unlock any locker with **RFID card**, **face recognition** or **PIN** — watch the bolt release the door's 'C' hook and the door swing open
- "Wrong card" demo showing access denied
- Removable 18 mm compact-laminate lid and raisable lockboard / PCB tray
- Blueprint options: recessed or metal-rod handle; hinges or pin hinges
- iPad control panel and RFID reader with live screens and status lights

### 2. BNP Paribas Trader Desk
1500 × 950 mm module · qty 44 sets

- Working height controller (hold ▲ ▼ or memory 1 / 2 / 3) driving 3-stage lifting columns from 680 to 1250 mm
- Cable spines that stretch with the desk; motor hum and status light
- Perforated cabinet doors and retractable CPU holder tray
- 4, 6 or 8 live trading screens; single module or back-to-back pair

## Features

| Feature | Description |
|---|---|
| ▶ Play show | Full-screen, narrated cinematic tour: hero reveal, close-up shots with callouts on each mechanism, exploded view, colour changes and an end card. Pause, skip scenes, voice on/off |
| 360° view | Drag to rotate in any direction, pinch / scroll to zoom, preset views (3/4, front, side, top, back) |
| Exploded view | One toggle separates every component and labels it |
| Finishes | Change each component's material and colour: HPL, FENIX NTM®, woodgrain, Polykem, RAL powder-coat, metal finishes |
| Specs | Full specification taken from the blueprints |
| Blueprints | Original drawings with zoom, plus the PDF |
| Renders | Photoreal concept renders (generated with Higgsfield) |
| Light / dark studio | Two showroom lighting moods; sound effects on/off |

## How to use

1. Press **▶ Play show** for the guided, narrated tour — or choose **BLOCKS Smart Lockset** or **Trader Desk** at the top.
2. Use the **Live demo** tab to run the mechanisms — or tap a door, the reader, the iPad or the desk controller directly in 3D.
3. Turn on **Exploded view** to see inside.
4. Use **Finishes** to try materials and colours, **Specs** for dimensions, and **Blueprint** for the original drawings.

## Project structure

```
index.html        The whole app (HTML, CSS, JavaScript)
vendor/           three.js 3D engine (r160) and add-ons
assets/           VCOP logo and photoreal renders
blueprints/       Original blueprints (JPG preview + PDF)
```

Static website — no build step. Hosted on GitHub Pages from the `main` branch.

## Credits

- Product design and blueprints: **VCOP Pte Ltd**, 1557 Keppel Road, #02-03, Singapore 089066 · Tel 6338 9822
- Interactive demo: Daniel Phua
- 3D engine: [three.js](https://threejs.org) (MIT License)
- Fonts: [Manrope](https://fonts.google.com/specimen/Manrope) and [JetBrains Mono](https://fonts.google.com/specimen/JetBrains+Mono) (SIL Open Font License)
- Concept renders: generated with [Higgsfield](https://higgsfield.ai)

## Disclaimer

This is a visual demonstration. 3D models are representations based on concept blueprints; final dimensions, materials, finishes, hardware and mechanisms are subject to confirmation in production drawings. Colours on screen may differ from physical samples. BNP Paribas is named only as the project client; trading screens show simulated data. FENIX NTM® and other trademarks belong to their respective owners.

## License

© 2026 VCOP Pte Ltd. All rights reserved. See [LICENSE](LICENSE).
