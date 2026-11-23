# Material Bridge testing channel

This repository contains two **separate** Dalamud third-party plugin manifests.

**Public production (unchanged):**
`https://raw.githubusercontent.com/leelookoneko/material-bridge-feed/main/repo.json`
— Version **0.5.6.0**.

**Development testing (experimental):**
`https://raw.githubusercontent.com/leelookoneko/material-bridge-feed/main/repo-testing.json`
— Version **0.5.7.0 TEST 1**, archive `MaterialBridge-0.5.7.0-test.1.zip`.

ZIP SHA-256: `8e4d0bc1d8340292105316655175a90df831bb216d0f0bed69a93d0db696fb2d`
Archive size: **292,122 bytes**. Created and validated by the Windows Dalamud API 15 build.

## Before installing
Both manifests use the same `InternalName` (`MaterialBridge`). Do **not**
enable both installed versions. Disable or remove the existing production
repository entry before switching to the testing repository, and keep a copy
of your Material Bridge / Dalamud plugin configuration. The channel may
share saved projects and settings with an existing installation.

## Install
1. Exit FFXIV and back up the plugin configuration.
2. Open FFXIV/Dalamud. Enter `/xlsettings`, then open **Experimental**
   and **Custom Plugin Repositories**.
3. Disable the production Material Bridge repository entry while testing.
4. Add the testing URL above and enable it.
5. Open `/xlplugins` and install or update **Material Bridge (TEST)**.
6. Enter `/materialbridge`, visit **Crafting**, and start by observing a
   cheap, normal manual synthesis. Test the data readers and comparisons.
7. Enable the **experimental action observer** checkbox only after baseline
   read-only checks pass. The checkbox is **off by default**.

## Limitations
- No automatic synthesis, no actions sent by this plugin.
- All numerical predictions, UI gauges and native hook events still require
  live FFXIV verification.
- Completing a craft may close the synthesis window before final comparison.
- Disable the testing channel and re-enable the production channel to return
  to 0.5.6.0. Do not delete configuration unless you choose to reset saved data.
- The test channel is public but separate; `repo.json` is unaffected.
