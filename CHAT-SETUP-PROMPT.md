# Claude Chat setup prompt — Motion Graphics Studio

I am providing you with the ZIP archive `motion-graphics-style-library.zip` and access to this GitHub repository:

`https://github.com/exonvaldez90-hue/motion-graphics-studio`

Your task is to install the supplied Motion Graphics Style Library into that repository. Do not merely explain how I could do it; perform the work if your connected GitHub tools allow it.

## Required procedure

1. Inspect the GitHub repository and its default branch (`main`) before making changes. Preserve any existing files. The repository may currently contain only a README.
2. Extract the ZIP archive and inspect its full contents. The archive contains a top-level folder `motion-graphics-style-library/`; install the contents of that folder at the repository root, not inside an extra nested folder.
3. Add/merge the `.claude/skills/style/` directory and all seven profiles, including every `STYLE.md`, `tokens.json`, `motion.json`, and the supplied reference images and notes.
4. Add `README.md` and `PROJECT-INSTALL-PROMPT.md` from the archive. If the repository already has a README, merge the useful project information rather than blindly overwriting unrelated content.
5. Also add this `CHAT-SETUP-PROMPT.md` for future reference.
6. Commit the changes to `main` with a clear message such as `Add Motion Graphics Studio style library`.
7. Verify the commit and list the exact paths added. Confirm that all seven profile directories and the reference images are present.

## Important architecture and behavior

- This is a reusable style library for a Remotion-based Motion Graphics Studio.
- The central skill is `.claude/skills/style/SKILL.md`.
- The seven style IDs are `vox-editorial`, `kurzgesagt-inspired`, `kinetic-typography`, `data-visualization`, `isometric`, `swiss-editorial`, and `cinematic-product-anatomy`.
- Default studio identity: editorial white / black / orange.
- A specifically selected style profile takes precedence over the studio default when its visual language requires a different palette or composition.
- Preserve the existing repository structure and existing files. Do not create a new Remotion app, replace package configuration, add dependencies, or generate a preview composition unless I ask separately.
- Do not omit binary reference images. If your GitHub integration cannot upload binary files or cannot write to this repository, stop and tell me exactly which limitation occurred. Do not claim success unless the commit and files are verifiably present.

## Completion report

At the end, report:
- commit SHA and link;
- exact directory tree (at least down to each profile);
- any files that could not be uploaded;
- whether the repository contents were verified after the commit.
