# Status System

The setting uses exactly seven core status categories:

- HP
- MP
- ATK
- DEF
- INT
- SPD
- DEX

## Meaning

- HP: physical endurance, vitality, and how much damage can be sustained
- MP: magical energy capacity and magical stamina
- ATK: physical offensive power
- DEF: physical durability and resistance to physical damage
- INT: magical aptitude, spellcasting ability, knowledge, and magical control
- SPD: movement speed, reaction speed, and agility
- DEX: precision, manual skill, fine control, weapon handling, and technical accuracy

## Total status points

The numerical system shifts every old status value upward by +5 so that the old -4 to 25 scale becomes 1 to 30.

Because there are seven status categories, that baseline shift adds a total of **+35** points to every character.

Therefore a character's seven status values add up to:

**Level × 7 + 35**

Equivalent form:

**(Level + 5) × 7**

Examples:
- Lv1 → total 42
- Lv10 → total 105
- Lv20 → total 175
- Lv50 → total 385
- Lv100 → total 735

## F-S reference anchors

The original nonlinear F-S reference values are:

- F = -4
- E = -1
- D = 1
- C = 4
- B = 9
- A = 16
- S = 25

After the universal +5 shift, the reference anchors become:

- F = 1
- E = 4
- D = 6
- C = 9
- B = 14
- A = 21
- S = 30

After the ×7 conversion used for the numerical status scale, the corresponding numerical anchors are:

| Grade | Shifted anchor | Numerical reference |
|---|---:|---:|
| F | 1 | 7 |
| E | 4 | 28 |
| D | 6 | 42 |
| C | 9 | 63 |
| B | 14 | 98 |
| A | 21 | 147 |
| S | 30 | 210 |

These values are **reference anchors**, not exact single-value requirements.

## Grade interpretation

A status receives the grade of the nearest appropriate anchor rather than using equal-width grade bands.

Because the anchor spacing is nonlinear, the grade widths are also nonlinear.

Example:
- shifted value 27 is much closer to S=30 than A=21, so it is treated as S.

Exact integer boundary rules between every pair of grades are not fixed yet. Do not replace the nonlinear anchors with equal-width bands.

## Converting an old F-S status spread into numerical stats

When converting an existing seven-grade character card into the numerical system:

1. Replace each F-S grade with its shifted anchor weight: F=1, E=4, D=6, C=9, B=14, A=21, S=30.
2. Treat those seven values as the character's status-distribution weights.
3. Scale the weights proportionally so that the seven numerical stats add up to that character's required total, **(Level + 5) × 7**.
4. Round to whole numbers while keeping the required total exact.
5. After the proportional baseline is made, add a **small amount of random variation** so the final spread is not mechanically identical to the anchor ratio.

### Small random variation rule

- The random adjustment should be only a slight nudge, normally around **±1 to ±3 points per affected stat**.
- Any points added to one stat must be removed from another so the seven-stat total never changes.
- The adjustment should preserve the character's original strength/weakness pattern and should not casually push a stat into a clearly different rank character.
- The purpose is only to make characters with the same letter-grade pattern feel a little less mathematically identical.

Example for a Lv50 character:
- Required total = 385.
- A proportional baseline such as 63 / 40 / 63 / 94 / 4 / 94 / 27 may be nudged to 64 / 41 / 62 / 95 / 3 / 92 / 28.
- Both totals remain exactly 385.

## Rule

Do not add extra core categories or change the total-point formula without an explicit user decision.
