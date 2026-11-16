# Motion, Contact, and Lighting

Read this guide when the scene includes movement or visible interactions with a surface or light source. Choose details that explain the action through their placement, direction, and timing. Apply the sections relevant to the requested scene.

## Choose a single moment

Choose the phase that defines the requested activity. A jump may show takeoff or landing. A handoff may show shared support or release. Writing may show the pen touching the page during a stroke. Align the body's balance, supporting points, contacts, tools, and materials around that moment.

For scenes with several participants or exchanged objects, coordinate their timing and interactions using [scene-coherence.md](scene-coherence.md).

## General physical details

- Trace weight through the body, held objects, furniture, and receiving surfaces. Adapt balance and support to the activity and the character's anatomy.
- Show effort locally through appropriate contour changes, compression, stretched fabric, or a firm grip. Scale the effort to the load and movement.
- Let soft parts, loose clothing, hair, and attached objects follow the initiating movement with plausible delay. Keep attachment points clear.
- Use moderate effects concentrated around the source of an action. Keep their direction, material, and persistence consistent with the cause and the shared moment.
- For quiet poses, use subtle support, contact, expression, and lighting to make the scene convincing.
- For explicitly fantastical actions, establish the requested physical behavior and apply its visible consequences consistently.

## Activity examples

### Running

- **Line of action.** Lean the body into the direction of travel and connect the torso and limbs with clear flowing curves. Scale squash and stretch to the speed and character design.
- **Push-off.** Slightly flatten the contacting part of the foot as it pushes against the ground. Suggest tension in the ankle or calf with a small contour change or short curved mark. Keep the muscle detail at the reference's simple cartoon level. The other leg prepares for the next phase.
- **Arms and legs.** Use the usual opposing arm and leg action unless the requested pose calls for a different cartoon gesture. Clarify near and far limbs through overlap and interrupted contours. Keep motion effects visually distinct from limbs.
- **Flight.** Both feet may be airborne. Place their projected shadows on the ground at an appropriate distance. Any dust should remain near the preceding push-off point.
- **Dust on dry ground.** Emit small dirt particles and compact dust puffs from the foot's actual push-off contact. Fresh particles are more distinct near the foot. Older dust disperses farther behind the runner. Give heavier fragments a downward trajectory.
- **Readable detail.** Prioritize sole compression, a few tension marks, a small disturbance in loose ground, or the follow-through of ears and flexible body shapes. Keep interior lines economical.

### Other actions

| Action | Body mechanics and surface response | Contact and shadows |
| --- | --- | --- |
| Jump takeoff | Extend the supporting leg and leave an appropriate surface reaction at the takeoff point. | Transition from a contact shadow to a separated ground projection as the foot lifts. |
| Top of a jump | Use a clear airborne silhouette and trailing curves in the limbs or ears. Any surface disturbance belongs to the earlier takeoff point. | Use the separation between the body and its ground shadow to convey height. |
| Landing | Compress the body and feet, bend the knees, and let a small surface reaction spread from the landing point. | Connect the darkest shadow under the planted foot with the broader cast shadow. |
| Braking or sliding | Show continuing momentum in the body and resistance through the braced leg. Displaced material may collect ahead of the foot or scatter sideways. | Connect the planted foot to the slide mark. Choose the debris direction to match the braking force. |
| Pushing or lifting | Establish hand and foot support, subtle tension in loaded areas, and a body lean appropriate to the weight. | Emphasize the hand/object and foot/ground contacts. Add surface effects only where the interaction supports them. |
| Resting or standing | Use the base proportions, a relaxed silhouette, and slight compression through the weight-bearing foot. | Establish a stable contact shadow and quiet surroundings. |
| Seated conversation | Support the pelvis and body on the chair and connect gestures with the exchange. | Align the body with the seat, feet with the floor where appropriate, and shadows with both receiving surfaces. |
| Writing or drawing | Place the tool's working tip on the surface during a stroke and support the page or tablet. | Keep the grip, tip, mark, and hand shadow aligned with the same plane. |
| Pouring or stirring | Match the container angle or utensil movement to the chosen phase of the task. | Show a supported vessel, a coherent liquid path or swirl, and the relevant contact points. |
| Moving an object together | Coordinate participants' steps, grips, and effort around the shared load. | Keep all grips connected to the same object and show consistent height, orientation, and shadows. |

## Match effects to the surface

- **Dry dirt.** Use small grains and restrained dust. Make sand finer and wet soil heavier and more clumped.
- **Grass.** Compress the grass beneath the foot. Add a few disturbed blades or exposed soil where appropriate.
- **Water.** Place droplets and ripples at the actual contact point. Keep the overlap of water and body readable.
- **Clean indoor flooring.** Show sole compression, contact shadows, and a few motion marks when helpful. Choose effects consistent with the clean surface.
- **Tables, paper, and tools.** Concentrate detail on support, working contact, and the material being changed. Match marks, shavings, splashes, or displaced objects to the specific activity.
- **Synthetic sports tracks.** Use spike contact, subtle sole compression, and restrained motion marks. Match any particles to the actual surface and keep the lane markings readable.
- **Character cutouts.** Include ground effects according to the requested asset format. When separate character, effect, and shadow layers are requested, or the game supplies its own ground shadows, deliver those elements according to that setup.

## Keep lighting coherent

1. **Establish the light and camera.** Consider the light's side, height, and depth together with the ground plane and viewpoint. The default is a single light from the upper left and toward the viewer. Reuse existing scene lighting when available.
2. **Distinguish three kinds of shadow.** Form shadows describe surfaces turned away from the light. Cast shadows describe light blocked by the body onto another surface. Contact shadows anchor touching surfaces in a narrow dark area. Simplify each according to its role.
3. **Keep travel direction independent of lighting.** With a light from the upper left and toward the viewer, the ground shadow extends toward the right and away from the viewer. Keep that relationship when the runner changes direction. When flipping the character, recompute the shading for the established light.
4. **Anchor the shadow correctly.** A planted foot meets its shadow at the sole. A lifted foot has a ground projection separated according to its height and the light direction. Shape the broader shadow to roughly reflect the torso, limbs, and ground perspective.
5. **Account for height.** A higher light generally produces shorter shadows and a lower light longer ones. As the distance from the receiving surface increases, shadow edges may soften depending on the size of the light source. Derive an airborne figure's shadow scale from the projection and light geometry.
6. **Preserve the cartoon treatment.** Simplify shadows into a small number of readable color shapes. Distinguish the darkest contact area from the broader shadow. Light effect particles consistently with the character.
7. **Maintain continuity.** With a fixed camera, keep the same light direction on screen. When the camera rotates, retain the light's position in the scene and update its screen direction for the new view.

## Example prompt

Adapt this example to the requested direction, action, surface, and background.

> Jake sprints to the right along a dry dirt path. Keep the base reference's golden-yellow body, facial proportions, smooth black contours, and flat colors. One forefoot pushes backward against the dirt and compresses slightly. A small contour bulge and a short curved mark suggest tension in the loaded calf. The opposite foot lifts forward. Small dirt particles and light dust scatter from the actual push-off point, keeping the face and feet clearly visible. Light the scene from the upper left and toward the viewer. Cast the ground shadow toward the right and away from the viewer, with a tight dark contact beneath the planted forefoot and a separated projection beneath the lifted foot. Keep the whole character and the effects within the frame.

For indoor running, a character cutout, or the top of a jump, adapt the surface effects and contact state to that scene. During edits, preserve the established face, palette, viewpoint, and lighting except where the user requests a change.
