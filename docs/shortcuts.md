# Shortcuts & settings

The tables show the **default bindings**. Customize them in **Edit > Preferences > Add-ons > BagaCAD**. The header and sidebar reminders follow your settings.

## Main actions

| Key or gesture | Action |
| --- | --- |
| Left click | Draw / confirm / extrude a hovered face, depending on context |
| Ctrl + click away from guides | Draw on a face |
| Shift + click on a face | Add / remove it from the extrusion selection |
| Alt + click on a face | Extrude connected coplanar faces |
| Right click | New chain / cancel preview / deselect, depending on context |
| D outside input | Switch Draw / Dimensions |
| X / Y / Z | Lock an axis |
| Shift + X / Y / Z during drawing | Lock YZ / XZ / XY |
| Tab while drawing | Switch length / angle input |
| Ctrl + Z | Cancel an active preview, otherwise undo the last validated edit, including extrusion |
| Backspace | Delete a digit or cancel the current step; keep validated geometry |
| Esc | Cancel input/setup/selection, otherwise finish |
| Enter | Confirm input/selection, otherwise finish |
| Hold Ctrl while drawing | Disable snapping while held; enabled by default |
| Hold Ctrl while extruding | Enable snapping while held; disabled by default |

## Construction references

| Key or gesture | Action |
| --- | --- |
| Hover a vertex / midpoint for 2 s | Add an XYZ guide |
| Hover an edge interior for 2 s | Add an edge guide |
| Hover a vertex / guide intersection for 0.15 s | Acquire a temporary reference point |
| A on a vertex, then click another | Add a guide through the two vertices |
| Hold Alt over a guide | Move it |
| Hold Shift over an XYZ axis | Rotate that reference |
| X / Y / Z during rotation | Lock the local rotation axis; repeat to unlock |
| R / Shift + R | Remove last guide / clear guides and temporary points; preserve grid |
| G | Show / hide the grid |
| Shift + G | Reposition / reorient the grid |
| Ctrl + G | Set cell size |
| Alt + G | Align grid to a face |
| G during direction setup / Ctrl at second click | Use direction-segment length as cell size |

## Dimensions

| Key or gesture | Action |
| --- | --- |
| Click / drag a value | Type / adjust it |
| Ctrl while dragging | Use rounding increments |
| Shift while dragging | Use fine adjustment |
| Tab outside input / click support icon | Switch fixed endpoint |
| Hover a value, then click its padlock | Toggle the dimension lock |
| Ctrl + A / Ctrl + V during input | Select all / paste |
| D / Esc outside input | Return to Draw |

## Preferences

| Setting | Default |
| --- | --- |
| Create Guide Timer | 2.0 s |
| Edge Guide Delay | 2.0 s |
| Temporary Vertex Delay | 0.15 s |
| Temporary Intersection Delay | 0.15 s |
| Grid Step | 0.1 Blender unit |
| Length Snap Step | 10 cm |
| Angle Snap Step | 15° |

The length and angle increments apply only to Ctrl-dragging dimensions. **Display Text** controls labels near the cursor.

Shortcut rows configure keys and modifiers. Shared input keys configure picking, confirmation, cancellation and text correction. Hold modifiers configure related gestures together; use a different modifier for each row. Red rows flag conflicting bindings. Right-click a setting to reset it to its default.

Saved preferences can differ from these defaults. Digits, decimal separators and minus remain numeric input. View navigation follows Blender's own keymap.

The viewport header changes with the current step: start point, segment input, face selection, extrusion, guide edit, grid setup or dimension edit. It displays the configured bindings. Ctrl disables drawing snaps but enables extrusion snaps while held; Alt moves a hovered guide.
