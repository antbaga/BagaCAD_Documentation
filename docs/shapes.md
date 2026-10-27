# Shapes & offsets

Use **C**, **B** or **O** during Draw, or the matching button in **N > BagaCAD**. Press the active tool key again to return to lines. **Esc / right click** cancels the current shape and returns to Draw. Each confirmed shape is one undo step.

## Circles and arcs

| Key or gesture | Action |
| --- | --- |
| C, then two clicks | Circle: centre, then radius |
| Type a radius after placing the centre | Set an exact radius; click / Enter to confirm |
| Tab | Switch centre-radius / three-point method; restart the current shape |
| Three clicks in three-point mode | Create a full circle through the three points |
| V | Switch full circle / open arc, keeping placed points |
| Wheel after the first click | Change segment count without zooming |

For a centre-based arc, click the **centre**, **start/radius**, then **end**; the arc runs counterclockwise in its drawing plane. For a three-point arc, it runs from the first point to the third through the second.

The radius and edge count appear on the preview. The initial resolution is **48 segments**, configurable in preferences; the wheel allows **3–256** during drawing. Before the first click, the wheel still zooms. Arcs remain open lines.

## Rectangles and squares

| Key or gesture | Action |
| --- | --- |
| B, then two clicks | First corner, then opposite corner |
| Hold Shift | Constrain to a square |
| Hold Alt | First point becomes the centre; aim at a corner |
| Hold Shift + Alt | Centred square |
| Type a size, then Tab | Enter width, then height; Tab switches the active side |

Both side lengths appear on the preview. The active value is highlighted beside its side; the first digit after Tab replaces the previous value. For centred shapes, width and height are the **total dimensions**.

## Drawing plane and references

Before each new circle or rectangle, hover the target face. Its plane is detected before the first click, including from an incident face when snapping to an edge or vertex. Without a face, the tool uses the active grid, then guides or the view. The plane stays fixed after the first click and is detected again for the next shape.

The soft grid around the cursor shows this plane; it is an indicator, not an extra snap grid. **X / Y / Z** after the first point orients the shape plane to **YZ / XZ / XY** in the current reference frame. A three-point circle uses the actual 3D snapped points to determine its plane.

Hover references and construction guides remain available while drawing shapes and offsets. **A** creates a two-point guide; **G** and grid setup commands stay available. Hold **Ctrl** to suspend placement snapping. The snap marker stays on the target even when the shape needs a projection onto its plane.

## Offset edges

Press **O**, click an edge, move to the desired side, then click to confirm. Type a distance for an exact offset; the mouse chooses the side.

For several edges: **O → hold Shift → click the edges → release Shift → move/type → click**. Each click adds only the targeted edge, shown in orange. Releasing Shift groups the selection into chains and starts the preview from the last selected edge. Independent chains share the distance and one undo step.

Source edges remain in place. Chains must be planar; corners use miter joins and self-crossing offsets are rejected. Offsets work on existing faces or loose edges.

## Filled faces or lines only

Closed shapes create faces by default. **Hold F** to invert filling while placing a circle, rectangle or offset. The preference **Shapes: Create Faces by Default** reverses this default.

With filling enabled, an offset also creates the connecting strip. With filling disabled, it creates only parallel lines. On an existing face, the new lines still cut the surface: disabling fill does not remove existing material. Shared edges and intersections merge into the active mesh.
