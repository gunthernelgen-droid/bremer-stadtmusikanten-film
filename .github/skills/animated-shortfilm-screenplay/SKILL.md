---
name: animated-shortfilm-screenplay
description: >-
  Use when asked to adapt a children's story, picture book, fairy tale, or fable
  into a screenplay for an animated short film, or to write or revise such a
  screenplay. Preserves the source's core story while making it visual,
  age-appropriate, and production-readable. Trigger for requests such as
  "turn this story into a film", "write an animation screenplay", "Kindergeschichte
  verfilmen", or "Drehbuch für einen Animationskurzfilm".
---

# Children's Story to Animated Short Screenplay

Turn the story the user provides into a complete, readable screenplay for an animated short. Write the screenplay, not a review, storyboard, shot list, or video-generation prompt.

## Intake and defaults

Read the supplied story or workspace file in full before adapting it. Do not reconstruct a story from its title or claim details that are not in the source.

Use the user's stated audience, runtime, language, tone, and adaptation preference. If a choice is missing, proceed with these defaults unless it would materially change the story:

- Write in the language of the request or source.
- Match the source's tone and preserve its central conflict, character motivations, emotional payoff, and meaning.
- Aim for a 5–7 minute short. Treat runtime as an estimate, not an exact promise.
- Infer the intended age from the request and story. If it is unclear, use ages 5–8 and say so briefly.

Ask only the fewest necessary questions when an unanswered choice would lead to substantially different scripts. Otherwise, state any important assumptions and continue.

## Adaptation workflow

1. Identify the protagonist, their goal, the obstacle, the key turning point, the climax, and the resolution. Track the story's essential events and emotional meaning.
2. Select only the characters and events needed for a clear short film. Compress repetition and secondary incidents before cutting the causal steps that make the ending feel earned.
3. Make prose filmable: express important information through visible action, expression, sound, setting, and dialogue. Use narration only when it fits the requested style or is the clearest way to bridge time.
4. Keep the protagonist active. Make the central choice and its consequence legible, and resolve the main story question on screen.
5. If age-appropriateness requires changing frightening or harmful material, preserve its story function while reducing unnecessary intensity. Do not add graphic detail or turn the story into a lecture. Mention significant adaptation choices briefly.

Do not change the source's central message or ending, add unrelated subplots, or invent major characters unless the user asks for a loose adaptation. If the requested runtime cannot hold the full story, explain the main compression in one concise note rather than silently changing its meaning.

## Screenplay format

Unless the user asks for a different format, provide:

1. **Title and brief details** — intended age, approximate runtime, and visual tone.
2. **Logline** — one sentence describing the protagonist, goal, and obstacle.
3. **Characters** — only the essential characters, with a short visual or behavioral identifier when useful.
4. **Screenplay** — a complete sequence of scenes, using clear scene headings such as `SZENE 1 – AUSSEN – WALDRAND – TAG`.

Write action in present tense, in concise paragraphs that describe what an audience can see or hear. Keep dialogue performable and distinct to each character; for younger audiences, prefer concrete, natural, read-aloud-friendly lines. Use sound, music, or animation notes only when they materially help tell the story. Make special visual transformations, expressive acting, and physical comedy clear where they matter, but leave routine staging to the animation team.

End on the story's earned resolution. Do not stop at an outline, leave screenplay placeholders, or add a moral that the action has not earned. Do not include shot numbers, camera-by-camera directions, storyboard panels, or production prompts unless requested.

## Final pass

Before responding, check that:

- The screenplay covers the full story arc and the ending follows from the events shown.
- The protagonist, goal, obstacle, turning point, and resolution are understandable.
- Essential action is visible or audible rather than hidden in explanation.
- The tone and intensity fit the stated or assumed age group.
- The scene sequence feels plausible for the requested short-film runtime; label the estimate as approximate.
- Any substantial departure from the source is disclosed briefly.

Return the screenplay in the conversation unless the user asks for a file. If they do, save it as a new Markdown file at the requested workspace location; do not overwrite the source story.
