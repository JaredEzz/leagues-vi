# Fishing — Skill Guide

**Target:** 99 | **Regions:** Kandarin, Karamja, Kourend, Desert, Varlamore | **Mostly AFK**

---

## Relic Synergy: EH + Hotfoot + Flow State (The Triple Engine)

### How Each Relic Works

| Relic | Effect on Fishing |
|-------|-------------------|
| **Endless Harvest (T1)** | 2x fish per catch, auto-banked. XP granted for both fish. Infinite fishing spots (never deplete). Character chases spot as it moves. |
| **Hotfoot (T2)** | Searing boots auto-cook caught fish, granting Cooking XP. 100% cooking success rate (no burns, ever). |
| **Flow State (T7)** | All fishing spots roll at 2-tick (1.2s) instead of the standard 5-tick (3.0s). A 2.5x speed increase. |

### Critical Question: Does Hotfoot Cook BOTH Fish from EH?

**Almost certainly yes.** The evidence:

1. **EH wiki states:** "Resources gathered from Fishing are multiplied by 2. XP is granted for all additional resources gathered."
2. **Hotfoot wiki states:** "Caught fish are automatically cooked, granting XP."
3. **Theorycrafting wiki states:** "Auto-Cook makes training Cooking a 0-time skill by combining it with Fishing; however, for this to be good, you must pair it with Endless Harvest."
4. **The relics.md already models this as 2.5x Cooking XP alongside 2.5x Fishing XP.**

The phrasing "caught fish are automatically cooked" applies to ALL caught fish, including the bonus fish from EH. EH grants XP for additional resources, and Hotfoot cooks each one. The community consensus and theorycrafting pages all treat this as confirmed double cooking XP per action.

**Per catch action with all 3 relics:** You get 2 fish caught (EH), both are auto-cooked (Hotfoot), and this happens every 2 ticks (Flow State). Result:
- **Fishing XP per action = 2x base XP** (XP for both fish)
- **Cooking XP per action = 2x base cooking XP** (both fish cooked)
- **Actions per hour = 3,000** (2-tick = 1.2s per action, 3600/1.2 = 3000 theoretical max)
- **Realistic actions per hour ~2,400-2,700** (accounting for catch rate <100%, spot movement, micro-breaks)

### Effective Multipliers

| Metric | Base (5-tick, no relics) | With EH+Hotfoot+FlowState |
|--------|--------------------------|---------------------------|
| Catch attempts/hr | ~1,200 | ~3,000 |
| Fish caught/hr (at 99) | Varies by method | ~2.5x base fish/hr (2x from EH, 2.5x from speed) |
| Fishing XP/hr | Base rate | ~5x base (2x fish XP * 2.5x speed) |
| Cooking XP/hr | 0 (separate skill) | Same fish/hr * cooking XP per fish (FREE) |

---

## Fishing Methods — Complete Reference

### Tier 1: Barbarian Fishing (Kandarin) -- BEST FISHING XP/HR

| Attribute | Value |
|-----------|-------|
| **Fish** | Leaping trout (48), Leaping salmon (58), Leaping sturgeon (70) |
| **Fishing XP** | 50 / 70 / 80 per catch |
| **Bonus XP** | +5/6/7 Strength XP, +5/6/7 Agility XP per catch |
| **Cooking XP** | **CANNOT BE COOKED.** Can be gutted with knife for 10-15 Cooking XP (roe/caviar), but this is NOT auto-cooking. |
| **Location** | Otto's Grotto, Baxtorian Falls (Kandarin) |
| **Equipment** | Barbarian rod + feathers (or bait/offcuts/roe/caviar) |
| **Bait availability** | Feathers: infinite from shops. Roe/caviar self-sustaining from gutting. |
| **AFK-friendly** | No (requires dropping fish or 3-tick manipulation for best rates) |
| **Base tick rate** | 5 ticks (3-tick with manipulation in main game; Flow State makes it 2-tick) |
| **Base XP/hr (main game, 3-tick)** | ~108,000 Fishing + ~9,800 Str/Agi |

**CRITICAL: Leaping fish CANNOT be cooked by Hotfoot.** They are not cookable items. The wiki explicitly says "While it cannot be cooked, it can be gutted with a knife." Searing boots only auto-cook fish that have a normal cooking recipe. Leaping fish would NOT trigger Hotfoot's auto-cook.

**Gutting XP (knife, not auto-cook):**
| Fish | Cooking XP from gutting | Product |
|------|-------------------------|---------|
| Leaping trout | 10 XP (if roe obtained) | Roe + fish offcuts |
| Leaping salmon | 10 XP (if roe obtained) | Roe + fish offcuts |
| Leaping sturgeon | 15 XP (if caviar obtained) | Caviar + fish offcuts |

Roe/caviar chance scales with Cooking level (1/80 at level 1, guaranteed at level 80).

**League XP/hr estimate (Flow State 2-tick, EH 2x fish):**
- At 70+ Fishing (mostly leaping sturgeon): ~80 XP * 2 = 160 Fishing XP per action
- ~2,500 successful actions/hr (2-tick with catch rate factored)
- **~400,000 raw Fishing XP/hr** (before league multiplier)
- **~25,000 raw Str + Agi XP/hr** (before league multiplier)
- **Cooking XP: ~0** (leaping fish not cookable by Hotfoot)

**Verdict:** Best raw Fishing XP/hr. Also trains Str + Agi passively. But **zero Cooking XP** from Hotfoot since leaping fish aren't cookable. Choose this if you ONLY care about Fishing XP and want passive Str/Agi.

---

### Tier 2: Anglerfish (Kourend) -- BEST COOKING XP/HR

| Attribute | Value |
|-----------|-------|
| **Fish** | Raw anglerfish |
| **Fishing level** | 82 |
| **Fishing XP** | 120 per catch (79.2 with diabolic worms) |
| **Cooking level** | 84 |
| **Cooking XP** | **230 per cook** (HIGHEST in your regions) |
| **Location** | Port Piscarilius, Kourend |
| **Equipment** | Fishing rod + sandworms (or diabolic worms) |
| **Bait availability** | Sandworms: 90 gp each from Tynan's Fishing Supplies (Port Piscarilius). **Infinite stock in leagues.** Easy. |
| **Diabolic worms** | Dropped by Yama boss (Kourend). 50% chance for 1-tick-faster catch. Reduces XP to 79.2 but ~2.8x catch rate. |
| **AFK-friendly** | **Very AFK.** Spots move randomly (8-830 ticks) but EH chases the spot. |
| **Favour requirement** | None (removed Jan 2024) |
| **Base catch rate (99 Fishing)** | ~14.5% with sandworms, ~39.5% with diabolic worms |
| **Base XP/hr (main game)** | ~23,000 (sandworms), ~39,000 (diabolic worms) |

**League XP/hr estimate with sandworms (EH + Hotfoot + Flow State):**
- 2-tick attempts = ~3,000 attempts/hr
- ~14.5% catch rate at 99 = ~435 successful catches/hr
- EH 2x = ~870 fish/hr
- Fishing: 870 * 120 = **~104,400 raw Fishing XP/hr**
- Cooking: 870 * 230 = **~200,100 raw Cooking XP/hr**

**League XP/hr estimate with diabolic worms (EH + Hotfoot + Flow State):**
- 2-tick attempts = ~3,000 attempts/hr
- ~39.5% catch rate at 99 = ~1,185 successful catches/hr
- EH 2x = ~2,370 fish/hr
- Fishing: 2,370 * 79.2 = **~187,704 raw Fishing XP/hr**
- Cooking: 2,370 * 230 = **~545,100 raw Cooking XP/hr**

**Verdict:** BEST combined Cooking XP source. Anglerfish have the highest cooking XP (230) of any fish in your regions. With diabolic worms, the cooking XP/hr is absurd. Even with sandworms, 200k raw cooking XP/hr is excellent. At 16x multiplier, anglerfish with diabolic worms = ~8.7M Cooking XP/hr. **This is the single best way to train Cooking.**

---

### Tier 3: Sharks (Kandarin) -- STRONG ALL-ROUNDER

| Attribute | Value |
|-----------|-------|
| **Fish** | Raw shark |
| **Fishing level** | 76 |
| **Fishing XP** | 110 per catch |
| **Cooking level** | 80 |
| **Cooking XP** | **210 per cook** |
| **Location** | Fishing Guild (Kandarin), Catherby (Kandarin) |
| **Equipment** | Harpoon (no bait needed). Dragon harpoon from Tempoross for +speed. |
| **Bait availability** | None needed |
| **AFK-friendly** | **Very AFK.** Harpoon spots, EH infinite + auto-bank. |
| **Base catch rate** | Low. Sharks are notoriously slow. ~150-170/hr at 99 in main game. |
| **Base XP/hr (main game)** | ~18,000-20,000 |

**League XP/hr estimate (EH + Hotfoot + Flow State):**
- 2-tick attempts = ~3,000 attempts/hr
- Shark catch rate is low (~5-8% per roll at 99) -- this is why sharks are slow even with tick manipulation
- Estimated ~200-280 successful catches/hr (2-tick speed compensates for low rate)
- EH 2x = ~400-560 fish/hr
- Fishing: ~500 * 110 = **~55,000 raw Fishing XP/hr** (rough estimate)
- Cooking: ~500 * 210 = **~105,000 raw Cooking XP/hr**

**Verdict:** Decent cooking XP (210/fish), no bait needed (huge convenience). But catch rate is very low, dragging down XP/hr in both skills. Better than karambwan for cooking XP per fish but worse catch rate. Best used as a "zero-effort" AFK method when you don't want to buy bait.

---

### Tier 4: Karambwan (Karamja) -- CLASSIC AFK

| Attribute | Value |
|-----------|-------|
| **Fish** | Raw karambwan |
| **Fishing level** | 65 |
| **Fishing XP** | 50 per catch |
| **Cooking level** | 30 (requires Tai Bwo Wannai Trio quest + talking to Tinsay) |
| **Cooking XP** | **190 per cook** |
| **Location** | NE Karamja, near fairy ring DKP |
| **Equipment** | Karambwan vessel + raw karambwanji as bait |
| **Bait availability** | Raw karambwanji: catch with small net at Holy Lake (5 Fishing, stackable, 2-20 per catch based on level). Also buyable from Tiadeche's shop for 10 gp each (50 stock, infinite in leagues). Easy to stock up. |
| **AFK-friendly** | **Extremely AFK.** Spot NEVER moves. One of the most AFK fishing methods in the game. |
| **Quest requirement** | Tai Bwo Wannai Trio (auto-completed in leagues) |
| **Base catch rate** | Good. ~600/hr at 80, ~875/hr at 99 (main game with banking). |
| **Base XP/hr (main game)** | ~42,000 |

**League XP/hr estimate (EH + Hotfoot + Flow State):**
- 2-tick attempts = ~3,000 attempts/hr
- Karambwan catch rate is decent at 99
- Estimated ~600-900 successful catches/hr
- EH 2x = ~1,200-1,800 fish/hr
- Using ~1,500 fish/hr as mid estimate:
- Fishing: 1,500 * 50 = **~75,000 raw Fishing XP/hr**
- Cooking: 1,500 * 190 = **~285,000 raw Cooking XP/hr**

**Verdict:** Extremely AFK (spot never moves), good cooking XP (190/fish), and decent catch rate. The spot never moving is a huge deal for AFK play -- no need to chase spots. Bait is easy (buy from shop). Lower Fishing XP per fish (50) is the main downside. **Best pure AFK method.** Excellent for WFH hours.

---

### Tier 5: Monkfish (Kandarin)

| Attribute | Value |
|-----------|-------|
| **Fish** | Raw monkfish |
| **Fishing level** | 62 |
| **Fishing XP** | 120 per catch |
| **Cooking level** | 62 |
| **Cooking XP** | **150 per cook** |
| **Location** | Piscatoris Fishing Colony (Kandarin) |
| **Equipment** | Small fishing net (no bait) |
| **Quest requirement** | Swan Song (auto-completed in leagues) |
| **AFK-friendly** | Yes, normal fishing spots. |
| **Base catch rate (99)** | ~36% success. ~350-400 fish/hr. |
| **Base XP/hr (main game)** | ~42,000 |

**League XP/hr estimate (EH + Hotfoot + Flow State):**
- 2-tick attempts = ~3,000/hr
- ~36% catch rate at 99 = ~1,080 catches/hr
- EH 2x = ~2,160 fish/hr
- Fishing: 2,160 * 120 = **~259,200 raw Fishing XP/hr**
- Cooking: 2,160 * 150 = **~324,000 raw Cooking XP/hr**

**Verdict:** Surprisingly strong. High catch rate + 120 fishing XP/fish + no bait = very solid. Cooking XP (150/fish) is decent but lower than anglerfish (230), sharks (210), or karambwan (190). Available early (62 Fishing). Good bridging method before anglerfish (82).

---

### Tier 6: Swordfish/Tuna (Kandarin) -- 2-TICK HARPOON SPECIALIST

| Attribute | Value |
|-----------|-------|
| **Fish** | Raw swordfish (50 Fishing, 100 XP) / Raw tuna (35 Fishing, 80 XP) |
| **Cooking XP** | Swordfish: 140 / Tuna: 100 |
| **Location** | Fishing Guild (Kandarin), Catherby, Port Piscarilius (Kourend) |
| **Equipment** | Harpoon (no bait) |
| **AFK-friendly** | Moderate. Spots move. |
| **Base XP/hr (main game, 2-tick)** | ~132,800 (highest in main game) |

In main game, 2-tick swordfish harpooning at Port Piscarilius is the fastest fishing XP method. With Flow State giving automatic 2-tick, this becomes effortless. However, Flow State makes ALL methods 2-tick, so the relative advantage vanishes.

**League XP/hr estimate:** Moderate. Catch rate is decent but swordfish/tuna mix reduces average XP per fish compared to monkfish. Cooking XP per fish is lower too. Not competitive with anglerfish or monkfish for combined XP.

---

### Tier 7: Infernal Eels (Karamja) -- SPECIALTY

| Attribute | Value |
|-----------|-------|
| **Fish** | Infernal eel |
| **Fishing level** | 80 |
| **Fishing XP** | 95 per catch |
| **Cooking** | **CANNOT be cooked.** Smashed with hammer for tokkul/onyx bolt tips/lava shards. |
| **Location** | Mor Ul Rek (TzHaar city, Karamja). Requires fire cape to enter. |
| **Equipment** | Oily fishing rod + bait + ice gloves equipped |
| **AFK-friendly** | Yes, spots exist in inner city. |
| **Base XP/hr (main game)** | ~34,000 |

**Verdict:** Decent fishing XP but **zero Cooking XP** (not cookable). Useful for onyx bolt tips (crafting) and tokkul. Not a training method for Cooking. Skip for our purposes unless you need the crafting supplies.

---

### Tier 8: Minnows (Kandarin) -- FISHING XP SPECIALIST

| Attribute | Value |
|-----------|-------|
| **Fish** | Minnow (stackable) |
| **Fishing level** | 82 (cannot be boosted) |
| **Fishing XP** | 26.1 per minnow catch |
| **Cooking** | **CANNOT be cooked.** Exchange 40 minnows for 1 raw shark. |
| **Location** | Fishing Guild platform (Kandarin) |
| **Equipment** | Small fishing net + full angler's outfit required for access |
| **AFK-friendly** | No! Spots rotate every 15 seconds. Flying fish can eat minnows. Requires attention. |
| **Base XP/hr (main game)** | ~56,000 |

**EH interaction:** Minnows are stackable, so EH auto-banking works differently. The spot rotation every 15 seconds means EH's "chase the spot" may help, but the constant movement and flying fish mechanic make this less AFK than other methods.

**Verdict:** Moderate fishing XP, zero cooking XP, not AFK, requires angler outfit. The only appeal is converting minnows to sharks for food supply. With Hotfoot auto-cooking other fish, food supply isn't a concern. **Skip.**

---

### Tier 9: Dark Crabs (WILDERNESS ONLY -- LOCKED)

| Attribute | Value |
|-----------|-------|
| **Fish** | Raw dark crab |
| **Fishing level** | 85 |
| **Fishing XP** | 130 per catch |
| **Cooking level** | 90 |
| **Cooking XP** | **215 per cook** |
| **Location** | NE Wilderness coast + Resource Area. **WILDERNESS REGION LOCKED.** |
| **Bait** | Dark fishing bait |

**Verdict: UNAVAILABLE.** Wilderness is not in your regions. Dark crabs cannot be fished.

---

### Tier 10: Sacred Eels (Tirannwn -- LOCKED)

| Attribute | Value |
|-----------|-------|
| **Fish** | Sacred eel |
| **Fishing level** | 87 |
| **Fishing XP** | 105 per catch |
| **Cooking** | Cannot be cooked. Dissected with knife for Zulrah's scales (72+ Cooking, 109-127 Cooking XP). |
| **Location** | Zul-Andra (Tirannwn) |

**Verdict: UNAVAILABLE.** Tirannwn is not in your regions.

---

### Tempoross (Desert) -- MINIGAME

| Attribute | Value |
|-----------|-------|
| **Fishing level** | 35 |
| **Location** | Tempoross Cove, Ruins of Unkah (Desert) |
| **Base XP/hr (main game)** | ~70,000-95,000 Fishing XP/hr at 99 |
| **Cooking** | Optional. Can cook harpoonfish during minigame for more points but less Fishing XP. |

**Relic Interactions:**
- **Flow State:** 2-tick minigame actions = faster harpoonfish catching, faster cannon loading, faster cooking = more points, faster clears.
- **Endless Harvest:** Unclear if EH doubles harpoonfish inside Tempoross. EH description says "resources gathered from Fishing" but minigame fish may be handled differently.
- **Hotfoot:** Auto-cook may apply to harpoonfish caught during the fight, but this needs testing.

**Rewards worth getting:**
- Dragon harpoon (faster harpooning)
- Spirit flakes (+50% extra fish when regular fishing -- stacks with EH?)
- Tome of Water (boosts water spells)
- Tiny Tempor pet
- Angler's outfit recolor to Spirit Angler

**Verdict:** Do Tempoross for the rewards (dragon harpoon, tome of water, spirit flakes) and collection log, not as a primary training method. Flow State 2-tick makes runs very fast. At 8x minigame points (T4 passive), you'll get everything quickly.

---

### Fishing Trawler (Kandarin) -- OUTFIT ONLY

| Attribute | Value |
|-----------|-------|
| **Fishing level** | 15 for rewards |
| **Location** | Port Khazard (Kandarin) |
| **Fish available** | Shrimp, sardine, lobster, swordfish, shark, sea turtle (79), manta ray (81) |
| **Duration** | 5-minute games |

**Unique fish from Trawler only:**

| Fish | Fishing Level | Fishing XP | Cooking Level | Cooking XP |
|------|--------------|------------|--------------|------------|
| Sea turtle | 79 | 57 | 82 | 211.3 |
| Manta ray | 81 | 69 | 91 | 216.3 |

**Verdict:** Do Trawler ONLY for the angler's outfit (4 pieces, ~1/12 per piece per game). With 4x minigame points, this goes fast. Sea turtle and manta ray have high cooking XP (211/216) but are Trawler-only drops, not fishable at regular spots. Not a training method.

---

### Varlamore Fishing -- NEGLIGIBLE

| Attribute | Value |
|-----------|-------|
| **Location** | Civitas illa Fortis park pond |
| **Method** | Big net fishing |
| **Fish caught** | Not real fish. Broken glass, old boots, caskets, house keys. Rare jade/topaz. |
| **Fishing XP** | 7.5 per catch |
| **AFK-friendly** | Extremely AFK (spot never moves) |

**Two fishing shops in Varlamore:**
- Picaria's Fishing Shop (Sunset Coast)
- Sulisal's Superb Fishing Store (Kastori)

**Verdict:** Varlamore has NO meaningful fishing training. The Civitas pond gives house keys and trash at 7.5 XP/catch. The fishing shops are useful for buying equipment. **Do all real fishing in other regions.**

---

## Cooking XP Rankings (Highest to Lowest, In Your Regions)

| Fish | Cooking XP | Cooking Level | Region | Available? |
|------|-----------|--------------|--------|-----------|
| **Anglerfish** | **230** | 84 | Kourend | YES |
| Dark crab | 215 | 90 | Wilderness | NO (locked) |
| Manta ray | 216.3 | 91 | Kandarin (Trawler only) | YES (limited) |
| Sea turtle | 211.3 | 82 | Kandarin (Trawler only) | YES (limited) |
| **Shark** | **210** | 80 | Kandarin | YES |
| **Karambwan** | **190** | 30 | Karamja | YES |
| **Monkfish** | **150** | 62 | Kandarin | YES |
| Swordfish | 140 | 45 | Kandarin | YES |
| Lobster | 120 | 40 | Kandarin | YES |
| Tuna | 100 | 30 | Kandarin/Karamja | YES |
| Salmon | 90 | 25 | Kandarin | YES |
| Trout | 70 | 15 | Kandarin | YES |

**Winner: Anglerfish at 230 Cooking XP/cook.** This is the highest cookable fish available in your regions.

---

## Recommended Strategy

### Phase 1: Angler's Outfit (Fishing Trawler, Kandarin)
- 15 Fishing for rewards, 5-min games, 4x minigame points
- ~4 games for full outfit with league drop rates
- +2.5% Fishing XP bonus

### Phase 2: Early Fishing (1-65)
- Fly fish trout/salmon at Shilo Village or Barbarian Village (Kandarin)
- With Hotfoot: auto-cook trout (70 Cooking XP) and salmon (90 Cooking XP) as you catch them
- Fast with 5x-8x multiplier

### Phase 3: Karambwan (65-82, and AFK sessions)
- Karamja, fairy ring DKP
- Spot never moves = maximum AFK
- 190 Cooking XP per fish with Hotfoot auto-cook
- Buy karambwanji bait from Tiadeche's shop (10 gp each, infinite stock)
- **Best for WFH AFK sessions** -- click once, anti-logout every 5 min

### Phase 4: Anglerfish (82-99, and active sessions)
- Port Piscarilius, Kourend
- 230 Cooking XP per fish = highest in your regions
- Buy sandworms from Tynan's (90 gp, infinite stock)
- With diabolic worms (from Yama boss): massively increased catch rate
- **Best for maximizing both Fishing AND Cooking XP simultaneously**

### Phase 5: Tempoross (Desert, anytime after 35)
- Do for rewards: dragon harpoon, tome of water, spirit flakes, Spirit Angler outfit
- Flow State 2-tick makes runs very fast
- 8x minigame points at T4 = quick completion

### When to Barbarian Fish
- If you need Str/Agi XP and don't care about Cooking XP
- Good for early game before Hotfoot (T2) when auto-cook isn't available yet
- At T7 with Flow State: ~400k raw Fishing XP/hr is highest available
- But you get ZERO cooking XP, so Anglerfish is usually better overall

---

## Summary Comparison Table (All at 99 Fishing, with EH + Hotfoot + Flow State)

| Method | Raw Fish XP/hr | Raw Cook XP/hr | Bait Needed | AFK? | Region | Notes |
|--------|---------------|----------------|-------------|------|--------|-------|
| **Barbarian** | ~400,000 | **0** | Feathers | No | Kandarin | Best Fishing XP. +Str/Agi. No Cooking. |
| **Anglerfish (diabolic)** | ~188,000 | **~545,000** | Diabolic worms | Very | Kourend | BEST Cooking XP/hr by far. Need Yama drops. |
| **Anglerfish (sandworm)** | ~104,000 | **~200,000** | Sandworms (shop) | Very | Kourend | Great Cooking XP. Easy bait. |
| **Monkfish** | ~259,000 | ~324,000 | None | Yes | Kandarin | Strong all-rounder. No bait! |
| **Karambwan** | ~75,000 | ~285,000 | Karambwanji (shop) | ULTRA | Karamja | Best AFK. Spot never moves. |
| **Shark** | ~55,000 | ~105,000 | None | Very | Kandarin | Low catch rate hurts. No bait is nice. |
| **Infernal eel** | ~? | **0** | Bait + oily rod | Yes | Karamja | Not cookable. For supplies only. |
| **Minnow** | ~56,000* | **0** | None | No | Kandarin | Not cookable. Skip. |

*Minnow XP rates are main-game numbers; Flow State interaction with spot rotation is uncertain.

**At 16x league multiplier:**
- Anglerfish (diabolic): ~3.0M Fishing + ~8.7M Cooking XP/hr
- Anglerfish (sandworm): ~1.7M Fishing + ~3.2M Cooking XP/hr
- Monkfish: ~4.1M Fishing + ~5.2M Cooking XP/hr
- Karambwan: ~1.2M Fishing + ~4.6M Cooking XP/hr
- Barbarian: ~6.4M Fishing XP/hr + 0 Cooking

**Surprise winner for TOTAL combined XP/hr: Monkfish.** High catch rate + no bait + 120 fishing XP + 150 cooking XP = enormous combined throughput. But for pure Cooking XP, anglerfish (230 each) with diabolic worms is unmatched.

---

## Decision Framework

| Goal | Best Method |
|------|-------------|
| **Max Fishing XP/hr only** | Barbarian fishing (Kandarin) |
| **Max Cooking XP/hr** | Anglerfish with diabolic worms (Kourend) |
| **Max combined Fish+Cook XP/hr** | Monkfish (Kandarin) or Anglerfish with diabolic worms |
| **Best AFK (WFH)** | Karambwan (Karamja) -- spot never moves |
| **No bait, low effort** | Sharks or Monkfish (Kandarin) |
| **Fastest to 99 Cooking while fishing** | Anglerfish with diabolic worms, then top off if needed |
| **Early game (pre-62)** | Fly fish trout/salmon with Hotfoot auto-cook |
| **Rewards/collection log** | Tempoross (Desert) |

---

## Time to 99 Estimates (with 16x multiplier)

99 requires 13,034,431 XP.

| Method | Est. time to 99 Fishing | Est. time to 99 Cooking (passive) |
|--------|------------------------|----------------------------------|
| Barbarian (active) | **~2 hrs** | N/A (need separate Cooking) |
| Anglerfish + diabolic worms | ~4.3 hrs | **~1.5 hrs** (99 Cooking achieved during Fishing!) |
| Anglerfish + sandworms | ~7.7 hrs | ~4.1 hrs |
| Monkfish | ~3.2 hrs | ~2.5 hrs |
| Karambwan (AFK) | ~10.9 hrs | ~2.8 hrs |

**Best overall plan for 99 in both:** Fish anglerfish with diabolic worms until 99 Cooking (achieved in ~1.5 hrs of fishing), then switch to barbarian fishing for fastest 99 Fishing if desired. Or just keep anglerfish to ~4.3 hrs for both 99s simultaneously.

**Realistically:** With league multiplier ramping (5x -> 8x -> 12x -> 16x), actual times will be shorter at higher tiers. Karambwan AFK during WFH + anglerfish active sessions = both 99s in 3-5 hrs of total fishing time.
