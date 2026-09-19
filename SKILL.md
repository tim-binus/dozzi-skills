---
name: dozzi-photography
description: Plan, generate, edit, and review DOZZI sleep-mask photography using its product construction, supplied models, selected images, and brand direction. Use for DOZZI product shots, bundle thumbnails, PDP features, relatable scenes, lifestyle and casual phone-style imagery, including email image selection.
---

# DOZZI photography

Make each image do one job while keeping DOZZI recognisable across a collection. The user wants the product, person and environment to look photographed together. “Million-dollar brand” means convincing materials, deliberate light, comfortable expressions and consistent art direction—not gloss, luxury props or a new visual identity for every frame.

## Start with the appropriate references

Paths below are relative to this skill folder. Resolve them to absolute paths before passing images to tools.

1. Read [product anatomy](references/product.md) for any image showing a mask. This includes source precedence and wearing instructions.
2. Read [brand and shoot modes](references/brand-and-modes.md) for a new scene or series.
3. Use [reference routing](references/reference-guide.md) to choose a small, relevant set of images. [image-index.json](references/image-index.json) records every bundled image's original path, purpose and hash. Open the actual selected images; filenames are not sufficient.
4. For generation or edits, use [prompt and review workflow](references/workflow.md). It contains the repeated failure cases from the user's feedback.

## Non-negotiable product checks

- Nose insert aligns with the wearer's nose bridge in face coordinates, including head tilt; it is not an arbitrary triangular decoration.
- Wide soft wraparound band runs **outside the hair**: 头发在里面，眼罩在外面. Do not create a narrow elastic, buckle or strap threading underneath the hair.
- Rear closure follows the supplied opened-band reference: broad overlapping textile ends and pale soft contact surfaces for Apricot. Do not invent a hard fastener or a closed narrow loop.
- Black is a textured deep charcoal, not featureless pitch black. Apricot is a pale warm oatmeal/ivory, not orange or yellow.
- DOZZI logo stays on the front panel in its physical location, with perspective following the cloth; it must not drift onto the temple or wraparound side.
- Keep the product's physical scale plausible relative to a head, hand or pocket. No miniature mask, inflated padding or rigid slab.

## Workflow and scope

For a new creative direction, draft scenes, prompts and selected references before generating. For a series, establish one anchor image first, then use the accepted anchor across the remaining images. Existing approval to generate a planned batch or make a specific edit is sufficient; do not restart approvals unnecessarily. A request for a draft only is not permission to generate.

Preserve the user's current scope: “product showcase in Apricot” does not exclude Black variants or mixed packs. “Existing models only” applies to the established branded gallery, not automatically to a separately requested avatar campaign. Current explicit instructions outrank historic defaults.

Use the available image-generation/edit tool and follow its current reference-input rules. Never claim to have supplied a reference that was only mentioned as text. For edits, preserve unrelated composition, model, palette and background. Save deliverables to persistent project output paths; do not rely only on temporary generated-image URLs.

Creation does not authorize Shopify uploads, theme updates or email sends. Local previews remain local unless the user requests deployment. For casual AI scenes, describe them as generated lifestyle/casual imagery, never verified customer photos, purchases or testimonials.
