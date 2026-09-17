---
name: dog-folder-icon
description: Turn a real pet photo or breed description into a consistent minimalist dog-face folder icon, and create twelve activity variants as independent transparent PNGs for Mac/Windows.
---
# Dog Folder Icon

## Trigger
Use when the user uploads a pet photo, requests a dog folder icon, requests a named activity variant, or requests a matching set. Ask for a photo only if neither a photo nor an approved character master is available. Do not assume breed from appearance when uncertain.

## Short-prompt defaults
- Treat “给金毛做一套”, a pet photo plus “帮我做一套文件夹图标”, and similarly short requests as complete. Do not ask the user to restate this skill's style, states, dimensions, transparency or platform requirements.
- “一套 / a set” means all twelve canonical states as twelve separate files. A named state means that state alone. “一个 / an icon” without a named state means `daily`.
- A breed name alone is sufficient character input. A pet photo is sufficient individual character input; ask only when a crucial identity feature is obscured or materially ambiguous.
- Briefly state the inferred scope and proceed. Do not require approval of a rewritten long prompt. Establish one base character master before deriving a set.

## Priority of references
1. `references/style-standard.png`: mandatory visual language, extracted from the user's approved six-icon desktop screenshot. This image is a STYLE reference only, not a character identity reference.
2. User's actual pet photo: individual appearance and markings only, not background, lighting, accessories or photographic rendering.
3. Approved generated base icon: immutable CHARACTER MASTER for subsequent variants. If no master exists, make and approve a base icon first.
4. `references/variant-sheet.png`: object-placement inspiration only; it is a contact sheet, NEVER the requested final output.

## Non-negotiable style lock
- The dog's face IS the folder's front surface. Keep a recognizable horizontal rounded folder and visible top-left tab; never paste a separate dog head onto a folder.
- Smooth silhouette, sparse flat geometric color blocks, small solid eyes, simple nose/mouth, integrated ears. No realistic fur, hair strands, photorealism, glossy highlights, gradients, heavy shadows, outlines, complex scenery or text.
- Keep the same folder skeleton, tab, face position, scale, palette, ear silhouette and markings for one character across variants. Preserve pet-specific markings using only the minimum necessary large shapes. Do not add white muzzle fur to a golden retriever unless present in the reference.
- Lock character identity, not the base icon's temporary expression. The daily tongue is state-specific and must not be inherited automatically. Redesign eyes and mouth for each activity; avoid repeating one mouth expression so often that the set feels interchangeable.
- One dog, one state, one icon per image. No grids, sheets, collages, labels, desktop mockups or checkerboard painted into pixels.
- Default output: one independent 1024×1024 RGBA PNG with genuine transparency. This is the shared high-resolution source for macOS and Windows. Center every icon consistently and keep all visible artwork inside a 10% safe margin so tabs, ears and props do not clip when scaled or previewed.
- A breed/photo is not permission to change the locked style. If identity conflicts with minimalism, keep 2–4 distinctive features and simplify everything else.

## Photo-to-folder workflow
1. Inspect the actual uploaded photo. Identify main coat colors, placement of major markings, ear type, muzzle and eye arrangement; ignore photo lighting, background, harness, clothing and props unless requested. If a crucial feature is obscured, avoid inventing it.
2. Convert these features into 2–4 signature flat shapes. Build the folder silhouette first, then merge ears and facial color patches into its front.
3. Produce ONE base icon. Use it as character master for silhouette, markings, palette and facial-feature placement; do not treat its expression as immutable. For a set, proceed without asking the user to write or approve twelve prompts.
4. Apply exactly one activity per file. Choose activity-appropriate eyes and mouth instead of copying the daily smile/tongue. Keep props large, simple, subordinate and physically interactive.
5. Validate silhouette, identity, style, count, transparency, canvas size and safe margin. Inspect downscales at 16, 32, 64, 128 and 256 px; identity and the main prop must remain recognizable at 32–64 px without clipping. Correct failures before delivery.

## Twelve canonical states
These are the 12 slots in the user's approved set; 'work' replaces 'backpack/travel'.
| Key | State | Visual treatment |
|---|---|---|
| daily | 日常 / Daily | Simple smile; a small tongue is allowed here. |
| music | 聽音樂 / Music | Headphones worn over head and ears; relaxed mouth, normally no tongue. |
| play | 玩耍 / Play | Tennis ball visibly held in mouth; no tongue. |
| eat | 吃飯 / Eat | Food bowl at bottom; closed or small eating mouth, no default tongue. |
| sleep | 睡覺 / Sleep | Closed eyes and mouth, two paws, optional tiny Z; no tongue. |
| think | 思考 / Think | Small three-dot thought bubble and restrained puzzled/closed mouth; no tongue. |
| read | 閱讀 / Read | Open book held by paws below eyes; calm closed or tiny smile, normally no tongue. |
| photo | 拍照 / Photo | Camera held by paws with one lens; attentive closed or tiny smile, normally no tongue. |
| celebrate | 慶祝 / Celebrate | Small party hat; joyful open mouth allowed but tongue is optional, not automatic. |
| work | 工作 / Work | Laptop with paws on sides; focused closed or tiny smile, no tongue. No backpack or straps. |
| paint | 畫畫 / Paint | Brush in mouth or paw plus small palette; if brush is in mouth, no tongue. |
| coffee | 喝咖啡 / Coffee | Mug near mouth or paw with restrained steam; sipping/closed mouth, no tongue. |

For any named state, output that state alone unless user explicitly requests a batch. For a batch, generate/export twelve SEPARATE files, not one contact sheet. If the image tool can only deliver a sheet, do not pretend it satisfies separate files; split only if each icon is complete and transparency can be verified, otherwise generate individually.

## Quality gate
Reject and revise when: no obvious folder tab; separate pasted-on head; changing identity; repeated tongue/mouth expression across unrelated states; excessive realism; ambiguous accessory interaction; illegible at 32–64 px; artwork crosses the 10% safe margin or clips; multiple icons in one deliverable; fake/nontransparent background; non-square or wrong dimensions. Inspect the actual alpha channel when possible.

## Deliverables
Use filenames `dog-folder_<character>_<state>.png`. Provide 1024×1024 transparent PNGs as cross-platform source files. If the user explicitly requests install-ready formats and converters are available, also derive a proper multi-resolution `.icns` for macOS and a Windows `.ico` containing 16, 24, 32, 48, 64, 128 and 256 px layers; retain the PNG originals. Never rename a PNG to pretend it is ICNS/ICO.
