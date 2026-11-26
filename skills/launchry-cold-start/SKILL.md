---
name: launchry-cold-start
description: Turn a single product feature, update, or workflow into an editable demo film that shows an action and its result.
---

# Launchry Product Demo Film

Show what one product feature does through an action a viewer can follow. Start with a 15–30 second, 16:9 film at 30 fps. Recompose the interface and copy for vertical channels.

## Prepare

- Use the release brief, product page, or screen recording to identify one audience, one action, and one result the viewer can see. Ask for missing information only if it changes the action or the proof.
- Separate verified behavior, simulated screens, and intended outcomes. Label a mock interface as a prototype. Leave out unverified numbers, customer names, and results.
- Check the [15 Launchry references](references/candidates.md). Start with L06 for a warm paper workflow, L18 for a single feature, L09 for a before-and-after, L12 for vertical, or L02, L13, and L19 for a teaser. Choose one reference that suits the action.

## Make and check the film

1. Write three beats: establish the current state in the first 3–6 seconds, make the action and its target clear, then hold on visible proof of the result.
2. Copy [film.html](assets/film.html) and [scene.html](assets/scene.html) into the same project directory. Edit the scene’s `copy` object. Dayfold is a fictional example. For a different feature, replace the interface, pointer path, and the start and end states with authorized footage, screenshots, or original graphics.
3. Keep `window.film.frame(t)` deterministic when called out of order. Open or export in OpenFilm Studio. From the project directory, you can run `openfilm open .`, `openfilm look`, and `openfilm render --out launch.mp4 --fps 30`.
4. Deliver the MP4, editable project, and a visual DNA card. Use an actual frame to show the subject, color roles, and visual hierarchy. Describe the action and explain how a still frame communicates the result. Record source rights and reference IDs. See the [visual DNA card data](references/visual-dna.json).
5. Inspect the opening, action, and final hold. The result must make sense without sound. Replace a real input and export again to check that sample text and fictional results have not carried over.

For a longer launch film, choose a story structure from the reference library and split the shots into separate pages. If rendering is unavailable, deliver the editable project and state which export is missing.
