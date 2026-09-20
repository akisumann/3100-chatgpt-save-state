# ChatGPT Save State — Fantasy Summoner

This repository is dedicated to one setting only: Aki's Lv1–100 fantasy summoner world.

Its purpose is to act as a durable manual save state for long-running ChatGPT work. It is not a raw conversation archive.

## Read order

1. `CURRENT_STATE.md` — current work position
2. `CORE_RULES.md` — stable facts and constraints
3. `SOURCE_INDEX.md` — canonical source to retrieve for detail
4. `ROSTER.md` — established summon roster
5. `NEXT.md` — unresolved items and exact next action
6. `SAVE_PROTOCOL.md` — save/load procedure

Historical checkpoints live under `saves/`.

## Principle

Do not silently invent missing project facts. If a detail is absent from the checkpoint, retrieve the canonical source named in `SOURCE_INDEX.md` before changing established material.

This repository is currently public. Keep private or explicit source text out of it unless the user explicitly decides otherwise.
