# Pact Phasing & Respec Plan

How to roll out the Demonic Pacts build across the league. Maps each phase to:
1. Which pacts to unlock as points come in
2. When to use each of your 3 respecs
3. Which gear unlocks gate which pacts being worth taking
4. What spellbook is available

Target endgame build: **Option 3 (DPS + Light Sustain)** in [builds.md](builds.md). The earlier phases pre-build toward this.

---

## Surge vs Barrage — answering the spellbook question first

> "Is there a reason to spend points converting smoke or shadow to their respective elemental types when I have access to surge spells with wrath runes from Transmutation? Are the max hits just so much higher?"

Short answer: **conversions only matter for AoE multi-target. For single bosses, native Surge spells are better.**

### Numbers (99 Magic, no boosts)

| Spell | Spellbook | Max hit | Targets | Element | Gates |
|---|---|---|---|---|---|
| Air Surge | Standard | 22 | 1 | Air native | 81 Magic |
| Water Surge | Standard | 24 | 1 | Water native | 85 Magic |
| Earth Surge | Standard | 26 | 1 | Earth native | 90 Magic |
| **Fire Surge** | Standard | **24** | 1 | Fire native | 95 Magic |
| **Ice Barrage** | Ancient | **30** | **9 (3×3)** | Ice → water w/ L6 | 94 Magic, **Desert region** |
| Smoke Barrage | Ancient | ~27 | 9 | Smoke → air w/ L5 | 94 Magic, Desert |
| Blood Barrage | Ancient | 29 | 9 | Blood → fire w/ L7 | 92 Magic, Desert |
| Shadow Barrage | Ancient | 28 | 9 | Shadow → earth w/ L8 | 92 Magic, Desert |

### When each wins

| Scenario | Best spell | Conversion needed? |
|---|---|---|
| **Single boss, fire-weak** (Ice Demon, Vespula, Kephri) | Fire Surge | **No** — native fire triggers I3/L3 directly |
| **Single boss, earth-weak** (Olm, Wardens, Hueycoatl, Hydra) | Earth Surge | **No** — native earth triggers I4/L4 directly |
| **Single boss, water-weak** (Yama, Inferno) | Water Surge | **No** — native water triggers I2 directly |
| **Single boss, air-weak** | Air Surge | **No** — native air triggers I1/L1 directly |
| **AoE Slayer/Catacombs, water-weak** (Hellhounds, Demonic Gorillas) | Ice Barrage | **L6 yes** — there's no "water barrage", L6 is the only AoE water option |
| **AoE Slayer, fire-weak** (Ice Demon trash, Sarachnis) | Blood Barrage + L7 OR Fire Wave (Standard, single target) | L7 needed for AoE; Fire Wave for ST |
| **AoE Slayer, earth-weak** (Dark beast, dragons) | Shadow Barrage + L8 OR Earth Surge ST | L8 only if you want AoE |
| **AoE Slayer, air-weak** (Smoke devils, Ankou) | Smoke Barrage + L5 OR Air Surge ST | L5 only if you want AoE |

### The verdict

- Barrages have **+4-6 max hit** AND **9× target coverage** vs Surges. That's a big advantage when the targets are stacked.
- For **single bosses**, the multi-target is wasted, and the +4-6 max hit is less valuable than the slot cost of pathing to the conversion (3 picks per conversion: I[X], I[Letter], L[X/conversion]).
- **L6 is special:** the only AoE water spell exists via Ice Barrage + L6. Keep it.
- **L5/L7/L8 are luxury picks:** worth it ONLY if you do heavy AoE Slayer barrage on those weakness types. Option 3 (recommended) drops them.
- **Switching spellbooks is free at altars** in Leagues. There's no penalty for using Standard for boss DPS and Ancients for AoE Slayer.

### Spellbook gating (CRITICAL for early game)

**Ancient Magicks requires the Desert region unlock.** This is your **2nd** region pick. So:
- **Phase 1-2 (Varlamore + Karamja + Kourend)**: Standard spellbook only. **No Ice Barrage.** Use Surge spells.
- **Phase 3+ (Desert unlocked)**: Ancients available. L6 + Ice Barrage become usable. L conversions become evaluable.

This means **Phase 1-2 Slayer in Catacombs is single-target Surge spamming**, not multi-target Ice Barrage. Plan accordingly.

---

## Pact phasing by region unlock

### Phase 1 — Varlamore + Karamja (Day 1, ~5x scaling)

**Spellbook:** Standard only.
**Best damage spell:** Fire Wave / Earth Wave / Fire Surge once you hit 95 Magic.
**Available pacts you can use immediately** (they trigger off Standard spellbook spells):
- AA, B1 (foundation)
- F1 (+35% acc) — instant DPS uplift
- F7 (-2 ticks combat spell speed) — works on Surge spells
- FA, FB, FC, FD (+4% mage damage, foundational)
- I1, I2, I3, I4 (elemental damage payloads) — work natively with Surge spells
- B1 + C1/C3/C4 chain (rune-regen payloads)
- AA + BA/BB/BC + F3 (regen %)

**Pacts NOT yet useful in Phase 1:**
- L6 (Ice→water) — no Ice Barrage spell available
- L5/L7/L8 — no Smoke/Blood/Shadow spells available
- F+C water heal C2 — can use, but Surge spells regen runes already
- F8 — only useful AFTER Eye of Ayak drops (mid-late Phase 1 if you grind Doom)
- L1 (air weakness) — only relevant if Augury is online (Phase 2 CoX) for max prayer bonus

**Recommended Phase 1 unlock order** (as pact points come in):
1. AA (root)
2. F1 (+35% acc)
3. FA (+1% mage dmg) — direct add via I1 chain
4. I1 (air dmg per active prayer — works with Air Surge)
5. F7 (spell speed)
6. FB (+1% mage dmg) — bridge node
7. I2 (water dmg at full HP — works with Water Surge)
8. FC, FD (+1% mage dmg)
9. I3, I4 (fire/earth payloads)
10. BA, BB, BC (regen %)
11. B1 (mag boost on regen)
12. F3 (+30% regen)
13. **F8** (once Eye of Ayak drops) — enables Eye of Ayak 1-tick for big DPS jump
14. C1, C3, C4 (rune-regen payloads — assuming Mage gloves equip soon)
15. F5, F6, F9, F10 (charge → rune regen — only useful if you have a powered staff or charged wand)

By end of Phase 1, you should have ~15-20 pacts unlocked depending on point earnings. **No respec used yet.**

### Phase 2 — + Kourend (~weeks 2-4)

**Spellbook:** Still Standard only. **CoX Augury, Ancestral, Kodai unlock.** Slayer in Catacombs (single-target, no barrage).

**Big change:** Augury online → I1 air spell damage gets MUCH bigger (+7% per active prayer × ~5 prayers = +35% on Air Surge!). L1 starts mattering (prayer bonus from Augury).

**Pacts to add in Phase 2:**
- L3 (fire bounce + burn AoE — large pact, when you reach FC chain)
- L4 (earth flat dmg per def — large pact, scales with def levels)
- L1 (air weakness max-hit chance — pairs with Augury prayer bonus)
- IA, IB, IC, ID (more +1% mage damage, get to 8 stacks)
- F2, H9 (overheal cap +60% HP — sustain in CoX learning)
- CB, CC (+30% accuracy stacking with F1)
- F4, H8 (defence levels for L4 fuel)
- I5 (prayer pen)

By end of Phase 2: ~25-30 pacts unlocked. Still **no respec used.**

### Phase 3 — + Desert (Ancients UNLOCKED)

**🔄 Use Respec #1 here.** Major restructure:
1. **Tempoross** → Tome of Water for water bonuses
2. **Ancient Magicks** → Ice Barrage usable
3. **ToA** → Wardens (earth-weak, Earth Surge primary), Tumeken's Shadow eventually
4. **Giants' Foundry** + smithing
5. **Master Wand** from MTA

**Why respec now:**
- You've been adding pacts piecemeal with no overall structure — the build has accumulated some bridge waste
- L6 becomes usable (Ice Barrage → water for AoE Catacombs Slayer)
- Add F+C heal sustain (C2 + L2) for harder ToA invocations and Inferno attempts
- Drop any Phase 1 fluff that doesn't fit Option 3 final layout

**Target after Respec #1: ~33-35 of the 40 picks from Option 3 in builds.md.** You won't have all 40 yet — keep earning points.

**Add over Phase 3:**
- L6 (Ice→water) — single direct add
- Final F+C chain pieces
- The remaining sustain pacts (J8 if you path it, more overheal)
- Continue toward full Option 3 build

By end of Phase 3: ~38-40 pacts. **1 respec used.**

### Phase 4 — + Kandarin (Devil's Element, Confliction Gauntlets)

**🔄 Use Respec #2 here** (only if you're not happy with current spec).

**Big unlocks:**
- **Confliction Gauntlets** (Demonic Gorilla zenytes) → +20 mage atk, +7% mage dmg
- **Devil's Element** (Echo Thermy) → +20 mage atk, +6% dmg, **doubles all enemy elemental weaknesses**
- **Trident of the Seas** (Kraken)
- **Occult Necklace** (Thermo, 93 Slayer)

**Why respec now (optionally):**
- Devil's Element doubles your damage on weakness-tagged content. The damage curve shifts. You may want to reconsider whether overheal/sustain is still needed (you can probably brute-force more bosses with the doubled damage).
- Confliction Gauntlets passive (accuracy reroll on 1H weapons) makes Eye of Ayak even better — F8 burst becomes more reliable.
- This is when you commit to the "endgame" layout.

**Target after Respec #2:** Full Option 3 (or push toward Option 2 if you've now leaned into AoE Slayer with Culling Spree).

By end of Phase 4: 40/40 pacts. **2 respecs used.**

### Phase 5 — Endgame (T8 Flask of Fervour)

**🔄 Save Respec #3 for content-specific tuning.**

Possible uses:
- **Inferno push:** Drop AoE conversions, max sustain (heal stacks), maybe add I6 prayer regen via expensive pathing. Focus on TzKal-Zuk's water weakness with L6 Ice Barrage on Jal-* pillars.
- **Sol Heredit push:** All-DPS, no sustain (Sol mechanics don't pact-heal), max F8 + raw mage damage stacks. Sol is no-weakness so L payloads are dead — squeeze every +1% damage stat.
- **Echo boss farming:** Tune for echo content's specific mechanics.
- **Specific raid speed runs:** Drop everything not relevant to the target raid.

**Don't waste this respec.** If you don't need it, leave it.

---

## Early game tree investment — should you do melee/ranged pacts for Moons of Peril?

### TL;DR: **No. Pure mage from Day 1.**

**Why:**
1. **Blue Moon (mage variant) of Moons of Peril is killable with starter mage gear** — you don't need elite gear to clear it. Your basic mage damage stacks (FA-FD + F1 accuracy) are enough.
2. **Pact slots are precious** — every melee/ranged pact you take is a slot you're not putting toward your endgame mage build. Even with respecs, you spend time grinding points to unlock pacts you'll throw away.
3. **The melee/ranged trees don't synergize back into your mage core** — there's no shared "general damage" pact line. The G/H/J/K/M/N families are entirely separate from F/I/L (mage).
4. **Blood Moon (melee) and Eclipse (ranged) gear is irrelevant for a mage main.** Blue Moon set is the only Moons of Peril output you care about, and Blue Moon gives you mage gear (helm/body/tassets/sceptre).
5. **Your day-1 LAN party Doubleshine route already handles early progression** — you don't need to optimize early bossing.

### When would you reconsider?

- **Tekton/Vasa speed runs in CoX:** Tekton is melee-only, Vasa requires melee. If you commit to fast CoX clears, picking up some melee strength pacts (G6, G7, G+letters) could matter. But this is Phase 4+ optimization, not Day 1.
- **Inferno melee phase:** Some Inferno strats use melee for specific waves. Mage carries 99% of Inferno though.
- **Diary tasks** that require killing X with Y style. These are point earners but not worth pact slots.

**Recommendation:** Take only mage pacts for the entire league. Use respecs for mage-internal restructuring (sustain vs DPS vs spec content), not for cross-style swaps.

---

## Pact unlock cost — confirmed

**1 combat task = 1 pact unlock.** All pacts cost equal (1 point each). 40 pacts total = 40 combat tasks. The "10/30/80/200" labels on the Jagex news page are league reward points, not pact points.

**Your task budget** (filtered to your unlocked regions):
- **9 global tasks** (always available)
- **4 Varlamore + 6 Karamja + 7 Kourend + 7 Desert + 7 Kandarin = 31 regional tasks**
- **Total: exactly 40** — perfect 1:1 to fill the build

You will complete every accessible combat task to unlock all 40 pacts. The interesting question is **the order**, which is constrained by:
1. **Task accessibility** (region unlock order, gear prerequisites)
2. **Pact tree topology** (each pact must be adjacent to one already unlocked)
3. **Pact value** (high-impact pacts should unlock as early as topology allows)

---

## Task → Pact unlock mapping (40/40)

Every accessible combat task paired with the next pact in topological-value order. The build is **Option 3 v2** in [builds.md](builds.md).

**Pact tree constraint:** each unlock must be adjacent to a previously-unlocked pact. The order below is verified to respect this.

**Value priority:** F1 (+35% acc), mage damage stacks, and elemental I-payloads come first because they work immediately with Standard spellbook Surge spells. F8 unlocks at task 18 (~when Eye of Ayak should drop). L6 unlocks at task 23 (~when Desert/Ancients should be available).

### Phase 1 — Varlamore + Karamja (tasks 1-14)

| # | Task | Where / How | → Pact | Why this pact |
|---|---|---|---|---|
| 1 | Complete the Leagues Tutorial | Auto on day 1 | **AA** | Mandatory root |
| 2 | Open the Leagues Menu | Auto on day 1 | **B1** | Mage level boost on regen — foundation |
| 3 | Defeat a Hill Giant | Trivial. Karamja Volcano hill giants or any accessible region | **C1** | Air rune regen → prayer restore (cheap bridge) |
| 4 | Defeat a TzHaar | Mor Ul Rek (Karamja). Trivial after Karamja autounlocks | **CA** | +15% accuracy + bridge to F1 |
| 5 | Reach Combat Level 50 | Sulphur Naguas, Slayer training, or general combat | **F1** | **+35% accuracy — biggest single Phase 1 boost** |
| 6 | Use Protect from Melee Prayer | Need 43 Prayer (~33 real). Easy after Ralos' Rise dump | **FA** | +1% mage damage |
| 7 | Defeat a Steel Dragon on Karamja | Brimhaven Dungeon. Steel dragons | **I1** | Air spell damage per active prayer (synergy w/ Augury later) |
| 8 | 1 Hueycoatl Kill | Varlamore. Day 1 priority — DHW farming target | **IA** | +1% mage damage |
| 9 | Complete TzHaar-Ket-Rek's 3rd Challenge | Fight Caves clear (TzTok-Jad) | **C2** | Water rune regen → heal 1 |
| 10 | Equip a Fire Cape | Same fight. Equip after Fight Caves clear | **CB** | +15% accuracy stack |
| 11 | Kill 1 unique Echo Boss | Echo Amoxliatl in Varlamore. Earliest echo. **Grants 1 Reset** | **C3** | Fire rune regen → +1 dmg next spell |
| 12 | Equip Avernic Treads | Drop from Doom of Mokhaiotl Delve 4+. Hard early — better at T4 (5x drops) | **C4** | Earth rune regen → +1 def level |
| 13 | Defeat Awakened Vardorvis | Awakened mode of Vardorvis (Varlamore). Hard practice content | **CC** | +15% accuracy stack (3rd) |
| 14 | Complete Wave 12 of Fortis Colosseum | Sol Heredit prep — wave 12 only, not full Sol | **F6** | Charge regen → +1 air rune |

**End of Phase 1:** 14 pacts unlocked. You have **+50% accuracy** (CA + F1), **+2% mage damage** (FA + IA), all 4 C-rune-regen payloads, and air spell I1 boost. Powered staff F8 not yet unlocked — that's Phase 2.

### Phase 2 — + Kourend (tasks 15-22)

| # | Task | Where / How | → Pact | Why this pact |
|---|---|---|---|---|
| 15 | Open 1 Grubby Chest | Forthos Dungeon, Kourend. Easy | **F5** | Charge regen → +1 water rune (powers C2 heal chain) |
| 16 | 1 Skotizo Kill | Need dark totem from Catacombs. Kourend | **FB** | +1% mage damage + critical bridge to F-payloads |
| 17 | 150 Lizardmen Shaman Kills | Lizardman Settlement (Kourend). Slayer task — assign or unlock task | **F7** | **−2 ticks combat spell speed (Surge spells go faster!)** |
| 18 | Equip any Ancestral Piece | CoX drop — also stack the build's main goal | **F8** | **−3 ticks powered staff (Eye of Ayak → 1-tick if you have it)** |
| 19 | 25 Chambers of Xeric | CoX clears. Stack with Ancestral farming | **FC** | +1% mage damage |
| 20 | Equip a Dragon Hunter Lance | Alchemical Hydra drop. Need 95 Slayer. Stack with Brimstone Ring | **I2** | Water spell +20% dmg at 100% HP |
| 21 | Equip a piece of Radiant Oathplate | Verify drop source (likely new Yama-related armor) | **I3** | Fire spell burn boost (+2× damage from HP burn) |
| 22 | Kill 2 unique Echo Bosses | + Echo Hespori (Kourend) — easy farm. **Grants 2nd Reset** | **IB** | +1% mage damage |

**End of Phase 2:** 22 pacts unlocked. **+5% mage damage**, F7+F8 active, all 4 elemental damage payloads (I1-I4) ready, full F+C heal chain online. Augury from CoX should be feeding I1 hard at this point.

**🔄 Use Reset #1** — Optional. By now you've taken some Phase 1-flavored picks (e.g. C1 air payload unused before Augury). Restructure to drop any picks that didn't pan out and re-pick the optimal Phase 2-3 layout. Or save the reset.

### Phase 3 — + Desert (Ancients unlock) (tasks 23-29)

| # | Task | Where / How | → Pact | Why this pact |
|---|---|---|---|---|
| 23 | Cast Ice Barrage | 94 Magic. Single cast = pact. **Ancients unlock with Desert region** | **L6** | **Ice → water conversion. Ice Barrage now triggers C2/L2/I2 chain.** |
| 24 | Set a mummy ablaze | Pyramid Plunder mummies (Desert) | **IC** | +1% mage damage |
| 25 | Equip a Piece of Masori Armour | Tombs of Amascut drop. Stack with Shadow/Ward farming | **F10** | Charge regen → +1 fire rune |
| 26 | Equip a Dragon Chainbody in Kharidian Desert | Kalphite Queen drop, equip in Desert | **F9** | Charge regen → +1 earth rune |
| 27 | Equip Osmumten's Fang (or) | ToA fang drop + ornament kit drop. Both required | **FD** | +1% mage damage (final F-stack) |
| 28 | Defeat Awakened Leviathan | DT2 Leviathan awakened. Hard | **I4** | Earth spell drains enemy Defence + Magic Defence by 2 per hit |
| 29 | Equip the Venator Ring | DT2 ring (Awakened drops). Same content as Leviathan | **ID** | +1% mage damage |

**End of Phase 3:** 29 pacts unlocked. **+8% mage damage (8 stacks!)** is now MAXED. Full elemental engine: all 4 I-payloads + L6 conversion + all 4 F-rune-regen + all 4 C-payloads. Now in possession of Tumeken's Shadow, Masori, Lightbearer, Tome of Water.

### Phase 4 — + Kandarin (Devil's Element) (tasks 30-38)

| # | Task | Where / How | → Pact | Why this pact |
|---|---|---|---|---|
| 30 | Defeat a Demonic Gorilla | Kandarin. Zenytes for Confliction Gauntlets — main farm | **L3** | **Fire spell hits apply burn (max 5) + bounce to 2 nearby targets (large pact)** |
| 31 | Defeat a Mithril Dragon | Smoke Dungeon (Kandarin). Easy task | **L4** | **Earth spells +1 dmg per 12 def levels (large pact, +8 dmg w/ 99 def)** |
| 32 | Defeat the Kraken Boss 50 Times | Kraken Cove. 50 kills = grind, but Trident drops along the way | **BA** | +5% regen chance |
| 33 | Equip a Trident of the Seas | Kraken drop (1/512). Pairs with the 50 kraken kills | **BB** | +5% regen chance |
| 34 | Equip Some Zenyte Jewelry | Craft any zenyte item (e.g., from Demonic Gorilla shard) | **BC** | +5% regen chance |
| 35 | Equip an Abyssal Tentacle | Abyssal whip + Kraken tentacle. Slayer task | **F3** | +30% regen chance (regen total now 95% capped 100%) |
| 36 | Equip an Occult Necklace | Thermo drop. Need 93 Slayer | **F2** | Overheal cap +30% (sustain) |
| 37 | Kill 3 unique Echo Bosses | + Echo Thermy (Kandarin). Stack with Devil's Element farm. **Grants 3rd Reset** | **F4** | +15 Defence levels (feeds L4 earth damage!) |
| 38 | Kill 4 unique Echo Bosses | Need 4th echo — Echo Doom of Mokhaiotl (V) or Echo Sol Heredit. Verify what's in your regions | **H8** | +5 Defence levels (bridge connector) |

**End of Phase 4:** 38 pacts unlocked. The endgame build is essentially complete. You have all 8 mage damage stacks, full F+C+I+L payloads, full charge-regen chain, accuracy + spell speed + powered staff burst. Now wearing: Eye of Ayak/Shadow + Confliction Gauntlets + Devil's Element + Ancestral + Augury + Lightbearer.

**🔄 Use Reset #2 here IF you have full Virtus by now.** Switch from Option 3 → **Option 4 (Virtus DPS Variant)** in [builds.md](builds.md). Drop L2/F2/BB, add L5/L7/L8 to enable all 4 spell-type conversions. With Virtus equipped and Ancients spellbook, Barrage spells now trigger elemental payloads at +15% mage damage (vs +9% Ancestral on Surge), giving **+12% to +30% damage per cast** depending on element. If Virtus hasn't dropped yet, save Reset #2 for later — switching to Option 4 without Virtus is worse than staying on Option 3.

### Phase 5 — Endgame Inferno push (tasks 39-40)

| # | Task | Where / How | → Pact | Why this pact |
|---|---|---|---|---|
| 39 | Equip an Infernal Cape | Inferno full clear (Karamja). Hardest task in the league | **H9** | Overheal cap +30% (bringing total to +60% HP overheal) |
| 40 | Complete TKR's Special Challenge | Same Inferno content. Should drop alongside cape | **L2** | **Water spell hits bounce 60% damage as heal — large pact, the final survivability piece** |

**End of Phase 5:** 40/40 pacts unlocked. Build complete.

**🔄 Reset #3** is unspent at this point. Use it for content-specific tuning (e.g. Sol Heredit push, harder echo bosses, raid speed runs) — or leave it and feel safe knowing you have a panic-button respec available.

---

## Summary table — pact unlocks by phase

| Phase | Tasks | Pacts unlocked | Build state |
|---|---|---|---|
| **1** (Varlamore + Karamja) | 14 | AA, B1, C1, CA, F1, FA, I1, IA, C2, CB, C3, C4, CC, F6 | +50% acc, +2% dmg, foundational |
| **2** (+ Kourend) | 8 | F5, FB, F7, F8, FC, I2, I3, IB | +5% dmg, F7/F8 online, all I-payloads |
| **3** (+ Desert / Ancients) | 7 | L6, IC, F10, F9, FD, I4, ID | +8% dmg MAX, full elemental engine + L6 |
| **4** (+ Kandarin) | 9 | L3, L4, BA, BB, BC, F3, F2, F4, H8 | Large payloads + sustain begins |
| **5** (endgame) | 2 | H9, L2 | Build complete |
| **TOTAL** | **40** | **40** | **Option 3 v2** |

## Critical notes on the unlock order

1. **F8 unlocks at task 18 (mid-Phase 2)** — you need Eye of Ayak by then to use it. If you don't have Eye yet, F8 sits dormant in your build until the drop. **Push Doom of Mokhaiotl in Phase 1** so Eye is in hand by task 18.
2. **L6 unlocks at task 23 (start of Phase 3)** — exactly when Ancient Magicks comes online with the Desert pick. Cast Ice Barrage as your 23rd task to unlock L6 and immediately weaponize it.
3. **C1 unlocks at task 3 (Hill Giant)** — air rune regen payload sits unused until Phase 2 Augury. That's the cost of forcing the topology to reach F1 quickly. Acceptable.
4. **L3/L4 large payloads unlock in Phase 4** — they need defence levels (L4) and adjacency through I3/I4 (Phase 3 picks). Hold them until then.
5. **Reset #1 in Phase 2-3 transition** lets you rip out any wasted Phase 1 picks (e.g. if C1's air payload chain didn't carry as expected). Save it if the build feels right.
6. **"Radiant Oathplate" task (#21)** is unverified — confirm the drop source in-game. May need to swap with another Kourend task if it's a quest reward.
7. **"Kill 4 unique Echo Bosses" (#38)** requires a 4th echo boss in your regions. Confirmed: Echo Amoxliatl (V), Echo Hespori (Ko), Echo Thermy (Ka). The 4th likely Echo Doom of Mokhaiotl or Echo Sol Heredit — verify on launch.

---

## Quick reference: pact-task overlap from your existing plan

These tasks (from `pacts.md`) earn points AND already happen as part of your build plan:

| Task | Points | Phase |
|---|---|---|
| Equip any Ancestral piece | 200 | 2 (CoX) |
| Equip Avernic Treads | 200 | 1-3 (Doom) |
| Equip Occult Necklace | 200 | 4 (Kandarin Slayer) |
| Equip Masori piece | 200 | 3 (ToA) |
| Cast Ice Barrage | 200 | 3+ (Ancients unlock) |
| Equip Zenyte jewelry | 200 | 4 (Demonic Gorillas) |
| 1 Hueycoatl Kill | 80 | 1 |
| 25 Chambers of Xeric | 80 | 2-3 |
| 1 Demonic Gorilla | 80 | 4 |
| Wave 12 Fortis Colosseum | 200 | 1-2 |
| Awakened Vardorvis | 200 | 1-2 |
| Echo Boss x1 + Reset | 80 | 1-2 |
| Infernal Cape | 400 | 5 |

You don't need to grind pact-specific tasks. Build progression overlaps almost entirely.
