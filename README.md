# Sanctuary V1.5 — Narrative Edition

Open `index.html` in a modern browser. Files are static, so hosting on GitHub Pages is optional.

## Narrative
90 sequential events across three habitats, with scene-setting continuity notes in `narrative.js`. All 270 outcomes are individually written in `choices.js` with character-specific reactions; stories and prompts are in `stories.js`. Three choices per event are offered, and the selected response is recorded in the Memory Book. The following event acknowledges the prior shared moment. **This remains a linear story with personalised scenes, not a fully branching engine.**

## What carries forward
The Cottage is the player's home base, not the physical location of active plants. Milestones 1/8/15/22/29 unlock keepsakes, and event 30 unlocks a placeable plant representation. Progress and decisions save to localStorage. The key `little-sanctuary-v1` remains unchanged, so saved progress migrates automatically. Import/export is available in Settings. Existing completed events do not retroactively change their recorded text, and pre-V1.5 choices are preserved if present.

## Fixes
A completion-order bug in V1.4 discarded the selected choice. V1.5 records the choice before clearing the draft. The new writing avoids generic moral sentences in the choice outcomes, and the scene introductions add context without lengthy exposition.

## Limits
Story branches don't alter the fixed order of events; callbacks currently reference the prior event rather than persistent branching consequences. These are editorially refreshed stories, not clinical guidance. Art still uses simple symbols and CSS. Browser interaction testing should be completed before public testing.
