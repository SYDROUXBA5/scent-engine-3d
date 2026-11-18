# Scent Engine: 3D studies

Two interactive 3D studies of how scent moves, made for people who work dogs on scent.

**Open them here: https://sydrouxba5.github.io/scent-engine-3d/**

| Study | What it shows |
|---|---|
| [The field](https://sydrouxba5.github.io/scent-engine-3d/field.html) | A hillside with a stone wall, a hedge and a stand of trees. Set the ground and air temperature, the wind and the time of day, move the source, and see scent pool, lift, and go round what stands in front of it. |
| [The lake](https://sydrouxba5.github.io/scent-engine-3d/lake.html) | Human-remains scent from a source under water. Set the depth, the water temperature, the current and the wind. Watch gas bubbles and droplets of fat rise, the film drift on the surface, and a dog on a search boat work out where the scent comes up. |

## Using them

- **On a computer:** drag the picture to look around, scroll to zoom. The controls are on the left and the explanation on the right.
- **On a phone or tablet:** the picture stays at the top of the screen while the controls scroll under it, so you can move a slider and watch what it does. Drag the picture to look around, pinch to zoom, double-tap to place things.
- Each study has a "Try a ..." row of ready-made conditions that plays by itself until you touch a control.

They draw a few hundred thousand moving particles, so a recent device gives the smoothest picture. They need a browser with WebGL 2.

## How far to trust them

These are illustrations, not forecasts. Each study has a sheet, "What is measured, and what is a guess", that sorts every part of the picture into measured, published rule, or illustrative. Very little about the scent of remains under water has been measured, and the lake study says so.

## What is in this repository

The finished pages only: `index.html`, `field.html`, `lake.html` and two preview pictures. Each study is a single self-contained file.

## Credits

- Trees, bushes, grass, stones, ground and lake bed: scans and photographs from [Poly Haven](https://polyhaven.com) (public domain, CC0).
- Drawn with [three.js](https://threejs.org), loaded from jsDelivr.
- The boat, handler and dog in the lake study are a 3D model made with an AI tool, not a scan of a real boat.
