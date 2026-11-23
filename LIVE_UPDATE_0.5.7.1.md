# Live feed hotfix 0.5.7.1

Author: **Leeloo**. Version: **0.5.7.1 TEST 2**.

Public custom repository URL:
`https://raw.githubusercontent.com/leelookoneko/material-bridge-feed/main/repo.json`

- The live update checker must use `repo.json` above, not a local **Dev Plugin Location** DLL.
- The live ZIP and the test-channel ZIP contain the **same validated 0.5.7.1 build**, with `Author` = `Leeloo` in `MaterialBridge.json`. The two manifests have the same `InternalName`; do not enable both feed entries.
- ZIP SHA-256: `eed4f703c5f30ee431675edfbedeeba1f3c8a54394227ea2f44762ee6bbd3ca4`.
- ZIP size: **292,111 bytes**.
- Old releases remain available; no existing ZIP was overwritten.

If no in-game update is shown, check the exact enabled custom repository URL in `/xlsettings` → Experimental → Custom Plugin Repositories. Then refresh/restart Dalamud so it retrieves the new manifest. If Material Bridge appears under **Dev Tools → Installed Dev Plugins**, disable that manual installation and install from the feed; developer DLLs don't receive feed updates. Keep a backup of plugin configuration and do not uninstall or delete your saved project data just to force a refresh.

The native action observer is opt-in, read-only previews are uncalibrated, and no automatic synthesis is enabled.
