# Paper Thread: adapting a new topic

Read after `STYLE.md` and `STORY.md`. This is the part that makes the profile a creative system instead of a template. The style fixes how things look and move. What is on the sheet is invented from scratch for every topic.

## 1. Inputs to ask for

Required: the topic or event; the single claim the video should land ("why is this remarkable?"); language; target length.
Useful: sources for numbers; real photos or clips that can serve as plates (and rights to use them); brand constraints; whether a loop ending is wanted.
If numbers have no source, find one or leave the number out. Never invent a figure to fill a counter.

## 2. Creative adaptation engine

Work through these steps in order. Write the answers down; they become the production plan.

### Step 1. Find the route

The thread needs something real to follow. Decide what the thread **is** in this topic. Pick one:

| The topic is mostly about... | The thread is... | Camera travels along... |
|---|---|---|
| a journey, delivery, migration, signal | the physical path | space (map, cross-section) |
| a process or mechanism | the flow of the thing being processed (money, data, energy, a part) | the pipeline, stage by stage |
| growth, decline, a record | the value over time | a chart that is as tall or long as the sheet |
| a history or a decision | the timeline | time, with branches not taken drawn in dashed ink |
| a structure or hierarchy | a probe going down through layers | depth |
| a cause chain | the line connecting cause to effect | a chain of linked stations |

The thread does not have to move through physical space: time, money, a message, a temperature or a rank are all valid routes, and the sheet can be laid out vertically or horizontally to suit.

If none fits, the topic probably does not suit this profile. The test: can you say in one sentence "the red line is ___ and it goes from ___ to ___"? If not, stop and rethink.

### Step 2. Lay out the sheet

Sketch the whole sheet as a map before any scene: where each station sits in world space, how the thread gets from one to the next, where the camera zooms out. Vary direction (not always downward) and scale (at least one big pull-out and one push-in per video). The opening and closing should be the same place on the sheet if a loop is wanted.

### Step 3. Split the script into stations

One station per idea, usually one to three sentences. For each station write: the sentence(s), the one thing the viewer must understand, and the one number if there is one.

### Step 4. Choose the visual form for each station

Pick by what the sentence is doing, not by what was used last time.

| The sentence... | Use | Notes |
|---|---|---|
| states a quantity | counter + unit label, next to the object it measures | ticks up or down during the sentence |
| compares size or amount with something familiar | the hero cutout beside a line-drawn familiar object built up in steps | the familiar object must be instantly recognisable in outline |
| describes a path, cycle or repetition | the thread draws it | let repetitions pile up visibly |
| says something really happened | photo plate with `WHEN · WHAT` label | 2 to 5 s, never the only thing on screen in the body |
| names a part | callout label with leader line or bracket | caps, 1 to 3 words |
| makes a blunt claim or turn | headline, 1 to 3 words, hard cut on the word | empty paper around it |
| lists absences or conditions with the same structure | statement stack built word by word | optionally the missing things appear as ghost-accent outlines and are removed |
| describes a state changing | a simple gauge, bar or solid block that fills or empties | ink only |
| describes a hypothetical, a failure, or what is not there | ghost-accent outline or dashed ink path | never red |
| places something geographically or within a system | halftone-filled map or schematic, thread as route, 2 to 4 labels | simplify outlines |
| gives history or context | many thin ink traces of the past cases, then the thread as the one that differs | the contrast is the point |
| asks the audience's question | one-word or two-word headline with a question mark | hold it through the answer's first clause |

A station can combine two forms; three is the limit.

### Step 5. Invent the object vocabulary

List the 3 to 6 physical things this topic is made of. Decide for each: hero (halftone cutout of the real thing) or generic (line drawing). There should be one or two heroes per video; they recur at different scales. Then list the metaphors and comparisons, and check each one is drawn from the audience's everyday world, not from the reference video.

Originality check for every station: "Would this picture make sense for any other topic?" If yes, it is a stock picture; make it more specific to this subject.

### Step 6. Motivate every camera move

A move must be caused by meaning. Allowed reasons: following the thread to where the story goes next; changing scale because the sentence changes scale; travelling along an axis the sentence is measuring; arriving at the thing just named. If the only reason is "next scene", redesign the layout so the next station lies along the thread.

Ways to connect two stations, to mix across a video:
- the thread's head travels there and the camera follows;
- zoom out until the current object is a detail of the next picture;
- zoom in until a detail of the current picture is the next picture;
- the object itself moves (falls, rises, rotates) and the camera stays with it while the surroundings change;
- a plate arrives over the current station and the sheet is rearranged behind it (stepped block wipe);
- a ruler or axis slides past, turning the move into a measurement.

### Step 7. Set density

Count the facts. If a station has more than one number and two labels, split it or drop something. If the topic is simple, use fewer, longer stations and let the thread and counters do the work. If it is complex, add stations, not elements per station.

### Step 8. Plan the loop (optional)

Decide what the thread's head lands on in the last station so that zooming into it can become the first frame.

## 3. Production workflow

1. **Brief.** Collect inputs (section 1). Confirm the one-sentence claim.
2. **Research.** Gather numbers with sources; list candidate plates.
3. **Script.** Write to the beats in `STORY.md`. Check word count against target length and language pace.
4. **Route and sheet map.** Steps 1 and 2 above. Deliver as a simple labelled sketch or coordinate list.
5. **Station table.** One row per station: time range, sentence, visual form, objects, counter (start, end, unit, source), headline, labels, plate, incoming camera move and its motivation, thread behaviour.
6. **Approval.** Show script, sheet map and station table to the user. Nothing is generated or rendered before approval.
7. **Voice.** Produce the final voice-over; extract word timestamps.
8. **Assets.** Prepare halftone cutouts, line drawings, plates, map outlines. Convert, do not restyle by hand each time: one halftone recipe for all cutouts.
9. **Build.** World layer, camera track, thread path, HUD captions, per-station additions timed to words (`STYLE.md` section 5).
10. **Preview stills.** Render one still per station and check against section 4 below before rendering motion.
11. **Render and review.** Watch at full speed with sound; fix; export.

The output of steps 1 to 6 is the production plan. It should be usable by someone who has never seen the reference video.

## 4. Quality control

Identity (all must be yes):
- [ ] Could the whole video be printed as one large sheet? No element exists only "in a scene".
- [ ] Is there exactly one red element, continuous from first to last frame?
- [ ] Is every frame either paper-with-grid or the opening/closing live shot?
- [ ] Are all colours from `tokens.json`, with other hues only inside plates?
- [ ] Only two type families, all caps, hard-cut entrances?
- [ ] Does the caption box sit in the same place in every frame, with nothing essential under it?
- [ ] Is every image a halftone cutout, an ink line drawing or a labelled plate?
- [ ] Is the picture still whenever there is something to read?

Adaptation (all must be yes):
- [ ] Can the thread's meaning be said in one sentence, and is it specific to this topic?
- [ ] Does every station's visual form follow from its sentence (Step 4)?
- [ ] Does every camera move have a stated motivation (Step 6)?
- [ ] Does every counter have a real number, a unit and a source?
- [ ] Is there at least one comparison with something from the audience's daily life?
- [ ] Is there at least one big scale change in each direction?
- [ ] Has no object, diagram, layout or sentence been carried over from the reference video?

Rhythm:
- [ ] Something changes every 0.5 to 1.0 s inside stations; camera travel is under about 20 % of runtime.
- [ ] Type and counter landings match word timestamps within 2 frames.
- [ ] No station holds more than one counter and one headline at the same time.

Legibility:
- [ ] All essential content clear of the right 12 % and bottom 18 %.
- [ ] Label text at least 20 px cap height at 1080 width.
- [ ] Thread visible against everything it crosses.

## 5. Common mistakes

- Treating stations as slides and adding a "transition" between them. Fix: lay them out on the sheet and move the camera.
- Decorative thread: a red line that is merely present. Fix: Step 1.
- Recreating the reference's pictures with different labels. Fix: Step 5 originality check.
- Too many counters, so none matters. Fix: one per station, each sourced.
- Smooth, floaty motion. Fix: lock the camera between moves; hard-cut the type.
- Filling the paper. Fix: remove until one focal object remains.
- Letting plates carry the story. Fix: plates prove, drawings explain.
