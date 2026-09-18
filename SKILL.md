---
name: dog-folder-icon
description: Turn a pet photo or breed request into an integrated dog-shaped folder icon and twelve consistent activity variants.
---
# Dog Folder Icon — v1.4.3 integrated-front fix

## Short requests and reference loading
Accept a pet photo plus “帮我做一套文件夹图标”, “给金毛做一套”, or a named state without requiring a long prompt. A set means twelve separate files; one unspecified icon means daily. Reuse an available same-pet approved master.

BEFORE drawing, actually VIEW the supplied pet photo and the approved visual references. In the complete ZIP, `references/approved-style.jpg` is the approved six-icon screenshot and STYLE authority; `references/approved-full-color-six.webp` and `references/example-<state>.webp` are color/composition examples; `references/approved-black-dog-base.png` is a character reference ONLY for that exact black dog. Do not substitute the reference dog's identity for the user's pet. In installations without these exact files, use only genuinely available user-approved references and disclose missing ones; never pretend they were loaded. A raster reference is NOT an editable vector master. User photo supplies identity ONLY: coat distribution, markings, ear shape, facial proportions. Discard camera-angle, head-turn and posture distortions, not genuine asymmetric markings.

## HARD capability gate
Check whether you can actually inspect the photo/references AND pass them to an image-generation/editing tool AND export genuine transparent PNGs; alternatively, whether you have an approved EDITABLE vector master for THIS EXACT pet and can edit/export it. If neither path works, STOP and explain. Never silently replace generation with hand-coded SVG, generic breed art, another pet, HTML/CSS or a contact sheet. Never claim reference use or verification that did not occur.

## P0: DOG IS THE FOLDER — mandatory geometry
**The dog IS the folder, not a decoration ON a folder. The dog's face and cheek-color regions constitute the folder's entire front panel.** The outer left/right cheek or fur contours and lower rounded edge form ONE continuous integrated folder silhouette. Major facial/coat-color shapes must extend naturally into the front panel, down toward its bottom and out toward its sides as appropriate for the pet's markings. The bottom may be a large single coat-color area only if it is visibly part of the dog's integrated face/body design; it must NOT look like a separate empty stationery folder under a small floating head.

**DO NOT draw a complete conventional blank folder first and paste, overlay, center, or perch a smaller dog head on top.** Do not draw a separate circular/oval dog-head silhouette with its own visible bottom boundary over a plain rectangular folder. No seam, halo, sticker border, exposed blank lower folder slab, or independent dog-head layer. The ONLY conventional folder cue is the subtle approved LEFT-SIDE top tab behind the integrated dog-shaped front. The dog-face color/cheek design and folder front must share a single continuous outer contour. The ears emerge organically from this unified silhouette.

**Construction order (overrides any older 'folder skeleton first' instruction):** (1) use the approved wide, horizontal rounded folder proportions as a GEOMETRY GUIDE ONLY, not a separately drawn blank object; (2) construct ONE integrated dog-colored front silhouette with cheeks/fur reaching its side and lower edges; (3) add the subtle original LEFT-SIDE tab behind it; (4) place coat markings, ears and facial features ON this integrated front; (5) add ONE state accessory. Never start with a completed yellow/plain folder. If a pet has a white muzzle, the white patch can be an internal flat color shape, but it cannot create a separate floating head outline.

**Mandatory prompt fragment, verbatim in every image-generation prompt:** “The dog IS the folder: one continuous integrated dog-face front panel extending to the folder's bottom and side edges; no separate dog head, no blank folder slab underneath, no pasted-on sticker; subtle original left-side tab only; front-facing view, approximately balanced outer fur and cheek contour.” Supply the actual pet photo and approved style examples alongside this text whenever supported.

## Other fixed visual grammar
- Preserve the approved wide horizontal rounded shape, left-side tab, integrated ears, flat large color blocks, minimal eyes/nose/mouth and 2–4 pet-specific identity features. Simplify texture, NOT identity or silhouette. No realistic fur, hair strands, glossy highlights, gradients, 3D, heavy outlines, complex scenery or text. Floppy ears stay floppy; do not invent white muzzle fur.
- Reconstruct a front-facing outer FUR/CHEEK contour with approximately balanced left/right width, volume, tufts and curvature. Correct side-photo distortion, but do NOT mirror the whole icon: left tab, genuine asymmetric coat markings, ear details and off-center accessories remain legitimate. Ears should look balanced, not mechanically identical.
- Lock the approved SAME-PET daily master geometry, colors, marking placement, ear silhouette, face proportions and icon scale across all states. Change only appropriate expressions and props. Props must interact naturally with head, mouth or paws.

## Photo -> icon workflow
Inspect photo -> select 2–4 identity features -> classify authentic marking versus perspective artifact -> reconstruct front-facing balanced fur/cheek silhouette -> construct ONE integrated dog-colored folder front (NOT a separate blank folder) -> add left tab, internal markings, ears and features -> produce and CHECK one daily master -> only then reuse/edit it for other states. A request for a set does not require twelve extra prompts or approval of a rewritten prompt.

## Twelve states
Backpack/travel was rejected and replaced with work.
| Key | Visual action |
|---|---|
| daily | Friendly baseline expression |
| music | Headphones worn over ears |
| play | Tennis ball held in mouth |
| eat | Food bowl in front |
| sleep | Closed eyes and tiny paws; optional tiny Z |
| think | Small three-dot thought bubble |
| read | Open book held by paws |
| photo | Camera held by paws |
| celebrate | Small party hat |
| work | Laptop in front, paws interacting; optional mug, NO backpack |
| paint | Brush and small palette |
| coffee | Cup near mouth/paw |

Each state SHOULD carry its own fitting expression instead of copying the daily face unchanged — tongue only where natural (daily/play/eat/celebrate), closed mouth for focused states (work/read/photo/paint/coffee/think), and closed eyes only for sleep. No tongue conflicting with a ball/brush in the mouth. Music has a relaxed expression, not automatic tongue.

## P0 geometry acceptance gate — BEFORE any batch
Inspect the daily icon at normal size AND as a 64px thumbnail. Ask: (A) Is the dog itself the front panel, sharing the folder's sides and lower boundary? (B) Does any visible independent dog-head outline end halfway down, leaving a broad plain folder rectangle underneath? (C) Would removing the dog head leave a complete ordinary folder? If B or C is YES, FAIL even if the icon looks cute, symmetric or recognizable. Correct the daily master first; do NOT generate variants from a failed master. A plain folder plus a centered dog-head sticker, including the reported yellow-folder/corgi-head example, is a REJECTED FAILURE, never a reference. For a true integrated design, removing facial features should still leave a dog-colored, character-shaped folder front, not a complete plain stationery folder with an obvious pasted-on head.

Then check: same pet identity, genuine left tab, front-facing approximately balanced outer fur/cheek contour (ignore tab/props for symmetry), no invented pointy ears, no generic schematic style, correct props and distinct expressions. Do not compare the full alpha mask for symmetry; left tab and props are intentionally asymmetric. Reject opaque white/checkerboard backgrounds, floating props, repeated tongues, missing tab, different character across states and collages substituted for individual icons.

## Delivery
One state = ONE independent 1024×1024 transparent RGBA PNG. A twelve-state request = twelve separate PNG files; contact sheet only as explicitly requested extra preview. Verify actual alpha, dimensions, file count, consistent padding and legibility at 64px if tools permit; disclose unverified checks. Genuine multi-resolution `.ico`/`.icns` only when conversion tools are available and explicitly requested. This skill provides instructions/references, not a built-in image model or a cross-model fidelity guarantee.
