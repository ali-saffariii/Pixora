# Pixora — Pixels Alive

Turn **images, text and videos** into ASCII art, pixel art, halftone and 25+ other effects.
100% client-side: no uploads, no server, no dependencies. Just open `index.html`.

By [Ali Saffari](https://github.com/alisaffari).

## Features
- **ASCII art**: 10 character ramps, area-averaged sampling, edge glyphs (`| - / \`), custom text and background colors, copy as text, save `.txt` or hi-res PNG
- **Pixel art**: square pixels, circle dots, mosaic, cross-stitch with clean area-averaged downscaling
- **Retro Palette Pro**: adaptive palette (k-means, 2-32 colors), Game Boy, PICO-8, Sweetie-16, CGA, C64, NES, Vapor and mono; Bayer 2x2 / 4x4 / 8x8, Floyd-Steinberg and Atkinson dithering; outline and pixel-grid options
- **Stylize**: halftone, crosshatch, pencil, oil paint, pointillism, voronoi, topographic, liquid chrome, 3D extrude, letterpress, outline, duotone, thermal
- **Retro / glitch**: CRT, VHS, glitch, Lo-Fi camera
- **Adjustments**: brightness, contrast, saturation, hue, blur, flip H/V, color modes
- **Video**: upload MP4/WebM, live effect preview, scrub, speed, quality, **trim in/out**, live fps cap (stutter look), record fps, save any frame, **record the result** (MP4 or WebM, with audio when the browser allows)
- **Export**: PNG / WebP / JPG at 1x-8x with nearest-neighbour scaling (perfect for pixel art)
- **Text mode**: render text with a font, then apply any effect
- Paste (`Ctrl+V`) or drop an image anywhere on the page; live re-render on every slider move

## Usage
Open `index.html` in a modern browser (Chrome / Edge / Firefox / Safari).
Drop an image or video, pick an effect, press **Apply**. For video, Apply starts the live preview; **Record** plays the trimmed range once and saves the processed result.
Shortcuts: `Space` play/pause, `Enter` apply.

## Host on GitHub Pages
Settings → Pages → Deploy from branch → `main` / root.

## Notes
- Heavy effects (voronoi, oil paint) are slow on video; lower the quality (360p/480p) or cap the live fps.
- Recording is real-time, so very heavy effects may drop frames.
- Canvas `filter` (Adjust sliders) needs a recent browser.

## License
MIT © Ali Saffari
