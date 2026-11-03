# Colorful Scientific Vector Explainer

## Intent
Original, highly polished vector-world explainer with stylized characters, bold color fields, simple geometric forms and dimensional 2D/2.5D staging. Inspired by the broad explainer genre, not a reproduction of any studio's assets.

## Visual language
Build a coherent illustrated world from clean vector shapes, layered environments, simplified objects and expressive original characters. Use foreground/midground/background for depth.

## Color system
Curated saturated palette with strong contrast and controlled complementary accents. Limit each scene to a small family of colors; keep contrast accessible.

## Typography
Friendly geometric sans-serif. Large concise headings, short labels, minimal on-screen copy.

## Motion language
Smooth, deliberate character acting; shape morphs; layered parallax; scale-based reveals; looping environmental motion. Transitions should feel designed, not random.

## Lighting / composition / sound
Use lighting and composition appropriate to the selected medium; maintain clear hierarchy and readable safe areas.
Compose for the requested aspect ratio and preserve clear focal hierarchy.
Use restrained sound design that reinforces the visual rhythm and narration.

## Avoid
Photorealism, inconsistent character proportions, excessive gradients, copying recognizable character designs or exact branded compositions.

## Implementation guidance
- Keep visual tokens centralized and reusable.
- Prefer small composable Remotion components over one monolithic scene.
- Use deterministic timing based on `useCurrentFrame()` and the project's configured FPS.
- Respect the project's installed Remotion version and existing conventions.
- Provide a static fallback or graceful simplification for complex effects.
