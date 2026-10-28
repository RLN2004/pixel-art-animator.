# Pixel Art Animator

A free, local-first browser tool for adding procedural motion to still images. Built with vanilla HTML, CSS, and JavaScript—no build step, packages, backend, or account required.

## Features
- Load an image by file picker or drag and drop.
- Adjustable pixelation and subtle camera drift.
- Procedural rain, drifting cloud shapes, twinkling stars, warm light pulse, scanlines, grain and floating particles.
- Pause/play, reset settings, and export a standalone HTML animation.
- Record a 6-second WebM clip using browser MediaRecorder (supported browsers only).
- Responsive interface; all processing happens locally in the browser.

## Run locally
Open `index.html` in a modern browser, or run `python -m http.server 8000` and visit `http://localhost:8000`.

## Limitations
This is a procedural effects tool, not an AI scene-understanding system. Effects are drawn over the whole image and cannot independently animate the original character or objects. Rain/clouds/stars are overlays, so use subtle settings to suit the image. WebM recording support depends on the browser; MP4 encoding is not built in.

## Privacy
Images are processed locally and are not uploaded by this application. Exported HTML embeds the selected image; treat the exported file as containing your image.

## License
MIT. See [LICENSE](LICENSE).
