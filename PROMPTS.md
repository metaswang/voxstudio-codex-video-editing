# Codex prompts for the demo

These prompts keep discovery read-only until the user has reviewed the proposed source ranges. They are written for VoxStudio for Mac with the Native MCP connection enabled.

## 1. Find candidate moments (read-only)

> Inspect the currently open VoxStudio project and identify the imported NASA source named “Artemis II and Space Station Expedition 74 Astronauts Call in Space” (about 10:35). Search its transcript and media for short moments about:
>
> - seeing Earth from orbit and the scale/distance of Earth;
> - how the experience changed the astronauts’ perspective;
> - watching Earth grow during return;
> - Jessica’s hopes about the mission; and
> - what makes seeing Earth special.
>
> Do not edit, split, move, create a timeline, or export anything yet. Return up to six candidates with source-media in/out timecodes to two decimals, a short exact transcript excerpt, and one sentence explaining the match. If a theme is not supported by the source, say so. Keep the original media untouched.

## 2. Create a new edit after range review

> Use only the reviewed source ranges below, in this order. Create a new project named “VoxStudio Codex Demo - Artemis II” and a new timeline named “Artemis II short — NASA demo”, 30 fps and 1080 × 608. Do not modify or overwrite the imported source media, an existing project, or an existing timeline. Add each selected range as a new video clip with its linked audio. Preserve the order and source in/out points:
>
> 1. 00:53.92–01:03.52
> 2. 02:34.87–02:50.07
> 3. 07:31.82–07:38.14
> 4. 08:55.91–09:01.35
> 5. 10:19.84–10:24.64
>
> Before editing, reread the active project, media and timeline IDs through this Native MCP connection. After assembling, report the actual timeline duration and clip count. Stop before export so I can inspect it.

## 3. Add captions, review, and export

> On the new “Artemis II short — NASA demo” timeline only, generate English captions from the selected clip audio. Keep captions readable against the video and avoid long lines. Inspect the timeline preview at the beginning, each cut, and at least one caption mid-line. Compare uncertain words with the original audio and correct transcription errors; do not invent speech. Tell me what was corrected and what still needs a human listen. Export the new timeline as H.264 at Match Timeline resolution and 30 fps. Do not overwrite the source file. Confirm the export path, codec, duration and status.

## 4. Ask for a safer alternative when a theme is unsupported

> The transcript does not support [theme]. Do not stretch a quote or invent a match. Show the closest evidence with its source timestamp and ask whether to replace it with a better-supported theme before changing the edit.

## Manual review checklist

- Confirm each selected range begins and ends on a complete spoken word or intentional visual beat.
- Listen to the original audio around each in/out point.
- Verify caption wording and timing; AI transcription is a draft.
- Check for unintended gaps, duplicate frames, black frames, and clipped audio at every cut.
- Confirm the project and timeline are new and the source remains untouched.
- Play the exported file and check its codec, resolution, frame rate, duration and captions.
- If publishing any NASA excerpt, add **“Credit: NASA”**, review current NASA media guidance and check any third-party rights notices.
