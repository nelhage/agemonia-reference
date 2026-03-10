---
title: 'Conditions Reference'
date: 2026-03-10T00:00:00-00:00
summary: 'All conditions (status effects) and their rules'
---

| | Condition | Gist |
|---|-----------|------|
| {{< condition "invisible" >}} | [Invisible](#invisible) | Can't be targeted by Enemies |
| {{< condition "blessed" >}} | [Blessed](#blessed) | Roll 1 extra die on a check/attack |
| {{< condition "bleeding" >}} | [Bleeding](#bleeding) | 1 damage at start of each turn |
| {{< condition "slowed" >}} | [Slowed](#slowed) | 1 fewer movement point |
| {{< condition "weakened" >}} | [Weakened](#weakened) | Reduced attack (see below) |
| {{< condition "held" >}} | [Held](#held) | Can't move |
| {{< condition "cursed" >}} | [Cursed](#cursed) | Spent stamina flips to wound side |
| {{< condition "confused" >}} | [Confused](#confused) | Miss next action/attack |
| {{< condition "stunned" >}} | [Stunned](#stunned) | Miss next action + maneuver (or turn) |
| {{< condition "dominated" >}} | [Dominated](#dominated) | Damages nearest ally instead (see below) |
{class="conditions"}

## Detailed Conditions

### {{< condition "invisible" >}} Invisible

Affected Ally
: You may not be targeted by an Enemy attack. You may still be attacked by an area attack targeting another Ally. If you attack or an Enemy is within range 1, discard.

Affected Enemy
: — (Does not affect Enemies)

### {{< condition "blessed" >}} Blessed

Affected Ally
: After any one ability check or attack roll, you may roll 1 more die and add its result. If you do, discard.

Affected Enemy
: — (Does not affect Enemies)

### {{< condition "bleeding" >}} Bleeding

Affected Ally
: Suffer 1 damage at the start of each turn. Spend a maneuver to discard.

Affected Enemy
: Suffer 1 damage at the start of each turn. If they did not move during their turn, discard.

### {{< condition "slowed" >}} Slowed

Affected Ally
: Next time you perform a move maneuver / jump, get 1 fewer movement point / jump 1 fewer area and discard.

Affected Enemy
: On their next move, get 1 fewer movement point and discard.

### {{< condition "weakened" >}} Weakened

Affected Ally
: Next time you roll 1 or more attack dice, roll 1 fewer die and discard.

Affected Enemy
: On their next attack that causes damage or {{< stamina >}} loss, reduce that attack by 2 and discard.

### {{< condition "held" >}} Held

Affected Ally
: You may not perform a move maneuver or a jump. Spend a maneuver to discard.

Affected Enemy
: On their next move, do not move and discard.

### {{< condition "cursed" >}} Cursed

Affected Ally
: Next time your Hero performs an attack action, any {{< stamina >}} you spend during that action (including the action's cost) is flipped to its wound side. After the attack, discard.

Affected Enemy
: — (Does not affect Enemies)

### {{< condition "confused" >}} Confused

Affected Ally
: Next time you perform an action, miss that action and discard.

Affected Enemy
: On their next attack, do not attack and discard. The Enemy still moves as if it was attacking normally.

### {{< condition "stunned" >}} Stunned

Affected Ally
: Next time you would perform an action, miss that action. Next time you would perform a maneuver, miss that maneuver. Once you have missed both, discard.

Affected Enemy
: On their next turn, miss that turn and discard.

### {{< condition "dominated" >}} Dominated

Affected Ally
: At the start of your next turn, the closest other Ally within range 2 suffers 2 magic damage. Use highest Taunt value to break ties for closest. Another Hero in the same area as the targeted Ally may choose to suffer the damage instead. Once you have missed your action, discard.

Affected Enemy
: The next time the Enemy would perform their attack, they do not attack. Instead, the closest other Enemy of your choice within range 2 suffers 2 damage. Once they have missed their attack, discard. The Enemy still moves as if it was attacking normally.
