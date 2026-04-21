# Glyph Naming System

Assign each Oraphine glyph a unique identifier and descriptive name. Use the following conventions:

- IDs start with **G** for glyph, **E** for elevated glyph, **S** for sigil, **D** for divider mark or **M** for modifier.
- Followed by a three‑digit number (e.g., `G001`, `S005`).
- Names describe the visual structure, such as *Right-Crescent Stem* or *Forked Eye Chamber*.
- When creating new glyphs, update the JSON inventory in `data/glyphs/` and provide descriptions in `docs/02_glyph_families/`.

Consistent naming helps maintain order and allows code to reference glyphs programmatically.
