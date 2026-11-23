# Vibrant Wicked Stickman Cinematic

Use this creative preset for new Code Engine stories unless the brief specifies another look. Use B6 for layered cinematic stickman storytelling and respect any explicitly selected engine or style. The preset pairs sincere emotional acting with visual comedy, lively cutting and rich environments.

## Start a new story

From the installed skill directory, initialize the native ratio. Use portrait for a vertical video.

```bash
node scripts/autopilot.mjs init /absolute/new-story --style B6 --ratio 9:16
```

The initializer installs `creative-preset.json` and `creative-brief.json` beside `project.json`. Edit only the brief for a routine new story.

1. Create `source/` in the new project. Put the new script in `source/script.md` and the approved narration in `source/voiceover.mp3`. If your files have other names or formats, enter their project-relative paths in the brief. Fill in the title, language, setting, period and any factual or production constraints.
2. Choose a tone from `creative-preset.json`. The template starts at `balanced`. The other choices are `emotional`, `funny`, `mystery`, `historical`, `educational` and `dramatic`. Tone is an authoring choice. Combine directions in the brief when the story spans genres.
3. Follow the [B6 production workflow](b6-installed-production.md), [art direction](b6-art-direction.md), and [character binding guide](b6-character-binding.md). Write the exact timed spoken text to `story.json` and the cues to `captions.json`. Fill the native shot plan and cast inventory. Reference the original-speed prepared audio in `project.json` with its SHA-256 and actual duration. The brief paths identify the source materials. Populate the production manifest and shot plan after alignment.
4. For each shot, identify what the viewer learns, whose reaction matters, and which word, sound or movement motivates the cut. Give the lead a readable change in gaze, breath, brow or pose before cutting away from a serious beat. Save the fastest moves for a reveal, interruption or reaction. Use an insert or held frame where it improves timing.
5. Author original fitted views, layer order, fixed-face expression variants, and actions in the B6 scene. Keep a stable contour and eye layout across variants. Compose mouth, eye, brow and lid parts into per-view head variants, and schedule them against dialogue or reaction cues. Draw separate angles for real view changes. Verify thin arms and legs at the intended render size against B6 visibility, reach and contact checks, with the installed B6 quality reference as the motion and review benchmark.
6. Run character preflight and project validation. Review a motion draft when useful, then inspect the encoded native preview, subtitle fit, continuity, decode, and original-speed audio. Complete the existing B6 independent review and approval workflow before a final render.

## What the workflow controls

**In code.** Standard B6 initialization copies the preset and editable brief template, records their paths in the project manifest, and includes both as fingerprinted inputs. It provisions the existing native layout and installed Archivo Black caption profile. The existing B6 runtime enforces native 30 fps, valid shot coverage, character and contact checks, caption alignment to the declared text, and original-speed supplied audio. It composites authored layers and registered head variants and encodes the video. Those capabilities require an authored scene.

**Creative direction.** Tone, warm face colors, glossy eyes, facial hair, costumes, lighting, camera rhythm, comedy and emotional acting guide the artist or agent. The renderer does not apply them as automatic filters. Visuals, calibrated rigs, lip-sync cues, parallax, snap zooms and cuts must be authored and reviewed per story. B6 supports registered 2D views, not continuous 3D turns. The template does not synthesize speech, infer timings, generate artwork, or approve a preview.

The preset is copied into new B6 production projects. Existing projects and explicit B6 examples retain their original setup.
