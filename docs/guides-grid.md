# Guides & grid

## Guides

Hover to acquire a reference. A short hover stores a temporary reference; a longer hover creates a persistent guide.

- Vertex or midpoint: an XYZ reference.
- Edge interior: an infinite construction line.
- **A** on a vertex, then click another vertex: a guide through both.
- **Hold Ctrl over a guide:** move it; release to confirm.
- **Hold Shift over an XYZ axis:** rotate that reference around its origin; release to confirm.
- **Esc / right-click:** cancel a transformation.
- **R:** remove the last guide.
- **Shift + R:** remove all guides and temporary references.

Temporary references keep the two most recent acquired vertices/intersections. They provide axes, edge extensions and real 3D intersections. They clear after committing a segment or starting a new chain.

## Grid

| Shortcut | Action |
| --- | --- |
| G | Show or hide the remembered grid |
| Shift + G | Place or reorient it in two clicks |
| Ctrl + G | Set cell size by measurement or typing |
| Alt + G | Place and align it to the hovered face |
| Shift + X / Y / Z | Set a world grid to YZ / XZ / XY, with no segment active |

For placement, click an origin, then a direction. **Esc / right-click** cancels the setup.

The grid snaps to line intersections, not cell centers. Its default step is 0.1 Blender unit. Showing or hiding it preserves current numeric input.
