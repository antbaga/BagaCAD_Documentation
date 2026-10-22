# Extrude

Hover inside a face, with no segment in progress. Click the highlighted face, move the mouse, then click again or press **Enter**.

Type a distance for an exact result. Negative values move in the opposite direction. **Esc / right-click** cancels the preview.

## Several faces

- **Shift + click:** add or remove a face from the selection.
- Release Shift, then click a selected face, or press **Enter**, to extrude the selection.
- **Alt + click:** extrude the connected coplanar faces instead; this replaces the manual selection.

For non-coplanar selected faces, the whole group moves in one direction: the normal of the last selected face.

**Esc / right-click**, before extrusion starts, clears the selection.

## Snapping

Aim at a vertex, midpoint, edge or face to match its height along the extrusion direction. Hold **Alt** during extrusion to disable this snap. A typed distance takes priority.

## Result

Outward extrusion can fuse with volumes in the same mesh. Inward extrusion can make a pocket or a through-hole. The exact boolean calculation happens when you confirm.

An isolated surface keeps a bottom and becomes a volume. Other objects remain separate.
