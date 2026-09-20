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

The old F-S scale is first shifted upward by +5, then the resulting values are multiplied by 7.

The +5 shift applies to all seven status categories. After the ×7 conversion, this adds:

**5 × 7 × 7 = 245**

to the character's old level-based total.

Therefore a character's seven numerical status values add up to:

**Level × 7 + 245**

Equivalent form:

**(Level + 35) × 7**

Examples:
- Lv1 → total 252
- Lv10 → total 315
- Lv20 → total 385
- Lv50 → total 595
- Lv100 → total 945

## Base-status interpretation

The seven core values represent the character's own underlying capability at that level.

They are the character's **base stats**, before external additions such as:

- weapons
- armor
- accessories
- magical equipment
- passive or active skills
- spell effects
- temporary buffs or debuffs

Equipment and skills are layered on top of the base stats rather than being baked into the level-based total.

This allows two characters with similar base stats to perform very differently because of equipment quality, skill loadout, specialization, situational effects, or temporary enhancements.

A character can therefore temporarily perform above the apparent level of their raw base stats without changing their underlying level or base-stat total.

## Equipment slots

Each character has exactly **three equipment slots**:

- Equipment slot 1
- Equipment slot 2
- Accessory slot 1

The two equipment slots are intentionally broad rather than being tied to fixed body parts. They can hold things such as a primary weapon, shield, armor, staff, magical tool, or other major piece of gear depending on the character.

The accessory slot is for smaller or more specialized items such as rings, necklaces, charms, talismans, or similar magical accessories.

Equipment bonuses are added on top of base stats and do not change the character's level-based base-stat total.

## Level-appropriate equipment power

Level-appropriate equipment is intended to be extremely important in combat.

Each of the three slots has roughly the same **overall potential budget**:

- Equipment slot 1: about **40% of base-stat total**
- Equipment slot 2: about **40% of base-stat total**
- Accessory slot: about **40% of base-stat total** in total potential

The difference is that major equipment can spend essentially all of its budget on raw numerical stats if it is a simple stat-focused item, while an accessory cannot.

An accessory inherently spends at least half of its potential on special properties. Therefore, even though its total potential is about 40% of base-stat total, its ordinary maximum raw-stat contribution is about **20% of base-stat total**, with at least the other **20%** represented by special effects.

As a result, a fully equipped character with level-appropriate gear can still gain roughly another **100% of base-stat total in raw numerical bonuses** at the upper end:

- major equipment 1: up to about 40% raw stats
- major equipment 2: up to about 40% raw stats
- accessory: up to about 20% raw stats, plus at least about 20% worth of special properties

So the raw numerical total can still reach roughly double the naked/base value, while the accessory also contributes inherent utility or unique effects beyond that raw total.

Example at Lv50:
- Base-stat total = **595**
- Major equipment full potential = about **238** each
- Accessory total potential = about **238**
- Accessory raw-stat ceiling = about **119**
- Accessory inherent special-effect share = at least about **119** worth
- Maximum raw-stat gain across all three slots = about **595**
- Base + maximum raw numerical equipment = about **1190**, before considering accessory special effects

These percentages describe total stat-budget value, not a mandatory increase to every stat.

### Stat power versus special effects

Major equipment can trade raw numerical bonus for special properties.

A completely straightforward stat-focused major item can use essentially **100% of that slot's normal numerical budget**.

When a major item has special effects, its raw numerical bonus can be reduced very flexibly. As a broad design range, a special item will often retain somewhere around **30% to 100% of its slot's normal stat budget**, depending on how strong, broad, reliable, or conditional its special effect is.

This is not a rigid tier table. Values can sit anywhere within that range rather than being forced into fixed 100/80/60/40/30 steps.

For a Lv50 major equipment slot whose full potential is about +238, examples of the scale are:

- 100% raw-stat emphasis: about **+238**
- 80% raw-stat emphasis: about **+190**
- 60% raw-stat emphasis: about **+143**
- 40% raw-stat emphasis: about **+95**
- 30% raw-stat emphasis: about **+71**

The remaining value is conceptually spent on special effects such as elemental damage, status effects, lifesteal, conditional boosts, defensive reactions, unusual utility, or other unique properties.

The exact exchange rate is deliberately fluid. A narrow or heavily conditional effect may cost relatively little raw stat power, while a strong, reliable, broadly useful effect may require a much larger reduction.

### Accessory design baseline

Accessories have the same roughly **40% total potential** as a major equipment slot, but they are inherently special-effect-oriented.

No matter how simple an accessory is, at least roughly **half of its potential** is tied up in special properties. Thus:

- total accessory potential: about 40% of base-stat total
- maximum ordinary raw-stat share: about 20% of base-stat total
- minimum inherent special-effect share: about 20% of base-stat total

An accessory may sacrifice even more of its raw-stat share for stronger or more specialized effects, but it does not normally convert the inherent special half back into plain stats.

This makes accessories not weaker equipment, but equipment whose power is structurally expressed through effects rather than raw numbers.

### Equipment level-equivalent is variable

An item's level-equivalent is a description of that item's own overall performance, not a fixed requirement tied to the wielder's level.

Real equipment is not perfectly uniform. Even nominally standardized products can vary because of materials, workmanship, finishing quality, enchantment stability, and production tolerances.

Therefore equipment should often be described by a **performance range** rather than one exact level.

Example:
- A highly reputable workshop supplying near-uniform mass-produced military swords might consistently produce swords around **Lv18-Lv22 equivalent**.
- Individual swords from that same production line can still differ slightly inside that range.

This variance can be much wider for handmade, improvised, damaged, repaired, experimental, ancient, magical, or unique equipment.

A character can also use equipment above or below their own level-equivalent; item level-equivalent is a property of the item, not a rule that forces matching character and equipment levels.

## Level 1 baseline interpretation

Lv1 does **not** mean a completely undeveloped or barely functional person, and it does not specifically mean a novice adventurer.

The large fixed baseline represents the minimum ordinary capability a human needs simply to live as a functioning person in the world. Level growth is added on top of that pre-existing human baseline rather than creating all ability from zero.

A generic Lv1 human with four D-grade stats and three E-grade stats fits the total exactly:

- D = 42 × 4 = 168
- E = 28 × 3 = 84
- Total = **252**

This is a useful example of an ordinary low-level human baseline, not a mandatory exact distribution for every Lv1 person.

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

When converting an existing seven-grade character card:

1. Replace each F-S grade with its numerical anchor: F=7, E=28, D=42, C=63, B=98, A=147, S=210.
2. Add the seven anchor values.
3. Compare that sum with the level-based target, **(Level + 35) × 7**.
4. Adjust the small difference across the seven stats while preserving the original strength/weakness pattern and keeping each stat near its original rank anchor.
5. Add a slight zero-sum irregularity so the final values are not mechanically identical to the anchors, while keeping the exact target total.

The original old card system only treated the sum of grade values as approximately level-equivalent, so a converted card can naturally be a few points away from the level target before this adjustment.

### Small random variation rule

- The random adjustment should be only a slight nudge, normally around **±1 to ±3 points per affected stat**.
- Any points added to one stat must be removed from another so the seven-stat total never changes.
- Preserve the character's original strength/weakness pattern and rank neighborhood.
- The purpose is only to avoid mechanically identical stat lines.

### Example: Lv50 card with B / C / B / A / F / A / D

Direct numerical anchors:

**98 / 63 / 98 / 147 / 7 / 147 / 42 = 602**

Lv50 target total:

**(50 + 35) × 7 = 595**

So the final stat line should stay close to those anchors while removing 7 total points and adding only slight irregularity.

## Rule

Do not add extra core categories or change the total-point formula without an explicit user decision.
