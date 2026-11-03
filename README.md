# motion-graphics-studio

# Motion Graphics Style Library

Starter library for Claude Code + Remotion. It contains one central `/style` skill and seven reusable style profiles.

## Included profiles
1. `vox-editorial` — documentary editorial explainers, maps, archival imagery and annotations.
2. `kurzgesagt-inspired` — colorful vector worlds, stylized characters and clean 2D/2.5D storytelling.
3. `kinetic-typography` — expressive type-led sequences and rhythm-driven text animation.
4. `data-visualization` — charts, statistics, diagrams and data-led storytelling.
5. `isometric` — axonometric scenes and spatial process explanations.
6. `swiss-editorial` — grid-based typography, restrained layouts and precise transitions.
7. `cinematic-product-anatomy` — custom dark, cinematic 3D product storytelling based on the supplied references.

## Install
Copy the `.claude` directory into the root of your existing Motion Graphics Studio project. Merge folders if `.claude` already exists; do not overwrite existing skills.

Then open Claude Code in the project and try:
- `/style`
- `/style vox-editorial`
- `/style cinematic-product-anatomy`

The style skill can also be invoked naturally: "Use the cinematic product anatomy profile."

## Project assumptions
- Remotion is the rendering target.
- Keep scenes modular and reusable.
- Use the existing studio identity (editorial white / black / orange) as the studio-wide default, but do not force it onto a selected style when that would break the profile.
- Treat brand-inspired profiles as high-level visual languages, not instructions to reproduce proprietary artwork, logos, exact frames or distinctive assets.

## Important
This is a starter architecture and style specification, not a finished Remotion application. Claude should inspect the existing repository before editing code, preserve current conventions, and ask before adding dependencies or replacing project configuration.
