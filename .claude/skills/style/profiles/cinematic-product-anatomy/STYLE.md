# Cinematic Product Anatomy

## Intent
A dark, premium, cinematic 3D product-explainer language based on the user's three reference screenshots: a closed laptop hero shot, an exploded battery assembly with warm glowing energy, and a vertical console surrounded by floating circular elements. The core idea is to reveal the hidden engineering inside familiar technology.

## Visual language
Treat the product as a hero object in a dark studio or near-black void. Use photorealistic or premium stylized CGI, precise industrial geometry, floating exploded components, separated layers, internal circuitry and small suspended elements. Compose centrally with strong silhouette and generous black negative space. The product must remain recognizable and mechanically plausible.

## Color system
Near-black and charcoal environment; graphite, brushed aluminum, titanium and warm neutral product surfaces. Use amber/orange internal illumination as the signature energy accent. White or cool-grey typography. Avoid rainbow neon.

## Typography
Minimal, restrained sans-serif captions. Short phrases placed above or below the hero object. Emphasize one or two words; avoid paragraphs over the 3D scene. Optional refined italic serif subtitle for a secondary editorial note.

## Motion language
Slow, controlled cinematic camera drift or macro push-in; exploded components separate along believable mechanical axes; internal parts illuminate in stages; tiny particles and indicators float with restrained inertia; components reassemble cleanly. Use slow-motion timing and purposeful pauses. Avoid frantic movement.

## Lighting / composition / sound
Low-key studio lighting, controlled rim lights, soft reflections on metal, deep shadows and localized amber emission from batteries, processors or power paths. Keep highlights detailed; avoid clipping the glow.
Vertical 9:16 is supported: product centered in a tall hero frame, title in upper negative space, explanatory caption near lower safe area. For 16:9, widen the negative space and use a product-led left/right split when useful.
Subtle low-frequency cinematic bed, precise mechanical clicks, soft servo movement, electrical hum and restrained impact accents. Sound should support each reveal, not overwhelm narration.

## Avoid
Generic sci-fi HUD clutter, excessive lens flares, impossible component geometry, random floating debris, oversaturated orange, toy-like materials unless requested, busy backgrounds, unreadable labels, and reproducing any exact reference frame or brand presentation.

## Implementation guidance
- Keep visual tokens centralized and reusable.
- Prefer small composable Remotion components over one monolithic scene.
- Use deterministic timing based on `useCurrentFrame()` and the project's configured FPS.
- Respect the project's installed Remotion version and existing conventions.
- Provide a static fallback or graceful simplification for complex effects.
