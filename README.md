# Dog Folder Icon Skill · v1.4.2

Turn a breed name or a real pet photo into a minimalist dog-face folder icon, or twelve consistent activity variants. Short prompts such as “给金毛做一套” or a photo plus “帮我做一套文件夹图标” are sufficient.

**Current specification:** [`SKILL.md`](SKILL.md). It locks the approved left-side folder tab and character identity, corrects camera-perspective artifacts, and asks for an approximately balanced *outer fur/cheek contour only*. Do not mathematically mirror the whole folder, authentic markings, ears, expressions, or accessories. The daily master must pass this contour check before variants are made.

The twelve states are daily, music, play, eat, sleep, think, read, photo, celebrate, work, paint and coffee. Expressions must fit each activity; do not copy the daily tongue into every icon. Backpack is not part of the approved set.

## Installation and references

Place this repository in your agent's skills directory and read `SKILL.md`. The bundled `references/style-standard.png` is the approved style screenshot; `references/variant-sheet.png` is composition inspiration, **not** a deliverable. A user's pet photo determines that pet's identity. If the user supplies a newer approved character or full-color reference, load it as directed by `SKILL.md`.

This repository's reference images are raster references, **not editable SVG character masters**. An agent must have an image tool capable of receiving the actual pet photo and references, or an approved editable vector master for that same pet. Otherwise it must disclose the limitation rather than silently draw a different dog.

## Output

One 1024×1024 transparent PNG per state, twelve separate files for a set. Verify real alpha and appearance at small sizes. Genuine macOS `.icns` and Windows `.ico` conversions are optional when requested and supported. A skill alone does not bundle an image-generation model or guarantee identical outputs across models.
