# Prompting, iterations and visual review

## Scene draft

For each proposed image state: placement, one job, scene/action, mask colour/count, model reference, composition, light/palette anchor, visible construction risks, and actual reference files. Use the user's requested number of images; don't turn every task into a large campaign.

Explain which file controls what. Typical new image references: (1) same-colour product front for geometry/material/logo, (2) visible side/rear/nose detail, (3) model identity when relevant, (4) accepted series image for light and grade. Read the selected files before generation. Do not pass the entire library blindly.

For a new series, generate one anchor after the user requests generation; let feedback establish the direction before expanding. If the user says “generate the rest” after accepting the first, proceed with the approved batch without another design questionnaire.

## Prompt scaffold (adapt, do not copy mechanically)

“Create/edit [deliverable and crop]. Use reference A for the physical DOZZI mask, B for [nose/rear/side], C for this model's identity, D for lighting/colour continuity. [One concrete scene and action]. The [Apricot/charcoal] mask has the reference's width, soft textile thickness, central ribbed nose insert and modest front DOZZI logo. [Pose-specific fitting rule]. [Physical light source, direction, softness; contact surfaces and their shadows]. [Framing and focus priority]. Preserve fine skin and fabric texture, gravity, cloth compression and natural hand support. Match [series anchor] in white balance and exposure. [Specific exclusions from actual failure history].”

For precision edits, explicitly localise the change: align the nose insert to the actual nose bridge; move the logo on the front cloth; naturally tuck the protruding rear tab. Preserve face, expression, framing, light, colour and unrelated anatomy. A previous failed generation is an edit base, not geometry truth.

For casual mode replace studio language with concrete phone conditions. Do not combine “perfect commercial softbox shoot” and “unposed customer's phone snapshot” in the same prompt.

## Quality checks before calling an image ready

Inspect at full frame, relevant detail crop and intended display size. Report meaningful defects honestly; an agent's review is not user approval.

- Product: outline, softness, same colour, correct mask count, no duplicate/invented band.
- Nose: ribbed panel tracks nose bridge and head tilt; not offset or hovering; nostrils remain plausible.
- Side/rear: wide outer-hair wrap, correct overlap/contact surfaces, no buckle/elastic substitute, no extra dangling tab.
- Logo: spelling, scale, front placement and cloth perspective. Never forced into view by a bizarre pose.
- Scale: front spans eye region naturally; believable relative to hand, head and pocket.
- Physical reality: finger count/grip, fabric indentation, pillow contact, consistent shadows, no compositing halo or texture pasted across skin/fabric.
- Person: supplied identity when required; pleasant comfortable expression appropriate to scene; coherent body pose, teeth and eyes.
- Collection: same grade, camera language and model continuity as required. No shot that looks like an unrelated brand.
- Display: product still legible at thumbnail size; mobile crop does not cut off the intended feature.

If a defect remains after a targeted revision, change the approach or ask for the specific missing reference. Do not run an unbounded sequence of nearly identical generations. Keep failed outputs separate from accepted selections.

## Delivery and future memory

Save final candidates, prompts, the reference list and a short review note under a persistent dated project output directory. Include requested changes and any unresolved issues. Status labels: candidate, user-selected, user-approved-with-corrections, or approved-final only when explicitly established. Never assume every file in a folder is final.

Preserve high-quality masters and use WebP for storefront delivery when requested. Existing Shopify WebP sources can be used with verified JPEG delivery for email compatibility; do not rename file extensions and assume conversion occurred. Image-only work does not require a Shopify push.
