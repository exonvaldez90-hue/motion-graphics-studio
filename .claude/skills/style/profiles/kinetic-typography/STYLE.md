# Kinetic Typography

## Intent
Typography is the primary visual actor. Rhythm, scale, alignment, masking and word-level timing communicate the message.

## Visual language
Build layouts around a small number of high-impact words. Use scale contrast, cropping, text blocks, baseline shifts and occasional geometric support elements.

## Color system
Restrained base with one accent color. Ensure high text/background contrast.

## Typography
Display sans-serif or expressive editorial type paired with a highly legible secondary face. Limit font families and weights.

## Motion language
Animate by phrase, word or syllable. Use precise stagger, overshoot sparingly, tracking changes, masked reveals, directional movement and beat-aware cuts. Sync to narration when available.

## Lighting / composition / sound
Use lighting and composition appropriate to the selected medium; maintain clear hierarchy and readable safe areas.
Compose for the requested aspect ratio and preserve clear focal hierarchy.
Use restrained sound design that reinforces the visual rhythm and narration.

## Avoid
Animating every word identically, unreadable speed, random bouncing, excessive font changes and text collisions.

## Implementation guidance
- Keep visual tokens centralized and reusable.
- Prefer small composable Remotion components over one monolithic scene.
- Use deterministic timing based on `useCurrentFrame()` and the project's configured FPS.
- Respect the project's installed Remotion version and existing conventions.
- Provide a static fallback or graceful simplification for complex effects.
