# Pixel Art Animator

A lightweight, local-first browser tool for adding procedural motion to still images. Built with vanilla HTML, CSS, and JavaScript—no build step, packages, backend, or account required.

## Features

- Load an image by file picker or drag and drop.
- Preview subtle camera drift, warm light pulsing, scanlines, grain, and floating particles.
- Tune effects with live controls and reset to defaults.
- Export a standalone HTML file with the selected image embedded, so it can run offline.
- Responsive interface for desktop and mobile.

## Run locally

Open `index.html` in a modern browser. Alternatively, run a local static server:

```bash
python -m http.server 8000
```

Then visit http://localhost:8000.

## Limitations

This is a procedural image-effects tool, not an AI scene-understanding system. It animates the image as a whole and overlays effects. It does **not** automatically separate hands, vehicles, trees, clouds, or other objects into independently animated layers.

Future work could add segmentation/masking, manual layer editing, per-layer transforms, and export to a sprite sheet or game engine.

## Privacy

Images are processed in your browser and are not sent to a server by this application. Export embeds the selected image into the generated HTML file; treat that exported file as containing your image.

## License

MIT. See [LICENSE](LICENSE).
