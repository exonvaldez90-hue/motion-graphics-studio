# Animated Data Visualization

## Intent
Accurate information design using charts, diagrams, counters, timelines, maps and labels. Data integrity and legibility take priority.

## Visual language
One chart or analytical claim per composition. Label units, baselines and comparisons. Use direct labels where possible and consistent visual encoding.

## Color system
Use a neutral foundation and a limited categorical palette. Accent colors must retain the same meaning across scenes.

## Typography
Highly legible sans-serif with tabular numerals. Distinguish titles, values, units, axes and footnotes.

## Motion language
Animate chart construction in reading order; reveal data progressively; use counters only for meaningful quantities; transition between related chart states without distorting scale.

## Lighting / composition / sound
Use lighting and composition appropriate to the selected medium; maintain clear hierarchy and readable safe areas.
Compose for the requested aspect ratio and preserve clear focal hierarchy.
Use restrained sound design that reinforces the visual rhythm and narration.

## Avoid
Invented data, misleading axes, 3D chart distortion, unlabeled units, decorative motion that obscures values.

## Implementation guidance
- Keep visual tokens centralized and reusable.
- Prefer small composable Remotion components over one monolithic scene.
- Use deterministic timing based on `useCurrentFrame()` and the project's configured FPS.
- Respect the project's installed Remotion version and existing conventions.
- Provide a static fallback or graceful simplification for complex effects.
