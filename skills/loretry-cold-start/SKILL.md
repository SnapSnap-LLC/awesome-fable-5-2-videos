---
name: loretry-cold-start
description: Turn one concept from an article, note, or document into a source-faithful animated explainer with an editable project and a visual DNA card.
---

# Loretry Animated Concept Explainer

Choose a question the source can answer through a visible relationship. Start with a 20–35 second, 16:9 film at 30 fps; keep any condition that changes the conclusion.

## Prepare

- Define what the audience already knows, where they are likely to get stuck, and the relationship they should be able to explain afterwards. Extract one testable example or counterexample from the source. Check quantities, units, terminology, and the direction of causality.
- Read the [42 Loretry references](references/candidates.md). Use R01, R03, or R65 for a process or cycle; R04 for changes across eras; R66 for a data transformation; and R55 for a mathematical mapping. Change the narration when the relationship on screen changes.
- Keep a record of facts and asset rights. Study the sample films, then make original graphics and narration or use assets specifically licensed for the project.

## Make and check the film

1. Ask a question, let one variable drive the picture, and hold on the relationship it reveals. Keep the same point, object, scale, or place in view long enough to follow it. Use a visible change to direct attention and leave a frame that stands on its own.
2. Copy [film.html](assets/film.html) and [scene.html](assets/scene.html) into the same project directory. The example maps the height of a point on a unit circle to a sine wave. Edit the scene’s `copy` object. When changing the concept, also change the geometry, labels, units, and motion in `frame(t)`.
3. Keep `window.film.frame(t)` deterministic when called out of order. Open or export in OpenFilm Studio. From the project directory, you can run `openfilm open .`, `openfilm look`, and `openfilm render --out explainer.mp4 --fps 30`.
4. Deliver the MP4, editable project, and a visual DNA card. Use actual frames to show composition, accent colors, and how attention moves through the diagram. Record source facts, asset rights, and reference IDs. See the [visual DNA card data](references/visual-dna.json).
5. Check the opening, the frame that establishes the relationship, and the closing frame against the source. Make clear what changes and what stays the same, even on mute. Revise one line or label, export again, and check that the picture still agrees with the text.

For a historical or narrative subject, use a timeline, a scrolling panorama, or a continuous scene in place of the mathematical diagram. If rendering is unavailable, deliver the editable project and state which export is missing.
