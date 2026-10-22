# Shortcuts & settings

These are the current defaults, not the proposed future keymap.

| Action | Shortcut |
| --- | --- |
| Draw / confirm / extrude a hovered face | Left click, depending on context |
| Draw on a face | Ctrl + click, away from guides |
| Select extrusion faces | Shift + click |
| Extrude connected coplanar faces | Alt + click |
| New drawing chain / cancel preview | Right click |
| Dimensions / return to drawing | D, outside input |
| Axis lock | X / Y / Z |
| Plane lock while drawing | Shift + X / Y / Z |
| Length / angle input | Tab |
| Undo geometry | Ctrl + Z |
| Delete digit / undo geometry outside input | Backspace |
| Cancel current input/setup, otherwise finish | Esc |
| Confirm input/selection, otherwise finish | Enter |
| Suspend drawing inferences | Hold Alt |
| Grid | G; Shift/Ctrl/Alt + G for setup |
| Guide through two vertices | A, then click |
| Move guide / rotate XYZ reference | Hold Ctrl / hold Shift over guide |
| Remove last guide / all guides | R / Shift + R |

## Preferences

Open **Edit > Preferences > Add-ons > BagaCAD**.

| Setting | Default in the current source |
| --- | --- |
| Create Guide Timer | 2.0 s |
| Edge Guide Delay | 2.0 s |
| Temporary Vertex Delay | 0.15 s |
| Temporary Intersection Delay | 0.15 s |
| Grid Step | 0.1 Blender unit |
| Length Snap Step | 10 cm |
| Angle Snap Step | 15° |

The length and angle increments apply to Ctrl-dragging dimensions. **Display Text** controls labels near the cursor. Leave **Debug Mode** off for normal use.

Saved preferences can differ from these defaults. Hover delays are already editable; a complete custom keymap editor is not implemented in this version.
