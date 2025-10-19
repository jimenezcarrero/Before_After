# Before/After Image Comparison Generator

Interactive before/after image comparison generator: upload two images, pan/zoom to align, rotate the split slider, preview, and export a high‑resolution composite.

Generador interactivo de comparativas antes/después: sube dos imágenes, ajusta con pan/zoom, rota el deslizador y exporta una imagen final en alta resolución.

## Features
- Upload “Before” and “After” images
- Pan and zoom each image independently to align
- Adjustable split angle (0–180°) with draggable slider
- Live preview that matches the exported result (pixel parity)
- Export to a single high‑resolution JPEG

## Quick start
1. Open `Before_After.html` in your browser (no build step required).
2. Click “Imagen Antes” and “Imagen Después” to select images.
3. Pan by dragging inside each editor; adjust zoom with the slider.
4. Use the “Ángulo del deslizador” to rotate the split.
5. In “Previsualización Interactiva”, drag the slider line to position the split.
6. Click “Generar y Descargar Imagen”.

## Notes
- The preview and export use the same math for exact pixel match.
- Tailwind is loaded via CDN; no external build tools are required.

## Roadmap
- Output dimension selector (presets and custom) that resizes the editors, preview wrapper, and export canvas in sync.
- Keyboard panning and zoom shortcuts
- PNG export with transparency and quality controls
- Mobile gesture support (pinch to zoom)

## License
MIT © 2025 Juan Jimenez Carrero
