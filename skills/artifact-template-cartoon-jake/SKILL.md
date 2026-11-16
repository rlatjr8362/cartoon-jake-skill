---
name: artifact-template-cartoon-jake
description: 'Create or edit 2D cartoon images using the three saved Cartoon Jake references. Use when the user requests Cartoon Jake, a Jake-inspired style, or this template. Preserve subject identity, clear visual emphasis, coordinated actions and interactions, believable contact, and coherent lighting. Apply across sports, everyday activities, quiet scenes, and fantasy when this style is requested.'
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

## Composition and focal subject

- For a protagonist-led action scene, inspect the [approved Usain Bolt composition](assets/usain-bolt-composition.png). Study its large foreground protagonist, dynamic silhouette, and smaller active supporting figures. Use it as a guide to visual emphasis and adapt the subject, activity, pose, setting, and framing to the current request.
- Establish the intended main subject or group. Make that focus immediately clear through framing, scale, placement, contrast, and detail.
- For a single-protagonist scene, give the protagonist a strong silhouette and appropriate visual prominence. Keep supporting figures legible at their smaller scale.
- Preserve an approved close-up, camera angle, crop, and subject size during corrections. Repair background poses, contacts, or perspective within that composition whenever possible.
- Check the focal subject again after every revision. A correction should retain the visual emphasis the user liked. Give a group equal prominence when the request calls for an ensemble.

## Scene-wide defaults

Apply these preferences whenever the request leaves a choice open.

- Coordinate everyone around the same event and moment, with small natural differences in reaction and pose.
- Keep balance, weight transfer, contact, and cause and effect believable. Use cartoon exaggeration in shapes, proportions, and elasticity.
- Add supporting participants when the situation calls for them, such as teammates, opponents, or a referee. Follow explicit subject counts and composition requests.
- Simplify background faces and clothing while keeping their readable actions, direction, gaze, contact, and shadows consistent with the scene.
- Choose a camera angle that makes the important movement, contact, or interaction easy to understand.
- For real people and recognizable events, verify defining appearance, representative clothing, equipment, and the key action against relevant reliable references.
- Use moderate, purposeful effects so the important force or movement is immediately readable.
- Prioritize a thorough visual review and targeted corrections before presenting a finished image.

Use these principles across active and quiet scenes, including sport, everyday tasks, conversation, cooperation, animals, and fantasy. For a portrait or symbolic composition, apply the checks that are relevant to that format. Preserve the user's explicit choices.

## Creation workflow

1. Identify the focal subject, requested moment, action or interaction, mood, viewpoint, setting, and output use. For an edit, establish the requested changes and the design features to retain, including the approved composition, crop, and subject scale. Reuse existing production settings.
2. Establish the stable face, body proportions, palette, line weight, camera, and lighting. For a series, use the same approved reference throughout and compare each result back to it.
3. For a named real person or recognizable event, inspect relevant supplied evidence and look up missing defining details through reliable sources. Prefer official athlete, team, event, museum, or creator material and original photography when relevant. Verify the subject's appearance, representative attire, equipment, and action. Match a particular year or edition when specified. If a necessary reference is inaccessible, briefly identify the resulting uncertainty.
4. Build a concise scene description. Identify the shared moment, the state of each important participant, meaningful gaze targets, and the relevant hand/object or body/surface contacts. Read [references/scene-coherence.md](references/scene-coherence.md) for scenes with multiple participants, object handling, event timing, or a sequence of panels.
5. Read [references/motion-and-light.md](references/motion-and-light.md) when movement, physical support, surface effects, or lighting needs attention. Choose a viewpoint that reveals the defining contacts and actions. Use a single light from the upper left and toward the viewer as a default, following the established scene or the user's lighting when available.
6. Use the available `imagegen` skill and image generation tool. Supply the saved style references as actual image inputs. Specify the requested scene, stable character features, shared timing, participant interactions, physical support, relevant effects, and light direction. Include background participants' actions explicitly. Request a real alpha channel for transparent output.
7. Review the generated image at both scene and detail level. Correct material inconsistencies before presenting it as finished. Retain successful visual features during each focused revision, then inspect the whole scene again for changes elsewhere. If the same problem persists after repeated focused corrections, report the remaining issue and retain the strongest result.

## Visual review

First check the whole scene for timing and spatial relationships. Then inspect the main subject, interacting objects, every readable background participant, and the lighting.

- **Visual emphasis.** Confirm that the intended protagonist or group remains immediately recognizable as the focus. Preserve the user's preferred framing and subject scale through corrections.
- **Shared moment.** Confirm that the foreground and background describe compatible stages of the same event. Natural reaction differences should fit the elapsed time.
- **Character and style.** Compare identities, proportions, linework, colors, expressions, and clothing with the chosen references.
- **Action and support.** Check balance, weight transfer, joints, grips, planted and airborne limbs, object support, and the cause of each effect.
- **Interaction and gaze.** Confirm that hands reach their intended objects, exchanged objects occupy one coherent position, and attention points toward the relevant person or action.
- **Space and background.** Check relative scale, depth, orientation, paths, lanes, furniture, and occlusion. Apply the same timing and physical logic to readable background figures.
- **Light and effects.** Align lit surfaces, form shadows, contact shadows, cast shadows, reflections when present, and environmental effects. Match particles or surface disturbances to their source and age.
- **Framing and output.** Keep required features within the frame, make essential contacts readable, and check for stray source captions, logos, checkerboards, or malformed requested text.

Compare a series using consistent design and camera conventions, with lighting adjusted coherently for any intentional viewpoint changes. Replace a saved reference only when the user explicitly approves that change. Save project assets to the requested destination and report the final result and any remaining material limitation accurately.
