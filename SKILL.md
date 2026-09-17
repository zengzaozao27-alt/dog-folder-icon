---
name: dog-folder-icon
description: Convert a real pet photo or breed request into a consistent minimalist dog-folder icon, or twelve independent activity variants.
---
# Dog Folder Icon — reference-locked v1.4.2

## Short requests
Accept a pet photo plus “帮我做一套文件夹图标”, “给金毛做一套”, or a request for a single named state. Do not require a long prompt. A set means the twelve states below, each in its OWN file; a single unspecified icon means daily. Reuse the current pet photo or approved master without asking again.

## Mandatory reference loading and precedence
1. VIEW `references/style-standard.png` as the approved six-icon screenshot STYLE authority. It is not a pet identity source or output background. If the user's latest approved reference supersedes it, use that reference.
2. VIEW the actual pet photo for identity ONLY: coat-color distribution, authentic markings, ear shape and facial proportions. Ignore lighting, harness, background, head turn, posture and camera angle. Any left/right outline difference caused by perspective is an artifact: discard it, never encode it in the permanent silhouette. Do not discard real asymmetric markings.
3. VIEW any previously approved base icon for THIS pet as the CHARACTER master. Never replace the pet with the reference dog.
4. VIEW `references/variant-sheet.png` only for state composition, not as a final-output format. If newer approved full-color examples are supplied, use them as visual targets. Never claim an unavailable example was loaded.
Priority: latest user-approved artwork > approved style reference > same-pet character master for identity/geometry > state references > prose. Photo controls identity, approved artwork controls style. A raster reference is NOT an editable vector master.

## HARD tool-capability gate
Before generating, determine whether you can (A) actually inspect the photo and references; (B) supply them to an available image-generation/editing tool; (C) alternatively edit an approved editable vector master of this EXACT pet; and (D) export/verify real transparent PNG files. Preferred path is A+B+D. Controlled vector path is A+C+D and may edit only permitted layers. If neither path works, STOP and explain the limitation. Never silently substitute a hand-coded SVG, a generic breed drawing, another dog, a schematic, or a collage. Never claim reference loading, generation, transparency tests, or completed files without actually performing them. An image-reading tool alone does not imply that the image generator received the references.

## Fixed visual grammar
- The dog's face IS the folder's flat front, not a separate sticker. Preserve the approved wide horizontal rounded folder, original LEFT-SIDE tab, integrated ears, proportions and visual scale. Never center or duplicate the tab to satisfy symmetry.
- Large smooth flat color blocks, minimal eyes/nose/mouth and 2–4 identity features. Simplify texture, NOT identity or silhouette. No realistic fur, strands, 3D, glossy highlights, gradients, heavy outlines, extra scenery, labels or floating emoji. Do not invent triangular ears for a floppy-eared pet or white muzzle markings not present in the photo.
- Lock folder skeleton, tab, character colors, markings, eye/nose placement and head/ear silhouette across states. Change expression and activity props as needed, not the character identity. Props must interact naturally with head, mouth or paws.
- FRONT-FACING FUR SILHOUETTE (mandatory): reconstruct the dog's outer head fur and cheek contour as a clean front-facing design. Its LEFT and RIGHT sides SHOULD closely correspond in overall width, volume, prominent tufts and curvature, with small natural differences allowed. Do NOT trace the photo's side-angle outline. If one side has an accidental bulge, narrow cheek or tuft caused by head rotation, correct it; where appropriate, give a matching shape on the other side. This is a rule for the OUTER FUR/CHEEK CONTOUR ONLY, not mathematical symmetry of the entire icon. The left tab, genuine coat markings, real ear differences, expressions and off-center accessories may remain asymmetric. Ears should look balanced, not mechanically identical.

## Photo -> icon workflow
Inspect photo -> select 2–4 defining identity features -> classify each as authentic identity marking (keep; may be asymmetric) or camera/perspective artifact (discard) -> simplify into a FRONT-FACING design with approximately balanced outer fur/cheek contours -> apply the approved folder skeleton and left tab -> make ONE daily character master -> correct it -> reuse/edit it for variants. If a feature is obscured, do not invent it. A set request does not require twelve new user prompts.

## Mandatory image-generation prompt fragment
Include this phrase in EVERY generation prompt alongside actual references and pet identity: “front-facing view, approximately left-right symmetric outer fur and cheek contour, balanced ears, preserve the approved left-side folder tab and original folder geometry”. Explicitly correct camera-angle bias; do not force the entire icon, markings or accessories to mirror.

## Twelve canonical states
Backpack/travel was rejected and replaced by WORK.
| Key | State | Action |
|---|---|---|
| daily | 日常 | Friendly baseline face |
| music | 音乐 | Headphones worn over ears |
| play | 玩耍 | Tennis ball held in mouth |
| eat | 吃饭 | Food bowl in front; eyes visible |
| sleep | 睡觉 | Closed eyes, tiny paws; optional small Z |
| think | 思考 | Small three-dot thought bubble |
| read | 阅读 | Open book held by paws |
| photo | 拍照 | Simple camera held by paws |
| celebrate | 庆祝 | Small party hat; no clutter |
| work | 工作 | Laptop in front, paws interacting; optional mug; NO backpack |
| paint | 画画 | Brush and simple small palette |
| coffee | 咖啡 | One cup near mouth/paw |

Each state SHOULD carry its own fitting expression instead of copying the daily face unchanged — tongue only where natural (daily/play/eat/celebrate), closed mouth for focused states (work/read/photo/paint/coffee/think), and closed eyes only for sleep. A ball or brush occupying the mouth must not conflict with a tongue. Music should use a relaxed expression rather than an automatic tongue. The daily expression is not an immutable face template.

## REJECT examples
Reject: dog becomes a different breed or coat color; floppy ears become pointy; pet head pasted on a folder; tab absent, moved or duplicated; generic schematic or photorealistic drawing; same tongue on every state; backpack straps on paws; props floating or overpowering the character; one grid instead of individual outputs; checkerboard painted into the background; outer fur/ear outline asymmetric because the source photo was shot from a side angle. These are failures, NOT references.

## Batch and delivery gate
Make and inspect the DAILY master FIRST. Hide/ignore tab and props when comparing the two OUTER FUR/CHEEK contours around the face centerline: approximately matching cheek width, volume, major protrusions and curvature are required. A visibly distorted or shifted head = FAIL; fix the daily master BEFORE generating variants. Do NOT mirror or compare the full icon alpha mask: the legitimate left tab and props make whole-icon IoU/pixel-difference checks invalid. An optional fur-only layer comparison is acceptable if a real isolated mask exists; otherwise use visual inspection and do not claim an automated symmetry test. Check variants inherit the corrected master.

Deliver one independent 1024×1024 transparent RGBA PNG per requested state, with consistent padding and clear appearance at 64px. For a set, deliver twelve PNGs; a contact sheet is optional EXTRA preview only when requested. Verify dimensions, actual alpha/transparency, filenames, number of files, visible identity and accessory placement; disclose anything unverified or incomplete. A white/checkerboard image is not proof of transparency. If explicitly requested and tools permit, convert to genuine multi-size Windows `.ico` and macOS `.icns`; never rename a PNG extension. A SKILL.md does not contain an image-generation model or guarantee identical output across models.
