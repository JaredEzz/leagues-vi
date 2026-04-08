# Pact Build Candidates

Concrete 40-pact loadouts being evaluated. Each is a fully-decoded share link from osrsleaguescountdown.io with verified tree connectivity.

---

## Option 1 — Sustain + F8 Hybrid (40/40)

**Origin:** Forked from "Mage Regenerate Infinite Sustain" (share `1czkAyC8PACA4zAU-gAIRAAA`), with F8 slotted in by dropping leaf prayer-pen overcap.

**Identity:** Self-sustaining Ice Barrage engine with F8 burst for Eye of Ayak. Heavy on healing/regen, moderate DPS. Best for general PvM, Catacombs grinding, Slayer chaining.

### Loadout (40 pacts) — verified connected

```
AA, B1, BA, BC,
C2, C3, CA, CB, CC,
F1, F2, F3, F4, F5, F7, F8, F10, F12, F13,
FA, FB, FC, FD,
H7, H8, H9, H10,
I1, I2, I5, I6, I7, IB,
J5, J6, J7, J8, J9,
L2, L6
```

**Drops from base share** (3 leaves):
- `BB` — regen +5% leaf. Regen still caps via AA + remaining stacks.
- `K5` — prayer pen leaf. Pen still caps with 7 remaining stacks.
- `K7` — prayer pen leaf. Same.

**Adds** (3 zero-cost adjacent picks):
- `F8` — Powered staff −3 ticks (Eye of Ayak 1-tick, ~2.27× DPS) [neighbors: FB, FC]
- `F10` — Charge regen → +1 fire rune [neighbor: FC]
- `C3` — Fire rune regen → +1 dmg next spell hit per rune [neighbors: B1, CB]

### Key totals (after swaps)

| Stat | Value |
|---|---|
| Rune/charge regen chance | 100% (capped) |
| Magic damage | +5% (FA, FB, FC, FD, IB) |
| Prayer penetration | 100% (capped, 7 stacks) |
| Accuracy | +80% |
| Defence levels | +25 |
| Overheal cap | +90% HP (3 stacks) |

### Sustain loop

1. Cast Ice Barrage (Kodai) or fire EoA spec → triggers regen rolls
2. AA + 60% regen = ~100% chance to regen runes/charges per cast
3. Regenerated water rune → C2 heals 1 + L2 reflects 60% damage as heal + I2 +20% dmg at full HP
4. Regenerated charges (EoA/Shadow/DHW) → F5 chain regens water rune → C2 chain heals
5. F10 → fire rune regen → C3 buffs next spell damage
6. B1 → magic level boost on every regen tick (caps +10)
7. I6 → passive prayer regen, J8 → 0-dmg hit restores prayer

### Weapon profile

| Weapon | DPS profile |
|---|---|
| Eye of Ayak | F8 1-tick burst, F5/F10 fuel C2/C3 chains via charge regen |
| Tumeken's Shadow | F8 helps (powered staff), but Shadow is 2H so J8 off-hand bonus inactive |
| Kodai Wand (Ice Barrage) | F7 spell speed, L6 makes Ice = water → I2/L2/C2 fire, base AA regen on direct rune use |
| Dragon Hunter Wand | F5/F6/F10 trigger via wand charge regen |

### Caveats

- F8 −8 max hit makes EoA ~2.27× DPS via attack speed, validated in HANDOFF.md math.
- Skips full F+C elemental engine (F6/F9 + C1/C4) to keep healing intact.
- Prayer pen capped at 7 stacks; over-cap was wasted in source build.
- Earth + Air rune regen NOT included → does not exploit earth/air-weak bosses.

---

## Option 2 — Full Elemental DPS Engine (40/40)

**Origin:** Steiner-tree-optimized DPS build covering all 4 elemental damage chains. Designed to weapon-switch and spell-switch for any boss weakness in your regions. See [boss-weaknesses.md](boss-weaknesses.md) for the cross-referenced target list.

**Identity:** Pure DPS. Zero sustain pacts — relies on prayer flicks, supplies, and Augury for survival. Built for a skilled mage main who can handle mechanics without Pact-driven heals.

### Loadout (40 pacts) — verified connected

```
AA, B1,
BA, BB, BC,
C1, C3, C4,
CA, CB, CC,
F1, F3, F5, F6, F7, F8, F9, F10,
FA, FB, FC, FD,
I1, I2, I3, I4, I5, I7,
IA, IB, IC, ID,
L1, L3, L4, L5, L6, L7, L8
```

### Key totals

| Stat | Value |
|---|---|
| **Magic damage** | **+8%** (FA, FB, FC, FD, IA, IB, IC, ID — 8 stacks) |
| **Accuracy** | **+80%** (F1 +35% + CA/CB/CC 3×15%) |
| Rune/charge regen chance | 95% (50% AA + 3×5% BA/BB/BC + 30% F3) |
| Spell speed (spellbook) | F7 (−2 ticks, Ice/Smoke/Blood/Shadow Barrage to 3 ticks) |
| Powered staff speed | **F8 (−3 ticks, Eye of Ayak to 1-tick)** |
| Prayer penetration | +30% (I5 + I7) — partial, dropped to fit DPS |
| Defence levels | 0 — dropped entirely |
| Overheal cap | 0 — dropped entirely |

### The four elemental chains

| Element | Damage payload | Conversion | Charge→rune | Rune→payload |
|---|---|---|---|---|
| **Air** | I1 (+7% per active prayer) | L5 (Smoke→Air) | F6 | C1 (15% chance restore prayer) |
| **Water** | I2 (+20% at full HP) | L6 (Ice→Water) | F5 | (no C2 — heal dropped) |
| **Fire** | I3 (burn 6% HP for 2× return), L3 (burn + bounce) | L7 (Blood→Fire) | F10 | C3 (+1 dmg next spell hit) |
| **Earth** | I4 (drain enemy def + mage def 2/hit), L4 (+1 dmg per 12 def) | L8 (Shadow→Earth) | F9 | C4 (+1 def level per rune) |

Plus **L1**: Air spells +1% max-hit chance per prayer bonus, **doubled vs air-weak enemies** (only weakness-exploit pact in tree).

### Spellbook → boss matrix

**Critical clarification:** Powered staves (Eye of Ayak, Tumeken's Shadow) cast a **classless magic projectile** — NOT a typed spell. None of L1/L2/L3/L4/L5/L6/L7/L8 apply to their built-in attacks. Only `F8` (powered staff speed) helps them. The L-payloads only fire when you cast a **spellbook spell** with a wand.

| Boss element | Cast spell | Spellbook | Damage payloads triggered |
|---|---|---|---|
| **Earth-weak** (Olm, Wardens, Hueycoatl, Hydra, Kraken, Dark beast) | **Earth Surge** (single) OR **Shadow Barrage + L8** (multi) | Standard / Ancient | I4 (drain def 2/hit), L4 (+1 dmg per 12 def), C4 chain, F9 chain |
| **Water-weak** (Inferno, Yama, Hellhounds, DGorillas, Skotizo) | **Water Surge** (single) OR **Ice Barrage + L6** (multi) | Standard / Ancient | I2 (+20% @ full HP), F5 chain |
| **Fire-weak** (Ice Demon 150%, Vespula, Kephri, KQ, Amoxliatl) | **Fire Surge** (single) OR **Blood Barrage + L7** (multi) | Standard / Ancient | I3 (burn boost), L3 (burn+bounce AoE), C3 chain, F10 chain |
| **Air-weak** (Thermo, Smoke devils, Ankou) | **Air Surge** (single) OR **Smoke Barrage + L5** (multi) | Standard / Ancient | I1 (+7% per prayer), L1 (max hit chance, **2× vs air-weak**), F6/C1 chain |
| **No weakness** (Sol, Doom, Echos, ToA Akkha/Ba-Ba/Zebak, CoX side bosses) | Eye of Ayak built-in OR Shadow built-in | Powered staff | F8 1-tick burst + +8% raw mage damage. **No L payloads.** |

**Why keep the L conversions in Option 2:** they let you stay on Ancient Magicks (Barrage spellbook) for AoE Slayer/Catacombs grinding while still triggering elemental payloads. For single bosses, native Surge spells already work — see Option 3 if you don't need barrage AoE.

### Weapon profile

| Weapon | Best use | Pact synergies |
|---|---|---|
| **Eye of Ayak** (powered staff, 1H) | No-weakness single bosses, Doom delves, general PvM | F8 1-tick, +8% raw mage damage. **No L payloads** (built-in spell isn't a typed element). |
| **Tumeken's Shadow** (powered staff, 2H) | No-weakness bosses where raw DPS matters (Sol, Doom, Echos) | F8 1-tick, +8% mage damage stack ×3 (Shadow's passive triples gear bonus). **No L payloads.** |
| **Kodai Wand** (1H) + Ancient Magicks | All weakness exploitation via Barrage AoE | F7 spell speed, all 4 L conversions, all 4 I/L payloads |
| **Dragon Hunter Wand** (1H) | Dragons (Brimhaven, Hydra) — Hydra is earth-weak → cast Earth Surge or Shadow Barrage + L8 | F8 does NOT apply (wand). Use DHW's +75% acc/+40% dmg vs dragons + earth payloads |

### Off-hand swaps

| Off-hand | When |
|---|---|
| **Devil's Element** (Echo Thermy, Kandarin) | Default endgame — **doubles enemy elemental weaknesses** (Hueycoatl 60% → 120%, Ice Demon 150% → 300%). The single biggest force multiplier on this build. |
| **Tome of Water** (Tempoross, Desert) | Water-weak bosses pre-Devil's Element. +10% dmg on water spells |
| **Elidinis' Ward** (ToA, Desert) | Defensive interim. No element synergy |

### What's intentionally dropped vs Option 1

- **C2** (water rune → +1 heal)
- **L2** (water spell hits → 60% dmg heal)
- **F2, F13, H9** (3× overheal cap, +90% HP)
- **I6** (passive prayer regen)
- **J8** (0-dmg hit → +2 hp +2 prayer)
- **F4, F12, H8** (defence levels +25)
- **7 prayer pen stacks** (kept only 2 — 30% vs 100% capped)

In exchange you gain:
- **+3% magic damage** (5 → 8 stacks)
- **All 4 elemental damage chains** (was water-only)
- **All 4 spell conversions** (L5/L7/L8 added)
- **F8** Eye of Ayak burst
- **F1** +35% accuracy

### Caveats

- **Powered staves are not boosted by L payloads** — confirmed via wiki. Eye of Ayak and Tumeken's Shadow built-in spells are classless. Use them on no-weakness bosses where raw +mage damage and F8 speed matter most.
- **No prayer regen** — must drink restores or use altars between fights.
- **No heal sustain** — must brew/sara brews/blood barrage manually.
- **Ice Demon at 150% fire weakness × Devil's Element 2× = effective 300%** — Blood Barrage + L7 melts Ice Demon for fast CoX.
- **Hueycoatl at 60% earth × Devil's Element = 120%** — Shadow Barrage + L8 (or Earth Surge native) on this Day 1 DHW farming target.
- **L conversions pay off ONLY for AoE Slayer/multi-target.** For single bosses, switch to Standard spellbook and cast native Surge spells.

### Slot-swap candidates if you want a sustain hybrid

Drop these DPS picks to free slots for sustain:

| Drop | Effect lost | Gain back |
|---|---|---|
| `L5` (smoke→air) | Smoke Barrage no longer counts as air | Slot for `C2` (water heal) — direct add |
| `I7` (+15% prayer pen) | Prayer pen 30% → 15% | Slot for `F2` (overheal +30%) — direct add |
| `I5` (+15% prayer pen) | Prayer pen 15% → 0% | Slot for `J8` (0-dmg sustain) — needs path |

---

## Option 3 — Middle Ground: DPS + Light Sustain (40/40)

**Identity:** Drops the Slayer-only Barrage conversions (L5/L7/L8) and air-weakness exploit (L1) to fit critical sustain. Keeps the full single-boss DPS engine: all 8 mage damage stacks, all 4 elemental I-payloads, the L3/L4 large damage payloads, full F+C rune-regen chains, F8/F7. Adds back C2 heal, L2 bounce heal, 2× overheal cap, +20 def levels.

**Best for:** Hard PvM mains who don't barrage-grind Slayer often. Single bosses use native Surge spells which already trigger I/L payloads without conversions. Survival cushion for Inferno/ToA/Sol learning.

### Loadout (40 pacts) — verified connected

```
AA, B1,
BA, BB, BC,
C1, C2, C3, C4,
CA, CB, CC,
F1, F2, F3, F4, F5, F6, F7, F8, F9, F10,
FA, FB, FC, FD,
H8, H9,
I1, I2, I3, I4,
IA, IB, IC, ID,
L2, L3, L4, L6
```

**Note:** v2 swaps `I5` (15% prayer pen, mostly wasted at 1 stack) for `CA` (+15% accuracy + critical bridge that lets F1 unlock at task 5 instead of task 21). Net: better accuracy AND better unlock order.

### Key totals

| Stat | Value | vs Option 2 |
|---|---|---|
| **Magic damage** | **+8%** | same |
| Accuracy | **+80%** | same as Option 2 |
| Regen chance | 95% | same |
| Spell speed | F7 + F8 | same |
| Prayer pen | 0% | dropped |
| **Defence levels** | **+20** | +20 |
| **Overheal cap** | **+60% HP** | +60% |
| **Heal payloads** | **C2 + L2** | both added back |

### What's kept from Option 2

- **All 8 mage damage stacks** (FA, FB, FC, FD, IA, IB, IC, ID)
- **All 4 elemental damage payloads** (I1 air, I2 water, I3 fire, I4 earth)
- **L3 + L4** (fire bounce/burn + earth flat damage — large pacts, the high-impact payloads)
- **L6** (Ice Barrage → water for Slayer Catacombs water-weak content)
- **All 4 charge→rune** (F5/F6/F9/F10) and **all 4 rune→payload** (C1/C2/C3/C4)
- **F1, F7, F8** (accuracy, spell speed, powered staff burst)

### What's dropped from Option 2

- `L1` air weakness exploit — air is your lowest-priority element
- `L5` smoke→air conversion — only useful for AoE Slayer on smoke devils
- `L7` blood→fire conversion — Fire Surge already triggers I3/L3 natively
- `L8` shadow→earth conversion — Earth Surge already triggers I4/L4 natively
- `I5` + `I7` (both prayer pen stacks)

### What's added back for sustain

- `C2` — water rune regen → heal 1 per rune
- `L2` — water spell hits bounce 60% damage as heal
- `F2` — overheal cap +30% HP
- `H9` — overheal cap +30% HP (2× total = +60%)
- `F4` — +15 Defence levels
- `H8` — +5 Defence levels (also bridge connector)

### Boss matrix (no conversions, just native spells)

| Boss element | Cast | Spellbook | Triggers |
|---|---|---|---|
| **Earth** (Olm, Wardens, Hueycoatl, Hydra, Kraken) | **Earth Surge** | Standard | I4 (drain def 2/hit), L4 (+1 dmg/12 def), C4, F9 chain |
| **Water** (Inferno, Yama, Hellhounds, DGorillas) | **Water Surge** OR **Ice Barrage + L6** | Standard / Ancient | I2 (+20% @ full HP), L2 (60% bounce heal), C2 heal, F5 chain |
| **Fire** (Ice Demon, Vespula, Kephri, KQ) | **Fire Surge** | Standard | I3 (burn boost), L3 (burn+bounce AoE), C3, F10 chain |
| **Air** (Thermo, Smoke devils, Ankou) | **Air Surge** | Standard | I1 (+7% per active prayer), F6/C1 chain |
| **No weakness** | Eye of Ayak / Shadow built-in | Powered staff | F8 1-tick burst + +8% raw mage dmg |

### Tradeoff vs Option 2

| | Option 2 (Pure DPS) | Option 3 (Hybrid) |
|---|---|---|
| AoE Slayer barrage damage | Excellent (all conversions) | Limited (only L6 Ice Barrage→water) |
| Single-boss DPS | Excellent | Excellent (same stacks, payloads) |
| Sustain | None | Moderate (heal + overheal + def) |
| Survival in Inferno/Sol | Pure mechanics | Pacts contribute |
| Best for | Pure DPS, weapon-switch heavy | Mixed PvM, learning hard content |

### Why this is the recommended endgame build

- **Native Surge spells** already trigger I1-I4 and L3/L4 payloads without needing L5/L7/L8 conversions. The ~3 pact slots saved are better spent on sustain.
- **L6 (Ice→water) is kept** because Ice Barrage is the multi-target spell of choice for Slayer/Catacombs grinding on water-weak content (Hellhounds 50%, Demonic Gorillas 35%, Skotizo 40%) — there's no "water barrage" so this conversion is the only way to AoE on water.
- **Sustain matters** for hard PvM learning. Brews/restores work but pacts that auto-heal or restore prayer give breathing room when learning Sol/Inferno/Echo bosses.
- **F8 + 8 mage damage stacks** carries no-weakness content (Sol Heredit, Doom of Mokhaiotl, Echo content, ToA non-Wardens, CoX side bosses) just as well as Option 2.

---

<!-- Future options below -->
