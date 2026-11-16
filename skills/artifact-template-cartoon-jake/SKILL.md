---
name: artifact-template-cartoon-jake
description: 'Create or edit 2D cartoon images using the three saved Cartoon Jake references. Use when the user requests Cartoon Jake, a Jake-inspired style, or this template. Maintain character design, linework, and color while depicting movement, physical effort, surface effects, and coherent shadows. Apply to other subjects when this style is requested.'
---

# Cartoon Jake

Create expressive cartoons with rounded silhouettes, flexible limbs, clean black outlines, and vivid flat colors. Use detail to make actions, expressions, contact, weight, and spatial relationships easy to read. The user's requested subject and explicit changes take precedence over the defaults below.

## Visual references

Resolve `artifact-template.json` and all relative paths from this skill's directory. Preserve the saved reference files.

| Reference | What to study | Source presentation elements |
| --- | --- | --- |
| [assets/reference.png](assets/reference.png) | Base proportions, expressions, linework, and flat colors, especially Jake's face and body. | The checkerboard is baked into the pixels. Use the characters as the style reference and follow the requested background. Include Finn only when the scene calls for him. |
| [assets/reference-action.png](assets/reference-action.png) | Strong lines of action, flexible limbs, lively silhouettes, and clear foreground/background overlap. | Treat the title, logos, surrounding cast, and print texture as features of the source poster. |
| [assets/reference-contact.png](assets/reference-contact.png) | Squash and stretch, physical contact, facial reactions, and simple outdoor staging. | Treat the subtitles, logo, black bars, and compression artifacts as features of the source capture. |

- Inspect all three images when first applying the skill. Reuse those observations throughout the same task.
- Supply the base reference and relevant supporting images as actual image inputs to the generation tool. Explain each input's role. Verify that the tool receives the images alongside the prompt.
- When drawing Jake, retain his recognizable character design. When drawing another subject, retain that subject's face, clothing, and defining colors while applying this style's linework, simplification, and movement.
- Adapt the pose and composition to the request. Choose supporting characters, text, and scenery according to the requested scene.

## Visual style

- Use smooth black or near-black outlines, rounded corners, and economical interior marks. Keep the apparent line weight consistent at the same viewing scale and emphasize overlaps selectively.
- Jake's defining features are his warm golden-yellow body, large white eyes outlined in black, small black nose, rounded muzzle, soft torso, and slender flexible limbs. Keep the relative sizes and spacing of his facial features consistent. Approximate colors sampled from the base reference are `#FDBB1B` and `#FFCE1E` for yellow and `#020203` for the outline. Adjust these starting points to the user's palette and lighting.
- Build the image from broad flat fills. Convey volume through restrained cel shading, overlap, and contact shadows. Keep fur, skin, musculature, and material surfaces at the reference's simple cartoon level.
- Show effort in a loaded foot or calf with a slight contour bulge, a short curved mark, or compression of the sole. Keep the character's overall proportions recognizable as the pose changes.
- Use squash and stretch to support the action while retaining facial identity and the underlying body design. Check that the pose remains readable with the effects removed.

## Creation workflow

1. Identify the subject, action, expression, viewpoint, surface, background, and intended use. For an edit, distinguish the requested changes from the elements to preserve. Reuse any established production settings.
2. Establish the stable features of the face, body, palette, line weight, camera, and lighting. Define the pose changes separately. For a series, use the same approved reference throughout and compare new images back to it to control drift.
3. Read [references/motion-and-light.md](references/motion-and-light.md) when movement, ground contact, or lighting is important. For running, specify the supporting foot, direction of propulsion, surface response, and shadow placement. Choose effects appropriate to the action.
4. For a standalone image with an unspecified setting, choose a simple background that keeps the subject readable. Use a single light from the upper left and toward the viewer as a production default. Follow established scene lighting or the user's chosen light when available.
5. Use the available `imagegen` skill and image generation tool. Include the image roles, requested action, stable design features, contact and surface effects, lighting, shadows, and output requirements in the prompt. Generate the requested background explicitly. For transparency, request a real alpha channel.
6. Inspect the result against the checks below. When correcting a defect, retain the successful face, colors, and composition and focus the next edit on that defect. If targeted corrections repeatedly fail, report the remaining issue and the current result.

## Visual checks

- Compare the face, proportions, linework, and colors with the references.
- Check that the loaded body parts, planted and lifted feet, movement direction, and phase of the action agree. Confirm that every limb and joint connects clearly.
- Check that dust, droplets, or debris originate at the relevant contact point, match the surface, and leave the face and footwork readable.
- Check that lit surfaces, form shadows, and cast shadows share the same light source. Distinguish ground contact from airborne parts.
- For a full-body request, keep the hands, feet, and necessary effects within the frame. Check the output for stray checkerboards, source logos, and captions.

Compare a series using the same camera and lighting conventions. Replace a saved reference only when the user explicitly approves that change. Save project assets to the requested output location and briefly report what was generated, what was inspected, and where the files were saved.
