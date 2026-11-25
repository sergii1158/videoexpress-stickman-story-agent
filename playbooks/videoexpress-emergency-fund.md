# VideoExpress Emergency Fund Playbook

Use this playbook for the user's emergency-fund explainer project. The user has completed the current video; do not resume editing it unless asked. Blue Check is specific to this Emergency Fund film. A future film may have a different protagonist and must use its own user-approved character reference.

## Source of truth and complete coverage

- Use the latest user-provided script and the narration already on the timeline as the sources of truth. Read the full script before creating clips.
- Make a scene checklist with one entry per narration line, in exact script order. Record the exact line, opening words, audio start/end/duration, intended track, and status.
- Match each script line to its narration segment and existing clip before generating anything. Start at the first genuinely missing clip and continue sequentially; never skip, duplicate, merge, reorder, or invent a scene.
- Treat portions the user says they checked or arranged as verified. Do not recheck them unless asked.
- Do not ask the user to resend a script, reference name, timing, or preference already present in the conversation, repo, or timeline.

## Protect narration and existing timeline work

- The narration already exists on the timeline. Do not create narration, use CloneVoice, add voiceover, or modify any audio clip. Generated clips are visual-only.
- Never move, trim, split, stretch, mute, delete, or replace the audio track.
- Do not move, reorder, trim, or delete existing video clips unless the user explicitly requests that specific change.
- Count tracks from the bottom upward, with the existing audio track as track 1. For this project, add requested new clips to track 3 unless the user specifies another track. Do not place clips on the topmost track by default.
- Place each new clip at the timeline position matching its narration segment. Preserve all existing placements and gaps unless the user explicitly asks to change them.

## Match clip duration to the audio exactly

- Before generation, determine the narration segment's actual start and end from its clip boundaries and the timeline ruler. Record both times and the duration in the checklist. Do not estimate from word count or speaking speed.
- Set the generated video duration to the measured audio duration. The video must start and end with that spoken segment, without extra footage or truncation.
- If timing is hard to read, zoom in or inspect available timing information. Never guess. If the app cannot produce the exact length, explain the specific limit; do not change the audio to make it fit.
- If a duration control offers fixed choices, select the closest duration and trim only the video to the exact audio boundaries when possible. Follow a user-provided duration if it matches the current timeline; a later timeline edit takes precedence over an older estimate.
- Verify the placed video's start, end, and duration against the audio segment after adding it.

## Character and generation settings

- For this completed Emergency Fund film, use only the approved library reference named **APPROVED MASTER STICKMAN - NO BANK**, identified by the user's blue check. Select it using the lower **Reference Photo** control for character inheritance; **Use from Library** alone does not satisfy this requirement.
- For every future film, use the character reference that the user approves for that specific film. The protagonist may change between films. Do not carry Blue Check, its costume, or any other prior protagonist into a new film unless the user approves that character for it. Once approved for a film, keep that film's chosen master consistent across its scenes and revisions.
- Set **Image Type: 2D**, **Creative mode: ON**, and **Use Consistent Character: ON**. Keep automatic image-prompt enhancement OFF. Keep the current project's aspect ratio unless the user requests a change.
- For the Emergency Fund film, preserve the Blue Check design: white shirt, turquoise tie, glasses, slim stickman body, narrow torso, thin arms and legs. Do not add a green sweater, bank, jar, or container. For a future film, follow that film's approved character design and applicable props instead of imposing these Emergency Fund exclusions.
- Specify a dynamic, non-upright starting pose and meaningful movement in every scene. Vary poses between scenes; do not begin with a straight-standing character. Keep limbs proportionate and require exactly two arms and two legs when the character design is a stickman.
- Make the visual action directly illustrate the exact narration line. Avoid unrelated props, invented claims, or extra wording that could confuse the meaning.
- If the user asks only for prompts, provide detailed prompts and do not generate or change the timeline. If the user asks to make clips, continue through generation, review, and placement rather than stopping after drafting prompts.

## Generate, inspect, retry, and place safely

- Submit one image or video generation at a time. Check its status before another generation action, then every 1–2 minutes while it is processing. Never submit a duplicate while a job may still be active.
- Review each generated image before video generation. Review each finished clip's first frame and full motion for narration match, dynamic action, 2D style, approved character for that film, proportionate limbs, exactly two arms and two legs for stickman characters, and absence of prohibited props or clothing.
- Add no rejected image or video attempt to the timeline. Add a verified clip exactly once, named with the first words of its narration line, at the matching audio position and requested track. Verify the label, track, order, and exact timing.

## Retry policy for generation and transient app glitches

- This retry policy applies to still-image generation, video generation, and recoverable transient VideoExpress interface failures during an authorized operation.
- When an action fails, appears stuck, or produces no expected result, inspect the current app state and job status first. Confirm whether it actually failed, is still processing, or partially succeeded before retrying.
- For a confirmed failed generation or an unusable image/video, retry the same scene and generation step up to at least five attempts. Keep the narration meaning, approved reference, and required settings; adjust a prompt only to correct an identified visual defect. The user authorizes additional attempts beyond five when needed and safe.
- For a recoverable interface glitch, repeat the same interrupted operation after checking that it did not already succeed. Do not blindly click a control again if that could create duplicate clips, duplicate jobs, or other repeated side effects.
- After every retry, check the resulting status before doing anything else. Keep retrying while the failure is transient and the action remains safe; report a concrete blocker when the app shows a lasting restriction or no safe retry remains.
- Stop immediately on **authentication_required** and request reauthorization. Do not retry around authentication, payment restrictions, unavailable required references, or other explicit access/policy blocks.

## Save and completion check

- Save after substantial changes when the app supports saving. Never publish the video to a public gallery or delete library originals.
- Before reporting completion, compare the checklist with the full script and timeline. Confirm every intended narration line has exactly one approved, correctly named clip on the intended track and aligned to the correct audio segment.
- If the user says the entire video is complete, stop editing and acknowledge that. Do not restart production or ask for the script again.

## Project status

The Emergency Fund video is complete according to the user. Preserve its current project, timeline, and Blue Check reference. For a new film, follow the new film's script and user-approved character reference; make further changes only when asked.
