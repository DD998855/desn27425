# 3D 06 Hair Clip — English Sixteen-Material Viewer v002

- Date: 2026-10-16
- Skill: blendsmith 2026.09.010
- Work type: versioned web-presentation derivative
- Source: `HairClip_Web_v01`
- Output: `hairclip_viewer_v002`
- Scope change: the user cancelled the new cover-render stage and explicitly requested Stage 2 only.

## Confirmed Requirements

- Preserve the combined overview and all sixteen individually selectable materials.
- Use English only in the interactive webpage.
- Match the smartwatch and duck viewer language: pale blue-gray studio background, translucent rounded information surfaces, compact instructions, and local offline assets.
- Do not integrate the viewer into the Project 1 page during this stage.
- Preserve the existing Chinese viewer and all source GLBs.

## Implementation

- Reused the existing 17 GLBs: one combined all-material overview and sixteen individual variants.
- Set the overview as the initial state.
- Replaced the large permanent sidebar with a compact accessible material selector that fits the existing Project 1 iframe ratio.
- Added English material names and short descriptions explaining how each surface changes the perceived object.
- Added local controls for camera reset and automatic rotation.
- Added English loading, success, and error states.
- Retained drag rotation, wheel or pinch zoom, touch support, shadows, and neutral environment lighting.
- Used the same pale blue-gray background and translucent rounded cards as the approved duck viewer.
- Added responsive layouts for the 720 × 450 desktop embed and narrower mobile frames.

## Material Set

Original Pink, Full Gold, Soft Matte, Transparent Acrylic, Glossy Plastic, Holographic, Pink Glitter, Pink Emissive, Pink Paper, Mother of Pearl, Glazed Ceramic, Soft Silicone, Pink Glass, Pink Candy, Pink Velvet, and Pink Wood.

## Verification

- Source asset preservation: PASS. No source GLB or v01 webpage file was modified.
- English-only static scan: PASS. The page source and rendered body contain no CJK characters.
- Asset inventory: PASS. Seventeen menu states map to the combined overview plus all sixteen individual GLBs; no model file is missing.
- All-material initial load: PASS. The 21.61 MB combined GLB reaches the English ready state.
- Individual material switching: PASS. The Holographic variant loaded and displayed its matching English name, description, and interaction state.
- Reset and auto-rotate controls: PASS. Controls are present in English; the rotate button changes to `Stop Rotation` and updates its pressed state.
- Responsive embed presentation: PASS. Visually checked at 720 × 450, matching the Project 1 iframe ratio, and at 390 × 560 for a narrow mobile view. A mobile-specific camera distance prevents single variants from being cropped.
- Browser console errors: PASS. No warnings or errors were reported during the tested overview and variant states.

