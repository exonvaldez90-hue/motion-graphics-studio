# Paper Thread Explainer

Profile id: `paper-thread`. Extracted from one 94-second vertical explainer Reel (see `references/REFERENCE_NOTES.md`). Values marked *(est.)* were measured from a screen recording and are approximate.

This profile has more files than the others. Read them in this order:

1. `STYLE.md` (this file): identity, visual system, motion language, what to avoid.
2. `STORY.md`: storytelling framework, editing and rhythm, audio direction.
3. `ADAPTATION.md`: how to turn any new topic into this style, production workflow, quality control.
4. `tokens.json` and `motion.json`: the numbers.

## 1. Style identity

One sheet of aged drafting paper, as large as the story needs. Everything in the video is drawn, pasted or printed on that single sheet. The camera never cuts away from it; it travels across it. One red line (the thread) runs through the whole video from the first frame to the last and is the path the viewer's eye follows. The story is literally a route.

The look is a technical dossier or an engineer's pinboard: halftone newspaper cutouts, thin ink line drawings, dotted fills, ruler ticks, small stamped labels, a few colour photographs pasted in as evidence. Text is heavy, condensed, black, all caps.

The feeling is calm authority with one loud colour. It is not playful, not glossy, not 3D.

Use it for: explaining how one thing happened or works, with real numbers, scales, routes, comparisons and a clear "why it matters". Vertical 9:16, 45 to 120 seconds, voice-over led.

Poor fit: emotional or character stories, product glamour, topics with no measurable quantities and no spatial or sequential structure. Say so and suggest another profile.

### What must never change (identity)

1. Single continuous canvas. No scene cuts on paper; only camera travel.
2. Exactly one thread, in the signal colour, continuous for the whole video, with a round head.
3. Paper background with the registration grid, in every frame that is not a photo plate.
4. Three ink values only: paper, ink black, thread red. One optional cool accent reserved for "hypothetical or absent" things.
5. Condensed heavy caps for all display text; wide bold caps for small labels. Nothing else.
6. Word-by-word caption box in a fixed screen position for the entire video.
7. Imagery is either a greyscale halftone cutout, a thin ink line drawing, or a rectangular colour photo plate with a label. No other rendering style.
8. Motion is "hold, then travel": things stay still while they are being read, and the camera moves fast between them.

### What flexes per video

Length, number of stations, how many photo plates, how many counters, density of labels, speed of the voice-over, how far the camera zooms, where on the frame the thread sits, whether the opening and closing are live footage or paper.

### What is topic-specific and must be invented fresh

Every object on the sheet, every diagram, every metaphor, every comparison, every route the thread takes, every counter and its unit, every transition motivation. Nothing drawn for the reference video (rockets, towers, globes, orbit loops, maps of North America, building comparisons) is part of the style. See `ADAPTATION.md`.

## 2. Visual design system

### Colour

| Role | Value | Use |
|---|---|---|
| Paper | `#D8CFBD` | Background everywhere. Slight mottled texture, a little darker toward edges. |
| Ink | `#13100F` | All type, line drawings, ruler ticks, halftone dots, solid blocks. |
| Thread | `#F44814` | The thread and its head only. Never for type, fills or decoration. |
| Caption box | `#FCF2EC` | Caption box, counter boxes placed over busy areas, label chips. |
| Pending word | `#B6B0A9` | Caption words not yet spoken. |
| Ghost accent | `#2B35E9` | Thin outlines or one flat block for things that are hypothetical, missing, or "what would be needed". Used rarely; at most 2 or 3 moments per video. |
| Plate border | `#FFFFFF` at ~3 px | Border around colour photo plates. |

Rules: red means "the subject's path, right now". If a second thing needs a path (a failure case, an alternative), draw it as a dashed ink line or in the ghost accent, never in red. Colour photographs are the only place other hues appear, and they stay inside their bordered rectangle.

### Typography

Two families, no more.

- Display: a heavy condensed grotesque, all caps, tight tracking. Open-licence match: Anton. Used for captions, counters, headlines, statement stacks.
- Label: a wide bold grotesque, all caps, slightly open tracking. Open-licence match: Archivo at weight 700 to 800 (expanded width if available). Used for unit labels, map labels, plate labels, callouts.

Sizes at 1080 px width *(est.)*:

| Element | Cap height | Notes |
|---|---|---|
| Headline word(s) | 150 to 210 px | 1 to 3 words, max 2 lines, left-aligned, sits in empty paper. |
| Statement stack | 90 to 110 px | Repeated-structure list (e.g. three "NO ..." lines), built one word at a time. |
| Counter number | 120 to 170 px | With a label line directly under it. |
| Caption | 50 to 58 px | In the caption box. |
| Label / unit | 20 to 28 px | Always caps. |

Punctuation is used as a weapon: a one-word headline can end in a full stop or a question mark. No italics, no lowercase, no outlines, no gradients, no shadows on type.

### Caption box (fixed HUD)

- Position: horizontally centred, vertical centre at about 66 % of frame height *(est.)*. It does not move for the whole video, whatever the camera does.
- Box: off-white rectangle, square corners, padding about 20 px, height about 98 px, width hugs the text.
- Content: 1 to 3 words per group (4 at most), about 16 characters or fewer. The group appears with all words in the pending grey; each word turns ink black as it is spoken; the word being spoken carries a thick underline (about 6 px) that jumps to the next word. Already-spoken words stay black.
- Nothing important may be placed under the caption box. The thread may pass behind it.
- Languages with long words (Czech, German): reduce to 1 or 2 words per group and allow up to 20 characters before reducing type size. Check that the display font carries the needed diacritics.

### Canvas furniture

- Registration grid: small `+` marks on a regular lattice (roughly every 475 px across, 240 px down *(est.)*), joined by very faint hairlines. It moves with the canvas, which is what makes camera travel readable.
- Ruler: a vertical or horizontal tick scale with labelled milestones whenever the camera travels along a measurable axis (height, distance, time, money, temperature, any unit the sentence is counting).
- Halftone fill: regular ink dots on paper for any "mass" (ground, a land area, the shaded side of a sphere, a zone). Outline in a 2 to 3 px ink line.
- Ground or baseline: a single thin ink line objects stand on.
- Solid ink blocks: plain black rectangles for anonymous mass (a base, a weight, a filled gauge).

### Imagery, three kinds only

1. Halftone cutout: a real object photographed, cut out with a hard edge, converted to coarse greyscale halftone. This is the "hero object" treatment. It must read as printed, not as a clean PNG.
2. Ink line drawing: simple outline schematics, 2 to 3 px stroke, cream fill or none. For comparisons, generic versions of things, diagrams.
3. Photo plate: a real colour photo, video clip, screenshot, document or archive scan in a rectangle with a thin white border and a label chip on its top-left edge reading `WHEN · WHAT` (e.g. a date and a source). Plates are evidence: they prove that what is being drawn really happened. They take at most about a third of the frame and never fill it, except the opening and closing shot.

Topics without a photographable subject: the hero can be any real artefact that stands for the subject (a device, a card, a printed document, a tool, a building). If there is truly nothing real to cut out, use line drawings only and let plates supply the reality; do not fake a halftone from an illustration.

Topics without live footage: open and close on paper. Make the first frame the strongest plate at up to half the frame, with the headline, the label and the thread already in place.

### Composition

- At rest the thread is a straight line with its head at the end: vertical by default, horizontal when the sheet is laid out sideways. The route decides, not habit. Its position across the frame is chosen per station (anywhere from 10 % to 93 % of the frame) so that the station's content has room on the other side. Object and thread interact: the thread ends at, hangs, passes through, or wraps around the hero object.
- One focal object per station, one supporting number or headline, labels as needed. Empty paper is expected; 40 to 60 % of the frame can be bare.
- Headlines and counters go in the largest empty area, away from the caption box.
- Callout labels attach with a thin straight leader line or a small bracket.
- Keep the right-hand 12 % and bottom 18 % free of essential content (platform UI).

## 3. Motion language

The governing rule: **still while read, fast while moving, and the thread leads.**

### Camera

- All scene changes are camera moves across the one sheet: pan, tilt, zoom, or a combination. Duration 9 to 15 frames at 30 fps (0.3 to 0.5 s) for a normal station change, with strong ease-in-out; up to 2 to 3 s for a "journey" move that is itself the content (travelling up a scale, following a route).
- Zoom changes are part of the grammar: pull out to show scale (a curve becomes a horizon, an object becomes a dot), push in to show mechanism.
- Captions and the platform-safe HUD stay fixed while the canvas moves under them.
- Between moves the camera is locked. No drift, no float, no parallax wobble.

### Thread

- The thread is drawn ahead of the camera or with it: its head moves first, the camera follows, then content appears where the head stopped.
- At rest it is a straight vertical line with a dot. When the content is a route, loop, orbit, cycle or fall, the thread itself draws that shape (it can wrap an object many times, trace a path on a map, hang slack, drop).
- Width about 8 px, head about 27 px diameter at 1080 width *(est.)*. On photo footage it gains a thin white outline so it reads.
- The thread never disappears, never restarts and never changes colour. If the camera must leave it briefly, it re-enters from the frame edge within a second.

### Type and numbers

- Display type appears with a hard cut on the exact spoken word: no fade, no slide, no scale-up. Multi-word headlines and statement stacks build one word at a time on the voice.
- Type leaves by being carried off with the canvas on the next camera move. It does not animate out on its own.
- Counters tick continuously while the related sentence is spoken, decelerating into the final value; they finish on or just before the last word. A counter that represents a live quantity (speed dropping, height falling) keeps running across several stations.
- A counter that runs across several stations is pinned to the screen (HUD) in a caption-coloured box, top right, clear of the platform UI; a counter that belongs to one station sits on the sheet next to what it measures.
- Labels pop in with their leader line drawn in 3 to 6 frames.

### Objects

- Hero cutouts are placed, not animated: they are revealed by the camera arriving. When they must move (rotate, separate, fall, dock), the move is mechanical and direct, 10 to 20 frames, with a clear start and stop.
- Line drawings draw on (stroke reveal) or stack up in discrete steps (a comparison object that grows floor by floor in time with a counter).
- Photo plates enter as a hard-edged rectangle sliding or wiping in over about 0.3 s, hold 2 to 5 s, and are covered or carried away by the next move. Larger changes of place can use a stepped block wipe: a few big paper-coloured rectangles covering and uncovering in 6 to 10 frames.
- Ambient motion is limited to things that mean something: streak lines for speed or falling, a dashed path being dashed. No particles, no idle bobbing.

### Easing

Camera: ease-in-out, steep (cubic or stronger). Counters: ease-out. Thread draw: near-linear with a short ease-out at the stop. Mechanical object moves: ease-in-out. Type: none (hard cut).

### Brand overlay

The profile takes precedence over the studio default palette. A studio logo may sit small in a top corner on the HUD layer, in ink or its own mark colour, and on an end frame if one is wanted. If a brand requires its own signal colour, it may replace the thread colour only when it is a saturated warm hue that reads clearly on the paper; it then replaces it everywhere. Do not add brand colours as extra accents.

## 4. Avoid

- Scene cuts, cross-dissolves, glitch, zoom-blur, whoosh transitions, light leaks.
- A second bright colour, gradients, glow, drop shadows, glass, 3D, rounded "app UI" cards.
- More than one red element on screen that is not the thread.
- Soft or bouncy type animation, per-letter effects, kinetic-typography tricks.
- Full-screen stock footage in the body of the video; emoji; icons from icon packs; clip-art.
- Clean vector illustration of the hero object (it must be a halftone cutout) and photographic rendering of generic things (they must be line drawings).
- Lowercase, italics, more than two font families, centred paragraphs, text over the hero object.
- Decorative counters or labels with no real, sourced number behind them.
- Reusing any object, diagram or layout from the reference video. See `ADAPTATION.md`.

## 5. Implementation guidance (Remotion)

- Build the sheet as one large absolutely-positioned world layer and animate a single camera transform (translate + scale) over it. Stations are coordinates in world space, not separate compositions.
- Keep three layers: world (paper, grid, objects, thread), plates (if pinned to world, they belong in world), and HUD (caption box, nothing else).
- Draw the thread as one SVG path in world space and reveal it with stroke-dash offset driven by the timeline; compute the head position from the same progress value.
- Drive captions, hard-cut type and counter end points from word timestamps of the final voice-over, not from guessed frame numbers.
- Take every colour, size and duration from `tokens.json` and `motion.json`.
- Respect the project's Remotion version and conventions; inspect the repository first.
