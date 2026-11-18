# purescript-hylograph-canvas

Canvas 2D drawing primitives for Hylograph visualizations.

## Overview

Draws circles and lines to a Canvas 2D context, with zoom and pan, for scenes with too many elements for SVG. It is a set of drawing calls, not a rendering backend for HATS: it does not take a HATS `Tree`, and no other Hylograph library depends on it.

## Installation

```bash
spago install hylograph-canvas
```

## Modules

- `Hylograph.Canvas` - Core canvas rendering
- `Hylograph.Canvas.Zoom` - Zoom/pan behavior for canvas

## Part of Hylograph

- **hylograph-canvas** - Canvas rendering (this package)
- **hylograph-selection** - SVG/DOM rendering
- **hylograph-simulation** - Force simulation

## License

MIT
