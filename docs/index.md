# BagaCAD

Draw edges, close faces and extrude directly in Blender.

**0.22 Alpha · Blender 5.2+**

This is a short working manual. The addon is still in development; save a copy before testing.

## Install

1. Open **Edit > Preferences > Get Extensions**.
2. Use the menu > **Install from Disk…** and select the BagaCAD ZIP.
3. Enable the extension. Disable older development copies first.

## Start drawing

- **F3 > BagaCAD New Drawing** creates an empty mesh.
- **F3 > BagaCAD Draw** works on the active mesh.
- Both commands are also in **N > BagaCAD**.

Click points to draw. Close a flat contour to make a face. Right-click to start another chain. The viewport header shows the current action.

[Drawing](draw.md) · [Extrusion](extrude.md) · [Dimensions](dimensions.md) · [Shortcuts](shortcuts.md)

## Scope

BagaCAD edits the active mesh. Other objects can hide snap targets but are not themselves snap targets. Hidden mesh elements are ignored. X-Ray and Wireframe allow snapping to revealed geometry.

Non-planar contours stay open. Complex geometry is not guaranteed to work. Dimensions and their locks are temporary tool data, not a persistent CAD constraint system.
