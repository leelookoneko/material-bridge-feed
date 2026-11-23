# 0.5.7.2 TEST 3 — first-time crafting log progress
Published November 23, 2026.

- Author: **Leeloo**
- Source branch: `release/0.5.7.2-first-craft`
- Feature: first-time completion count for each accessible crafting notebook leveling band, with checkmark on completion, shown on Material Bridge's Crafting page.
- Game API: `QuestManager.IsRecipeComplete`. Game data: `RecipeNotebookList` and `NotebookDivision`.
- Details: See `FIRST_CRAFT_PROGRESS.md` and `INTEGRATION_ROADMAP.md` in the Material Bridge source repository.
- Zip SHA-256: `a24a0da29ac0925240fc6f0fc27932336a60a5a1acf6611c85f9842124d2620a`.
- Archive length: **296,211 bytes**.
- Built and checked in Windows CI with official Dalamud API 15. Native game readings and the UI still require in-game verification.
- The game's Recipe Log is not modified; the counters appear in Material Bridge's own Crafting tab.
- No automatic synthesis. The native action observer remains manually opt-in.
- The existing `0.5.7.1`, `0.5.7.0` and `0.5.6.0` ZIPs are retained.
