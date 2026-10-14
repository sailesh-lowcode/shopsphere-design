# ShopSphere — E-commerce Design (Figma-ready)

Pixel-perfect e-commerce website design as three SVG artboards. SVGs import
into Figma natively as fully editable vector layers — frames, shapes, and
real text.

## Files

| Artboard | File | Size |
|---|---|---|
| Home — Desktop | `home-desktop.svg` | 1440×2260 |
| Product Detail — Desktop | `product-desktop.svg` | 1440×1160 |
| Home — Mobile | `home-mobile.svg` | 390×1600 |

Also includes `index.html` — a preview page that shows all three artboards.

## Import into Figma (30 seconds)

1. Open Figma → your design file (or create a new one: **File → New design file**)
2. Drag & drop the `.svg` files from this folder onto the canvas
   (or **Menu → Place image/video…**)
3. That's it — every shape and text string becomes an editable Figma layer.
   Ungroup (`Ctrl/Cmd + Shift + G`) to break the artboard into sections.

## Design system

- Brand: teal `#0f766e` → `#14b8a6`, accent amber `#f59e0b`
- Ink `#0f172a` · text muted `#64748b` · surface `#f8fafc` · border `#e2e8f0`
- Radius: 10–14px · system UI font stack
- Product art = vector glyphs on 8 gradient pairs (no external images)

## Why SVG instead of drawing via API

The Figma REST API (what API Rails exposes) is read/management-only — it
cannot create files or draw shapes. SVG import is the native bridge: Figma
converts SVG geometry 1:1 into editable design layers.
