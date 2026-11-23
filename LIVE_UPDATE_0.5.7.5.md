# Field & Forge 0.5.7.5 TEST 6 — published to live feed

Version: 0.5.7.5. Display name: Field & Forge. Author: Leeloo.
**InternalName remains MaterialBridge**; existing plugin configuration and old `/materialbridge` command remain supported. New `/fieldandforge` command added.

Features:
- Fishing settings: best verified bait policy, Release List for non-targets gated at Fisher level 22, dynamic per-hole new catches. **Policy only**; no actual bait or Release List modification yet.
- Floating user-toggled material-progress window (live outstanding Crafting List items; gathers/hunts not yet automated).
- Independent one-synthesis start without calling Artisan. Begin Crafting prepares first scheduled recipe; user confirms in Recipe Log, presses Start one synthesis. The actual crafting skills are still manual and repeat crafting is not yet supported.
- Optional Artisan import remains for migrating old lists; the obsolete `Artisan.StartListById` action bridge has been removed.

Windows CI test/build success:
https://github.com/leelookoneko/material-bridge/actions/runs/45155596354

ZIP SHA-256:
`9436fdedff42c16f8cccea8836d6db985cc27f47f0ac6cb7e7e896dc3a65553d`

ZIP bytes: **309,295**.

This is experimental. Native RecipeNote Synthesize callback must be tested in FFXIV using low-value materials; no automatic crafting/Release List behavior has been verified in the game. Previously published 0.5.7.4 ZIP files remain unchanged.
