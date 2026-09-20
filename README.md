# ChatGPT Save State

This repository is a durable checkpoint store for long-running ChatGPT projects.

It is not intended to be a raw conversation archive. The goal is to preserve the minimum structured state needed for a future chat to resume work without reconstructing decisions from memory.

## Read order

For a project, read files in this order:

1. `CURRENT_STATE.md` — where the work is now
2. `CORE_RULES.md` — facts and constraints that must not drift
3. `SOURCE_INDEX.md` — canonical source files to retrieve when detail is needed
4. `ROSTER.md` — important entities / characters already established
5. `NEXT.md` — unresolved items and the next safe action
6. `SAVE_PROTOCOL.md` — how to update this checkpoint

## Projects

- `projects/fantasy-summoner/` — Aki's Lv1–100 fantasy summoner setting

## Principle

Do not silently invent missing project facts. If a detail is absent from the checkpoint, retrieve the canonical source named in `SOURCE_INDEX.md` before changing established material.

The repository is currently public. Keep private or explicit source text out of this repository unless the user explicitly decides otherwise.
