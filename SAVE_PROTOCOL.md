# Save / Load Protocol

Repository 3100 is the save-state repository for this single fantasy setting.

## LOAD

When the user says `ロード`, `3100から再開`, or equivalent:

1. Read `WORLD_SETTING.md`.
2. Read `CURRENT_STATE.md`.
3. Read `CORE_RULES.md`.
4. Read `SOURCE_INDEX.md`.
5. Read `ROSTER.md`.
6. Read `NEXT.md`.

Use this repository as the canonical source for the setting unless the user explicitly supplies a newer source.

Do not import facts from unrelated projects.

## SAVE

When the user says `セーブ`:

1. Update `CURRENT_STATE.md` with the exact work position and newest confirmed facts.
2. Update the appropriate setting file with newly established canon.
3. Update `ROSTER.md` if established characters changed.
4. Update `CORE_RULES.md` only for stable setting or workflow rules.
5. Update `NEXT.md` with the exact next safe action.
6. Add a checkpoint under `saves/` when the state is useful to restore later.

## Continuous canon updates

Do not wait for a manual save command to record newly confirmed worldbuilding. When the user clearly adopts or establishes a setting element, add it to the appropriate 3100 file promptly.

Brainstormed possibilities are not canon until adopted.

## Conflict priority

1. User's newest explicit instruction
2. Newer canonical repository content
3. Older canonical repository content
4. Older checkpoint notes
5. Assistant memory

Assistant memory must never override a newer explicit instruction or source.

## Public repository rule

Repository 3100 is public at this checkpoint. Do not automatically save private or identifying information here.
