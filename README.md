<div align="center">

# ◈ TEARABLE

**A hyper-realistic cloth simulation running in your browser.**  
Powered by WebGL + GLSL shaders. 20 unique websites. Tear, burn, cut, explode.

[![Live Demo](https://img.shields.io/badge/LIVE%20DEMO-dxrkmonteva.github.io-a78bfa?style=for-the-badge&labelColor=0a0a0f)](https://dxrkmonteva.github.io/tearable-cloth)
[![Made with WebGL](https://img.shields.io/badge/WebGL-GLSL%20Shaders-38bdf8?style=for-the-badge&labelColor=0a0a0f)](https://github.com/dxrkmonteva/tearable-cloth)
[![License](https://img.shields.io/badge/License-MIT-34d399?style=for-the-badge&labelColor=0a0a0f)](LICENSE)

---

![TEARABLE Preview](https://via.placeholder.com/900x500/0a0a0f/a78bfa?text=◈+TEARABLE)

</div>

---

## ✦ What is this?

**TEARABLE** is a real-time cloth physics simulation rendered on a WebGL canvas.  
Each "cloth" is a fully interactive website texture stretched over a **90×80 point mesh** (7,200 points, 14,000+ constraints).

Tear it. Burn it. Cut it. Watch it fall.  
When destroyed — a new site appears. 20 unique designs. Loops forever.

---

## ⚡ Features

### 🎮 Interaction Tools
| Tool | Description |
|------|-------------|
| ✦ Grab | Drag the cloth with your finger/cursor |
| ✂ Cut | Slice through cloth like scissors |
| ◎ Push | Repel cloth from cursor |
| ✿ Pull | Attract cloth toward cursor |
| 🔥 Fire brush | Draw fire directly onto the cloth |
| 📌 Pin | Pin/unpin individual points |
| ❄ Freeze | Freeze points in place |
| ✦ Attract | Magnetic attraction to cursor |
| 💥 Explode brush | Blow up sections of cloth |

### 🌪 Forces & Effects
| Effect | Description |
|--------|-------------|
| ≋ Wind | Sinusoidal wind simulation |
| ▲ Fire | Auto-ignites cloth from bottom |
| ↕ Flip Gravity | Reverses gravity direction |
| ⚡ Storm | Chaotic wind + lightning + rain |
| 🌀 Vortex | Cloth spirals into center |
| 〜 Wave | Vertical wave oscillation |
| ⏳ Slow-Mo | 3× time dilation |
| ▓ Glitch | VHS/digital artifact effect |
| ❄ Snow | Snowfall particle system |
| ◑ Night | Dark mode filter |
| ◉ Rainbow | Prismatic color overlay |
| ⊕ Magnet | Mouse becomes magnetic |
| ● Black Hole | Gravity well follows cursor |
| ↩ Time Reverse | Rewinds cloth physics |

### 🎨 Shader Pipeline
- **Vertex shader** — Verlet integration, constraint solving
- **Fragment shader** — Texture mapping with burn distortion, rainbow overlay, noise wrinkle
- **Particle shader** — Point sprites for fire, sparks, smoke, rain, snow, lightning
- **Post-process shader** — Chromatic aberration, vignette, scanlines, film grain, glitch

### 🌐 20 Website Textures
```
01. VOID          — Tech startup
02. NEXUS         — Social media feed  
03. LUXE          — E-commerce store
04. CHRONICLE     — News site
05. PORTFOLIO     — Designer portfolio
06. DASHBOARD     — Analytics panel
07. WAVE          — Music streaming
08. WEATHER       — Weather app
09. GRIDLOCK      — Gaming platform
10. CHAIN         — Crypto exchange
11. VOYAGE        — Travel booking
12. MUNCH         — Food delivery
13. MEDIC         — Healthcare
14. LEARN         — E-learning
15. HAVEN         — Real estate
16. PULSE         — Fitness app
17. FRAME         — Photography
18. NOTES         — Productivity
19. SYNAPSE       — AI platform
20. MERIDIAN      — Magazine
```

---

## 🚀 Physics

- **7,200 points** (90×80 mesh)
- **14,000+ constraints** (Verlet integration)
- **22 solver iterations** per frame
- **Real-time fire spread** with burn timer per point
- **Particle systems**: fire, sparks, smoke, rain, snow, lightning
- **Time reversal buffer**: 180 frames stored
- **Auto-transition**: new site loads when cloth is 82% destroyed

---

## 🛠 Tech Stack

```
Rendering     WebGL 1.0 + GLSL ES 1.0
Physics       Verlet Integration (JS)
Textures      HTML5 Canvas 2D → WebGL texture
Particles     GPU point sprites
Post-FX       Framebuffer → post-process pass
Hosting       GitHub Pages
```

---

## 📦 Project Structure

```
tearable-cloth/
├── index.html    ← Everything. One file. No dependencies.
├── README.md
└── LICENSE
```

Zero dependencies. Zero build step. Just open and tear.

---

## 🎯 Controls

| Action | Desktop | Mobile |
|--------|---------|--------|
| Interact | Click + Drag | Touch + Drag |
| Multi-touch | — | Supported |
| Reset | Double-click | Double-tap |
| Next site | → next button | → next button |

---

<div align="center">

Made with 🔥 by **dxrkmonteva**  
*Built entirely on a phone. No PC. No excuses.*

</div>
