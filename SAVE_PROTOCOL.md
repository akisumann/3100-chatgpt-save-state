# Save / Load Protocol

Repository 3100 is the save-state repository for this single fantasy setting.

## LOAD

When the user says `ロード`, `3100から再開`, or equivalent:

1. Read `CURRENT_STATE.md`.
2. Read `CORE_RULES.md`.
3. Read `SOURCE_INDEX.md`.
4. Read `ROSTER.md`.
5. Read `NEXT.md`.
6. Retrieve the canonical Library source named in `SOURCE_INDEX.md` when more detail is needed.

Do not reconstruct missing character facts from memory if the source can be retrieved.

## SAVE

When the user says `セーブ` during work on this setting:

1. Update `CURRENT_STATE.md` with date, source/version, exact work position, latest completed change, important confirmed facts, and unresolved items.
2. Update `ROSTER.md` only if the established roster changed.
3. Update `CORE_RULES.md` only for stable user-confirmed rule changes.
4. Update `NEXT.md` with the exact next safe action.
5. Add a checkpoint under `saves/` when the state is useful to restore later.

## Conflict priority

1. User's newest explicit instruction
2. Current canonical source file
3. `CORE_RULES.md` / `CURRENT_STATE.md`
4. Older checkpoints
5. Assistant memory

Assistant memory must never override a newer explicit source or instruction.

## Public repository rule

Repository 3100 is public at this checkpoint. Do not automatically save private, identifying, or explicit source passages here.
