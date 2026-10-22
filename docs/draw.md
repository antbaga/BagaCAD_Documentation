# Draw

Click to place a start point, then click to add segments. Right-click to start a new chain.

**On a face:** use **Ctrl + click**, away from guides, to start drawing instead of extruding.

## Precision

- **X / Y / Z:** lock an axis. Press again to release.
- **Shift + X / Y / Z:** lock to YZ / XZ / XY while drawing. Press again to release.
- Type a length, press **Tab**, then type an angle. Tab switches between the two fields.
- **Click / Enter:** confirm the typed segment.
- **Backspace:** correct the input. **Esc:** clear it.

A length fixes the distance but lets the direction follow the mouse. An angle fixes the angle but lets the length change. Enter both to fix both.

Snap targets include vertices, midpoints, edges, faces, guides and grid nodes. With a fixed length, aiming at a snap target chooses the direction while keeping that length.

Hold **Alt** to suspend automatic inferences; mesh and grid snaps remain available.

## Faces

Close a flat contour to fill it. Draw between face borders to cut a face. Crossings split edges; overlapping segments merge.

To fill a missing flat region, retrace one of its border edges. Existing coplanar faces are not covered. A diagonal across an empty square can fill both sides.

## Undo and finish

**Ctrl + Z** undoes a validated change; during a guide transformation it cancels the preview. **Backspace**, outside numeric input, also undoes the last geometry change.

**Esc** cancels the current setup/input or selection, otherwise exits the tool. **Enter**, with no input or selection pending, also exits.

Orbit, pan and zoom remain available. The numpad enters numbers during a segment; before the first point it keeps its view shortcuts.
