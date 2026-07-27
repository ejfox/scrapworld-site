### Getting started

- Grab the latest Windows build from [Releases](https://github.com/ejfox/scrapworld/releases/latest), unzip, run `Scrapworld.exe`.
- Or open the project in Unity 6000.0.30f1+, open `SampleScene`, press Play. Everything bootstraps at runtime — no setup scene, no editor menus.

### First five minutes

- Walk up to a card and grab it with **E**. Hold the button and release to throw — the pink arc shows the trajectory.
- Pin a card with **P**: against a wall it flattens, in the air it floats in place.
- Press **M** and let the museum build itself around your cards.
- Press **F3** and drag the MOSH sliders while throwing cards at a wall.
- Lost? **Esc** shows the full keymap in-game.

### Cards and data

- Cards load from your Supabase `scraps` table, newest first. **Ctrl+R** refetches; layouts otherwise restore from `%USERPROFILE%\AppData\LocalLow\Scrapworld\Scrapworld\CardPositions.json`.
- **I** opens the import wizard for local markdown and Pinboard.
- PDF import needs [Poppler](https://poppler.freedesktop.org/) on your PATH (`scoop install poppler`).

### More

- [Quickstart and troubleshooting](https://github.com/ejfox/scrapworld/blob/codex/unity6-repair/docs/QUICKSTART.md)
- [Markdown import](https://github.com/ejfox/scrapworld/blob/codex/unity6-repair/docs/MARKDOWN_IMPORT.md)
- [Changelog](https://github.com/ejfox/scrapworld/blob/codex/unity6-repair/docs/CHANGELOG.md)
