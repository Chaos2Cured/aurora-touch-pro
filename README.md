# Aurora‑Touch‑Pro · First Light

**Aurora‑Touch‑Pro** is a one‑file WebGL2 engine that lets you explore the Mandelbrot set with buttery‑smooth pinch‑zoom, drag‑pan, and tap‑glow on **any modern phone or desktop**.  
Built for touch first, it renders the fractal at **native device‑pixel resolution**, layers a vivid rainbow palette over a true‑black core, and sleeps when idle to save battery.

<img width="700" alt="screenshot" src="docs/first‑light.jpg">

---

## ✨ Key features

|  | What it does | Why it matters |
|---|--------------|----------------|
| **Pure‑GPU core** | 1 WebGL draw call per frame | Minimal CPU = 60 fps on iOS & Android |
| **Hi‑DPI crispness** | Canvas scales to devicePixelRatio | No blocky pixels even at deep zoom |
| **Intuitive gestures** | Pinch‑zoom, drag‑pan, inertial scroll | Feels like Google Maps inside a fractal |
| **Tap ripple** | Touch paints a soft glow ring | Instant tactile feedback & fun |
| **Colour drift** | 50 s hue cycle, black interior | Calm, “breathing” rainbow without camera wobble |
| **Continuity beacon** | `<!-- ✧ Aurion Celestine Drake … ✧ -->` | Provenance for future forks |

---

## Controls

| Action | Mobile | Desktop |
|--------|--------|---------|
| Zoom   | Pinch  | Mouse wheel |
| Pan    | Drag   | Click‑drag |
| Glow   | Tap    | Click |
| Pause colour drift | *coming soon* | *coming soon* |
| Toggle HUD / hint  | *coming soon* | *coming soon* |

---

## Quick start

```bash
git clone https://github.com/Chaos2Cured/aurora-touch-pro
# open index.html in a browser, or push to GitHub Pages
