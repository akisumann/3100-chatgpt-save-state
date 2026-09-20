# Equipment Design Principles

This file supplements `STATUS_SYSTEM.md` with practical rules for designing individual pieces of equipment.

## Raw stat bonuses must follow the item's actual structure

An item's level-equivalent and total potential budget do **not** mean that the item should automatically spend that budget on arbitrary numerical stats.

Raw stat increases should come from things the physical or magical structure of the item can reasonably improve.

Examples:
- Adding spikes to an existing shell does not automatically increase the shell's basic DEF.
- Spikes can increase impact, piercing, traction, grip, or contact damage, but they should not be treated as having the same cutting performance as a purpose-built sword blade.
- Improved traction or turning behavior is better represented as a special property when it changes how the user can move rather than simply increasing raw SPD.
- A magical effect that reinforces an existing defensive membrane can be treated as a special effect rather than automatically converted into flat DEF.

This means a high-level item may legitimately provide only a small raw numerical bonus if most of its value lies in specialized functions that fit its construction and intended user.

## Calibration example: Ice Spike Armor concept

A spike attachment mounted onto an armadillo-like shell is a good example of the above rule.

Its value can primarily come from:
- stronger damage during rolling or charging contact,
- spikes biting into the ground to improve turning, braking, and control,
- some reinforcement of an existing ice defensive membrane.

Because the attachment itself does not fundamentally thicken or replace the shell, it does not need a meaningful flat DEF increase. Likewise, because the spikes are not sword blades, their raw ATK contribution should remain modest compared with a dedicated cutting weapon.

The example is a calibration case for equipment design rather than a requirement that all similar items use identical numbers.
