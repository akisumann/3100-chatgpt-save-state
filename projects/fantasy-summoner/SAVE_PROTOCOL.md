# Save / Load Protocol — Fantasy Summoner

This file defines how ChatGPT should use repository 3100 as a manual save-state system.

## LOAD

When the user says things like:
- `ロード`
- `3100から再開`
- `ファンタジー世界のセーブを読んで`

Read in this order:

1. `CURRENT_STATE.md`
2. `CORE_RULES.md`
3. `SOURCE_INDEX.md`
4. `ROSTER.md`
5. `NEXT.md`

Then retrieve the canonical Library source named in `SOURCE_INDEX.md` when the requested work requires detail not contained in the checkpoint.

Do not reconstruct missing character facts from memory if the source can be retrieved.

## SAVE

When the user says `セーブ` during work on this project:

1. Update `CURRENT_STATE.md` with:
   - date
   - current canonical source/version
   - exact current work position
   - latest completed change
   - important new confirmed facts
   - unresolved item, if any
2. Update `ROSTER.md` only if the established roster changed.
3. Update `CORE_RULES.md` only for stable, user-confirmed rule changes.
4. Update `NEXT.md` with the exact next safe action.
5. Add a checkpoint note under `saves/` when the change is substantial enough that rollback/history would be useful.

## What belongs in a checkpoint note

A checkpoint should record decisions, not dump the entire conversation.

Suggested format:

```md
# Checkpoint YYYY-MM-DD HHMM

## Position
What was being worked on.

## Completed
What was finalized since the previous checkpoint.

## New confirmed facts
Only facts the user actually confirmed.

## Corrections
Anything that replaced an earlier understanding.

## Unresolved
Questions still open.

## Resume
The exact next action.
```

## Priority order when information conflicts

1. The user's newest explicit instruction
2. The current canonical source file
3. `CORE_RULES.md` / `CURRENT_STATE.md`
4. Older checkpoint notes
5. Assistant memory

Assistant memory must never override a newer explicit source or instruction.

## Public repository rule

At this checkpoint repository 3100 is public. Do not save private, identifying, or explicit source passages here automatically. Keep such detail in the canonical Library source unless the user explicitly chooses to publish it.
