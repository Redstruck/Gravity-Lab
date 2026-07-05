# Gravity Lab

A browser-based physics playground built around a canvas simulation.
It is designed for experimenting with motion, gravity, bounce, water effects, and other interactive forces in a lightweight single-page setup.

🔗 **Live Demo:** https://gravity-lab.vercel.app/

---

## Overview

Gravity Lab is an interactive physics sandbox that runs entirely in the browser.
The experience centers on real-time motion, collision behavior, adjustable parameters, and visual feedback that makes the simulation easy to explore.

The project is intentionally simple at the application level: the main experience lives in a single HTML entry point, with inline styles and script powering the simulation.

---

## Key Features

- Real-time canvas-based physics simulation
- Interactive controls for tuning simulation behavior
- Gravity and bounce adjustments
- Water and particle effects
- Responsive layout that fills the browser viewport
- On-screen stats and simulation feedback
- Lightweight single-file implementation

---

## Tech Stack

- **HTML** + **CSS** + **JavaScript** — UI and simulation logic
- **Canvas API** — rendering the physics scene
- **Netlify** — deployment

---

## Project Structure

This repository is intentionally minimal.

- `index.html` — main application entry point, styles, and simulation logic
- `README.md` — project overview and usage notes

---

## Development Philosophy

This project was built as a compact, iterative physics experiment.

- Keep the experience immediate and easy to run
- Use the browser canvas directly for simulation and rendering
- Favor visible feedback over abstraction-heavy architecture
- Refine the feel of the physics through testing and adjustment

The goal is to provide a simple environment for exploring motion and interactions without unnecessary setup.

---

## Running Locally

### Prerequisites
- A modern browser

### Setup
```bash
git clone <repository-url>
cd Gravity-Lab
open index.html
```

If you are serving the project through a local dev server, open the root folder and load `index.html` in the browser.
