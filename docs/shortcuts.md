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

## Shapes, offsets and edge editing

| Key or gesture | Action |
| --- | --- |
| C / B / O | Circle / rectangle / offset; repeat the active key to return to lines |
| Tab in Circle | Switch centre-radius / three-point method; restart the shape |
| V in Circle | Switch full circle / open arc |
| Wheel after the first circle point | Change segments, without zooming |
| Shift / Alt in Rectangle | Square / centred rectangle; combine for a centred square |
| Tab in Rectangle | Switch width / height input |
| Hold F | Invert shape/offset face filling |
| Backspace in a shape | Delete a digit; without input, reset the placed points |
| Shift + clicks in Offset, then release Shift | Select individual edges, then start the shared offset |
| Hold Shift + right mouse and sweep | Erase visible edges |
| Alt over an edge, then left click | Preview, then confirm extension to a real target |

See [Shapes & offsets](shapes.md) and [Erase and extend](draw.md#erase-and-extend-edges) for steps and modifier priorities.

## Construction guides

Lasting references, kept until removed. See [Guides & grid](guides-grid.md#guide-or-temporary-point) for the difference with temporary points.

| Key or gesture | Action |
| --- | --- |
| Hover a vertex / midpoint for 2 s | Add an XYZ guide |
| Hover an edge interior for 2 s | Add an edge guide |
| A on a vertex, then click another | Add a guide through the two vertices |
| Hold Alt over a guide | Move it |
| Hold Shift over an XYZ axis | Rotate that XYZ guide |
| X / Y / Z during rotation | Lock the local rotation axis; repeat to unlock |
| R / Shift + R | Remove last guide / remove all guides and temporary points; the grid is kept |

## Temporary reference points

Short-lived alignment points for the segment in progress; not editable.

| Key or gesture | Action |
| --- | --- |
| Hover a vertex for 0.15 s, then move away | Use its XYZ projections and edge directions |
| Hover a guide intersection for 0.15 s | Remember that intersection |
| Confirm a segment / right click / Shift + R | Clear the temporary points |

## Grid

| Key or gesture | Action |
| --- | --- |
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
| Tab outside input / click support icon | Edge: switch fixed endpoint; vertex: toggle anchoring |
| Hover a value, then click its padlock | Toggle the dimension lock |
| Ctrl + A / Ctrl + V during input | Select all / paste |
| D / Esc outside input | Return to Draw |

## Preferences

| Setting | Default | Controls |
| --- | --- | --- |
| Create Guide Timer | 2.0 s | Hover time for an XYZ guide on a vertex / midpoint |
| Edge Guide Delay | 2.0 s | Hover time for an edge guide |
| Temporary Vertex Delay | 0.15 s | Hover time for a temporary point on a vertex |
| Temporary Intersection Delay | 0.15 s | Hover time for a temporary point on an intersection |
| Default Grid Step Size | 0.1 Blender unit | Initial grid cell size |
| Shapes: Create Faces by Default | Enabled | Fill closed shapes; hold F to invert |
| Circle Segments | 48 | Initial resolution (8–256; wheel while drawing: 3–256) |
| Length Snap Step | 10 cm | Ctrl-drag increment in Dimensions |
| Angle Snap Step | 15° | Ctrl-drag increment in Dimensions |

Shortcut rows configure keys and modifiers. Shared input keys configure picking, confirmation, cancellation and text correction. Hold modifiers configure related gestures together; use a different modifier for each row. Red rows flag conflicting bindings. Right-click a setting to reset it to its default.

Saved preferences can differ from these defaults. Digits, decimal separators and minus remain numeric input. View navigation follows Blender's own keymap.

The viewport header changes with the current step: start point, segment input, face selection, extrusion, guide edit, grid setup or dimension edit. It displays the configured bindings. Ctrl disables drawing snaps but enables extrusion snaps while held; Alt moves a hovered guide.
