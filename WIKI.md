# Malevolent Meat Master v0.9.90: the wiki

Everything in the game, from the game's own data (written by the build you can download, so the numbers match it). The same pages are in the game: press **F1**, or **GUIDE** in the Smokehouse or the Esc menu. [Download the game](https://github.com/LichIndex/MMM-Malevolent-Meat-Master#readme).

- [Start here](#start-here)
- [Runs, threat and drops](#runs-threat-and-drops)
- [The flamethrower](#the-flamethrower)
- [Parts and lanes](#parts-and-lanes)
- [Sets](#sets)
- [Exotic parts](#exotic-parts)
- [Fuels and stills](#fuels-and-stills)
- [Fuel reactions](#fuel-reactions)
- [Mutants](#mutants)
- [Destinations and factions](#destinations-and-factions)
- [Meat, sauce and selling](#meat-sauce-and-selling)
- [The Smokehouse](#the-smokehouse)
- [Cats and the crew](#cats-and-the-crew)
- [Automation: the 8-Ball and the hands](#automation-the-8-ball-and-the-hands)
- [Endgame](#endgame)
- [A New Truck (the prestige)](#a-new-truck-the-prestige)
- [The Showroom (tested builds)](#the-showroom-tested-builds)
- [Saves, settings and logs](#saves-settings-and-logs)

## Start here

You're a pig with a flamethrower. You fight mutants for their meat, get out alive, turn the meat into sauced, smoked barbecue and sell it from your food truck. The money and materials you bring home build a better flamethrower, so you can go deeper, where the meat is worth more.

### The loop
1. **Fight.** Pick a destination on the **Map** tab and press **FIGHT**. Hold the left mouse button to burn: every drop of fuel that lands sets a burn on the mutant, and the burns pile up. The threat climbs a level every 30 s, and so does what they drop.
2. **Get out.** Press **E** to start the truck. Its engine takes 30 s to catch; survive until then and everything comes home. Die and the run's meat and parts are lost, with part of its materials.
3. **Sauce.** In **Production > Kitchen**, brew a sauce from a recipe and ingredients and put it on your raw meat. Raw meat spoils over real time; sauced meat doesn't.
4. **Smoke.** The smoker on the truck smokes sauced meat: a full load in 90 s of a run, and at half that speed between runs, even with the game closed.
5. **Sell.** The truck's counter sells cooked meat in real time (also while you fight or the game is closed) to whoever's turf it's parked on. A sauce that suits their taste pays more. This is where **Energy Sprinkles** (◆, the money) come from.
6. **Build.** Fuel stills, better parts at the Workbench, sets, yard upgrades. Then push deeper.

### Controls

| Action | Key |
|---|---|
| Aim | Mouse (or W/S, arrow keys) |
| Burn (hold) | Left mouse or Space |
| Next tank / pick a tank | Q or the mouse wheel / 1 to 4 |
| Start the truck | E |
| Shoggoth Remote Control (it plays for you) | R |
| Flamethrower sheet | Tab or C |
| This guide | F1 |
| Pause / menu | Esc or P |
| Fullscreen | F11 or Alt+Enter |

### What you collect

| Resource | Where it comes from | What it's for |
|---|---|---|
| Energy Sprinkles (◆) | Selling smoked meat; Persian and Tabby cats | Nearly everything |
| Scrap Metal | Mutants with armor; scrapping parts; the Salvage Yard | Chassis, pumps, shrouds, the truck |
| Mutant Bits | Mutants with only health; the Salvage Yard | Fuel lines, nozzles, the kitchen |
| Chemicals | Mutants with shields; the Salvage Yard | Igniters, filters, stills |
| Sauce ingredients | Mutants (12% a kill), cats, faction shops | Sauces |
| Favor (a faction's) | Fighting on its turf; its contracts; its map's boss; breaking down its set's pieces; Siamese and Blue cats | Its exotic blueprints, its set's blueprints, affix and behavior re-rolls while parked there |
| Harry Berries | Selling the truck (a New Truck) | The Needless Complexity Emporium |

**Three currencies** (v0.9.26): Energy Sprinkles, favor and Harry Berries. Blueprint Shards, Mutagen and Flux are gone: what paid Shards (set blueprints, the third re-roll rung) costs favor with the place's or the set's faction, and what paid them (set pieces broken down, cats) pays that favor; Mutagen is **Chemicals** (10 a Mutagen: elites past threat 15 drop them, scrapping Mutated and Malevolent parts gives them, behaviors and tempers cost them); a contract's or a boss's Flux is **favor** (20 a Flux). An old save's Shards, Mutagen and Flux turn into favor and Chemicals as it loads.

### A first hour
- **The tabs open in order with what you've done** (v0.9.20): LOADOUT and MAP from the start; **CRAFT** at your first run that gets out (v0.9.89: it waited for a salvaged part, and since v0.9.88 nothing drops one, so a new game's CRAFT tab stayed shut until run 12 or threat 8); **PRODUCTION** at your first raw meat; **REFINE** at best threat 6, where tier 2 opens, or at your first Mutated part; **CREW** at your first hire; the **SHOWROOM** at threat 6; **8-BALL** when you hire the Magic 8-Ball (the Map tab's line). A line beside the tabs says what opens the next, with the note below it in its tooltip. A tab once open stays open, a link into a tab opens it, and a game with 12 runs or best threat 8 has them all (an older save loses nothing).
- Fight at the **Smokehouse Outskirts**, start the truck while you're still comfortable, and bring the meat home. A short run that gets out beats a long one that doesn't.
- Brew **Basic Rub** or **Backyard Glaze** with whatever ingredients you have, sauce the meat, and let the smoker and counter turn it into ◆.
- Build better parts in the **Craft** tab, from ◆ and what the mutants drop, and buy **armor** in the Loadout tab. Scrap a part you have outgrown: half of what went into it comes back.
- Reach threat 3 anywhere to open the **Rust Flats**; threat 6 opens tier 2 parts.
- Watch the heat bar. At 100% you have a choice (v0.9.25): hold on and the gun **redlines**, firing at half flow while the heat burns the pig (1 armor a second, then HP), or let go and it locks out for 2 s while it vents. A hold from cold lasts about 15 s.

## Runs, threat and drops

### Threat
- The threat rises one level every **30 s**. Each destination grows mutants' health, armor and shields by its own rate a level (see Destinations), and on top of that every pool toughens ×1.19 a level up to threat 11 and ×1.1 a level after it.
- **The waves** (v0.9.63). Mutants come in waves with a lull between: 10 waves a minute, 1 mutant a wave at threat 0 and one more every 2 threat levels, up to 4 arriving together. Never more than 20 ordinary mutants are alive at once (a wave waits for room). They walk 2% faster a level (up to ×1.6).
- **Fewer, tougher mutants.** A run gets harder because each mutant is tougher, not because more come: every pool gains 18% of itself a threat level for the first 12 levels (×3.16 by threat 12), on top of the growth above. The horn's wave is the one big crowd: 8 at once.
- **Bites.** A mutant that reaches the truck stands there (it can still be burnt) and waits its turn: mutants bite one at a time, a heart each, never sooner than **1.5 s** after the last one. An ordinary mutant is spent by its bite; a boss stays and takes its turn again. A mutant stands 0.5 s at the truck before its first bite.
- Meat is worth **+45% of its base value per threat level**, so staying longer pays, until it doesn't.
- Your best threat anywhere opens part tiers: T2 at 6, T3 at 12, T4 at 16, and T5 (crafted only; v0.9.28) at 24.

### Materials and recipes (v0.9.88)
**Parts are built, materials are hunted.** No part drops any more, from anything: not from mutants, elites or bosses, not from a cat's trip, not from a stray at the counter. A run brings home **named materials**, and the Workbench builds every part from them. The loot filter, ONLY UPGRADES, the drop queue, the stash cap, a place's featured slot and its pick went with dropped parts (v0.9.89: out of the menus and the rules).

| Material | Drops from |
|---|---|
| Creeper Sinew | Creepers, anywhere: 1 kill in 20 |
| Drudge Knuckle | Drudges, anywhere: 1 kill in 20 |
| Leaker Gland | Leakers, anywhere: 1 kill in 15 |
| Platehide Scute | Platehides, anywhere: 1 kill in 15 |
| Behemoth Tusk | Behemoths, anywhere: 1 kill in 5 |
| A place's material (16, below) | That place's elites: 0.6 a threat level of the run, carried by the next elite you kill |
| A boss's trophy (16, below) | That place's boss, every time. Bosses come every 5 threat levels from threat 5 |
| Black Ichor | Any boss: 1 in 4, 1 in 2 from threat 30, always from threat 40 |

- **Depth gives more of a drop, never a better one:** from threat 30 every named material drops in twos, from threat 40 in threes.
- **They are banked like exotic materials:** a death loses the same share, and what multiplies your drops multiplies them. There is no cap on what the truck holds. The result screen lists them (MATERIALS); the feed names only trophies and Black Ichor.

| Place | Theme | Its elites' material | Its boss's trophy |
|---|---|---|---|
| Smokehouse Outskirts | Balanced | Smokehouse Ash | Gristle's Jawbone |
| The Junk Bazaar | Balanced | Bazaar Trinket | The King's Purse |
| Dead Drive-In | Balanced | Scorched Reel | The Second Head |
| The Food Court | Balanced | Mall Token | The Bottomless Stomach |
| Rust Flats | Armor | Baron's Rivet | Colossus Rivet |
| Scrap Mountain | Armor | Prayer Gear | Titan Bolt |
| Tank Graveyard | Armor | Tread Link | The Hog's Snout Plate |
| Smelter Pits | Armor | Pit Clinker | Golem Core |
| Glow Crater | Shield | Crater Glass | The Glowing Femur |
| Reactor Row | Shield | Reactor Rod | The Choirmaster's Baton |
| The Neon Strip | Shield | Neon Tube | The Velvet Rope |
| Static Fields | Shield | Fulgurite | The Storm Rod |
| Sewer Delta | Health | Sewer Pearl | The Matriarch's Crown |
| The Flesh Farms | Health | Rancher's Brand | The Prize Ribbon |
| Fungal Bog | Health | Bog Cap | The Mother Spore |
| Bloat Marsh | Health | Bloat Bladder | The Bloat Cork |

**What things ask for** (on top of the Energy Sprinkles and the Scrap, Bits or Chemicals they cost before):
- **A lane part** is built at T1 and raised a tier at a time (**BUILD T2 FROM THIS PART** and so on, in Refine): the old part is used up and its affixes, mutation, Temper and mark carry over. T1 and T2 ask for nothing named; the step to T3 asks 3 of the slot's mutant material, to T4 6, to T5 9. By slot: Fuel Line: Creeper Sinew; Nozzle: Drudge Knuckle; Tank Chassis: Behemoth Tusk; Pump: Leaker Gland; Igniter: Drudge Knuckle; Filter: Creeper Sinew; Shroud & Grip: Platehide Scute.
- **A set piece** is built at T1 too, from its set's home (favor still buys the blueprint), and raised the same way. Each step asks: T1: 1 of the home's material; T2: 2 of the home's material; T3: 3 of the home's material, 9 of the slot's mutant material; T4: 6 of the home's material, 18 of the slot's mutant material; T5: 3 of its boss's trophy, 9 of the home's material, 27 of the slot's mutant material.
- **A keystone** is built: 5 trophies and 15 place materials of its theme (any mix), 45 of its slot's mutant material and 1 Black Ichor.
- **Exotic parts** as before: the blueprint for favor, the fuel's exotic material to craft.
- **A mutation** is chosen from the list (it was a roll) and asks 9 of its mutant material beside the Chemicals: Creeper Sinew for Opportunist, Steady Aim, Deadeye; Drudge Knuckle for Dregs, Primed, Pent-Up; Leaker Gland for Toxic, Volatile, Spreading, Chilling; Platehide Scute for Anvil, Marked, Backfire; Behemoth Tusk for Culling, Overkill, Fixated.
- **A boss's mark** (Refine, one a lane part or set piece): 1 of that boss's trophy, 3 of its place's material and 9 of the slot's mutant material. It adds +10% to the whole kit against that boss's theme's pool (Armor, Shield or Health), or +4% against all three for a Balanced place's boss. Marks on different parts add up.
- **A greater roll** is set into one affix of a part for 1 Black Ichor (Refine).
- **Scrapping** a part gives back half of the named materials that went into it, every step to its tier.
- **Every lane can be built from the first day.**

- **A build's bill of materials.** A Showroom ad or a build on the 8-Ball's list knows what it still lacks and where each thing drops. Its plan lists the materials, the scarcest first, and the 8-Ball flies where the first one drops; when the materials are in, the hands build the piece (before and after every run, or CRAFT WHAT I CAN).
- **Where to look** (v0.9.89). **The line under the FIGHT button** says where the 8-Ball flies next and what for, as RUST FLATS · 12 BARON'S RIVET FOR THE OVEN MITTS FUEL LINE (with the 8-Ball off: where it would fly). **The Map** puts a green number on every place where something MY BUILD still lacks drops (a place's own material and trophy, and a theme's mix at every place of the theme; a mutant's material drops anywhere, so it marks none), with the list in the pin's tooltip; a place's panel shows what it drops, what you hold of it and what your builds need from there. **CRAFT > MATERIALS** lists every material: how many the truck holds, where it drops, and which builds on the list ask for it (ONLY WHAT MY BUILDS LACK shortens it). **CRAFT > KEYSTONES** lists every keystone with its recipe, what you hold toward it, and BUILD. **The result screen** says how far a run's materials bring MY BUILD.
- **A keystone by name:** the 8-Ball's **A KEYSTONE** instruction (8-BALL > INSTRUCTIONS) flies for what that keystone's recipe lacks, the scarcest first, and builds it when the materials are in. Or build one by hand on CRAFT > KEYSTONES.
- **The cats bring materials too:** a trip brings the place's material and its mutants' by the hour (The crew), and a stray's gift can be a material (The cat counter).

### What mutants drop

| Drop | Chance a kill | Notes |
|---|---|---|
| Raw meat | 45% (elites always, 2 cuts) | Each mutant has its own cut. Worth its base × (1 + 0.45 × threat level). |
| Materials | 30% for each kind it carries, × the destination's bias (elites always, ×3) | Armor → Scrap Metal, shields → Chemicals, health only → Mutant Bits. 1 each, +1 every 6 threat levels. |
| Sauce ingredients | 12% (elites twice that) | From the destination's own mix. |
| Its kind's material | 1 kill in 20 (Creeper Sinew), 20 (Drudge Knuckle), 15 (Leaker Gland), 15 (Platehide Scute), 5 (Behemoth Tusk) | v0.9.88: no part drops. See Materials and recipes above. |
| The place's material | Elites: 0.6 a threat level of the run | The next elite you kill carries it, so a run's count does not hang on luck. |
| The boss's trophy, Black Ichor | Every boss its trophy; Black Ichor 1 boss in 4 (in 2 from threat 30, always from 40) | Both are named on the feed, with a sound. |
| Elite Chemicals | Elites past threat 15: 12% (10 a drop) |  |
| Still blueprint | Reach the threat shown on the Map at that destination, then get out | A new fuel (see Fuels). |

- Since mutants come fewer and tougher, each ordinary one's chances above count for the crowd it stands in for, so a minute at a threat level pays what it did before v0.9.63's waves (×3.9 at threat 0, ×4.7 at threat 6, ×19.9 from threat 12). At most 40% of a wave are elites; past that each elite carries the loot of the ones that could not come.
- **No part drops** (v0.9.88): every part is built (Starting out > Materials and recipes). Meat, Scrap, Bits, Chemicals, ingredients and exotic materials drop as they did.

### Elites
- 1% chance a spawn, +0.2% a threat level. They have ×3 the pools and an ELITE tag.
- **Waves are announced** (v0.9.25): 3 s before a wave comes, the right edge of the screen says what is in it (shielded in blue, armored in orange, flesh in pink) and, when another tank you carry does more to it, which to swap to. The swap is the read: a fuel on the wrong pool is **x0.25** (Lard, Napalm and Fryer Oil on shields or armor, Thermite on shields, Ion Gel on armor; they were x0.4 to x0.6), Lard is x1.2 against flesh (was x1), and Hooch and Rad Syrup are the generalists.
- They always drop 2 cuts and triple materials, and the place's material on a credit of 0.6 a threat level (v0.9.88; they dropped a part before).

### Start threat
- On the Map, **START THREAT** lets a run begin at a higher threat, skipping the easy opening waves (and their drops). It reaches up to your best threat at that destination minus 3 (v0.9.25: was 7), and a dial start opens with a **warm-up wave**: for its first 30 s every kill pays ×2 meat. The smoker still needs 90 s of survival from the start.
- **A mutator a run** (v0.9.25): from best threat 10 at a place, the Map offers one mutator of your choice for the run (Armored Season, Elite Pack, Heat Wave, Static Front or Swarm; see Infested runs) for **+25% drops and meat**. It stays picked until you change it; the Infested rule past 21 adds its own on top.

### Getting out, and dying
- **E** starts the truck under you. Its engine takes 30 s to catch; the fight (and the threat) goes on until it does, then it drives you home. Survive and everything comes home.
- **The horn** (v0.9.25): 10 s before the truck comes it sounds, calling a dense wave (×3 a wave's worth), and until the truck arrives every kill pays **×3 meat**: the last seconds of a run are all in. Press **E again** before the horn for a **quiet exit**: no horn, no wave, plain meat. The Shoggoth's runs are loud, except a truck it starts for a hurt pig, which goes quietly.
- The result screen sums the run up: the meat, the materials by name, and under them **how far they bring MY BUILD** (v0.9.89): a line for each material its recipes ask for that the run brought, as BARON'S RIVET +9 (21 OF 98), and how many pieces can be built or raised now. **Enter**, **Space** or **E** goes back to the Smokehouse.
- **If you die** (or abandon the run): the raw meat, fried cuts and any blueprint are lost, and you lose 10% + 5% per threat level (up to 75%) of the run's materials (the named ones too), ingredients and elite Chemicals. The smoker's load comes out overcooked (worth ×0.6).

### Health and armor
- The pig has **10 HP**. A mutant that reaches you does 1 damage and is gone.
- **Armor** (Loadout tab) is a pool of extra hit points that takes hits first and refills at its own rate once you've gone 2 s without a hit.

| Armor | Pool | Refill | Cost |  |
|---|---|---|---|---|
| Bare Bristles | 0 | 0/s | - | Just a pig and his apron. |
| Bottlecap Poncho | 2 | 2/s | ◆180 | Jingles. Recovers fast. |
| Hubcap Vest | 4 | 1/s | ◆420 | Four hubcaps and a prayer. |
| Tire-Rubber Plate | 7 | 0.45/s | ◆950 | Thick, slow to patch. |
| Fridge-Door Cuirass | 10 | 0.2/s | ◆2,200 | The maximum. Takes forever to re-seat. |

### Shoggoth Remote Control
- Press **R** (or the Shoggoth button under the top-left panel of a run) and the Shoggoth drives: it aims, burns, vents before the heat warning, swaps tanks and starts the truck. Press R again to take over. It's the same pilot that tests every build.
- **Its fee:** it eats 1 cut of meat in 5 of what drops while it drives. Nothing else.
- **v0.9.73, its truck calls gone over** (lab pilot0973, about 4,400 runs: every kit flown with no truck and the truck calls replayed over those runs, then flown for real on other seeds). AUTO used to start the truck a couple of levels under what the sheet said the kit holds, and the sheet is ten levels low for a finished build: a T5 build that holds threat 32 was taken home at 18 with 7% of the meat it could have had. Now: **It remembers how fast each build burns a boss** (in the build's own terms: each pool over the best fuel it carries for it) and leaves a boss fight it would need more than 60% of the pig's remaining time to win; a boss's pools differ two hundredfold from one boss to the next and most are barely dented when the choice has to be made, so the fight in front of it says little. **It leaves when the crowd has the pig 3 hearts down** with no boss about (your number): on the one bite clock a full pig lasts about as long as the truck takes, so 5 HP left is too late. **AUTO stays while it is winning**: it has no threat of its own once the build has beaten a boss. A build it knows nothing of keeps the sheet's estimate until it beats a boss (a run that starts deep stays past its first boss to find out). **After a death** it leaves 1.5 levels under where it died, there, with that build, for two runs. On seeds the rules were not tuned on, the old calls brought home 4,800 of meat value a run and the new ones 29,500 with a build it has never driven and 31,300 once it knows the build; it got home from 99 and 97 runs in 100 (it was 100: it left long before anything could go wrong). **v0.9.90: it remembers by build**, which is its fuels, its sets (two pieces on or more) and its keystone. Another set piece, a tier, a mutation or the exotic is the same build, and a build with its keystone newly on starts from what the Shoggoth knew of it without. It was the exact kit: each new piece made a build it knew nothing of, and in a test career one new part sent the truck back to leaving at threat 4, where the next 84 runs killed no boss.
- **v0.9.43, its logic gone over** (2,900 lab runs of the same builds with one habit changed at a time). It no longer twitches between two knots of mutants that score alike (it changed its mind 7 times a second; now 2). In a panic it pushes the gun past the heat warning only when your kit gets more fuel out that way: a cool, fast-venting gun used to sit pinned at 100% heat at half flow, burning its own armor, with a boss at the truck. **It starts the truck for a boss it can't stop:** it watches how fast the boss is going down, and if the boss will outlast the pig it leaves while the truck (30 s) can still make it, quietly. And hurt means hurt: a hurt setting at or above the pig's full health no longer starts the truck in the first second.
- **v0.9.64, gone over again after the waves rework** (about 2,600 lab runs). **It plays fuel reactions now**: with two or more tanks it swaps to the tank that would set a reaction off on the mutants in reach (ones burning with another fuel), at most every 2 s. It used to swap only when a tank ran dry or another was half again better, so a plain two-tank kit saw 15 reactions a minute; now 43, and it holds about 0.3 threat more. **It leaves for a lost boss fight sooner** (14 s of slack, it was 4): mutants at the truck bite on the same clock before the boss gets there, and the old slack got only 39 of 48 test runs home; the new one got all 48, with a third more meat a minute. Its other habits were measured under the new waves and left as they were.
- On the 8-BALL tab (RUNS): **ON/OFF** (your runs start with it driving; the 8-Ball's always do) and **when it starts the truck**: AUTO (2 threat levels under what your kit should hold there), only when hurt, or at a threat you pick. **v0.9.63: four more conditions, each switched on or off** (there, and on the TRUCK CALL button beside the Shoggoth's in a fight); any one that is on starts the truck: the pig is hurt at all; a number of HP or fewer remain (- and + set it; 5 as shipped); a number of armor hearts or fewer remain; a boss it cannot stop in time.

### The Magic 8-Ball
- It runs the pig for you, one Shoggoth run after another, working a list of goals: see **Automation: the 8-Ball and the hands**. Its settings live on the 8-BALL tab; the Map tab has one line saying what it does next. **B** switches it on and off anywhere.

## The flamethrower

### How fire hurts
- Every unit of fuel that lands adds a **burn stack** to the mutant. A stack deals the fuel's damage every 0.25 s until it runs out: 3 s × the fuel's burn × your burn-duration bonuses. Stacks never cap, so keep the flame on a crowd and they pile up.
- Damage eats **shields first, then armor, then health**. Each fuel has its own multiplier against each (see Fuels): a fuel weak against armor barely scratches a Platehide until something else strips it.
- **Peak DPS** (the Loadout and Tab sheets show it) = flow × burn duration × stack damage / 0.25 s: what the gun does once every unit is landing.

### The seven slots

| Slot | What it does | T1 | T2 | T3 | T4 | T5 |
|---|---|---|---|---|---|---|
| Fuel Line | Flow: fuel units a second (more stacks, more heat) | 12 flow/s | 18 flow/s | 27 flow/s | 40 flow/s | 60 flow/s |
| Nozzle | Cone width and range | 40° cone, 380 range | 42° cone, 395 range | 44° cone, 410 range | 46° cone, 425 range | 48° cone, 440 range |
| Tank Chassis | Tank mounts (how many fuels you carry) and every tank's capacity | 1 tank mount, +30% capacity | 2 tank mounts, +60% capacity | 2 tank mounts, +100% capacity | 3 tank mounts, +160% capacity | 3 tank mounts, +240% capacity |
| Pump | Pressure: more flow | +12% flow | +18% flow | +25% flow | +35% flow | +55% flow |
| Igniter | Burn duration | +15% burn duration | +20% burn duration | +28% burn duration | +38% burn duration | +60% burn duration |
| Filter | Stack damage | +12% stack damage | +18% stack damage | +24% stack damage | +32% stack damage | +52% stack damage |
| Shroud & Grip | Heat cap and cooling | 130 heat cap, cools 32/s | 150 heat cap, cools 36/s | 170 heat cap, cools 42/s | 200 heat cap, cools 50/s | 260 heat cap, cools 70/s |

These are the tier baselines (Scavenged quality, ×1, before the lane). Quality multiplies the main stat (Junk ×1 up to Malevolent ×1), and the lane reshapes it (see Parts).

### Heat
- Firing heats the gun; the shroud sets how much heat it holds and how fast it cools. Cooling starts 0.5 s after you let go.
- At **80%** the gun hisses and flow drops to ×0.7. At **100%** it **locks out** (v0.9.9): no firing for 2 s while it vents to 0. It doesn't hurt the pig any more. Fever Grip doubles the lockout.
- **Nobody holds the trigger forever** (v0.9.9). Firing heats the gun at least 1/15 of its heat cap a second, so a hold from cold reaches 100% within 15 s whatever the build. Heat cuts (affixes, sets, exotics, a cold fuel) stack to at most 70% less heat. The Loadout and the flamethrower sheet (Tab) show how long your gun holds fire.
- **Hard caps** (v0.9.21). Every multiplier has a ceiling for the total from every source (parts, sets, keystones, tempers, feasts and the Emporium): flow +150%, stack damage +350%, each conditional stack line (hot, far, close, elites) +100%, burn duration +200%, tank capacity +300%, fuel regen +300%, cooling +150%, heat cap +100%, range 2x the nozzle's own, a cone 150 degrees (a ring nozzle is its own thing), swap time never under 0.25 s, and the economy's multipliers (meat value, counter price, reputation, drops, Shards, hauls) x3, with Flux from one contract or boss at most 10. A stat sitting on its cap says **CAPPED** on the flamethrower sheet and the Loadout tab: more of it from any source does nothing, like the heat floor.
- Heat a unit = the fuel's heat × 0.4 × (1 + 15% for each tank past the first) × your heat modifiers × 2 × (30 / flow)^0.5. So heat a second grows with the square root of flow: a typical kit overheats after 5 to 8 s of solid fire at any tier.

### Fuel and tanks
- Each mounted tank holds one fuel. A tank holds 120 units, +25% per tank level of its still, then the chassis (T1 +30% up to T4 +160% and T5 +240%, × its quality and temper; v0.9.7, in place of the old tank mods) and bonuses.
- It refills at 5 units/s, +1.5 per still level. The tank you're firing from only refills 0.75 s after you stop; the others always refill.
- **Mounts:** the chassis sets them (T1 1, T2 and T3 2, T4 and T5 3); the Rack lane and the Bandolier set add one, up to 4. Each tank past the first costs 15% flow (less on a better chassis) and 15% heat. Swapping takes 0.4 s.
- Carry fuels that cover each other: one for health, one for shields and armor, and swap as the wave changes.

### Stats parts and sets can raise

| Stat | What it does | Applies to |
|---|---|---|
| Flow | More fuel units per second (more stacks, more heat). | all fuels only |
| Stack damage | Each burn stack hits harder. | one fuel or all |
| Burn duration | Stacks last longer before expiring. | one fuel or all |
| Tank capacity | Bigger tank. | one fuel or all |
| Fuel regen (units/s) | Fuel units refilled per second. | one fuel or all |
| Heat | Heat per unit fired. Negative = cooler. | one fuel or all |
| Vs armor | Damage multiplier against armor. | one fuel or all |
| Vs shields | Damage multiplier against shields. | one fuel or all |
| Vs shields + armor | Damage multiplier against both shields and armor. | one fuel or all |
| Vs health | Damage multiplier against health. | one fuel or all |
| Cone | Wider (or narrower) flame cone. | all fuels only |
| Range | Longer (or shorter) flame reach. | all fuels only |
| Heat cap | How much heat the gun holds before it overheats. | all fuels only |
| Cooling | Heat shed per second. | all fuels only |
| Fuel regen (%) | Multiplies the tank's refill rate. | one fuel or all |
| Swap time | Time to swap tanks. Negative = faster. | all fuels only |
| Tank mounts | Extra tank mounts on any chassis (up to 4). | all fuels only |
| Reaction power | Fuel reactions are stronger: the reaction a burning fuel sets off when another fuel lands, and the combos. | one fuel or all |
| Damage when hot | Extra stack damage while the gun is above 50% heat. | one fuel or all |
| Long-range damage | Extra stack damage on mutants beyond 300 px. | one fuel or all |
| Vs elites | Extra stack damage on elites and bosses. | one fuel or all |
| Close-range damage | Extra stack damage on mutants within 220 px of the muzzle. | one fuel or all |
| Cooler | Less heat per unit, and more heat shed per second (the same share of each). | all fuels only |

## Parts and lanes

### Tiers
- Parts come in **T0** (the starter parts) to **T5**. Their names are coloured by tier: T1 white, T2 green, T3 purple, T4 gold, T5 gold-red; set pieces teal. Pips show the tier too.
- You can craft (and find) a tier once your best threat reaches it: T2 at 6, T3 at 12, T4 at 16.
- **T5** (v0.9.28). A fifth tier opens at best threat 24. v0.9.32 made it a full tier step (the lab: +1.0 threat over T4, as T3 to T4 is +0.8): a T5 line flows 60 a second to a T4's 40; a T5 shroud holds 260 heat to a T4's 200; pump, igniter and filter add +55%, +60% and +52%, and a T5 chassis carries ×2.4 tank capacity. It is **built**, as every part is: a lane part or a set piece raised from T4 (Refine > BUILD THE NEXT TIER) for the tier's ◆ (36,000 for a fuel line) and 180 of its slot's common material, with the named materials its step asks for (Starting out > Materials and recipes). Keystones and exotics stay T4. From best threat 24 the 8-Ball builds orders at T5: it crafts their lane parts and set pieces at T5 (within THE HANDS KEEP), an order and a TOP TIER budget are done at T5, and the Showroom prints each ad's T5 lab number.
- **A five-piece bonus for every set** (v0.9.41; v0.9.42: all eighteen sets, each sized by the lab to about two threat levels). Wear five pieces of a set and each T5 piece among the five adds a chance; one roll a volley while the effect's condition holds; a volley that takes it hits harder on the mutants the effect is about, and takes its perk. Pieces below T5 add nothing. The run's HUD and the flamethrower's status show your chance.
  - **Flare-up** (the Brawler sets), 6.6% a piece: a volley landing on something close (the six nearest mutants, or within 220 px) hits x2 and costs no fuel.
  - **Long Shot** (Meltdown, Tesla Coilworks): Each T5 piece of the five adds 10.8%. A volley that takes it hits x2 and reaches 25% further.
  - **Blowoff** (Boiler Room, Hellmouth): Each T5 piece of the five adds 20%. At 50% heat or more, a volley that takes it hits x2 and stuns what it hits for 0.3 s.
  - **Second Helping** (Glacier Works, Slow Cooker): Each T5 piece of the five adds 15.6%. A volley that takes it hits x2 and costs no fuel.
  - **Fresh Tank** (Bandolier, Moonshine Run): Each T5 piece of the five adds 14.4%. A volley that takes it hits x2 and makes no heat.
  - **Cold Snap** (Walk-In Freezer): Each T5 piece of the five adds 9.6%. A volley that takes it hits x2 on every mutant that is slowed, stunned or frozen and stuns them for 0.02 s.
  - **Sear** (Hot Plate): Each T5 piece of the five adds 20%. A volley that takes it hits x2 on everything at the far end of your flame (the last 50% of its reach) and stuns them for 0.7 s.
  - **Seam** (Nutcracker): Each T5 piece of the five adds 20%. A volley that takes it hits x3 on every mutant with a shield or armor still up and stuns them for 0.3 s.
  - **Heaped Plate** (Potluck): Each T5 piece of the five adds 7.2%. A volley that takes it hits x2 on every mutant already carrying 20 stacks or more and makes no heat.
  - **Eureka** (Test Kitchen): Each T5 piece of the five adds 6%. A volley that takes it hits x2 on every mutant a reaction went off on in the last 3 s and makes no heat.
  - **Hot Handle** (Oven Mitts): Each T5 piece of the five adds 20%. A volley that takes it hits x2 on everything close (the six nearest mutants, or within 220 px) and stuns them for 0.3 s.
  - **Prime Cut** (Whole Hog): Each T5 piece of the five adds 10.8%. A volley that takes it hits x2 on elites and bosses.
  - **One More Round** (Last Call): Each T5 piece of the five adds 20%. For 15 s after the threat level rises, a volley that takes it hits x2 and makes no heat.
- **Close and long range** (v0.9.34). **Close** is the six mutants nearest the muzzle, or anything within the old distance (220 px; Bloom's 280). **Long range** starts at 450 px (it was 300, which four fifths of your fuel met). After a run the summary says what share of your fuel met each: close, long range, on elites, fired hot; the flamethrower's status keeps the last run's.
- **Greater rolls** (v0.9.34). One affix on a part can be a **greater roll**: it sits at x1.5 of its top roll, marked on the card. v0.9.88: Refine sets one for 1 Black Ichor (a dropped part carried one, while parts dropped); a part holds one, and setting another moves it. Optimize can't reach it, and rerolling that affix loses it. Never on a keystone or an exotic.
- **BUILD THE NEXT TIER** (v0.9.88, Refine; it was FORGE UP). A lane part or a set piece goes up one tier and keeps everything done to it: affixes, mutation, the half-step, Temper and its boss's mark. It costs that step of the recipe (Materials and recipes, in Starting out). **A greater roll** is set into one affix with 1 Black Ichor (Refine); no drop carries one any more.
- **FORGE UP** (v0.9.34, Refine). A lane part or a set piece goes up one tier and keeps everything done to it: affixes, behavior, the half-step, Temper. It costs 90% of crafting the part fresh at the new tier, up to your top craft tier. Keystones and exotics stay T4.
- **Sets and affixes, re-weighed** (v0.9.34). Potent, Pressurized, Recycling, Sticky and Catalytic roll half what they did (parts you own were halved to match); Bulging, Cooled and Searing kept their size. A set's stat lines now scale with its pieces' tier, and from 2 pieces each of your four best adds a plain bonus to every stack by its tier (each set's card gives its numbers). A set piece can be **re-forged to any lane**: the bonus counts the piece, the lane is yours. Every exotic adds +0% to its own fuel's stacks, outside the cap. In the lab a T5 build's affixes, keystone and set are now each worth two to three threat levels (they were 3.1, 1.6 and 1.0).
- **The half-step** (v0.9.24). A part's power is its tier, and a tier has two rungs: T3 and **T3+**, the "+" worth half the step to the next tier on the main stat and the lane's benefit lines (××1.24 on a fuel line, less where a tier's step is smaller; a "+" after the pips, and in the name). The Workbench rolls it by its level (25% at level 0, 85% at 8); Refine's **FORGE TO T+** adds it to a part for a craft and a half. A T3+ sits between T3 and T4; a plain T4 always beats it.

### Qualities

| Quality | Main stat | Affixes | Affix strength |
|---|---|---|---|
| Junk | ×1 | 0 | ×0.8 |
| Scavenged | ×1 | 0 | ×0.8 |
| Tuned | ×1 | 1 | ×1 |
| Mutated | ×1 | 2 | ×1.25 |
| Malevolent | ×1 | 3 | ×1.6 |

v0.9.24: **rarity is the affix count**, nothing else. A Scavenged part has no affix, a Tuned one, a Mutated two, a Malevolent three, and a rarer part's affixes roll stronger; the main stat is the tier's (Junk is retired: an old Junk part loads as Scavenged, and an old Mutated or Malevolent part keeps its edge as the half-step). Refine's UPGRADE adds an affix (the next rarity).

Every part has one **behavior** slot: a Mutated or Malevolent part rolls one 30% of the time, and Refine > BEHAVIOR rolls or changes one on any part for Chemicals (v0.9.24: one layer; they were mutations too).

### Lanes
Every slot has three **lanes**: three ways to build that part, each with a benefit (▲) and a drawback (▼). A lane exists at every tier. **Every lane can be built from the first day** (v0.9.88; a lane was learned by scrapping a dropped part of it), and a part can be **re-forged** into another lane of its slot.

#### Fuel Line

| Lane | Plays like | Benefit | Drawback | Builds |
|---|---|---|---|---|
| Gusher | Big bore, big bursts | ▲ Flow x1.35 | ▼ +15% heat per unit, and the tank empties 35% sooner | Juggler, Brawler |
| Capillary | Fewer drops, each one meaner | ▲ +35% stack damage, -20% heat | ▼ Flow x0.7: fewer stacks on a crowd per second | Miser, Lancer |
| Spool-Up Coil | Starts slow, ends hot | ▲ Flow climbs from x0.6 to x1.6 over 3 s of held fire | ▼ Drops back to x0.6 whenever you let go or swap | Furnace |

#### Nozzle

| Lane | Plays like | Benefit | Drawback | Builds |
|---|---|---|---|---|
| Lance | A needle at long range | ▲ Range x1.2, +40% burn duration, and +110% on what stands beyond the long-range line (450 px) | ▼ Cone x0.4 | Lancer |
| Fan | The steady all-rounder | ▲ Cone x1.5, and +90% on every stack (a plain bonus, outside the stack damage cap) | ▼ No extra reach, and +10% heat | Juggler, Miser |
| Bloom | Lets them come close | ▲ Cone x2, +220% stack damage within 280 px, -20% heat | ▼ No extra reach, and the bonus only lands on what is already close | Brawler |

#### Tank Chassis

| Lane | Plays like | Benefit | Drawback | Builds |
|---|---|---|---|---|
| Rack | More tanks | ▲ +1 tank mount | ▼ -15% flow per extra tank, swaps take 0.6 s | Juggler |
| Saddle Tank | One big tank | ▲ One mount with +200% capacity and +200% regen | ▼ One fuel only: nothing to rotate to when it's the wrong one | Miser, Lancer, Furnace |
| Carousel | Fast hands | ▲ Swaps take 0.1 s; +20% stack damage for 1 s after a swap | ▼ -20% capacity on every tank | Juggler |

#### Pump

| Lane | Plays like | Benefit | Drawback | Builds |
|---|---|---|---|---|
| Booster | More pressure | ▲ Pressure x1.5, +10% range | ▼ +20% heat | Brawler, Furnace |
| Siphon | Refills while it fires | ▲ The active tank refills at its full idle rate while firing; +10% range | ▼ Less pressure than a Booster (x1.2 against x1.5) | Miser |
| Accumulator | Saves it up | ▲ Stores pressure while idle; the first 3 s of a burst fire up to +125% flow | ▼ Nothing more once the store is spent | Juggler, Lancer |

#### Igniter

| Lane | Plays like | Benefit | Drawback | Builds |
|---|---|---|---|---|
| Smoulder | Long, low burns | ▲ Burn duration x1.6 | ▼ -15% stack damage | Miser, Brawler |
| Flash | Hits now | ▲ +55% on every stack (a plain bonus, outside the stack damage cap) | ▼ -30% burn duration, and half an igniter's burn bonus | Brawler, Juggler |
| Stoker | Builds on big targets | ▲ Each stack on a mutant past its 10th adds +0.8% to all its stacks (up to +20%) | ▼ -20% burn duration, and only x0.8 of the baseline burn | Lancer |

#### Filter

| Lane | Plays like | Benefit | Drawback | Builds |
|---|---|---|---|---|
| Distiller | Pure and hungry | ▲ Stack damage x1.5 | ▼ -15% tank capacity | Lancer, Furnace, Brawler |
| Catalyst | Breaks shells | ▲ +35% vs shields and armor | ▼ Three-quarters of the baseline stack damage, and -15% vs health | Juggler, Lancer |
| Coarse Mesh | Cheap fire | ▲ 20% of units cost no fuel | ▼ No stack damage bonus | Miser |

#### Shroud & Grip

| Lane | Plays like | Benefit | Drawback | Builds |
|---|---|---|---|---|
| Heatsink | Sheds heat | ▲ Cooling x1.6 | ▼ Heat cap x0.85 | Juggler, Miser, Lancer |
| Insulated | Holds heat | ▲ Heat cap x1.6 | ▼ Cooling x0.9, and it starts 1 s after you stop | Furnace |
| Vent Cowl | Dumps it all at once | ▲ Letting go above 50% heat vents it, burning everything within 120 px | ▼ Heat cap x0.7 | Brawler, Furnace |

### Builds
Lanes, sets and keystones lean toward five ways to play. None is required; mix what works.

| Build | Style | Lanes | Sets |
|---|---|---|---|
| Brawler | Lets them come close: wide cones, big bursts, damage up close. | Gusher, Bloom, Booster, Smoulder, Flash, Distiller, Vent Cowl | Deep Fryer, Grease Fire |
| Lancer | A needle at long range: picks apart big, shielded and armored targets. | Capillary, Lance, Saddle Tank, Accumulator, Stoker, Distiller, Catalyst, Heatsink | Meltdown, Tesla Coilworks |
| Furnace | Runs hot on purpose: holds heat and gets stronger near the top of the bar. | Spool-Up Coil, Saddle Tank, Booster, Distiller, Insulated, Vent Cowl | Boiler Room, Hellmouth |
| Miser | Makes fuel last: long burns, refills, cheap fire, one big tank. | Capillary, Fan, Saddle Tank, Siphon, Smoulder, Coarse Mesh, Heatsink | Glacier Works, Slow Cooker |
| Juggler | Many tanks and fast swaps: the right fuel for every mutant. | Gusher, Fan, Rack, Carousel, Accumulator, Flash, Catalyst, Heatsink | Bandolier, Moonshine Run |

### Affixes
Numeric rolls on a part: **eight affixes** (v0.9.24; fourteen before: the six that aimed at one pool or one condition folded into Potent and Searing, and every range grew ×1.5, so three affixes are a visible share of a part). The values are for Tuned rarity; multiply by the part's affix strength (Malevolent ×1.6).

| Affix | Raises | Fuel | Roll | From quality |
|---|---|---|---|---|
| Bulging | Tank capacity | All fuels | +12% to +30% | Junk |
| Catalytic | Reaction power | All fuels | +4% to +9% | Junk |
| Cooled | Cooler | All fuels | +6% to +15% | Junk |
| Potent | Stack damage | All fuels | +5% to +11% | Junk |
| Pressurized | Flow | All fuels | +4% to +9% | Junk |
| Recycling | Fuel regen | All fuels | +8% to +19% | Junk |
| Searing | Damage when hot | All fuels | +15% to +38% | Junk |
| Sticky | Burn duration | All fuels | +6% to +15% | Junk |

### Behaviors

| Behavior | What it does | From quality |
|---|---|---|
| Anvil | At full Fixated focus every 10th unit lands 12 stacks (it needs Fixated on another part) | Mutated |
| Backfire | Letting go of the trigger at 70% heat or hotter blasts what the gun fires in 5 seconds onto every mutant in the flame (once every 3 s) | Mutated |
| Chilling | Burning mutants are slowed 20%, and a chilled elite or boss bites 20% slower. Nothing with Flashpoint, where nothing is left burning | Mutated |
| Culling | A burning mutant under 30% of its health dies at once (a boss too). It has to be burning: nothing with Flashpoint | Mutated |
| Deadeye | The first unit to hit an elite or boss each second lands 20 more stacks | Mutated |
| Dregs | The last quarter of a tank hits +80% | Mutated |
| Fixated | Each second you fire one fuel, its stacks deal +8% more (up to +160%); a swap to another fuel starts it again, and it drains 2% a second while you aren't firing | Mutated |
| Marked | Hitting an elite or boss marks it: every stack on it deals x1.4 for 5 s, after every other bonus | Mutated |
| Opportunist | Stacks hit +90% on slowed mutants. It acts on a burn's ticks: nothing with Flashpoint | Mutated |
| Overkill | Damage past a kill carries, six times over, to the toughest burning mutant within 300 px (after a Flashpoint kill: the toughest mutant) | Mutated |
| Pent-Up | Each second you aren't firing with mutants about, your next burst charges +100% stack damage (up to +300%), spent over your next 30 units (90 with a boss on the field) | Mutated |
| Primed | The first 25 units from a full tank hit +180% | Mutated |
| Spreading | Burns jump to 2 nearby mutants when a burning mutant dies. With a boss on the field one of the jumps always lands on it. There has to be fuel on it: nothing with Flashpoint | Mutated |
| Steady Aim | After 2 s without firing, your next unit lands 36 stacks | Mutated |
| Toxic | Kills leave a toxic cloud that burns 7 stacks a tick for 2 s (70 px), each as strong as a stack you fire. With a boss on the field a second cloud forms on the boss | Mutated |
| Volatile | Kills explode for 30% of the mutant's max health on mutants nearby (a blast's own kills don't explode). An elite or boss in the blast also loses 3% of its own health | Mutated |

### Keystones
T4 parts that break one rule, at a cost. **They are built** (v0.9.88; they only dropped before): 5 trophies of the keystone's theme (any mix of that theme's four bosses), 15 of that theme's place materials (any mix), 45 of the slot's mutant material and 1 Black Ichor. The 8-Ball builds a build's keystone the moment the materials are in.

| Keystone | Slot | Rule | Cost | Builds | Its theme |
|---|---|---|---|---|---|
| Can Opener | Fuel Line | Shields, armor and health all take your fuel's best multiplier, and 30% more: whatever the fuel is good against, it is good against everything | It takes the fuel line's slot: no line lane's benefit | Brawler, Lancer | Armor |
| Double Distill | Filter | Every stack hits x2.0: a multiplier, over every stat and cap | Each unit costs 1.25 fuel and makes 15% more heat | Lancer, Furnace | Balanced |
| Feeding Frenzy | Nozzle | A kill streak: every kill adds +10% to all your stacks (an elite counts five), up to +250%. A Bloom nozzle under it: cone x2, +220% stack damage within 280 px, -20% heat | After 6 s without a kill the streak drains, four kills' worth a second | Brawler | Health |
| Fever Grip | Shroud & Grip | +25% stack damage per 5% heat, and heat cap +40% | A lockout at 100% heat lasts twice as long | Furnace | Armor |
| Flashpoint | Igniter | A stack's whole burn lands the instant it is applied, at 1.4 times its total, and at 2.8 times that on anything close (the six nearest mutants, or within 220 px) | Nothing lingers: Spreading, Chilling, Opportunist, Culling and Hellmouth do nothing (burn duration still counts: a longer burn lands more). A kill still sets off Toxic, Volatile and Overkill | Lancer, Brawler | Shield |
| Gatling Drum | Tank Chassis | Each unit fires from every mounted tank at once, each applying its own fuel's stack, and every tank refills like an idle one | Drains every tank together, each unit makes double heat, and every stack lands at 60% | Juggler | Balanced |
| Reaction Chamber | Pump | Fuel reactions hit four times as hard: +300% reaction power | +20% heat, and a plain pump's pressure where a Booster would give more | Juggler, Lancer | Shield |
- **v0.9.34 (the itemization build):** every keystone was run on every build. Three had stayed worth less than a plain lane part whatever their numbers (Afterburner, Blood Line, Backdraft Ring) and were **replaced**, slot for slot, by keystones that scale off things nothing else did: **Feeding Frenzy** (a kill streak), **Reaction Chamber** (fuel reactions) and **Can Opener** (every pool takes your fuel's best multiplier). One you owned became its replacement. Gatling Drum's stacks land at 60%, Flashpoint lands x1.4 and x2.8 more on anything close, Fever Grip gives +25% a 5% of heat (was 7%); Double Distill (x2.0 on every stack) is as it was. With those the lab's forty builds split across six keystones, the largest on about a third (it was half).

### Malevolent parts
The top quality. The Workbench can roll it once your best threat is past 21; until then a craft tops out at Mutated. Or upgrade a part's quality at the Workbench (the last step, Mutated to Malevolent, costs ×0.4).

## Sets

- **Eight sets outside the styles** (v0.9.39), eighteen sets in all. Hot Plate, Nutcracker, Walk-In Freezer, Potluck, Test Kitchen, Oven Mitts, Whole Hog and Last Call belong to no style and have no T5 effect: any build can wear them, each does one thing no other set does, and two of them (Whole Hog, Last Call) add no damage at all. They are listed after the style sets below. A build has six set slots beside its keystone, so a second set is paid for in pieces of the first: in the lab, giving up 2, 3 or 4 of a finished T5 build's own six pieces cost it about 0.7, 1.8 or 2.7 threat levels, and the six that deal damage were sized to give about that back on the builds they suit. Whole Hog and Last Call give back less, and pay in what comes home.
- **Three of them need something burning** (v0.9.39): Oven Mitts' Cooked, Potluck and Test Kitchen count stacks on a mutant or fuel reactions, so they do nothing under the Flashpoint igniter, which lands a stack's whole burn at once. Hot Plate, Nutcracker and the Freezer work with it (Nutcracker best of all).
- **Ten sets for the five styles** (v0.9.24; fifteen from v0.6.10: Pit Boss, Steeple Works, Foundry Rig, Thrift Shop and Cocktail Hour are retired, each into the other set of its style, which took its best line; their pieces, blueprints and ads in an old save become the survivor's, and their homes are the survivors' second homes). Every set has a piece for each of the seven slots. Wearing **2, 3 and 4 pieces** turns on its three bonuses and **5** its five-piece effect, and every bonus works on **every fuel** (since v0.7.8). A piece is a normal part of its tier and slot with affixes of its own, and **its lane is fixed** (v0.9.24; it rolled a random lane before, which left a build's set and its lanes at odds): the Showroom's builds wear their set pieces on the lanes the pieces are.
- **The 4-piece mechanics carry the set** (v0.9.24). The lab found a set worth about 0.6 threat levels and its stat lines no lever at all (doubling them moved a build 0.1), so the mechanics were raised instead: Grease Fire's kills explode for 6 stacks in a 120 px blast, Battered is +8% a stack up to +300% (and +150% close), Arc chains to 6 and chained stacks hit double, Critical Mass needs 30 stacks, Cold Start charges +60% a second to +200% and its chill is 30%, Still Hot is every other unit, and a Bandolier swap is +50% for 3 s. Mind that **Flashpoint** lands a stack's whole burn at once, so anything that counts the stacks *on* a mutant (Battered, Critical Mass, Hellmouth's endless burn, stacks outside the cone) does nothing with it; the Showroom says so on the ads it applies to.
- **Where they come from** (v0.9.88): a set's pieces are **built**, never found. A piece's blueprint is bought with its faction's favor; the piece is built at T1 from its home's elite material and raised a tier at a time (Starting out > Materials and recipes).
- **Blueprints:** breaking a piece down (Loadout > Stash) gives 10 + 2 × its quality favor with the set's faction (Blueprint Shards before v0.9.26), times (1 - 0.75 × the share of set blueprints you own; v0.8.2), so ×0.25 once you own them all. A set's blueprint costs 30 favor with its faction (Workbench > SETS), then you build its pieces. Faction reputation gives some blueprints too. Hellmouth's come only that way, with the Glow Cult's top reputation: buying them needs a Hellmouth piece in the stash, and nothing drops one now (an old save that holds a piece can still buy them).

### Deep Fryer
Brawler build · all fuels · built with Rancher's Brand, from the The Flesh Farms
- **2 pieces:** Kills drop +25% raw meat; +40% stack damage
- **3 pieces:** +150% stack damage within 220 px
- **4 pieces:** BATTERED: mutants within 220 px take +8% per stack on them (up to +300%)
- **Five pieces:** Flare-up. Each T5 piece of the five adds 6.6%. A volley landing on something close (the six nearest mutants, or within 220 px) that flares hits x2 and costs no fuel.
- **Every piece:** From 2 pieces, each of your four best adds to every stack by its tier (T1 to T5): 0.9% / 1.5% / 2.4% / 3.3% / 4.2%.

### Grease Fire
Brawler build · all fuels · built with Smokehouse Ash, from the Smokehouse Outskirts
- **2 pieces:** Stacks +60% damage
- **3 pieces:** Kills splash 2 stacks nearby
- **4 pieces:** GREASE FIRE: kills explode for 6 stacks in a wide blast; +60% stack damage
- **Five pieces:** Flare-up. Each T5 piece of the five adds 6.6%. A volley landing on something close (the six nearest mutants, or within 220 px) that flares hits x2 and costs no fuel.

### Meltdown
Lancer build · all fuels · built with Reactor Rod, from the Reactor Row
- **2 pieces:** Aging fuels (Rad Syrup) age 25% faster, +20% vs elites and bosses, and +20% stack damage beyond 300 px
- **3 pieces:** Elites and bosses take +25% more from every fuel, and every stack the gun lands on them hits twice as hard
- **4 pieces:** CRITICAL MASS: a mutant carrying 30+ stacks of one fuel takes +50% from every burn
- **Five pieces:** Long Shot. Each T5 piece of the five adds 10.8%. A volley that takes it hits x2 and reaches 25% further.
- **Every piece:** From 2 pieces, each of your four best adds to every stack by its tier (T1 to T5): 3.6% / 6% / 9.6% / 13.2% / 16.8%.

### Tesla Coilworks
Lancer build · all fuels · built with Crater Glass, from the Glow Crater
- **2 pieces:** +30% vs shields
- **3 pieces:** Breaking a shield stuns for 1 s
- **4 pieces:** ARC: every hit chains to 6 nearby mutants, and chained stacks deal +100%. A link with no mutant to jump to arcs back onto the one that was hit, at half strength
- **Five pieces:** Long Shot. Each T5 piece of the five adds 10.8%. A volley that takes it hits x2 and reaches 25% further.
- **Every piece:** From 2 pieces, each of your four best adds to every stack by its tier (T1 to T5): 6% / 10% / 16% / 22% / 28%.

### Boiler Room
Furnace build · all fuels · built with Pit Clinker, from the Smelter Pits
- **2 pieces:** Heat cap +25%, +35% stack damage
- **3 pieces:** Stacks +1.2% for every 1% of heat (up to +120% at full heat)
- **4 pieces:** PRESSURE COOKER: reaching 100% heat starts 3 s without a lockout and +50% flow, then the gun locks out and vents to 0 (once per 45 s); +60% stack damage
- **Five pieces:** Blowoff. Each T5 piece of the five adds 20%. At 50% heat or more, a volley that takes it hits x2 and stuns what it hits for 0.3 s.
- **Every piece:** From 2 pieces, each of your four best adds to every stack by its tier (T1 to T5): 4.8% / 8% / 12.8% / 17.6% / 22.4%.

### Hellmouth (rare)
Furnace build · all fuels · built with Neon Tube, from the The Neon Strip
- **2 pieces:** All fuels +220% stack damage
- **3 pieces:** All fuels +20% burn duration and +30% stack damage
- **4 pieces:** HELLMOUTH: stacks stop expiring while the mutant stays in the cone
- **Five pieces:** Blowoff. Each T5 piece of the five adds 20%. At 50% heat or more, a volley that takes it hits x2 and stuns what it hits for 0.3 s.

### Glacier Works
Miser build · all fuels · built with Sewer Pearl, from the Sewer Delta
- **2 pieces:** The gun cools 50% faster
- **3 pieces:** Burning mutants slow 30%
- **4 pieces:** COLD START: Pent-Up without the behavior (+60% a second idle, up to +200%), twice as fast with it; +40% stack damage
- **Five pieces:** Second Helping. Each T5 piece of the five adds 15.6%. A volley that takes it hits x2 and costs no fuel.
- **Every piece:** From 2 pieces, each of your four best adds to every stack by its tier (T1 to T5): 3.6% / 6% / 9.6% / 13.2% / 16.8%.

### Slow Cooker
Miser build · all fuels · built with Bog Cap, from the Fungal Bog
- **2 pieces:** +25% burn duration; tanks regen +1.5 units/s while you aren't firing
- **3 pieces:** Stacks on mutants outside the cone deal +45% damage
- **4 pieces:** SIMMER: every 10th unit applies 2 stacks, and stacks outside the cone deal +25% more; all fuels +57% stack damage
- **Five pieces:** Second Helping. Each T5 piece of the five adds 15.6%. A volley that takes it hits x2 and costs no fuel.
- **Every piece:** From 2 pieces, each of your four best adds to every stack by its tier (T1 to T5): 4.2% / 7% / 11.2% / 15.4% / 19.6%.

### Bandolier
Juggler build · all fuels · built with Prayer Gear, from the Scrap Mountain
- **2 pieces:** +1 tank mount on any chassis (up to 4)
- **3 pieces:** Swapping tanks gives +50% stack damage for 3 s
- **4 pieces:** QUICK DRAW: a swap within 1 s of the last costs no swap time
- **Five pieces:** Fresh Tank. Each T5 piece of the five adds 14.4%. A volley that takes it hits x2 and makes no heat.
- **Every piece:** From 2 pieces, each of your four best adds to every stack by its tier (T1 to T5): 3.6% / 6% / 9.6% / 13.2% / 16.8%.

### Moonshine Run
Juggler build · all fuels · built with Scorched Reel, from the Dead Drive-In
- **2 pieces:** Tanks +25% capacity, swap time -25%
- **3 pieces:** Swapping tanks fires +25% flow for 2 s
- **4 pieces:** STILL HOT: every other unit also applies a stack of the fuel fired before it; +30% stack damage
- **Five pieces:** Fresh Tank. Each T5 piece of the five adds 14.4%. A volley that takes it hits x2 and makes no heat.
- **Every piece:** From 2 pieces, each of your four best adds to every stack by its tier (T1 to T5): 0.9% / 1.5% / 2.4% / 3.3% / 4.2%.

### Walk-In Freezer
Any build · all fuels · built with Fulgurite, from the Static Fields
- **2 pieces:** Burning mutants slow by 6% a second, up to 40%
- **3 pieces:** At full chill a mutant freezes for 2 s, once every 6 s (a boss 1 s)
- **4 pieces:** SHATTER: a frozen mutant that dies bursts for 25% of its health onto mutants within 100 px; a frozen mutant under 15% health breaks
- **Five pieces:** Cold Snap. Each T5 piece of the five adds 9.6%. A volley that takes it hits x2 on every mutant that is slowed, stunned or frozen and stuns them for 0.02 s.

### Hot Plate
Any build · all fuels · built with Pit Clinker, from the Smelter Pits
- **2 pieces:** The far end of your flame leaves a burning patch (4 s): 32 stacks a second on mutants in it
- **3 pieces:** The patch burns 64 stacks a second and slows mutants on it 30%
- **4 pieces:** FIREBREAK: 96 stacks a second, and patches that touch last as long as any one is fed
- **Five pieces:** Sear. Each T5 piece of the five adds 20%. A volley that takes it hits x2 on everything at the far end of your flame (the last 50% of its reach) and stuns them for 0.7 s.
- **Every piece:** From 2 pieces, each of your four best adds to every stack by its tier (T1 to T5): 3% / 5% / 8% / 11% / 14%.

### Last Call
Any build · all fuels · built with Scorched Reel, from the Dead Drive-In
- **2 pieces:** The horn sounds 15 s before the truck (not 10), and kills in its window pay x4 (not x3)
- **3 pieces:** The gun makes no heat while the truck is starting
- **4 pieces:** ENCORE: when the truck arrives the horn sounds once more: another wave, another window, another 30 s
- **Five pieces:** One More Round. Each T5 piece of the five adds 20%. For 15 s after the threat level rises, a volley that takes it hits x2 and makes no heat.
- **Every piece:** From 2 pieces, each of your four best adds to every stack by its tier (T1 to T5): 3% / 5% / 8% / 11% / 14%.

### Nutcracker
Any build · all fuels · built with Tread Link, from the Tank Graveyard
- **2 pieces:** A broken shield drops Chemicals and broken armor drops Scrap; +40% vs shields and armor
- **3 pieces:** A shell that breaks bursts: 60% of it comes off the same shell of mutants within 120 px
- **4 pieces:** CRACK: the burst is 120%, and a shell a burst breaks bursts too
- **Five pieces:** Seam. Each T5 piece of the five adds 20%. A volley that takes it hits x3 on every mutant with a shield or armor still up and stuns them for 0.3 s.
- **Every piece:** From 2 pieces, each of your four best adds to every stack by its tier (T1 to T5): 1.5% / 2.5% / 4% / 5.5% / 7%.

### Oven Mitts
Any build · all fuels · built with Baron's Rivet, from the Rust Flats
- **2 pieces:** The pig heals 1 HP each time the threat level rises
- **3 pieces:** COOKED: a mutant carrying 30 or more stacks does no damage when it reaches you, at most one every 3 s. A boss carrying them misses one bite in five
- **4 pieces:** SECOND WIND: once a run, a hit that would kill you leaves you at 3 HP with full armor and lights everything near the truck
- **Five pieces:** Hot Handle. Each T5 piece of the five adds 20%. A volley that takes it hits x2 on everything close (the six nearest mutants, or within 220 px) and stuns them for 0.3 s.

### Potluck
Any build · all fuels · built with Bloat Bladder, from the Bloat Marsh
- **2 pieces:** A burning mutant passes 5 stacks a second to each mutant touching it
- **3 pieces:** 10 stacks a second, to mutants within 40 px
- **4 pieces:** PATIENT ZERO: the mutant carrying the most stacks shares half of them each second with everything within 150 px (a shared stack isn't shared again)
- **Five pieces:** Heaped Plate. Each T5 piece of the five adds 7.2%. A volley that takes it hits x2 on every mutant already carrying 20 stacks or more and makes no heat.

### Test Kitchen
Any build · all fuels · built with Mall Token, from the The Food Court
- **2 pieces:** A fuel reaction lands 5% of everything burning on the mutant at once
- **3 pieces:** 14%; reactions wait half as long, and each pair of fuels has its own wait (never Spatter)
- **4 pieces:** CHAIN REACTION: 23%, and a reaction goes off on the 2 nearest burning mutants too (never Spatter)
- **Five pieces:** Eureka. Each T5 piece of the five adds 6%. A volley that takes it hits x2 on every mutant a reaction went off on in the last 3 s and makes no heat.

### Whole Hog
Any build · all fuels · built with Rancher's Brand, from the The Flesh Farms
- **2 pieces:** Every kill drops its materials
- **3 pieces:** Elites and bosses drop their hoard twice (not the meat)
- **4 pieces:** NOSE TO TAIL: a run that gets out brings one more of the place's trophy for every boss killed
- **Five pieces:** Prime Cut. Each T5 piece of the five adds 10.8%. A volley that takes it hits x2 on elites and bosses.
- **Every piece:** From 2 pieces, each of your four best adds to every stack by its tier (T1 to T5): 3% / 5% / 8% / 11% / 14%.

## Exotic parts

One exotic part for every fuel in every slot (49 in all). **A build wears one exotic** (v0.9.41), and it is the build's second big choice beside its keystone. Each has **a rule of its own, built on its fuel's character** (v0.9.41: the old ones shared one effect a slot): Napalm's spread and stick, Thermite's work on armor, Ion Gel's on shields, Hooch's blasts, Rad Syrup's slow build, Fryer Oil's cooking, Lard's grease. An exotic adds no flat damage: it is its rule. The rule works on its fuel in whichever tank holds it. Putting a second exotic on sends the first back to the stash. **v0.9.42, the balance pass:** the lab measured every exotic on four finished builds of its fuel and three seeds, reworked the weak ones and trimmed the strong, until all 49 add about two threat levels (each within one of the others). What that means in play: most runs end at a boss, so the rules that count are the ones that reach the boss; a build that fires its exotic's fuel a third of the time (the three-fuel Juggler builds) gets about a third of it.

### Getting one
- **Blueprint:** bought from the faction that deals in the fuel (CRAFT tab > EXOTICS) with **favor**. Every reputation point you earn also earns a point of favor; spending favor never lowers your reputation level. Every blueprint needs reputation level 4 and costs 360 favor.
- **Crafting:** Energy Sprinkles, the slot's T4 material and the fuel's **exotic material** (v0.9.24: no Blueprint Shards any more, and half the material: Shards are the scrap economy's currency, an exotic is a faction's gift, and tying them stalled both). It's a T5 part (v0.9.41; T4 before), built on whichever of the slot's lanes you choose when you craft it, and rolls rarity, affixes and a behavior like a set piece. It costs ◆24,000, 12 exotic material and the slot's T4 material. Exotics can be refined, but not re-forged into another lane, and SCRAP SHOWN leaves them alone; scrapping one gives back half its exotic material.
- **Exotic materials** drop only at their destination, from threat 10: 1.5% a kill (an ordinary mutant counts its loot weight), 30% from elites; one each, +1 for every 5 threat levels past 10. Crew trips bring them home too.

| Material | Fuel | Drops at | Blueprints from |
|---|---|---|---|
| Tallow Brick | Rendered Lard | Bloat Marsh | Sewer Kings |
| Napalm Amber | Swamp Napalm | Fungal Bog | Sewer Kings |
| Slag Heart | Thermite Slurry | Smelter Pits | Rust Barons |
| Ion Crystal | Ion Gel | Static Fields | Glow Cult |
| Still Copper | Rocket Hooch | Scrap Mountain | Rust Barons |
| Isotope Seed | Rad Syrup | The Neon Strip | Glow Cult |
| Crackling | Fryer Oil | The Food Court | Sewer Kings |

### Rendered Lard
Blueprints from the Sewer Kings; crafted with Tallow Brick (Bloat Marsh).

| Slot | Part | Effect |
|---|---|---|
| Fuel Line | Schmaltz Aorta | RENDERING: Lard bites armor at x2 and shields at x1. A mutant that dies with Lard on it puts fuel back in the tank, more from a big one |
| Nozzle | Schmaltz Throat | SLIP: The touch of Lard takes a mutant's feet away: stunned 1.5 s, and again every 3 s |
| Tank Chassis | Schmaltz Altar | GREASED FEED: Every 4 s the feed coughs grease over the cone: 12 Lard stacks, a 0.25 s stun and a 60% slow for 3 s |
| Pump | Drippings Bellows | GUSHER: Lard adds no heat, flows +100% and bites shields and armor at x1 |
| Igniter | Schmaltz Crown | GREASE BOMB: A mutant that dies with Lard on it bursts: 2 Lard stacks plus 6% of the Lard it carried on everything around it, more and wider from a big mutant |
| Filter | Drippings Sieve | CLARIFIED: Lard bites shields at x2 and armor at x1 |
| Shroud & Grip | Tallow Mitt | SLICK: Whatever the gun hits, with any fuel, is slick for 2 s: slowed 50%, and it takes +30% from everything |

### Swamp Napalm
Blueprints from the Sewer Kings; crafted with Napalm Amber (Fungal Bog).

| Slot | Part | Effect |
|---|---|---|
| Fuel Line | Swamp-King Aorta | NEVER DRIES: A new Napalm stack sets the burn of those already there back to full, and each one that lands makes Napalm hit that mutant 3% harder (up to +200%) |
| Nozzle | Swamp-King Throat | CONTAGION: Each second a burning mutant passes 4 Napalm stacks to every mutant touching it that carries fewer |
| Tank Chassis | Swamp-King Altar | FERMENT: Napalm ferments in the tank into acid: it bites shields and armor at x1.3 |
| Pump | Jelly Bellows | GLOB LAUNCHER: Twice a second one glob lands everything the pump would have sprayed on a 150 px splat, at x3, and sticks what it lands on for 0.3 s |
| Igniter | Swamp-King Crown | PLAGUE: A mutant that dies with Napalm on it passes 100% of its stacks, with the time each has left, to the nearest mutant |
| Filter | Jelly Sieve | SEEPS THROUGH: Under a shield or armor, Napalm also burns the health beneath, at 15% of its strength. On bare health it hits +40% |
| Shroud & Grip | Bog Mitt | TAR PIT: Napalm slows 6% a stack, up to 55%. A mutant at the cap is stuck: every other hit it throws at the pig does nothing |

### Thermite Slurry
Blueprints from the Rust Barons; crafted with Slag Heart (Smelter Pits).

| Slot | Part | Effect |
|---|---|---|
| Fuel Line | Forge-Heart Aorta | SMELTER: Thermite hits +100%. Armor it breaks is smelted: 15 fuel back in the tank, 40 stacks on everything within 120 px, and that mutant takes +300% from everything for the rest of its life |
| Nozzle | Forge-Heart Throat | LANCE: The cone narrows to 67% of its width and reaches 40% further; everything in the line takes +60%, and its armor x3.5 |
| Tank Chassis | Forge-Heart Altar | HEAT SINK: Above half heat Thermite burns the gun's heat instead of fuel, and hits +50% |
| Pump | Crucible Bellows | FORGE BLAST: The hotter the gun, the harder Thermite hits: up to +200% at full heat. It heats the gun 20% faster |
| Igniter | Forge-Heart Crown | SPRAY: Armor Thermite breaks sprays 150% of its weight onto the armor of everything within 130 px |
| Filter | Crucible Sieve | CRACKED OPEN: Armor Thermite breaks stuns everything within 160 px for 2 s, and that mutant is cracked open for good: it takes 200% more from everything, after every other bonus. A boss is cracked open as soon as Thermite has its armor under 50%. The break jumps: the weakest armor within reach breaks the same way, up to 4 in a row (a boss's armor loses 15% instead, and stops it) |
| Shroud & Grip | Slag Mitt | TEMPERED: Each armor Thermite breaks makes the next 160 units of any fuel hit +220% |

### Ion Gel
Blueprints from the Glow Cult; crafted with Ion Crystal (Static Fields).

| Slot | Part | Effect |
|---|---|---|
| Fuel Line | Storm Aorta | STORM LINE: Every 3 s the line throws 60 Ion stacks and a 1.5 s stun on everything within 320 px of the muzzle |
| Nozzle | Storm Throat | CHAIN LIGHTNING: Ion Gel hits its cone +50%, then arcs to 10 more mutants beyond it at x14, each arc 10% weaker. Each mutant an arc reaches is jolted: stunned 0.5 s |
| Tank Chassis | Storm Altar | PARALLEL CIRCUIT: Ion Gel bites armor and health at x1 its bite on shields, and with Ion Gel in a tank your other fuel bites shields at x3 or better |
| Pump | Capacitor Bellows | PULSE: Ion Gel charges for 2 s and fires it all at once in a double cone at +150%, with a half-second stun |
| Igniter | Storm Crown | EMP: A shield Ion Gel pops deals 40% of what it held to everything within 150 px, shields first |
| Filter | Capacitor Sieve | OVERLOAD: A shield Ion Gel pops stuns everything within 110 px for 1 s, and that mutant takes +100% from everything for 4 s |
| Shroud & Grip | Static Mitt | STATIC FIELD: Every 2.5 s, 35 Ion stacks and a 1.5 s stun on everything within 300 px of the pig |

### Rocket Hooch
Blueprints from the Rust Barons; crafted with Still Copper (Scrap Mountain).

| Slot | Part | Effect |
|---|---|---|
| Fuel Line | Rocket Aorta | ROCKET LINE: Every 3 s a rocket lands 80 Hooch stacks and a 1 s stun on the thickest knot of mutants in range |
| Nozzle | Rocket Throat | FIREBALL: A mutant that dies with Hooch on it goes up: x0.75 of what its Hooch had left lands on everything within 90 px |
| Tank Chassis | Rocket Altar | KICK: Every 50 units of Hooch the tank kicks: everything in the cone takes 36 extra stacks and a 0.4 s stun |
| Pump | Moonshine Bellows | REDLINE: Past half heat Hooch hits harder the hotter the gun: +300% at full heat. It heats the gun 25% faster |
| Igniter | Rocket Crown | FLASHBANG: A Hooch kill staggers everything within 80 px for 0.15 s and leaves 4 stacks on it |
| Filter | Moonshine Sieve | DOOR-KICKER: A shield or armor Hooch breaks blows in: 50 stacks and a stagger on everything within 120 px |
| Shroud & Grip | Mash Mitt | ROCKET VENT: An overheat with Hooch loaded doesn't hurt: it is dumped forward as 160 stacks and a 2 s stun on everything in front, and heat drops to 30% (every 5 s) |

### Rad Syrup
Blueprints from the Glow Cult; crafted with Isotope Seed (The Neon Strip).

| Slot | Part | Effect |
|---|---|---|
| Fuel Line | Half-Life Aorta | HALF-LIFE: Rad Syrup burns x4 as long and ages x2 as fast |
| Nozzle | Half-Life Throat | DIRTY BOMB: A mutant that dies with Rad Syrup on it throws 34% of its stacks, at their age, and 110 fresh ones onto each of 3 mutants nearby |
| Tank Chassis | Half-Life Altar | RADIATION SICKNESS: From its first dose a mutant sickens every 2 s: 12% slower and +48% from everything each time, down to half speed and +200% |
| Pump | Isotope Bellows | DOSE: Every Rad stack that has ever landed on a mutant raises Rad Syrup's damage on it by 10% (up to +400%) |
| Igniter | Half-Life Crown | CRITICAL MASS: At 60 Rad stacks a mutant goes critical, once: 100% of what its Rad had left hits everything within 120 px, and each gets 15 stacks |
| Filter | Isotope Sieve | HARD GLOW: Under half health a mutant with Rad Syrup on it glows hard, once: stunned 2.5 s, +100% from everything for 6 s, and 80 stacks on everything within 120 px |
| Shroud & Grip | Glowing Mitt | GLOW: Each second a mutant with Rad Syrup on it passes 8 stacks to every mutant within 90 px that carries fewer |

### Fryer Oil
Blueprints from the Sewer Kings; crafted with Crackling (The Food Court).

| Slot | Part | Effect |
|---|---|---|
| Fuel Line | Deep-Fry Aorta | SEASONED OIL: Every kill with Fryer Oil adds 6% Fryer damage this run (up to +400%). Fire the tank dry and half the seasoning goes with the old oil |
| Nozzle | Deep-Fry Throat | FRY BASKET: The cone is 25% wider, and Fryer Oil bites shields and armor at x1.4 |
| Tank Chassis | Deep-Fry Altar | FRY STATION: Fryer Oil hits +90%, and +8% more for each raw cut you are carrying (up to +200% in all) |
| Pump | Crackling Bellows | CRISPY: 1.5 s in the oil and a mutant is crispy: +400% from everything, it shatters under 25% health, and a crispy mutant that dies puts 2 fuel back in the tank |
| Igniter | Deep-Fry Crown | BATTERED: The longer a mutant has been in the oil, the harder Fryer Oil hits it: +50% a second, up to +600%. Fried cuts are worth +50% |
| Filter | Crackling Sieve | TENDERISE: A shield or armor Fryer Oil has touched takes +400% from every fuel. Fryer Oil is +50% on bare health |
| Shroud & Grip | Batter Mitt | FRIED STIFF: A mutant Fryer Oil touched in the last 3 s is slowed 60% |

## Fuels and stills

Each fuel comes from its own **still** in the Production yard. Rendered Lard's still is there from the start; the others need a **blueprint**: reach the threat shown at that destination, then get out alive.

| Fuel | Still | Blueprint | Damage | vs health / shields / armor | Burn | Heat | Rule |  |
|---|---|---|---|---|---|---|---|---|
| Rendered Lard | Rendering Kettle | from the start | 1 | ×1.2 / ×0.25 / ×0.25 | ×1 | ×0.6 | - | Rendered from... best not to ask. Sticks to flesh, slides off metal. |
| Swamp Napalm | Bog-Gas Fermenter | Sewer Delta, threat 3 | 1 | ×1.35 / ×0.25 / ×0.25 | ×1.6 | ×0.8 | - | Gelled bog-gas. Burns forever, mostly on meat. |
| Thermite Slurry | Crucible Furnace | Rust Flats, threat 4 | 1 | ×0.85 / ×0.25 / ×2 | ×0.8 | ×1.2 | - | Eats through scrap plating like it owes money. |
| Ion Gel | Capacitor Stack | Glow Crater, threat 4 | 1 | ×0.7 / ×2.2 / ×0.25 | ×0.9 | ×1 | - | Crackling blue goop. Pops rad-shields like soap bubbles. |
| Rocket Hooch | Copper Moonshine Still | The Junk Bazaar, threat 8 | 1.4 | ×1.1 / ×1.1 / ×1.1 | ×0.6 | ×1.5 | - | Triple-distilled. Do not drink. Okay, maybe a sip. |
| Rad Syrup | Glow Vat | Reactor Row, threat 12 | 0.19 | ×1 / ×1 / ×0.8 | ×1.4 | ×0.7 | each stack deals +12% more for every second it has burned (up to +80%) | Sweet, sticky and glowing. The longer it clings, the worse it gets. |
| Fryer Oil | Deep-Fry Drum | The Flesh Farms, threat 12 | 0.85 | ×1.2 / ×0.25 / ×0.25 | ×0.8 | ×1.3 | its kills drop cuts already fried: they skip the smoker and sell for +25% | Ten thousand batches deep. Whatever it kills comes out crispy. |

Damage is per stack per tick; burn multiplies the 3 s a stack lasts; heat multiplies the heat each unit makes.

### Stills
- The yard has 7 still plots, one for each fuel; 2 are open at the start and the yard expansions open the rest (the eighth plot is the Mystery Meat Farm, below):

|  | Opens | Cost |
|---|---|---|
| Expansion 1 | plots 3 and 4 | ◆400 + 15 Scrap Metal |
| Expansion 2 | plots 5 and 6 | ◆2,000 + 50 Scrap Metal + 25 Chemicals |
| Expansion 3 | plot 7 | ◆7,000 + 140 Scrap Metal + 70 Chemicals + 70 Mutant Bits |
- **Still level** (up to 10): +1.5 fuel regen a second each. **Tank level** (up to 10): +25% tank capacity each. Both cost ◆ (rising each level) and materials.
- **Attachments:** each still has 4 sub-slots (2 regen, 2 tuning) that open at still levels 1 to 4. An attachment only affects that still's fuel, levels up to 5, and swapping one resets that slot to level 1.

| Attachment | Sub-slot | Effect |
|---|---|---|
| Drip Feeder | regen | +1.0 fuel regen/s per level |
| Potency Mixer | tuning | +8% stack damage per level |
| Gel Thickener | tuning | +10% burn duration per level |
| Breaker Catalyst | tuning | +10% vs shields and armor per level |
| Cool Runner | tuning | -8% heat per level |

## Fuel reactions

Swap fuels and they **react**. When stacks of one fuel land on a mutant that's still burning with another, the burning fuel's reaction goes off. A word pops on the mutant and the fire shows it (on LIVE HIGH and ULTRA).

- **It takes a swap.** The fuel that lands has to be a different one from the last fuel that landed on that mutant. Holding one fuel never reacts.
- **What counts as landing:** the gun's stream and your gear's effects (Gatling Drum, Still Hot, Vent bursts, set pools and blasts, chains). Part mutations (Spreading, Toxic, Volatile, Chilling, Backfire, Overkill) don't, and neither does a reaction's own fire.
- **How often:** each reaction goes off at most once every 0.5 s on one mutant (some wait longer: see the table).
- **Flashpoint** burns a stack out the instant it lands, so nothing is left burning to react with.

### The seven reactions (the burning fuel's)

| Burning fuel | Reaction | What it does |
|---|---|---|
| Rendered Lard | Spatter | Copies of 30% of its stacks splash onto the nearest mutant within 150 px (the burning one keeps its own). At most every 2 s on one mutant. |
| Thermite Slurry | Breach | For 4 s, every other fuel hits armor at full strength, however weak it usually is against armor. |
| Ion Gel | Static jolt | A 0.5 s stun (half on a boss), at most every 3 s. |
| Swamp Napalm | Burn-off | Its stacks burn out ×2 as fast for ×2.4 the damage a tick: ×1.2 in all, much sooner. A stack burns off once. |
| Rocket Hooch | Flashover | Everything its stacks had left lands at once, ×1.75, and they're gone. |
| Rad Syrup | Fallout | For 6 s the arriving fuel's stacks grow with age, like Rad Syrup's. |
| Fryer Oil | Hot oil | For 4 s every other fuel hits health +50%. |

### Combos (two fuels together)

| Fuels | Combo | What it does |
|---|---|---|
| Thermite + Ion Gel | Thermal shock | Shields and armor break together: 20% of what's left of each, but no more than ×4 the damage the Thermite and Ion burns have left on that mutant. At most every 4 s. |
| Swamp Napalm + Rocket Hooch | Inferno | A flashover on a mutant burning with Napalm throws 50% of its Napalm onto up to 3 mutants nearby. |
| Rendered Lard + Swamp Napalm | Tar | Slowed 30% for 3 s, and every burn on it lasts 0.5 s longer (once a stack). |
| Ion Gel + Rad Syrup | Isotope arc | A jolt carries 50% of the aged Rad stacks to the nearest mutant within 170 px. |

### Reaction power
- The **Catalytic** affix rolls +4% to +9% **reaction power** on a part (more on better parts). A reaction is as strong as the burning fuel's reaction power; a combo takes the stronger of its two fuels.
- The BALANCE menu's **Fuel reactions** knob scales every reaction (0 turns them off).

### Telling fuels apart
- On LIVE HIGH and ULTRA each fuel's flame has its own look: Lard's black smoke, Thermite's white-hot core, Ion Gel's arcs, Napalm's bog-gas bubbles, Hooch's afterburner jet with shock diamonds, Rad Syrup's sinking flame and fallout motes, Fryer Oil's popping oil. Where two fuels meet the colours blend, and a bright seam flickers on a mutant that's about to react.
- The flamethrower wears its fuels too (Settings: **FUEL STYLES**). Each tank wears its own fuel's look; the gun, the hose and the rack wear the loaded tank's, and change when you swap.

## Mutants

Pools below are at threat 0; they grow with the destination's rates and the difficulty curve every level. Elites have ×3.

**The mutants recast (v0.9.45).** Every mutant and boss is one of forty-three new creatures, kept at the art's own pixel size and walking in eight frames. A type is a different creature on each kind of map (Balanced, Armor, Shield, Health), and most slots have a second look that two spawns in five wear. The five types are named after the new cast: Drudge (was Shambler), Creeper (Skitter), Leaker (Glowbag), Platehide (Scrapper) and Behemoth (Tumor Hulk). Looks and names only: a type's health, speed, drops and size on screen are what they were.

| Type | Balanced maps | Armor maps | Shield maps | Health maps |
|---|---|---|---|---|
| Drudge | Fallout Lug / Jaundiced Lug | Rubbleback | Coil Ghoul | Gulper / Lasher |
| Creeper | Sludge Wisp / Geiger Wisp | Shellhound | Grub Hopper / Barrelhead | Brainling |
| Leaker | Geiger Ghost / Meltdown Porter | Tank Porter | Live Wire | Melter / Sump Porter |
| Platehide | Hazmat Bruiser | Pipe Hunch / Porthole Hog | Springback | Bolted Heap |
| Behemoth | Slimeback | Boiler Mule / Maul-Tail | Capacitor | Big Maw / Valve Tick |

| Mutant | Health | Shields | Armor | Speed | Shows up from | Meat | Drops | Common at |
|---|---|---|---|---|---|---|---|---|
| Drudge | 16 | - | - | 46 | threat 0 | Drudge Shank | Mutant Bits | Dead Drive-In, The Flesh Farms, Fungal Bog |
| Creeper | 6 | - | - | 105 | threat 1 | Creeper Drumettes | Mutant Bits | The Junk Bazaar, The Food Court, Scrap Mountain, The Neon Strip, Sewer Delta |
| Leaker | 12 | 18 | - | 40 | threat 2 | Leaker Belly | Chemicals | Dead Drive-In, Smelter Pits, Glow Crater, Reactor Row, The Neon Strip, Static Fields, Fungal Bog |
| Platehide | 14 | - | 28 | 34 | threat 3 | Platehide Ribs | Scrap Metal | The Junk Bazaar, Rust Flats, Scrap Mountain, Tank Graveyard, Smelter Pits, Reactor Row, Bloat Marsh |
| Behemoth | 104 | - | 32 | 24 | threat 6 | Behemoth Brisket | Scrap Metal, Mutant Bits | The Food Court, Tank Graveyard, Static Fields, Sewer Delta, The Flesh Farms, Bloat Marsh |

- A destination's favourite mutants show up 2 threat levels early and more often.
- Shields and armor come off before health, so fuels and parts that break shells (vs shields, vs armor) matter more as those pools grow.

### Map bosses
v0.9.3. A run brings the map's boss: one of its mutants grown huge (1.9x the size, 55% of the speed), with 14 times an elite's pools, shared out by the map's theme. v0.9.88: the elite it is sized from is the middle of that place's mutants, whichever one it is drawn as (it was the one drawn: a boss drawn as a Behemoth was 21 times one drawn as a Creeper before growth, and over six seeds the first boss had from 366 thousand to 81 million pools). v0.9.18: bosses come on a beat: at every threat level a run reaches that is a multiple of 5 (from threat 4 up), with a warning line 10 s before, one at a time (a boss still alive at the next beat holds it until it dies; the BALANCE menu's bosses knob scales the beat, 0 turns them off). It counts as an elite. At the truck it doesn't vanish like a mutant: it stays and takes its turn on the bite clock again and again (**1** heart every 1.5 s at the most; v0.9.63) until it dies. It drops **Flux** like a contract: 1 + threat / 10 (v0.9.18), so a fighter who never deals can still temper.

- **How they look** (v0.9.40). Every mutant is a different creature on each map theme: mutated flesh wearing the junk that lies around that kind of place. Each theme has its own boss body (The Furnace on Balanced maps, The Stack on Armor, The Twin Dynamo on Shield, The Skullsquid on Health; The Stack and The Skullsquid have a second body that every other one of their maps wears), and each map's boss wears its own piece on its head. An elite carries a radiation sign over its bars; a boss carries a burning skull. Its size to hit is as before.
- **Its pools follow the map's theme.** Health maps: 90% health. Armor maps: 72% armor. Shield maps: 72% shields. Balanced maps: a third each. Bring the fuel that answers the theme.
- **Its hoard:** 4 of the map's exotic material, +1 every 4 threat levels (at a place with none of its own, one of its theme-mates'), from any threat, its **trophy** (v0.9.88; a keystone half the time, before) and now and then **Black Ichor**, on top of an elite's drops.
- The BALANCE menu's **Boss chance** (0 turns them off) and **Boss toughness** change both.

| Place | Boss |  | Theme | Drops |
|---|---|---|---|---|
| Smokehouse Outskirts | Old Gristle | The Smokehouse's oldest regular | Balanced | Crackling |
| The Junk Bazaar | The Haggler King | Everything's for sale but him | Balanced | Crackling |
| Dead Drive-In | The Double Feature | Two heads, no intermission | Balanced | Crackling |
| The Food Court | The All-You-Can-Eat | It ate the food court | Balanced | Crackling |
| Rust Flats | The Rust Colossus | A walking scrapyard | Armor | Slag Heart, Still Copper |
| Scrap Mountain | The Scrapheap Titan | Bolted together from a mountain | Armor | Still Copper |
| Tank Graveyard | The Iron Hog | Wears a tank. Literally | Armor | Slag Heart, Still Copper |
| Smelter Pits | The Slag Golem | Cooled on the outside only | Armor | Slag Heart |
| Glow Crater | The Glowing One | You can see its bones from here | Shield | Ion Crystal, Isotope Seed |
| Reactor Row | The Choirmaster | Its hum holds the shields up | Shield | Ion Crystal, Isotope Seed |
| The Neon Strip | The Bouncer | Not on the list | Shield | Isotope Seed |
| Static Fields | The Storm Caller | Wrapped in its own weather | Shield | Ion Crystal |
| Sewer Delta | The Bloated Matriarch | Mother of the sewers | Health | Tallow Brick, Napalm Amber |
| The Flesh Farms | The Prize Steer | First prize at the mutant fair | Health | Tallow Brick, Napalm Amber |
| Fungal Bog | The Sporemother | More mushroom than mutant | Health | Napalm Amber |
| Bloat Marsh | The Big Bloat | Don't pop it near the truck | Health | Tallow Brick |

## Destinations and factions

### Destinations
Sixteen places in four themes, four places each (since v0.8.0). A theme's places grow their mutants at the same rates (the same difficulty), with a different mix of mutants each; every place but the Outskirts is the turf of its own faction, and the new ones open one after another with the reputation of the place before. Each set has one home, each still blueprint and each exotic material drops at one place.

- **Balanced** (Health, armor and shields grow alike): Smokehouse Outskirts, The Junk Bazaar, Dead Drive-In, The Food Court. Its rule in the run, **Two fronts**: Waves come high and low at once: half a pack along the top of the field, half along the bottom.
- **Armor** (Armor grows fastest: bring something that melts plates): Rust Flats, Scrap Mountain, Tank Graveyard, Smelter Pits. Its rule in the run, **Plates**: Armored mutants wear a plate (+50% armor). Burning it off stuns them for a moment and drops Scrap Metal.
- **Shield** (Shields grow fastest: bring something that pops them): Glow Crater, Reactor Row, The Neon Strip, Static Fields. Its rule in the run, **Radiation**: A shield that pops leaks radiation: the gun's heat jumps 8% of its cap.
- **Health** (Raw health grows fastest: big meaty mutants): Sewer Delta, The Flesh Farms, Fungal Bog, Bloat Marsh. Its rule in the run, **Flood**: The field floods but for one lane a wave: packs funnel into it, a mutant bigger.

**Map rules** (v0.9.28). Every theme fights a little differently; the Map tab names a place's rule and the HUD shows it for the run's first seconds. Plates: an armored mutant's armor is ××1.5; when it burns off the mutant is stunned 1.2 s and drops 2 Scrap Metal (× its loot share). Radiation: a popped shield adds 8% of the heat cap to the gun. Flood: each wave takes one of three lanes (14 px either way, where a wave spreads 50 elsewhere) and a pack has 1 mutant more. Two fronts: a pack splits between the top and bottom of the field (30 px in from the edges); a lone mutant takes the edges in turn.

#### Smokehouse Outskirts
Home turf. Balanced mutants, a neutral market that pays a flat 0.9x.
- **Unlock:** open from the start. **Market:** neutral (a flat ×0.9 for any sauce, no reputation).
- **Theme:** Balanced. **Growth a level:** health ×1.17, armor ×1.17, shields ×1.17.
- **Sets:** Grease Fire. **Still blueprints:** none. **Exotic material:** none.

#### The Junk Bazaar
Bazaar Hagglers turf. A swap meet under tarps; creepers steal from the stalls.
- **Unlock:** opens at best threat 6. **Market:** Bazaar Hagglers turf.
- **Theme:** Balanced. **Growth a level:** health ×1.17, armor ×1.17, shields ×1.17.
- **Common mutants:** Creeper, Platehide. **Extra drops:** none.
- **Sets:** none of its own. **Still blueprints:** Copper Moonshine Still (threat 8). **Exotic material:** none.

#### Dead Drive-In
Reel Cult turf. The last film still loops; drudges shuffle in for the late show.
- **Unlock:** needs Bazaar Hagglers reputation 1. **Market:** Reel Cult turf.
- **Theme:** Balanced. **Growth a level:** health ×1.17, armor ×1.17, shields ×1.17.
- **Common mutants:** Drudge, Leaker. **Extra drops:** none.
- **Sets:** Last Call, Moonshine Run. **Still blueprints:** none. **Exotic material:** none.

#### The Food Court
Mallrat Gangs turf. A gutted mall; behemoths nest in the fry pits.
- **Unlock:** needs Reel Cult reputation 1. **Market:** Mallrat Gangs turf.
- **Theme:** Balanced. **Growth a level:** health ×1.17, armor ×1.17, shields ×1.17.
- **Common mutants:** Behemoth, Creeper. **Extra drops:** none.
- **Sets:** Test Kitchen. **Still blueprints:** none. **Exotic material:** Crackling (threat 10).

#### Rust Flats
Rust Barons turf. Armor piles up fast; Platehide country. Their scrap comes out of the furnace still glowing.
- **Unlock:** opens at best threat 3. **Market:** Rust Barons turf.
- **Theme:** Armor. **Growth a level:** health ×1.12, armor ×1.29, shields ×1.11.
- **Common mutants:** Platehide. **Extra drops:** Scrap Metal ×2.
- **Sets:** Oven Mitts. **Still blueprints:** Crucible Furnace (threat 4). **Exotic material:** none.

#### Scrap Mountain
Tin Monks turf. A peak of crushed cars; platehides and creepers climb it in swarms.
- **Unlock:** needs Rust Barons reputation 2. **Market:** Tin Monks turf.
- **Theme:** Armor. **Growth a level:** health ×1.12, armor ×1.29, shields ×1.11.
- **Common mutants:** Platehide, Creeper. **Extra drops:** Scrap Metal ×2.
- **Sets:** Bandolier. **Still blueprints:** none. **Exotic material:** Still Copper (threat 10).

#### Tank Graveyard
Ironsides turf. Rusted tanks in rows; behemoths wear the turrets.
- **Unlock:** needs Tin Monks reputation 1. **Market:** The Ironsides turf.
- **Theme:** Armor. **Growth a level:** health ×1.12, armor ×1.29, shields ×1.11.
- **Common mutants:** Platehide, Behemoth. **Extra drops:** Scrap Metal ×2.
- **Sets:** Nutcracker. **Still blueprints:** none. **Exotic material:** none.

#### Smelter Pits
Slag Brothers turf. Open furnaces; the platehides come out glowing hot.
- **Unlock:** needs The Ironsides reputation 1. **Market:** Slag Brothers turf.
- **Theme:** Armor. **Growth a level:** health ×1.12, armor ×1.29, shields ×1.11.
- **Common mutants:** Platehide, Leaker. **Extra drops:** Scrap Metal ×2.
- **Sets:** Boiler Room, Hot Plate. **Still blueprints:** none. **Exotic material:** Slag Heart (threat 10).

#### Glow Crater
Glow Cult turf. Shields everywhere; bring Ion Gel.
- **Unlock:** needs the truck's engine at level 1. **Market:** Glow Cult turf.
- **Theme:** Shield. **Growth a level:** health ×1.18, armor ×1.1, shields ×1.24.
- **Common mutants:** Leaker. **Extra drops:** Chemicals ×2.
- **Sets:** Tesla Coilworks. **Still blueprints:** Capacitor Stack (threat 4). **Exotic material:** none.

#### Reactor Row
Reactor Choir turf. Cooling towers hum hymns; leakers drift between them.
- **Unlock:** needs Glow Cult reputation 1. **Market:** Reactor Choir turf.
- **Theme:** Shield. **Growth a level:** health ×1.18, armor ×1.1, shields ×1.24.
- **Common mutants:** Leaker, Platehide. **Extra drops:** Chemicals ×2.
- **Sets:** Meltdown. **Still blueprints:** Glow Vat (threat 12). **Exotic material:** none.

#### The Neon Strip
Neon Saints turf. Casino signs that never went dark; creepers under every one.
- **Unlock:** needs Reactor Choir reputation 1. **Market:** Neon Saints turf.
- **Theme:** Shield. **Growth a level:** health ×1.18, armor ×1.1, shields ×1.24.
- **Common mutants:** Leaker, Creeper. **Extra drops:** Chemicals ×2.
- **Sets:** none of its own. **Still blueprints:** none. **Exotic material:** Isotope Seed (threat 10).

#### Static Fields
Storm Callers turf. Lightning rods to the horizon; shielded behemoths walk through the strikes.
- **Unlock:** needs Neon Saints reputation 1. **Market:** Storm Callers turf.
- **Theme:** Shield. **Growth a level:** health ×1.18, armor ×1.1, shields ×1.24.
- **Common mutants:** Leaker, Behemoth. **Extra drops:** Chemicals ×2.
- **Sets:** Walk-In Freezer. **Still blueprints:** none. **Exotic material:** Ion Crystal (threat 10).

#### Sewer Delta
Sewer Kings turf. Meat-heavy mutants grow huge.
- **Unlock:** needs Rust Barons reputation 1. **Market:** Sewer Kings turf.
- **Theme:** Health. **Growth a level:** health ×1.24, armor ×1.14, shields ×1.13.
- **Common mutants:** Behemoth, Creeper. **Extra drops:** Mutant Bits ×2.
- **Sets:** Glacier Works. **Still blueprints:** Bog-Gas Fermenter (threat 3). **Exotic material:** none.

#### The Flesh Farms
Meat Ranchers turf. Pens of mutant cattle that got loose; the behemoths are the bulls.
- **Unlock:** needs Sewer Kings reputation 1. **Market:** Meat Ranchers turf.
- **Theme:** Health. **Growth a level:** health ×1.24, armor ×1.14, shields ×1.13.
- **Common mutants:** Behemoth, Drudge. **Extra drops:** Mutant Bits ×2.
- **Sets:** Deep Fryer, Whole Hog. **Still blueprints:** Deep-Fry Drum (threat 12). **Exotic material:** none.

#### Fungal Bog
Spore Mothers turf. Knee-deep mushrooms; drudges sprout from the mud.
- **Unlock:** needs Meat Ranchers reputation 1. **Market:** Spore Mothers turf.
- **Theme:** Health. **Growth a level:** health ×1.24, armor ×1.14, shields ×1.13.
- **Common mutants:** Drudge, Leaker. **Extra drops:** Mutant Bits ×2.
- **Sets:** Slow Cooker. **Still blueprints:** none. **Exotic material:** Napalm Amber (threat 10).

#### Bloat Marsh
Gluttons' Court turf. A swamp of rendered fat; the biggest behemoths wallow here.
- **Unlock:** needs Spore Mothers reputation 1. **Market:** Gluttons' Court turf.
- **Theme:** Health. **Growth a level:** health ×1.24, armor ×1.14, shields ×1.13.
- **Common mutants:** Behemoth, Platehide. **Extra drops:** Mutant Bits ×2.
- **Sets:** Potluck. **Still blueprints:** none. **Exotic material:** Tallow Brick (threat 10).

### Factions
Each faction owns a destination's market. They like a taste (spicy / sweet / savory, 0 to 5), pay ×1.25 for their favourite cut, and reward reputation. Reputation comes only from selling them a sauce that fits better than ×1; it doesn't raise prices, it unlocks things.

| Faction | Who | Turf | Ideal taste | Favourite cut | Rival | Reputation rewards |
|---|---|---|---|---|---|---|
| Bazaar Hagglers | Swap-meet traders | The Junk Bazaar | 3 / 3 / 2 | Drudge Shank | Mallrat Gangs | 1: Shows you the way to the Dead Drive-In<br>2: Recipe: Haggler's Hash Rub<br>3: Sells Marrow Butter<br>4: Slow Cooker blueprints |
| Reel Cult | Film-loop preachers | Dead Drive-In | 1 / 4 / 3 | Creeper Drumettes | none | 1: Shows you the way to the Food Court<br>2: Recipe: Buttered Popcorn Glaze<br>3: Sells Glowberry Syrup<br>4: Moonshine Run blueprints |
| Mallrat Gangs | Escalator raiders | The Food Court | 3 / 2 / 4 | Leaker Belly | Bazaar Hagglers | 1: Recipe: Food Court Teriyaki<br>2: Sells Ghost Chili Paste<br>3: Sells Glowberry Syrup<br>4: Moonshine Run blueprints |
| Rust Barons | Scrap warlords | Rust Flats | 4 / 1 / 3 | Platehide Ribs | The Ironsides | 1: Shows you the road into the Sewer Delta<br>2: Recipe: Baron's Brimstone Rub<br>3: Sells Glowberry Syrup (the Glow Cult loves it)<br>4: Boiler Room blueprints |
| Tin Monks | Junk-welding hermits | Scrap Mountain | 3 / 1 / 4 | Platehide Ribs | Slag Brothers | 1: Shows you the way to the Tank Graveyard<br>2: Recipe: Solder Salt Rub<br>3: Sells Marrow Butter<br>4: Bandolier blueprints |
| The Ironsides | Tread-riding road warriors | Tank Graveyard | 5 / 1 / 2 | Behemoth Brisket | Rust Barons | 1: Shows you the way to the Smelter Pits<br>2: Recipe: Diesel Pepper Dust<br>3: Sells Ghost Chili Paste<br>4: Grease Fire blueprints |
| Slag Brothers | Furnace-stoking cultists | Smelter Pits | 4 / 2 / 3 | Platehide Ribs | Tin Monks | 1: Recipe: Slag Sear<br>2: Sells Ghost Chili Paste<br>3: Sells Marrow Butter<br>4: Boiler Room blueprints |
| Glow Cult | Radioactive zealots | Glow Crater | 1 / 4 / 2 | Leaker Belly | Reactor Choir | 1: Recipe: Halo Honey Glaze<br>2: Sells Marrow Butter (the Sewer Kings love it)<br>3: Tesla Coilworks blueprints<br>4: Hellmouth blueprints |
| Reactor Choir | Hymn-singing technicians | Reactor Row | 1 / 5 / 1 | Leaker Belly | Glow Cult | 1: Shows you the way to the Neon Strip<br>2: Recipe: Hymnal Honey<br>3: Sells Glowberry Syrup<br>4: Meltdown blueprints |
| Neon Saints | Casino ghouls | The Neon Strip | 2 / 4 / 3 | Creeper Drumettes | Storm Callers | 1: Shows you the way to the Static Fields<br>2: Recipe: Neon Candy Glaze<br>3: Sells Glowberry Syrup<br>4: Meltdown blueprints |
| Storm Callers | Lightning-rod nomads | Static Fields | 4 / 3 / 1 | Drudge Shank | Neon Saints | 1: Recipe: Ozone Rub<br>2: Sells Ghost Chili Paste<br>3: Sells Glowberry Syrup<br>4: Tesla Coilworks blueprints |
| Sewer Kings | Underground mutant royalty | Sewer Delta | 2 / 1 / 5 | Behemoth Brisket | Meat Ranchers | 1: Recipe: Royal Marrow Gravy<br>2: Sells Ghost Chili Paste (the Rust Barons love it)<br>3: Glacier Works blueprints<br>4: Grease Fire blueprints |
| Meat Ranchers | Mutant cattle barons | The Flesh Farms | 2 / 2 / 5 | Behemoth Brisket | Sewer Kings | 1: Shows you the way to the Fungal Bog<br>2: Recipe: Rancher's Red-Eye Gravy<br>3: Sells Marrow Butter<br>4: Deep Fryer blueprints |
| Spore Mothers | Mushroom matriarchs | Fungal Bog | 1 / 3 / 4 | Drudge Shank | Gluttons' Court | 1: Shows you the way to Bloat Marsh<br>2: Recipe: Spore Butter Baste<br>3: Sells Marrow Butter<br>4: Slow Cooker blueprints |
| Gluttons' Court | Swollen swamp nobles | Bloat Marsh | 3 / 4 / 3 | Behemoth Brisket | Spore Mothers | 1: Recipe: Gluttony Glaze<br>2: Sells Glowberry Syrup<br>3: Sells Marrow Butter<br>4: Grease Fire blueprints |

**Rival factions** (v0.9.28). Factions pair off within a theme (the Reel Cult stands alone): the Bazaar Hagglers and the Mallrat Gangs; the Rust Barons and the Ironsides; the Tin Monks and the Slag Brothers; the Glow Cult and the Reactor Choir; the Neon Saints and the Storm Callers; the Sewer Kings and the Meat Ranchers; the Spore Mothers and the Gluttons' Court. Reputation earned by fighting on a turf (runs and crew trips; not sales or contracts) costs the rival 34% of it, though a rival never drops below the threshold of the level it holds, and its favor is untouched. A faction at level 4 sells its rival's exotic blueprints at ×2 the favor, paid in its own favor.

Reputation levels 1 to 4 need 20, 60, 150, 400 points. Three things earn it:
- **Fighting on their turf:** getting out of a run at a faction's destination earns 0.03 for every mutant killed there (an elite counts 3; an ordinary mutant counts for the ones it stands in for, see Runs). A threat-16 run brings home about 84.
- **The crew:** a cat's trip there earns 50% of the same.
- **Selling there:** a cut sold earns 2 × (fit - 1) points when the fit is over ×1.
- Every point also earns a point of **favor** with that faction, to spend on exotic blueprints (see Exotic parts) and on re-rolls at the Refine tab (v0.9.14, with the truck parked on its turf) without losing reputation.

## Meat, sauce and selling

### Cuts

| Cut | From | Base value | Favourite of |
|---|---|---|---|
| Creeper Drumettes | Creeper | ◆0.6 | Reel Cult, Neon Saints |
| Drudge Shank | Drudge | ◆1.2 | Bazaar Hagglers, Storm Callers, Spore Mothers |
| Leaker Belly | Leaker | ◆1.8 | Mallrat Gangs, Glow Cult, Reactor Choir |
| Platehide Ribs | Platehide | ◆2.1 | Rust Barons, Tin Monks, Slag Brothers |
| Behemoth Brisket | Behemoth | ◆5.4 | The Ironsides, Sewer Kings, Meat Ranchers, Gluttons' Court |

- A cut's value is its base × (1 + 0.45 × the threat level it dropped at).
- **Raw meat spoils:** it loses 10% of its value an hour, down to 20%. Each of the Pantry's first 5 levels halves that. Sauce it to stop the clock.
- The **Shoggoth Hatch** takes every raw cut at ×0.05 of its value: a dump for leftovers, not a business.
- **The Mystery Meat Farm** (v0.9.10, the yard's eighth plot): bought any time for ◆500, it grows **up to 100 raw cuts every 5 minutes**, a random mix of every cut worth what a threat-0 drop is, while you fight and while the game is closed. The BALANCE menu sets both numbers (MEAT FARM). v0.9.18: a harvest is never more than the pots can sauce in that time (one pot at kitchen 0: about 100 cuts), so the farm follows the kitchen instead of piling raw meat for the Shoggoth.

### The chef cat
- **Production > Kitchen > CHEF** hires a chef cat to run the kitchen. No fee up front: it takes **6% of every meat sale** for as long as it works there, and you can let it go any time.
- Whenever a pot is free and there's more raw meat than sauce on the way, it brews the best sauce it can from the recipes and ingredients you have, with the taste dials set as close as your dial upgrades reach, for the faction the truck is parked with (the one sell-to, v0.9.18). It sauces raw meat as sauces finish, the best-fitting sauce and the most valuable cuts first.
- **CHEF MODE** (v0.9.18, one switch): **MARKET** (brew what the turf pays most for; the contracts are yours) or **CONTRACTS FIRST** (every open contract first, then the market: what COOK AND DELIVER CONTRACTS did). Ingredient care and the surplus to the Shoggoth are always on; the parking keeps its own switch. The CHEF panel is three notes instead of five.
- It works on real time like the rest of the kitchen: while you fight and while the game is closed. You can still brew by hand.
- **PARKS THE TRUCK** (v0.9.11, on at first): the chef picks where the truck sells (parking it: the one sell-to). A reputation or favor goal's faction comes first (sales earn reputation); otherwise the open faction that pays the most for what's cooked and coming, after taste fit, its favourite cut and fatigue. It moves for 10% more, at most once a minute, and brews for whoever the truck sells to, with the fatigue on a taste counted, so it rotates tastes.
- **Ingredient care** (v0.9.11): it never brews with rare ingredients, or with what an open contract or your every-run feast needs, and it says once when it has nothing left it may use.
- **The surplus to the Shoggoth** (v0.9.11; always on since v0.9.18): raw meat past what the pots can sauce in an hour (v0.9.13; before, before it reached its spoilage floor, about 8 hours' worth) goes to the Shoggoth Hatch, the least valuable first.
- **CONTRACTS FIRST** (v0.9.10 as COOK AND DELIVER CONTRACTS; the chef's other mode since v0.9.18): for every faction's open contract it brews a sauce that meets the contract's taste, sauces that faction's cut with it, keeps those cuts out of the smoker and the contract's ingredient out of its other brews, and delivers the contract (paying its fee) as soon as everything is there, as long as the fee leaves what THE HANDS KEEP (v0.9.13; v0.9.16: the one reserve; v0.9.24: an amount, ◆5,000 today). A faction at the top reputation level is left to you (v0.9.14). The cuts have to come from somewhere: runs, the crew or the Mystery Meat Farm.

### Sauce
- **Brew** (Production > Kitchen): pick a recipe, fill its ingredient slots (one of each slotted ingredient per batch) and set the taste dials. A batch makes **60 portions** and takes 3 minutes (faster with Kitchen levels, which also add pots). One portion sauces one cut.
- A sauce's taste = the recipe's base + its ingredients, then the dials (v0.9.27: every 2 Sauce Kitchen levels let you nudge each taste by 1 more, to 3). Each taste caps at 5 (the Kitchen's levels 9 and 10 raise it, to 7).

| Recipe | Base taste (spicy / sweet / savory) | Ingredient slots | Value | Where |
|---|---|---|---|---|
| Basic Rub | 1 / 0 / 1 | 2 | ×1 | from the start |
| Backyard Glaze | 0 / 1 / 0 | 2 | ×1 | from the start |
| Baron's Brimstone Rub | 2 / 0 / 1 | 3 | ×1.1 | Rust Barons reputation 2 |
| Halo Honey Glaze | 0 / 2 / 1 | 3 | ×1.1 | Glow Cult reputation 1 |
| Royal Marrow Gravy | 1 / 0 / 2 | 3 | ×1.1 | Sewer Kings reputation 1 |
| Haggler's Hash Rub | 1 / 1 / 1 | 3 | ×1.1 | Bazaar Hagglers reputation 2 |
| Buttered Popcorn Glaze | 0 / 2 / 2 | 3 | ×1.1 | Reel Cult reputation 2 |
| Food Court Teriyaki | 1 / 1 / 2 | 3 | ×1.1 | Mallrat Gangs reputation 1 |
| Solder Salt Rub | 1 / 0 / 3 | 3 | ×1.1 | Tin Monks reputation 2 |
| Diesel Pepper Dust | 3 / 0 / 1 | 3 | ×1.1 | The Ironsides reputation 2 |
| Slag Sear | 2 / 1 / 1 | 3 | ×1.1 | Slag Brothers reputation 1 |
| Hymnal Honey | 0 / 3 / 0 | 3 | ×1.1 | Reactor Choir reputation 2 |
| Neon Candy Glaze | 1 / 2 / 1 | 3 | ×1.1 | Neon Saints reputation 2 |
| Ozone Rub | 2 / 1 / 0 | 3 | ×1.1 | Storm Callers reputation 1 |
| Rancher's Red-Eye Gravy | 1 / 1 / 3 | 3 | ×1.1 | Meat Ranchers reputation 2 |
| Spore Butter Baste | 0 / 1 / 3 | 3 | ×1.1 | Spore Mothers reputation 2 |
| Gluttony Glaze | 1 / 2 / 2 | 3 | ×1.1 | Gluttons' Court reputation 1 |

| Ingredient | Adds (spicy / sweet / savory) | Where |
|---|---|---|
| Rad Pepper | 2 / 0 / 0 | mutants and cats |
| Rust Salt | 1 / 0 / 1 | mutants and cats |
| Glow Honey | 1 / 2 / 0 | mutants and cats |
| Sludge Molasses | 0 / 2 / 1 | mutants and cats |
| Bone Marrow | 0 / 0 / 2 | mutants and cats |
| Mushroom Mash | 0 / 1 / 2 | mutants and cats |
| Glowberry Syrup | 0 / 4 / 1 | sold for ◆120 by Reel Cult (reputation 3), Mallrat Gangs (reputation 3), Rust Barons (reputation 3), Reactor Choir (reputation 3), Neon Saints (reputation 3), Storm Callers (reputation 3), Gluttons' Court (reputation 2); Sphynx, Siamese and Blue cats |
| Marrow Butter | 1 / 0 / 4 | sold for ◆120 by Bazaar Hagglers (reputation 3), Tin Monks (reputation 3), Slag Brothers (reputation 3), Glow Cult (reputation 2), Meat Ranchers (reputation 3), Spore Mothers (reputation 3), Gluttons' Court (reputation 3); Sphynx, Siamese and Blue cats |
| Ghost Chili Paste | 4 / 0 / 2 | sold for ◆120 by Mallrat Gangs (reputation 2), The Ironsides (reputation 3), Slag Brothers (reputation 2), Storm Callers (reputation 2), Sewer Kings (reputation 2); Sphynx, Siamese and Blue cats |

### Smoking
- The smoker holds 40 cuts, +40 per Smoker level. In a run it cooks (time survived / 90 s) of its load; if you die, the load comes out overcooked (×0.6).
- Between runs (and with the game closed) it smokes at 50% that speed, a batch at a time, loading itself from your sauced meat (the cuts worth most to the faction you sell to first: v0.9.18, one sell-to, the faction whose turf the truck is parked on; the MEAT panel's **SELL TO** buttons park it, and the smoker's own target picker is gone).
- **What the smoker gets through** (v0.9.85): one load a run, however long the run lasts (the load is done after 90 s), and one load every 180 s between runs. The pots sauce far more than that once runs go deep, so sauced meat piles up; it keeps (only raw meat spoils), and the smoker always takes the cuts worth most first. Sauced cuts of the same meat share one lot now: a long career's pile had come apart into thousands of small lots, and every load of the smoker sorted them all.
- **The chef waits for the smoker** (v0.9.88): while more sauced meat is waiting than the smoker gets through in an hour parked (800 cuts at your smoker's level), the chef neither sauces nor brews, and says WAITING FOR THE SMOKER. Raw meat past the chef's own keep still goes down the hatch.

### Faction contracts (v0.8.2)
- Every faction whose turf is open and whose reputation with you is level 1 or more posts one order at a time (Kitchen, **DEALS**): its favourite cut, sauced or smoked (not overcooked) with its strongest taste at its ideal minus one or more, some of one common ingredient, and a fee. Sizes grow with your best threat T (up to 30): 30 + 4 × T cuts, 10 + 2 × T of the ingredient (no more than your Pantry holds), ◆200 × T^1.5.
- **DELIVER** pays (1 + T/10) × 20 **favor** (v0.9.26; it was Flux) and 20 + 2 × T reputation (and with it favor). The next order comes 5 minutes later (the BALANCE menu's MARKET group sets it). **NEW ORDER NOW** swaps the order for another for 20 of that faction's favor.

### Feasts (v0.8.2)

| Feast | Cut | Ingredients | For the next run |
|---|---|---|---|
| Firebelly Chili | Platehide Ribs | Rad Pepper + Rust Salt | +10% stack damage for the run |
| Behemoth Roast | Behemoth Brisket | Bone Marrow + Mushroom Mash | +25% armor for the run |
| Frosted Shanks | Drudge Shank | Glow Honey + Rust Salt | 15% less heat for the run |
| Leaker Pie | Leaker Belly | Glow Honey + Sludge Molasses | +50% reputation from the run |

- Cooked in the Kitchen (**FEAST**) from 20 + 2 × T cuts of its kind (raw, sauced or smoked), 5 + T/2 of each ingredient and ◆50 × T^1.5 (T: your best threat, up to 30). The next run eats it (not the Gauntlet). **EVERY RUN** (on the feast, in the Kitchen; v0.9.17) cooks the one you pick before each run, yours and the 8-Ball's, whenever you have what it takes; not while a goal on the 8-Ball's list is saving Sprinkles, and not when it costs more than the last run's meat sold for (v0.9.84: on a young truck it ate more than a run earned).

### Selling
- Park the truck on a destination (Map tab, or SELL TO in the Kitchen's MEAT panel) to sell to its faction: the one sell-to (v0.9.18), which the smoker and the chef read too. **Smoked meat sells the moment it is smoked** (v0.9.26): a run's load sells as the truck gets home and the result says what it made; the between-runs smoker's loads sell as each finishes. The counter's speed, the drip and the glut are gone; each Serving Counter level adds +5% to every cut's price.
- **Price of a cut** = its value × the sauce's value × **fit** × favourite cut (×1.25) × the Serving Counter's levels.
- **Fit is three bands** (v0.9.26): a sauce within 1.5 taste points of what the faction wants (straight-line across spicy, sweet and savory) is **RIGHT** (×1.4), within 3.5 **NEAR** (×1), else **WRONG** (×0.7). The Map's faction panel shows what each wants and which band your sauces land in; the Kitchen says it as you set the dials. The neutral Outskirts market pays ×0.9 whatever the sauce. No fads, no fatigue: a faction wants what it wants, and selling it the same thing all day pays the same.

## The Smokehouse

The hub between runs. Tabs: **Loadout**, **Craft**, **Refine**, **Production**, **Map**, **Crew**; the cat counter is always on the right. **HIDE MAP** in Production folds the yard picture into a short list of the buildings and widens the panel.

### Loadout
- The seven part slots, the fuel in each tank, and armor. The preview pig rebuilds as you swap.
- **The score** (v0.9.86). A kit **holds threat N**: one number for the whole kit, at the place picked on the Map. The Loadout tab shows it under the kit's numbers, with where the Shoggoth was last forced home with that build there once it has flown it. A part in a list shows **+0.4** or **-1.2**: what wearing it in place of the part in its slot would do to that number. (Before, the list showed a share of the sheet's power, +12%, and the sheet called a kit that reaches threat 45 good for 21.6.)
  - **What it is.** The sheet's power (peak DPS, the share of the time it can fire, fuel, the fuel mix, reach) times what the sheet cannot see: a set's mechanics, the keystone, the exotic, the mutations. Each of those counts for what the lab found it worth on finished Showroom builds (five set pieces, the keystone and the exotic at T5, Malevolent, the half-step, temper +10): 2,880 flights, fitted 2026-11-22. It is an estimate: the fit's spread is about 2.84 threat levels on the Showroom's finished builds and about 3.68 on a build the lab has not flown (one standard deviation). A mutation's, a keystone's and an exotic's worths are read inside a build: the same kit with it and without. A set's worth also carries the strength of the builds it was flown on (a build is its set), so it tells a Showroom build's level better than it tells what one more piece adds.
  - **The scale.** The line from power to threat is the one the game has had since v0.7.0, so a kit with no set, keystone, exotic or mutation reads as it always did (a starter gun: about 6). Deep, the number is where the Shoggoth is forced home, not where the pig would die: the two part ways from threat 18 and are 6.4 levels apart from 28 on (the lab's finished kits, flown both ways).
  - **Your truck moves it.** The lab's pig has no legacy hit points and no feast, and it flew each build at its set's home. Every time the Shoggoth is forced home, the place's figure moves a third of the way to what that mark says (all the way the first time, never more than 15 levels), and a place with no mark of its own takes the others' middle. So the number settles on what your builds do on your truck; a part's +0.4 does not change with it.
  - **What goes by it:** the numbers on the list's rows; EQUIP BEST when no build is marked MINE; the stash list's MY KIT IS STRONGER WITH IT; IMPROVE AND SWAP (of two copies of a piece at the same level, the better is the one the kit holds more with; and a piece behind in level goes on as it is when the kit holds more with it, a set's next bonus say); the truck's AUTO call; and where the 8-Ball starts a build the Shoggoth has not flown (three minutes of threat under the number). MOST POWER and BEST FOR THE PLACE are gone (the picker went in v0.9.81).
  - **What it does not know:** how you play. The lab's pilot fires in short bursts and never overheats, so anything that pays for running hot or bleeding reads low. A mutation's worth is its average over thirty-six builds, not its worth on yours, and one that measured under nothing counts as nothing (two flights a build is not enough to call a mutation harmful). Anvil was flown alone, without the Fixated it needs. Where the pig dies moves in steps: bosses come every five levels and most kits die at one.

  What the lab measured, in threat levels: the same finished kit flown with the thing and without it, averaged over the Showroom builds that carry it (the number in brackets). Bosses come every five levels, so one build's figure moves in steps; the averages are steadier. The score's own weights are fitted to all the flights together and differ from these.

| What | Worth |
|---|---|
| Mutations (one worn alone, every build) | Fixated +1.0, Spreading +0.7, Chilling +0.6, Marked +0.6, Dregs +0.3, Overkill +0.3, Deadeye +0.2, Culling +0.2, Toxic +0.2, Opportunist +0.1, Backfire +0.1, Primed +0.1, Pent-Up +0.1, Volatile +0.1, Anvil 0.0, Steady Aim -0.1 |
| Keystones | Gatling Drum +3.7 (7), Flashpoint +2.9 (13), Can Opener +2.5 (5), Fever Grip +1.7 (5), Double Distill +0.9 (1), Feeding Frenzy +0.2 (3), Reaction Chamber -0.1 (2) |
| Sets: three pieces, four, five, over none (two builds each) | Oven Mitts +7.6 / +11.4 / +14.6, Test Kitchen +2.7 / +5.2 / +9.8, Moonshine Run +0.1 / +1.4 / +9.4, Potluck +1.6 / +3.3 / +7.8, Walk-In Freezer +2.1 / +4.1 / +6.3, Grease Fire +1.0 / +1.0 / +5.3, Last Call +0.3 / +0.8 / +5.1, Bandolier +0.4 / +0.5 / +4.7, Hellmouth +1.8 / +2.6 / +4.5, Tesla Coilworks +1.2 / +3.1 / +4.2, Hot Plate +1.7 / +1.4 / +4.2, Deep Fryer +1.5 / +4.5 / +4.1, Nutcracker +0.7 / +0.7 / +3.9, Glacier Works +1.4 / +1.8 / +3.8, Boiler Room +0.3 / +0.8 / +3.7, Meltdown +0.9 / +1.5 / +2.8, Slow Cooker +0.5 / +1.6 / +2.6, Whole Hog +0.4 / +0.3 / +0.9 |
| Exotics (the ones on Showroom builds) | Jelly Sieve +16.4 (1), Bog Mitt +7.1 (3), Schmaltz Aorta +5.6 (2), Batter Mitt +5.6 (4), Swamp-King Altar +3.7 (3), Rocket Altar +3.1 (2), Static Mitt +2.9 (2), Half-Life Altar +2.8 (3), Tallow Mitt +2.7 (2), Mash Mitt +2.6 (1), Capacitor Bellows +2.5 (1), Schmaltz Altar +2.4 (1), Forge-Heart Throat +2.3 (2), Slag Mitt +1.8 (1), Forge-Heart Altar +1.6 (2), Crucible Sieve +1.2 (1), Storm Crown +1.0 (1), Forge-Heart Crown +0.6 (1), Rocket Throat +0.5 (2), Half-Life Throat +0.1 (1) |

- **Loadouts:** save the gun under a name and put it back on later; copy or import a build code to share one; **ORDER THIS BUILD** makes a custom order from one (v0.9.18). Every 8-Ball order for you keeps one of its own, **ORDER: <NAME>**, kept up to date with the best you own for it (v0.8.8; orders for a cat keep none since v0.9.12).
- **Stash:** filter by worn, unworn, locked, unlocked, exotics, keystones, tier or quality (one or a range), slot or lane, one more test from a list (a behavior, an affix, a set, tempered, in a saved loadout, an order wants it, beats what you wear, a spare) and words typed into FIND (v0.9.55); the list sorts by slot, strongest, newest, most tempered or most affixes. **Lock** a part to protect it (**Space** locks or unlocks the selected part, here and in the Refine tab). **Scrap** a part (or **SCRAP SHOWN** for everything the filters show: the one bulk scrap since v0.9.17) for half of what went into it; a set piece is broken down for its faction's favor instead. Parts you wear, locked parts and parts in a saved loadout are never scrapped. SCRAP SHOWN takes keystones the list shows too (v0.9.12; lock one to keep it), but not exotics. **LOCK SHOWN** and **UNLOCK SHOWN** (v0.9.84), under SCRAP SHOWN, put your lock on everything the filters show or take it off, each with its count; a lock an order holds is left alone both ways.
- **Scrapping** returns 50% of the part's crafting materials (by quality) plus 1 + 2 per tier Scrap Metal, gives back half of the named materials that went into it (v0.9.88, every step to its tier) and gives Chemicals for Mutated (1) and Malevolent (5) parts.
- **EQUIP BEST** (top left of the Loadout tab): with the Magic 8-Ball holding an order, the best you have for that ad (its keystone, its lanes highest tier first, 4 of its set's pieces, its exotic upgrade and its fuels); otherwise the parts that give the kit the most **power** (the estimate the crew and the Shoggoth use), keeping a keystone you wear and any set bonus you've reached, leaving your fuels alone. It never takes a part off a cat. It is the one dressing button (v0.9.17): a Showroom ad's **EQUIP BEST: THIS BUILD** is it for that ad and whoever the ad is for, the Crew tab's **EQUIP BEST: ITS ORDER** and **EQUIP BEST: FREE PARTS** are it for a cat. They say which of the build's parts someone else is wearing (v0.9.7).
- **A blocked change says why** (v0.9.7): a fuel with no still, a mount the chassis doesn't have (v0.9.29: cats wear no parts, so none of a cat's). A red message names it.
- **The stash list's filters** (v0.9.55). Above the list: what it shows, TIER (to T5, or a range), slot or SET PIECES, lane, **QUALITY**, and **MORE**, one more test from a list: a behavior (any, none, an empty slot, or one by name), an affix by name, a top-quarter roll, an affix for a loaded fuel, a set, a + part, tempered or not, in a saved loadout or in none, wanted by an order, better than what you wear, a spare. The **FIND box** takes any words on a part (name, slot, lane, T5, quality, affix, behavior, set). **SORT** orders the list by slot, strongest, newest, most tempered or most affixes. The corner says how many parts are shown, CLEAR goes back to all of them, and SCRAP SHOWN scraps what the filters leave.
- **The loot filter is gone** (v0.9.89). Nothing drops a part since v0.9.88, so there was nothing left for it to filter. With it went its rules and ready-made filters, the 8-BALL tab's LOOT FILTERS page, the stash's condition search and saved views (they were built with the filter's rule editor), the coloured marks, FAILS LOOT FILTER, NO ORDER WANTS and FOUND, NOT CRAFTED among the stash's filters, the stash limit and its stops, SCRAP WHAT NO ORDER WANTS, the targeted-loot pick and A PART HUNT. An old save's filters, saved searches and marks are dropped as it loads, with a note; every part stays.

### Craft and Refine (the Workbench)
- **CRAFT tab, PARTS:** pick a slot and a tier, then a lane. A part costs ◆ plus its slot's material (6, 15, 35, 80, 180 for T1 to T5), and from T3 the slot's mutant material (v0.9.88: Materials and recipes, in Starting out). Workbench levels raise the odds of a better quality.
- **CRAFT tab, SET BLUEPRINTS:** buy set blueprints with the set's faction's favor and craft the pieces (they roll a lane at your best tier). **BENCH:** Workbench upgrades, quality odds and the lane blueprints you know.
- **REFINE tab:** filter the parts on the left (worn, unworn, on the crew, locked, in a loadout, with a behavior, below Malevolent; slot, lane, tier, quality, or an affix the part carries), pick one, and refine it on the right. **REFINE THIS PART** in the Loadout tab opens it there. **Favor re-rolls** (v0.9.14): next to REROLL and MUTATE, the same roll for the favor of the faction whose turf the truck is parked on: 100 × (1 + tier) favor for an affix (a T4 one: 500), twice that for the behavior; flat, with no escalation.
  - **Quality up** one step at a time (◆ and materials; Mutated to Malevolent costs ×0.4).
  - **Reroll** one affix (◆; the second affix you touch on a part adds materials, the third favor with the parked faction). Each try on the same affix costs 30% more, up to ×2.
  - **Optimize** an affix: +10% of its range toward the top, paid in the slot's material.
  - **Mutate**: pick the mutation you want from the list (v0.9.88; it was a roll), or add one at Mutated quality and up, for 9 of that mutation's mutant material and Chemicals: 10 (T1 and T2), 20 (T3), 40 (T4).
  - (v0.9.26: it was Mutagen: 1, 2 and 4.
  - **Re-forge** a part into another lane of its slot that you know, keeping its tier, quality, affixes and behavior, for twice the tier's material and a quarter of the part's price.
  - **Temper** (v0.8.2) a Malevolent T4 or T5 part, +1 to +10: each level lifts its primary stat, its lane's benefit lines and its affix rolls (+2% for the first level, a little less each level after, ×1.16 at +10). Level n costs ◆12,000 × 1.5^(n-1), 60 × n of the slot's material and 2 × 1.5^(n-1) × 10 Chemicals (v0.9.26: it was Mutagen; v0.9.24: no Shards and no Flux any more). A tempered part shows +n after its name.

### The yard and the shack

| Upgrade | Where | What it does | Max level | First level |
|---|---|---|---|---|
| Workbench | Shack | Crafted parts roll higher qualities. Levels 9 to 14 climb to a 75% chance of Malevolent. | 8 (14 with the second band) | ◆250 + 5 Scrap Metal |
| Sauce Kitchen | Shack | More brewing pots (1 + level/2), faster brews, and the taste dials reach 1 further every 2 levels (to 3). Levels 9 and 10 raise the taste ceiling past 5. | 8 (14 with the second band) | ◆250 + 6 Mutant Bits + 3 Chemicals |
| Pantry | Shack | +20 ingredient storage per type per level (+50 a level past 8), and each of the first 5 levels halves how fast raw meat spoils. | 8 (14 with the second band) | ◆200 + 4 Mutant Bits + 2 Chemicals |
| Storage Shed | Yard | +150 storage for each material per level (+600 a level past 8). | 8 (14 with the second band) | ◆200 + 8 Scrap Metal |
| Salvage Yard | Yard | Sifts, renders and drips +6 of every material per hour per level (+18 a level past 10). | 10 (16 with the second band) | ◆700 + 5 Scrap Metal + 5 Mutant Bits + 5 Chemicals |
| Catnip Plant | Yard | Cats arrive 25% faster per level. | 10 (16 with the second band) | ◆100 + 3 Mutant Bits |
| Smoker | Garage | +40 cuts cooked per run per level. | 10 (16 with the second band) | ◆250 + 6 Scrap Metal |
| Engine | Garage | Range: reach farther destinations. | 5 | ◆500 + 20 Scrap Metal |
| Serving Counter | Garage | Every cut sells for 5% more per level. | 10 (16 with the second band) | ◆200 + 5 Mutant Bits |
| Crew Training | Cats | Every crew cat holds 2 threat levels more on its expeditions per level. | 10 | ◆400 + 6 Mutant Bits + 4 Scrap Metal |
| Bigger Counter | Cats | +5 cats can wait in line per level. | 6 (12 with the second band) | ◆150 + 3 Scrap Metal |
| High-Five Machine | Cats | A spring-loaded paw high-fives the cat on the counter by itself (offline too): at half the rate cats arrive, three quarters at level 2, as fast as they come at level 3. Its high fives pay the plain amount; yours pay half again as much. Coats you pick are set aside on a shelf for you. | 3 | ◆3,000 + 40 Scrap Metal + 20 Mutant Bits |

Prices in ◆ rise with each level; materials rise a step each level.

- **The second band** (v0.8.2; v0.9.27: six levels, was ten, and no Shards). The Kitchen, Pantry, Storage Shed, the Salvage Yard, the Catnip Plant, the Smoker, the Serving Counter and the Bigger Counter go 6 levels past their old top at steep prices: level max+k costs the last old level's ◆ × 2 × 1.25^(k-1), plus 60 × k of each of the building's materials. Each level does what the building's levels always did (the Shed adds 600 storage a level there, the Pantry 50, the Salvage Yard 18 of each material an hour; the Kitchen's levels 9 and 10 raise the taste ceiling). The Overseer buys them too.
- **Folded buildings** (v0.9.27). The Freezer is the Pantry's first 5 levels (each halves how fast raw meat spoils); the Spice Rack, Sugar Press, Stock Pot and Flavor Overdrive are the Sauce Kitchen's levels; the Scrap Sifter, Rendering Vat and Sludge Drip are one Salvage Yard that makes all three materials. An older save gets the Sprinkles it spent on them back, and its vats' highest level as the Yard's.
- **Storage** (v0.8.2: for everything). Each material holds 150, +150 per Storage Shed level, and each ingredient 20, +20 per Pantry level. Runs, crew trips, scrapping, cats and vats all stop at these: what doesn't fit is **sold** for 0.25 Sprinkles a unit of material and 1 an ingredient (the result screen says STORAGE FULL). What you already hold past a cap is kept.

### While you're away
Brewing, the vats, spoilage, fatigue, cats, the smoker, sales and crew trips all run on real time and catch up when you come back.

## Cats and the crew

### The cat counter
- Stray cats line up at the counter, one every 20 s (25% faster per Catnip Plant level). Up to 10 wait in line, +5 per Bigger Counter level.
- **Coming next** (v0.9.29). The counter shows the next 3 coats on their way, rolled ahead, so a Blue or a Cinder cat coming up is something to wait for (RARE!). Switching lures re-rolls them.
- **High five** the cat at the front for what it brings, or **hire** it for your crew.
- **High-Five Machine** (◆3,000 + 40 Scrap Metal + 20 Mutant Bits for the first level, three levels, at the counter): high-fives the cat at the front by itself, offline too: at half the rate cats arrive, three quarters at level 2, as fast as they come at level 3. Its high fives pay the plain amount; yours pay 50% more. Coats you pick are **set aside on its shelf** (3; v0.9.50), where a click sends one to the front of the line to high-five or hire; it stops only when the shelf is full. There is no off switch.
- **What a high five pays** (v0.9.50, from scratch). Every coat has a small table and pays one line of it. A common cat pays about 3% of what a run brings: Sprinkles against what your runs' meat sells for, materials against what your runs bank (a moving average of your runs, at its highest so far, so it keeps pace with you and never drops). Ingredients, favor, Blueprint Shards and exotic material grow with your best threat. Material over the Shed's cap is sold, as everywhere.
  - **Persian cat** (23%): sprinkles / meat boost / drudge knuckle.
  - **Tabby cat** (14%): scrap metal / platehide scute / sprinkles.
  - **Moss cat** (12%): chemicals / leaker gland / ingredients.
  - **Six-eyed cat** (12%): mutant bits / creeper sinew / scrap metal.
  - **Sphynx cat** (12%): ingredients / rare ingredients / behemoth tusk.
  - **Siamese cat** (6%): rare ingredients / favor / a place's material.
  - **Blue cat** (4%, rare): favor / a place's material / rare ingredients.
  - **Crimson cat** (4%, rare): a place's material / exotic material.
  - **Veined cat** (4%, rare): chemicals / material boost.
  - **Cyclops cat** (4%, rare): material boost / exotic material.
  - **Spirit cat** (3%, rare): exotic material / a trophy.
  - **Cinder cat** (1%, rare): pick of three.
- **Rare coats** grow likelier with your best threat: twice as likely at threat 30, three times at 60. **No cat brings a part** (v0.9.88): the common coats can bring their own mutant material, the Siamese, Blue and Crimson cats the material of **the place set on the Map**, the Spirit cat that place's trophy. **Boosts** are for your next run that gets out, up to 5: MEAT is +20% value on that run's raw meat, MATERIAL is 2 more of that run's place's material. The **Cinder cat** offers three: 5 of the trophy of the place set on the Map, a pile of exotic material, or one Black Ichor. Now and then a **golden cat** stops at the counter for a minute, worth 10 high fives; the machine leaves it for you.

| Cat | High five brings | How often | Knack on the crew |
|---|---|---|---|
| Persian cat | sprinkles / meat boost / drudge knuckle | 23% | Brings home 25% more meat |
| Tabby cat | scrap metal / platehide scute / sprinkles | 14% | +50% Scrap Metal |
| Moss cat | chemicals / leaker gland / ingredients | 12% | +50% Chemicals |
| Six-eyed cat | mutant bits / creeper sinew / scrap metal | 12% | +50% Mutant Bits |
| Sphynx cat | ingredients / rare ingredients / behemoth tusk | 12% | Twice the sauce ingredients |
| Siamese cat | rare ingredients / favor / a place's material | 6% | 1 in 4 ingredients it finds is a rare one |
| Blue cat | favor / a place's material / rare ingredients | 4% | Brings twice the place's material |
| Crimson cat | a place's material / exotic material | 4% | Brings 50% more mutant materials |
| Veined cat | chemicals / material boost | 4% | Elite Chemicals from threat 10 (not 15), twice as often |
| Cyclops cat | material boost / exotic material | 4% | 25% more meat and 25% more mutant materials |
| Spirit cat | exotic material / a trophy | 3% | Exotic materials drop twice as often on its trips |
| Cinder cat | pick of three | 1% | Brings the place's trophy: about one every four hours out |

**Lures** (bought once, one active at a time) make one coat show up ×3 as often; a coat's lure is sold once you have high-fived that coat (v0.9.50):
- **Brushed Yarn** (◆250): Persian cats show up 3x as often.
- **Laser Pointer** (◆250): Tabby cats show up 3x as often.
- **Moss lure** (◆250): Moss cats show up 3x as often.
- **Six-eyed lure** (◆250): Six-eyed cats show up 3x as often.
- **Glowing Fish** (◆250): Sphynx cats show up 3x as often.
- **Siamese lure** (◆250): Siamese cats show up 3x as often.
- **Blue lure** (◆250): Blue cats show up 3x as often.
- **Crimson lure** (◆250): Crimson cats show up 3x as often.
- **Veined lure** (◆250): Veined cats show up 3x as often.
- **Cyclops lure** (◆250): Cyclops cats show up 3x as often.
- **Spirit lure** (◆250): Spirit cats show up 3x as often.
- **Cinder lure** (◆250): Cinder cats show up 3x as often.

### The crew
- Hire up to **3 cats** off the counter: ◆300, ◆2,000, ◆8,000 for the first, second and third. Its coat is its knack (table above).
- **Cats wear no parts** (v0.9.29). A cat's strength on its trips is three things: the **Crew Training** building at the cat counter (every cat holds threat 4 + 3 a level, to 34 at level 10; the Overseer's cat counter group buys it), its coat's knack, and a **trait** it rolls when hired, shown on its card and the Crew tab:
  - **Brave**: Holds 3 threat levels more.
  - **Glutton**: Brings home 50% more meat, holds 1 level less.
  - **Scrounger**: Brings 50% more place and mutant materials.
  - **Sprinter**: Short trips (15 and 60 minutes) get half again as many kills.
  - **Nightcat**: Long trips (4 and 8 hours) get a third more kills.
  - **Plated**: Holds 3 levels more on the Armor maps.
  - **Shielded**: Holds 3 levels more on the Shield maps.
  - **Wader**: Holds 3 levels more on the Health maps.
  Builds are yours alone: an order is never for a cat, and parts an older save's cats wore are back in the stash.
- **Expeditions:** send a cat to an open destination at a threat up to your best, for 15 minutes, 1 hour, 4 hours, 8 hours. It fights on its own (also with the game closed) and brings home meat, Scrap, Bits, Chemicals, ingredients and elite Chemicals as a run would, and **named materials by the hour** (v0.9.88; no parts): each hour out 1 of the place's material and 3 mutant materials of the kinds that live there, twice that from threat 30. No trophies and no Black Ichor: a cat fights no boss (a hired Cinder cat is the exception for trophies). Longer trips bring more meat, but less a minute.
- The planner shows the threat the cat should hold there, the **odds** of a clean trip (3% to 97%) and the expected haul. A trip that goes wrong brings home 20% to 60% of the haul, and the cat rests for a while (25% of the trip, at least 10 minutes).
- **RECALL** brings a cat home early with a quarter of the haul.
- The **chef cat** is a separate hire, in Production > Kitchen > CHEF (see Meat, sauce and selling).

### The Overseer
- A big floating eye over the Production yard (or THE OVERSEER at the top of the folded list). Click it to wake it (no fee) and it **buys Production upgrades for you**: from its groups in the order you set on 8-BALL > YARD (v0.9.38), the cheapest thing first within a group, at most one every 4 s, never touching the share of your Energy Sprinkles the hands keep back (8-BALL tab).
- You pick what it may buy (8-BALL > YARD): **stills** (building a still for a blueprint you own, still and tank levels, levels of attachments you've fitted, yard expansions; never a new attachment), **the shack**, **the yard**, **the garage** and **the cat counter** (v0.9.27: the kitchen dials folded into the kitchen). Its panel shows what it buys next (or saves up for), and what it has bought and spent.
- It works while the game runs, runs included (quietly; it's in the debug log), not while the game is closed. Switch it off or close its eye any time.

## Automation: the 8-Ball and the hands

Every automation setting is on the **8-BALL** tab. Hands are still hired where they live: the **Magic 8-Ball** on the 8-BALL tab (or the Map's 8-Ball line), the **chef cat** in Production > Kitchen > CHEF, the **Overseer** by clicking its eye over the yard. **High fives** are yours, or the **High-Five Machine**'s at the cat counter (v0.9.7).

### The Magic 8-Ball
- Hire it (no fee) and switch it on with its switch or **B** anywhere. 8 s after you're back in the Smokehouse (with no menu open) it starts a run, with the Shoggoth driving (its truck setting applies; the Shoggoth's fee too). The result screen goes back by itself after 6 s and it goes again. B in a run switches it for the runs after this one.
- **The wait and the stops** (v0.9.38, RUNS). The wait before a run is 3, 8, 15 or 30 s. It also waits while you type (a custom order's name, a loadout's) or have a drop-down list open; **HOLD 8-BALL** (top of the screen) holds it until you resume, and while it counts down **FIGHT is GO NOW**. A run you start yourself (8-Ball off, held, or FIGHT with the Gauntlet armed) is **your run**: you drive unless SHOGGOTH REMOTE CONTROL is on, and the result screen waits for you. It can **stop itself**: STOP AFTER THE NEXT RUN, or after 5, 10, 25 or 50 runs (v0.9.89: the stash limit and its stop went with dropped parts). When it stops, pauses a goal or finishes one there is a meow, and the message stays on the FIGHT button until you click it.
- **While you were away** (v0.9.38): the 8-BALL tab shows what the hands did since you last clicked or pressed a key in the Smokehouse: runs and deaths, materials won and parts built, Energy Sprinkles in and out, what the Overseer bought, goals finished and what is waiting on you. GOT IT clears it. It isn't saved.
- It works **its list of goals**: with one goal it can work, that one; with two or more, **round in turn, a goal a run** (v0.9.24; top first before), so an order waiting on part luck doesn't hold the list, and an order farming parts never pauses on luck. A goal that can't move now (waiting on a fee, a full Shed, an offer) is skipped and says why. Each goal shows what it does next, a progress bar and its **budget**. Six kinds of goal to add (v0.9.24): a build, a reputation level, a map, a best threat, one of every exotic, Sprinkles; the rest (favor, a still, materials, Shards, one exotic, a blueprint, contracts) are steps the planner takes on the way.

### Two lists
- **The 8-Ball's list**: its runs work it. **Every cat has its own list** (v0.9.11): that cat's trips work it, with **CREW FARMS TOO** on (CREW), and (v0.9.29) every build order is yours. **<>** on a goal hands it to the next list (the 8-Ball's, then each cat's). A build, a best-threat goal or a still goal can't go on a cat's list: cats wear no parts, and trips don't raise your best threat or bring still blueprints.
- **Goals:** reputation with a faction (or **every open faction** to a level: the one furthest behind first), favor, opening a map (or every map), **a new fuel's still** (v0.9.6), Scrap, Bits or Chemicals, **exotic materials** (a stockpile of one: v0.9.6), **Blueprint Shards** (v0.9.6; gone in v0.9.26), an exotic part, an exotic blueprint, faction contracts (one faction or all, so many or keep going), a best threat (one place or anywhere), Energy Sprinkles, and builds (orders from the Showroom).
- **A best-threat goal's target** shows on the Map's START THREAT dial as **▲ GOAL n** while it's pushing there, and the Map's destination panel says where the 8-Ball's next run and each cat's next trip go (v0.9.18).
- **How a goal plans:** reputation and favor are fought for on the faction's turf, and a locked turf is opened first (back along the chain of factions, or by pushing your best threat, or by buying the truck engine). Materials: the open map that yields most of them (with the Shed full, the hands build it up first; past the biggest Shed, a full Shed is as done as it gets). Exotic materials: the material's home map (it drops there from threat 10, where your kit holds it, more a drop the deeper the run starts, and the map's boss drops a pile), opening the map first if it's shut. A new fuel's still: its blueprint (reach its threat at its map and get out: the run pushes there and starts the truck at it), then the still (opening two plots first if the yard is full; Sprinkles farmed first if they're short). Favor with a set's faction is also paid for **spare set pieces** broken down (a copy of a piece you have as good or better that nobody wears, no order or loadout wants and isn't locked). An exotic part: the reputation and favor for its blueprint, the blueprint, its material at its home (as above), then the craft (farming Sprinkles first if they're short). Contracts: the cut where its mutant is common (with the chef saucing for that faction), the ingredient where it's found, then the delivery. Sprinkles: meat from the deepest place the kit holds. What the hands can do without a run (buy the truck engine or a blueprint, craft the exotic, deliver a contract) they do between runs.
- **Budgets** (BUDGET on each goal, going round): until it's done (the default), 5, 10, 25 runs (trips for the crew), 15, 30, 60, 120 minutes of runs, or for a build **until every part it wears is at your top tier**. A goal whose budget is spent leaves the list.
- **An order's still or exotic is a goal of its own** (v0.9.23): the build's still blueprint is fetched by a run pushed to its threat, its exotic's reputation, favor and material count as the order's progress (an order used to pause after two runs that brought no part while that was being earned), and the hands build the still and buy and craft the exotic. With nothing left to farm and CRAFT off, the order says how many parts the 8-Ball could craft or re-forge for it (a set piece rolls a random lane, so a build's set and its lanes often need a re-forge to agree).
- **Saving up** (v0.9.23): a step that needs Energy Sprinkles (a still plot, a still, a bigger Shed, an exotic's craft) sets a target that holds still (the cost plus what THE HANDS KEEP of it), and while it's the 8-Ball's step the Overseer, the chef and the 8-Ball's own crafting spend nothing below it. An exotic short of Blueprint Shards farms them (spare set pieces broken down first) instead of waiting.
- **Held materials** (v0.9.38): the Scrap, Bits and Chemicals such a step costs are held too: the Overseer leaves them. With the 8-Ball off (and no crew farming) nothing is held: the reserve used to stick at the last price until a restart. After a death the turn passes to the next goal (the count of deaths is kept). A reputation goal for every faction stays with the faction nearest the level until it's there, then the next (it went to the furthest behind: a new map at start threat 0 every run). The log keeps 200 lines, filters by hand, and folds the Overseer's purchases into a line a minute.
- **When things go badly:** 2 runs in a row that don't move a goal (an order farming parts excepted, v0.9.24) **pause** it for 20 minutes (or until your kit's power is up 10%), and the next goal takes over. 2 deaths in a row **lower its threat by 1** (where the run starts and where the Shoggoth starts the truck) until the kit's power is up the same way; when it can't go lower the goal pauses. 2 crew trips in a row that go wrong pause a crew goal. II pauses a goal by hand; GO brings a paused one back now.
- **When a list is empty** (or every goal waits), v0.9.18: one idle for both, **HELP** or **STOP**. HELP: the 8-Ball farms the crew's first unmet order (a build for a cat) and a cat works the 8-Ball's goal; with nothing to help, either fights where reputation is **lowest**. STOP (STAY HOME for the cats) does nothing. Reputation, favor and exotic blueprints are goals you add (an older save's EXOTIC BLUEPRINTS idle becomes the **one of every exotic** goal). With no goal, 2 deaths in a row lower the 8-Ball's threat too, and when it can't go lower it switches off.
- **One of every exotic** (v0.9.18): a goal that works through every exotic part you don't own one of, start to finish. It picks the **nearest to crafted** (fewest stages left: reputation, favor, blueprint, exotic material, other materials, Sprinkles), with exotics for the **fuels you and the crew have loaded** before the rest, and runs that one as an exotic goal (farm the reputation and favor, buy the blueprint, farm the material, craft it), then the next. It ends when one of each is in the stash, on you or on a cat.
- **THE HANDS** row (v0.9.18, top of 8-BALL): every hand's hire and switch in one place: the 8-Ball (hire, on / off), the chef (hire), the Overseer (hire, on / off), the High-Five Machine (once built at the cat counter; its stops are set there) and HIRE A CAT (the next in the counter's line). The Map line, the Kitchen's CHEF panel, the eye and the counter still work as shortcuts.

### Runs
- **Where its runs start** (v0.9.76): where the build you wear lasts. The Shoggoth remembers, build by build and place by place, the threat it was last forced home at (the pig died, was hurt, or met a boss it could not stop), and the next run starts three minutes of threat under that, so a run lasts about that long. A build it has not flown there starts three minutes under what the score says the kit holds (v0.9.86; before, at the sheet's own figure, which read low enough to be its own margin), or three minutes under the mark of the build it flew there last, whichever is lower (v0.9.77). Never past the map's START THREAT dial, your best there minus 3 (which is where every run started before, whatever you wore). An instruction's own start stands: a number, COMFORT, or HIGH (the dial's top, whatever you wear). A best-threat goal starts the truck at its target, or at what the kit holds there if that's lower (AUTO stops 2 under what the kit holds); when the kit holds no more than your best, the goal waits for more power.
- **MY BUILD** (v0.9.81): one build on the 8-Ball's list is yours, marked **MINE** on its goal (or MY BUILD in the Showroom). The first build you order is marked for you. The 8-Ball's runs go for it, the hands raise and dress you by it, and EQUIP BEST on the Loadout tab puts it on. The other builds on the list **wait their turn** (v0.9.89): when MY BUILD is finished (every piece in, and nothing left for the hands to raise, roll or buy) the 8-Ball's runs go for the next build down the list and the hands build its pieces; when that one is whole it leaves the list and the one below takes its place. Until MY BUILD is finished no runs go for them. (The mark was WEAR. The five-way EQUIP BEST picker, EQUIP BEST AFTER EACH RUN and the saved loadout kept for every order are gone.)
- **The hands and your kit** (v0.9.81; one switch, on the Loadout tab and here): **OFF**, nothing automatic touches what you wear. **IMPROVE IN PLACE**, before and after its runs the 8-Ball raises the parts you wear, the weakest first, a step at a time, with what is over THE HANDS KEEP: a tier, the half-step, a quality, an affix's roll, temper; with MY BUILD marked also a re-forge to the lane the build names, a reroll toward an affix it asks for and the behaviors it seeks. It never changes which part is in a slot. **IMPROVE AND SWAP**, that, and it puts on MY BUILD's pieces: a better copy of a piece you wear, a piece of the build where you wear none, the build's part where yours is off its lane. A piece of the build is never traded for a different part. A new truck starts on IMPROVE AND SWAP; a save from before starts OFF. **v0.9.90: with a build marked MINE, IMPROVE AND SWAP works only on what is the build's.** A part the build is going to replace (the starter kit, a plain part where the slot's piece is owned) gets no quality, lane or affix work, and a set piece, keystone or exotic of another build is left as it is. A plain part holding a slot until its piece is built (a stand-in) gets its tier and its quality and nothing else. IMPROVE IN PLACE, which never changes a part, still raises any plain part you wear.
- **UNDO** (v0.9.81): the hands' last change to the kit is one line (THE 8-BALL: ...), and UNDO THE 8-BALL on the Loadout tab puts the kit back as it was and gives back what it cost.
- **BRING TO TOP** (v0.9.81): on a part in Refine, and BRING KIT TO TOP on the Loadout tab, with the cost shown first. Top is your Workbench's top tier, Malevolent, the half-step and temper +10. It does what you can pay for.
- **When every piece is in** (v0.9.81): MY BUILD's runs farm where meat pays, for the Sprinkles and materials raising it takes. (It farmed better rolls at the build's home; a roll is bought now.) The run line names the next step and what it costs (v0.9.84: the weakest part you wear, and what is done to it next). When nothing more can be raised and the kit has all the build asks, the 8-Ball says **MY BUILD IS FINISHED** once; MY BUILD stays on the list. If the kit still lacks something the hands cannot buy, the line says what. **v0.9.90, finished:** five set pieces, the keystone and the exotic, every part at its top tier, Malevolent and +10, with as many of the build's fuels loaded as its chassis has tanks (a Saddle Tank build needs only its first: 26 of the 36 Showroom builds could never be finished). The Smokehouse shows a card with the hours since it became MY BUILD and your best threat, the journal keeps a milestone, and the kit is saved as a loadout. Then the 8-Ball works the next build on the list; with none, it flies the finished build for depth at the place where your best threat is highest. While a piece is still to be built the line names it: NEXT, BUILD ... and what it costs.
- **A piece goes on only if it is as good** (v0.9.84). IMPROVE AND SWAP puts a piece of MY BUILD on over a part you wear only when the piece is at least as far along (tier, the half-step, quality, temper), or when the hands can pay to raise it to match: then they raise it first and put it on after. A piece they cannot bring level stays in the stash. Marking a build that would change your kit shows which parts would go on and asks again before it does. The hands change nothing while a run is on. **MY BUILD: NONE** is a choice and is kept when the game is started again. Exotics are raised like any other part.
- **Rolls are bought, for every build** (v0.9.84): no run goes looking for better rolls. MY BUILD's are raised where you wear them. For any other build on the list the hands buy what it asks of its own parts in the stash before a run: its lane, your top tier, the half-step and the quality if it asks for them, an affix it must have (a reroll), a must's roll. The part furthest behind first, a few steps a go, never under THE HANDS KEEP.
- **One copy of each piece** (v0.9.84): the 8-Ball keeps its lock on the best copy of each piece a build on the list names, and on nothing else. A worse copy it had locked is let go when a better one is built: unlocked and left in the stash (v0.9.89; while parts dropped it was scrapped). The parts of a build that leaves the list are let go and left where they are.
- **A place no build has flown** (v0.9.84): the 8-Ball's run starts 10 under the lowest threat your kit has lasted to anywhere else. (It started at 0: the START THREAT dial has no room at a place you have never been.) The first run there sets the mark the next ones go by.
- **Armor first** (v0.9.77): before a run the 8-Ball buys the next armor up from the best you own, as soon as you have its price, and puts on the best armor you own. THE HANDS KEEP does not hold armor back (v0.9.79: it is 5,000 on a new truck, which kept a pig bare for hours), nor does a list step that is saving up. **v0.9.90: the first two armors, then MY BUILD's first tier.** While tier 1 set pieces or plain parts of MY BUILD wait on Sprinkles alone (their materials and blueprint are in hand), or the still for its fuel does, they are paid for first, out of THE HANDS KEEP too; the third and fourth armor, the reserve and the Overseer come after. The Scrap, Bits and Chemicals those parts and that still ask are held too: the Overseer spends none of them and the hands buy no quality with them. (In eight test careers no kit had changed at hour 2, and the first boss died between hour 3.3 and hour 5.8.) A step at a time: Bottlecap Poncho 180, Hubcap Vest 420, Tire-Rubber Plate 950, Fridge-Door Cuirass 2200.
- **A build's slots** (v0.9.90): a Showroom build is five set pieces, a keystone and an exotic, one slot each. The hands keep the exotic's slot free of set pieces and build the exotic on the build's own lane for that slot; a plain part of that lane holds the slot until the exotic is built, and another holds the keystone's slot until the keystone is. (The hands used to put a set piece in the exotic's slot: seven test careers of eight built the exotic and never wore it.) A set piece an old save has in the exotic's slot stays on until the piece for the free slot is built and raised.
- **Only what a run can reach** (v0.9.90): the 8-Ball does not fly for a boss's trophy or Black Ichor while the Shoggoth's truck leaves before the first boss (threat 5), nor for a still blueprint's threat the kit does not hold. It flies for the next thing a run can bring, or for Sprinkles, and its line ends WAITING ON and what it has put off. With your own hands on the gun, with the truck on ONLY WHEN HURT, or once the Shoggoth has beaten a boss with the build, a boss's drops are in reach.
- **A boss the kit does not beat** (v0.9.90): a run flown for a boss's drop that kills no boss is a dry run. After 3 in a row at a place the step waits for a better kit: one the score says holds 1.5 threat levels more than the most the kit held where it failed. The 8-Ball's line says WAITING ON A KIT THAT HOLDS and the number. A theme's trophies and Black Ichor drop at several places: they are hunted where the kit can reach, and nowhere it holds less than where it failed. A boss killed at a place clears that place. After the pig dies somewhere, the threat the truck leaves at there rises as the kit's score does, so an early death is not a wall for good.
- **The set's pieces first** (v0.9.90): what a build's set pieces that are not built yet wait on comes before anything scarcer: the favor a piece's blueprint asks (flown for at the faction's turf), then their home's material. The keystone's trophies come after.
- **A map an order needs** (v0.9.80): when a step of an order drops at a map that is not open, opening it is the order's next job (the reputation, best threat or truck engine it takes), after any still or exotic the build lacks. It farmed "better rolls" before. v0.9.90: every such map is tried, in the plan's order, not the first alone. The truck engine's Sprinkles and materials are farmed and held, and with a build to work for it is paid out of THE HANDS KEEP like the first tier. A push past your best threat that the sheet doubts is flown until 3 in a row have not passed it.
- **Two orders, one set** (v0.9.80): a set piece that another order on the list wants on the lane it has now is not re-forged.
- **After a death** the Shoggoth leaves 1.5 levels under where the pig died, there and with that build: for 2 runs, and for twice as many each time it dies there again (v0.9.79; up to 16), until an ordinary run comes home from as deep.
- **The Shoggoth's settings** (your runs and the 8-Ball's): see Shoggoth Remote Control.
- **THE WEEKLY GAUNTLET** (off at first): its first run each week is this week's Gauntlet, once you can enter it. A Gauntlet death doesn't count against it.

### Builds
- **Orders.** Press **ORDER IT** on a Showroom ad and the 8-Ball works for that build (it's hired for free if it wasn't). A run goes for the first thing the build lacks that a run can get: a missing fuel's still blueprint (where it is found), then the named materials its recipes still ask for, the scarcest first and each where it drops (the set's home for its pieces, the places of the keystone's theme for the keystone), then the exotic's faction favor (at that faction's turf) and material (where it drops). The hands build each piece the moment its materials are in. With everything a run can bring in, what is left is bought, and the runs go where the meat pays.
- **Custom orders** (v0.8.8). **+ CUSTOM ORDER** on the Showroom tab starts a build of your own from the kit you wear; **CUSTOMIZE** on an ad starts one from that ad. Pick its set (or none) and how many pieces of it, 2 to 5 (v0.9.72: the list stopped at 4), keystone (or none), a lane for every slot, up to 3 affixes, up to 4 fuels (the first is the signature) and one exotic for any gun slot (its home map is its set's, or where you fight when it has none; v0.9.15), then **ORDER IT**: the 8-Ball farms, crafts and puts it on like any ad. **DELETE** throws it away with its orders. **ORDER THIS BUILD** on a saved loadout (Loadout tab) starts one from that loadout's parts and fuels (v0.9.18). Every list shows what each choice does, and the long ones filter as you type (v0.9.7); **WHAT YOUR PICKS DO** sums up the keystone, the set bonuses, the exotic and the mutations.
- **What an order asks of a part** (v0.9.47). In the custom builder each of a build's affixes is **NICE TO HAVE** (it breaks ties, as before) or **A MUST**: a slot only counts as filled by a part that has every MUST. MUST ROLL asks for any roll, the top half or the top quarter of the affix's range; QUALITY asks for a floor of Tuned, Mutated or Malevolent; + PARTS asks for the half-step; TEMPER TO has the 8-Ball temper the build's parts up to a level; and any slot can have **its own MUSTs** in place of the build's. The plan gains a step, PARTS WITH THE ROLLS IT ASKS FOR, farmed at the build's home; the 8-Ball never crafts for a roll (a crafted part's affixes are luck), it farms. A part that has what its slot asks ranks above a better quality without it, below a higher tier. An ad from the Showroom asks for nothing until you CUSTOMIZE it.
- **The 8-Ball's instructions** (v0.9.48). Besides goals it plans by itself, the list takes two you direct: **FARM A MAP** (runs there until you take it off, or for a number of runs) and **A KEYSTONE** by name (it flies for what the recipe lacks, the scarcest first, and builds it). A PART HUNT went in v0.9.89: nothing drops a part to hunt. Every instruction on the 8-Ball's list has its own **START** (PLAN, HIGH, COMFORT or a threat), **TRUCK** call (SAME as the Shoggoth's, AUTO, WHEN HURT or a threat), and **KIT** (a saved loadout worn for its runs; what you wore goes back on after), a **weight** (turns in a row when the list goes IN TURN) and an **ONLY WHEN** condition (Sprinkles or the stash under or over an amount, kit power a quarter above today's, or the instruction above it finished). RUNS sets the order of work (IN TURN or TOP FIRST), more stops (after so many minutes, when any instruction finishes), the numbers for runs that go wrong (runs before a pause, minutes paused, deaths before the threat drops and how far), shows **the next five runs**, and saves the whole list as a **program** you can load back or copy and paste as text. **MAKE IT THE STANDING INSTRUCTION** in the add form sets what the 8-Ball does when the list is empty or every instruction waits.
- **The 8-BALL tab** (v0.9.51; it was AUTOMATION) has two pages (v0.9.89: LOOT FILTERS went with the loot filter). **INSTRUCTIONS**: the lists and the hands. **ORDERS**: every build on order with its settings, what it still lacks, and the switches for what the 8-Ball builds for them. On an instruction, **KIT: AUTO** wears the strongest kit you own and loads the fuels that do most to what grows fastest on the map (armor, shields or health), and **FEAST** cooks a feast before each of its runs when you have what it takes. **ONLY WHEN** also takes a material under or over an amount.
- **The crew's one list** (v0.9.51). The cats share one list of goals. A goal says **ANY CAT WORKS IT**, or is **pinned** to one cat (press it to go round the crew): a pinned goal is worked by that cat only. Letting a cat go unpins what was its.
- **An order for one part** (v0.9.47). ORDER A BETTER ONE OF THESE on a stash part orders that one slot: its lane at your top tier, with the affixes it has as wants. The hands build and raise that one part, and it is met by one part.
- **STOPS WHEN MET or KEEPS IMPROVING** (v0.9.47, on the order's goal). A met order leaves the list, or stays and trades up. **LIMIT** is the order's budget in Sprinkles for the 8-Ball's crafting (none, 10,000, 50,000, 250,000 or 1,000,000); used up, the order only farms. The Workshop has a switch for each kind of work: craft set pieces, buy blueprints, craft lane parts, re-forge lanes, roll behaviors, craft the exotic, temper to the order's level.
- **CRAFT WHAT I CAN** (v0.9.7), on an ad and on an order card in 8-BALL: one click crafts everything the build still lacks that you can make and afford now (set pieces and their blueprints, lane parts at your top tier, re-forges onto its lanes, the exotic upgrade, the mutations it seeks). It spends freely and locks what it makes.
- **Mix and match sets** (v0.9.2). A custom build picks how many pieces of its set to wear (2, 3 or 4: each turns on one more bonus) and can add a **second set** with its own count, say 4 Grease Fire + 2 Glacier Works, or 2 + 2. Both counts together fit in the slots the keystone leaves (when they don't, the second set's count gives way first). The 8-Ball farms, crafts, re-forges and puts on pieces of both, never taking a slot from one set for the other.
- **Behaviors to seek** (v0.9.2 as mutations; v0.9.24: one layer, one word). An order can seek up to 7 behaviors (v0.9.18: one a slot) (Anvil, Backfire, Chilling, Culling, Deadeye, Dregs, Fixated, Marked, Opportunist, Overkill, Pent-Up, Primed, Spreading, Steady Aim, Toxic, Volatile). One part of the build with each is all a kit uses (they don't stack). Every part has one behavior slot: Mutated and Malevolent parts roll one 30% of the time, and Refine > **BEHAVIOR** rolls or changes one on any part for Chemicals (v0.9.54: on an exotic too). The order's plan adds a step for each, PUT IT ON swaps in a part of the build that carries one, an order isn't done until they're worn, and with **CRAFT FOR THE ORDER** on, the 8-Ball rolls a part of the build one roll at a time until it has the one sought (v0.9.55: the keystone and the exotic first, since they are never traded up). Every ad seeks the behavior that helped its build most in the lab.
- **Order loadouts** (v0.8.8). Every order keeps a saved loadout (v0.9.29: every order is yours), **ORDER: <NAME>** on the Loadout tab: the best kit you own for it right now (what the 8-Ball would put on), kept up to date as parts come in, are crafted or go. You can rename it. When the order is matched its loadout stays, as an ordinary one; cancel the order and its loadout goes too, unless you renamed it. Delete it while the order is on and that order keeps none. Like every saved loadout, its parts are never scrapped.
- **The order list**: every build you order is yours and goes on the 8-Ball's list (cats wear no parts since v0.9.29). X on the goal takes it off and removes its saved loadout, as CANCEL ORDER in the Showroom does.
- **Its parts and your kit.** What the hands build for a build on the list is **locked** (the best copy of each piece). The 8-Ball dresses you for **one build only: MY BUILD** (above); with none marked it **never touches your kit**. A build that is not MY BUILD is **done when you own its whole kit**: it leaves the list and its parts stay in the stash.

### Workshop
- **Building for its builds** (v0.9.89: always; CRAFT FOR THE ORDERS was a switch, off at first). Before and after each 8-Ball run the hands build what **the build that run is for** still lacks and can pay for (on a run for another kind of goal: MY BUILD, or the next build once it is finished): set pieces up to the count the build asks for (buying a piece's blueprint with the set's faction's favor first), a lane part for every slot, the keystone, the next tier of a part it owns (a tier a go), the exotic (its blueprint with favor, then the craft) and the mutations it names. What they make is locked. At most 6 things a go. On the ORDERS page a switch turns each kind of work off, and SPRINKLES LIMIT caps what the builds may spend.
- **TEMPER WORN PARTS** (off at first): before each 8-Ball run it tempers the Malevolent T4 and T5 parts you wear, the least tempered first.
- **The stash** has no limit, but past 500 parts the Smokehouse's lists slow down: you're warned when it goes over.

### One reserve
- **THE HANDS KEEP** ◆0, ◆1,000, ◆5,000 (the default), ◆25,000, ◆100,000 or ◆500,000 of your Energy Sprinkles (v0.9.24: an amount; it was a share of your cash, which made every hand's budget a fraction of a moving number): the 8-Ball (crafting, blueprints, the truck engine, tempering), the Overseer and the chef's contracts (v0.9.16) never spend into it. A step that saves up for a cost saves the cost plus this.

### The crew, the kitchen and the yard
- **CREW FARMS TOO** (CREW): the 8-Ball sends every idle, rested cat out by itself: each goes where its own list says, at the highest threat they're safe at, for the trip length you pick (15 minutes to 8 hours). Cats are only sent while the game runs.
- **KITCHEN:** the chef cat's status (a contract goal points it at that faction), and the feast cooked before every run, picked in the Kitchen's FEASTS panel (v0.9.17).
- **YARD:** the Overseer's switch, what it may buy and what it buys next (see Cats and the crew).
- **LOG:** what the hands did lately, newest first.

## Endgame

### Infested runs
Past threat **21** a run turns Infested:
- from threat 30 every named material drops in twos, from 40 in threes (v0.9.88; while parts dropped, their quality rose here);
- every level adds a **mutator** (below), and each one raises elite Chemicals. A run that starts past threat 21 gets one for every level it skipped. There are five, so the same mutator lands again, **three times at the most** (v0.9.88: when every one has landed three times, at threat 36, no more land; before there was no limit, and Armored Season's fourth landing made armor at an Armor place 190 times itself by threat 40). Elite Pack adds each time (3 times, then 5, 7: v0.9.84, it multiplied before), the others multiply (two Heat Waves: the gun cools at 49% of its speed; two Swarms: 2.25 times the mutants at 49% of the health);
- elites past threat 15 drop Chemicals, more with every mutator.

| Mutator | What it does |
|---|---|
| Armored Season | Armor grows 6% faster per level. |
| Elite Pack | Three times as many elites, as far as 40% of a wave; past that each elite pays for the rest in loot. A second pack makes it five times, then seven, nine. |
| Heat Wave | The gun cools 30% slower. |
| Static Front | Shields refill after 3 s without damage. |
| Swarm | Half again as many mutants, each with 30% less health. |

### The weekly Gauntlet
- Opens at best threat 20. Each week has one destination and 3 mutators, the same for everyone. Arm it with WEEKLY GAUNTLET on the Map and your next run is the Gauntlet: it starts at threat 20 with those mutators.
- The board keeps your best Gauntlet runs of the week (deepest threat, then longest time), by main fuel, with each run's build code to copy.

### Chemicals from elites, favor from sets
- **Elite Chemicals** (v0.9.26; Mutagen before): elites past threat 15 (12%) drop 10 Chemicals, scrapping a Mutated part gives 10 and a Malevolent 50 (Veined cats bring Chemicals too). Behaviors and tempers cost Chemicals.
- **Set favor** (v0.9.26; Blueprint Shards before): breaking down a set piece pays favor with the set's faction (its home map's), Siamese and Blue cats pay the parked faction. Set blueprints cost 30 favor with the set's faction.

### Where to push
- Compare destinations by their growth: the Rust Flats piles on armor, the Glow Crater shields, the Sewer Delta health. Bring fuels and parts that answer the pool that grows fastest there.
- The Shoggoth's AUTO truck setting uses an estimate of what your kit holds at a destination: a good guide to how deep to go.

## A New Truck (the prestige)

v0.9.21. A **New Truck** sells the truck and starts the Smokehouse over, keeping what you've learned and paying **Harry Berries** for how deep this truck went. Berries buy lasting buffs in the **Needless Complexity Emporium**. Each New Truck is a **Spicy Level**.

### Selling the truck
- **Esc > NEW TRUCK**, offered from best threat 20 (and not during a run). The sheet lists exactly what goes and what stays, with counts, and the Berries it pays; you type SELL to confirm. There's no undo (the slot's backup is the save before).
- **The first truck comes early** (v0.9.29). Your first new truck is offered from best threat 15, with a smaller purse while you're below 20: 1 Berry per 2 levels past 5 at your best map (5 at 15, 7 at 19) and nothing from the other maps, so the first reset is a decision an hour or two in and the Emporium's first lines get tried. From best threat 20 the first truck pays the full price like any other.
- **It pays** 1 Berry a threat level past 10 at your best map, 1 per 2 levels past 10 at every other map, and this week's Gauntlet score's levels past 20. A 26 / 18 / 14 career pays 22. The same career pays the same every time: the Emporium's rising prices are the brake.
- **What stays:** your recipes, the lane blueprints you've learned, your still blueprints (the stills themselves are rebuilt), the first 5 saved loadouts **as custom orders** (their lanes, set, keystone, affixes, behaviors and fuels; no parts cross: a new truck starts from an empty stash), your custom orders, the cats (their names and coats), every setting (THE HANDS KEEP, the idle modes, the Shoggoth's truck setting, the every-run feast, the High-Five Machine's coats; the 8-Ball's settings come back when it's hired again), the journal, the milestones, the Gauntlet board and the tabs you had open.
- **What goes:** every part, Sprinkles, favor, reputation, best threat and map unlocks, set and exotic blueprints, the buildings and plots, the stills, the meat, the goal lists, and the 8-Ball, the chef and the Overseer (hired again, free).

### The Needless Complexity Emporium
- On the Esc menu, and on the Smokehouse's top bar once you've sold a truck. Two trees, each line with 10 levels, a cost that climbs x1.5 a level (the first level of most lines is 1 Berry) and a **hard cap** shared with every other source (above). Every line is a multiplier on top of your parts, sets, keystones and feasts; the flamethrower sheet shows the lines you own as a HARRY BERRIES line. The whole Emporium is 824 Berries.
- **The flamethrower**, at the top of each line: Flow (+15% flow); Stack damage (+15% stack damage); Burn duration (+20% burn duration); Heat (-15% heat per unit); Cooling (+20% cooling); Heat cap (+20% heat cap); Tank capacity (+30% tank capacity); Fuel regen (+20% fuel regen); Range (+15% range); Swap time (-20% swap time); Hit points (+10 HP).
- **The economy**, at the top of each line: Meat value (+20% meat value); Counter price (+10% counter price); Reputation (+30% reputation and favor); Material drops (+20% material drops); Set favor (+40% set favor); Pot speed (+20% pot speed); The chef's cut (-5% chef's cut); Crew hauls (+30% crew hauls); Contract favor (+100 favor a contract); A fuller wallet (start with ◆10,000).
- **One-offs**, applied when a new truck starts: The farm comes along (20 Berries); The 8-Ball comes along (10 Berries); The chef comes along (15 Berries); The Rust Flats are open (10 Berries); A head start in the yard (15 Berries); One more loadout kept (20 Berries, 3 times).
- **RESPEC**, free once a Spicy Level: every line back to 0 and the Berries back in hand (the one-offs stay).

### The Cinder cat
- v0.9.88: at the counter it offers 5 of the trophy of the place set on the Map, a pile of exotic material, or one Black Ichor (v0.9.21: it brought keystones you didn't own yet). Hired, its trips bring the place's trophy, about one every four hours out.

## The Showroom (tested builds)

The Smokehouse's **SHOWROOM** tab sells flamethrowers. The ads are jokes; the builds are real: the balance lab's 36 finished builds, two for every set, all tested under the same balance (v0.9.41: rebuilt from scratch as five set pieces, a keystone and an exotic). It stocks 10 at a time, 2 of each style, with **new stock after every run**: it shows every ad of a style before it shows one again, so a new game and five runs show all of them; an ad on order stays listed until the order is done, and the guide below has them all. In the game each ad also checks its parts list against your stash, links to the set blueprints and the fuel's exotics, and has **ORDER NOW!**: the Magic 8-Ball's plan for the build, what you wear of it, **ORDER IT** (the 8-Ball then works for it: it flies for the materials the build lacks and builds its pieces; with an order already in hand, **ADD TO THE LIST**), **MY BUILD** (marks it as the one build that is yours), **EQUIP BEST: THIS BUILD** (puts on the best you have for it) and **CRAFT WHAT I CAN** (builds what you can pay for now). **CUSTOMIZE** (v0.8.8) starts a custom order from the ad, and **+ CUSTOM ORDER** one from the kit you wear: your own build, ordered like an ad.

**Reading an ad** (v0.9.41: rebuilt from scratch). A finished build is **5 pieces of one set, one keystone and one exotic**: a lane for every slot (the set pieces sit on the build's lanes), a keystone (the Miser builds borrow one), the exotic in the slot the ad names, its fuels (the first is the signature) and three affixes worth hunting on every part. **Lab** is the threat a robot pig held at the build's home map, starting at threat 16, with every part Malevolent and near-perfect rolls (2 seeds), at T4 and at T5. **The exotic** line says what the build's exotic does and what the lab measured it adding, against the same build with a plain part in that slot.

| Build | Style | Set | Fuels | Home | Lab T4 | Lab T5 |
|---|---|---|---|---|---|---|
| Fry Station Fried Stiff | Brawler | Deep Fryer | Fryer Oil, Rendered Lard | The Flesh Farms | 31.8 | 34.9 |
| Fry Station Rendering | Brawler | Deep Fryer | Rendered Lard, Fryer Oil | The Flesh Farms | 30.7 | 34.7 |
| Grease Monkey Ferment | Brawler | Grease Fire | Swamp Napalm, Rocket Hooch | Smokehouse Outskirts | 31.7 | 35.8 |
| Grease Monkey Heat Sink | Brawler | Grease Fire | Thermite Slurry, Rocket Hooch | Smokehouse Outskirts | 29.0 | 32.6 |
| Oven Mitts Greased Feed | Brawler | Oven Mitts | Rendered Lard, Thermite Slurry | Rust Flats | 32.5 | 41.2 |
| Oven Mitts Radiation Sickness | Brawler | Oven Mitts | Rad Syrup, Thermite Slurry | Rust Flats | 31.6 | 41.1 |
| Whole Hog Ferment | Brawler | Whole Hog | Swamp Napalm, Rendered Lard | The Flesh Farms | 30.6 | 33.6 |
| Whole Hog Cracked Open | Brawler | Whole Hog | Thermite Slurry, Rendered Lard | The Flesh Farms | 27.5 | 29.7 |
| Meltdown Kick | Lancer | Meltdown | Rocket Hooch, Ion Gel | Reactor Row | 29.3 | 33.1 |
| Meltdown Pulse | Lancer | Meltdown | Ion Gel, Rocket Hooch | Reactor Row | 32.2 | 34.2 |
| Nutcracker Static Field | Lancer | Nutcracker | Ion Gel, Thermite Slurry | Tank Graveyard | 27.5 | 30.3 |
| Nutcracker Lance | Lancer | Nutcracker | Thermite Slurry, Rocket Hooch | Tank Graveyard | 28.1 | 33.1 |
| Coilworks Kick | Lancer | Tesla Coilworks | Rocket Hooch, Ion Gel | Glow Crater | 31.8 | 33.6 |
| Coilworks EMP | Lancer | Tesla Coilworks | Ion Gel, Rocket Hooch | Glow Crater | 31.1 | 33.5 |
| Boiler Room Redline | Furnace | Boiler Room | Rocket Hooch, Rendered Lard | Smelter Pits | 33.0 | 34.4 |
| Boiler Room Rendering | Furnace | Boiler Room | Rendered Lard, Thermite Slurry | Smelter Pits | 29.2 | 30.6 |
| Hellmouth Fireball | Furnace | Hellmouth | Rocket Hooch, Thermite Slurry | The Junk Bazaar | 31.2 | 34.8 |
| Hellmouth Tar Pit | Furnace | Hellmouth | Swamp Napalm, Rocket Hooch | The Junk Bazaar | 29.6 | 32.0 |
| Hot Plate Seeps Through | Furnace | Hot Plate | Swamp Napalm, Thermite Slurry | Smelter Pits | 31.9 | 36.1 |
| Hot Plate Lance | Furnace | Hot Plate | Thermite Slurry, Rocket Hooch | Smelter Pits | 28.5 | 30.8 |
| Walk-In Freezer Static Field | Miser | Walk-In Freezer | Ion Gel, Rocket Hooch | Static Fields | 31.8 | 36.6 |
| Walk-In Freezer Tar Pit | Miser | Walk-In Freezer | Swamp Napalm, Ion Gel | Static Fields | 29.0 | 32.6 |
| Glacier Works Ferment | Miser | Glacier Works | Swamp Napalm, Rendered Lard | Sewer Delta | 27.6 | 32.1 |
| Glacier Works Tempered | Miser | Glacier Works | Thermite Slurry, Rendered Lard | Sewer Delta | 27.6 | 31.2 |
| Slow Cooker Slick | Miser | Slow Cooker | Rendered Lard, Fryer Oil | Fungal Bog | 28.5 | 32.0 |
| Slow Cooker Heat Sink | Miser | Slow Cooker | Thermite Slurry, Rendered Lard | Fungal Bog | 27.4 | 31.8 |
| Bandolier Tar Pit | Juggler | Bandolier | Swamp Napalm, Thermite Slurry, Ion Gel | Scrap Mountain | 28.0 | 38.6 |
| Bandolier Lance | Juggler | Bandolier | Thermite Slurry, Rad Syrup, Rendered Lard | Scrap Mountain | 29.0 | 31.9 |
| Last Call Fried Stiff | Juggler | Last Call | Fryer Oil, Rocket Hooch, Thermite Slurry | Dead Drive-In | 27.4 | 33.0 |
| Last Call Radiation Sickness | Juggler | Last Call | Rad Syrup, Rocket Hooch, Thermite Slurry | Dead Drive-In | 27.1 | 32.0 |
| Moonshine Run Slick | Juggler | Moonshine Run | Rendered Lard, Rocket Hooch, Thermite Slurry | Dead Drive-In | 28.9 | 37.2 |
| Moonshine Run Radiation Sickness | Juggler | Moonshine Run | Rad Syrup, Rocket Hooch, Thermite Slurry | Dead Drive-In | 25.5 | 34.1 |
| Potluck Fried Stiff | Juggler | Potluck | Fryer Oil, Rendered Lard, Thermite Slurry | Bloat Marsh | 28.7 | 31.3 |
| Potluck Rocket Vent | Juggler | Potluck | Rocket Hooch, Swamp Napalm, Thermite Slurry | Bloat Marsh | 27.3 | 31.9 |
| Test Kitchen Fried Stiff | Juggler | Test Kitchen | Fryer Oil, Rocket Hooch, Thermite Slurry | The Food Court | 31.1 | 38.2 |
| Test Kitchen Dirty Bomb | Juggler | Test Kitchen | Rad Syrup, Rocket Hooch, Thermite Slurry | The Food Court | 26.6 | 34.6 |

### Fry Station Fried Stiff
**Brawler** (up close and in the crowd, Deep Fryer). "Golden, crisp and not going anywhere." Works at arm's length and nowhere else. The closer they get, the worse it goes for them, and the meat sells itself. This one runs Fryer Oil and is built around the Batter Mitt.

- Deep Fryer set, five pieces: Kills drop +25% raw meat; +40% stack damage; +150% stack damage within 220 px; BATTERED: mutants within 220 px take +8% per stack on them (up to +300%). Five pieces: the FLARE-UP, a chance for a close volley to hit harder and cost no fuel.
- Feeding Frenzy keystone (nozzle): A kill streak: every kill adds +10% to all your stacks (an elite counts five), up to +250%. A Bloom nozzle under it: cone x2, +220% stack damage within 280 px, -20% heat. After 6 s without a kill the streak drains, four kills' worth a second.
- Batter Mitt, the exotic (shroud): FRIED STIFF. A mutant Fryer Oil touched in the last 3 s is slowed 60%.
- Fryer Oil's kills come out fried and sell for more. With it, Rendered Lard. Home: the The Flesh Farms.
- The pieces sit on: Gusher fuel line (Flow x1.35), Saddle Tank chassis (One mount with +200% capacity and +200% regen), Booster pump (Pressure x1.5, +10% range), Smoulder igniter (Burn duration x1.6), Distiller filter (Stack damage x1.5), Vent Cowl shroud (Letting go above 50% heat vents it, burning everything within 120 px).

| Slot | Part |
|---|---|
| Fuel Line | Gusher |
| Nozzle | Feeding Frenzy (keystone) |
| Tank Chassis | Saddle Tank |
| Pump | Booster |
| Igniter | Smoulder |
| Filter | Distiller |
| Shroud & Grip | Vent Cowl |

**Set:** 5 Deep Fryer pieces. **Fuels:** Fryer Oil, Rendered Lard. **Affixes:** Potent, Recycling, Sticky. **Home:** The Flesh Farms. **Lab:** threat 31.8 at T4, 34.9 at T5.

**The exotic:** Batter Mitt (the exotic Fryer Oil shroud & grip I, in the shroud & grip slot). FRIED STIFF: A mutant Fryer Oil touched in the last 3 s is slowed 60%. Lab: +3.7 threat.

### Fry Station Rendering
**Brawler** (up close and in the crowd, Deep Fryer). "The big ones fill the tank back up." Works at arm's length and nowhere else. The closer they get, the worse it goes for them, and the meat sells itself. This one runs Rendered Lard and is built around the Schmaltz Aorta.

- Deep Fryer set, five pieces: Kills drop +25% raw meat; +40% stack damage; +150% stack damage within 220 px; BATTERED: mutants within 220 px take +8% per stack on them (up to +300%). Five pieces: the FLARE-UP, a chance for a close volley to hit harder and cost no fuel.
- Flashpoint keystone (igniter): A stack's whole burn lands the instant it is applied, at 1.4 times its total, and at 2.8 times that on anything close (the six nearest mutants, or within 220 px). Nothing lingers: Spreading, Chilling, Opportunist, Culling and Hellmouth do nothing (burn duration still counts: a longer burn lands more). A kill still sets off Toxic, Volatile and Overkill.
- Schmaltz Aorta, the exotic (fuel line): RENDERING. Lard bites armor at x2 and shields at x1. A mutant that dies with Lard on it puts fuel back in the tank, more from a big one.
- Rendered Lard runs cool and sticks to flesh. With it, Fryer Oil. Home: the The Flesh Farms.
- The pieces sit on: Gusher fuel line (Flow x1.35), Bloom nozzle (Cone x2, +220% stack damage within 280 px, -20% heat), Saddle Tank chassis (One mount with +200% capacity and +200% regen), Booster pump (Pressure x1.5, +10% range), Distiller filter (Stack damage x1.5), Vent Cowl shroud (Letting go above 50% heat vents it, burning everything within 120 px).

| Slot | Part |
|---|---|
| Fuel Line | Gusher |
| Nozzle | Bloom |
| Tank Chassis | Saddle Tank |
| Pump | Booster |
| Igniter | Flashpoint (keystone) |
| Filter | Distiller |
| Shroud & Grip | Vent Cowl |

**Set:** 5 Deep Fryer pieces. **Fuels:** Rendered Lard, Fryer Oil. **Affixes:** Potent, Recycling, Sticky. **Home:** The Flesh Farms. **Lab:** threat 30.7 at T4, 34.7 at T5.

**The exotic:** Schmaltz Aorta (the exotic Rendered Lard fuel line III, in the fuel line slot). RENDERING: Lard bites armor at x2 and shields at x1. A mutant that dies with Lard on it puts fuel back in the tank, more from a big one. Lab: +6.0 threat.

### Grease Monkey Ferment
**Brawler** (up close and in the crowd, Grease Fire). "Aged in the tank until it eats plating." One goes up, and the blast lights the ones beside it. Sold to people who like a crowd. This one runs Swamp Napalm and is built around the Swamp-King Altar.

- Grease Fire set, five pieces: Stacks +60% damage; Kills splash 2 stacks nearby; GREASE FIRE: kills explode for 6 stacks in a wide blast; +60% stack damage. Five pieces: the FLARE-UP, a chance for a close volley to hit harder and cost no fuel.
- Flashpoint keystone (igniter): A stack's whole burn lands the instant it is applied, at 1.4 times its total, and at 2.8 times that on anything close (the six nearest mutants, or within 220 px). Nothing lingers: Spreading, Chilling, Opportunist, Culling and Hellmouth do nothing (burn duration still counts: a longer burn lands more). A kill still sets off Toxic, Volatile and Overkill.
- Swamp-King Altar, the exotic (chassis): FERMENT. Napalm ferments in the tank into acid: it bites shields and armor at x1.3.
- Swamp Napalm sticks, spreads and burns the longest. With it, Rocket Hooch. Home: the Smokehouse Outskirts.
- The pieces sit on: Gusher fuel line (Flow x1.35), Bloom nozzle (Cone x2, +220% stack damage within 280 px, -20% heat), Saddle Tank chassis (One mount with +200% capacity and +200% regen), Booster pump (Pressure x1.5, +10% range), Distiller filter (Stack damage x1.5), Vent Cowl shroud (Letting go above 50% heat vents it, burning everything within 120 px).

| Slot | Part |
|---|---|
| Fuel Line | Gusher |
| Nozzle | Bloom |
| Tank Chassis | Saddle Tank |
| Pump | Booster |
| Igniter | Flashpoint (keystone) |
| Filter | Distiller |
| Shroud & Grip | Vent Cowl |

**Set:** 5 Grease Fire pieces. **Fuels:** Swamp Napalm, Rocket Hooch. **Affixes:** Potent, Recycling, Sticky. **Home:** Smokehouse Outskirts. **Lab:** threat 31.7 at T4, 35.8 at T5.

**The exotic:** Swamp-King Altar (the exotic Swamp Napalm tank chassis III, in the tank chassis slot). FERMENT: Napalm ferments in the tank into acid: it bites shields and armor at x1.3. Lab: +2.7 threat.

### Grease Monkey Heat Sink
**Brawler** (up close and in the crowd, Grease Fire). "Past half heat it burns the fever, not the fuel." One goes up, and the blast lights the ones beside it. Sold to people who like a crowd. This one runs Thermite Slurry and is built around the Forge-Heart Altar.

- Grease Fire set, five pieces: Stacks +60% damage; Kills splash 2 stacks nearby; GREASE FIRE: kills explode for 6 stacks in a wide blast; +60% stack damage. Five pieces: the FLARE-UP, a chance for a close volley to hit harder and cost no fuel.
- Flashpoint keystone (igniter): A stack's whole burn lands the instant it is applied, at 1.4 times its total, and at 2.8 times that on anything close (the six nearest mutants, or within 220 px). Nothing lingers: Spreading, Chilling, Opportunist, Culling and Hellmouth do nothing (burn duration still counts: a longer burn lands more). A kill still sets off Toxic, Volatile and Overkill.
- Forge-Heart Altar, the exotic (chassis): HEAT SINK. Above half heat Thermite burns the gun's heat instead of fuel, and hits +50%.
- Thermite Slurry runs hot and eats armor. With it, Rocket Hooch. Home: the Smokehouse Outskirts.
- The pieces sit on: Gusher fuel line (Flow x1.35), Bloom nozzle (Cone x2, +220% stack damage within 280 px, -20% heat), Saddle Tank chassis (One mount with +200% capacity and +200% regen), Booster pump (Pressure x1.5, +10% range), Distiller filter (Stack damage x1.5), Vent Cowl shroud (Letting go above 50% heat vents it, burning everything within 120 px).

| Slot | Part |
|---|---|
| Fuel Line | Gusher |
| Nozzle | Bloom |
| Tank Chassis | Saddle Tank |
| Pump | Booster |
| Igniter | Flashpoint (keystone) |
| Filter | Distiller |
| Shroud & Grip | Vent Cowl |

**Set:** 5 Grease Fire pieces. **Fuels:** Thermite Slurry, Rocket Hooch. **Affixes:** Potent, Recycling, Sticky. **Home:** Smokehouse Outskirts. **Lab:** threat 29.0 at T4, 32.6 at T5.

**The exotic:** Forge-Heart Altar (the exotic Thermite Slurry tank chassis III, in the tank chassis slot). HEAT SINK: Above half heat Thermite burns the gun's heat instead of fuel, and hits +50%. Lab: +2.9 threat.

### Oven Mitts Greased Feed
**Brawler** (up close and in the crowd, Oven Mitts). "Every four seconds it clears its throat." For when they reach you anyway. The well-done ones cannot bite, and one killing blow a run does not count. This one runs Rendered Lard and is built around the Schmaltz Altar.

- Oven Mitts set, five pieces: The pig heals 1 HP each time the threat level rises; COOKED: a mutant carrying 30 or more stacks does no damage when it reaches you, at most one every 3 s. A boss carrying them misses one bite in five; SECOND WIND: once a run, a hit that would kill you leaves you at 3 HP with full armor and lights everything near the truck.
- Feeding Frenzy keystone (nozzle): A kill streak: every kill adds +10% to all your stacks (an elite counts five), up to +250%. A Bloom nozzle under it: cone x2, +220% stack damage within 280 px, -20% heat. After 6 s without a kill the streak drains, four kills' worth a second.
- Schmaltz Altar, the exotic (chassis): GREASED FEED. Every 4 s the feed coughs grease over the cone: 12 Lard stacks, a 0.25 s stun and a 60% slow for 3 s.
- Rendered Lard runs cool and sticks to flesh. With it, Thermite Slurry. Home: the Rust Flats.
- The pieces sit on: Gusher fuel line (Flow x1.35), Saddle Tank chassis (One mount with +200% capacity and +200% regen), Booster pump (Pressure x1.5, +10% range), Smoulder igniter (Burn duration x1.6), Distiller filter (Stack damage x1.5), Vent Cowl shroud (Letting go above 50% heat vents it, burning everything within 120 px).

| Slot | Part |
|---|---|
| Fuel Line | Gusher |
| Nozzle | Feeding Frenzy (keystone) |
| Tank Chassis | Saddle Tank |
| Pump | Booster |
| Igniter | Smoulder |
| Filter | Distiller |
| Shroud & Grip | Vent Cowl |

**Set:** 5 Oven Mitts pieces. **Fuels:** Rendered Lard, Thermite Slurry. **Affixes:** Potent, Recycling, Sticky. **Home:** Rust Flats. **Lab:** threat 32.5 at T4, 41.2 at T5.

**The exotic:** Schmaltz Altar (the exotic Rendered Lard tank chassis III, in the tank chassis slot). GREASED FEED: Every 4 s the feed coughs grease over the cone: 12 Lard stacks, a 0.25 s stun and a 60% slow for 3 s. Lab: +4.5 threat.

### Oven Mitts Radiation Sickness
**Brawler** (up close and in the crowd, Oven Mitts). "One dose. It only gets worse for them." For when they reach you anyway. The well-done ones cannot bite, and one killing blow a run does not count. This one runs Rad Syrup and is built around the Half-Life Altar.

- Oven Mitts set, five pieces: The pig heals 1 HP each time the threat level rises; COOKED: a mutant carrying 30 or more stacks does no damage when it reaches you, at most one every 3 s. A boss carrying them misses one bite in five; SECOND WIND: once a run, a hit that would kill you leaves you at 3 HP with full armor and lights everything near the truck.
- Feeding Frenzy keystone (nozzle): A kill streak: every kill adds +10% to all your stacks (an elite counts five), up to +250%. A Bloom nozzle under it: cone x2, +220% stack damage within 280 px, -20% heat. After 6 s without a kill the streak drains, four kills' worth a second.
- Half-Life Altar, the exotic (chassis): RADIATION SICKNESS. From its first dose a mutant sickens every 2 s: 12% slower and +48% from everything each time, down to half speed and +200%.
- Rad Syrup hits harder the longer it clings. With it, Thermite Slurry. Home: the Rust Flats.
- The pieces sit on: Gusher fuel line (Flow x1.35), Saddle Tank chassis (One mount with +200% capacity and +200% regen), Booster pump (Pressure x1.5, +10% range), Smoulder igniter (Burn duration x1.6), Distiller filter (Stack damage x1.5), Vent Cowl shroud (Letting go above 50% heat vents it, burning everything within 120 px).

| Slot | Part |
|---|---|
| Fuel Line | Gusher |
| Nozzle | Feeding Frenzy (keystone) |
| Tank Chassis | Saddle Tank |
| Pump | Booster |
| Igniter | Smoulder |
| Filter | Distiller |
| Shroud & Grip | Vent Cowl |

**Set:** 5 Oven Mitts pieces. **Fuels:** Rad Syrup, Thermite Slurry. **Affixes:** Potent, Recycling, Sticky. **Home:** Rust Flats. **Lab:** threat 31.6 at T4, 41.1 at T5.

**The exotic:** Half-Life Altar (the exotic Rad Syrup tank chassis III, in the tank chassis slot). RADIATION SICKNESS: From its first dose a mutant sickens every 2 s: 12% slower and +48% from everything each time, down to half speed and +200%. Lab: +4.5 threat.

### Whole Hog Ferment
**Brawler** (up close and in the crowd, Whole Hog). "Aged in the tank until it eats plating." Every kill drops its materials and every boss pays twice. It fights for the haul. This one runs Swamp Napalm and is built around the Swamp-King Altar.

- Whole Hog set, five pieces: Every kill drops its materials; Elites and bosses drop their hoard twice (not the meat); NOSE TO TAIL: a run that gets out brings one more of the place's trophy for every boss killed.
- Flashpoint keystone (igniter): A stack's whole burn lands the instant it is applied, at 1.4 times its total, and at 2.8 times that on anything close (the six nearest mutants, or within 220 px). Nothing lingers: Spreading, Chilling, Opportunist, Culling and Hellmouth do nothing (burn duration still counts: a longer burn lands more). A kill still sets off Toxic, Volatile and Overkill.
- Swamp-King Altar, the exotic (chassis): FERMENT. Napalm ferments in the tank into acid: it bites shields and armor at x1.3.
- Swamp Napalm sticks, spreads and burns the longest. With it, Rendered Lard. Home: the The Flesh Farms.
- The pieces sit on: Gusher fuel line (Flow x1.35), Bloom nozzle (Cone x2, +220% stack damage within 280 px, -20% heat), Saddle Tank chassis (One mount with +200% capacity and +200% regen), Booster pump (Pressure x1.5, +10% range), Distiller filter (Stack damage x1.5), Vent Cowl shroud (Letting go above 50% heat vents it, burning everything within 120 px).

| Slot | Part |
|---|---|
| Fuel Line | Gusher |
| Nozzle | Bloom |
| Tank Chassis | Saddle Tank |
| Pump | Booster |
| Igniter | Flashpoint (keystone) |
| Filter | Distiller |
| Shroud & Grip | Vent Cowl |

**Set:** 5 Whole Hog pieces. **Fuels:** Swamp Napalm, Rendered Lard. **Affixes:** Potent, Recycling, Sticky. **Home:** The Flesh Farms. **Lab:** threat 30.6 at T4, 33.6 at T5.

**The exotic:** Swamp-King Altar (the exotic Swamp Napalm tank chassis III, in the tank chassis slot). FERMENT: Napalm ferments in the tank into acid: it bites shields and armor at x1.3. Lab: +1.5 threat.

### Whole Hog Cracked Open
**Brawler** (up close and in the crowd, Whole Hog). "One plate goes and the rest follow." Every kill drops its materials and every boss pays twice. It fights for the haul. This one runs Thermite Slurry and is built around the Crucible Sieve.

- Whole Hog set, five pieces: Every kill drops its materials; Elites and bosses drop their hoard twice (not the meat); NOSE TO TAIL: a run that gets out brings one more of the place's trophy for every boss killed.
- Flashpoint keystone (igniter): A stack's whole burn lands the instant it is applied, at 1.4 times its total, and at 2.8 times that on anything close (the six nearest mutants, or within 220 px). Nothing lingers: Spreading, Chilling, Opportunist, Culling and Hellmouth do nothing (burn duration still counts: a longer burn lands more). A kill still sets off Toxic, Volatile and Overkill.
- Crucible Sieve, the exotic (filter): CRACKED OPEN. Armor Thermite breaks stuns everything within 160 px for 2 s, and that mutant is cracked open for good: it takes 200% more from everything, after every other bonus. A boss is cracked open as soon as Thermite has its armor under 50%. The break jumps: the weakest armor within reach breaks the same way, up to 4 in a row (a boss's armor loses 15% instead, and stops it).
- Thermite Slurry runs hot and eats armor. With it, Rendered Lard. Home: the The Flesh Farms.
- The pieces sit on: Gusher fuel line (Flow x1.35), Bloom nozzle (Cone x2, +220% stack damage within 280 px, -20% heat), Saddle Tank chassis (One mount with +200% capacity and +200% regen), Booster pump (Pressure x1.5, +10% range), Distiller filter (Stack damage x1.5), Vent Cowl shroud (Letting go above 50% heat vents it, burning everything within 120 px).

| Slot | Part |
|---|---|
| Fuel Line | Gusher |
| Nozzle | Bloom |
| Tank Chassis | Saddle Tank |
| Pump | Booster |
| Igniter | Flashpoint (keystone) |
| Filter | Distiller |
| Shroud & Grip | Vent Cowl |

**Set:** 5 Whole Hog pieces. **Fuels:** Thermite Slurry, Rendered Lard. **Affixes:** Potent, Recycling, Sticky. **Home:** The Flesh Farms. **Lab:** threat 27.5 at T4, 29.7 at T5.

**The exotic:** Crucible Sieve (the exotic Thermite Slurry filter II, in the filter slot). CRACKED OPEN: Armor Thermite breaks stuns everything within 160 px for 2 s, and that mutant is cracked open for good: it takes 200% more from everything, after every other bonus. A boss is cracked open as soon as Thermite has its armor under 50%. The break jumps: the weakest armor within reach breaks the same way, up to 4 in a row (a boss's armor loses 15% instead, and stops it). Lab: +1.6 threat.

### Meltdown Kick
**Lancer** (long reach, one target at a time, Meltdown). "Fifty units in, the tank has an opinion." A long barrel with a grudge against anything big. Elites and bosses get the gun's full attention, twice over. This one runs Rocket Hooch and is built around the Rocket Altar.

- Meltdown set, five pieces: Aging fuels (Rad Syrup) age 25% faster, +20% vs elites and bosses, and +20% stack damage beyond 300 px; Elites and bosses take +25% more from every fuel, and every stack the gun lands on them hits twice as hard; CRITICAL MASS: a mutant carrying 30+ stacks of one fuel takes +50% from every burn. Five pieces: LONG SHOT.
- Flashpoint keystone (igniter): A stack's whole burn lands the instant it is applied, at 1.4 times its total, and at 2.8 times that on anything close (the six nearest mutants, or within 220 px). Nothing lingers: Spreading, Chilling, Opportunist, Culling and Hellmouth do nothing (burn duration still counts: a longer burn lands more). A kill still sets off Toxic, Volatile and Overkill.
- Rocket Altar, the exotic (chassis): KICK. Every 50 units of Hooch the tank kicks: everything in the cone takes 36 extra stacks and a 0.4 s stun.
- Rocket Hooch burns hot, short and against everything. With it, Ion Gel. Home: the Reactor Row.
- The pieces sit on: Capillary fuel line (+35% stack damage, -20% heat), Lance nozzle (Range x1.2, +40% burn duration, and +110% on what stands beyond the long-range line (450 px)), Saddle Tank chassis (One mount with +200% capacity and +200% regen), Accumulator pump (Stores pressure while idle; the first 3 s of a burst fire up to +125% flow), Distiller filter (Stack damage x1.5), Heatsink shroud (Cooling x1.6).

| Slot | Part |
|---|---|
| Fuel Line | Capillary |
| Nozzle | Lance |
| Tank Chassis | Saddle Tank |
| Pump | Accumulator |
| Igniter | Flashpoint (keystone) |
| Filter | Distiller |
| Shroud & Grip | Heatsink |

**Set:** 5 Meltdown pieces. **Fuels:** Rocket Hooch, Ion Gel. **Affixes:** Potent, Recycling, Sticky. **Home:** Reactor Row. **Lab:** threat 29.3 at T4, 33.1 at T5.

**The exotic:** Rocket Altar (the exotic Rocket Hooch tank chassis III, in the tank chassis slot). KICK: Every 50 units of Hooch the tank kicks: everything in the cone takes 36 extra stacks and a 0.4 s stun. Lab: +3.0 threat.

### Meltdown Pulse
**Lancer** (long reach, one target at a time, Meltdown). "Two seconds of nothing, then all of it." A long barrel with a grudge against anything big. Elites and bosses get the gun's full attention, twice over. This one runs Ion Gel and is built around the Capacitor Bellows.

- Meltdown set, five pieces: Aging fuels (Rad Syrup) age 25% faster, +20% vs elites and bosses, and +20% stack damage beyond 300 px; Elites and bosses take +25% more from every fuel, and every stack the gun lands on them hits twice as hard; CRITICAL MASS: a mutant carrying 30+ stacks of one fuel takes +50% from every burn. Five pieces: LONG SHOT.
- Can Opener keystone (fuel line): Shields, armor and health all take your fuel's best multiplier, and 30% more: whatever the fuel is good against, it is good against everything. It takes the fuel line's slot: no line lane's benefit.
- Capacitor Bellows, the exotic (pump): PULSE. Ion Gel charges for 2 s and fires it all at once in a double cone at +150%, with a half-second stun.
- Ion Gel pops shields. With it, Rocket Hooch. Home: the Reactor Row.
- The pieces sit on: Lance nozzle (Range x1.2, +40% burn duration, and +110% on what stands beyond the long-range line (450 px)), Saddle Tank chassis (One mount with +200% capacity and +200% regen), Accumulator pump (Stores pressure while idle; the first 3 s of a burst fire up to +125% flow), Stoker igniter (Each stack on a mutant past its 10th adds +0.8% to all its stacks (up to +20%)), Distiller filter (Stack damage x1.5), Heatsink shroud (Cooling x1.6).

| Slot | Part |
|---|---|
| Fuel Line | Can Opener (keystone) |
| Nozzle | Lance |
| Tank Chassis | Saddle Tank |
| Pump | Accumulator |
| Igniter | Stoker |
| Filter | Distiller |
| Shroud & Grip | Heatsink |

**Set:** 5 Meltdown pieces. **Fuels:** Ion Gel, Rocket Hooch. **Affixes:** Potent, Recycling, Sticky. **Home:** Reactor Row. **Lab:** threat 32.2 at T4, 34.2 at T5.

**The exotic:** Capacitor Bellows (the exotic Ion Gel pump II, in the pump slot). PULSE: Ion Gel charges for 2 s and fires it all at once in a double cone at +150%, with a half-second stun. Lab: +2.5 threat.

### Nutcracker Static Field
**Lancer** (long reach, one target at a time, Nutcracker). "Personal space, enforced every two and a half seconds." Break one shell and the ones next to it crack. Break those and it keeps going. This one runs Ion Gel and is built around the Static Mitt.

- Nutcracker set, five pieces: A broken shield drops Chemicals and broken armor drops Scrap; +40% vs shields and armor; A shell that breaks bursts: 60% of it comes off the same shell of mutants within 120 px; CRACK: the burst is 120%, and a shell a burst breaks bursts too.
- Can Opener keystone (fuel line): Shields, armor and health all take your fuel's best multiplier, and 30% more: whatever the fuel is good against, it is good against everything. It takes the fuel line's slot: no line lane's benefit.
- Static Mitt, the exotic (shroud): STATIC FIELD. Every 2.5 s, 35 Ion stacks and a 1.5 s stun on everything within 300 px of the pig.
- Ion Gel pops shields. With it, Thermite Slurry. Home: the Tank Graveyard.
- The pieces sit on: Lance nozzle (Range x1.2, +40% burn duration, and +110% on what stands beyond the long-range line (450 px)), Saddle Tank chassis (One mount with +200% capacity and +200% regen), Accumulator pump (Stores pressure while idle; the first 3 s of a burst fire up to +125% flow), Stoker igniter (Each stack on a mutant past its 10th adds +0.8% to all its stacks (up to +20%)), Distiller filter (Stack damage x1.5), Heatsink shroud (Cooling x1.6).

| Slot | Part |
|---|---|
| Fuel Line | Can Opener (keystone) |
| Nozzle | Lance |
| Tank Chassis | Saddle Tank |
| Pump | Accumulator |
| Igniter | Stoker |
| Filter | Distiller |
| Shroud & Grip | Heatsink |

**Set:** 5 Nutcracker pieces. **Fuels:** Ion Gel, Thermite Slurry. **Affixes:** Potent, Recycling, Sticky. **Home:** Tank Graveyard. **Lab:** threat 27.5 at T4, 30.3 at T5.

**The exotic:** Static Mitt (the exotic Ion Gel shroud & grip I, in the shroud & grip slot). STATIC FIELD: Every 2.5 s, 35 Ion stacks and a 1.5 s stun on everything within 300 px of the pig. Lab: +1.4 threat.

### Nutcracker Lance
**Lancer** (long reach, one target at a time, Nutcracker). "Narrow, long, and through the plating." Break one shell and the ones next to it crack. Break those and it keeps going. This one runs Thermite Slurry and is built around the Forge-Heart Throat.

- Nutcracker set, five pieces: A broken shield drops Chemicals and broken armor drops Scrap; +40% vs shields and armor; A shell that breaks bursts: 60% of it comes off the same shell of mutants within 120 px; CRACK: the burst is 120%, and a shell a burst breaks bursts too.
- Flashpoint keystone (igniter): A stack's whole burn lands the instant it is applied, at 1.4 times its total, and at 2.8 times that on anything close (the six nearest mutants, or within 220 px). Nothing lingers: Spreading, Chilling, Opportunist, Culling and Hellmouth do nothing (burn duration still counts: a longer burn lands more). A kill still sets off Toxic, Volatile and Overkill.
- Forge-Heart Throat, the exotic (nozzle): LANCE. The cone narrows to 67% of its width and reaches 40% further; everything in the line takes +60%, and its armor x3.5.
- Thermite Slurry runs hot and eats armor. With it, Rocket Hooch. Home: the Tank Graveyard.
- The pieces sit on: Capillary fuel line (+35% stack damage, -20% heat), Lance nozzle (Range x1.2, +40% burn duration, and +110% on what stands beyond the long-range line (450 px)), Saddle Tank chassis (One mount with +200% capacity and +200% regen), Accumulator pump (Stores pressure while idle; the first 3 s of a burst fire up to +125% flow), Distiller filter (Stack damage x1.5), Heatsink shroud (Cooling x1.6).

| Slot | Part |
|---|---|
| Fuel Line | Capillary |
| Nozzle | Lance |
| Tank Chassis | Saddle Tank |
| Pump | Accumulator |
| Igniter | Flashpoint (keystone) |
| Filter | Distiller |
| Shroud & Grip | Heatsink |

**Set:** 5 Nutcracker pieces. **Fuels:** Thermite Slurry, Rocket Hooch. **Affixes:** Potent, Recycling, Sticky. **Home:** Tank Graveyard. **Lab:** threat 28.1 at T4, 33.1 at T5.

**The exotic:** Forge-Heart Throat (the exotic Thermite Slurry nozzle III, in the nozzle slot). LANCE: The cone narrows to 67% of its width and reaches 40% further; everything in the line takes +60%, and its armor x3.5. Lab: +3.9 threat.

### Coilworks Kick
**Lancer** (long reach, one target at a time, Tesla Coilworks). "Fifty units in, the tank has an opinion." One hit, seven mutants. And when there is only one left standing, the arc comes back for it. This one runs Rocket Hooch and is built around the Rocket Altar.

- Tesla Coilworks set, five pieces: +30% vs shields; Breaking a shield stuns for 1 s; ARC: every hit chains to 6 nearby mutants, and chained stacks deal +100%. A link with no mutant to jump to arcs back onto the one that was hit, at half strength. Five pieces: LONG SHOT.
- Flashpoint keystone (igniter): A stack's whole burn lands the instant it is applied, at 1.4 times its total, and at 2.8 times that on anything close (the six nearest mutants, or within 220 px). Nothing lingers: Spreading, Chilling, Opportunist, Culling and Hellmouth do nothing (burn duration still counts: a longer burn lands more). A kill still sets off Toxic, Volatile and Overkill.
- Rocket Altar, the exotic (chassis): KICK. Every 50 units of Hooch the tank kicks: everything in the cone takes 36 extra stacks and a 0.4 s stun.
- Rocket Hooch burns hot, short and against everything. With it, Ion Gel. Home: the Glow Crater.
- The pieces sit on: Capillary fuel line (+35% stack damage, -20% heat), Lance nozzle (Range x1.2, +40% burn duration, and +110% on what stands beyond the long-range line (450 px)), Saddle Tank chassis (One mount with +200% capacity and +200% regen), Accumulator pump (Stores pressure while idle; the first 3 s of a burst fire up to +125% flow), Distiller filter (Stack damage x1.5), Heatsink shroud (Cooling x1.6).

| Slot | Part |
|---|---|
| Fuel Line | Capillary |
| Nozzle | Lance |
| Tank Chassis | Saddle Tank |
| Pump | Accumulator |
| Igniter | Flashpoint (keystone) |
| Filter | Distiller |
| Shroud & Grip | Heatsink |

**Set:** 5 Tesla Coilworks pieces. **Fuels:** Rocket Hooch, Ion Gel. **Affixes:** Potent, Recycling, Sticky. **Home:** Glow Crater. **Lab:** threat 31.8 at T4, 33.6 at T5.

**The exotic:** Rocket Altar (the exotic Rocket Hooch tank chassis III, in the tank chassis slot). KICK: Every 50 units of Hooch the tank kicks: everything in the cone takes 36 extra stacks and a 0.4 s stun. Lab: +2.5 threat.

### Coilworks EMP
**Lancer** (long reach, one target at a time, Tesla Coilworks). "Pop one shield and the room hears about it." One hit, seven mutants. And when there is only one left standing, the arc comes back for it. This one runs Ion Gel and is built around the Storm Crown.

- Tesla Coilworks set, five pieces: +30% vs shields; Breaking a shield stuns for 1 s; ARC: every hit chains to 6 nearby mutants, and chained stacks deal +100%. A link with no mutant to jump to arcs back onto the one that was hit, at half strength. Five pieces: LONG SHOT.
- Can Opener keystone (fuel line): Shields, armor and health all take your fuel's best multiplier, and 30% more: whatever the fuel is good against, it is good against everything. It takes the fuel line's slot: no line lane's benefit.
- Storm Crown, the exotic (igniter): EMP. A shield Ion Gel pops deals 40% of what it held to everything within 150 px, shields first.
- Ion Gel pops shields. With it, Rocket Hooch. Home: the Glow Crater.
- The pieces sit on: Lance nozzle (Range x1.2, +40% burn duration, and +110% on what stands beyond the long-range line (450 px)), Saddle Tank chassis (One mount with +200% capacity and +200% regen), Accumulator pump (Stores pressure while idle; the first 3 s of a burst fire up to +125% flow), Stoker igniter (Each stack on a mutant past its 10th adds +0.8% to all its stacks (up to +20%)), Distiller filter (Stack damage x1.5), Heatsink shroud (Cooling x1.6).

| Slot | Part |
|---|---|
| Fuel Line | Can Opener (keystone) |
| Nozzle | Lance |
| Tank Chassis | Saddle Tank |
| Pump | Accumulator |
| Igniter | Stoker |
| Filter | Distiller |
| Shroud & Grip | Heatsink |

**Set:** 5 Tesla Coilworks pieces. **Fuels:** Ion Gel, Rocket Hooch. **Affixes:** Potent, Recycling, Sticky. **Home:** Glow Crater. **Lab:** threat 31.1 at T4, 33.5 at T5.

**The exotic:** Storm Crown (the exotic Ion Gel igniter III, in the igniter slot; the fuel becomes EMP Gel). EMP: A shield Ion Gel pops deals 40% of what it held to everything within 150 px, shields first. Lab: +0.6 threat.

### Boiler Room Redline
**Furnace** (runs hot and holds the trigger, Boiler Room). "The needle belongs in the red." The hotter it runs the harder it hits, and at the top of the gauge it gets three seconds the warranty does not mention. This one runs Rocket Hooch and is built around the Moonshine Bellows.

- Boiler Room set, five pieces: Heat cap +25%, +35% stack damage; Stacks +1.2% for every 1% of heat (up to +120% at full heat); PRESSURE COOKER: reaching 100% heat starts 3 s without a lockout and +50% flow, then the gun locks out and vents to 0 (once per 45 s); +60% stack damage. Five pieces: BLOWOFF.
- Feeding Frenzy keystone (nozzle): A kill streak: every kill adds +10% to all your stacks (an elite counts five), up to +250%. A Bloom nozzle under it: cone x2, +220% stack damage within 280 px, -20% heat. After 6 s without a kill the streak drains, four kills' worth a second.
- Moonshine Bellows, the exotic (pump): REDLINE. Past half heat Hooch hits harder the hotter the gun: +300% at full heat. It heats the gun 25% faster.
- Rocket Hooch burns hot, short and against everything. With it, Rendered Lard. Home: the Smelter Pits.
- The pieces sit on: Spool-Up Coil fuel line (Flow climbs from x0.6 to x1.6 over 3 s of held fire), Saddle Tank chassis (One mount with +200% capacity and +200% regen), Siphon pump (The active tank refills at its full idle rate while firing; +10% range), Smoulder igniter (Burn duration x1.6), Catalyst filter (+35% vs shields and armor), Insulated shroud (Heat cap x1.6).

| Slot | Part |
|---|---|
| Fuel Line | Spool-Up Coil |
| Nozzle | Feeding Frenzy (keystone) |
| Tank Chassis | Saddle Tank |
| Pump | Siphon |
| Igniter | Smoulder |
| Filter | Catalyst |
| Shroud & Grip | Insulated |

**Set:** 5 Boiler Room pieces. **Fuels:** Rocket Hooch, Rendered Lard. **Affixes:** Potent, Recycling, Sticky. **Home:** Smelter Pits. **Lab:** threat 33.0 at T4, 34.4 at T5.

**The exotic:** Moonshine Bellows (the exotic Rocket Hooch pump II, in the pump slot). REDLINE: Past half heat Hooch hits harder the hotter the gun: +300% at full heat. It heats the gun 25% faster. Lab: +1.4 threat.

### Boiler Room Rendering
**Furnace** (runs hot and holds the trigger, Boiler Room). "The big ones fill the tank back up." The hotter it runs the harder it hits, and at the top of the gauge it gets three seconds the warranty does not mention. This one runs Rendered Lard and is built around the Schmaltz Aorta.

- Boiler Room set, five pieces: Heat cap +25%, +35% stack damage; Stacks +1.2% for every 1% of heat (up to +120% at full heat); PRESSURE COOKER: reaching 100% heat starts 3 s without a lockout and +50% flow, then the gun locks out and vents to 0 (once per 45 s); +60% stack damage. Five pieces: BLOWOFF.
- Fever Grip keystone (shroud): +25% stack damage per 5% heat, and heat cap +40%. A lockout at 100% heat lasts twice as long.
- Schmaltz Aorta, the exotic (fuel line): RENDERING. Lard bites armor at x2 and shields at x1. A mutant that dies with Lard on it puts fuel back in the tank, more from a big one.
- Rendered Lard runs cool and sticks to flesh. With it, Thermite Slurry. Home: the Smelter Pits.
- The pieces sit on: Spool-Up Coil fuel line (Flow climbs from x0.6 to x1.6 over 3 s of held fire), Bloom nozzle (Cone x2, +220% stack damage within 280 px, -20% heat), Saddle Tank chassis (One mount with +200% capacity and +200% regen), Booster pump (Pressure x1.5, +10% range), Smoulder igniter (Burn duration x1.6), Distiller filter (Stack damage x1.5).

| Slot | Part |
|---|---|
| Fuel Line | Spool-Up Coil |
| Nozzle | Bloom |
| Tank Chassis | Saddle Tank |
| Pump | Booster |
| Igniter | Smoulder |
| Filter | Distiller |
| Shroud & Grip | Fever Grip (keystone) |

**Set:** 5 Boiler Room pieces. **Fuels:** Rendered Lard, Thermite Slurry. **Affixes:** Potent, Recycling, Sticky. **Home:** Smelter Pits. **Lab:** threat 29.2 at T4, 30.6 at T5.

**The exotic:** Schmaltz Aorta (the exotic Rendered Lard fuel line III, in the fuel line slot). RENDERING: Lard bites armor at x2 and shields at x1. A mutant that dies with Lard on it puts fuel back in the tank, more from a big one. Lab: +9.3 threat.

### Hellmouth Fireball
**Furnace** (runs hot and holds the trigger, Hellmouth). "The dead ones do the rest." Found, not made. Nothing it lights goes out while you keep it in the flame. This one runs Rocket Hooch and is built around the Rocket Throat.

- Hellmouth set, five pieces: All fuels +220% stack damage; All fuels +20% burn duration and +30% stack damage; HELLMOUTH: stacks stop expiring while the mutant stays in the cone. Five pieces: BLOWOFF.
- Fever Grip keystone (shroud): +25% stack damage per 5% heat, and heat cap +40%. A lockout at 100% heat lasts twice as long.
- Rocket Throat, the exotic (nozzle): FIREBALL. A mutant that dies with Hooch on it goes up: x0.75 of what its Hooch had left lands on everything within 90 px.
- Rocket Hooch burns hot, short and against everything. With it, Thermite Slurry. Home: the The Junk Bazaar.
- The pieces sit on: Spool-Up Coil fuel line (Flow climbs from x0.6 to x1.6 over 3 s of held fire), Bloom nozzle (Cone x2, +220% stack damage within 280 px, -20% heat), Saddle Tank chassis (One mount with +200% capacity and +200% regen), Booster pump (Pressure x1.5, +10% range), Smoulder igniter (Burn duration x1.6), Distiller filter (Stack damage x1.5).

| Slot | Part |
|---|---|
| Fuel Line | Spool-Up Coil |
| Nozzle | Bloom |
| Tank Chassis | Saddle Tank |
| Pump | Booster |
| Igniter | Smoulder |
| Filter | Distiller |
| Shroud & Grip | Fever Grip (keystone) |

**Set:** 5 Hellmouth pieces. **Fuels:** Rocket Hooch, Thermite Slurry. **Affixes:** Potent, Recycling, Sticky. **Home:** The Junk Bazaar. **Lab:** threat 31.2 at T4, 34.8 at T5.

**The exotic:** Rocket Throat (the exotic Rocket Hooch nozzle III, in the nozzle slot). FIREBALL: A mutant that dies with Hooch on it goes up: x0.75 of what its Hooch had left lands on everything within 90 px. Lab: +2.5 threat.

### Hellmouth Tar Pit
**Furnace** (runs hot and holds the trigger, Hellmouth). "Stuck fast, and swinging at nothing." Found, not made. Nothing it lights goes out while you keep it in the flame. This one runs Swamp Napalm and is built around the Bog Mitt.

- Hellmouth set, five pieces: All fuels +220% stack damage; All fuels +20% burn duration and +30% stack damage; HELLMOUTH: stacks stop expiring while the mutant stays in the cone. Five pieces: BLOWOFF.
- Double Distill keystone (filter): Every stack hits x2.0: a multiplier, over every stat and cap. Each unit costs 1.25 fuel and makes 15% more heat.
- Bog Mitt, the exotic (shroud): TAR PIT. Napalm slows 6% a stack, up to 55%. A mutant at the cap is stuck: every other hit it throws at the pig does nothing.
- Swamp Napalm sticks, spreads and burns the longest. With it, Rocket Hooch. Home: the The Junk Bazaar.
- The pieces sit on: Spool-Up Coil fuel line (Flow climbs from x0.6 to x1.6 over 3 s of held fire), Bloom nozzle (Cone x2, +220% stack damage within 280 px, -20% heat), Saddle Tank chassis (One mount with +200% capacity and +200% regen), Booster pump (Pressure x1.5, +10% range), Smoulder igniter (Burn duration x1.6), Insulated shroud (Heat cap x1.6).

| Slot | Part |
|---|---|
| Fuel Line | Spool-Up Coil |
| Nozzle | Bloom |
| Tank Chassis | Saddle Tank |
| Pump | Booster |
| Igniter | Smoulder |
| Filter | Double Distill (keystone) |
| Shroud & Grip | Insulated |

**Set:** 5 Hellmouth pieces. **Fuels:** Swamp Napalm, Rocket Hooch. **Affixes:** Potent, Recycling, Sticky. **Home:** The Junk Bazaar. **Lab:** threat 29.6 at T4, 32.0 at T5.

**The exotic:** Bog Mitt (the exotic Swamp Napalm shroud & grip I, in the shroud & grip slot). TAR PIT: Napalm slows 6% a stack, up to 55%. A mutant at the cap is stuck: every other hit it throws at the pig does nothing. Lab: +8.0 threat.

### Hot Plate Seeps Through
**Furnace** (runs hot and holds the trigger, Hot Plate). "Burns what is under the shell first." Leaves the ground burning where your flame ends, and keeps it burning for as long as you feed it. This one runs Swamp Napalm and is built around the Jelly Sieve.

- Hot Plate set, five pieces: The far end of your flame leaves a burning patch (4 s): 32 stacks a second on mutants in it; The patch burns 64 stacks a second and slows mutants on it 30%; FIREBREAK: 96 stacks a second, and patches that touch last as long as any one is fed.
- Fever Grip keystone (shroud): +25% stack damage per 5% heat, and heat cap +40%. A lockout at 100% heat lasts twice as long.
- Jelly Sieve, the exotic (filter): SEEPS THROUGH. Under a shield or armor, Napalm also burns the health beneath, at 15% of its strength. On bare health it hits +40%.
- Swamp Napalm sticks, spreads and burns the longest. With it, Thermite Slurry. Home: the Smelter Pits.
- The pieces sit on: Spool-Up Coil fuel line (Flow climbs from x0.6 to x1.6 over 3 s of held fire), Bloom nozzle (Cone x2, +220% stack damage within 280 px, -20% heat), Saddle Tank chassis (One mount with +200% capacity and +200% regen), Booster pump (Pressure x1.5, +10% range), Smoulder igniter (Burn duration x1.6), Distiller filter (Stack damage x1.5).

| Slot | Part |
|---|---|
| Fuel Line | Spool-Up Coil |
| Nozzle | Bloom |
| Tank Chassis | Saddle Tank |
| Pump | Booster |
| Igniter | Smoulder |
| Filter | Distiller |
| Shroud & Grip | Fever Grip (keystone) |

**Set:** 5 Hot Plate pieces. **Fuels:** Swamp Napalm, Thermite Slurry. **Affixes:** Potent, Recycling, Sticky. **Home:** Smelter Pits. **Lab:** threat 31.9 at T4, 36.1 at T5.

**The exotic:** Jelly Sieve (the exotic Swamp Napalm filter II, in the filter slot). SEEPS THROUGH: Under a shield or armor, Napalm also burns the health beneath, at 15% of its strength. On bare health it hits +40%. Lab: +8.9 threat.

### Hot Plate Lance
**Furnace** (runs hot and holds the trigger, Hot Plate). "Narrow, long, and through the plating." Leaves the ground burning where your flame ends, and keeps it burning for as long as you feed it. This one runs Thermite Slurry and is built around the Forge-Heart Throat.

- Hot Plate set, five pieces: The far end of your flame leaves a burning patch (4 s): 32 stacks a second on mutants in it; The patch burns 64 stacks a second and slows mutants on it 30%; FIREBREAK: 96 stacks a second, and patches that touch last as long as any one is fed.
- Fever Grip keystone (shroud): +25% stack damage per 5% heat, and heat cap +40%. A lockout at 100% heat lasts twice as long.
- Forge-Heart Throat, the exotic (nozzle): LANCE. The cone narrows to 67% of its width and reaches 40% further; everything in the line takes +60%, and its armor x3.5.
- Thermite Slurry runs hot and eats armor. With it, Rocket Hooch. Home: the Smelter Pits.
- The pieces sit on: Spool-Up Coil fuel line (Flow climbs from x0.6 to x1.6 over 3 s of held fire), Bloom nozzle (Cone x2, +220% stack damage within 280 px, -20% heat), Saddle Tank chassis (One mount with +200% capacity and +200% regen), Booster pump (Pressure x1.5, +10% range), Smoulder igniter (Burn duration x1.6), Distiller filter (Stack damage x1.5).

| Slot | Part |
|---|---|
| Fuel Line | Spool-Up Coil |
| Nozzle | Bloom |
| Tank Chassis | Saddle Tank |
| Pump | Booster |
| Igniter | Smoulder |
| Filter | Distiller |
| Shroud & Grip | Fever Grip (keystone) |

**Set:** 5 Hot Plate pieces. **Fuels:** Thermite Slurry, Rocket Hooch. **Affixes:** Potent, Recycling, Sticky. **Home:** Smelter Pits. **Lab:** threat 28.5 at T4, 30.8 at T5.

**The exotic:** Forge-Heart Throat (the exotic Thermite Slurry nozzle III, in the nozzle slot). LANCE: The cone narrows to 67% of its width and reaches 40% further; everything in the line takes +60%, and its armor x3.5. Lab: +2.5 threat.

### Walk-In Freezer Static Field
**Miser** (cheap fuel, long burns, cool head, Walk-In Freezer). "Personal space, enforced every two and a half seconds." They slow, they stop, and the ones that die frozen take a piece of the neighbours with them. This one runs Ion Gel and is built around the Static Mitt.

- Walk-In Freezer set, five pieces: Burning mutants slow by 6% a second, up to 40%; At full chill a mutant freezes for 2 s, once every 6 s (a boss 1 s); SHATTER: a frozen mutant that dies bursts for 25% of its health onto mutants within 100 px; a frozen mutant under 15% health breaks.
- Can Opener keystone (fuel line): Shields, armor and health all take your fuel's best multiplier, and 30% more: whatever the fuel is good against, it is good against everything. It takes the fuel line's slot: no line lane's benefit.
- Static Mitt, the exotic (shroud): STATIC FIELD. Every 2.5 s, 35 Ion stacks and a 1.5 s stun on everything within 300 px of the pig.
- Ion Gel pops shields. With it, Rocket Hooch. Home: the Static Fields.
- The pieces sit on: Fan nozzle (Cone x1.5, and +90% on every stack (a plain bonus, outside the stack damage cap)), Saddle Tank chassis (One mount with +200% capacity and +200% regen), Siphon pump (The active tank refills at its full idle rate while firing; +10% range), Smoulder igniter (Burn duration x1.6), Coarse Mesh filter (20% of units cost no fuel), Heatsink shroud (Cooling x1.6).

| Slot | Part |
|---|---|
| Fuel Line | Can Opener (keystone) |
| Nozzle | Fan |
| Tank Chassis | Saddle Tank |
| Pump | Siphon |
| Igniter | Smoulder |
| Filter | Coarse Mesh |
| Shroud & Grip | Heatsink |

**Set:** 5 Walk-In Freezer pieces. **Fuels:** Ion Gel, Rocket Hooch. **Affixes:** Potent, Recycling, Sticky. **Home:** Static Fields. **Lab:** threat 31.8 at T4, 36.6 at T5.

**The exotic:** Static Mitt (the exotic Ion Gel shroud & grip I, in the shroud & grip slot). STATIC FIELD: Every 2.5 s, 35 Ion stacks and a 1.5 s stun on everything within 300 px of the pig. Lab: +4.7 threat.

### Walk-In Freezer Tar Pit
**Miser** (cheap fuel, long burns, cool head, Walk-In Freezer). "Stuck fast, and swinging at nothing." They slow, they stop, and the ones that die frozen take a piece of the neighbours with them. This one runs Swamp Napalm and is built around the Bog Mitt.

- Walk-In Freezer set, five pieces: Burning mutants slow by 6% a second, up to 40%; At full chill a mutant freezes for 2 s, once every 6 s (a boss 1 s); SHATTER: a frozen mutant that dies bursts for 25% of its health onto mutants within 100 px; a frozen mutant under 15% health breaks.
- Can Opener keystone (fuel line): Shields, armor and health all take your fuel's best multiplier, and 30% more: whatever the fuel is good against, it is good against everything. It takes the fuel line's slot: no line lane's benefit.
- Bog Mitt, the exotic (shroud): TAR PIT. Napalm slows 6% a stack, up to 55%. A mutant at the cap is stuck: every other hit it throws at the pig does nothing.
- Swamp Napalm sticks, spreads and burns the longest. With it, Ion Gel. Home: the Static Fields.
- The pieces sit on: Fan nozzle (Cone x1.5, and +90% on every stack (a plain bonus, outside the stack damage cap)), Saddle Tank chassis (One mount with +200% capacity and +200% regen), Siphon pump (The active tank refills at its full idle rate while firing; +10% range), Smoulder igniter (Burn duration x1.6), Coarse Mesh filter (20% of units cost no fuel), Heatsink shroud (Cooling x1.6).

| Slot | Part |
|---|---|
| Fuel Line | Can Opener (keystone) |
| Nozzle | Fan |
| Tank Chassis | Saddle Tank |
| Pump | Siphon |
| Igniter | Smoulder |
| Filter | Coarse Mesh |
| Shroud & Grip | Heatsink |

**Set:** 5 Walk-In Freezer pieces. **Fuels:** Swamp Napalm, Ion Gel. **Affixes:** Potent, Recycling, Sticky. **Home:** Static Fields. **Lab:** threat 29.0 at T4, 32.6 at T5.

**The exotic:** Bog Mitt (the exotic Swamp Napalm shroud & grip I, in the shroud & grip slot). TAR PIT: Napalm slows 6% a stack, up to 55%. A mutant at the cap is stuck: every other hit it throws at the pig does nothing. Lab: +3.3 threat.

### Glacier Works Ferment
**Miser** (cheap fuel, long burns, cool head, Glacier Works). "Aged in the tank until it eats plating." Cools in half the time and hits hardest after a rest. For the patient. This one runs Swamp Napalm and is built around the Swamp-King Altar.

- Glacier Works set, five pieces: The gun cools 50% faster; Burning mutants slow 30%; COLD START: Pent-Up without the behavior (+60% a second idle, up to +200%), twice as fast with it; +40% stack damage. Five pieces: SECOND HELPING.
- Flashpoint keystone (igniter): A stack's whole burn lands the instant it is applied, at 1.4 times its total, and at 2.8 times that on anything close (the six nearest mutants, or within 220 px). Nothing lingers: Spreading, Chilling, Opportunist, Culling and Hellmouth do nothing (burn duration still counts: a longer burn lands more). A kill still sets off Toxic, Volatile and Overkill.
- Swamp-King Altar, the exotic (chassis): FERMENT. Napalm ferments in the tank into acid: it bites shields and armor at x1.3.
- Swamp Napalm sticks, spreads and burns the longest. With it, Rendered Lard. Home: the Sewer Delta.
- The pieces sit on: Capillary fuel line (+35% stack damage, -20% heat), Fan nozzle (Cone x1.5, and +90% on every stack (a plain bonus, outside the stack damage cap)), Saddle Tank chassis (One mount with +200% capacity and +200% regen), Siphon pump (The active tank refills at its full idle rate while firing; +10% range), Coarse Mesh filter (20% of units cost no fuel), Heatsink shroud (Cooling x1.6).

| Slot | Part |
|---|---|
| Fuel Line | Capillary |
| Nozzle | Fan |
| Tank Chassis | Saddle Tank |
| Pump | Siphon |
| Igniter | Flashpoint (keystone) |
| Filter | Coarse Mesh |
| Shroud & Grip | Heatsink |

**Set:** 5 Glacier Works pieces. **Fuels:** Swamp Napalm, Rendered Lard. **Affixes:** Potent, Recycling, Sticky. **Home:** Sewer Delta. **Lab:** threat 27.6 at T4, 32.1 at T5.

**The exotic:** Swamp-King Altar (the exotic Swamp Napalm tank chassis III, in the tank chassis slot). FERMENT: Napalm ferments in the tank into acid: it bites shields and armor at x1.3. Lab: +1.2 threat.

### Glacier Works Tempered
**Miser** (cheap fuel, long burns, cool head, Glacier Works). "Every plate it breaks sharpens the next tank." Cools in half the time and hits hardest after a rest. For the patient. This one runs Thermite Slurry and is built around the Slag Mitt.

- Glacier Works set, five pieces: The gun cools 50% faster; Burning mutants slow 30%; COLD START: Pent-Up without the behavior (+60% a second idle, up to +200%), twice as fast with it; +40% stack damage. Five pieces: SECOND HELPING.
- Flashpoint keystone (igniter): A stack's whole burn lands the instant it is applied, at 1.4 times its total, and at 2.8 times that on anything close (the six nearest mutants, or within 220 px). Nothing lingers: Spreading, Chilling, Opportunist, Culling and Hellmouth do nothing (burn duration still counts: a longer burn lands more). A kill still sets off Toxic, Volatile and Overkill.
- Slag Mitt, the exotic (shroud): TEMPERED. Each armor Thermite breaks makes the next 160 units of any fuel hit +220%.
- Thermite Slurry runs hot and eats armor. With it, Rendered Lard. Home: the Sewer Delta.
- The pieces sit on: Capillary fuel line (+35% stack damage, -20% heat), Fan nozzle (Cone x1.5, and +90% on every stack (a plain bonus, outside the stack damage cap)), Saddle Tank chassis (One mount with +200% capacity and +200% regen), Siphon pump (The active tank refills at its full idle rate while firing; +10% range), Coarse Mesh filter (20% of units cost no fuel), Heatsink shroud (Cooling x1.6).

| Slot | Part |
|---|---|
| Fuel Line | Capillary |
| Nozzle | Fan |
| Tank Chassis | Saddle Tank |
| Pump | Siphon |
| Igniter | Flashpoint (keystone) |
| Filter | Coarse Mesh |
| Shroud & Grip | Heatsink |

**Set:** 5 Glacier Works pieces. **Fuels:** Thermite Slurry, Rendered Lard. **Affixes:** Potent, Recycling, Sticky. **Home:** Sewer Delta. **Lab:** threat 27.6 at T4, 31.2 at T5.

**The exotic:** Slag Mitt (the exotic Thermite Slurry shroud & grip I, in the shroud & grip slot). TEMPERED: Each armor Thermite breaks makes the next 160 units of any fuel hit +220%. Lab: +6.1 threat.

### Slow Cooker Slick
**Miser** (cheap fuel, long burns, cool head, Slow Cooker). "Whatever you hit loses its footing and its nerve." Paint them once and look away. It does its best work on whatever you are not aiming at. This one runs Rendered Lard and is built around the Tallow Mitt.

- Slow Cooker set, five pieces: +25% burn duration; tanks regen +1.5 units/s while you aren't firing; Stacks on mutants outside the cone deal +45% damage; SIMMER: every 10th unit applies 2 stacks, and stacks outside the cone deal +25% more; all fuels +57% stack damage. Five pieces: SECOND HELPING.
- Flashpoint keystone (igniter): A stack's whole burn lands the instant it is applied, at 1.4 times its total, and at 2.8 times that on anything close (the six nearest mutants, or within 220 px). Nothing lingers: Spreading, Chilling, Opportunist, Culling and Hellmouth do nothing (burn duration still counts: a longer burn lands more). A kill still sets off Toxic, Volatile and Overkill.
- Tallow Mitt, the exotic (shroud): SLICK. Whatever the gun hits, with any fuel, is slick for 2 s: slowed 50%, and it takes +30% from everything.
- Rendered Lard runs cool and sticks to flesh. With it, Fryer Oil. Home: the Fungal Bog.
- The pieces sit on: Capillary fuel line (+35% stack damage, -20% heat), Fan nozzle (Cone x1.5, and +90% on every stack (a plain bonus, outside the stack damage cap)), Saddle Tank chassis (One mount with +200% capacity and +200% regen), Siphon pump (The active tank refills at its full idle rate while firing; +10% range), Coarse Mesh filter (20% of units cost no fuel), Heatsink shroud (Cooling x1.6).

| Slot | Part |
|---|---|
| Fuel Line | Capillary |
| Nozzle | Fan |
| Tank Chassis | Saddle Tank |
| Pump | Siphon |
| Igniter | Flashpoint (keystone) |
| Filter | Coarse Mesh |
| Shroud & Grip | Heatsink |

**Set:** 5 Slow Cooker pieces. **Fuels:** Rendered Lard, Fryer Oil. **Affixes:** Potent, Recycling, Sticky. **Home:** Fungal Bog. **Lab:** threat 28.5 at T4, 32.0 at T5.

**The exotic:** Tallow Mitt (the exotic Rendered Lard shroud & grip I, in the shroud & grip slot). SLICK: Whatever the gun hits, with any fuel, is slick for 2 s: slowed 50%, and it takes +30% from everything. Lab: +2.6 threat.

### Slow Cooker Heat Sink
**Miser** (cheap fuel, long burns, cool head, Slow Cooker). "Past half heat it burns the fever, not the fuel." Paint them once and look away. It does its best work on whatever you are not aiming at. This one runs Thermite Slurry and is built around the Forge-Heart Altar.

- Slow Cooker set, five pieces: +25% burn duration; tanks regen +1.5 units/s while you aren't firing; Stacks on mutants outside the cone deal +45% damage; SIMMER: every 10th unit applies 2 stacks, and stacks outside the cone deal +25% more; all fuels +57% stack damage. Five pieces: SECOND HELPING.
- Flashpoint keystone (igniter): A stack's whole burn lands the instant it is applied, at 1.4 times its total, and at 2.8 times that on anything close (the six nearest mutants, or within 220 px). Nothing lingers: Spreading, Chilling, Opportunist, Culling and Hellmouth do nothing (burn duration still counts: a longer burn lands more). A kill still sets off Toxic, Volatile and Overkill.
- Forge-Heart Altar, the exotic (chassis): HEAT SINK. Above half heat Thermite burns the gun's heat instead of fuel, and hits +50%.
- Thermite Slurry runs hot and eats armor. With it, Rendered Lard. Home: the Fungal Bog.
- The pieces sit on: Capillary fuel line (+35% stack damage, -20% heat), Fan nozzle (Cone x1.5, and +90% on every stack (a plain bonus, outside the stack damage cap)), Saddle Tank chassis (One mount with +200% capacity and +200% regen), Siphon pump (The active tank refills at its full idle rate while firing; +10% range), Coarse Mesh filter (20% of units cost no fuel), Heatsink shroud (Cooling x1.6).

| Slot | Part |
|---|---|
| Fuel Line | Capillary |
| Nozzle | Fan |
| Tank Chassis | Saddle Tank |
| Pump | Siphon |
| Igniter | Flashpoint (keystone) |
| Filter | Coarse Mesh |
| Shroud & Grip | Heatsink |

**Set:** 5 Slow Cooker pieces. **Fuels:** Thermite Slurry, Rendered Lard. **Affixes:** Potent, Recycling, Sticky. **Home:** Fungal Bog. **Lab:** threat 27.4 at T4, 31.8 at T5.

**The exotic:** Forge-Heart Altar (the exotic Thermite Slurry tank chassis III, in the tank chassis slot). HEAT SINK: Above half heat Thermite burns the gun's heat instead of fuel, and hits +50%. Lab: +4.0 threat.

### Bandolier Tar Pit
**Juggler** (many tanks, many swaps, Bandolier). "Stuck fast, and swinging at nothing." A fourth tank and no time lost changing between them. Every swap hits harder than the last shot did. This one runs Swamp Napalm and is built around the Bog Mitt.

- Bandolier set, five pieces: +1 tank mount on any chassis (up to 4); Swapping tanks gives +50% stack damage for 3 s; QUICK DRAW: a swap within 1 s of the last costs no swap time. Five pieces: FRESH TANK.
- Gatling Drum keystone (chassis): Each unit fires from every mounted tank at once, each applying its own fuel's stack, and every tank refills like an idle one. Drains every tank together, each unit makes double heat, and every stack lands at 60%.
- Bog Mitt, the exotic (shroud): TAR PIT. Napalm slows 6% a stack, up to 55%. A mutant at the cap is stuck: every other hit it throws at the pig does nothing.
- Swamp Napalm sticks, spreads and burns the longest. With it, Thermite Slurry and Ion Gel. Home: the Scrap Mountain.
- The pieces sit on: Gusher fuel line (Flow x1.35), Fan nozzle (Cone x1.5, and +90% on every stack (a plain bonus, outside the stack damage cap)), Accumulator pump (Stores pressure while idle; the first 3 s of a burst fire up to +125% flow), Flash igniter (+55% on every stack (a plain bonus, outside the stack damage cap)), Catalyst filter (+35% vs shields and armor), Heatsink shroud (Cooling x1.6).

| Slot | Part |
|---|---|
| Fuel Line | Gusher |
| Nozzle | Fan |
| Tank Chassis | Gatling Drum (keystone) |
| Pump | Accumulator |
| Igniter | Flash |
| Filter | Catalyst |
| Shroud & Grip | Heatsink |

**Set:** 5 Bandolier pieces. **Fuels:** Swamp Napalm, Thermite Slurry, Ion Gel. **Affixes:** Potent, Recycling, Sticky. **Home:** Scrap Mountain. **Lab:** threat 28.0 at T4, 38.6 at T5.

**The exotic:** Bog Mitt (the exotic Swamp Napalm shroud & grip I, in the shroud & grip slot). TAR PIT: Napalm slows 6% a stack, up to 55%. A mutant at the cap is stuck: every other hit it throws at the pig does nothing. Lab: +9.5 threat.

### Bandolier Lance
**Juggler** (many tanks, many swaps, Bandolier). "Narrow, long, and through the plating." A fourth tank and no time lost changing between them. Every swap hits harder than the last shot did. This one runs Thermite Slurry and is built around the Forge-Heart Throat.

- Bandolier set, five pieces: +1 tank mount on any chassis (up to 4); Swapping tanks gives +50% stack damage for 3 s; QUICK DRAW: a swap within 1 s of the last costs no swap time. Five pieces: FRESH TANK.
- Flashpoint keystone (igniter): A stack's whole burn lands the instant it is applied, at 1.4 times its total, and at 2.8 times that on anything close (the six nearest mutants, or within 220 px). Nothing lingers: Spreading, Chilling, Opportunist, Culling and Hellmouth do nothing (burn duration still counts: a longer burn lands more). A kill still sets off Toxic, Volatile and Overkill.
- Forge-Heart Throat, the exotic (nozzle): LANCE. The cone narrows to 67% of its width and reaches 40% further; everything in the line takes +60%, and its armor x3.5.
- Thermite Slurry runs hot and eats armor. With it, Rad Syrup and Rendered Lard. Home: the Scrap Mountain.
- The pieces sit on: Gusher fuel line (Flow x1.35), Bloom nozzle (Cone x2, +220% stack damage within 280 px, -20% heat), Rack chassis (+1 tank mount), Siphon pump (The active tank refills at its full idle rate while firing; +10% range), Catalyst filter (+35% vs shields and armor), Heatsink shroud (Cooling x1.6).

| Slot | Part |
|---|---|
| Fuel Line | Gusher |
| Nozzle | Bloom |
| Tank Chassis | Rack |
| Pump | Siphon |
| Igniter | Flashpoint (keystone) |
| Filter | Catalyst |
| Shroud & Grip | Heatsink |

**Set:** 5 Bandolier pieces. **Fuels:** Thermite Slurry, Rad Syrup, Rendered Lard. **Affixes:** Potent, Recycling, Sticky. **Home:** Scrap Mountain. **Lab:** threat 29.0 at T4, 31.9 at T5.

**The exotic:** Forge-Heart Throat (the exotic Thermite Slurry nozzle III, in the nozzle slot). LANCE: The cone narrows to 67% of its width and reaches 40% further; everything in the line takes +60%, and its armor x3.5. Lab: +1.7 threat.

### Last Call Fried Stiff
**Juggler** (many tanks, many swaps, Last Call). "Golden, crisp and not going anywhere." Earns its keep in the last half minute. A longer horn, a cold gun while the engine turns over, and then the horn again. This one runs Fryer Oil and is built around the Batter Mitt.

- Last Call set, five pieces: The horn sounds 15 s before the truck (not 10), and kills in its window pay x4 (not x3); The gun makes no heat while the truck is starting; ENCORE: when the truck arrives the horn sounds once more: another wave, another window, another 30 s.
- Gatling Drum keystone (chassis): Each unit fires from every mounted tank at once, each applying its own fuel's stack, and every tank refills like an idle one. Drains every tank together, each unit makes double heat, and every stack lands at 60%.
- Batter Mitt, the exotic (shroud): FRIED STIFF. A mutant Fryer Oil touched in the last 3 s is slowed 60%.
- Fryer Oil's kills come out fried and sell for more. With it, Rocket Hooch and Thermite Slurry. Home: the Dead Drive-In.
- The pieces sit on: Gusher fuel line (Flow x1.35), Fan nozzle (Cone x1.5, and +90% on every stack (a plain bonus, outside the stack damage cap)), Accumulator pump (Stores pressure while idle; the first 3 s of a burst fire up to +125% flow), Flash igniter (+55% on every stack (a plain bonus, outside the stack damage cap)), Catalyst filter (+35% vs shields and armor), Heatsink shroud (Cooling x1.6).

| Slot | Part |
|---|---|
| Fuel Line | Gusher |
| Nozzle | Fan |
| Tank Chassis | Gatling Drum (keystone) |
| Pump | Accumulator |
| Igniter | Flash |
| Filter | Catalyst |
| Shroud & Grip | Heatsink |

**Set:** 5 Last Call pieces. **Fuels:** Fryer Oil, Rocket Hooch, Thermite Slurry. **Affixes:** Potent, Recycling, Sticky. **Home:** Dead Drive-In. **Lab:** threat 27.4 at T4, 33.0 at T5.

**The exotic:** Batter Mitt (the exotic Fryer Oil shroud & grip I, in the shroud & grip slot). FRIED STIFF: A mutant Fryer Oil touched in the last 3 s is slowed 60%. Lab: +5.1 threat.

### Last Call Radiation Sickness
**Juggler** (many tanks, many swaps, Last Call). "One dose. It only gets worse for them." Earns its keep in the last half minute. A longer horn, a cold gun while the engine turns over, and then the horn again. This one runs Rad Syrup and is built around the Half-Life Altar.

- Last Call set, five pieces: The horn sounds 15 s before the truck (not 10), and kills in its window pay x4 (not x3); The gun makes no heat while the truck is starting; ENCORE: when the truck arrives the horn sounds once more: another wave, another window, another 30 s.
- Flashpoint keystone (igniter): A stack's whole burn lands the instant it is applied, at 1.4 times its total, and at 2.8 times that on anything close (the six nearest mutants, or within 220 px). Nothing lingers: Spreading, Chilling, Opportunist, Culling and Hellmouth do nothing (burn duration still counts: a longer burn lands more). A kill still sets off Toxic, Volatile and Overkill.
- Half-Life Altar, the exotic (chassis): RADIATION SICKNESS. From its first dose a mutant sickens every 2 s: 12% slower and +48% from everything each time, down to half speed and +200%.
- Rad Syrup hits harder the longer it clings. With it, Rocket Hooch and Thermite Slurry. Home: the Dead Drive-In.
- The pieces sit on: Gusher fuel line (Flow x1.35), Fan nozzle (Cone x1.5, and +90% on every stack (a plain bonus, outside the stack damage cap)), Rack chassis (+1 tank mount), Accumulator pump (Stores pressure while idle; the first 3 s of a burst fire up to +125% flow), Catalyst filter (+35% vs shields and armor), Heatsink shroud (Cooling x1.6).

| Slot | Part |
|---|---|
| Fuel Line | Gusher |
| Nozzle | Fan |
| Tank Chassis | Rack |
| Pump | Accumulator |
| Igniter | Flashpoint (keystone) |
| Filter | Catalyst |
| Shroud & Grip | Heatsink |

**Set:** 5 Last Call pieces. **Fuels:** Rad Syrup, Rocket Hooch, Thermite Slurry. **Affixes:** Potent, Recycling, Sticky. **Home:** Dead Drive-In. **Lab:** threat 27.1 at T4, 32.0 at T5.

**The exotic:** Half-Life Altar (the exotic Rad Syrup tank chassis III, in the tank chassis slot). RADIATION SICKNESS: From its first dose a mutant sickens every 2 s: 12% slower and +48% from everything each time, down to half speed and +200%. Lab: +0.5 threat.

### Moonshine Run Slick
**Juggler** (many tanks, many swaps, Moonshine Run). "Whatever you hit loses its footing and its nerve." Bigger tanks, faster hands, and every second shot carries a taste of the fuel before it. This one runs Rendered Lard and is built around the Tallow Mitt.

- Moonshine Run set, five pieces: Tanks +25% capacity, swap time -25%; Swapping tanks fires +25% flow for 2 s; STILL HOT: every other unit also applies a stack of the fuel fired before it; +30% stack damage. Five pieces: FRESH TANK.
- Reaction Chamber keystone (pump): Fuel reactions hit four times as hard: +300% reaction power. +20% heat, and a plain pump's pressure where a Booster would give more.
- Tallow Mitt, the exotic (shroud): SLICK. Whatever the gun hits, with any fuel, is slick for 2 s: slowed 50%, and it takes +30% from everything.
- Rendered Lard runs cool and sticks to flesh. With it, Rocket Hooch and Thermite Slurry. Home: the Dead Drive-In.
- The pieces sit on: Gusher fuel line (Flow x1.35), Fan nozzle (Cone x1.5, and +90% on every stack (a plain bonus, outside the stack damage cap)), Rack chassis (+1 tank mount), Flash igniter (+55% on every stack (a plain bonus, outside the stack damage cap)), Catalyst filter (+35% vs shields and armor), Heatsink shroud (Cooling x1.6).

| Slot | Part |
|---|---|
| Fuel Line | Gusher |
| Nozzle | Fan |
| Tank Chassis | Rack |
| Pump | Reaction Chamber (keystone) |
| Igniter | Flash |
| Filter | Catalyst |
| Shroud & Grip | Heatsink |

**Set:** 5 Moonshine Run pieces. **Fuels:** Rendered Lard, Rocket Hooch, Thermite Slurry. **Affixes:** Potent, Recycling, Sticky. **Home:** Dead Drive-In. **Lab:** threat 28.9 at T4, 37.2 at T5.

**The exotic:** Tallow Mitt (the exotic Rendered Lard shroud & grip I, in the shroud & grip slot). SLICK: Whatever the gun hits, with any fuel, is slick for 2 s: slowed 50%, and it takes +30% from everything. Lab: +3.5 threat.

### Moonshine Run Radiation Sickness
**Juggler** (many tanks, many swaps, Moonshine Run). "One dose. It only gets worse for them." Bigger tanks, faster hands, and every second shot carries a taste of the fuel before it. This one runs Rad Syrup and is built around the Half-Life Altar.

- Moonshine Run set, five pieces: Tanks +25% capacity, swap time -25%; Swapping tanks fires +25% flow for 2 s; STILL HOT: every other unit also applies a stack of the fuel fired before it; +30% stack damage. Five pieces: FRESH TANK.
- Reaction Chamber keystone (pump): Fuel reactions hit four times as hard: +300% reaction power. +20% heat, and a plain pump's pressure where a Booster would give more.
- Half-Life Altar, the exotic (chassis): RADIATION SICKNESS. From its first dose a mutant sickens every 2 s: 12% slower and +48% from everything each time, down to half speed and +200%.
- Rad Syrup hits harder the longer it clings. With it, Rocket Hooch and Thermite Slurry. Home: the Dead Drive-In.
- The pieces sit on: Gusher fuel line (Flow x1.35), Fan nozzle (Cone x1.5, and +90% on every stack (a plain bonus, outside the stack damage cap)), Rack chassis (+1 tank mount), Flash igniter (+55% on every stack (a plain bonus, outside the stack damage cap)), Catalyst filter (+35% vs shields and armor), Heatsink shroud (Cooling x1.6).

| Slot | Part |
|---|---|
| Fuel Line | Gusher |
| Nozzle | Fan |
| Tank Chassis | Rack |
| Pump | Reaction Chamber (keystone) |
| Igniter | Flash |
| Filter | Catalyst |
| Shroud & Grip | Heatsink |

**Set:** 5 Moonshine Run pieces. **Fuels:** Rad Syrup, Rocket Hooch, Thermite Slurry. **Affixes:** Potent, Recycling, Sticky. **Home:** Dead Drive-In. **Lab:** threat 25.5 at T4, 34.1 at T5.

**The exotic:** Half-Life Altar (the exotic Rad Syrup tank chassis III, in the tank chassis slot). RADIATION SICKNESS: From its first dose a mutant sickens every 2 s: 12% slower and +48% from everything each time, down to half speed and +200%. Lab: +2.1 threat.

### Potluck Fried Stiff
**Juggler** (many tanks, many swaps, Potluck). "Golden, crisp and not going anywhere." Light one and it passes the plate. The hungriest mutant in the yard feeds everything near it. This one runs Fryer Oil and is built around the Batter Mitt.

- Potluck set, five pieces: A burning mutant passes 5 stacks a second to each mutant touching it; 10 stacks a second, to mutants within 40 px; PATIENT ZERO: the mutant carrying the most stacks shares half of them each second with everything within 150 px (a shared stack isn't shared again).
- Gatling Drum keystone (chassis): Each unit fires from every mounted tank at once, each applying its own fuel's stack, and every tank refills like an idle one. Drains every tank together, each unit makes double heat, and every stack lands at 60%.
- Batter Mitt, the exotic (shroud): FRIED STIFF. A mutant Fryer Oil touched in the last 3 s is slowed 60%.
- Fryer Oil's kills come out fried and sell for more. With it, Rendered Lard and Thermite Slurry. Home: the Bloat Marsh.
- The pieces sit on: Gusher fuel line (Flow x1.35), Fan nozzle (Cone x1.5, and +90% on every stack (a plain bonus, outside the stack damage cap)), Accumulator pump (Stores pressure while idle; the first 3 s of a burst fire up to +125% flow), Flash igniter (+55% on every stack (a plain bonus, outside the stack damage cap)), Catalyst filter (+35% vs shields and armor), Heatsink shroud (Cooling x1.6).

| Slot | Part |
|---|---|
| Fuel Line | Gusher |
| Nozzle | Fan |
| Tank Chassis | Gatling Drum (keystone) |
| Pump | Accumulator |
| Igniter | Flash |
| Filter | Catalyst |
| Shroud & Grip | Heatsink |

**Set:** 5 Potluck pieces. **Fuels:** Fryer Oil, Rendered Lard, Thermite Slurry. **Affixes:** Potent, Recycling, Sticky. **Home:** Bloat Marsh. **Lab:** threat 28.7 at T4, 31.3 at T5.

**The exotic:** Batter Mitt (the exotic Fryer Oil shroud & grip I, in the shroud & grip slot). FRIED STIFF: A mutant Fryer Oil touched in the last 3 s is slowed 60%. Lab: +5.3 threat.

### Potluck Rocket Vent
**Juggler** (many tanks, many swaps, Potluck). "Overheat forward." Light one and it passes the plate. The hungriest mutant in the yard feeds everything near it. This one runs Rocket Hooch and is built around the Mash Mitt.

- Potluck set, five pieces: A burning mutant passes 5 stacks a second to each mutant touching it; 10 stacks a second, to mutants within 40 px; PATIENT ZERO: the mutant carrying the most stacks shares half of them each second with everything within 150 px (a shared stack isn't shared again).
- Gatling Drum keystone (chassis): Each unit fires from every mounted tank at once, each applying its own fuel's stack, and every tank refills like an idle one. Drains every tank together, each unit makes double heat, and every stack lands at 60%.
- Mash Mitt, the exotic (shroud): ROCKET VENT. An overheat with Hooch loaded doesn't hurt: it is dumped forward as 160 stacks and a 2 s stun on everything in front, and heat drops to 30% (every 5 s).
- Rocket Hooch burns hot, short and against everything. With it, Swamp Napalm and Thermite Slurry. Home: the Bloat Marsh.
- The pieces sit on: Gusher fuel line (Flow x1.35), Fan nozzle (Cone x1.5, and +90% on every stack (a plain bonus, outside the stack damage cap)), Accumulator pump (Stores pressure while idle; the first 3 s of a burst fire up to +125% flow), Flash igniter (+55% on every stack (a plain bonus, outside the stack damage cap)), Catalyst filter (+35% vs shields and armor), Heatsink shroud (Cooling x1.6).

| Slot | Part |
|---|---|
| Fuel Line | Gusher |
| Nozzle | Fan |
| Tank Chassis | Gatling Drum (keystone) |
| Pump | Accumulator |
| Igniter | Flash |
| Filter | Catalyst |
| Shroud & Grip | Heatsink |

**Set:** 5 Potluck pieces. **Fuels:** Rocket Hooch, Swamp Napalm, Thermite Slurry. **Affixes:** Potent, Recycling, Sticky. **Home:** Bloat Marsh. **Lab:** threat 27.3 at T4, 31.9 at T5.

**The exotic:** Mash Mitt (the exotic Rocket Hooch shroud & grip I, in the shroud & grip slot). ROCKET VENT: An overheat with Hooch loaded doesn't hurt: it is dumped forward as 160 stacks and a 2 s stun on everything in front, and heat drops to 30% (every 5 s). Lab: +2.7 threat.

### Test Kitchen Fried Stiff
**Juggler** (many tanks, many swaps, Test Kitchen). "Golden, crisp and not going anywhere." Two fuels on one mutant is an experiment. This set publishes the results on the two beside it. This one runs Fryer Oil and is built around the Batter Mitt.

- Test Kitchen set, five pieces: A fuel reaction lands 5% of everything burning on the mutant at once; 14%; reactions wait half as long, and each pair of fuels has its own wait (never Spatter); CHAIN REACTION: 23%, and a reaction goes off on the 2 nearest burning mutants too (never Spatter).
- Gatling Drum keystone (chassis): Each unit fires from every mounted tank at once, each applying its own fuel's stack, and every tank refills like an idle one. Drains every tank together, each unit makes double heat, and every stack lands at 60%.
- Batter Mitt, the exotic (shroud): FRIED STIFF. A mutant Fryer Oil touched in the last 3 s is slowed 60%.
- Fryer Oil's kills come out fried and sell for more. With it, Rocket Hooch and Thermite Slurry. Home: the The Food Court.
- The pieces sit on: Gusher fuel line (Flow x1.35), Fan nozzle (Cone x1.5, and +90% on every stack (a plain bonus, outside the stack damage cap)), Accumulator pump (Stores pressure while idle; the first 3 s of a burst fire up to +125% flow), Flash igniter (+55% on every stack (a plain bonus, outside the stack damage cap)), Catalyst filter (+35% vs shields and armor), Heatsink shroud (Cooling x1.6).

| Slot | Part |
|---|---|
| Fuel Line | Gusher |
| Nozzle | Fan |
| Tank Chassis | Gatling Drum (keystone) |
| Pump | Accumulator |
| Igniter | Flash |
| Filter | Catalyst |
| Shroud & Grip | Heatsink |

**Set:** 5 Test Kitchen pieces. **Fuels:** Fryer Oil, Rocket Hooch, Thermite Slurry. **Affixes:** Potent, Recycling, Sticky. **Home:** The Food Court. **Lab:** threat 31.1 at T4, 38.2 at T5.

**The exotic:** Batter Mitt (the exotic Fryer Oil shroud & grip I, in the shroud & grip slot). FRIED STIFF: A mutant Fryer Oil touched in the last 3 s is slowed 60%. Lab: +3.3 threat.

### Test Kitchen Dirty Bomb
**Juggler** (many tanks, many swaps, Test Kitchen). "Leaves everything it had to three neighbours." Two fuels on one mutant is an experiment. This set publishes the results on the two beside it. This one runs Rad Syrup and is built around the Half-Life Throat.

- Test Kitchen set, five pieces: A fuel reaction lands 5% of everything burning on the mutant at once; 14%; reactions wait half as long, and each pair of fuels has its own wait (never Spatter); CHAIN REACTION: 23%, and a reaction goes off on the 2 nearest burning mutants too (never Spatter).
- Gatling Drum keystone (chassis): Each unit fires from every mounted tank at once, each applying its own fuel's stack, and every tank refills like an idle one. Drains every tank together, each unit makes double heat, and every stack lands at 60%.
- Half-Life Throat, the exotic (nozzle): DIRTY BOMB. A mutant that dies with Rad Syrup on it throws 34% of its stacks, at their age, and 110 fresh ones onto each of 3 mutants nearby.
- Rad Syrup hits harder the longer it clings. With it, Rocket Hooch and Thermite Slurry. Home: the The Food Court.
- The pieces sit on: Gusher fuel line (Flow x1.35), Fan nozzle (Cone x1.5, and +90% on every stack (a plain bonus, outside the stack damage cap)), Accumulator pump (Stores pressure while idle; the first 3 s of a burst fire up to +125% flow), Flash igniter (+55% on every stack (a plain bonus, outside the stack damage cap)), Catalyst filter (+35% vs shields and armor), Heatsink shroud (Cooling x1.6).

| Slot | Part |
|---|---|
| Fuel Line | Gusher |
| Nozzle | Fan |
| Tank Chassis | Gatling Drum (keystone) |
| Pump | Accumulator |
| Igniter | Flash |
| Filter | Catalyst |
| Shroud & Grip | Heatsink |

**Set:** 5 Test Kitchen pieces. **Fuels:** Rad Syrup, Rocket Hooch, Thermite Slurry. **Affixes:** Potent, Recycling, Sticky. **Home:** The Food Court. **Lab:** threat 26.6 at T4, 34.6 at T5.

**The exotic:** Half-Life Throat (the exotic Rad Syrup nozzle III, in the nozzle slot). DIRTY BOMB: A mutant that dies with Rad Syrup on it throws 34% of its stacks, at their age, and 110 fresh ones onto each of 3 mutants nearby. Lab: +0.8 threat.

*Lab results: a robot pig wearing five set pieces, the keystone and the exotic, every part at T4 (and T5 for the T5 column) Malevolent with near-perfect rolls, starting at threat 16 at the build's home map, bosses, fuel reactions and all. Your results may vary. Not a toy. Do not refuel near open flame. Do not taste the Lard. Mutants were harmed in the making of this advertisement.

## Saves, settings and logs

### Saves
- **3 save slots.** The main menu's **SAVE SLOTS** shows what each holds (runs, best threat, Energy Sprinkles, time played, cats, parts, when it was saved) and has **PLAY**, **NEW GAME**, **IMPORT** and **DELETE** for each. Starting over or deleting a slot that holds a game asks first; deleting takes its backup and career journal too. The game opens on the slot you played last, and the Esc menu names it. Settings and the BALANCE menu are shared by every slot.
- **A bigger window shows more** (v0.9.56). The game no longer grows with its window: maximize it and the Smokehouse's lists and panels get taller and wider, and the fight shows more of the field (v0.9.57: mutants run in from its edge at 700 px/s and walk from where a 1280 screen's field starts, so a wide window does not slow a fight down). **UI SIZE** in Settings (50% to 200%) is how big everything is drawn; things never get so big that the game's 1280 x 720 screen no longer fits the window.
- Every version keeps its own saves, so updating never breaks your game. **IMPORT** brings the newest older version's save into a slot (that save itself isn't changed); the main menu also offers it while the slot in use has no progress.
- The game saves after every change, keeping the save before as a backup. Settings has the volume, the **MUSIC** level (v0.9.18: the ambient score, two long loops: the wastes in the Smokehouse and the menu, the burn in a run, cross-fading between them; 0 turns it off), the window size, fullscreen, fire effects, an FPS counter, VSync and a frame limit.
- **The small HUD** (v0.9.22): **[H]** in a run folds the stat window to icons and bars (the hearts, the shields, each tank's fuel icon and bar with the active one bright, the heat bar) and back to the full panel with its numbers and words; the choice is remembered.
- **The damage meter** (v0.9.71): under the materials readout in a run. One bar a damage channel, the biggest on top, the top five and the rest as OTHER; each channel keeps its colour. A bar is that channel's share of the whole fight; the number beside it and the figure at the top are damage a second over the last 5 s. The thin white line in a bar is that channel's share of what bosses took. **[N]** flips between all damage and what bosses took, **[V]** between channels and fuels, **[M]** hides it and shows it, and the game remembers. The result screen shows two meters, the whole run and what bosses took, with the total and the run's average damage a second; the career log keeps each run's meter.
- **Sounds and the score** (v0.9.18): starting the truck is an engine start (the key, the starter labouring, two coughs, the catch, the idle), and the score is synthesized from the game's own generator (tools/audio/make_audio.py), so it can be regenerated. The chef cat in the truck's serving window bobs, turns and pads back and forth behind the counter during a run.

### The BALANCE menu
- In the Esc menu and on the main menu: a slider for each of these, to try the game tuned your way: enemy toughness, enemy speed, elite chance, boss beat (0 = no bosses), boss toughness, fuel reactions (0 = off), waves a minute, mutants in a wave at threat 0, most mutants in a wave, toughness gained a threat level, seconds between bites, start threat dial: how far below your best, reputation rate, meat price, faction contracts: minutes to the next, mystery meat farm: cuts a harvest, mystery meat farm: minutes a harvest, crafting cost: energy sprinkles, crafting cost: scrap metal, crafting cost: mutant bits, crafting cost: chemicals, set blueprints: favor cost, exotic blueprints: favor price, crafting cost: tallow brick, crafting cost: napalm amber, crafting cost: slag heart, crafting cost: ion crystal, crafting cost: still copper, crafting cost: isotope seed, crafting cost: crackling.
- **LOCK** a number (or press **Space** over it) so a stray drag can't move it (RESET and RESET ALL leave it alone). Changes apply at once (mutant changes from the next wave), are saved with this version, and are written to the debug log at the start of every session, whenever they change, and with every run.

### Frame rate
- **VSYNC** on (the default) draws one frame per screen refresh, so on a 60 Hz screen the FPS counter sits at 60 however much room the machine has to spare. Turn it off to see what each fire setting really costs (the picture may tear while it's off).
- **FRAME LIMIT** caps the frames a second (30, 60, 120, 144, 165, 240); **NONE** with VSync off runs flat out. A limit keeps the graphics card cooler and quieter.
- The FPS counter is green near the limit, yellow below it and red when slow. A graphics driver set to force VSync on keeps the game at the refresh rate whatever the setting says.

### Fire effects
Every setting fires the same flamethrower: damage comes from the cone and the burn rules, never from how the fire is drawn.
- **LIVE ULTRA** (the default): the fire simulation plus burning fuel (the jet sprays fuel that catches as it flies, so it rolls and billows), fire light on the ground, the pig and the mutants, heat haze, embers and sparks, scorch marks and glowing coals where things burned, and puddles that keep burning with flames on them. v0.9.15 gave it a torch root, a deeper tonal range and smoke lit by the fire; v0.9.19 (the flame build) a **drawn flame core** (a tapered torch along the aim for the first third of the range, licking at its edges and blending into the simulation's billow, so the jet leaves the gun as one flame instead of a thin fed line), **soot** (burnt-out heat with no vapour left reads darker orange, so the body of the flame has structure that moves with the flow), **smoke puffs** (pixel-art puffs with edges, rising off burning mutants, pools, blasts and the end of the jet, over a thinner wash), an **impact splash** where the cone first touches a mutant (a flash on the body and a spray of sparks back toward the gun) with a brighter, pulsing glow on a mutant carrying 20 or more stacks, and a **rim light** on mutants within 150 px of the jet, a burning pool or a burning mutant, on the side facing the fire. v0.9.22: a wide cone (30 degrees and up) burns as **one continuous fan** instead of 2 to 5 tongues on fixed lanes: the whole sector is fed at once, blown straight out from the muzzle, with the fuel rolling across the arc as drifting sheets and thinning toward the edges, and the drawn core opens to the cone; the tongues read as prongs.
- **LIVE HIGH**: the fire simulation (the flame splashes off mutants, bends as you sweep, rains burning fuel). **LIVE LOW**: the same, chunkier and lighter on the graphics chip. **CLASSIC**: the old particle flame.
- On LIVE HIGH and ULTRA the flame's fine detail rides the flow (v0.9.82): the wisps and veins travel with the fire, stretch along the jet and curl with the billows, and the billows are shaded as rolls of flame (the side facing the gun burns a band hotter).
- More of the same study (v0.9.83). On LIVE HIGH and ULTRA the heat is carried more sharply, so the flame keeps its fine shapes further out. On LIVE ULTRA the fire's light reaches about 240 pixels across the ground and the mutants block it (one standing at the edge of the fire throws a shadow behind it), and the embers ride the fire's own air: they follow the jet and its swirls.
- **Radiance cascades** (v0.9.87, LIVE ULTRA). The fire's light is worked out a new way. Light is kept in four cascades: the lowest has a probe every 4 pixels with 4 directions and looks 6 pixels out; each one above has a quarter of the probes, four times the directions and looks four times further, and hands what it sees down. So near light is sharp, far light is smooth, and the cost does not depend on how much is burning. The light now reaches about 510 pixels (it stopped at 240), is worked out every 4 pixels (it was 8), has no grain to smooth away, and a mutant's shadow is soft-edged and reaches as far as the light does. A mutant itself is lit like the ground it stands on. The two far cascades are worked out every other frame, and none of them while nothing is burning.
- **FULL AIR GRID / HALF AIR GRID** (v0.9.83, in the settings beside the fire effects): HALF works the fire's air out on half the grid, a quarter of the work for the heaviest part of the simulation. It is lighter on the graphics chip, but a wide flame fills less of its cone and thin jets are coarser, so FULL is the default. LIVE HIGH and ULTRA only.
- If the game can't keep up (under 48 frames a second while firing, or under 80% of a lower frame limit) it steps down by itself (ULTRA to HIGH, HIGH to LOW), says so, and remembers it.

### Logs (for bug reports)
- With **Settings > DEBUG LOG** on (the default), each session writes a text file to a **logs** folder next to the game: your kit, every run in detail, hub actions, the crew and any errors. **OPEN LOG FOLDER** opens it.
- The result screen's **COPY RUN LOG** copies just that run, ready to paste.
- **Settings > DUMP CAREER** writes your whole career (every run, milestones, how the kit changed, hour by hour) to one file in the same folder.
- The Windows download is a debug build so the log catches every error; it can run a little slower than a release build would.

### This guide
- It's in the game (**F1**) and on the download page as **WIKI.md** (https://github.com/LichIndex/MMM-Malevolent-Meat-Master/blob/HEAD/WIKI.md), and both are written from the game's data by each build, so they always match the version you have.
