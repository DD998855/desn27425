# Duck Project 1 Integration — v006

Date: 2026-10-16

## Purpose

Integrate the final duck render and the local interactive GLB viewer into Published 3D Model 2 while matching the layout, scale, behaviour, and English presentation of the completed smartwatch entry.

## Source Evidence

- Eight photographic views of the physical duck were used during the modeling process.
- The final presentation render is `duck-hero-v004.png`.
- The interactive asset is `Duck_v003d.glb`, based on the final adjusted `.001` collection.
- The first AI-assisted clay model captured the character but produced a rear and lower-body silhouette that was too flat.
- The rear vertices were manually adjusted in Blender with Proportional Editing to create a fuller backside closer to the reference photographs.
- The approved geometry was developed from a white clay study into a yellow molded-plastic material version.
- A physical 3D-print test was attempted at 0.12 mm layer height with automatic tree supports. The body and several appendages formed, but the supported bill and front facial area failed.

## Web Presentation

- Reused the smartwatch entry's `project-model-summary`, `project-model-thumb`, `project-model-copy`, and `project-model-frame` classes.
- Replaced the placeholder image and external iframe in Published 3D Model 2.
- Added an English reflection paragraph outside the modal.
- Added the approved square hero render as the clickable cover image.
- Added a detailed English process account inside the modal.
- Embedded the local offline duck viewer below the process text.
- Kept all viewer labels, loading states, instructions, accessibility text, and captions in English.
- Preserved the same 50% thumbnail width, borderless presentation, modal width, image-first sequence, and responsive iframe behaviour used by the smartwatch.

## Technical Delivery

- Hero image target: `images/final/duck-hero-v004.png`
- Viewer target: `models/duck/index.html`
- GLB target: `models/duck/Duck_v003d.glb`
- Local viewer library target: `models/duck/model-viewer.min.js`
- Main page target: `index.html`

## Verification Checklist

- [x] Main-page copy is English.
- [x] Modal title and detailed process copy are English.
- [x] Viewer interface and error/loading states are English.
- [x] Duck cover uses the same class and width as the smartwatch cover.
- [x] No decorative pink border is added to the image.
- [x] Hero render appears before the detailed process text and interactive viewer.
- [x] Viewer uses the final adjusted model.
- [x] Source files remain preserved.
- [x] Staged browser verification confirmed equal 377 px cover widths, zero image borders, a 720 px modal image, correct English copy, a working local iframe, the interactive success state, and no browser console errors.

## Deployment

- A timestamped copy of the previous main page was preserved in the website's `backups` folder before replacement.
- The verified main page, hero image, offline viewer, GLB, and local model-viewer library were copied to the requested Project 1 website.
- SHA-256 comparisons were used after copying to confirm that the deployed files match the tested staged files.

