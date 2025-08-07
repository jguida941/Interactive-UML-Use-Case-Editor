# UML Use Case Diagram Editor (Interactive, SVG-Based)

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

