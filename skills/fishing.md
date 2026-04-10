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
| **Quest requirement** | Tai Bwo Wannai Trio (**NOT auto-completed** — must complete manually; needs 15 Agility, 30 Cooking, 5 Fishing; Jungle Potion prereq IS auto-completed) |
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

### Varlamore Fishing -- UPDATED: Has Real Spots

**Contrary to initial assumptions, Varlamore has legitimate fishing spots** added in 2024-2025 updates.

#### Fly Fishing (Lure/Bait — Trout/Salmon/Pike)
- North of Ortus Farm (near Civitas illa Fortis)
- East of Nemus Retreat (Auburn Valley, fairy ring AIS)
- South-East of Auburnvale (Auburn Valley)
- North-East of Tal Teklan (Tlati Rainforest)
- All mainland, no Sailing required
- **Trout (20 Fishing, 50 XP), Salmon (30 Fishing, 70 XP), Pike (25 Fishing, 60 XP)**

#### Net/Bait (Shrimps/Anchovies/Sardine/Herring)
- South-West of Kastori
- Northern & North-Western coast of Aldarin (island, charter ship access)

#### Big Net/Harpoon (Mackerel/Cod/Bass/Shark)
- Salvager Overlook (north of Civitas illa Fortis)
- Tal Teklan (Tlati Rainforest, 2 spots)

#### Cage/Harpoon (Lobster/Tuna/Swordfish)
- Southern coast of Mistrock, Aldarin

#### Civitas illa Fortis Park Pond (Novelty)
- Big net: house keys, caskets, jade, red topaz, junk. 7.5 XP/catch. Spot never moves.
- Only useful for house keys (Stealing Valuables), not fishing training.

**Two fishing shops in Varlamore (both fully stocked with all equipment, bait, feathers):**
- Picaria's Fishing Shop (Sunset Coast) — 1,000 bait, 1,000 feathers, all rods/nets/harpoons
- Sulisal's Superb Fishing Store (Kastori) — same inventory

**Verdict:** Varlamore's fly fishing spots let you train trout/salmon from day 1 without leaving the region. The Big Net/Harpoon spots at Salvager Overlook give access to sharks at 76+. However, for serious endgame training, Karamja (karambwan AFK), Kourend (anglerfish), and Kandarin (barbarian/monkfish) are still superior. **Use Varlamore spots for early-game progression (1-35ish) before Karamja spots become optimal.**

See [fishing-spots-research.md](../fishing-spots-research.md) for complete location reference.

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

## EH Changes Everything: All Spots Are Infinite

With Endless Harvest, **every fishing spot never depletes and auto-banks**. Your character also chases moving spots. This means the old AFK hierarchy (karambwan > everything else) is wrong. The real differentiators are:

| Factor | Why it matters |
|---|---|
| **Spot movement** | Karambwan spot is static (never moves). All other spots move periodically, but EH auto-chases. Moving spots require slightly more attention to ensure your character follows. |
| **Bait restock frequency** | No-bait methods (monkfish, sharks, harpoon fish) = true zero-input. Bait methods need periodic restocking from shop. |
| **Cooking XP per fish** | With Hotfoot auto-cooking both EH fish, higher cooking XP/fish = more passive Cooking XP |
| **Catch rate** | Higher catch rate = more fish/hr = more XP. Some fish have terrible catch rates (sharks) despite high cooking XP |

**AFK tier list (with EH):**

| Tier | Method | Why | Input needed |
|---|---|---|---|
| **S (zero input)** | Monkfish, Sharks | No bait. EH infinite + auto-bank. Just click spot and anti-logout. | Anti-logout every 20 min |
| **A (near-zero)** | Karambwan | Static spot (no movement). Needs bait but huge stacks from shop. | Anti-logout every 20 min. Restock bait occasionally |
| **A (near-zero)** | Anglerfish | Needs bait (sandworms from shop). EH chases spot. | Anti-logout every 20 min. Restock bait occasionally |
| **B (light attention)** | Trout/Salmon | Needs feathers (huge stacks from shop). EH chases spot. | Restock feathers. Spot chasing |
| **C (active)** | Barbarian | Feathers. No Hotfoot auto-cook (leaping fish). | Active for best rates. No cooking synergy |

## Progression Tree

### Prerequisites
- **Tai Bwo Wannai Trio** (Karamja): 15 Agility, 30 Cooking, 5 Fishing. NOT auto-completed. Do ASAP to unlock karambwan fishing + Tiadeche's shop. Jungle Potion (prereq) IS auto-completed.
- **Angler's Outfit** (Fishing Trawler, Kandarin): 15 Fishing for rewards. 4x minigame points = ~4 games for full set. +2.5% Fishing XP. Do when Kandarin unlocks.
- **Dragon Harpoon** (Tempoross, Desert): faster harpoon fishing. Do when Desert unlocks.
- **Diabolic Worms** (Yama boss, Kourend): massively boost anglerfish catch rate. Get from Yama when ready.

### Phase 1: Varlamore Only (Day 1, T1 5x, EH active)

| Level | Method | Location | Bait | Hotfoot cooks? | Cooking XP/fish | Notes |
|---|---|---|---|---|---|---|
| 1-15 | Net shrimp/anchovies | Kastori coast (Varlamore) | None (net) | Yes (shrimp 30, anchovy 34) | 30-34 | Buy small net from Picaria's |
| 15-20 | Bait sardine/herring | Kastori coast | Fishing bait (Picaria's, 1000 stock) | Yes (sardine 70, herring 50) | 50-70 | |
| 20-48 | **Fly fish trout/salmon** | **North of Ortus Farm** or Nemus Retreat (Varlamore) | Feathers (Picaria's, 1000 stock) | Yes (trout 70, salmon 90) | 70-90 | EH: 2x fish auto-cooked. Best early method. Available Day 1 in Varlamore! |

**Key:** You can fly fish in Varlamore from level 20 without leaving the starting region. Buy fly rod + feathers from Picaria's Fishing Shop (Sunset Coast).

### Phase 2: Karamja Unlocks (auto, still T1 5x)

| Level | Method | Location | Bait | Hotfoot cooks? | Cooking XP/fish | Notes |
|---|---|---|---|---|---|---|
| 20-48 | Fly fish trout/salmon | Shilo Village (Karamja, 4 spots) | Feathers | Yes (70/90) | 70-90 | Bank right there. But EH auto-banks anyway |
| 35-65 | Cage lobster | Musa Point or Aldarin (Varlamore) | None (cage) | Yes (120) | 120 | No bait! EH infinite spots. Good bridge to karambwan |
| 40-65 | Harpoon tuna/swordfish | Musa Point (Karamja) | None (harpoon) | Yes (tuna 100, sword 140) | 100-140 | No bait needed. Decent cooking XP |
| **65+** | **Karambwan** | **Fairy ring DKP** (Karamja) | Karambwanji (Holy Lake CKR: free, or Tiadeche's: 10 gp) | **Yes (190)** | **190** | **Complete TWW Trio first!** Static spot. Best early-game cooking XP. Stock up bait at Holy Lake (stackable, 2-20 per catch) |

**Do TWW Trio as soon as you have 15 Agility + 30 Cooking + 5 Fishing** — Cooking levels come free from Hotfoot auto-cooking during fly fishing.

### Phase 3: First Region Pick (Kourend recommended first)

| Level | Method | Location | Bait | Hotfoot cooks? | Cooking XP/fish | Notes |
|---|---|---|---|---|---|---|
| 65+ | Karambwan (WFH AFK) | Fairy ring DKP | Karambwanji (shop) | Yes (190) | 190 | Keep running this during work hours |
| **82+** | **Anglerfish** | **Port Piscarilius** (Kourend) | Sandworms (Tynan's, 90 gp, infinite) | **Yes (230)** | **230** | **Highest cooking XP in your regions!** Switch to this as primary when you hit 82 |
| 82+ | Anglerfish + diabolic worms | Port Piscarilius | Diabolic worms (Yama drops) | Yes (230) | 230 | ~2.8x catch rate over sandworms. Get worms when you farm Yama |

### Phase 4: Kandarin Unlocks

| Level | Method | Location | Bait | Hotfoot cooks? | Cooking XP/fish | Notes |
|---|---|---|---|---|---|---|
| 62+ | **Monkfish** | Piscatoris (Kandarin) | **None** | Yes (150) | 150 | **Best zero-bait method.** Highest catch rate. True zero-input AFK with EH. |
| 76+ | Shark | Fishing Guild (Kandarin) | None (harpoon) | Yes (210) | 210 | High cooking XP but terrible catch rate. Only if you want zero-bait + high cook XP/fish |
| 48+ | Barbarian fishing | Otto's Grotto (Kandarin) | Feathers | **NO** (leaping fish not cookable) | **0** | Best raw Fishing XP/hr. +Agi/Str. No cooking. Use when you only care about Fishing XP |

**Angler's Outfit:** Do Fishing Trawler (Port Khazard, Kandarin) when you unlock. ~4 games for full set at 4x minigame points.

### Phase 5: Desert Unlocks + Tempoross

| Level | Method | Location | Bait | Notes |
|---|---|---|---|---|
| 35+ | **Tempoross** | Ruins of Unkah (Desert) | N/A (minigame) | Do for: dragon harpoon, spirit flakes, tome of water, Spirit Angler outfit. Flow State 2-tick = fast clears. 8x minigame pts at T4 |

### Phase 6: Flow State (T7, 16x) — Endgame

All methods now at 2-tick. Pick based on your goal:

| Goal | Method | Where | Why |
|---|---|---|---|
| **200m Fishing XP** | Barbarian fishing | Kandarin | ~6.4M Fish XP/hr. No cooking but fastest raw XP |
| **200m Cooking XP while fishing** | Anglerfish + diabolic worms | Kourend | ~8.7M Cook XP/hr. Also ~3.0M Fish XP/hr |
| **Max combined XP/hr** | Monkfish | Kandarin | ~4.1M Fish + ~5.2M Cook = ~9.3M total XP/hr. No bait |
| **WFH AFK (minimal input)** | Monkfish OR Karambwan | Kandarin / Karamja | Monkfish: zero bait, EH infinite. Karambwan: static spot, needs bait |
| **Points + clog** | Tempoross | Desert | 2-tick minigame, fast clears, 8x pts |
| **Passive Agi/Str + Fishing** | Barbarian | Kandarin | Only option for passive combat stats. No cooking |

## When to Fish What (Quick Reference)

```
Day 1 (Varlamore)     → Fly fish trout/salmon at Ortus Farm (feathers from Picaria's)
Karamja unlocks        → Do TWW Trio → Karambwan at DKP for 190 cook XP
Kourend unlocks (82+)  → Anglerfish at Piscarilius for 230 cook XP (best in regions)
Kandarin unlocks (62+) → Monkfish at Piscatoris for zero-bait AFK
Kandarin unlocks (48+) → Barbarian fishing for max Fish XP (no cooking)
Desert unlocks (35+)   → Tempoross for dragon harpoon + clog
T7 Flow State          → Everything at 2-tick. Pick goal from table above.

WFH AFK default: Karambwan (65+) → Monkfish (62+, no bait) → Anglerfish (82+, best cook XP)
Active sessions: Anglerfish + diabolic worms (82+) → Barbarian (48+, Fish XP only)
```

---

## Summary Comparison Table (All at 99 Fishing, with EH + Hotfoot + Flow State at 16x)

All spots are infinite with EH. AFK rating is based on bait restocking + spot movement.

| Method | Fish XP/hr (16x) | Cook XP/hr (16x) | Total XP/hr | Bait | Spot Moves? | AFK Tier | Region |
|--------|------------------|-------------------|-------------|------|-------------|----------|--------|
| **Barbarian** | **~6.4M** | **0** | 6.4M | Feathers | Yes (EH chases) | C (no cooking) | Kandarin |
| **Anglerfish (diabolic)** | ~3.0M | **~8.7M** | **11.7M** | Diabolic worms (Yama) | Yes (EH chases) | A | Kourend |
| **Anglerfish (sandworm)** | ~1.7M | ~3.2M | 4.9M | Sandworms (90 gp shop) | Yes (EH chases) | A | Kourend |
| **Monkfish** | ~4.1M | ~5.2M | **9.3M** | **None** | Yes (EH chases) | **S (zero input)** | Kandarin |
| **Karambwan** | ~1.2M | ~4.6M | 5.8M | Karambwanji (10 gp shop) | **No (static)** | A | Karamja |
| **Shark** | ~0.9M | ~1.7M | 2.6M | **None** | Yes (EH chases) | **S (zero input)** | Kandarin |
| **Infernal eel** | ~1.5M | **0** | 1.5M | Bait + oily rod + ice gloves | No (static) | B | Karamja |
| **Minnow** | ~0.9M | **0** | 0.9M | None | Rotates every 15s | D (active) | Kandarin |

### Key Takeaways

- **Best total XP/hr: Anglerfish + diabolic worms (11.7M combined).** Requires Yama farming for worms.
- **Best zero-input AFK: Monkfish (9.3M combined).** No bait, no restock, EH handles everything. Click and forget.
- **Best raw Fishing XP: Barbarian (6.4M).** But zero Cooking XP — leaping fish can't be cooked.
- **Karambwan is overrated with EH.** Static spot is nice but low Fish XP (1.2M) and needs bait. Monkfish is zero-bait with 3.4x more Fishing XP.
- **Sharks are bad.** Terrible catch rate tanks both skills despite high cook XP per fish.

### Decision Framework

| Goal | Best Method | Why |
|------|-------------|-----|
| **Max total XP/hr** | Anglerfish + diabolic worms | 11.7M combined. Nothing else is close |
| **Max Fishing XP/hr** | Barbarian fishing | 6.4M Fish. No Cooking though |
| **Max Cooking XP/hr** | Anglerfish + diabolic worms | 8.7M Cook. Highest cookable fish (230 each) |
| **True zero-input AFK** | Monkfish | No bait, no restock. EH infinite. 9.3M combined |
| **Early AFK (before Kandarin)** | Karambwan | Static spot, available from Karamja. 5.8M combined |
| **Early game (pre-62)** | Fly fish trout/salmon | Available in Varlamore Day 1. Hotfoot auto-cooks |
| **Passive Agi/Str XP** | Barbarian fishing | Only method that gives combat stats. No cooking |
| **Points + clog** | Tempoross | 2-tick minigame, 8x pts at T4 |

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
