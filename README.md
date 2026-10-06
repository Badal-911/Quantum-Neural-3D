# AETHEON 3D Spatial Studio

A real-time, interactive 3D spatial viewport and geometry visualizer built with **Three.js**, **React 19**, **TypeScript**, and **Tailwind CSS**. AETHEON 3D allows users to explore procedural 3D models with physically based rendering (PBR), kinematic exploded assembly views, interactive screen-projected annotation hotspots, customizable studio lighting, and high-resolution render captures.

---

## Features

### 1. Curated 3D Spatial Artifacts
- **01. Quantum Chronometer**: High-frequency horological skeleton mechanism with a 60-second rotating flying tourbillon, harmonic oscillating balance wheel, planetary gear train with calibrated gear ratios, synthetic ruby jewel bearings, and double-sided sapphire crystal optics.
- **02. Aero-Spatial Speedform**: Aerodynamic concept hypercar study featuring ground-effect venturi diffusers, active hydraulic rear wing, carbon splitter, sculpted cockpit canopy, and dynamic wind-tunnel airflow particle streamlines.
- **03. Kinetic Nexus Pavilion**: Parametric architectural spatial installation composed of 64 articulating solar louvers undulating to wave phases, stainless steel tensegrity trusses, translucent structural glass, and an acoustic reflecting basin.
- **04. Quantum Neural Swarm**: Real-time GPU particle simulation of 12,000 vector nodes calculating gravitational vortices, double-helix coils, and quantum singularities.

### 2. Kinematic Exploded Assembly & 3D Hotspot Tracking
- **Exploded Separation Slider**: Smoothly deconstructs complex assemblies into discrete structural layers along calibrated separation vectors (0% compact assembly to 100% full exploded inspection).
- **Screen-Projected 3D Hotspots**: Annotation pins computed in 3D world space and dynamically projected onto 2D screen coordinates, providing live tooltips, technical specifications, and click-to-focus camera targeting.

### 3. Physical Shader & Material Studio
- **PBR Materials**: Calibrated micro-roughness, metallic reflection, clearcoat, and optical transmission.
- **Material Finishes**:
  - *Cyber Titanium* (Grade 5 aerospace satin alloy)
  - *Liquid Chrome* (Ultra-high specular mirror finish)
  - *Obsidian Matte* (Stealth nano-ceramic composite)
  - *Rose Gold* (Precious 18K warm alloy)
  - *Frosted Glass* (Refractive optical transmission with 1.77 sapphire IOR)
  - *Holo Vector* (Tactical holographic wireframe)
  - *Architectural Clay* (Neutral ambient occlusion clay render)

### 4. Directional Studio Lighting & Backdrops
- **Three-Point Studio Rig**: Warm key light with PCF soft shadows, cool directional fill light, and sharp silhouette rim highlight.
- **Environment Backdrops**:
  - *Minimalist Travertine Studio*
  - *Neo-Tokyo Cyber Skyline*
  - *Deep Cosmic Nebula*
  - *High-Contrast Obsidian Void*
- Ground reflection grid and adjustable turntable rotation speed.

### 5. Camera Choreography & Render Export
- **Smooth Inertial Controls**: Damped orbit rotation, pan (Right-Click or Shift + Drag), and scroll-wheel zoom.
- **Perspective Presets**: Free Orbit, Isometric 45°, Top Orthographic, Macro Lens 10x, and Low Cinematic.
- **Capture Render**: Single-click high-resolution PNG export directly from the WebGL framebuffer.

### 6. Acoustic Feedback Synthesizer
- Built-in zero-dependency sound engine powered by the **Web Audio API** producing subtle mechanical winding clicks, resonance whooshes, and harmonic chimes for interaction feedback (with one-click mute/unmute).

### 7. Real-Time Telemetry HUD
- Tabular telemetry display tracking real-time framerate (FPS), rendered triangle count, WebGL draw calls, and active geometry buffers.

---

## Tech Stack

- **Core 3D Engine**: [Three.js](https://threejs.org/) (WebGL 2.0, PBR, PCF Soft Shadows)
- **Framework**: [React 19](https://react.dev/) + [TypeScript](https://www.typescriptlang.org/)
- **Bundler & Tooling**: [Vite 8](https://vitejs.dev/) + [tsx](https://github.com/privatenumber/tsx)
- **Styling**: [Tailwind CSS v4](https://tailwindcss.com/)
- **Icons**: [Lucide React](https://lucide.dev/)
- **Typography**: Google Fonts (*Syne*, *Plus Jakarta Sans*, *JetBrains Mono*)

---

## Project Structure
