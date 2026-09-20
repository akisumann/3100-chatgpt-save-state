# Save / Load Protocol

Repository 3100 is the save-state repository for this single fantasy setting.

## LOAD

When the user says `ロード`, `3100から再開`, or equivalent:

1. Read `CURRENT_STATE.md`.
2. Read `CORE_RULES.md`.
3. Read `WORLD_SETTING.md`.
4. Read `SOURCE_INDEX.md`.
5. Read `ROSTER.md`.
6. Read `NEXT.md`.
7. Retrieve the canonical Library source named in `SOURCE_INDEX.md` when more detail is needed.

Do not reconstruct missing character facts from memory if the source can be retrieved.

## CONTINUOUS ACCUMULATION

This repository is not only updated when the user explicitly says `セーブ`.

As this fantasy setting grows, add newly confirmed material to repository 3100 as part of the normal workflow.

Examples include:
- world setting and geography
- countries, cities, villages and locations
- organizations and factions
- races and cultures
- magic, skills, professions and technology
- monsters, dungeons and ecology
- religion, economy and social rules
- important NPCs and established characters
- stable rules, corrections and retcons
- any other setting fact that becomes established enough to matter later

Prefer extending an appropriate existing file when practical. If a subject becomes large enough to deserve its own file, create one rather than forcing everything into a single oversized document.

Do not save every casual brainstorm as canon. Add material once it is clearly adopted, confirmed, or used as part of the setting. If the user explicitly says something should be recorded, record it immediately.

When new material contradicts old material, preserve the newest explicit user decision and update or remove the superseded statement so the repository does not contain two competing versions of canon.

## SAVE

When the user says `セーブ` during work on this setting:

1. Update `CURRENT_STATE.md` with date, source/version, exact work position, latest completed change, important confirmed facts, and unresolved items.
2. Update `ROSTER.md` only if the established roster changed.
3. Update `CORE_RULES.md` only for stable user-confirmed rule changes.
4. Update `WORLD_SETTING.md` and any other setting files with confirmed worldbuilding not yet recorded.
5. Update `NEXT.md` with the exact next safe action.
6. Add a checkpoint under `saves/` when the state is useful to restore later.

## Conflict priority

1. User's newest explicit instruction
2. Current canonical source file
3. `CORE_RULES.md` / `CURRENT_STATE.md` / current setting files
4. Older checkpoints
5. Assistant memory

Assistant memory must never override a newer explicit source or instruction.

## Public repository rule

Repository 3100 is public at this checkpoint. Do not automatically save private, identifying, or explicit source passages here.
