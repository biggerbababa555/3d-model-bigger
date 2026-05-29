# 3D Model Exhibition Viewer — "Alex Face" Studio

An elegant, ultra-minimalist, black-and-white (monochrome) single-page 3D model exhibition web application built using HTML, CSS, vanilla JavaScript, and Google's `<model-viewer>` component.

## 🏛️ Exhibition Showcases

The viewer features a minimalist switcher supporting five dynamically loaded exhibition pieces:
1. **01. Alex Face**: The iconic, world-famous street art mascot mesh (`white_mesh.glb`).
2. **02. FIFA Ball**: A compressed, high-fidelity reconstruction of the star-panel Champions League match ball (`ball.glb`).
3. **03. Bigger**: A digital sculpture study of the human form (`model.glb`).
4. **04. Alex Rowing**: A narrative 3D sculpture showing the mascot rowing a rowboat (`alex2.glb`).
5. **05. Ranger**: The Bigger mascot sculpture wearing a detailed military ranger uniform (`bigranger.glb`).

## 🛠️ Features

* **Strict Monochrome Theme**: Designed with an enterprise-level minimalist aesthetic inspired by Apple's design language, featuring custom transitions and a photography studio radial gradient vignette.
* **Dynamic Theme Switcher**: Easily switch between **Light Studio Mode** and **Dark Studio Mode** directly from the bottom toolbar.
* **Dynamic Loading System**: Includes a custom loading screen that monitors actual loading percentages of `.glb` files and swaps branding titles smoothly during transitions.
* **Detailed Info Drawer**: A slide-in drawer on the right offering contextual descriptions and interaction guides tailored to each model.
* **Camera Toolbar**: Bottom controls to toggle auto-rotation, reset the camera angle dynamically to the model's distinct coordinates, and activate AR projection modes on mobile.
* **Mobile Responsive**: Fully responsive grid layout that adapts to mobile, tablet, and desktop viewports.

## 🕹️ Interaction Guide

### Desktop
* **Orbit Rotation**: Left-Click + Drag
* **Pan Camera**: Right-Click + Drag or Shift + Drag
* **Zoom In / Out**: Scroll Mouse Wheel

### Mobile
* **Orbit Rotation**: One Finger Swipe
* **Zoom & Pan**: Two Finger Pinch / Drag

## 🚀 How to Run Locally

You can serve this single-page app locally using any static file server:

### Python 3
```bash
python3 -m http.server 8000
```
Open **[http://localhost:8000](http://localhost:8000)** in your browser.

### Node.js (via serve)
```bash
npx serve
```

---
© 2026 Art Exhibition Studio. Crafted with Model Viewer.
