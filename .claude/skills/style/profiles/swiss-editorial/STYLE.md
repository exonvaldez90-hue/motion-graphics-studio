# Swiss Editorial Motion

## Intent
Grid-driven, typography-led editorial design with disciplined hierarchy, asymmetry, negative space and precise transitions.

## Visual language
Use a modular grid, strong alignment, generous negative space, geometric cropping and restrained graphic accents. Let composition carry the impact.

## Color system
Primarily black, white and neutral tones, with one controlled accent. The studio's orange may be used as a signal accent.

## Typography
Modern grotesk sans-serif, strong size contrast, disciplined weights and consistent line lengths. Editorial serif may be used sparingly as contrast.

## Motion language
Precise position, opacity and scale transitions; restrained wipes; line reveals; deliberate holds. Motion should feel confident and controlled.

## Lighting / composition / sound
Use lighting and composition appropriate to the selected medium; maintain clear hierarchy and readable safe areas.
Compose for the requested aspect ratio and preserve clear focal hierarchy.
Use restrained sound design that reinforces the visual rhythm and narration.

## Avoid
Unnecessary ornament, too many colors, excessive easing effects, inconsistent margins and decorative clutter.

## Implementation guidance
- Keep visual tokens centralized and reusable.
- Prefer small composable Remotion components over one monolithic scene.
- Use deterministic timing based on `useCurrentFrame()` and the project's configured FPS.
- Respect the project's installed Remotion version and existing conventions.
- Provide a static fallback or graceful simplification for complex effects.
