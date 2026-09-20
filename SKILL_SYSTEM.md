# Skill System

## Skill-total budget

A character's total skill budget is based on level:

**Skill total = Level ÷ 2**

Examples:
- Lv10 → skill total 5
- Lv20 → skill total 10
- Lv50 → skill total 25
- Lv100 → skill total 50

The handling of odd-numbered levels is not fixed yet; do not invent a rounding rule without an explicit decision.

## Separation from stats and equipment

Skills are a separate layer from the seven base stats and from equipment bonuses.

- Base stats describe the character's own numerical capability.
- Equipment adds numerical bonuses and/or special properties.
- Skills consume the character's skill-total budget and define learned techniques, passives, spells, special moves, and similar capabilities.

Do not bake skill value into the level-based base-stat total or equipment budget unless explicitly decided later.
