# Draw

Place a start point, then add segments. On a face, hold Ctrl when clicking to draw instead of extruding; keep away from a guide handle.

| Key or gesture | Action |
| --- | --- |
| Left click | Place the start point or confirm the next segment |
| Right click | Start a new chain |
| Ctrl + click inside a face | Start drawing on the face |
| X / Y / Z | Lock the corresponding axis; press again to release |
| Shift + X / Y / Z | Lock to YZ / XZ / XY; press again to release |
| Type digits | Set the active length or angle value |
| Tab | Switch between length and angle input |
| Click / Enter | Confirm the segment |
| Backspace | Delete a digit; outside input, cancel the unfinished chain |
| Ctrl, held | Disable mesh, grid and guide snapping; release to restore snapping |
| Ctrl + Z | Undo a validated edit; discard any unfinished guide/grid setup first |
| Esc | Clear input, setup or selection; otherwise finish the tool |
| Enter without input or selection | Finish the tool |

## Precision

A typed length fixes distance while the direction follows the mouse. A typed angle fixes the angle while the length changes. Enter both to fix both. Tab alone selects a field without locking it.

Drawing snapping is on by default. Hold Ctrl to disable it; release Ctrl to restore it. Explicit axis/plane locks and typed dimensions stay active without Ctrl. Hovering can still acquire construction guides and temporary references.

Snap targets include vertices, midpoints, edges, faces, construction guides and grid nodes. With a fixed length, any snap target can choose the direction; the segment keeps its entered length. Displayed measurements follow the scene units. Drawing input uses Blender units; angles use degrees.

In empty space, free drawing uses a view-parallel plane at the 3D cursor depth when no snap or grid plane applies.

## Faces

Close a flat contour to fill it. Draw between face borders to cut a face. Crossings split edges; overlapping segments merge.

To fill a missing flat region, retrace one of its border edges. Existing coplanar faces are not covered. A diagonal across an empty square can fill both sides.

## Navigation

| Key or gesture | Action |
| --- | --- |
| Middle mouse / Shift + middle mouse / wheel | Orbit / pan / zoom with the default Blender keymap |
| Numpad during a segment | Enter numbers |
| Numpad before the first point | Use Blender view shortcuts |

BagaCAD shortcuts can be changed in the [preferences](shortcuts.md); navigation uses Blender's keymap.
