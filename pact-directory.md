# Pact Directory — Lookup Table

Every pact ID referenced in [builds.md](builds.md) (Options 1-4) explained. Use this when you see a pact ID and want to know what it actually does.

- For the **naming pattern** (why `F1` is medium and `FA` is small, family themes) → [pact-legend.md](pact-legend.md)
- For the **strategy & sustain loop** (F8 math, weapon profiles) → [pacts.md](pacts.md)
- For **which pacts go in which build** → [builds.md](builds.md)

---

## Option 2 quick reference (the 40 pacts you asked about)

The full DPS engine. Reading the loadout in plain English:

| Group | Pacts | What this group does |
|---|---|---|
| **Foundation** | `AA` | Required root — 50% base regen chance |
| **Magic level boost** | `B1` | +1 Magic level per rune regen tick (caps +10) |
| **Regen stacks** | `BA, BB, BC` | +5% regen each = +15% (stacks with AA + F3) |
| **Rune→payload chains** | `C1, C3, C4` | Air→prayer restore / Fire→next-hit dmg / Earth→def boost |
| **Accuracy small stacks** | `CA, CB, CC` | +15% accuracy each = **+45%** |
| **Accuracy medium** | `F1` | **+35% accuracy** (combined with C-stacks = **+80% total**) |
| **Regen %** | `F3` | +30% regen chance |
| **Charge→rune chains** | `F5, F6, F9, F10` | Powered staff charge regen also regens water/air/earth/fire rune |
| **Spell speed** | `F7` | Combat spell -2 ticks (Barrage 5→3 ticks) |
| **Powered staff burst** | `F8` | -3 ticks powered staff (Eye of Ayak 3→1 tick = **~2.27× DPS**) |
| **Mage damage F-stacks** | `FA, FB, FC, FD` | +1% mage damage each |
| **Elemental payloads** | `I1, I2, I3, I4` | Air +7%/prayer / Water +20% @ full HP / Fire burn-boost / Earth def-drain |
| **Prayer penetration** | `I5, I7` | +15% prayer pen each = +30% |
| **Mage damage I-stacks** | `IA, IB, IC, ID` | +1% mage damage each |
| **Large payloads** | `L1, L3, L4` | Air max-hit chance/prayer / Fire burn+bounce AoE / Earth +1dmg per 12 def lvl |
| **Spell type conversions** | `L5, L6, L7, L8` | Smoke→air / Ice→water / Blood→fire / Shadow→earth |

**Totals:** +8% mage damage (8 stacks), +80% accuracy (max), +30% prayer pen, ~95% regen chance, all 4 elemental chains, F7+F8 speed, all 4 Barrage conversions.

---

## Family A — Root

| Pact | Effect |
|---|---|
| **AA** | Mandatory starting pact. **50% base chance** to regenerate runes / ammo / charges per attack. Every build has it. |

---

## Family B — Regen foundations

| Pact | Type | Effect |
|---|---|---|
| **B1** | md | Combat spell rune regen → **+1 Magic level** for 30 ticks (caps at +10 = effective 109 Magic) |
| **BA** | sm | +5% chance to regenerate runes/ammo/charges |
| **BB** | sm | +5% regen chance |
| **BC** | sm | +5% regen chance |

Stacks with `AA` (50%) + `F3` (30%) = up to ~95% regen.

---

## Family C — Combat rune-regen payloads + accuracy

| Pact | Type | Effect |
|---|---|---|
| **C1** | md | **Air** rune regen → restores prayer points |
| **C2** | md | **Water** rune regen → heals 1 HP |
| **C3** | md | **Fire** rune regen → +1 damage on next spell hit |
| **C4** | md | **Earth** rune regen → temporary +1 Defence level (stacking) |
| **CA** | sm | **+15% accuracy** (all combat styles) |
| **CB** | sm | +15% accuracy |
| **CC** | sm | +15% accuracy |

The C1-C4 medium pacts are the **rune→payload tier** of each elemental chain. Each fires only on the matching element.

---

## Family F — Mage core (17 pacts, the biggest mage family)

| Pact | Type | Effect |
|---|---|---|
| **F1** | md | **+35% accuracy** — single biggest accuracy pact in the tree |
| **F2** | md | Overheal cap **+30% HP** (lets brews/heals push you above max HP) |
| **F3** | md | **+30% regen chance** (stacks with AA + B family) |
| **F4** | md | **+15 permanent Defence levels** |
| **F5** | md | Powered staff charge regen → **also regenerates a water rune** |
| **F6** | md | Powered staff charge regen → **also regenerates an air rune** |
| **F7** | md | **Combat spell speed −2 ticks** (Ice/Smoke/Blood/Shadow Barrage 5→3 ticks). Core for Kodai barrage Slayer |
| **F8** | md | **Powered staff speed −3 ticks, −8 max hit on 1H**. Eye of Ayak 3-tick → **1-tick = ~2.27× DPS**. Core for bossing |
| **F9** | md | Powered staff charge regen → **also regenerates an earth rune** |
| **F10** | md | Powered staff charge regen → **also regenerates a fire rune** |
| **F12** | sm | +5 permanent Defence levels (numbered exception — small stack despite F12 number) |
| **F13** | md | Overheal cap +30% HP (3rd overheal stack alongside F2/H9) |
| **FA** | sm | **+1% Magic damage** |
| **FB** | sm | +1% Magic damage |
| **FC** | sm | +1% Magic damage |
| **FD** | sm | +1% Magic damage |

`FA-FD` × `IA-ID` = **8 total +1% mage damage stacks** = +8% (taken in Options 2/3/4).

---

## Family H — Multi-style sustain + offhand bonuses

| Pact | Type | Effect |
|---|---|---|
| **H7** | sm | +15% Prayer penetration (numbered exception — small stack despite H7 number) |
| **H8** | sm | +5 permanent Defence levels — also a **key bridge connector** in Option 3/4 paths |
| **H9** | md | Overheal cap +30% HP |
| **H10** | sm | +15% Prayer penetration (numbered exception) |

---

## Family I — Mage elemental damage + more mage stacks (11 pacts)

| Pact | Type | Effect |
|---|---|---|
| **I1** | md | **Air spells +7% damage per active prayer** (Augury, Mystic Might etc. each count) |
| **I2** | md | **Water spells +20% damage at 100% HP** — pairs with L6 Ice→water |
| **I3** | md | Fire spell casts can burn up to 6% of your max HP to multiply damage |
| **I4** | md | **Earth spell hits drain enemy Defence and Magic Defence by 2** (stacking debuff — direct counter to high mage def bosses) |
| **I5** | md | +15% Prayer penetration |
| **I6** | md | Passive prayer point regeneration |
| **I7** | md | +15% Prayer penetration |
| **IA** | sm | +1% Magic damage |
| **IB** | sm | +1% Magic damage |
| **IC** | sm | +1% Magic damage |
| **ID** | sm | +1% Magic damage |

---

## Family J — Tank / 0-dmg sustain (mostly bridges for mage)

| Pact | Type | Effect |
|---|---|---|
| **J5** | md | Family J theme: tank/melee sustain. Used in Option 1 as path connector to reach J8. **Effect unverified** — confirm in-game |
| **J6** | md | Bridge connector toward J8. **Effect unverified** |
| **J7** | md | Bridge connector toward J8. **Effect unverified** |
| **J8** | md | **0-damage hit taken → +2 HP and +2 prayer points**. Pairs with I6 for the Option 1 sustain loop |
| **J9** | md | Bridge connector. **Effect unverified** |

J5/J6/J7/J9 only appear in Option 1 (sustain hybrid) and are taken purely for tree connectivity. Not used in Options 2/3/4. If you commit to Option 1, verify each in-game before unlocking.

---

## Family L — Endgame elemental payloads + spell conversions (8 pacts)

L1-L4 are **large** payload pacts. L5-L8 are **medium** spell-type conversions.

| Pact | Type | Effect |
|---|---|---|
| **L1** | lg | **Air spells +1% max-hit chance per prayer bonus, doubled vs air-weak enemies**. The only direct weakness-exploit pact |
| **L2** | lg | **Water spell hits → 60% of damage dealt healed back**. Major sustain — Option 1/3 only |
| **L3** | lg | **Fire spell hits apply burn (max 5 stacks) + bounce to 2 nearby targets**. AoE + DoT |
| **L4** | lg | **Earth spells +1 damage per 12 Defence levels** (≈ +8 dmg at 99 Def) |
| **L5** | md | **Smoke spells count as air spells** → Smoke Barrage triggers I1/L1 air payloads |
| **L6** | md | **Ice spells count as water spells** → Ice Barrage triggers I2/L2/F5/C2 water chain (the most-used conversion) |
| **L7** | md | **Blood spells count as fire spells** → Blood Barrage triggers I3/L3/F10/C3 fire chain |
| **L8** | md | **Shadow spells count as earth spells** → Shadow Barrage triggers I4/L4/F9/C4 earth chain |

---

## Reading shorthand

| Symbol | Meaning |
|---|---|
| `sm` | Small stackable bonus (the +1%/+5%/+15% repeat-buy pacts) |
| `md` | Unique medium pact — single effect, can only own 1 |
| `lg` | Large payload — heavyweight unique effect (mostly L1-L4) |

---

## Verified vs inferred

Most effects above are pulled directly from `pacts.md`, `pact-legend.md`, and explicit descriptions in `builds.md`. The following were **deduced** from build totals or family theme and should be confirmed in-game before pulling the trigger on a reset:

| Pact | How it was deduced | Confidence |
|---|---|---|
| `F12` | builds.md:157 says "F4, F12, H8 = +25 def levels"; F4=+15, H8=+5, so F12=+5 | High |
| `F13` | builds.md:154 says "F2, F13, H9 = +90% overheal"; pattern points to +30% each | High |
| `H7`, `H10` | pact-legend.md:122 says "H7, H10 are small prayer pen pacts"; assumed +15% each | Medium |
| `J5`, `J6`, `J7`, `J9` | Family J theme + Option 1 uses them as path connectors. Specific effects not documented anywhere in current files | **Low — verify in-game** |

Everything else is sourced verbatim from existing docs.
