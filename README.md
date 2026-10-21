# NEXUS — BEYOND REALITY

A AAA, cinematic, interactive next-generation gaming universe web experience built with React, Vite, Three.js, React Three Fiber, GSAP ScrollTrigger, Lenis smooth scrolling, and Framer Motion.

---

## 🚀 Live Development & Build Commands

### 1. Install Dependencies
```bash
npm install
```

### 2. Start Development Server
```bash
npm run dev
```
Open [http://localhost:5173](http://localhost:5173) in your browser.

### 3. Production Build
```bash
npm run build
```

### 4. Preview Production Build
```bash
npm run preview
```

---

## 🌌 Implemented Pages & Routing Architecture

Every route is directly accessible, supports browser refresh, and features code-splitting via React `lazy` and `Suspense`:

| Route | Page | Description |
| :--- | :--- | :--- |
| `/` | **Home** | Full-screen cinematic Three.js hero scene with procedural fractured core, orbital tech rings, stars, mouse parallax, GSAP ScrollTrigger narrative, 3 editorial flagship showcases, and fictional brand metrics. |
| `/games` | **Games Explorer** | Real-time search filter, multi-genre selector, release status filter, sorting controls, dynamic count badge, reset button, and editorial game card grid. |
| `/games/:slug` | **Game Details** | Dynamic detail template rendering game telemetry, trailer modal with interactive fallback, persistent wishlist toggle (localStorage), 4K screenshot gallery with keyboard-navigated Lightbox (Left/Right/ESC), hardware specs matrix, and related titles. |
| `/universe` | **Interactive Universe** | Interactive 3D planetary sphere with orbital controls, 4 interactive 3D POI markers opening declassified dossiers, Character Database with biometric attribute radars, and a 4-era timeline. |
| `/community` | **Community Hub** | Live operative telemetry pulse, announcement system with category filtering and read-more modal, tournament calendar with registration modal + validation + celebratory confetti, and accessible FAQ accordion. |
| `/about` | **Studio & Mission** | Studio manifesto, design philosophy pillars, leadership architects team showcase, historical milestones, and direct communication transmission form. |
| `*` | **Not Found (404)** | Atmospheric "Signal Lost" sci-fi anomaly screen with navigation recovery vectors. |

---

## 🎨 Visual Identity & Design System

- **Primary Background**: Near-black (`#050609`)
- **Secondary Background**: Dark Charcoal (`#0c0e15`, `#121520`)
- **Primary Accent**: Electric Crimson (`#ff1744`)
- **Secondary Accent**: Burnt Orange (`#ff5722`)
- **Atmospheric Lighting**: Deep Red & Amber
- **Typography**:
  - Headings: `Orbitron` & `Syne`
  - Body: `Space Grotesk`
  - Technical / HUD: `JetBrains Mono`

---

## 🛠️ Key Technical Features

1. **Procedural Web Audio API Soundscape**:
   - Zero-dependency synthesizer generating an ambient sci-fi background drone and futuristic UI chirps for button clicks and hovers.
   - Saves mute/unmute state in `localStorage` without risking network errors or missing MP3 files.
2. **WebGL Resilience & Adaptive Fallbacks**:
   - Both `HeroScene.jsx` and `PlanetScene.jsx` feature graceful 2.5D CSS fallbacks if WebGL is unavailable or disabled.
3. **Smooth Scroll & Animation Synchrony**:
   - Lenis smooth scrolling synchronized directly with `gsap.ticker` and `ScrollTrigger`.
4. **Interactive Custom Cursor**:
   - Smooth desktop follower with spring physics, contextual text badges (`INTEL`, `ZOOM`, `TRAILER`, `WISHLIST`), and automatic touch-screen detection.
5. **Persistent Wishlist & Registration State**:
   - State persists across browser refreshes via `localStorage`.
