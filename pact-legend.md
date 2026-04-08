# Pact ID Legend & Naming Guide

The Demonic Pact tree uses 2-character IDs like `AA`, `F8`, `L6`, `IB`. They look cryptic but follow a strict pattern. Once you know the system, you can read any pact ID at a glance.

## The two-character pattern

```
   F  8
   │  └── second char: number = unique medium pact, letter = stackable small pact
   └────── first char: family letter (A-N)
```

### First character = family

The tree is divided into 14 families (A through N). Each family is a connected sub-tree that shares a theme.

### Second character

| Type | Means | Pact size | Example |
|---|---|---|---|
| **Number** (1-13) | Unique medium effect — each one is different | `md` (most) or `lg` (L family) | `F8` = powered staff speed |
| **Letter** (A-D) | Stackable small bonus — multiple copies of the same effect | `sm` | `FA`, `FB`, `FC`, `FD` = each adds +1% mage damage |

So `FA` is *the first small stack in the F family*, and `F1` is *the first medium pact in the F family*. Different things.

## Family-by-family theme

| Family | Count | Theme | Mage-relevant? |
|---|---|---|---|
| **A** | 1 | Root (just `AA` — the starting pact) | Mandatory |
| **B** | 6 | Generic regen/buff foundations | Yes (B1) |
| **C** | 7 | Combat spell rune-regen payloads | **YES — core mage** |
| D | 7 | Shield + heavy melee mixed | No |
| E | 6 | Ranged echoes (bow/cbow/thrown) | No |
| **F** | 17 | **MAGE CORE** — accuracy, regen, mage damage stacks, F8 powered staff | **YES — biggest mage family** |
| G | 16 | **MELEE CORE** — strength, melee damage stacks | No |
| H | 14 | Multi-style sustain + offhand bonuses | Some (H4 mage offhand) |
| **I** | 11 | **MAGE elemental damage** + more mage damage stacks | **YES — core mage** |
| J | 13 | Tank / melee sustain / 0-dmg restore | Some (J8 sustain) |
| **K** | 13 | RANGED CORE | No |
| **L** | 8 | **LARGE elemental payloads + spell type conversions** | **YES — endgame mage** |
| M | 4 | LARGE melee | No |
| N | 9 | LARGE ranged + ranged stacks | No |

**Mage-relevant families:** B, C, F, I, L (and a few crossovers in H/J). The other families are for other styles — you can ignore them for a mage main.

## The "stackable suffix" pattern

When a family has small pacts ending in A-D, they're usually identical copies of the same effect. Take all of them to stack.

| Stackable group | What it does | Total if you take all |
|---|---|---|
| `BA, BB, BC` | +5% chance to Regenerate runes/ammo/charges | +15% regen |
| `CA, CB, CC` | +15% accuracy in all combat styles | +45% accuracy |
| `FA, FB, FC, FD` | +1% Magic damage | +4% mage damage |
| `IA, IB, IC, ID` | +1% Magic damage | +4% mage damage |
| `GA, GB, GC, GD` | +1% Melee damage | +4% melee |
| `HA, HB, HC, HD` | +1% Ranged damage | +4% ranged |
| `JA, JB, JC, JD` | +1% Melee damage (different family bridges) | +4% melee |
| `KA, KB, KC` | +1% Ranged damage | +3% ranged |
| `N1, N2, N3` | +1% Ranged damage (note: numeric suffix here, exception) | +3% ranged |
| Various sm pacts | +5 permanent Defence level boost | varies |
| Various sm pacts | +15% Prayer penetration | varies (caps at 100%) |

**Total mage damage available across both families:** FA-FD + IA-ID = **+8% magic damage** (8 stacks of +1% each). Both Option 2 and Option 3 builds take all 8.

## The L family is special

L pacts are mostly **large** (`lg` size) — the heavyweight endgame payloads. Each one is impactful enough that I separated them.

| Pact | Effect | What it does |
|---|---|---|
| `L1` | Air spells +1% max hit chance per prayer bonus, **doubled vs air-weak enemies** | The only weakness-exploit pact |
| `L2` | Water spell hits → 60% damage as heal | Major sustain |
| `L3` | Fire spell hits apply burn (max 5) + bounce to 2 nearby targets | AoE + burn DoT |
| `L4` | Earth spells +1 dmg per 12 def levels | Flat damage on Earth surge (~+8 dmg at 99 def) |
| `L5` | Smoke spells now count as 'air' spells | Conversion |
| `L6` | **Ice spells now count as 'water' spells** | **Lets Ice Barrage trigger water payloads** |
| `L7` | Blood spells now count as 'fire' spells | Conversion |
| `L8` | Shadow spells now count as 'earth' spells | Conversion |

L1-L4 are **damage payloads** (large pacts).
L5-L8 are **spell type conversions** (medium pacts) — they let Ancient Magicks Barrages trigger the basic-element payload effects.

## Quick decoder for any pact you see

When you see a pact ID, here's how to read it:

1. **First letter** → which family/branch
2. **Second char**:
   - If a number → unique medium effect (read the description)
   - If a letter → stackable small bonus (probably one of the standard +X% buffs above)
3. **L1-L4** → large payload, expect a big effect
4. **L5-L8** → spell-type conversion

### Examples from your build

| Pact | Decoded |
|---|---|
| `AA` | Family A (root) — the mandatory starting pact, 50% rune regen |
| `B1` | Family B, medium #1 — magic level boost when runes regenerate |
| `BA` | Family B, small stack #1 — +5% regen chance |
| `C2` | Family C, medium #2 — water rune regen → heal 1 |
| `CA` | Family C, small stack #1 — +15% accuracy |
| `F1` | Family F (mage core), medium #1 — **+35% accuracy** |
| `F7` | Family F, medium #7 — **−2 ticks combat spell speed** |
| `F8` | Family F, medium #8 — **−3 ticks powered staff (Eye of Ayak burst)** |
| `FA` | Family F, small stack #1 — +1% mage damage |
| `I1` | Family I (mage elemental), medium #1 — air spells +7% per active prayer |
| `I4` | Family I, medium #4 — earth spells drain enemy def + mage def |
| `IA` | Family I, small stack #1 — +1% mage damage |
| `L6` | Family L, conversion — **Ice spells count as water spells** |
| `L4` | Family L, large payload #4 — earth spells +1 dmg per 12 def levels |

## A pattern that's *almost* consistent (gotchas)

The system is mostly clean but has a few edge cases:

- **Family N**: numbers start at 1 but `N1-N3` are actually small +1% ranged stacks (numeric instead of letter — the only family that breaks the convention)
- **Family L**: contains both large damage pacts (L1-L4) AND medium conversions (L5-L8). Same family letter but different roles
- **Family F**: has BOTH medium pacts numbered F1-F13 AND small stacks FA-FD. F11 and F12 are small but use numbers (defence stacks). Inconsistent within the family
- **Family H**: H7, H10 are small prayer pen pacts despite having numbers (most other families use letters for stacks)

The pattern holds for ~90% of pacts. When in doubt, the size (`sm`/`md`/`lg`) tells you whether it's a stackable small or a unique medium/large.

## TL;DR

- **First letter** = family (mage cares about B, C, F, I, L)
- **Second character**: number = unique effect, letter = stackable bonus
- **Mage damage stacks**: FA-FD + IA-ID = +8% total
- **L family** = endgame elemental payloads + spell conversions
- **F8** = the powered staff burst pact (Eye of Ayak 1-tick)
- **L6** = the only conversion you really need (Ice→water for AoE Ice Barrage)

Save this file as your decoder ring whenever you see a pact ID.
