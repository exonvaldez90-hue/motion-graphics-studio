# VOX Editorial Explainer

## Intent
Documentary visual journalism: evidence-led storytelling using maps, archival images, typography, diagrams and purposeful annotations. Broad inspiration only; create original compositions.

## Visual language
Editorial, documentary, evidence-first. Combine real photography/video with clean graphic overlays. Use crop, masks, circles, arrows, labels, timelines and map layers. Maintain a clear focal point.

## Color system
Neutral base (off-white, charcoal, black) with one or two deliberate signal colors such as red, yellow or the studio orange. Color must encode meaning.

## Typography
Strong sans-serif headline, restrained body text, compact labels and numerals. Clear hierarchy; avoid decorative type.

## Motion language
Measured, explanatory motion. Reveal evidence in sequence; use tracking lines, map routes, controlled push-ins, masked reveals and restrained parallax. Motion should clarify the argument.

## Lighting / composition / sound
Use lighting and composition appropriate to the selected medium; maintain clear hierarchy and readable safe areas.
Compose for the requested aspect ratio and preserve clear focal hierarchy.
Use restrained sound design that reinforces the visual rhythm and narration.

## Avoid
Random transitions, excessive decoration, unsupported data, fake archival claims, cluttered annotations.

## Implementation guidance
- Keep visual tokens centralized and reusable.
- Prefer small composable Remotion components over one monolithic scene.
- Use deterministic timing based on `useCurrentFrame()` and the project's configured FPS.
- Respect the project's installed Remotion version and existing conventions.
- Provide a static fallback or graceful simplification for complex effects.
