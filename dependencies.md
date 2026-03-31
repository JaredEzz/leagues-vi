# Dependencies — What Unlocks What

*Mermaid diagrams render on GitHub. Each chain shows prerequisites → unlocks.*

---

## Mage Build Gear

```mermaid
flowchart TD
    subgraph Varlamore["Varlamore (Start)"]
        DOOM[Doom of Mokhaiotl]
        DOOM -->|delve 3+| EOA[Eye of Ayak]
        DOOM -->|delve 4+| TREADS[Avernic Treads]
        DOOM -->|delve 2+| CLOTH[Mokhaiotl Cloth]
    end

    subgraph Kourend["Kourend (1st Region)"]
        COX[Chambers of Xeric]
        COX --> ANCESTRAL[Ancestral Hat/Top/Bottom]
        COX --> KODAI_I[Kodai Insignia]
        COX --> AUGURY[Augury Prayer]
    end

    subgraph Desert["Desert (2nd Region)"]
        MTA[Mage Training Arena]
        MTA --> MASTER_WAND[Master Wand]
        TOA[Tombs of Amascut]
        TOA --> SHADOW[Tumeken's Shadow]
        TOA --> WARD[Elidinis' Ward base]
        ANCIENTS[Ancient Magicks Quest]
    end

    subgraph Kandarin["Kandarin (3rd Region)"]
        GORILLAS[Demonic Gorillas]
        GORILLAS --> ZENYTE[Zenyte Shard]
        SLAYER93[93 Slayer]
        SLAYER93 --> THERMY[Thermonuclear Smoke Devil]
        THERMY --> OCCULT[Occult Necklace]
        THERMY -->|echo orb| ECHO_THERMY[Echo Thermy]
        ECHO_THERMY --> DEVIL[Devil's Element offhand]
    end

    subgraph Crafting["Crafting Chain"]
        ZENYTE --> TORMENTED[Tormented Bracelet]
        TORMENTED --> CONFLICTION[Confliction Gauntlets]
        CLOTH --> CONFLICTION
        CRAFT83[83 Crafting] --> CONFLICTION
        SMITH70[70 Smithing] --> CONFLICTION
    end

    subgraph Kodai["Kodai Chain"]
        MASTER_WAND --> KODAI[Kodai Wand]
        KODAI_I --> KODAI
    end

    style EOA fill:#9b59b6,color:#fff
    style CONFLICTION fill:#9b59b6,color:#fff
    style KODAI fill:#9b59b6,color:#fff
    style OCCULT fill:#9b59b6,color:#fff
    style DEVIL fill:#9b59b6,color:#fff
    style TREADS fill:#9b59b6,color:#fff
    style ANCESTRAL fill:#9b59b6,color:#fff
    style AUGURY fill:#9b59b6,color:#fff
    style SHADOW fill:#9b59b6,color:#fff
    style WARD fill:#9b59b6,color:#fff
```

**Purple = final gear piece.** Mage build is complete when you have all purple nodes.

---

## Barrage Slayer Engine

```mermaid
flowchart TD
    KOUREND[Kourend Unlock] --> CATACOMBS[Catacombs of Kourend]
    DESERT[Desert Unlock] --> ANCIENTS[Ancient Magicks]

    CATACOMBS --> BARRAGE_SPOT[Barrage Location]
    ANCIENTS --> BARRAGE_SPELL[Ice Burst/Barrage]

    T6[T6: 8,000 pts] --> CULLING[Culling Spree Relic]
    CULLING --> FREE_HELM[Free Slayer Helm Effect]
    CULLING --> CHOOSE_TASK[Choose Task from 3]
    CULLING --> SUPERIOR_CHAIN[Superior Chaining 50%]

    FREE_HELM --> ANCESTRAL_HAT[Wear Ancestral Hat instead]

    BARRAGE_SPOT --> BARRAGE_SLAYER[Barrage Slayer Online]
    BARRAGE_SPELL --> BARRAGE_SLAYER
    CULLING --> BARRAGE_SLAYER

    COX_KODAI[Kodai Wand] --> BARRAGE_SLAYER

    BARRAGE_SLAYER --> MAGIC_XP[Magic XP]
    BARRAGE_SLAYER --> DEF_XP[Defence XP]
    BARRAGE_SLAYER --> SLAYER_XP[Slayer XP]
    BARRAGE_SLAYER --> ELITE_CLUES[Elite Clue Chains]

    T4[T4: 2,500 pts] --> CONNIVING[Conniving Clues]
    ELITE_CLUES --> CONNIVING
    CONNIVING --> POINTS[Massive League Points]

    style BARRAGE_SLAYER fill:#e74c3c,color:#fff
    style POINTS fill:#f39c12,color:#fff
```

**Red = core engine. Orange = points output.** Everything feeds into barrage Slayer → clue chains → points.

---

## Wintertodt + Woodcutting Chain

```mermaid
flowchart TD
    WC_TRAIN[Train WC to 51 real / 61 effective] --> DRAGON_AXE_WIELD[Can wield Dragon Axe]

    KOUREND[Kourend Unlock] --> WT_ACCESS[Wintertodt Accessible]
    FM40[40 FM real / 50 effective] --> WT_ACCESS
    RUNE_AXE[Get Rune Axe] --> WT_ACCESS

    WT_ACCESS --> WT[Do Wintertodt]

    WT -->|1/10k, 1/2k at T4| DRAGON_AXE[Dragon Axe Drop]
    WT --> CARTS[Reward Carts banked]

    DRAGON_AXE --> DRAGON_AXE_WIELD
    DRAGON_AXE_WIELD --> REDWOODS[Redwoods 80 real with Dragon Axe]

    FARM67[Farming 67 real] --> OPEN_CARTS[Open Carts for Best Seeds]
    HERB56[Herblore 56 real] --> OPEN_CARTS
    CARTS --> OPEN_CARTS

    OPEN_CARTS --> SEEDS[Tree + Herb Seeds]

    T5[T5: Nature's Accord] --> SEEDS_10X[10x Yield from Seeds]
    SEEDS --> SEEDS_10X

    style WT fill:#e67e22,color:#fff
    style OPEN_CARTS fill:#27ae60,color:#fff
    style REDWOODS fill:#27ae60,color:#fff
```

**Key:** Don't push WC past 51 real (61 effective = Dragon Axe wieldable) before Wintertodt. Bank carts, open when Farming/Herblore are high enough.

---

## Skilling Prerequisites

```mermaid
flowchart TD
    subgraph Phase1["Phase 1: Varlamore"]
        MINING[Mining: Calcified Rocks 31 real] --> SHARDS[Blessed Bone Shards]
        AGILITY[Agility: Colossal Wyrm 40 real] --> SHARDS
        HUNTER_SACKS[Hunter: Rumour Sacks] --> SHARDS
        SHARDS --> PRAYER[Prayer: Ralos' Rise 20 real]
        WINE[Buy Jugs of Wine with GP] --> PRAYER

        HUNTER36[Hunter 36 real] --> GUILD[Hunter Guild Access]
        GUILD --> RUMOURS[Hunters' Rumours]

        RC23[RC 23 real] --> SUNFIRE[Sunfire Runecrafting]

        HERB50[Herblore 50 real] --> MIXOLOGY[Mastering Mixology]
    end

    subgraph Phase2["Phase 2: + Kourend"]
        WC51[WC 51 real] --> DRAGON_W[Dragon Axe Wieldable]
        RUNE_AXE[Rune Axe] --> WT[Wintertodt]
        FM40[FM 40 real] --> WT

        FARM_GUILD[Farming Guild] --> CONTRACTS[Farming Contracts]
        CONTRACTS --> SEED_SUPPLY[Seed Supply]

        RC67[RC 67 real] --> BLOODS[Blood Runes]
    end

    subgraph Phase3["Phase 3: + Desert"]
        GEM_TRADER[Al Kharid Gem Trader] --> CRAFT_PUSH[Crafting to 73 real / 83 eff]
        GIANTS[Giants' Foundry] --> SMITH_PUSH[Smithing to 60 real / 70 eff]

        CRAFT_PUSH --> CONFLICTION_REQ[Confliction Gauntlets Craftable]
        SMITH_PUSH --> CONFLICTION_REQ
    end

    subgraph Phase4["Phase 4: + Kandarin"]
        SLAYER65[65 Slayer] --> DUST[Dust Devils barrageable]
        SLAYER80[80 Slayer] --> NECHS[Nechryaels barrageable]
        SLAYER87[87 Slayer] --> KRAKEN[Kraken: Trident]
        SLAYER93[93 Slayer] --> THERMY[Thermy: Occult + Echo]
        SLAYER95[95 Slayer] --> HYDRA[Alchemical Hydra]
    end

    style PRAYER fill:#9b59b6,color:#fff
    style MIXOLOGY fill:#9b59b6,color:#fff
    style CONFLICTION_REQ fill:#9b59b6,color:#fff
```

---

## Region + Relic Unlock Chain

```mermaid
flowchart LR
    START[Start: Varlamore] --> T1[T1: Abundance 0 pts]
    T1 --> TASKS90[90 Tasks]
    TASKS90 --> R1[1st Region: Kourend + Karamja auto]
    T1 --> T2[T2: Hotfoot 750 pts]
    T2 --> T3[T3: Evil Eye 1,500 pts]

    T3 --> TASKS200[200 Tasks]
    TASKS200 --> R2[2nd Region: Desert]
    T3 --> T4[T4: Conniving Clues 2,500 pts]
    T4 --> T5[T5: Nature's Accord 5,000 pts]

    T5 --> TASKS400[400 Tasks]
    TASKS400 --> R3[3rd Region: Kandarin]
    T5 --> T6[T6: Culling Spree 8,000 pts]
    T6 --> T7[T7: 16x Multiplier 16,000 pts]
    T7 --> T8[T8: Flask of Fervour 25,000 pts]

    style R1 fill:#3498db,color:#fff
    style R2 fill:#3498db,color:#fff
    style R3 fill:#3498db,color:#fff
    style T6 fill:#e74c3c,color:#fff
    style T8 fill:#e74c3c,color:#fff
```

---

## Critical Path Summary

The longest dependency chain (what takes the most sequential steps):

```
Kandarin unlock (400 tasks)
  → 93 Slayer (barrage Slayer to level fast)
    → Culling Spree (T6, choose Smoke Devil tasks)
      → Thermonuclear Smoke Devil kills
        → Occult Necklace
        → Echo orb
          → Echo Thermy
            → Devil's Element (BIS offhand)
```

And for Confliction Gauntlets:
```
Kandarin unlock (400 tasks)
  → Demonic Gorillas
    → Zenyte shard
      → Tormented Bracelet (need 93 Magic to enchant, or 83 with Abundance)
        + Mokhaiotl Cloth (Doom of Mokhaiotl, can farm earlier)
        + 83 Crafting (73 real, gem trader in Desert)
        + 70 Smithing (60 real, Giants' Foundry in Desert)
          → Confliction Gauntlets
```

**Bottleneck:** Kandarin is the 3rd unlock (~400 tasks). Everything that needs Kandarin (Confliction, Occult, Devil's Element, chinchompas) is gated behind this. Focus on task completions in Phase 1-3 to reach 400 tasks as fast as possible.

**Second bottleneck:** 93 Slayer for Occult + Echo Thermy. Barrage Slayer with Culling Spree is the fastest path, but that requires Desert (Ancients) + Kourend (Catacombs) + T6 (Culling Spree, 8,000 pts). Start melee Slayer early to build toward this.

---

## Do-Before List

Quick reference: what to do before each key activity.

| Activity | Do First |
|----------|----------|
| **Wintertodt** | WC 51 real (Dragon Axe wieldable), FM 40 real, get a rune axe, unlock Kourend |
| **Open WT Carts** | Farming 67+ real, Herblore 56+ real (for best seeds/herbs) |
| **Redwoods** | WC 80 real. Ideally have Dragon Axe from WT |
| **Barrage Slayer** | Kourend + Desert unlocked, Culling Spree (T6), Kodai Wand (CoX + MTA) |
| **Doom hard-farm** | T4 (5x drops). Before that, just do KC tasks |
| **CoX** | Decent combat stats (~70s-80s). Evil Eye (T3) for teleport |
| **ToA** | Desert unlock. Evil Eye for teleport. Decent gear |
| **Giants' Foundry** | Desert unlock. Bank ores/bars beforehand from Mining + WT carts |
| **Confliction Gauntlets** | Kandarin unlock + zenyte + Mokhaiotl Cloth + 73 real Crafting + 60 real Smithing |
| **Occult Necklace** | Kandarin unlock + 93 Slayer |
| **Devil's Element** | Kandarin unlock + 93 Slayer + Thermy echo orb |
| **Farming contracts** | Kourend unlock (start ASAP — compounds over time) |
| **Mixology** | Herblore 50 real (in Varlamore, no region needed) |
| **Prayer dump** | Bank shards from Mining + Agility + Hunter first. Buy wine with GP |
