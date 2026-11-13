# Frac — Mandelbrot Explorer

A single-file, dependency-free Mandelbrot fractal explorer. Open `index.html` in any browser.

## Features

- Click to zoom in, right-click (or shift-click) to zoom out
- Drag to pan, scroll wheel to zoom at the cursor
- Smooth continuous escape-time coloring
- Iteration slider with automatic depth boost for deep zooms
- Preset locations (Seahorse Valley, Elephant Valley, Mini Mandelbrot, …) and a reset view button
- Performance-conscious rendering: Web Worker kernel, progressive 1/8 → 1/1 resolution passes, instant palette recoloring from cached iteration data, snapshot-based panning
