---
name: scene-to-3d-diorama
description: Turn a supplied landscape photograph, game screenshot, or illustration into a standalone three-dimensional miniature diorama. Use when the user asks to transform an image into a 3D scene, miniature landscape, tabletop model, or terrain diorama.
---
# Scene to 3D Diorama

Turn a source image into one freestanding miniature scene. The result is an AI-generated image of a model, not a 3D mesh or a fabrication-ready asset.

## Workflow

1. **Read the source.** Identify its main subject, recognizable landmarks, color and lighting, and their spatial relationships. Map the existing high points, low points and any paths or water flow. If the source is missing or ambiguous, ask the user to supply or identify it.
2. **Design the miniature.** Reconstruct the source as a physical tabletop model seen from an elevated three-quarter angle. Select a base suited to the scene—thin terrain slice, rock foundation, shallow pool or another appropriate shape. Thickness is a design choice, not the source of terrain relief.
3. **Build depth.** Give mountains, cliffs and buildings real volume and visible sides; cut valleys, riverbeds and pools into the terrain with visible interiors and cavity shadows. Preserve high/middle/low relationships and make water flow downhill. For relatively flat sources, use their actual local variations rather than inventing mountains or deep canyons. Exaggerate vertical relief enough to read at miniature scale while retaining the source's identity.
4. **Generate an image edit.** Supply the actual source image to an image-editing tool; if the user provides a style reference, distinguish it from the scene source. Make figures, trees and buildings separate three-dimensional models with natural ground contact, overlap, lighting and shadows. Use material and base choices appropriate to the scene. By default, output only the standalone diorama, without the source image, collage, UI, text or watermark. Include a comparison only if requested.
5. **Inspect and deliver.** Check that recognizable scene elements are present, the model is visibly three-dimensional rather than a screenshot on a flat tray, and source-appropriate high and recessed areas can be read. If not, revise and inspect again. Save the result and identify it as AI-generated.

## Boundaries

- This skill describes a workflow; it requires an image-generation tool that can edit using a reference image. It does not provide a model, API key, image generator, or guaranteed pixel-for-pixel preservation.
- Preserve the subject and spatial relationships rather than copying unrelated objects from a style reference. AI may change or invent details; describe results accurately.
- Confirm rights to source images and any output use. For commercial or public publication, check applicable permissions, platform AI-disclosure rules and client approval.
