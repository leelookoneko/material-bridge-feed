# Field & Forge 0.5.7.4 TEST 5

Published from `release/0.5.7.4-fishing-progress`.

## Changes
- Visible plugin name: **Field & Forge** (author **Leeloo**).
- Original plugin `InternalName=MaterialBridge`, assembly `MaterialBridge.dll`, saved configuration and `/materialbridge` command remain unchanged; also registers `/fieldandforge` when available.
- Settings → Fishing: save best verified bait preference; release non-target fish only with appropriate game state, protect target/mooch/other-project fish, update newly registered fish when eligible.
- Settings → Activity progress pop-up: show on gathering/hunting/fishing start, keep on complete, and Preview the independent draggable/resizable window.
- A pure `FishingSessionPolicy` and `AcquisitionProgressSnapshot` model for future native workers and tests.

## Not implemented yet
No actual fishing automation, bait switch, release-list write, native gathering/hunting workers, automated NPC purchase or autonomous crafting executor. The popup currently shows **preview/demo** data only. The actual worker-to-popup connection is pending.

## Cautions
Release List requires Fisher level 22, can affect only fish already registered in the Fish Guide, and resets on rod stow. A first-ever catch cannot be released retroactively. Protect mooch and prerequisite fish. Do not claim verified catch probabilities without game evidence.

## Verified package
GitHub Actions Windows (official Dalamud API 15) compile, standalone tests, ZIP and manifest name/version/author verification.

- Archive: `MaterialBridge-0.5.7.4.zip`
- SHA256: `662614da6b71ae94b90556eb9fd0a9779873d33d70b97288f4edd99321b72dee`
- Bytes: **311,442**
- Source: <https://github.com/leelookoneko/material-bridge/blob/release/0.5.7.4-fishing-progress/FISHING_AND_PROGRESS_WINDOW.md>
- Roadmap: <https://github.com/leelookoneko/material-bridge/blob/release/0.5.7.4-fishing-progress/FIELD_AND_FORGE_ROADMAP.md>
