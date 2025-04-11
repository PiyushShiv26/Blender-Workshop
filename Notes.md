# Blender Workshop Quick Reference

A concise cheat sheet for essential Blender operations, tools, and best practices — perfect for beginners and quick lookups.

---

## Navigation & Selection

- **Middle Mouse Button**: Rotate view around object.
- **Shift + Middle Mouse**: Pan the viewport.
- **Left Click + G**: Grab/Move selected object.
- **Left Click + S**: Scale selected object.
- **G + Y/X/Z**: Move along the Y/X/Z axis.
- **Shift + A**: Add a new object.
- **Spacebar**: Open command search.
- **Select + X**: Delete selected object.

---

## Basic Object Modifiers

- **Array**: Create multiple instances of the same object.
- **Mirror**: Mirror object across an axis.
- **Bevel**: Smooth or round edges of a model.
- **Ico Sphere**: Use Proportional Editing (TAB → O key).

---

## Camera & View

- **N**: Open sidebar → Enable *"Lock Camera to View"*.
- **F12**: Render the scene from the camera view.

---

## Materials & Shading

- **Materials Tab**: Use to set base colors (e.g., Red).
- **Shading Workspace**:
  - `Shift + A` → Add *Image Texture* → Connect to *Base Color* of *Principled BSDF*.
  - `Shift + A` → Add *Mapping Node* → Connect to *Vector* of Image Texture.
  - `Shift + A` → Add *Texture Coordinates* → Connect to *Vector* of Mapping.

---

## UV Editing

- **UV Sync Selection**: Enable for unified selection.
- **Manifold Check**: Ensure clean geometry (no holes or overlapping faces).
- **Fix Normals**: Flip/recalculate normals as needed.
- **Z-Fighting**: Avoid overlapping faces.
- **Merge by Distance**: Clean up stray vertices.

---

## Object Operations

- **Shift + A** → Add Mesh (e.g., Monkey).
- **Wok Quad** (possibly "Weld Quads"): Join quad faces.

---

## General Modeling Tips

- **Avoid N-Gons**: Stick to tris/quads for better topology.
- **Viewport Shading**: Use different modes (Solid, Material Preview, Rendered).
- **Clear Inside/Outside Geometry**: Keep models clean and efficient.

---

*Pro tip:* Save incremental versions of your `.blend` files (`filename_v1.blend`, `filename_v2.blend`) to prevent data loss.

