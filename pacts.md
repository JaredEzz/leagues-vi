# Demonic Pacts — Combat Mastery System

*Separate from relics. 40 active pacts at once, 130+ available, 3 resets per league. Earn pact points from combat tasks, spend points to unlock pacts.*

## How It Works

- **Pact points** earned by completing combat tasks (kill X, equip Y, etc.) — see [visual-guide.html](visual-guide.html) Pact Tasks section
- Spend points to unlock individual pacts
- **40 active pacts at once**
- **3 resets** per league to respec
- 130+ total pacts to choose from

## The Two Loadouts

Your build has two distinct combat profiles. Pacts should serve both:

| Slot | Bossing (Eye of Ayak) | Barrage Slayer (Kodai Wand) |
|------|----------------------|---------------------------|
| Weapon | Eye of Ayak (powered staff, 1H) | Kodai Wand (wand, 1H) |
| Off-hand | Elidinis' Ward base → Devil's Element | **Tome of Water** (with L6) → Devil's Element |
| Spell | Built-in (powered staff) | Ice Barrage from spellbook |
| Key Pact | **F8** (powered staff speed) | **F7** (combat spell speed) |

**F8 only affects powered staves** (Eye of Ayak qualifies). Kodai Wand is a wand, not a powered staff — uses F7 instead.

**Tome of Water only boosts spellbook spells**, NOT Eye of Ayak's built-in spell. So it's a barrage Slayer offhand (with L6 active), not a bossing offhand.

---

## Eye of Ayak F8 Math

**Pact F8:** "Attack rate with powered staves is sped up by 3 ticks. All one-handed powered staves have their max hit reduced by 8. This cannot reduce attack rate below 1 tick (0.6s)."

### Base Eye of Ayak (99 Magic)

- Max hit formula: ⌊level/3⌋ - 6 = **27 base max hit**
- Attack speed: 3 ticks (1.8s)
- Powered staves benefit from magic damage % multiplicatively

### With Full Mage Gear (Phase 4, no Devil's Element yet)

Magic damage stack:
- Ancestral 9% × Confliction 7% × Occult 5% × Avernic 1% = **+23.6% multiplicative**
- Eye of Ayak max hit: 27 × 1.236 = **~33 max hit**

### DPS Comparison

**Without F8:**
| | Value |
|---|---|
| Max hit | 33 |
| Avg damage | 16.5 |
| Attack speed | 1.8s (3-tick) |
| **DPS** | **~9.17** |

**With F8 (1-tick speed, -8 max hit):**
| | Value |
|---|---|
| Max hit | 25 |
| Avg damage | 12.5 |
| Attack speed | 0.6s (1-tick) |
| **DPS** | **~20.83** |

**F8 = 2.27x DPS increase on Eye of Ayak. No-brainer pick.**

### Why F8 Wins So Hard

- 3x more attacks per second (linear DPS gain)
- -8 max hit is fixed (only ~24% loss on base 33 max hit)
- Bigger max hits = even better F8 ratio (Devil's Element pushes max hit to ~35, making F8 even more favorable)
- Charge consumption goes 5x faster, but Transmutation provides infinite runes

### F8 With Devil's Element (Endgame)

Adding Devil's Element +6%:
- Magic damage stack: 1.09 × 1.07 × 1.05 × 1.01 × 1.06 = **+31% multiplicative**
- Eye of Ayak max hit: 27 × 1.31 = **~35**
- F8 DPS: (35 - 8) / 0.6s × 0.5 = **22.5 DPS**
- Without F8: 35 / 1.8s × 0.5 = **9.72 DPS**
- **2.31x ratio** (slightly better than pre-Devil's Element)

---

## Tome of Water Clarification

**Important:** Tome of Water boosts spellbook spells, NOT powered staff built-in spells.

| Setup | Tome of Water Effect |
|-------|---------------------|
| Eye of Ayak (built-in spell) | **Does NOT boost** (built-in is not a spellbook spell) |
| Kodai Wand autocasting Ice Barrage | **DOES boost** (with L6 making ice = water) |

So Tome of Water is your **barrage Slayer offhand** as an interim option until Devil's Element from Echo Thermy in Phase 4. Source: Tempoross (1/1,600 unique drop).

---

## Magic-Related Pacts (Confirmed)

### Spell Type Conversions

| Pact | Effect | Use Case |
|------|--------|----------|
| **L5** | Smoke spells now function as air spells | If using smoke spells |
| **L6** | **Ice spells now function as water spells** | **CORE for barrage Slayer** — unlocks I2 + Tome of Water synergy |
| **L7** | Blood spells now function as fire spells | If using blood spells |
| **L8** | Shadow spells now function as earth spells | If using shadow spells |

### Elemental Spell Boosts

| Pact | Effect | Use Case |
|------|--------|----------|
| **I1** | Air spells deal +7% damage per active prayer | Multi-prayer setups |
| **I2** | **Water spells deal +20% damage at 100% HP** | **CORE — pairs with L6 for Ice Barrage boost** |
| **I3** | Fire spell casts burn up to 6% max HP to increase damage | Risk/reward |
| **I4** | Earth spell hits reduce enemy Defence & Magic Defence by 2 | Stacking debuffs |

### Magic Damage / Speed

| Pact | Effect | Use Case |
|------|--------|----------|
| **FA** | +1% Magic damage per stack (multiplied by Tumeken's Shadow effect) | Stack multiple copies |
| **F7** | **Combat spell attack rate sped up by # ticks (min 2 ticks)** | **CORE for Kodai/barrage Slayer** |
| **F8** | **Powered staff attack rate sped up by 3 ticks (min 1 tick), -8 max hit on 1H** | **CORE for Eye of Ayak — 2.27x DPS gain** |

### Rune Regeneration Synergy

| Pact | Effect |
|------|--------|
| **B1** | Combat spell rune regen → Magic level boost +1 for 30 ticks (max +10 boost) |
| **C1** | Air rune regen → restore prayer points |
| **C2** | Water rune regen → healing |
| **C3** | Fire rune regen → boost next spell damage |
| **C4** | Earth rune regen → temporary Defence boost |

With Kodai Wand's 15% rune negation chance, these proc constantly.

---

## Pact Selection Plan

### Tier S — Core DPS (Take First)

1. **F8** — Eye of Ayak → 1-tick speed, 2.27x boss DPS
2. **F7** — Combat spell speed (probably need 3 stacks to hit 2-tick min) — 2.5x barrage Slayer DPS
3. **L6** — Ice spells = water spells (unlocks I2 + Tome of Water synergy)
4. **I2** — Water spells +20% damage at full HP
5. **FA** — +1% magic damage per stack (take many)

### Tier S — Build Defining Synergy

6. **B1** — Magic level boost on rune regen (effective 109 Magic = +max hit)
7. **C2** — Water rune regen → healing (sustains full HP for I2)
8. **C3** — Fire rune regen → boost next spell damage

### Tier A — Sustain

9. **C1** — Air rune regen → prayer restore
10. **C4** — Earth rune regen → defence boost

### Tier A — Task Tasks

To research:
- Pacts that boost loot drops
- Pacts that scale with Slayer
- Echo boss damage pacts
- Pacts that synergize with Confliction Gauntlets passive
- Any pact that affects Eye of Ayak special attack (magic def drain)

---

## Open Questions / TBD

1. **F7 stacking:** "# ticks" suggests stackable. Need exact stack count to reach 2-tick floor (probably 3 copies)
2. **FA stacking:** How many copies can you take? Each is +1% mage damage
3. **L6 + Tome of Water interaction:** Need to confirm Tome of Water's +10% post-hit modifier applies when Ice Barrage is converted to "water spell" via L6
4. **Confliction Gauntlets pacts:** Any pacts that strengthen the passive (extra accuracy re-rolls)?
5. **Eye of Ayak spec pacts:** Any pacts that strengthen the magic def drain spec?
6. **Pact unlock costs:** Do all pacts cost the same? Different tiers?

---

## Earning Pact Points (Combat Tasks)

See [visual-guide.html](visual-guide.html) "Demonic Pact Tasks" section for the full filtered list of accessible tasks.

**Highest priority points (build overlap):**

| Points | Task | Reason |
|--------|------|--------|
| 200 | Equip any Ancestral piece | Already farming CoX |
| 200 | Equip Avernic Treads | Already farming Doom of Mokhaiotl |
| 200 | Equip Occult Necklace | Already farming Thermy |
| 200 | Equip Masori piece | Already farming ToA |
| 200 | Cast Ice Barrage | Already your main spell |
| 200 | Equip Zenyte jewelry | Confliction Gauntlets prerequisite |
| 80 | 1 Hueycoatl Kill | Already farming for DHW |
| 80 | 25 Chambers of Xeric | Already farming CoX |
| 80 | 1 Demonic Gorilla | Already farming zenytes |
| 200 | Wave 12 Fortis Colosseum | Sol Heredit practice |
| 200 | Awakened Vardorvis | Hard boss practice |
| 80 | Echo Boss x1 + Reset | Echo Amoxliatl easiest |
| 200 | Echo Boss x2/x3 + Reset | Easy stacking |
| 400 | Infernal Cape | Endgame goal |

Most build progression overlaps with pact points. Don't go out of your way for niche tasks.
