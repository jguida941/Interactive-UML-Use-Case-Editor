# UML Use Case Diagram Editor (Interactive, SVG-Based)

[![License: MIT](https://img.shields.io/badge/License-MIT-ff6a00?style=flat-square&labelColor=0a0a0a)](LICENSE)
![App](https://img.shields.io/badge/App-Single--file%20HTML%2FJS%2FCSS-ff6a00?style=flat-square&labelColor=0a0a0a)
![Build](https://img.shields.io/badge/Build-None%20required-ff6a00?style=flat-square&labelColor=0a0a0a)
![Deps](https://img.shields.io/badge/Dependencies-0-ff6a00?style=flat-square&labelColor=0a0a0a)
![Runtime](https://img.shields.io/badge/Runtime-Browser-ff6a00?style=flat-square&labelColor=0a0a0a)
![Offline](https://img.shields.io/badge/Offline-Ready-ff6a00?style=flat-square&labelColor=0a0a0a)
![Export](https://img.shields.io/badge/Export-SVG%20%7C%20PNG-ff6a00?style=flat-square&labelColor=0a0a0a)
![Persistence](https://img.shields.io/badge/Save%2FLoad-JSON-ff6a00?style=flat-square&labelColor=0a0a0a)
![Relations](https://img.shields.io/badge/Relations-Association%20%7C%20Include%20%7C%20Extend%20%7C%20Generalization-ff6a00?style=flat-square&labelColor=0a0a0a)
![Canvas](https://img.shields.io/badge/Canvas-Pan%20%7C%20Zoom%20%7C%20Reset-ff6a00?style=flat-square&labelColor=0a0a0a)
![Editing](https://img.shields.io/badge/Editing-Drag%20%26%20Drop%20%7C%20Inline%20Text%20%7C%20Context%20Menu-ff6a00?style=flat-square&labelColor=0a0a0a)

A lightweight, single-file web app for creating **UML Use Case diagrams** — no build step, no backend.  
Add actors and use cases, drag to position, connect with UML relationships (association, include, extend, generalization), and **export to SVG/PNG** or **save/load JSON**.

> **Live-ready:** Open `index.html` in any modern browser and you’re building.
> I also have automated gant chart editors etc. This is a simple version I built for UML case diagrams cause lucid chart keeps wanting me to "pay for shapes"

## Features

- **Interactive editing**
  - Add **Actors** (primary/secondary) and **Use Cases**
  - Drag & drop positioning with smooth re-rendering
  - Inline text editing (double-click labels)
  - Right-click context menu (Edit, Duplicate, Delete)
- **UML relationships**
  - Association, `<<include>>`, `<<extend>>`, and **generalization** (open arrowhead)
- **Canvas controls**
  - Pan (click-drag background), **Zoom In/Out**, **Reset View**
- **Export & persistence**
  - Export **SVG** (vector) and **PNG** (raster)
  - **Save** diagram as JSON and **Load** it back
- **System boundary & title**
  - Dashed system rectangle and editable system name
- **At-a-glance stats**
  - Live counts of Actors, Use Cases, and Connections

## Screenshot
<img width="1000" height="1080" alt="Screenshot 2025-08-07 at 6 07 50 PM" src="https://github.com/user-attachments/assets/723ad181-67b8-4eb2-8c82-5b8f90e494ee" />


## Quick Start

### Option A — Open directly
1. Download the file as `index.html`.
2. Double-click to open in Chrome/Edge/Firefox/Safari.

### Option B — Serve locally (recommended)
Some browsers are picky about local file URLs. Run a local server:

```bash
# Python 3
python3 -m http.server 8080

# Or Node
npx http-server -p 8080

