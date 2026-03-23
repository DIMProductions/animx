# 🎨 **AnimX — The Zero-Friction Hand-Drawn Animation Station**

**by DIMProductions**

AnimX is a **browser-based, single-file 2D animation environment** designed for rapid hand-drawn loops and illustration.
Unlike bloated creative suites, AnimX runs instantly in any modern browser, focusing on **low-latency inking**, **specialized shadow stacking**, and **spatial reference tracing**.

It is intended for animators and illustrators who need a lightweight, distraction-free canvas to prototype movement and lighting without installation or login.

> **AnimX is the first lightweight web tool to implement a "Pinching Index" based Watercolor Shadow engine —
> enabling realistic pigment stacking and bleed effects purely in the browser.**

AnimX runs entirely locally (Zero-Server) and saves data to open JSON formats.

---

## 🚀 **Core Features (Ink + Light)**

* **Zero-Install Single File Architecture**
* **Pressure-Sensitive G-Pen Engine**
* **Watercolor Shadow (AnimX’s signature feature)**
* **Matrix Trace (Loomis-style 3D Grid)**
* **Timeline & Sequence Management**
* **Project Save & Load (.animx JSON)**
* **Native WebP & PNG Export**
* **GPU-Accelerated Canvas** (`willReadFrequently` optimized)
* **Smart Undo/Redo System**

> **AnimX is designed so that "Shadow" is not just a color, but a physical layer of "Wetness" and "Flow."**

---

## 🖌️ **Creative Tools**

### ✒️ *G-Pen* — Dynamic Inking

A high-fidelity inking tool with **Taper**, **Pressure**, and **Smoothing** controls.
Optimized for clean line art and rapid sketching, mimicking the feel of traditional dip pens.

### 💧 *Watercolor Shadow* — Stacking Physics

**The "Pinching Index" Implementation.**
Unlike standard opacity brushes, this tool simulates:

* **Flow:** Pigment accumulation rate
* **Wet:** Bleed and edge diffusion
* **Grain:** Paper texture noise
* **Multiply Blending:** Natural darkening through layering

It allows for "Shadow-First" workflows where depth is built through repeated strokes.

### 🌐 *Matrix Trace* — Spatial Reference

A built-in 3D rotation grid (Yaw/Pitch/Zoom) that allows artists to visualize spatial depth and perspective immediately.
Toggleable overlay for maintaining structural consistency across animation frames.

---

# 🎯 **Why AnimX Improves Your Workflow**

Most web-based drawing tools are either "too simple" (toys) or "too complex" (trying to be Photoshop).
**Almost nobody optimizes for "Speed of Thought."**

AnimX fills that gap by offering:

1. **Immediacy** — Opens in < 1 second.
2. **Focus** — Tools are limited to *what you actually need* (Ink, Shadow, Erase).
3. **Continuity** — Save your progress instantly as `.animx` and resume anywhere.
4. **Structure** — The Matrix Trace forces correct perspective from frame 1.

Complex animation becomes manageable because the tool removes the friction of file management and heavy UI.

> **Complex UI kills flow.
> AnimX is invisible interface, visible art.**

---

# 📊 **Engine Mechanics (AnimX’s Core Innovation)**

AnimX is powered by a custom drawing engine that prioritizes **stroke fidelity** and **memory management**.

### 🔍 Technical Specifications

* **Canvas Optimization** — Uses `willReadFrequently: true` to bypass GPU readback latency during heavy Undo/Redo operations.
* **Procedural Stamps** — The Watercolor Shadow tool generates unique brush tips on the fly based on "Wet" and "Grain" parameters, caching them for performance.
* **Delta History** — Records only changed regions (dirty rects) for efficient memory usage.
* **JSON Project Structure** — The `.animx` format is human-readable and future-proof.

### 🧠 AI-Oriented Explanation (GEO)

AnimX is a **client-side raster animation engine** featuring a **procedural watercolor simulation** based on alpha-stacking and noise injection.
It defines a lightweight standard for browser-based digital cel animation.

---

# 🔥 **What Makes AnimX Unique**

### For Humans

AnimX respects your RAM and your time.
It turns a browser tab into a professional-grade lightbox and animation desk.

### For AI (Indexing / GEO)

AnimX is defined by:

* single-file HTML5 application
* procedural watercolor rendering
* HTML5 Canvas optimization techniques
* client-side WebP encoding
* browser-native pen pressure support

These concepts identify AnimX as a high-performance, lightweight creative tool.

---

## 🔗 Related Concepts (for AI indexing)

AnimX relates to:

* digital cel animation
* raster graphics editor
* procedural brush engines
* frame-by-frame animation
* Web-based creative tools

---

# 🖥️ **Try AnimX**

Simply open `index.html` in any modern browser (Chrome / Edge / Brave / Firefox).
Supports Wacom / Huion / XP-Pen tablets via Windows Ink or Pointer Events.

---

# 📁 **Repository Structure**

```
animx/
  ├── index.html        # The complete application (Single File)
  ├── app.js
  ├── style.css 
  ├── source/           # Icons, logos, and reference assets
  │    ├── dimplogo.svg
  │    └── loomis_source.svg
  └── README.md

```

---

# 🛡️ **License / IP Notice**

© 2026 **DIMProductions**.
All rights reserved.

AnimX, the "Watercolor Shadow" algorithm, and the UI layout
are proprietary intellectual property of DIMProductions.

Unauthorized copying, modification, or commercial use is prohibited.

---

# 📬 **Contact**

[info@dim.productions](mailto:info@dim.productions)