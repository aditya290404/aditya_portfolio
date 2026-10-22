# Aditya Prasad — Software Engineering & Interactive 3D Portfolio

A high-performance, light-themed, scroll-driven 3D developer portfolio built with **Three.js**, **GSAP ScrollTrigger**, and modern semantic HTML/CSS. Designed and engineered for software engineering roles and technical recruiting.

👉 **Live Portfolio Experience**: *(Hosted via GitHub Pages / Vercel)*

---

## 🎨 Creative Direction & Aesthetic

The portfolio embraces a light, minimal, Swiss-editorial aesthetic inspired by modern editorial publications and premium product design:
- **Color Palette (Light Mode)**: Warm off-white canvas (`#FAFAF7`), soft cool-gray alternate surfaces (`#F1F3F5`), deep charcoal typography (`#20242B`), muted slate metadata (`#68717D`), and sophisticated cobalt blue accents (`#4568F5`).
- **Color Palette (Dark Mode)**: Deep charcoal background (`#0D1017`), soft dark surfaces (`#131822`), warm white typography, and adjusted cobalt highlights.
- **Typography**: Paired with **Space Grotesk** for bold display headings, **Inter** for readable body copy, and **JetBrains Mono** for technical metadata and code readouts.
- **Gridless Canvas**: Uninterrupted solid color surfaces paired with generous negative space and an evolving 3D storytelling environment.

---

## 🌐 Immersive 3D Scroll Architecture

Instead of a static 3D widget, the portfolio utilizes a **single persistent Three.js WebGL renderer** synchronized with the page's scroll progress across 7 distinct scenes:

1. **Scene 01 — Introduction (Kinetic Core)**: A beautifully lit architectural sculpture composed of an octahedral ceramic core, cobalt nucleus, and interlocking brushed-silver gimbals beside the hero introduction.
2. **Scene 02 — Transition Bridge**: The camera DOLYS closer as the object deconstructs into satellite shards, bridging the hero and project sections.
3. **Scene 03 — ScriptMarket**: Transforms into a cinematic screenplay folio with layered document planes and publishing motifs.
4. **Scene 04 — APEX VELOCITY 3D**: Sweeps into a closed 3D banked race circuit complete with a procedural low-poly drift vehicle moving along a Catmull-Rom spline.
5. **Scene 05 — Trade-wide**: Morphs into a distributed cloud topology with connected data nodes and real-time structured telemetry bars.
6. **Scene 06 — System Architecture**: Refines into a layered cylinder stack representing frontend, backend, database, and infrastructure layers.
7. **Scene 07 — Equilibrium (Contact)**: Settles into a calm, balanced composition as visitors reach the final contact invitation.

---

## 🚀 Featured Projects & Engineering Highlights

### 1. ScriptMarket
* **Category**: Full-Stack Product · Marketplace
* **Description**: A marketplace for screenplay creators to publish, discover, buy, sell, and manage script assets.
* **Tech Stack**: Next.js, React, TypeScript, Tailwind CSS, Prisma, PostgreSQL, Neon, AWS Amplify.
* **Links**: [Live Demo](https://main.d15xbsk1qtkv82.amplifyapp.com) · [GitHub Repository](https://github.com/aditya290404/ScriptMarket)

### 2. APEX VELOCITY 3D: Drift Edition
* **Category**: Interactive 3D · Browser Game
* **Description**: An immersive browser-based 3D racing game featuring custom vehicle dynamics, drift mechanics, procedural audio, and a real-time racing HUD.
* **Tech Stack**: HTML5, Vanilla JavaScript, Three.js, Web Audio API, Custom Physics.
* **Links**: [Play Live Demo](https://3dracinggame-hfun7ld7l-aditya290404s-projects.vercel.app/)

### 3. Trade-wide
* **Category**: Cloud-Native Application · FinTech
* **Description**: A cloud-native paper-trading platform designed around simulated trading, user wallets, leaderboards, and real-time market alerts.
* **Tech Stack**: Next.js, Node.js, PostgreSQL, Prisma, Redis, Socket.io, Docker, Kubernetes, Jenkins.
* **Links**: [GitHub Repository](https://github.com/aditya290404/Trade-wide)

---

## 🛠️ Technical Implementation & Performance

* **Single WebGL Context**: Avoids memory leaks and performance overhead by maintaining one persistent canvas across all scroll positions.
* **GSAP ScrollTrigger**: Smooth interpolation, responsive camera pathing, and scrubbing synchronized with native browser scrolling.
* **Responsive Breakpoints**: Seamlessly adapts 3D object positioning and layout scaling for mobile viewports without scroll-jacking.
* **Theme Persistence**: FOUC-protected dynamic theme switcher backed by `localStorage` and synchronized with Three.js scene fog, lighting, and material properties.
* **Accessibility & Fallback**: Includes `prefers-reduced-motion` support and a non-WebGL CSS fallback.

---

## 📂 Project Structure

```text
├── index.html            # Complete single-file application (HTML, CSS, Three.js & GSAP)
└── README.md             # Repository documentation
