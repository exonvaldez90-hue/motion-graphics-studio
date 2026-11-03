# Isometric Explainer

## Intent
Axonometric spatial storytelling for systems, places, infrastructure, workflows and product ecosystems.

## Visual language
Consistent isometric grid and projection. Construct scenes from modular buildings, devices, people, paths and platforms. Keep object scale and shadow direction consistent.

## Color system
Controlled palette with distinct colors for functional zones or system layers. Use restrained shading to separate planes.

## Typography
Compact sans-serif labels placed on clear planes or in external callouts. Avoid perspective-distorted body copy.

## Motion language
Camera pans or zooms along the grid; objects assemble, connect or illuminate; paths draw in sequence; use layer separation to explain flow.

## Lighting / composition / sound
Use lighting and composition appropriate to the selected medium; maintain clear hierarchy and readable safe areas.
Compose for the requested aspect ratio and preserve clear focal hierarchy.
Use restrained sound design that reinforces the visual rhythm and narration.

## Avoid
Mixing perspective systems, inconsistent angles, overcrowded scenes, tiny labels and arbitrary camera rotation.

## Implementation guidance
- Keep visual tokens centralized and reusable.
- Prefer small composable Remotion components over one monolithic scene.
- Use deterministic timing based on `useCurrentFrame()` and the project's configured FPS.
- Respect the project's installed Remotion version and existing conventions.
- Provide a static fallback or graceful simplification for complex effects.
