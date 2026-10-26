# BagaCAD

Draw edges, close faces, extrude and edit dimensions directly in Blender.

**0.22 Alpha · Blender 5.0+**

## Install

Drag the BagaCAD extension **ZIP** from your file browser into Blender, then confirm installation. Keep the ZIP intact; enable BagaCAD if prompted. Disable older development copies first.

You can also use **Edit > Preferences > Get Extensions > menu > Install from Disk…**. Both methods are described in the [Blender manual](https://docs.blender.org/manual/en/5.0/editors/preferences/extensions.html).

## Start

Open the 3D Viewport sidebar with **N**, then select **BagaCAD**.

| Key or gesture | Action |
| --- | --- |
| Click **Draw** in the panel | Draw on the active mesh; create an empty mesh if no mesh is active |
| Click **Dimensions** in the panel | Start directly in dimension editing on the active mesh |
| F3 > BagaCAD New Drawing | Create an empty mesh and start drawing |
| F3 > BagaCAD Draw | Start drawing on the active mesh |
| Click **Documentation** in the panel | Open this manual |

Click points to draw. Close a flat contour to make a face. The viewport header shows the current action. The Dimensions button needs an active mesh.

[Draw](draw.md) · [Guides & grid](guides-grid.md) · [Extrude](extrude.md) · [Dimensions](dimensions.md) · [Shortcuts & settings](shortcuts.md)

Short GIF demonstrations are included in the tool pages. Some recordings use earlier development builds; the written shortcuts describe the current defaults.

## Scope

BagaCAD edits the active mesh. Other objects can hide snap targets but are not themselves snap targets. Hidden mesh elements are ignored. X-Ray and Wireframe allow snapping to revealed geometry.

Non-planar contours stay open. Dimensions and their locks are temporary tool data, not a persistent CAD constraint system. This alpha is still in development.
