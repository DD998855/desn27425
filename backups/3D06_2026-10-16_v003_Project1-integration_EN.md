# 3D 06 Hair Clip — Project 1 Copy and Integration v003

- Date: 2026-10-16
- Skill: blendsmith 2026.09.010
- Work type: Stage 3 coursework copy and Stage 4 website integration
- Source model record: `Clip_high_v01.blend`
- Source viewer: `HairClip_Web_v02`
- Cover supplied by user: `images/final/cilp.png`, 1153 × 721
- Target: Published 3D Model 3 in the Modeling & Materials Module 1 website

## User-authored Process Summary

The user described beginning with the button's basic Blender form, using cylinders and Boolean operations for the holes, revising hole size to match the real clip, building the metal structure underneath, experimenting with materials, and learning that material changes can make the same model appear completely different. The user identified the clip as one of the three final works selected for the course webpage.

## Copy Strategy

- The outer paragraph focuses on iteration, reflection, and the conceptual discovery produced by the sixteen-material comparison.
- The modal paragraph focuses on modeling evidence, functional parts, topology counts, UV/PBR structure, and the specific material set.
- Repetition is minimized: the outer text explains why the project mattered, while the modal text explains how it was made and checked.
- The AI-assisted role is stated without removing the user's authorship in reference comparison, geometric revision, material direction, selection, and presentation.

## Website Integration

- Replaced the Published 3D Model 3 placeholder.
- Reused the exact summary, thumbnail, modal-copy, and iframe classes used by the smartwatch and duck.
- Used the user's `cilp.png` as the cover.
- Added a `material-overview` modifier that preserves the complete 1153 × 721 overview inside the same square 50% thumbnail footprint without cropping any clip.
- Added the English sixteen-material interactive viewer below the process copy.
- Preserved the image-first sequence, borderless thumbnail, modal width, and responsive iframe ratio established by the previous two models.

## Technical Evidence Used in the Copy

- Nine separate editable mesh components.
- 6,108 base quads and 232 base triangles.
- 35,520 evaluated triangles.
- No detected n-gons or nonmanifold edges in the recorded verification.
- One 4096 × 4096 UV atlas.
- BaseColor, Normal, Roughness, and Metallic maps.
- Sixteen material interpretations plus a combined overview.

## Verification

- Staged file and asset checks: PASS. The cover, English viewer, local library, and all seventeen GLBs are present; the old Model 3 placeholder is absent.
- Thumbnail layout: PASS. All three Project 1 covers render at the same 377 × 377 CSS size with zero border. The hair-clip cover uses `object-fit: contain`, preserving its full 1153 × 721 composition.
- Modal layout: PASS. The supplied cover renders at its full 720 × 450 aspect ratio, followed by the English process copy and the standard 62.5% interactive frame.
- All-material viewer load: PASS. The overview reaches the English ready state.
- Material switching: PASS. Pink Glass was selected inside the embedded iframe and loaded with its matching English title, description, accessible label, and interaction instructions.
- English interface: PASS. The viewer contains no CJK characters.
- Browser console: PASS. No warnings or errors occurred during the tested overview and Pink Glass states.
- Official destination copy and hash comparison: PASS. The deployed main page, viewer page, model-viewer library, All16 GLB, and Original GLB match the staged files by SHA-256. The official viewer contains all seventeen GLBs, and the prior main page is preserved in a timestamped backup.
- Official browser verification: PASS. The deployed cover, copy, iframe, All16 ready state, and English interface loaded from the official destination with no browser warnings or errors.

