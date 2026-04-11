# Primary Build: 100% Max Hit Air Mage

**Status:** Current primary build. Supersedes both the original Desert/Ancestral plan and the Crystal Mage/Tirannwn alt plan.
**Origin:** HeavyNettle's Reddit post — "100% max hit chance air mage build with 2 regions"
**Build URL:** https://tools.runescape.wiki/demonic-pacts/?n=1-10-107-108-109-11-12-122-2-44-45-46-5-55-56-57-58-6-60-67-69-7-72-74-8-82-83-86-9

---

## The Core Insight: Devil's Element (Demonic Pacts Version)

**CRITICAL:** The Demonic Pacts version of Devil's Element is fundamentally different from the Raging Echoes version.

| Version | Passive Effect |
|---|---|
| **Raging Echoes** | Doubles existing elemental weaknesses; does not introduce new ones |
| **Demonic Pacts** | **Adds 30% elemental weakness against ALL elements in addition to any existing weaknesses** |

With Devil's Element equipped, **every enemy in the game becomes at least 30% air-weak** (and water-weak, fire-weak, earth-weak simultaneously). This is the cornerstone of the build.

### Why This Changes Everything

The L1 pact: "Air spells have a +1% chance to max hit for every 1 prayer bonus, **this chance is doubled against enemies weak to air spells**."

Before DE: L1's doubling only applied to traditionally air-weak content (smoke devils, dust devils, Thermy). The build was a specialized Slayer engine.

With DE's universal weakness: **L1's doubled mode triggers on EVERY TARGET.** Every boss, every raid, every slayer monster is now air-weak. The build is no longer specialized — it's universal BIS.

At 56+ prayer bonus × 2 (doubled) = **100% max hit chance on every target in the game.**

---

## Gear: Max Prayer, Not Mage Armor

Mage armor (Ancestral, Virtus, Crystal) is actively WORSE for this build than max prayer gear. The reason is simple: L1's max hit chance scales with prayer bonus, not magic damage. Max prayer gear gives ~60 prayer bonus vs ~20 for crystal or ancestral. The L1 proc rate advantage (80-100% vs 40%) outweighs the max hit advantage from mage armor.

### The Loadout

| Slot | Item | Prayer | Magic Atk | Magic Dmg % | Source |
|---|---|---|---|---|---|
| **Head** | Mitre (Sara/Zam/Guthix) or Zealot's helm | +4 to +6 | 0 | 0% | GWD (Fremennik) or Muspah (if Fremennik) |
| **Neck** | Dragonbone / Bonecrusher necklace | **+12** | 0 | 0% | Alchemical Hydra (Kourend) — hydra tail needed |
| **Body** | Zealot's / Sunfire Fanatic / Proselyte | +6 to +8 | 0 | 0% | Varies by region |
| **Legs** | Zealot's / Sunfire Fanatic / Proselyte | +5 to +6 | 0 | 0% | Varies by region |
| **Cape** | Ardougne cloak 4 | +4 | 0 | 0% | Elite Ardougne Diary (Kandarin) |
| **Weapon** | **Shadowflame Quadrant (SQ)** | 0 | +25 | **+15%** | Echo Thermy (Kandarin) |
| **Offhand** | **Devil's Element** | +3 | +20 | +6% | Echo Thermy (Kandarin) |
| **Ammo** | Holy blessing / Crystal blessing | +5 to +8 | 0 | 0% | Varies |
| **Ring** | Ring of the gods (i) | **+8** | 0 | 0% | Dagannoth Rex (Fremennik) |
| **Boots** | Devout boots | **+7** | 0 | 0% | Kourend & Kebos Hard Diary reward |
| **Gloves** | Holy wraps | +1 | 0 | 0% | Last Man Standing |

**Total prayer bonus: ~55-60** (depending on 3rd region pick and specific items available).

### The Only Mage Items

**Just two slots matter for magic:**
- **Shadowflame Quadrant** (+25 atk, +15% dmg, spell echo, auto-weakness, 5-tick base)
- **Devil's Element** (+20 atk, +6% dmg, +30% universal elemental weakness)

Every other slot sacrifices magic stats for prayer bonus. The build's damage comes from:
1. Pact stacks (not gear)
2. I1 active prayer scaling (not gear damage%)
3. L1 100% max hit chance (via prayer bonus)
4. DE's universal 30% weakness multiplier
5. Culling Spree's free Slayer helm effect (on task)

---

## DPS Calculations

### Shared Assumptions

- 99 Magic, Air Surge base max hit: 22
- 6 active prayers for I1: +42% damage
- Additive magic damage %: SQ 15% + DE 6% + pact 3% + offhand node12 2% = **+26%**
- SQ at F7 3-tick speed (1.8s per cast)
- B1 effective +10 magic levels → slight base max hit increase
- L1 hits 100% max hit chance cap (assume every cast = max hit)
- SQ spell echo: +40% second hit on elemental spells

### Air-Weak Content (Thermy, smoke devils, dust devils)

Thermy has 100% air weakness natively + 30% DE = 130% effective air weakness.

```
Max hit = 22 × 1.26 × 1.42 × 2.30 × 1.15 (Slayer helm on task)
       ≈ 105
```

With echo: 105 + 42 = **147 damage per cast**
**DPS: 147 / 1.8 = ~82**

### Non-Weakness Content (Sol Heredit, Doom, Vardorvis, Inferno, CoX Olm, etc.)

Target has no native weakness + 30% air weakness from DE alone.

```
Max hit = 22 × 1.26 × 1.42 × 1.30 × 1.15 (on task)
       ≈ 59
```

With echo: 59 + 24 = **83 damage per cast**
**DPS: 83 / 1.8 = ~46**

### Comparison: Air Mage vs Crystal EoA+F8 vs Ancestral

| Build | Non-weakness DPS | Air-weak DPS | Gear complexity | Region requirement |
|---|---|---|---|---|
| **Air Mage + SQ + Max Prayer** | **~46** | **~82** | Low (one gear set) | Kourend + Kandarin + 1 |
| Crystal EoA + F8 | ~25 | ~25 | High (crystal set + blessing) | Kourend + Kandarin + Tirannwn |
| Ancestral EoA + F8 | ~10.5 | ~10.5 | Very high (CoX grind) | Kandarin + Kourend + ??? |

**Air mage wins by 84% on non-weakness content and dominates air-weak Slayer.** No other build comes close.

---

## Region Strategy

### Mandatory Regions (for SQ + DE + bonecrusher)
- **Varlamore** (start)
- **Karamja** (auto-unlock)
- **Kandarin** (Echo Thermy → SQ + DE, Ardougne cloak 4)
- **Kourend** (Alchemical Hydra → Dragonbone necklace, Devout boots from Hard Diary)

That's 4 regions. You get 1 more pick.

### 3rd Region Choice: Fremennik vs Tirannwn vs Desert

#### Option A: Fremennik (RECOMMENDED for max prayer bonus)

**Why:** Fremennik uniquely provides the highest-tier prayer bonus items.

| Unlocks | Prayer bonus | Other value |
|---|---|---|
| **Dagannoth Rex** | Ring of the gods (+8 prayer) | BIS prayer ring |
| **Saradomin GWD** | God cape (+2-6 prayer), Sara hilt gear | Access to Nex, Bandos, Zamorak, Armadyl |
| **Zamorak GWD** | Zamorak Mitre (+4 prayer) | Staff of the Dead, Zamorak Spear |
| **Temple of Light / Phantom Muspah area** | Zealot's robes (+6/+8/+6 = +20 prayer) | Ancient tablets |
| **Blast Furnace (Keldagrim)** | — | Best Smithing training |
| **Lunar Spellbook** | — | NPC Contact for Slayer tasks remotely |
| **Dagannoth Kings** | Berserker ring, Seers ring (i), Archers ring (i) | BIS rings all styles |
| **Vorkath** | — | Consistent GP, d claws, Dragonfire Ward |

**Max prayer setup with Fremennik:**
- Zamorak Mitre: +4
- Dragonbone necklace: +12
- Zealot's robe top: +8
- Zealot's robe bottom: +6
- Ardougne cloak 4: +4
- Devil's Element: +3
- Holy blessing: +8
- Ring of the gods (i): **+8**
- Devout boots: +7
- Holy wraps: +1
- **Total: +61 prayer bonus**

61 × 2 = 122% L1 chance on air-weak (capped at 100%) and 61% on non-weakness → doubled by DE-imposed weakness to **100%+ on everything**.

#### Option B: Tirannwn (Crystal/Prif QoL)

**Why:** Better skilling QoL + CG as backup content + crystal gathering tools.

| Unlocks | Prayer bonus | Other value |
|---|---|---|
| **Prifddinas** | Bonecrusher necklace (+12) | Best Agility course, elite Thieving |
| **Corrupted Gauntlet** | Crystal blessing ammo (+5) | Backup crystal armor if ever needed |
| **Zulrah** | — | Blowpipe, Magic Fang, herb drops |
| **Crystal trees** (Nature's Accord tree patch) | — | Passive crystal shards |
| **Crystal tools** | — | Crystal pickaxe/axe/harpoon for EH gathering |

**Max prayer setup with Tirannwn:**
- No good mitre source (Fremennik has GWD mitres)
- Bonecrusher necklace: +12 (same as dragonbone)
- Zealot's robes: NOT ACCESSIBLE (Phantom Muspah is Fremennik-adjacent)
- Ardougne cloak 4: +4
- Devil's Element: +3
- Crystal blessing: +5
- Ring of the gods: NOT ACCESSIBLE (no DK, no Wilderness)
- Devout boots: +7 (Kourend diary)
- Holy wraps: +1
- **Total: ~+32 prayer bonus** (missing ring, mitre, top-tier armor)

32 × 2 = 64% L1 chance on air-weak. **Significantly lower than Fremennik option.**

#### Option C: Desert (ToA + Lightbearer)

| Unlocks | Prayer bonus | Other value |
|---|---|---|
| **ToA** | Masori (no prayer), Lightbearer (no prayer) | Best raid for mage, spec restore ring |
| **Giants' Foundry** | — | Best Smithing training |
| **KQ** | — | D-pick source |
| **Tempoross** | — | Dragon harpoon, spirit flakes |
| **Pharaoh's Sceptre** | — | Desert teleports |

**Max prayer setup with Desert: similar to Tirannwn (~32 prayer bonus).** Desert doesn't add prayer gear — it adds raid content and skilling tools.

### Verdict on 3rd Region

**Fremennik is the correct 3rd pick for this build.** The +29 extra prayer bonus (61 vs 32) is worth far more than any skilling QoL or raid content from Tirannwn/Desert.

**Final regions: Varlamore + Karamja + Kandarin + Kourend + Fremennik**

---

## Pact Plan

HeavyNettle's 29-pact loadout is the starting point. I recommend a few adjustments.

### HeavyNettle's Loadout (Decoded)

| Pact | Effect |
|---|---|
| AA | 50% regen chance (foundation) |
| F3 | +30% regen chance |
| node60 | +30% regen chance |
| B1 | Combat spell regen → +10 magic level cap boost |
| C1 | Air rune regen → 15% chance restore 1 prayer |
| C2 | Water rune regen → heal 1 |
| F1 | +35% accuracy all styles |
| F7 | **Combat spell speed -2 ticks (SQ 5→3 tick)** |
| I1 | **Air spells +7% damage per active prayer** |
| L1 | **Air spells +1% max hit chance per prayer bonus, doubled vs air-weak** |
| FA, FB, FC | +1% magic damage each (3 stacks = +3%) |
| Node 12 | **+2% magic damage while offhand equipped** (always active with DE) |
| CA, CB, CC + 6 more accuracy pacts | +195% total accuracy (capped at 100%) |
| Node 6, 8 | +10 permanent Defence |
| Nodes 2, 5, 9, 72, 74 | Path connectors (ranged/melee filler) |

### Accuracy Is a Multiplier, Not a Cap

**Correction:** Accuracy stacks are multiplicative, not capped at 100%. +195% accuracy means your attack roll is multiplied by 2.95x, NOT capped. Against high-def bosses (Olm, Sol Heredit, Inferno enemies) this is genuinely valuable and should NOT be dropped.

HeavyNettle's accuracy-heavy stack is correct. The build relies on:
- **L1 max hit chance** (damage guarantee)
- **I1 active prayer scaling** (damage amp)
- **Massive accuracy stack** (ensuring casts LAND, not just hit max)

Without crystal armor's 1.3x multiplier or Ancestral's +83 magic attack, the accuracy pact stack is load-bearing for overcoming boss magic defence. Don't drop it.

### Suggested Optional Improvement

If you can find a path in the tree to fit more damage stacks without sacrificing core accuracy/regen/L1/I1/F7, pick up:
- FD, IA, IB, IC, ID (+1% magic damage × 5)
- = **+5% more magic damage** (from +3% to +8% total)

But this is a path-routing optimization — don't force it if it breaks your connectivity. HeavyNettle's 29-pact structure is proven.

**Keep the core L1 + I1 + F7 + accuracy engine intact.** That's what makes the build work.

### Totals (HeavyNettle's Build)

| Stat | Value |
|---|---|
| Accuracy multiplier | +195% (nearly 3x attack roll, multiplicative) |
| Magic damage | +3% pacts + 2% offhand (node12) = +5% |
| Regen chance | ~100% (AA + F3 + node60) |
| Spell speed | F7 (SQ 5→3 tick) |
| Prayer-based damage | I1 6-stack (+42%) |
| Max hit chance | L1 100% via 56+ prayer bonus, doubled vs air-weak (universal with DE) |
| Magic level boost | B1 (+10 effective magic) |
| Defence | +10 permanent |

### Max Hit Reference (unchanged from HeavyNettle's original)

- Air-weak Thermy (130% weakness): ~105 max hit
- Non-weakness boss (30% weakness from DE): ~59 max hit
- At 100% L1 chance: every cast = max hit

### Pacts NOT Needed

- **F8** (powered staff speed): EoA is no longer the bossing weapon. Skip entirely.
- **L5/L6/L7/L8** (spell conversions): You only cast Air Surge. Other element conversions are irrelevant.
- **I2/I3/I4** (water/fire/earth payloads): Air-only build. Skip.
- **L2** (water bounce heal): No water spells cast.
- Heavy overheal stacks: Max prayer gear + Flask of Fervour + bonecrusher necklace sustain is enough.

---

## Active Prayer Stack for I1 (+42% damage)

I1 gives +7% damage per active prayer. Stack 6 for +42%:

| Prayer | Effect | Drain | Slot |
|---|---|---|---|
| **Augury** | +25% magic dmg, +5% acc, +25% mage def | High | Magic (required) |
| **Protect from [style]** | Damage reduction | Medium | Protection |
| **Preserve** | Stats decay 50% slower | Very Low | Utility |
| **Rapid Restore** | 2x stat regen | Very Low | Utility |
| **Rapid Heal** | 2x HP regen | Very Low | Utility |
| **Mystic Will / Thick Skin** | Minor buffs (just for stack) | Very Low | Filler |

**6 active prayers = +42% damage from I1.**

Prayer drain with max prayer gear (+60 bonus) + bonecrusher necklace passive + Flask of Fervour cooldowns = sustainable.

---

## Skilling Impact

The air mage build uses prayer armor, not mage armor. This has some skilling implications:

| Skill | Impact | Mitigation |
|---|---|---|
| **Crafting** | No change — EH gem rocks still work | Unchanged |
| **Smithing** | No change — EH + Hotfoot free bars + 2-tick anvil | Unchanged |
| **Runecraft** | No change — Map of Alacrity Zeah loop | Unchanged |
| **Fishing** | No change — Hotfoot auto-cooks | Unchanged |
| **All gathering** | No change — EH + Flow State + Hotfoot | Unchanged |
| **Slayer** | **Massive boost** — 82 DPS on barrage tasks | Air mage Slayer is the best |
| **Bossing** | **Massive boost** — 46 DPS on everything | Universal upgrade |
| **Inferno** | Easier due to high DPS + Flask of Fervour + prayer sustain | Cleaner attempts |

The relic engine (EH + Hotfoot + Flow State + Transmutation + Nature's Accord + Culling Spree + MoA) is unchanged and still handles all skilling.

---

## Gear Progression Timeline

### Week 1: Varlamore + Karamja Bridge

| Slot | Item | Source |
|---|---|---|
| Weapon | **Eye of Ayak** | Doom of Mokhaiotl |
| Body/Legs/Helm | **Blue Moon set** | Moons of Peril |
| Boots | **Avernic Treads** | Doom of Mokhaiotl (delve 4+) |
| Weapon (dragons) | **Dragon Hunter Wand** | Hueycoatl (1/105) |

Bridge weapons. EoA for general, DHW for dragons. No air mage build yet — just surviving and building points.

### Week 2: Kourend (2nd pick recommended) — Start Prayer Gear

Focus: XP engine (WT, Catacombs, anglerfish, Blood/Soul RC) + early prayer gear.

| Slot | Upgrade | Source |
|---|---|---|
| Neck | **Dragonbone necklace** | Alchemical Hydra (Kourend) |
| Boots | **Devout boots** | Kourend & Kebos Hard Diary |
| Ammo | Holy blessing | Varies — check accessible sources |

Also: start stockpiling elite clue scrolls from Slayer for prayer gear drops later.

### Week 3: Kandarin (3rd pick) — THE Weapon Unlock

**Prerequisites before Kandarin pick:**
- Culling Spree (T6 relic) active
- 93 Slayer
- Points for Echo Thermy access

| Slot | Upgrade | Source |
|---|---|---|
| **Weapon** | **Shadowflame Quadrant** | Echo Thermy |
| **Offhand** | **Devil's Element** | Echo Thermy |
| Cape | **Ardougne cloak 4** | Elite Ardy Diary |
| Body/Legs bonus | Sunfire Fanatic | Sol Heredit (if not already) |

**Once SQ + DE are in hand, the air mage build is ONLINE.** You can start using it immediately even with incomplete prayer gear.

### Week 4: Fremennik (4th pick) — Complete Prayer Stack

| Slot | Upgrade | Source |
|---|---|---|
| Head | **Zamorak Mitre** | Zamorak GWD (or elite clue backup) |
| Ring | **Ring of the gods (i)** | Dagannoth Rex |
| Body | **Zealot's robe top** | Phantom Muspah area |
| Legs | **Zealot's robe bottom** | Same |
| Cape (alt) | Imbued god cape | GWD bosses |

**Alternative: Skip Fremennik, farm elite clues harder for mitres + Armadyl robes.** Works at ~80-90% efficiency of Fremennik path.

### Week 5+: Endgame

- Full max prayer build online
- Push Inferno, ToB, high-invocation ToA (if Desert), Doom high delves
- 200m XP grinds with EH + Hotfoot + Flow State
- Collection log completion

## Regions Decision Update

**The build can work with 2 different 3rd+4th region combos:**

### Path A: Kandarin + Kourend + Fremennik (MAX PRAYER)

Best overall prayer bonus (~61). Ring of the gods is the big unique. Access to GWD, Nex, DK rings, Lunar spells, Vorkath, Blast Furnace.

**Prayer bonus: ~61** → L1 at 100% cap + big buffer.

### Path B: Kandarin + Kourend + Tirannwn (CLUE-SUPPLEMENTED)

Lower prayer bonus from regions (~32-45) but supplemented by elite clue rewards (mitres, Armadyl robes). Gains Prifddinas QoL, Zulrah, crystal tools, Zalcano d-pick, CG as backup.

**Prayer bonus: ~45-55** with clue rewards → L1 still hits 90-100% cap against air-weak content.

### Path C: Kandarin + Kourend + Desert (RAID FOCUS)

Adds ToA + Lightbearer + Tempoross + Giants' Foundry. Lower prayer bonus (~40-50) but gains raid content and Lightbearer for spec management.

**Prayer bonus: ~40-50** → L1 at 80-100% chance on air-weak. Weaker on non-weakness content.

### Recommendation

**Fremennik is the strict optimal pick** for pure air mage BIS. Ring of the gods (+8) alone is +16% L1 chance on air-weak vs not having it. Plus the GWD/DK/Vorkath content is excellent.

**But if you want Prifddinas QoL or ToA raids, you can make Tirannwn or Desert work** with aggressive elite clue farming for prayer gear. The build still functions at ~90% efficiency.

---

## This Is a LATE Build — How Long Until It's Running?

**This is not a Day 1 build.** It's locked behind several prerequisites that all gate the core setup. Here's the realistic timeline.

### Critical Gates

| Gate | Unlocks | Why it matters |
|---|---|---|
| **Culling Spree (T6 relic)** | Choose Slayer tasks on demand | Without it, Echo Thermy tasks are random luck. Can't reliably farm SQ + DE. |
| **Kandarin (2nd or 3rd region pick)** | Echo Thermy access | SQ + DE are the entire weapon setup. Nothing works without them. |
| **93 Slayer** | Smoke devil tasks | Echo Thermy needs smoke devil task (or echo orb). |
| **Kourend unlock** | Alchemical Hydra → dragonbone necklace, Devout boots via Hard Diary | Core prayer gear. |
| **Fremennik unlock** (if 3rd region) | Ring of the gods, god mitres, Zealot's robes | Completes prayer stack. |

### Point Requirements Estimate

You need enough league points to reach T6 (Culling Spree), plus the tasks to unlock Kandarin, Kourend, and Fremennik. Rough estimate:

- **T1 → T6:** ~3500-4500 points (varies with task completion)
- **Region unlocks:** Kandarin/Kourend/Fremennik each cost ~1500-2500 points depending on unlock order
- **Total to setup:** ~8000-10,000 points

**Realistic timeline:**
- **Week 1:** Varlamore + Karamja content. EoA from Doom, Fire Cape, early bosses, first region pick.
- **Week 2:** Second region (likely Kourend for XP engine), reach T5-T6. Start Alch Hydra for hydra tail.
- **Week 3:** Third region (Kandarin), 93 Slayer grind, Culling Spree unlocks, Echo Thermy farming starts.
- **Week 4:** SQ + DE in hand, fourth region (Fremennik), start completing prayer gear set.
- **Week 5+:** Build fully online. Push hard content, 200m grinds, collection log.

**The air mage build is an endgame setup, not an early-game carry.** You need a different plan for the first 2-3 weeks.

## Early Game Bridge: What to Use Before SQ + DE

You can't wait around for Echo Thermy. Here's the progression before the air mage build is online.

### Phase 1 (Day 1 - Week 1): Eye of Ayak + Blue Moon Set

| Slot | Item | Source | Available |
|---|---|---|---|
| Weapon | **Eye of Ayak** | Doom of Mokhaiotl | Day 1 Varlamore |
| Body/Legs/Head | Blue Moon set | Moons of Peril | Day 1 Varlamore |
| Boots | Avernic Treads | Doom of Mokhaiotl (delve 4+) | Day 1 Varlamore |

Eye of Ayak is your Day 1 weapon. Built-in spell is classless (no L payloads apply) but it's the fastest early-game powered staff. Use it for all bossing until SQ unlocks.

### Phase 2 (Week 2-3): Dragon Hunter Wand + Any Mage Armor You Can Find

| Slot | Item | Source | Notes |
|---|---|---|---|
| Weapon (dragons) | **Dragon Hunter Wand** | Hueycoatl (1/105, Varlamore) | +75% acc/+40% dmg vs dragons |
| Weapon (general) | Eye of Ayak | Doom | Still your primary |
| Body | Mystic top / Infinity (if shops) | Varies | Whatever has magic stats |
| Ammo | Holy blessing (if accessible) | Various | Start building prayer bonus |

### Phase 3 (Mid-Week 2+): Fire Surge via Kodai or Mage's Book

**Critical early substitute for Air Surge on Thermy (pre-SQ):**

Before you have SQ + DE, you can still cast Air Surge via any staff that autocasts. At 81 Magic you unlock Air Surge (40 max hit cast from standard spellbook). Pair with:

- **Any staff** (Staff of air, Mystic air staff, Mage's book offhand)
- **Holy blessing ammo** for some prayer bonus
- **L1 still works** but without high prayer bonus it's low % chance
- **I1 still works** with 6 active prayers for +42% damage

**But there's no DE yet** — so Thermy is still only naturally air-weak (100%), not amplified to 130%. And no 30% weakness on other targets.

**Early-game Thermy cheese:** Thermy is already 100% air-weak. Even without DE, casting Air Surge with any staff + Augury + max prayer stack you can assemble = reasonable DPS on Thermy tasks for barrage Slayer XP.

### Phase 4 (Week 3+): Echo Thermy Farming Begins

Once Kandarin is unlocked AND Culling Spree (T6) is active AND 93 Slayer:
1. Force smoke devil task via Culling Spree
2. Grind Thermy for Tome of Fire / Occult / Smoke Battlestaff
3. Unlock Echo Thermy (fight enhanced version)
4. Farm Echo Thermy for SQ + DE (rates TBD but 5x drop rate helps)

**Expected time from Kandarin unlock to SQ + DE: ~3-5 hours** of active Echo Thermy farming with a full point efficient setup.

## Prayer Gear Fast-Track

### Clue Scrolls via Culling Spree

Culling Spree superiors drop 1-3 elite clues. At 5x drop rates (T4), you'll drown in clues during barrage Slayer. Elite clue reward lists include:

| Item | Prayer Bonus | Rarity |
|---|---|---|
| **3rd age mage robes** (3 pieces) | Mage bonuses | Rare elite clue reward |
| **Armadyl robe top/bottom** | +3/+2 prayer, +8/+6 magic atk | Hard/elite clue reward |
| **Saradomin/Zamorak/Guthix/Armadyl mitre** | +4 prayer | Elite clue reward |
| **Holy sandals** | +3 prayer | Hard clue reward |
| **Zealot's robes** (helm/top/bot) | +6/+8/+6 prayer | Hard clue reward |

**Critical:** Clue rewards are the fastest source of prayer gear without region unlocks. Do a few hundred elites during barrage Slayer and you'll build most of the set passively. This sidesteps the "need Fremennik for mitres" problem — clue mitres work fine.

### Region-Locked Prayer Gear Sources

| Item | Prayer | Primary Source | Region | Clue backup? |
|---|---|---|---|---|
| Dragonbone necklace | +12 | Alchemical Hydra | **Kourend** | No |
| Devout boots | +7 | Kourend Hard Diary reward | **Kourend** | No |
| Ring of the gods (i) | +8 | Dagannoth Rex | Fremennik | No (Chaos Fanatic wilderness) |
| Zamorak mitre | +4 | Zamorak GWD or **elite clue** | Fremennik OR clue | **Yes, elite clue** |
| Sara/Guthix mitre | +4 | GWD or **elite clue** | Fremennik OR clue | **Yes, elite clue** |
| Armadyl robe top | +3 | Armadyl GWD or **elite clue** | Fremennik OR clue | **Yes, hard+ clue** |
| Armadyl robe bot | +2 | Same | Fremennik OR clue | **Yes** |
| Zealot's robes | +20 total | Phantom Muspah | Fremennik-adjacent | No |
| Ardougne cloak 4 | +4 | Elite Ardy Diary | **Kandarin** | No |
| Sunfire Fanatic | varies | Sol Heredit | **Varlamore** | No |

**Key insight:** If you farm enough elite clues via Culling Spree + Conniving Clues (if slotted), you can get a passable prayer set WITHOUT Fremennik. You lose Ring of the gods (+8) and Devout boots needs Kourend diary, but mitres + Armadyl robes come from clues.

### Is Crystal Armor Competitive?

Even with the blessing giving +60 magic atk and +6% dmg, crystal armor has low prayer bonus (~+9 total with blessing). Compared to clue-sourced prayer gear:

| Setup | Prayer Bonus | Magic Atk | Magic Dmg % |
|---|---|---|---|
| Crystal + Blessing | +9 | +24 | +6% |
| Armadyl robes + Zealot set + mitre + clue gear | **+30-40** | 0-10 | 0% |

**Prayer gear wins for this build.** Crystal is only worth it for powered staff builds (EoA + F8) which aren't the current plan.

## Why This Build is BIS

1. **Universal damage via DE.** Every enemy is air-weak. L1 triggers everywhere.
2. **100% max hit chance.** Prayer bonus stacking + L1 doubling = guaranteed max hit on every cast.
3. **Only 2 mage items needed.** SQ + DE. Everything else is prayer armor. Massively simplifies gearing.
4. **~46 DPS on non-weakness content.** Beats crystal EoA+F8 by 84%, beats Ancestral EoA by 340%.
5. **~82 DPS on air-weak Slayer.** Dominant on barrage tasks.
6. **Sustain from max prayer bonus + bonecrusher necklace + Flask of Fervour.** Self-healing air mage.
7. **Works with your existing relic plan.** EH + Hotfoot + Flow State engine unchanged.
8. **Doesn't require CG grind.** Crystal armor obsolete → can skip Tirannwn if preferred.
9. **Culling Spree + SQ spell echo + auto-weakness = perfect barrage Slayer.** Best Slayer build possible.
10. **Flask of Fervour + active prayers = Inferno-capable sustain.** Can push hard content.

---

## What Changed from Previous Builds

| Build | Status | Why Obsolete |
|---|---|---|
| Original (Desert + Ancestral + EoA F8) | **Retired** | Ancestral loses to max prayer gear for L1 build. Desert only needed if you want ToA. |
| Crystal Mage (Tirannwn + crystal armor + EoA F8) | **Retired** | Crystal armor loses to max prayer gear. F8 EoA path obsolete due to air mage DPS superiority. |
| **Air Mage Max Prayer (this)** | **Current** | Devil's Element universal weakness makes air mage BIS for everything. |

The pivot is driven entirely by the Demonic Pacts version of Devil's Element adding +30% elemental weakness to ALL enemies instead of only doubling existing weaknesses. This single relic text change invalidates both previous build plans and makes a prayer-stacking air mage the universal BIS.
