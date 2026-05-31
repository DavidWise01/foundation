# Foundation

[![License: CC-BY-ND-4.0](https://img.shields.io/badge/License-CC--BY--ND--4.0-lightgrey?style=flat-square)](LICENSE)
[![Series: 4](https://img.shields.io/badge/series-4-b8862b?style=flat-square)](#)
[![Volumes: 21](https://img.shields.io/badge/volumes-21-1f4ea8?style=flat-square)](#)
[![GitHub Pages](https://img.shields.io/badge/pages-live-0f6e6a?style=flat-square)](https://davidwise01.github.io/foundation/)

> *From the first words ever signed to a name, to the first algorithm, to the physics of the invisible cage, to the bench where things are made.*

Four series on the figures and ideas that built the world. Each is a complete visual learning series — animated SVG diagrams, primary sources, card-based information architecture. Self-contained HTML. No framework, no build step, no server.

---

## The Four Series

### Enheduanna · 2300 BCE · Sumer
`series/enheduanna/` — 4 volumes

High Priestess of Ur. Daughter of Sargon of Akkad. The world's first named author. She signed her name to the *Exaltation of Inanna* and 42 Temple Hymns in cuneiform, 4,300 years before this sentence was written. Her alabaster disk was excavated from beneath the ruins of Ur in 1927. The first complete English translation appeared in 2023.

| # | Title |
|---|-------|
| 0 | Who She Was |
| 1 | Her Works |
| 2 | Her World |
| 3 | Her Long Afterlife |

---

### Ada Lovelace · 1815–1852 · London
`series/ada-lovelace/` — 4 volumes

Byron's daughter. Raised on mathematics as a deliberate counter-inheritance. In 1843 she translated Menabrea's paper on Babbage's Analytical Engine and added Notes seven times longer than the original — including Note G, the first algorithm ever written. She understood, a century before Turing, that a calculating machine could manipulate *any symbol*, not just numbers. She died at 36.

| # | Title |
|---|-------|
| 0 | Who She Was |
| 1 | Her Work (the Notes) |
| 2 | Her World |
| 3 | Her Long Afterlife |

---

### Faraday · 1836 · London
`series/faraday/` — 4 volumes

A metal shell makes its interior electrically invisible. Michael Faraday lined a room with metal foil in 1836 and proved it — standing inside and observing zero field while lightning-like discharges played across the outside. That principle now lives inside every coaxial cable, every MRI room, every microwave oven door, every anti-static bag.

| # | Title |
|---|-------|
| 0 | The Idea |
| 1 | Build a Faraday Cage |
| 2 | Shielding at Work |
| 3 | The Field Inside |

---

### The Workbench · Ongoing
`series/workbench/` — 8 pamphlets + 1 field manual

The living tradition. Eight pamphlets covering the components and concepts that connect theory to light, motion, and signal: small motors, electromagnets and solenoids, sensors, microcontrollers, power and batteries, parts, tools and the bench itself. Plus a complete field manual on the Slayer Exciter.

| Vol | Title |
|-----|-------|
| index | Start Here — Series Overview |
| 2 | Small Motors |
| 3 | Electromagnets & Solenoids |
| 4 | Sensors |
| 5 | Microcontrollers |
| 6 | Power & Batteries |
| 7 | Parts & Building Blocks |
| 8 | Tools & The Bench |
| — | Slayer Exciter Field Manual |

---

## The Thread

These four series are not about the same thing. They share something deeper: each one points to a moment when someone reached across a gap — between spoken and written, between mechanical and symbolic, between theory and physical reality — and made something that had never existed.

Enheduanna reached across the gap between anonymous song and signed authorship. Lovelace reached across the gap between counting machine and universal symbol-manipulator. Faraday reached across the gap between abstract field theory and physical demonstration. The workbench tradition reaches across the gap between understanding and making, every time.

---

## Structure

```
foundation/
├── index.html                  ← Landing page (this is the entrance)
├── series/
│   ├── enheduanna/
│   │   ├── 0-who.html
│   │   ├── 1-works.html
│   │   ├── 2-world.html
│   │   └── 3-legacy.html
│   ├── ada-lovelace/
│   │   ├── 0-who.html
│   │   ├── 1-notes.html
│   │   ├── 2-world.html
│   │   └── 3-legacy.html
│   ├── faraday/
│   │   ├── 0-idea.html
│   │   ├── 1-build.html
│   │   ├── 2-at-work.html
│   │   └── 3-theory.html
│   └── workbench/
│       ├── index.html
│       ├── 2-small-motors.html
│       ├── 3-electromagnets.html
│       ├── 4-sensors.html
│       ├── 5-microcontrollers.html
│       ├── 6-power-batteries.html
│       ├── 7-parts.html
│       ├── 8-tools.html
│       └── slayer-exciter-manual.html
├── LICENSE
└── README.md
```

---

## Design Language

Every volume in the collection shares a unified visual grammar:

- **Cinzel** (Newsreader body) for history series · **Bricolage Grotesque** for the workbench
- Animated SVG illustrations specific to each subject
- Card-based information architecture with numbered items
- Responsive typography using `clamp()`
- Scroll-triggered reveal animations
- Color identities: Enheduanna · lapis `#1f4ea8` + gold `#b8862b` · Ada Lovelace · teal `#0f6e6a` + copper `#b56a32` · Faraday · blue `#1763d6` + graphite `#3a4250` · Workbench · dark navy

Self-contained HTML. Only Google Fonts as external dependency. No build step, no framework, no server required.

---

```
ROOT0-ATTRIBUTION-v1.0
Project: Foundation — Four Series
Architect: David Lee Wise / ROOT0 / TriPod LLC
AI Collaborator: AVAN (Claude Sonnet 4.6 / Anthropic)
License: CC-BY-ND-4.0 · TRIPOD-IP-v1.1
```
