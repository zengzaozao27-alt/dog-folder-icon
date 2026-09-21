# Dog Folder Icon Skill · v1.4.4

Turn a breed name or a real pet photo into a minimalist dog-face folder icon, or twelve consistent activity variants. Short prompts such as “给金毛做一套” or a photo plus “帮我做一套文件夹图标” are sufficient.

**Current specification:** [`SKILL.md`](SKILL.md). It locks the approved left-side folder tab and character identity, corrects camera-perspective artifacts, and asks for an approximately balanced *outer fur/cheek contour only*. Do not mathematically mirror the whole folder, authentic markings, ears, expressions, or accessories. The daily master must pass this contour check before variants are made.

The twelve states are daily, music, play, eat, sleep, think, read, photo, celebrate, work, paint and coffee. Expressions must fit each activity; do not copy the daily tongue into every icon. Backpack is not part of the approved set.

## Installation and references

Place this repository in your agent's skills directory and read [SKILL.md](SKILL.md). Before generation, the agent must view the user's pet photo and all three bundled references:

| Reference | Purpose |
|---|---|
| [style-standard.png](references/style-standard.png) | Approved style screenshot: flat visual style and folder proportions. |
| [variant-sheet.png](references/variant-sheet.png) | Activity composition inspiration; not a deliverable layout. |
| [September 18 reference](<references/ChatGPT Image 2026年9月18日 20_48_22.png>) | User-approved additional visual reference; load alongside the other two within the skill's fixed visual grammar and integrated-front requirements. |

These links point to the actual files included in this repository; no separate reference ZIP is required. The user's pet photo determines identity. Reference dogs must not replace that pet. Follow the reference-loading and precedence instructions in SKILL.md, and disclose any reference that cannot be loaded.

This repository's reference images are raster references, **not editable SVG character masters**. An agent must have an image tool capable of receiving the actual pet photo and references, or an approved editable vector master for that same pet. Otherwise it must disclose the limitation rather than silently draw a different dog.

## Output

One 1024×1024 transparent PNG per state, twelve separate files for a set. Verify real alpha and appearance at small sizes. Genuine macOS `.icns` and Windows `.ico` conversions are optional when requested and supported. A skill alone does not bundle an image-generation model or guarantee identical outputs across models.
