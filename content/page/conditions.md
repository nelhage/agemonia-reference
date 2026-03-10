---
title: 'Conditions Reference'
date: 2026-03-10T00:00:00-00:00
summary: 'All conditions (status effects) and their rules'
---

| # | | Condition | Gist |
|---|---|-----------|------|
| 1 | {{< condition "invisible" >}} | [Invisible](#1--invisible) | Can't be targeted by Enemies |
| 2 | {{< condition "blessed" >}} | [Blessed](#2--blessed) | Roll 1 extra die on a check/attack |
| 3 | {{< condition "bleeding" >}} | [Bleeding](#3--bleeding) | 1 damage at start of each turn |
| 4 | {{< condition "slowed" >}} | [Slowed](#4--slowed) | 1 fewer movement point |
| 5 | {{< condition "weakened" >}} | [Weakened](#5--weakened) | Reduced attack (see below) |
| 6 | {{< condition "held" >}} | [Held](#6--held) | Can't move |
| 7 | {{< condition "cursed" >}} | [Cursed](#7--cursed) | Spent stamina flips to wound side |
| 8 | {{< condition "confused" >}} | [Confused](#8--confused) | Miss next action/attack |
| 9 | {{< condition "stunned" >}} | [Stunned](#9--stunned) | Miss next action + maneuver (or turn) |
| 10 | {{< condition "dominated" >}} | [Dominated](#10--dominated) | Damages nearest ally instead (see below) |

## Detailed Conditions

### {{< condition "invisible" >}} #1 — Invisible *(Positive, Cards Only)*

Affected Ally
: You may not be targeted by an Enemy attack. You may still be attacked by an area attack targeting another Ally. If you attack or an Enemy is within range 1, discard.

Affected Enemy
: — (Does not affect Enemies)

### {{< condition "blessed" >}} #2 — Blessed *(Positive, Cards Only)*

Affected Ally
: After any one ability check or attack roll, you may roll 1 more die and add its result. If you do, discard.

Affected Enemy
: — (Does not affect Enemies)

### {{< condition "bleeding" >}} #3 — Bleeding *(Negative, Cards & Tokens)*

Affected Ally
: Suffer 1 damage at the start of each turn. Spend a maneuver to discard.

Affected Enemy
: Suffer 1 damage at the start of each turn. If they did not move during their turn, discard.

### {{< condition "slowed" >}} #4 — Slowed *(Negative, Cards & Tokens)*

Affected Ally
: Next time you perform a move maneuver / jump, get 1 fewer movement point / jump 1 fewer area and discard.

Affected Enemy
: On their next move, get 1 fewer movement point and discard.

### {{< condition "weakened" >}} #5 — Weakened *(Negative, Cards & Tokens)*

Affected Ally
: Next time you roll 1 or more attack dice, roll 1 fewer die and discard.

Affected Enemy
: On their next attack that causes damage or {{< stamina >}} loss, reduce that attack by 2 and discard.

### {{< condition "held" >}} #6 — Held *(Negative, Cards & Tokens)*

Affected Ally
: You may not perform a move maneuver or a jump. Spend a maneuver to discard.

Affected Enemy
: On their next move, do not move and discard.

### {{< condition "cursed" >}} #7 — Cursed *(Negative, Cards Only)*

Affected Ally
: Next time your Hero performs an attack action, any {{< stamina >}} you spend during that action (including the action's cost) is flipped to its wound side. After the attack, discard.

Affected Enemy
: — (Does not affect Enemies)

### {{< condition "confused" >}} #8 — Confused *(Negative, Cards & Tokens)*

Affected Ally
: Next time you perform an action, miss that action and discard.

Affected Enemy
: On their next attack, do not attack and discard. The Enemy still moves as if it was attacking normally.

### {{< condition "stunned" >}} #9 — Stunned *(Negative, Cards & Tokens)*

Affected Ally
: Next time you would perform an action, miss that action. Next time you would perform a maneuver, miss that maneuver. Once you have missed both, discard.

Affected Enemy
: On their next turn, miss that turn and discard.

### {{< condition "dominated" >}} #10 — Dominated *(Negative, Cards & Tokens)*

Affected Ally
: At the start of your next turn, the closest other Ally within range 2 suffers 2 magic damage. Use highest Taunt value to break ties for closest. Another Hero in the same area as the targeted Ally may choose to suffer the damage instead. Once you have missed your action, discard.

Affected Enemy
: The next time the Enemy would perform their attack, they do not attack. Instead, the closest other Enemy of your choice within range 2 suffers 2 damage. Once they have missed their attack, discard. The Enemy still moves as if it was attacking normally.
