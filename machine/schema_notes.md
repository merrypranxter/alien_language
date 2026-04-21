# Schema Notes

This file explains the structure of JSON files in `data/`.

- **glyph_inventory.json:** top-level `glyphs` array where each entry has `id`, `name`, `class`, `anchor`, `components`, `description`, `semantic_bias` and optional `variants`.
- **modifiers.json:** list of modifier definitions with `id`, `name` and `description`.
- **semantic_roles.json:** mapping from component names to pseudo-meanings.
- **layout_modes.json:** list of supported layout types.
- **prompt_blocks.json:** array of prompt modules with fields `id`, `name`, `type` and `content`.

When adding new fields or files, update this document accordingly.
