# Malevolent Meat Master v0.9.49: the wiki

Everything in the game, from the game's own data (written by the build you can download, so the numbers match it). The same pages are in the game: press **F1**, or **GUIDE** in the Smokehouse or the Esc menu. [Download the game](https://github.com/LichIndex/MMM-Malevolent-Meat-Master#readme).

- [Start here](#start-here)
- [Runs, threat and drops](#runs-threat-and-drops)
- [The flamethrower](#the-flamethrower)
- [Parts and loot lanes](#parts-and-loot-lanes)
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
| Energy Sprinkles (◆) | Selling smoked meat; long-haired cats | Nearly everything |
| Scrap Metal | Mutants with armor; scrapping parts; the Salvage Yard | Chassis, pumps, shrouds, the truck |
| Mutant Bits | Mutants with only health; the Salvage Yard | Fuel lines, nozzles, the kitchen |
| Chemicals | Mutants with shields; the Salvage Yard | Igniters, filters, stills |
| Sauce ingredients | Mutants (12% a kill), cats, faction shops | Sauces |
| Favor (a faction's) | Fighting on its turf; its contracts; its map's boss; breaking down its set's pieces; tuxedo cats | Its exotic blueprints, its set's blueprints, its map's featured slot, affix and behavior re-rolls while parked there |
| Harry Berries | Selling the truck (a New Truck) | The Needless Complexity Emporium |

**Three currencies** (v0.9.26): Energy Sprinkles, favor and Harry Berries. Blueprint Shards, Mutagen and Flux are gone: what paid Shards (set blueprints, the featured-slot pick, the third re-roll rung) costs favor with the place's or the set's faction, and what paid them (set pieces broken down, tuxedo cats) pays that favor; Mutagen is **Chemicals** (10 a Mutagen: elites past threat 15 drop them, scrapping Mutated and Malevolent parts gives them, behaviors and tempers cost them); a contract's or a boss's Flux is **favor** (20 a Flux). An old save's Shards, Mutagen and Flux turn into favor and Chemicals as it loads.

### A first hour
- **The tabs open in order with what you've done** (v0.9.20): LOADOUT and MAP from the start; **CRAFT** at your first salvage; **PRODUCTION** at your first raw meat; **REFINE** at your first Mutated part; **CREW** at your first hire; the **SHOWROOM** at threat 6; **AUTOMATION** when you hire the Magic 8-Ball (the Map tab's line). A line beside the tabs says what opens the next, with the note below it in its tooltip. A tab once open stays open, a link into a tab opens it, and a game with 12 runs or best threat 8 has them all (an older save loses nothing).
- Fight at the **Smokehouse Outskirts**, start the truck while you're still comfortable, and bring the meat home. A short run that gets out beats a long one that doesn't.
- Brew **Basic Rub** or **Backyard Glaze** with whatever ingredients you have, sauce the meat, and let the smoker and counter turn it into ◆.
- Spend ◆ in the **Craft** tab on better parts, and on **armor** in the Loadout tab. Scrap the salvage you won't wear: it teaches you new lanes.
- Reach threat 3 anywhere to open the **Rust Flats**; threat 6 opens tier 2 parts.
- Watch the heat bar. At 100% you have a choice (v0.9.25): hold on and the gun **redlines**, firing at half flow while the heat burns the pig (1 armor a second, then HP), or let go and it locks out for 2 s while it vents. A hold from cold lasts about 15 s.

## Runs, threat and drops

### Threat
- The threat rises one level every **30 s**. Each destination grows mutants' health, armor and shields by its own rate a level (see Destinations), and on top of that every pool toughens ×1.19 a level up to threat 11 and ×1.1 a level after it.
- They also come faster (a wave every 1.7 s at first, ×0.83 a level, down to one every 0.22 s), in packs (5% more likely a level, up to 55%) and move 2% faster a level (up to ×1.6).
- **Fewer, tougher mutants:** waves come at 80% of that pace at threat 0, falling to 60% from threat 12 on. Each mutant is tougher for the ones that don't come (×1.07 at threat 0, ×1.17 from threat 12), and as many elites still turn up, so they're a bigger share of a wave deeper in. An ordinary mutant's drops count for the ones it stands in for, so a run brings home about as much as before.
- Meat is worth **+45% of its base value per threat level**, so staying longer pays, until it doesn't.
- Your best threat anywhere opens part tiers: T2 at 6, T3 at 12, T4 at 16, and T5 (crafted only; v0.9.28) at 24.

### What mutants drop

| Drop | Chance a kill | Notes |
|---|---|---|
| Raw meat | 45% (elites always, 2 cuts) | Each mutant has its own cut. Worth its base × (1 + 0.45 × threat level). |
| Materials | 30% for each kind it carries, × the destination's bias (elites always, ×3) | Armor → Scrap Metal, shields → Chemicals, health only → Mutant Bits. 1 each, +1 every 6 threat levels. |
| Sauce ingredients | 12% (elites twice that) | From the destination's own mix. |
| Salvage crate (a part) | 1% + 0.1% a level, up to 3% | 5% of crates hold a set piece instead. |
| Keystone | 0.15% of crates from threat 15, 0.4% in Infested runs (×3 from elites) | Rare parts that break a rule (see Parts). |
| Elite Chemicals | Elites past threat 15: 12% (10 a drop) |  |
| Still blueprint | Reach the threat shown on the Map at that destination, then get out | A new fuel (see Fuels). |

- Since mutants come fewer and tougher (the waves, and half the crowd since v0.9.10), each ordinary one's chances above count for the ones it stands in for (×2.5 at threat 0, ×3.33 from threat 12); elites keep theirs and turn up as often as before. (v0.9.13: the half crowd counts too; before, half the mutants dropped half the loot.)
- **Gear thins out deeper.** Kills a minute explode as the threat rises, so from threat 6 salvage, set pieces, keystones and elite Chemicals drop ×0.88 as often each level. Meat, materials and ingredients don't thin out.
- **Salvage tiers** follow the run's threat (T2 from 6, T3 from 12, T4 from 16). Once T3 is open a crate holds one of the top two tiers; past threat 21 (Infested) only T4.
- **Salvage quality** rises with the threat, but tops out at Mutated until the run is Infested (past threat 21).
- Each destination **features one slot a day**: its parts drop ×4 as often there (the Map shows which; 60 favor with its faction picks another for the rest of the day).

### Elites
- 1% chance a spawn, +0.2% a threat level. They have ×3 the pools and an ELITE tag.
- **Waves are announced** (v0.9.25): 3 s before a wave comes, the right edge of the screen says what is in it (shielded in blue, armored in orange, flesh in pink) and, when another tank you carry does more to it, which to swap to. The swap is the read: a fuel on the wrong pool is **x0.25** (Lard, Napalm and Fryer Oil on shields or armor, Thermite on shields, Ion Gel on armor; they were x0.4 to x0.6), Lard is x1.2 against flesh (was x1), and Hooch and Rad Syrup are the generalists.
- They always drop 2 cuts, triple materials and a part: 40% of the time a set piece, otherwise salvage from 2 threat levels higher (gear thinning applies).

### Start threat
- On the Map, **START THREAT** lets a run begin at a higher threat, skipping the easy opening waves (and their drops). It reaches up to your best threat at that destination minus 3 (v0.9.25: was 7), and a dial start opens with a **warm-up wave**: for its first 30 s every kill pays ×2 meat. The smoker still needs 90 s of survival from the start.
- **A mutator a run** (v0.9.25): from best threat 10 at a place, the Map offers one mutator of your choice for the run (Armored Season, Elite Pack, Heat Wave, Static Front or Swarm; see Infested runs) for **+25% drops and meat**. It stays picked until you change it; the Infested rule past 21 adds its own on top.

### Getting out, and dying
- **E** starts the truck under you. Its engine takes 30 s to catch; the fight (and the threat) goes on until it does, then it drives you home. Survive and everything comes home.
- **The horn** (v0.9.25): 10 s before the truck comes it sounds, calling a dense wave (×3 a wave's worth), and until the truck arrives every kill pays **×3 meat**: the last seconds of a run are all in. Press **E again** before the horn for a **quiet exit**: no horn, no wave, plain meat. The Shoggoth's runs are loud, except a truck it starts for a hurt pig, which goes quietly.
- The result screen sums the run up (salvage as a count by tier). **Enter**, **Space** or **E** goes back to the Smokehouse.
- **If you die** (or abandon the run): the raw meat, fried cuts, salvage and any blueprint are lost, and you lose 10% + 5% per threat level (up to 75%) of the run's materials, ingredients and elite Chemicals. The smoker's load comes out overcooked (worth ×0.6).

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
- **v0.9.43, its logic gone over** (2,900 lab runs of the same builds with one habit changed at a time). It no longer twitches between two knots of mutants that score alike (it changed its mind 7 times a second; now 2). In a panic it pushes the gun past the heat warning only when your kit gets more fuel out that way: a cool, fast-venting gun used to sit pinned at 100% heat at half flow, burning its own armor, with a boss at the truck. **It starts the truck for a boss it can't stop:** it watches how fast the boss is going down, and if the boss will outlast the pig it leaves while the truck (30 s) can still make it, quietly. And hurt means hurt: a hurt setting at or above the pig's full health no longer starts the truck in the first second.
- On the AUTOMATION tab (RUNS): **ON/OFF** (your runs start with it driving; the 8-Ball's always do) and **when it starts the truck**: AUTO (2 threat levels under what your kit should hold there), only when hurt, or at a threat you pick. It always calls it when the pig is hurt: at 5 HP or less, or 3, 10 or 20 (v0.9.38: a setting there; it was fixed at 5).

### The Magic 8-Ball
- It runs the pig for you, one Shoggoth run after another, working a list of goals: see **Automation: the 8-Ball and the hands**. Its settings live on the AUTOMATION tab; the Map tab has one line saying what it does next. **B** switches it on and off anywhere.

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

## Parts and loot lanes

### Tiers
- Parts come in **T0** (the starter parts) to **T5**. Their names are coloured by tier: T1 white, T2 green, T3 purple, T4 gold, T5 gold-red; set pieces teal. Pips show the tier too.
- You can craft (and find) a tier once your best threat reaches it: T2 at 6, T3 at 12, T4 at 16.
- **T5** (v0.9.28). A fifth tier opens at best threat 24. v0.9.32 made it a full tier step (the lab: +1.0 threat over T4, as T3 to T4 is +0.8): a T5 line flows 60 a second to a T4's 40; a T5 shroud holds 260 heat to a T4's 200; pump, igniter and filter add +55%, +60% and +52%, and a T5 chassis carries ×2.4 tank capacity. It is **crafted only**: salvage never rolls past T4, and every T5 part is a lane part or a set piece from the Workbench, at ◆36,000 and 180 of its slot's material. Keystones and exotics stay T4. From best threat 24 the 8-Ball builds orders at T5: it crafts their lane parts and set pieces at T5 (within THE HANDS KEEP), an order and a TOP TIER budget are done at T5, and the Showroom prints each ad's T5 lab number.
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
- **Greater rolls** (v0.9.34). 5% of salvaged parts with an affix carry one **greater roll**: that affix sits at x1.5 of its top roll, marked on the card. Only a drop has one: the Workbench can't make it, Optimize can't reach it, and rerolling that affix loses it (the part's other affixes are yours to work on). Never on a keystone or an exotic. From threat 24, 10% of a crate's parts are T5.
- **FORGE UP** (v0.9.34, Refine). A lane part or a set piece goes up one tier and keeps everything done to it: affixes, behavior, the half-step, Temper. It costs 90% of crafting the part fresh at the new tier, up to your top craft tier. Keystones and exotics stay T4.
- **Sets and affixes, re-weighed** (v0.9.34). Potent, Pressurized, Recycling, Sticky and Catalytic roll half what they did (parts you own were halved to match); Bulging, Cooled and Searing kept their size. A set's stat lines now scale with its pieces' tier, and from 2 pieces each of your four best adds a plain bonus to every stack by its tier (each set's card gives its numbers). A set piece can be **re-forged to any lane**: the bonus counts the piece, the lane is yours. Every exotic adds +0% to its own fuel's stacks, outside the cap. In the lab a T5 build's affixes, keystone and set are now each worth two to three threat levels (they were 3.1, 1.6 and 1.0).
- **The half-step** (v0.9.24). A part's power is its tier, and a tier has two rungs: T3 and **T3+**, the "+" worth half the step to the next tier on the main stat and the lane's benefit lines (××1.24 on a fuel line, less where a tier's step is smaller; a "+" after the pips, and in the name). Salvage rolls it from 3 levels past the tier's unlock (certain 6 levels past); the Workbench rolls it by its level (25% at level 0, 85% at 8); Refine's **FORGE TO T+** adds it to a part for a craft and a half. A T3+ sits between T3 and T4; a plain T4 always beats it.

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

### Loot lanes
Every slot has three **lanes**: three ways to build that part, each with a benefit (▲) and a drawback (▼). A lane exists at every tier. The first lane of each slot is known from the start; you learn another by **scrapping** one of its parts, and then you can craft it at the Workbench or **re-forge** a part into it.

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
| Backfire | Locking out at 100% heat blasts 3 stacks onto every mutant in the flame | Mutated |
| Chilling | Burning mutants are slowed 20% | Mutated |
| Fixated | Each second you fire one fuel, its stacks deal +8% more (up to +160%); a swap to another fuel starts it again, and it drains 2% a second while you aren't firing | Mutated |
| Marked | Hitting an elite marks it: every stack on it deals +25% for 5 s | Mutated |
| Overkill | Damage past a kill carries to the nearest burning mutant | Mutated |
| Pent-Up | Each second you aren't firing with mutants about, your next burst charges +20% stack damage (up to +100%), spent over your next 30 units | Mutated |
| Spreading | Burns jump to 2 nearby mutants when a burning mutant dies | Mutated |
| Toxic | Kills leave a toxic cloud that burns 2 stacks a tick for 2 s (70 px) | Mutated |
| Volatile | Burning kills explode for 10% of the mutant's max health on mutants nearby (a blast's own kills don't explode) | Mutated |

### Keystones
Rare T4 parts that break one rule, at a cost. They only drop (from threat 15; more in Infested runs) and are never crafted.

| Keystone | Slot | Rule | Cost | Builds | Drops from |
|---|---|---|---|---|---|
| Can Opener | Fuel Line | Shields, armor and health all take your fuel's best multiplier, and 30% more: whatever the fuel is good against, it is good against everything | It takes the fuel line's slot: no line lane's benefit | Brawler, Lancer | threat 15 |
| Double Distill | Filter | Every stack hits x2.0: a multiplier, over every stat and cap | Each unit costs 1.25 fuel and makes 15% more heat | Lancer, Furnace | threat 15 |
| Feeding Frenzy | Nozzle | A kill streak: every kill adds +10% to all your stacks (an elite counts five), up to +250%. A wide nozzle: cone +80% | After 2 s without a kill the streak drains, four kills' worth a second | Brawler | threat 15 |
| Fever Grip | Shroud & Grip | +25% stack damage per 5% heat, and heat cap +40% | A lockout at 100% heat lasts twice as long | Furnace | threat 15 |
| Flashpoint | Igniter | A stack's whole burn lands the instant it is applied, at 1.4 times its total, and at 2.8 times that on anything close (the six nearest mutants, or within 220 px) | Nothing lingers: Spreading, Toxic and Hellmouth do nothing (burn duration still counts: a longer burn lands more) | Lancer, Brawler | threat 15 |
| Gatling Drum | Tank Chassis | Each unit fires from every mounted tank at once, each applying its own fuel's stack, and every tank refills like an idle one | Drains every tank together, each unit makes double heat, and every stack lands at 60% | Juggler | threat 15 |
| Reaction Chamber | Pump | Fuel reactions hit four times as hard: +300% reaction power | +20% heat, and a plain pump's pressure where a Booster would give more | Juggler, Lancer | threat 15 |
- **v0.9.34 (the itemization build):** every keystone was run on every build. Three had stayed worth less than a plain lane part whatever their numbers (Afterburner, Blood Line, Backdraft Ring) and were **replaced**, slot for slot, by keystones that scale off things nothing else did: **Feeding Frenzy** (a kill streak), **Reaction Chamber** (fuel reactions) and **Can Opener** (every pool takes your fuel's best multiplier). One you owned became its replacement. Gatling Drum's stacks land at 60%, Flashpoint lands x1.4 and x2.8 more on anything close, Fever Grip gives +25% a 5% of heat (was 7%); Double Distill (x2.0 on every stack) is as it was. With those the lab's forty builds split across six keystones, the largest on about a third (it was half).

### Malevolent parts
The top quality. Salvage only rolls it in Infested runs (past threat 21), each level past that adding 2 quality steps; until then it tops out at Mutated. You can still craft one, or upgrade a part's quality at the Workbench (the last step, Mutated to Malevolent, costs ×0.4).

## Sets

- **Eight sets outside the styles** (v0.9.39), eighteen sets in all. Hot Plate, Nutcracker, Walk-In Freezer, Potluck, Test Kitchen, Oven Mitts, Whole Hog and Last Call belong to no style and have no T5 effect: any build can wear them, each does one thing no other set does, and two of them (Whole Hog, Last Call) add no damage at all. They are listed after the style sets below. A build has six set slots beside its keystone, so a second set is paid for in pieces of the first: in the lab, giving up 2, 3 or 4 of a finished T5 build's own six pieces cost it about 0.7, 1.8 or 2.7 threat levels, and the six that deal damage were sized to give about that back on the builds they suit. Whole Hog and Last Call give back less, and pay in what comes home.
- **Three of them need something burning** (v0.9.39): Oven Mitts' Cooked, Potluck and Test Kitchen count stacks on a mutant or fuel reactions, so they do nothing under the Flashpoint igniter, which lands a stack's whole burn at once. Hot Plate, Nutcracker and the Freezer work with it (Nutcracker best of all).
- **Ten sets for the five styles** (v0.9.24; fifteen from v0.6.10: Pit Boss, Steeple Works, Foundry Rig, Thrift Shop and Cocktail Hour are retired, each into the other set of its style, which took its best line; their pieces, blueprints and ads in an old save become the survivor's, and their homes are the survivors' second homes). Every set has a piece for each of the seven slots. Wearing **2, 3 and 4 pieces** turns on its three bonuses, and every bonus works on **every fuel** (since v0.7.8). A piece is a normal part of its tier and slot with affixes of its own, and **its lane is fixed** (v0.9.24; it rolled a random lane before, which left a build's set and its lanes at odds): the Showroom's builds wear their set pieces on the lanes the pieces are.
- **The 4-piece mechanics carry the set** (v0.9.24). The lab found a set worth about 0.6 threat levels and its stat lines no lever at all (doubling them moved a build 0.1), so the mechanics were raised instead: Grease Fire's kills explode for 6 stacks in a 120 px blast, Battered is +8% a stack up to +300% (and +150% close), Arc chains to 6 and chained stacks hit double, Critical Mass needs 30 stacks, Cold Start charges +60% a second to +200% and its chill is 30%, Still Hot is every other unit, and a Bandolier swap is +50% for 3 s. Mind that **Flashpoint** lands a stack's whole burn at once, so anything that counts the stacks *on* a mutant (Battered, Critical Mass, Hellmouth's endless burn, stacks outside the cone) does nothing with it; the Showroom says so on the ads it applies to.
- **Where they drop:** set pieces come from salvage crates (5% of them) and elites (40%). A set piece found at a destination comes 70% of the time from a set that drops there; the rest from any common set, and 5% from a rare one.
- **Blueprints:** breaking a piece down (Loadout > Stash) gives 10 + 2 × its quality favor with the set's faction (Blueprint Shards before v0.9.26), times (1 - 0.75 × the share of set blueprints you own; v0.8.2), so ×0.25 once you own them all. A set's blueprint costs 30 Shards (Workbench > SETS), then you craft its pieces for ◆ and materials. Faction reputation gives some blueprints too, and Hellmouth's needs one found Hellmouth piece first (or the Glow Cult's top reputation).

### Deep Fryer
Brawler build · all fuels · drops at the The Flesh Farms
- **2 pieces:** Kills drop +25% raw meat; +40% stack damage
- **3 pieces:** +150% stack damage within 220 px
- **4 pieces:** BATTERED: mutants within 220 px take +8% per stack on them (up to +300%)
- **Five pieces:** Flare-up. Each T5 piece of the five adds 6.6%. A volley landing on something close (the six nearest mutants, or within 220 px) that flares hits x2 and costs no fuel.
- **Every piece:** From 2 pieces, each of your four best adds to every stack by its tier (T1 to T5): 0.9% / 1.5% / 2.4% / 3.3% / 4.2%.

### Grease Fire
Brawler build · all fuels · drops at the Smokehouse Outskirts
- **2 pieces:** Stacks +60% damage
- **3 pieces:** Burning kills splash 2 stacks nearby
- **4 pieces:** GREASE FIRE: burning kills explode for 6 stacks in a wide blast; +60% stack damage
- **Five pieces:** Flare-up. Each T5 piece of the five adds 6.6%. A volley landing on something close (the six nearest mutants, or within 220 px) that flares hits x2 and costs no fuel.

### Meltdown
Lancer build · all fuels · drops at the Reactor Row
- **2 pieces:** Aging fuels (Rad Syrup) age 25% faster, +20% vs elites and bosses, and +20% stack damage beyond 300 px
- **3 pieces:** Elites and bosses take +25% more from every fuel
- **4 pieces:** CRITICAL MASS: a mutant carrying 30+ stacks of one fuel takes +50% from every burn
- **Five pieces:** Long Shot. Each T5 piece of the five adds 10.8%. A volley that takes it hits x2 and reaches 25% further.
- **Every piece:** From 2 pieces, each of your four best adds to every stack by its tier (T1 to T5): 3.6% / 6% / 9.6% / 13.2% / 16.8%.

### Tesla Coilworks
Lancer build · all fuels · drops at the Glow Crater
- **2 pieces:** +30% vs shields
- **3 pieces:** Breaking a shield stuns for 1 s
- **4 pieces:** ARC: every hit chains to 6 nearby mutants, and chained stacks deal +100%
- **Five pieces:** Long Shot. Each T5 piece of the five adds 10.8%. A volley that takes it hits x2 and reaches 25% further.
- **Every piece:** From 2 pieces, each of your four best adds to every stack by its tier (T1 to T5): 6% / 10% / 16% / 22% / 28%.

### Boiler Room
Furnace build · all fuels · drops at the Smelter Pits
- **2 pieces:** Heat cap +25%, +35% stack damage
- **3 pieces:** Stacks +1.2% for every 1% of heat (up to +120% at full heat)
- **4 pieces:** PRESSURE COOKER: reaching 100% heat starts 3 s without a lockout and +50% flow, then the gun locks out and vents to 0 (once per 45 s); +60% stack damage
- **Five pieces:** Blowoff. Each T5 piece of the five adds 20%. At 50% heat or more, a volley that takes it hits x2 and stuns what it hits for 0.3 s.
- **Every piece:** From 2 pieces, each of your four best adds to every stack by its tier (T1 to T5): 4.8% / 8% / 12.8% / 17.6% / 22.4%.

### Hellmouth (rare)
Furnace build · all fuels · drops anywhere
- **2 pieces:** All fuels +220% stack damage
- **3 pieces:** All fuels +20% burn duration and +30% stack damage
- **4 pieces:** HELLMOUTH: stacks stop expiring while the mutant stays in the cone
- **Five pieces:** Blowoff. Each T5 piece of the five adds 20%. At 50% heat or more, a volley that takes it hits x2 and stuns what it hits for 0.3 s.

### Glacier Works
Miser build · all fuels · drops at the Sewer Delta
- **2 pieces:** The gun cools 50% faster
- **3 pieces:** Burning mutants slow 30%
- **4 pieces:** COLD START: Pent-Up without the behavior (+60% a second idle, up to +200%), twice as fast with it; +40% stack damage
- **Five pieces:** Second Helping. Each T5 piece of the five adds 15.6%. A volley that takes it hits x2 and costs no fuel.
- **Every piece:** From 2 pieces, each of your four best adds to every stack by its tier (T1 to T5): 3.6% / 6% / 9.6% / 13.2% / 16.8%.

### Slow Cooker
Miser build · all fuels · drops at the Fungal Bog
- **2 pieces:** +25% burn duration; tanks regen +1.5 units/s while you aren't firing
- **3 pieces:** Stacks on mutants outside the cone deal +45% damage
- **4 pieces:** SIMMER: every 10th unit applies 2 stacks, and stacks outside the cone deal +25% more; all fuels +57% stack damage
- **Five pieces:** Second Helping. Each T5 piece of the five adds 15.6%. A volley that takes it hits x2 and costs no fuel.
- **Every piece:** From 2 pieces, each of your four best adds to every stack by its tier (T1 to T5): 4.2% / 7% / 11.2% / 15.4% / 19.6%.

### Bandolier
Juggler build · all fuels · drops at the Scrap Mountain
- **2 pieces:** +1 tank mount on any chassis (up to 4)
- **3 pieces:** Swapping tanks gives +50% stack damage for 3 s
- **4 pieces:** QUICK DRAW: a swap within 1 s of the last costs no swap time
- **Five pieces:** Fresh Tank. Each T5 piece of the five adds 14.4%. A volley that takes it hits x2 and makes no heat.
- **Every piece:** From 2 pieces, each of your four best adds to every stack by its tier (T1 to T5): 3.6% / 6% / 9.6% / 13.2% / 16.8%.

### Moonshine Run
Juggler build · all fuels · drops at the Dead Drive-In
- **2 pieces:** Tanks +25% capacity, swap time -25%
- **3 pieces:** Swapping tanks fires +25% flow for 2 s
- **4 pieces:** STILL HOT: every other unit also applies a stack of the fuel fired before it; +30% stack damage
- **Five pieces:** Fresh Tank. Each T5 piece of the five adds 14.4%. A volley that takes it hits x2 and makes no heat.
- **Every piece:** From 2 pieces, each of your four best adds to every stack by its tier (T1 to T5): 0.9% / 1.5% / 2.4% / 3.3% / 4.2%.

### Walk-In Freezer
Any build · all fuels · drops at the Static Fields
- **2 pieces:** Burning mutants slow by 6% a second, up to 40%
- **3 pieces:** At full chill a mutant freezes for 2 s, once every 6 s (a boss 1 s)
- **4 pieces:** SHATTER: a frozen mutant that dies bursts for 25% of its health onto mutants within 100 px; a frozen mutant under 15% health breaks
- **Five pieces:** Cold Snap. Each T5 piece of the five adds 9.6%. A volley that takes it hits x2 on every mutant that is slowed, stunned or frozen and stuns them for 0.02 s.

### Hot Plate
Any build · all fuels · drops at the Smelter Pits
- **2 pieces:** The far end of your flame leaves a burning patch (4 s): 32 stacks a second on mutants in it
- **3 pieces:** The patch burns 64 stacks a second and slows mutants on it 30%
- **4 pieces:** FIREBREAK: 96 stacks a second, and patches that touch last as long as any one is fed
- **Five pieces:** Sear. Each T5 piece of the five adds 20%. A volley that takes it hits x2 on everything at the far end of your flame (the last 50% of its reach) and stuns them for 0.7 s.
- **Every piece:** From 2 pieces, each of your four best adds to every stack by its tier (T1 to T5): 3% / 5% / 8% / 11% / 14%.

### Last Call
Any build · all fuels · drops at the Dead Drive-In
- **2 pieces:** The horn sounds 15 s before the truck (not 10), and kills in its window pay x4 (not x3)
- **3 pieces:** The gun makes no heat while the truck is starting
- **4 pieces:** ENCORE: when the truck arrives the horn sounds once more: another wave, another window, another 30 s
- **Five pieces:** One More Round. Each T5 piece of the five adds 20%. For 15 s after the threat level rises, a volley that takes it hits x2 and makes no heat.
- **Every piece:** From 2 pieces, each of your four best adds to every stack by its tier (T1 to T5): 3% / 5% / 8% / 11% / 14%.

### Nutcracker
Any build · all fuels · drops at the Tank Graveyard
- **2 pieces:** A broken shield drops Chemicals and broken armor drops Scrap; +40% vs shields and armor
- **3 pieces:** A shell that breaks bursts: 60% of it comes off the same shell of mutants within 120 px
- **4 pieces:** CRACK: the burst is 120%, and a shell a burst breaks bursts too
- **Five pieces:** Seam. Each T5 piece of the five adds 20%. A volley that takes it hits x3 on every mutant with a shield or armor still up and stuns them for 0.3 s.
- **Every piece:** From 2 pieces, each of your four best adds to every stack by its tier (T1 to T5): 1.5% / 2.5% / 4% / 5.5% / 7%.

### Oven Mitts
Any build · all fuels · drops at the Rust Flats
- **2 pieces:** The pig heals 1 HP each time the threat level rises
- **3 pieces:** COOKED: a mutant carrying 30 or more stacks does no damage when it reaches you
- **4 pieces:** SECOND WIND: once a run, a hit that would kill you leaves you at 3 HP with full armor and lights everything near the truck
- **Five pieces:** Hot Handle. Each T5 piece of the five adds 20%. A volley that takes it hits x2 on everything close (the six nearest mutants, or within 220 px) and stuns them for 0.3 s.

### Potluck
Any build · all fuels · drops at the Bloat Marsh
- **2 pieces:** A burning mutant passes 5 stacks a second to each mutant touching it
- **3 pieces:** 10 stacks a second, to mutants within 40 px
- **4 pieces:** PATIENT ZERO: the mutant carrying the most stacks shares half of them each second with everything within 150 px (a shared stack isn't shared again)
- **Five pieces:** Heaped Plate. Each T5 piece of the five adds 7.2%. A volley that takes it hits x2 on every mutant already carrying 20 stacks or more and makes no heat.

### Test Kitchen
Any build · all fuels · drops at the The Food Court
- **2 pieces:** A fuel reaction lands 5% of everything burning on the mutant at once
- **3 pieces:** 14%; reactions wait half as long, and each pair of fuels has its own wait (never Spatter)
- **4 pieces:** CHAIN REACTION: 23%, and a reaction goes off on the 2 nearest burning mutants too (never Spatter)
- **Five pieces:** Eureka. Each T5 piece of the five adds 6%. A volley that takes it hits x2 on every mutant a reaction went off on in the last 3 s and makes no heat.

### Whole Hog
Any build · all fuels · drops at the The Flesh Farms
- **2 pieces:** Every kill drops its materials
- **3 pieces:** Elites and bosses drop their hoard twice (not the meat)
- **4 pieces:** NOSE TO TAIL: a run that gets out brings one more crate for every boss killed, at a better quality
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
| Filter | Jelly Sieve | SEEPS THROUGH: Under a shield or armor, Napalm burns the health beneath at x1.5. On bare health it hits +80% |
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
| Filter | Crucible Sieve | CRACKED OPEN: Armor Thermite breaks stuns everything within 160 px for 2 s, and that mutant takes +200% from everything for 6 s |
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
| Swamp Napalm | Bog-Gas Fermenter | Sewer Delta, threat 4 | 1 | ×1.35 / ×0.25 / ×0.25 | ×1.6 | ×0.8 | - | Gelled bog-gas. Burns forever, mostly on meat. |
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
v0.9.3. A run brings the map's boss: one of its mutants grown huge (1.9x the size, 55% of the speed), with 14 times an elite's pools, shared out by the map's theme. v0.9.18: bosses come on a beat: at every threat level a run reaches that is a multiple of 5 (from threat 4 up), with a warning line 10 s before, one at a time (a boss still alive at the next beat holds it until it dies; the BALANCE menu's bosses knob scales the beat, 0 turns them off). It counts as an elite. At the truck it doesn't vanish like a mutant: it stays and hits for **3** armor or HP every 2.5 s until it dies. It drops **Flux** like a contract: 1 + threat / 10 (v0.9.18), so a fighter who never deals can still temper.

- **How they look** (v0.9.40). Every mutant is a different creature on each map theme: mutated flesh wearing the junk that lies around that kind of place. Each theme has its own boss body (The Furnace on Balanced maps, The Stack on Armor, The Twin Dynamo on Shield, The Skullsquid on Health; The Stack and The Skullsquid have a second body that every other one of their maps wears), and each map's boss wears its own piece on its head. An elite carries a radiation sign over its bars; a boss carries a burning skull. Its size to hit is as before.
- **Its pools follow the map's theme.** Health maps: 90% health. Armor maps: 72% armor. Shield maps: 72% shields. Balanced maps: a third each. Bring the fuel that answers the theme.
- **Its hoard:** 4 of the map's exotic material, +1 every 4 threat levels (at a place with none of its own, one of its theme-mates'), from any threat, and a 50% chance of a keystone, on top of an elite's drops.
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
- **Theme:** Armor. **Growth a level:** health ×1.12, armor ×1.28, shields ×1.1.
- **Common mutants:** Platehide. **Extra drops:** Scrap Metal ×2.
- **Sets:** Oven Mitts. **Still blueprints:** Crucible Furnace (threat 4). **Exotic material:** none.

#### Scrap Mountain
Tin Monks turf. A peak of crushed cars; platehides and creepers climb it in swarms.
- **Unlock:** needs Rust Barons reputation 2. **Market:** Tin Monks turf.
- **Theme:** Armor. **Growth a level:** health ×1.12, armor ×1.28, shields ×1.1.
- **Common mutants:** Platehide, Creeper. **Extra drops:** Scrap Metal ×2.
- **Sets:** Bandolier. **Still blueprints:** none. **Exotic material:** Still Copper (threat 10).

#### Tank Graveyard
Ironsides turf. Rusted tanks in rows; behemoths wear the turrets.
- **Unlock:** needs Tin Monks reputation 1. **Market:** The Ironsides turf.
- **Theme:** Armor. **Growth a level:** health ×1.12, armor ×1.28, shields ×1.1.
- **Common mutants:** Platehide, Behemoth. **Extra drops:** Scrap Metal ×2.
- **Sets:** Nutcracker. **Still blueprints:** none. **Exotic material:** none.

#### Smelter Pits
Slag Brothers turf. Open furnaces; the platehides come out glowing hot.
- **Unlock:** needs The Ironsides reputation 1. **Market:** Slag Brothers turf.
- **Theme:** Armor. **Growth a level:** health ×1.12, armor ×1.28, shields ×1.1.
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
- **Theme:** Health. **Growth a level:** health ×1.2, armor ×1.12, shields ×1.1.
- **Common mutants:** Behemoth, Creeper. **Extra drops:** Mutant Bits ×2.
- **Sets:** Glacier Works. **Still blueprints:** Bog-Gas Fermenter (threat 4). **Exotic material:** none.

#### The Flesh Farms
Meat Ranchers turf. Pens of mutant cattle that got loose; the behemoths are the bulls.
- **Unlock:** needs Sewer Kings reputation 1. **Market:** Meat Ranchers turf.
- **Theme:** Health. **Growth a level:** health ×1.2, armor ×1.12, shields ×1.1.
- **Common mutants:** Behemoth, Drudge. **Extra drops:** Mutant Bits ×2.
- **Sets:** Deep Fryer, Whole Hog. **Still blueprints:** Deep-Fry Drum (threat 12). **Exotic material:** none.

#### Fungal Bog
Spore Mothers turf. Knee-deep mushrooms; drudges sprout from the mud.
- **Unlock:** needs Meat Ranchers reputation 1. **Market:** Spore Mothers turf.
- **Theme:** Health. **Growth a level:** health ×1.2, armor ×1.12, shields ×1.1.
- **Common mutants:** Drudge, Leaker. **Extra drops:** Mutant Bits ×2.
- **Sets:** Slow Cooker. **Still blueprints:** none. **Exotic material:** Napalm Amber (threat 10).

#### Bloat Marsh
Gluttons' Court turf. A swamp of rendered fat; the biggest behemoths wallow here.
- **Unlock:** needs Spore Mothers reputation 1. **Market:** Gluttons' Court turf.
- **Theme:** Health. **Growth a level:** health ×1.2, armor ×1.12, shields ×1.1.
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
| Glowberry Syrup | 0 / 4 / 1 | sold for ◆120 by Reel Cult (reputation 3), Mallrat Gangs (reputation 3), Rust Barons (reputation 3), Reactor Choir (reputation 3), Neon Saints (reputation 3), Storm Callers (reputation 3), Gluttons' Court (reputation 2); calico cats |
| Marrow Butter | 1 / 0 / 4 | sold for ◆120 by Bazaar Hagglers (reputation 3), Tin Monks (reputation 3), Slag Brothers (reputation 3), Glow Cult (reputation 2), Meat Ranchers (reputation 3), Spore Mothers (reputation 3), Gluttons' Court (reputation 3); calico cats |
| Ghost Chili Paste | 4 / 0 / 2 | sold for ◆120 by Mallrat Gangs (reputation 2), The Ironsides (reputation 3), Slag Brothers (reputation 2), Storm Callers (reputation 2), Sewer Kings (reputation 2); calico cats |

### Smoking
- The smoker holds 40 cuts, +40 per Smoker level. In a run it cooks (time survived / 90 s) of its load; if you die, the load comes out overcooked (×0.6).
- Between runs (and with the game closed) it smokes at 50% that speed, a batch at a time, loading itself from your sauced meat (the cuts worth most to the faction you sell to first: v0.9.18, one sell-to, the faction whose turf the truck is parked on; the MEAT panel's **SELL TO** buttons park it, and the smoker's own target picker is gone).

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

- Cooked in the Kitchen (**FEAST**) from 20 + 2 × T cuts of its kind (raw, sauced or smoked), 5 + T/2 of each ingredient and ◆50 × T^1.5 (T: your best threat, up to 30). The next run eats it (not the Gauntlet). **EVERY RUN** (on the feast, in the Kitchen; v0.9.17) cooks the one you pick before each run, yours and the 8-Ball's, whenever you have what it takes.

### Selling
- Park the truck on a destination (Map tab, or SELL TO in the Kitchen's MEAT panel) to sell to its faction: the one sell-to (v0.9.18), which the smoker and the chef read too. **Smoked meat sells the moment it is smoked** (v0.9.26): a run's load sells as the truck gets home and the result says what it made; the between-runs smoker's loads sell as each finishes. The counter's speed, the drip and the glut are gone; each Serving Counter level adds +5% to every cut's price.
- **Price of a cut** = its value × the sauce's value × **fit** × favourite cut (×1.25) × the Serving Counter's levels.
- **Fit is three bands** (v0.9.26): a sauce within 1.5 taste points of what the faction wants (straight-line across spicy, sweet and savory) is **RIGHT** (×1.4), within 3.5 **NEAR** (×1), else **WRONG** (×0.7). The Map's faction panel shows what each wants and which band your sauces land in; the Kitchen says it as you set the dials. The neutral Outskirts market pays ×0.9 whatever the sauce. No fads, no fatigue: a faction wants what it wants, and selling it the same thing all day pays the same.

## The Smokehouse

The hub between runs. Tabs: **Loadout**, **Craft**, **Refine**, **Production**, **Map**, **Crew**; the cat counter is always on the right. **HIDE MAP** in Production folds the yard picture into a short list of the buildings and widens the panel.

### Loadout
- The seven part slots, the fuel in each tank, and armor. The preview pig rebuilds as you swap.
- **Loadouts:** save the gun under a name and put it back on later; copy or import a build code to share one; **ORDER THIS BUILD** makes a custom order from one (v0.9.18). Every 8-Ball order for you keeps one of its own, **ORDER: <NAME>**, kept up to date with the best you own for it (v0.8.8; orders for a cat keep none since v0.9.12).
- **Stash:** filter by worn, unworn, on the crew, locked, unlocked, exotics, keystones (v0.9.7), tier, slot or lane. **Lock** a part to protect it (**Space** locks or unlocks the selected part, here and in the Refine tab). **Scrap** a part (or **SCRAP SHOWN** for everything the filters show: the one bulk scrap since v0.9.17, with FAILS LOOT FILTER and NO ORDER WANTS among the filters) for materials; a set piece is broken down for its faction's favor instead. Parts you or a cat wear, locked parts and parts in a saved loadout are never scrapped. SCRAP SHOWN takes keystones the list shows too (v0.9.12; lock one to keep it), but not exotics; the loot filter and the 8-Ball never scrap a keystone.
- **Scrapping** returns 50% of the part's crafting materials (by quality) plus 1 + 2 per tier Scrap Metal, teaches you its lane and gives Chemicals for Mutated (1) and Malevolent (5) parts.
- **EQUIP BEST** (top left of the Loadout tab): with the Magic 8-Ball holding an order, the best you have for that ad (its keystone, its lanes highest tier first, 4 of its set's pieces, its exotic upgrade and its fuels); otherwise the parts that give the kit the most **power** (the estimate the crew and the Shoggoth use), keeping a keystone you wear and any set bonus you've reached, leaving your fuels alone. It never takes a part off a cat. It is the one dressing button (v0.9.17): a Showroom ad's **EQUIP BEST: THIS BUILD** is it for that ad and whoever the ad is for, the Crew tab's **EQUIP BEST: ITS ORDER** and **EQUIP BEST: FREE PARTS** are it for a cat. They say which of the build's parts someone else is wearing (v0.9.7).
- **A blocked change says why** (v0.9.7): a fuel with no still, a mount the chassis doesn't have (v0.9.29: cats wear no parts, so none of a cat's). A red message names it.
- **Loot filter** (the LOOT FILTER row on the Loadout tab; rebuilt in v0.9.46). A filter is a list of **rules**; the first rule a part matches decides: KEEP, SCRAP, KEEP AND LOCK, KEEP AND MARK (a coloured tag) or KEEP THE BEST N (the worst one it holds is scrapped to make room). A rule's conditions all have to hold, any can be turned round with NOT, and a condition with several values holds for any of them. Conditions: tier, quality, slot, lane, a + part, a set piece (any, or named sets), a keystone, an exotic, its fuel, **named affixes** (at least 1, 2 or 3 of the ones you list, rolled anywhere, in the top half or the top quarter of their range), an affix for a loaded fuel, a **named behavior**, temper, a mark, and comparisons: beats what you wear on its lane, beats the best you own on its lane, you already own N as good, a saved loadout would take it, an order wants it, your kit is stronger with it. Better means tier, then quality, then +, then how many of the rule's affixes it has. **MY FILTER** keeps its panel of switches (they write the rules marked *) and takes rules of your own above them; **named filters** are rules only, and your runs, the 8-Ball's runs and the crew's trips each use the one you pick. Ready-made: STARTER, LIGHT, TIER, UPGRADES, NO ORDER WANTS (what SCRAP WHAT NO ORDER WANTS did: it is a filter now, not a switch), ENDGAME, and one written from any order. A crafted T5 part and the **first** copy of a keystone or an exotic are always kept; extra copies follow the rules. Every rule counts what it kept and scrapped, the debug log names the rule that scrapped each part, REPLAY shows what a filter would have done with the last run's loot, and COPY AS TEXT and the paste box move a filter between saves. A rule's SHOW button lists the stash parts it matches (the stash's SHOW list: MATCHES THE SEARCH), and a search can be saved. **SHOW THOSE n IN THE STASH** lists what the filter would take (FAILS LOOT FILTER), for SCRAP SHOWN. A new game's filter is on and keeps upgrades over what you wear, sets and Malevolent parts.

### Craft and Refine (the Workbench)
- **CRAFT tab, PARTS:** pick a slot and a tier, then any lane you know. A part costs ◆ plus its slot's material (6, 15, 35, 80, 180 for T1 to T5). Workbench levels raise the odds of a better quality.
- **CRAFT tab, SET BLUEPRINTS:** buy set blueprints with the set's faction's favor and craft the pieces (they roll a lane at your best tier). **BENCH:** Workbench upgrades, quality odds and the lane blueprints you know.
- **REFINE tab:** filter the parts on the left (worn, unworn, on the crew, locked, in a loadout, with a behavior, below Malevolent; slot, lane, tier, quality, or an affix the part carries), pick one, and refine it on the right. **REFINE THIS PART** in the Loadout tab opens it there. **Favor re-rolls** (v0.9.14): next to REROLL and MUTATE, the same roll for the favor of the faction whose turf the truck is parked on: 100 × (1 + tier) favor for an affix (a T4 one: 500), twice that for the behavior; flat, with no escalation.
  - **Quality up** one step at a time (◆ and materials; Mutated to Malevolent costs ×0.4).
  - **Reroll** one affix (◆; the second affix you touch on a part adds materials, the third favor with the parked faction). Each try on the same affix costs 30% more, up to ×2.
  - **Optimize** an affix: +10% of its range toward the top, paid in the slot's material.
  - **Mutate** the behavior (or add one at Mutated quality and up) for Chemicals: 10 (T1 and T2), 20 (T3), 40 (T4).
  - (v0.9.26: it was Mutagen: 1, 2 and 4.
  - **Re-forge** a part into another lane of its slot that you know, keeping its tier, quality, affixes and behavior, for twice the tier's material and a quarter of the part's price.
  - **Temper** (v0.8.2) a Malevolent T4 or T5 part, +1 to +10: each level lifts its primary stat, its lane's benefit lines and its affix rolls (+2% for the first level, a little less each level after, ×1.16 at +10). Level n costs ◆12,000 × 1.5^(n-1), 60 × n of the slot's material and 2 × 1.5^(n-1) × 10 Chemicals (v0.9.26: it was Mutagen; v0.9.24: no Shards and no Flux any more). A tempered part shows +n after its name.

### The yard and the shack

| Upgrade | Where | What it does | Max level | First level |
|---|---|---|---|---|
| Workbench | Shack | Crafted parts roll higher qualities. | 8 | ◆250 + 5 Scrap Metal |
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
| High-Five Machine | Cats | A spring-loaded paw high-fives the cat on the counter by itself, at half the rate cats arrive (offline too). Pick the coats it stops at, to hire them. | 1 | ◆3,000 + 40 Scrap Metal + 20 Mutant Bits |

Prices in ◆ rise with each level; materials rise a step each level.

- **The second band** (v0.8.2; v0.9.27: six levels, was ten, and no Shards). The Kitchen, Pantry, Storage Shed, the Salvage Yard, the Catnip Plant, the Smoker, the Serving Counter and the Bigger Counter go 6 levels past their old top at steep prices: level max+k costs the last old level's ◆ × 2 × 1.25^(k-1), plus 60 × k of each of the building's materials. Each level does what the building's levels always did (the Shed adds 600 storage a level there, the Pantry 50, the Salvage Yard 18 of each material an hour; the Kitchen's levels 9 and 10 raise the taste ceiling). The Overseer buys them too.
- **Folded buildings** (v0.9.27). The Freezer is the Pantry's first 5 levels (each halves how fast raw meat spoils); the Spice Rack, Sugar Press, Stock Pot and Flavor Overdrive are the Sauce Kitchen's levels; the Scrap Sifter, Rendering Vat and Sludge Drip are one Salvage Yard that makes all three materials. An older save gets the Sprinkles it spent on them back, and its vats' highest level as the Yard's.
- **Storage** (v0.8.2: for everything). Each material holds 150, +150 per Storage Shed level, and each ingredient 20, +20 per Pantry level. Runs, crew trips, scrapping, cats and vats all stop at these: what doesn't fit is **sold** for 0.25 Sprinkles a unit of material and 1 an ingredient (the result screen says STORAGE FULL). What you already hold past a cap is kept.

### While you're away
Brewing, the vats, spoilage, fatigue, cats, the smoker, sales and crew trips all run on real time and catch up when you come back.

## Cats and the crew

### The cat counter
- Stray cats line up at the counter, one every 20 s (25% faster per Catnip Plant level). Up to 10 wait in line, +5 per Bigger Counter level.
- **Coming next** (v0.9.29). The counter shows the next 3 coats on their way, rolled ahead, so a Tuxedo or an Eldritch cat coming up is something to wait for (RARE!). Switching lures re-rolls them.
- **High five** the cat at the front for what it brings, or **hire** it for your crew.
- **High-Five Machine** (v0.9.7; ◆3,000 + 40 Scrap Metal + 20 Mutant Bits, at the counter): high-fives the cat at the front by itself, at 50% the rate cats arrive, offline too. Its one setting (v0.9.29: there is no off switch) is the coats it **stops at** (v0.9.8): it waits while one is at the front of the line, so you can hire it, and says so.

| Cat | High five brings | How often | Knack on the crew |
|---|---|---|---|
| Long-haired cat | Energy Sprinkles (2 + 0.5 per best threat level) | 25% | Brings home 25% more meat |
| Short-haired cat | Scrap Metal | 15% | +50% Scrap Metal |
| Glowing cat | Chemicals | 13% | +50% Chemicals |
| Mutant cat | Mutant Bits | 13% | +50% Mutant Bits |
| Hairless cat | a sauce ingredient | 13% | Twice the sauce ingredients |
| Calico cat | a rare ingredient | 7% | 1 in 4 ingredients it finds is a rare one |
| Tuxedo cat | 1 to 2 favor with the parked faction | 5% | Finds set pieces twice as often |
| Radiant cat | 10 Chemicals | 4% | Elite Chemicals from threat 10 (not 15), twice as often |
| Hoarder cat | 1 to 3 of a random exotic material | 3% | Exotic materials drop twice as often on its trips |
| Eldritch cat | a keystone, rolled like salvage at threat 15 or your best | 1% | Finds keystones twice as often |

**Lures** (bought once, one active at a time) make a group of cats show up ×3 as often:
- **Brushed Yarn** (◆250): Long-haired cats (Energy Sprinkles) show up 3x as often.
- **Laser Pointer** (◆250): Material cats (short-haired, glowing and mutant) show up 3x as often.
- **Glowing Fish** (◆250): Ingredient cats (hairless and calico) show up 3x as often.

### The crew
- Hire up to **3 cats** off the counter: ◆300, ◆2,000, ◆8,000 for the first, second and third. Its coat is its knack (table above).
- **Cats wear no parts** (v0.9.29). A cat's strength on its trips is three things: the **Crew Training** building at the cat counter (every cat holds threat 4 + 2 a level, to 24 at level 10; the Overseer's cat counter group buys it), its coat's knack, and a **trait** it rolls when hired, shown on its card and the Crew tab:
  - **Brave**: Holds 2 threat levels more.
  - **Glutton**: Brings home 50% more meat, holds 1 level less.
  - **Scrounger**: Finds 50% more salvage crates.
  - **Sprinter**: Short trips (15 and 60 minutes) get half again as many kills.
  - **Nightcat**: Long trips (4 and 8 hours) get a third more kills.
  - **Plated**: Holds 3 levels more on the Armor maps.
  - **Shielded**: Holds 3 levels more on the Shield maps.
  - **Wader**: Holds 3 levels more on the Health maps.
  Builds are yours alone: an order is never for a cat, and parts an older save's cats wore are back in the stash.
- **Expeditions:** send a cat to an open destination at a threat up to your best, for 15 minutes, 1 hour, 4 hours, 8 hours. It fights on its own (also with the game closed) and brings home what a run would: meat, materials, ingredients, salvage (through your loot filter), set pieces and elite Chemicals. Longer trips bring more, but less a minute.
- The planner shows the threat the cat should hold there, the **odds** of a clean trip (3% to 97%) and the expected haul. A trip that goes wrong brings home 20% to 60% of the haul, and the cat rests for a while (25% of the trip, at least 10 minutes).
- **RECALL** brings a cat home early with a quarter of the haul.
- The **chef cat** is a separate hire, in Production > Kitchen > CHEF (see Meat, sauce and selling).

### The Overseer
- A big floating eye over the Production yard (or THE OVERSEER at the top of the folded list). Click it to wake it (no fee) and it **buys Production upgrades for you**: from its groups in the order you set on AUTOMATION > YARD (v0.9.38), the cheapest thing first within a group, at most one every 4 s, never touching the share of your Energy Sprinkles the hands keep back (AUTOMATION tab).
- You pick what it may buy (AUTOMATION > YARD): **stills** (building a still for a blueprint you own, still and tank levels, levels of attachments you've fitted, yard expansions; never a new attachment), **the shack**, **the yard**, **the garage** and **the cat counter** (v0.9.27: the kitchen dials folded into the kitchen). Its panel shows what it buys next (or saves up for), and what it has bought and spent.
- It works while the game runs, runs included (quietly; it's in the debug log), not while the game is closed. Switch it off or close its eye any time.

## Automation: the 8-Ball and the hands

Every automation setting is on the **AUTOMATION** tab. Hands are still hired where they live: the **Magic 8-Ball** on the AUTOMATION tab (or the Map's 8-Ball line), the **chef cat** in Production > Kitchen > CHEF, the **Overseer** by clicking its eye over the yard. **High fives** are yours, or the **High-Five Machine**'s at the cat counter (v0.9.7).

### The Magic 8-Ball
- Hire it (no fee) and switch it on with its switch or **B** anywhere. 8 s after you're back in the Smokehouse (with no menu open) it starts a run, with the Shoggoth driving (its truck setting applies; the Shoggoth's fee too). The result screen goes back by itself after 6 s and it goes again. B in a run switches it for the runs after this one.
- **The wait and the stops** (v0.9.38, RUNS). The wait before a run is 3, 8, 15 or 30 s. It also waits while you type (a custom order's name, a loadout's) or have a drop-down list open; **HOLD 8-BALL** (top of the screen) holds it until you resume, and while it counts down **FIGHT is GO NOW**. A run you start yourself (8-Ball off, held, or FIGHT with the Gauntlet armed) is **your run**: you drive unless SHOGGOTH REMOTE CONTROL is on, and the result screen waits for you. It can **stop itself**: STOP AFTER THE NEXT RUN, after 5, 10, 25 or 50 runs, or when the stash passes 300, 500, 1,000 or 2,000 parts (or, instead of stopping, scrap the weakest unlocked parts down to that limit: lowest tier, then quality, then temper; never a worn part, one on a cat, in a loadout, locked, a keystone or an exotic). When it stops, pauses a goal or finishes one there is a meow, and the message stays on the FIGHT button until you click it.
- **While you were away** (v0.9.38): the AUTOMATION tab shows what the hands did since you last clicked or pressed a key in the Smokehouse: runs and deaths, parts kept, scrapped and crafted, Energy Sprinkles in and out, what the Overseer bought, goals finished and what is waiting on you. GOT IT clears it. It isn't saved.
- It works **its list of goals**: with one goal it can work, that one; with two or more, **round in turn, a goal a run** (v0.9.24; top first before), so an order waiting on part luck doesn't hold the list, and an order farming parts never pauses on luck. A goal that can't move now (waiting on a fee, a full Shed, an offer) is skipped and says why. Each goal shows what it does next, a progress bar and its **budget**. Six kinds of goal to add (v0.9.24): a build, a reputation level, a map, a best threat, one of every exotic, Sprinkles; the rest (favor, a still, materials, Shards, one exotic, a blueprint, contracts) are steps the planner takes on the way.

### Two lists
- **The 8-Ball's list**: its runs work it. **Every cat has its own list** (v0.9.11): that cat's trips work it, with **CREW FARMS TOO** on (CREW), and (v0.9.29) every build order is yours. **<>** on a goal hands it to the next list (the 8-Ball's, then each cat's). A build, a best-threat goal or a still goal can't go on a cat's list: cats wear no parts, and trips don't raise your best threat or bring still blueprints.
- **Goals:** reputation with a faction (or **every open faction** to a level: the one furthest behind first), favor, opening a map (or every map), **a new fuel's still** (v0.9.6), Scrap, Bits or Chemicals, **exotic materials** (a stockpile of one: v0.9.6), **Blueprint Shards** (v0.9.6; gone in v0.9.26), an exotic part, an exotic blueprint, faction contracts (one faction or all, so many or keep going), a best threat (one place or anywhere), Energy Sprinkles, and builds (orders from the Showroom).
- **A best-threat goal's target** shows on the Map's START THREAT dial as **▲ GOAL n** while it's pushing there, and the Map's destination panel says where the 8-Ball's next run and each cat's next trip go (v0.9.18).
- **How a goal plans:** reputation and favor are fought for on the faction's turf, and a locked turf is opened first (back along the chain of factions, or by pushing your best threat, or by buying the truck engine). Materials: the open map that yields most of them (with the Shed full, the hands build it up first; past the biggest Shed, a full Shed is as done as it gets). Exotic materials: the material's home map (it drops there from threat 10, where your kit holds it, more a drop the deeper the run starts, and the map's boss drops a pile), opening the map first if it's shut. A new fuel's still: its blueprint (reach its threat at its map and get out: the run pushes there and starts the truck at it), then the still (opening two plots first if the yard is full; Sprinkles farmed first if they're short). Blueprint Shards: the hands break down **spare set pieces** (a copy of a piece you have as good or better that nobody wears, no order or loadout wants and isn't locked), then farm the deepest place the kit holds, where elites drop set pieces. An exotic part: the reputation and favor for its blueprint, the blueprint, its material at its home (as above), then the craft (farming Sprinkles first if they're short; Blueprint Shards come from breaking down set pieces and from tuxedo cats). Contracts: the cut where its mutant is common (with the chef saucing for that faction), the ingredient where it's found, then the delivery. Sprinkles: meat from the deepest place the kit holds. What the hands can do without a run (buy the truck engine or a blueprint, craft the exotic, deliver a contract) they do between runs.
- **Budgets** (BUDGET on each goal, going round): until it's done (the default), 5, 10, 25 runs (trips for the crew), 15, 30, 60, 120 minutes of runs, or for a build **until every part it wears is at your top tier**. A goal whose budget is spent leaves the list.
- **An order's still or exotic is a goal of its own** (v0.9.23): the build's still blueprint is fetched by a run pushed to its threat, its exotic's reputation, favor and material count as the order's progress (an order used to pause after two runs that brought no part while that was being earned), and the hands build the still and buy and craft the exotic. With nothing left to farm and CRAFT off, the order says how many parts the 8-Ball could craft or re-forge for it (a set piece rolls a random lane, so a build's set and its lanes often need a re-forge to agree).
- **Saving up** (v0.9.23): a step that needs Energy Sprinkles (a still plot, a still, a bigger Shed, an exotic's craft) sets a target that holds still (the cost plus what THE HANDS KEEP of it), and while it's the 8-Ball's step the Overseer, the chef and the 8-Ball's own crafting spend nothing below it. An exotic short of Blueprint Shards farms them (spare set pieces broken down first) instead of waiting.
- **Held materials** (v0.9.38): the Scrap, Bits and Chemicals such a step costs are held too: the Overseer leaves them. With the 8-Ball off (and no crew farming) nothing is held: the reserve used to stick at the last price until a restart. After a death the turn passes to the next goal (the count of deaths is kept). A reputation goal for every faction stays with the faction nearest the level until it's there, then the next (it went to the furthest behind: a new map at start threat 0 every run). The log keeps 200 lines, filters by hand, and folds the Overseer's purchases into a line a minute.
- **When things go badly:** 2 runs in a row that don't move a goal (an order farming parts excepted, v0.9.24) **pause** it for 20 minutes (or until your kit's power is up 10%), and the next goal takes over. 2 deaths in a row **lower its threat by 1** (where the run starts and where the Shoggoth starts the truck) until the kit's power is up the same way; when it can't go lower the goal pauses. 2 crew trips in a row that go wrong pause a crew goal. II pauses a goal by hand; GO brings a paused one back now.
- **When a list is empty** (or every goal waits), v0.9.18: one idle for both, **HELP** or **STOP**. HELP: the 8-Ball farms the crew's first unmet order (a build for a cat) and a cat works the 8-Ball's goal; with nothing to help, either fights where reputation is **lowest**. STOP (STAY HOME for the cats) does nothing. Reputation, favor and exotic blueprints are goals you add (an older save's EXOTIC BLUEPRINTS idle becomes the **one of every exotic** goal). With no goal, 2 deaths in a row lower the 8-Ball's threat too, and when it can't go lower it switches off.
- **One of every exotic** (v0.9.18): a goal that works through every exotic part you don't own one of, start to finish. It picks the **nearest to crafted** (fewest stages left: reputation, favor, blueprint, exotic material, other materials, Sprinkles), with exotics for the **fuels you and the crew have loaded** before the rest, and runs that one as an exotic goal (farm the reputation and favor, buy the blueprint, farm the material, craft it), then the next. It ends when one of each is in the stash, on you or on a cat.
- **THE HANDS** row (v0.9.18, top of AUTOMATION): every hand's hire and switch in one place: the 8-Ball (hire, on / off), the chef (hire), the Overseer (hire, on / off), the High-Five Machine (once built at the cat counter; its stops are set there) and HIRE A CAT (the next in the counter's line). The Map line, the Kitchen's CHEF panel, the eye and the counter still work as shortcuts.

### Runs
- **Where its runs start** (v0.9.11): as high as the map's START THREAT dial may go, your best there minus 3, whatever it farms. A best-threat goal starts the truck at its target, or at what the kit holds there if that's lower (AUTO stops 2 under what the kit holds); when the kit holds no more than your best, the goal waits for more power.
- **The Shoggoth's settings** (your runs and the 8-Ball's): see Shoggoth Remote Control.
- With a build to farm it buys that place's **targeted-loot pick** (60 shards) for the slot the build needs most, unless that's already today's featured slot there (PICKS). v0.9.38: the pick is for the build the run is for, and it buys none from a faction whose favor a goal on the list still has to pay (a build's exotic or set blueprints, an exotic goal's blueprint).
- **THE WEEKLY GAUNTLET** (off at first): its first run each week is this week's Gauntlet, once you can enter it. A Gauntlet death doesn't count against it.

### Builds
- **Orders.** Press **ORDER IT** on a Showroom ad and the 8-Ball farms for that build (it's hired for free if it wasn't). Each run it goes where the next missing piece drops, in this order: a missing fuel's still blueprint (where it drops), 5 set pieces (at the set's home), lane parts below your top tier and the keystone (at the build's home), then the exotic upgrade's faction favor (at that faction's turf) and material (where it drops). With everything in, it farms the build's home for better rolls; a place that isn't open yet is skipped. Building stills stays yours: the ad's plan marks it YOU.
- **Custom orders** (v0.8.8). **+ CUSTOM ORDER** on the Showroom tab starts a build of your own from the kit you wear; **CUSTOMIZE** on an ad starts one from that ad. Pick its set (or none), keystone (or none), a lane for every slot, up to 3 affixes, up to 4 fuels (the first is the signature) and one exotic for any gun slot (its home map is its set's, or where you fight when it has none; v0.9.15), then **ORDER IT**: the 8-Ball farms, crafts and puts it on like any ad. **DELETE** throws it away with its orders. **ORDER THIS BUILD** on a saved loadout (Loadout tab) starts one from that loadout's parts and fuels (v0.9.18). Every list shows what each choice does, and the long ones filter as you type (v0.9.7); **WHAT YOUR PICKS DO** sums up the keystone, the set bonuses, the exotic and the mutations.
- **What an order asks of a part** (v0.9.47). In the custom builder each of a build's affixes is **NICE TO HAVE** (it breaks ties, as before) or **A MUST**: a slot only counts as filled by a part that has every MUST. MUST ROLL asks for any roll, the top half or the top quarter of the affix's range; QUALITY asks for a floor of Tuned, Mutated or Malevolent; + PARTS asks for the half-step; TEMPER TO has the 8-Ball temper the build's parts up to a level; and any slot can have **its own MUSTs** in place of the build's. The plan gains a step, PARTS WITH THE ROLLS IT ASKS FOR, farmed at the build's home; the 8-Ball never crafts for a roll (a crafted part's affixes are luck), it farms. A part that has what its slot asks ranks above a better quality without it, below a higher tier. An ad from the Showroom asks for nothing until you CUSTOMIZE it.
- **The 8-Ball's instructions** (v0.9.48). Besides goals it plans by itself, the list takes three you direct: **FARM A MAP** (runs there until you take it off, or for a number of runs), **A PART HUNT** (runs your deepest map until a number of kept parts match a rule from one of your loot filters) and **A KEYSTONE** by name. Every instruction on the 8-Ball's list has its own **START** (PLAN, HIGH, COMFORT or a threat), **TRUCK** call (SAME as the Shoggoth's, AUTO, WHEN HURT or a threat), **KIT** (a saved loadout worn for its runs; what you wore goes back on after) and **LOOT** filter, a **weight** (turns in a row when the list goes IN TURN) and an **ONLY WHEN** condition (Sprinkles or the stash under or over an amount, kit power a quarter above today's, or the instruction above it finished). RUNS sets the order of work (IN TURN or TOP FIRST), more stops (after so many minutes, when any instruction finishes, when a keystone, an exotic or a marked part comes home), the numbers for runs that go wrong (runs before a pause, minutes paused, deaths before the threat drops and how far), shows **the next five runs**, and saves the whole list as a **program** you can load back or copy and paste as text. **MAKE IT THE STANDING INSTRUCTION** in the add form sets what the 8-Ball does when the list is empty or every instruction waits.
- **An order for one part** (v0.9.47). ORDER A BETTER ONE OF THESE on a stash part orders that one slot: its lane at your top tier, with the affixes it has as wants. It wants loot for that slot only, and it is met by one part.
- **STOPS WHEN MET or KEEPS IMPROVING** (v0.9.47, on the order's goal). A met order leaves the list, or stays and trades up. **LIMIT** is the order's budget in Sprinkles for the 8-Ball's crafting (none, 10,000, 50,000, 250,000 or 1,000,000); used up, the order only farms. The Workshop has a switch for each kind of work: craft set pieces, buy blueprints, craft lane parts, re-forge lanes, roll behaviors, craft the exotic, temper to the order's level.
- **CRAFT WHAT I CAN** (v0.9.7), on an ad and on an order card in AUTOMATION: one click crafts everything the build still lacks that you can make and afford now (set pieces and their blueprints, lane parts at your top tier, re-forges onto its lanes, the exotic upgrade, the mutations it seeks). It spends freely and locks what it makes.
- **Mix and match sets** (v0.9.2). A custom build picks how many pieces of its set to wear (2, 3 or 4: each turns on one more bonus) and can add a **second set** with its own count, say 4 Grease Fire + 2 Glacier Works, or 2 + 2. Both counts together fit in the slots the keystone leaves (when they don't, the second set's count gives way first). The 8-Ball farms, crafts, re-forges and puts on pieces of both, never taking a slot from one set for the other.
- **Behaviors to seek** (v0.9.2 as mutations; v0.9.24: one layer, one word). An order can seek up to 7 behaviors (v0.9.18: one a slot) (Backfire, Chilling, Fixated, Marked, Overkill, Pent-Up, Spreading, Toxic, Volatile). One part of the build with each is all a kit uses (they don't stack). Every part has one behavior slot: Mutated and Malevolent parts roll one 30% of the time, and Refine > **BEHAVIOR** rolls or changes one on any part for Chemicals. The order's plan adds a step for each, PUT IT ON swaps in a part of the build that carries one, an order isn't done until they're worn, and with **CRAFT FOR THE ORDER** on, the 8-Ball rolls a worn part of the build (not the keystone or the exotic) one roll at a time until it has the one sought. Every ad seeks the behavior that helped its build most in the lab.
- **Order loadouts** (v0.8.8). Every order keeps a saved loadout (v0.9.29: every order is yours), **ORDER: <NAME>** on the Loadout tab: the best kit you own for it right now (what the 8-Ball would put on), kept up to date as parts come in, are crafted or go. You can rename it. When the order is matched its loadout stays, as an ordinary one; cancel the order and its loadout goes too, unless you renamed it. Delete it while the order is on and that order keeps none. Like every saved loadout, its parts are never scrapped.
- **The order list**: every build you order is yours and goes on the 8-Ball's list (cats wear no parts since v0.9.29). X on the goal takes it off and removes its saved loadout, as CANCEL ORDER in the Showroom does.
- **Its loot and your kit** (v0.9.38). New salvage an order wants (its keystone, its exotic, its set's pieces and parts on its lanes, from one tier below your top) is **locked** on the way home, kept whatever your loot filter says, and kept in the order's saved loadout (Loadout tab). The 8-Ball puts parts on you for **one build only: the one marked WEAR** (on the build's goal, or WEAR IT in the Showroom); its best kit goes on before and after the 8-Ball's runs. With no build marked it **never touches your kit**. An order is **done when you own its whole kit**, worn or not: it leaves the list and its loadout stays for you to put on. (EQUIP BEST AFTER EACH RUN is gone: off, it still put new parts on.) **SCRAP WHAT NO ORDER WANTS** spares a part that beats what you wear in its slot on the lane you wear (a higher tier, or the same tier and a better quality).

### Workshop
- **Crafting for the order** (CRAFT FOR THE ORDERS, off at first): Before and after each 8-Ball run it crafts what **the build that run is for** still lacks (v0.9.38; the first build on the list before, and still on a run for another kind of goal): set pieces up to 4 (buying a piece's blueprint with shards first), a lane part at your top tier for every slot below it (lanes whose blueprint you know), and the exotic upgrade (its blueprint with favor, then the craft). What it makes is locked. It makes at most 6 things a go, and with EQUIP BEST AFTER EACH RUN on puts them on.
- **TEMPER WORN PARTS** (off at first): before each 8-Ball run it tempers the Malevolent T4 and T5 parts you wear, the least tempered first.
- **NO ORDER WANTS** (v0.9.46: a ready-made loot filter, not a switch; the Workshop's LOOT FILTER line puts every source on it or back on MY FILTER). While an order is on the list, loot no order wants is scrapped on the way home, except an upgrade on the lane you wear (the first copy of a keystone or an exotic is always kept). **SHOW THE n IN THE STASH** shows what it would take on the Loadout tab (NO ORDER WANTS), where SCRAP SHOWN takes them (v0.9.17; never parts that are worn, locked, on a cat, in a saved loadout, or exotics).
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
- salvage is T4 only, and Malevolent parts drop (each level adds 2 quality steps);
- every level adds a **mutator** (below), and each one raises salvage quality and elite Chemicals;
- keystones turn up more often (0.4% of crates); elites drop from 2 levels higher, so theirs turn Infested at threat 19.

| Mutator | What it does |
|---|---|
| Armored Season | Armor grows 6% faster per level. |
| Elite Pack | Three times as many elites. |
| Heat Wave | The gun cools 30% slower. |
| Static Front | Shields refill after 3 s without damage. |
| Swarm | Half again as many mutants, each with 30% less health. |

### The weekly Gauntlet
- Opens at best threat 20. Each week has one destination and 3 mutators, the same for everyone. Arm it with WEEKLY GAUNTLET on the Map and your next run is the Gauntlet: it starts at threat 20 with those mutators.
- The board keeps your best Gauntlet runs of the week (deepest threat, then longest time), by main fuel, with each run's build code to copy.

### Chemicals from elites, favor from sets
- **Elite Chemicals** (v0.9.26; Mutagen before): elites past threat 15 (12%) drop 10 Chemicals, scrapping a Mutated part gives 10 and a Malevolent 50, radiant cats bring 10. Behaviors and tempers cost Chemicals.
- **Set favor** (v0.9.26; Blueprint Shards before): breaking down a set piece pays favor with the set's faction (its home map's), tuxedo cats pay the parked faction. Set blueprints cost 30 favor with the set's faction; a destination's featured-slot pick 60 with its faction.

### Where to push
- Compare destinations by their growth: the Rust Flats piles on armor, the Glow Crater shields, the Sewer Delta health. Bring fuels and parts that answer the pool that grows fastest there.
- The Shoggoth's AUTO truck setting uses an estimate of what your kit holds at a destination: a good guide to how deep to go.

## A New Truck (the prestige)

v0.9.21. A **New Truck** sells the truck and starts the Smokehouse over, keeping what you've learned and paying **Harry Berries** for how deep this truck went. Berries buy lasting buffs in the **Needless Complexity Emporium**. Each New Truck is a **Spicy Level**.

### Selling the truck
- **Esc > NEW TRUCK**, offered from best threat 20 (and not during a run). The sheet lists exactly what goes and what stays, with counts, and the Berries it pays; you type SELL to confirm. There's no undo (the slot's backup is the save before).
- **The first truck comes early** (v0.9.29). Your first new truck is offered from best threat 15, with a smaller purse while you're below 20: 1 Berry per 2 levels past 5 at your best map (5 at 15, 7 at 19) and nothing from the other maps, so the first reset is a decision an hour or two in and the Emporium's first lines get tried. From best threat 20 the first truck pays the full price like any other.
- **It pays** 1 Berry a threat level past 10 at your best map, 1 per 2 levels past 10 at every other map, and this week's Gauntlet score's levels past 20. A 26 / 18 / 14 career pays 22. The same career pays the same every time: the Emporium's rising prices are the brake.
- **What stays:** your recipes, the lane blueprints you've learned, your still blueprints (the stills themselves are rebuilt), the first 5 saved loadouts **as custom orders** (their lanes, set, keystone, affixes, mutations and fuels; no parts cross: a new truck starts from an empty stash), your custom orders, the cats **bare** (their names and coats; their gear and fuel go), every setting (the loot filter, THE HANDS KEEP, the idle modes, the Shoggoth's truck setting, the every-run feast, the High-Five Machine's coats; the 8-Ball's settings come back when it's hired again), the journal, the milestones, the Gauntlet board and the tabs you had open.
- **What goes:** every part, Sprinkles, favor, reputation, best threat and map unlocks, set and exotic blueprints, the buildings and plots, the stills, the meat, the goal lists, and the 8-Ball, the chef and the Overseer (hired again, free).

### The Needless Complexity Emporium
- On the Esc menu, and on the Smokehouse's top bar once you've sold a truck. Two trees, each line with 10 levels, a cost that climbs x1.5 a level (the first level of most lines is 1 Berry) and a **hard cap** shared with every other source (above). Every line is a multiplier on top of your parts, sets, keystones and feasts; the flamethrower sheet shows the lines you own as a HARRY BERRIES line. The whole Emporium is 824 Berries.
- **The flamethrower**, at the top of each line: Flow (+15% flow); Stack damage (+15% stack damage); Burn duration (+20% burn duration); Heat (-15% heat per unit); Cooling (+20% cooling); Heat cap (+20% heat cap); Tank capacity (+30% tank capacity); Fuel regen (+20% fuel regen); Range (+15% range); Swap time (-20% swap time); Hit points (+10 HP).
- **The economy**, at the top of each line: Meat value (+20% meat value); Counter price (+10% counter price); Reputation (+30% reputation and favor); Material drops (+20% material drops); Set favor (+40% set favor); Pot speed (+20% pot speed); The chef's cut (-5% chef's cut); Crew hauls (+30% crew hauls); Contract favor (+100 favor a contract); A fuller wallet (start with ◆10,000).
- **One-offs**, applied when a new truck starts: The farm comes along (20 Berries); The 8-Ball comes along (10 Berries); The chef comes along (15 Berries); The Rust Flats are open (10 Berries); A head start in the yard (15 Berries); One more loadout kept (20 Berries, 3 times).
- **RESPEC**, free once a Spicy Level: every line back to 0 and the Berries back in hand (the one-offs stay).

### The Eldritch cat
- v0.9.21: it brings keystones you don't own yet; with every keystone in the stash it brings a double haul of exotic material instead.

## The Showroom (tested builds)

The Smokehouse's **SHOWROOM** tab sells flamethrowers. The ads are jokes; the builds are real: the balance lab's 36 finished builds, two for every set, all tested under the same balance (v0.9.41: rebuilt from scratch as five set pieces, a keystone and an exotic). It stocks 10 at a time, 2 of each style, with **new stock after every run**: it shows every ad of a style before it shows one again, so a new game and five runs show all of them; an ad on order stays listed until the order is done, and the guide below has them all. In the game each ad also checks its parts list against your stash, links to the set blueprints and the fuel's exotics, and has **ORDER NOW!**: the Magic 8-Ball's plan for the build, what you wear of it, **ORDER IT** (the 8-Ball then farms for it: where to fight and which targeted-loot pick to buy; with an order already in hand, **ADD TO THE LIST**), **FOR:** (you or a cat on the crew, v0.8.2), **PUT IT ON** (equips the best you have for it) and **LOOT FILTER FOR THIS BUILD** (keeps the build's lanes). **CUSTOMIZE** (v0.8.8) starts a custom order from the ad, and **+ CUSTOM ORDER** one from the kit you wear: your own build, ordered like an ad.

**Reading an ad** (v0.9.41: rebuilt from scratch). A finished build is **5 pieces of one set, one keystone and one exotic**: a lane for every slot (the set pieces sit on the build's lanes), a keystone (the Miser builds borrow one), the exotic in the slot the ad names, its fuels (the first is the signature) and three affixes worth hunting on every part. **Lab** is the threat a robot pig held at the build's home map, starting at threat 20, with every part Malevolent and near-perfect rolls (2 seeds), at T4 and at T5. **The exotic** line says what the build's exotic does and what the lab measured it adding, against the same build with a plain part in that slot.

| Build | Style | Set | Fuels | Home | Lab T4 | Lab T5 |
|---|---|---|---|---|---|---|
| Fry Station Fried Stiff | Brawler | Deep Fryer | Fryer Oil, Rendered Lard | The Flesh Farms | 28.1 | 31.3 |
| Fry Station Rendering | Brawler | Deep Fryer | Rendered Lard, Fryer Oil | The Flesh Farms | 28.0 | 31.3 |
| Grease Monkey Ferment | Brawler | Grease Fire | Swamp Napalm, Rocket Hooch | Smokehouse Outskirts | 27.5 | 29.4 |
| Grease Monkey Heat Sink | Brawler | Grease Fire | Thermite Slurry, Rocket Hooch | Smokehouse Outskirts | 26.2 | 28.1 |
| Oven Mitts Greased Feed | Brawler | Oven Mitts | Rendered Lard, Thermite Slurry | Rust Flats | 28.0 | 30.3 |
| Oven Mitts Radiation Sickness | Brawler | Oven Mitts | Rad Syrup, Thermite Slurry | Rust Flats | 27.5 | 30.5 |
| Whole Hog Ferment | Brawler | Whole Hog | Swamp Napalm, Rendered Lard | The Flesh Farms | 28.2 | 32.8 |
| Whole Hog Cracked Open | Brawler | Whole Hog | Thermite Slurry, Rendered Lard | The Flesh Farms | 28.6 | 32.1 |
| Meltdown Kick | Lancer | Meltdown | Rocket Hooch, Ion Gel | Reactor Row | 25.3 | 28.9 |
| Meltdown Overload | Lancer | Meltdown | Ion Gel, Rocket Hooch | Reactor Row | 26.7 | 30.9 |
| Nutcracker Static Field | Lancer | Nutcracker | Ion Gel, Thermite Slurry | Tank Graveyard | 25.8 | 28.5 |
| Nutcracker Lance | Lancer | Nutcracker | Thermite Slurry, Rocket Hooch | Tank Graveyard | 27.4 | 29.0 |
| Coilworks Fireball | Lancer | Tesla Coilworks | Rocket Hooch, Ion Gel | Glow Crater | 25.3 | 28.7 |
| Coilworks EMP | Lancer | Tesla Coilworks | Ion Gel, Rocket Hooch | Glow Crater | 28.6 | 31.7 |
| Boiler Room Fireball | Furnace | Boiler Room | Rocket Hooch, Thermite Slurry | Smelter Pits | 25.0 | 27.2 |
| Boiler Room Rendering | Furnace | Boiler Room | Rendered Lard, Thermite Slurry | Smelter Pits | 25.3 | 27.8 |
| Hellmouth Fireball | Furnace | Hellmouth | Rocket Hooch, Thermite Slurry | The Junk Bazaar | 29.4 | 35.6 |
| Hellmouth Tar Pit | Furnace | Hellmouth | Swamp Napalm, Rocket Hooch | The Junk Bazaar | 26.4 | 26.5 |
| Hot Plate Seeps Through | Furnace | Hot Plate | Swamp Napalm, Thermite Slurry | Smelter Pits | 30.5 | 34.4 |
| Hot Plate Cracked Open | Furnace | Hot Plate | Thermite Slurry, Rocket Hooch | Smelter Pits | 26.0 | 28.2 |
| Walk-In Freezer Static Field | Miser | Walk-In Freezer | Ion Gel, Rocket Hooch | Static Fields | 29.3 | 37.0 |
| Walk-In Freezer Tar Pit | Miser | Walk-In Freezer | Swamp Napalm, Ion Gel | Static Fields | 29.6 | 36.2 |
| Glacier Works Ferment | Miser | Glacier Works | Swamp Napalm, Rendered Lard | Sewer Delta | 26.6 | 29.2 |
| Glacier Works Cracked Open | Miser | Glacier Works | Thermite Slurry, Rendered Lard | Sewer Delta | 26.5 | 30.2 |
| Slow Cooker Slick | Miser | Slow Cooker | Rendered Lard, Fryer Oil | Fungal Bog | 26.8 | 30.4 |
| Slow Cooker Heat Sink | Miser | Slow Cooker | Thermite Slurry, Rendered Lard | Fungal Bog | 26.8 | 31.1 |
| Bandolier Tar Pit | Juggler | Bandolier | Swamp Napalm, Thermite Slurry, Ion Gel | Scrap Mountain | 23.3 | 27.2 |
| Bandolier Cracked Open | Juggler | Bandolier | Thermite Slurry, Rocket Hooch, Ion Gel | Scrap Mountain | 23.0 | 26.0 |
| Last Call Fried Stiff | Juggler | Last Call | Fryer Oil, Rocket Hooch, Thermite Slurry | Dead Drive-In | 25.0 | 28.7 |
| Last Call Critical Mass | Juggler | Last Call | Rad Syrup, Rocket Hooch, Thermite Slurry | Dead Drive-In | 23.8 | 26.1 |
| Moonshine Run Slick | Juggler | Moonshine Run | Rendered Lard, Rocket Hooch, Thermite Slurry | Dead Drive-In | 26.2 | 29.0 |
| Moonshine Run Radiation Sickness | Juggler | Moonshine Run | Rad Syrup, Rocket Hooch, Thermite Slurry | Dead Drive-In | 24.8 | 28.1 |
| Potluck Fried Stiff | Juggler | Potluck | Fryer Oil, Rendered Lard, Thermite Slurry | Bloat Marsh | 28.1 | 33.7 |
| Potluck Redline | Juggler | Potluck | Rocket Hooch, Rendered Lard, Thermite Slurry | Bloat Marsh | 25.8 | 29.1 |
| Test Kitchen Fried Stiff | Juggler | Test Kitchen | Fryer Oil, Rocket Hooch, Thermite Slurry | The Food Court | 28.4 | 33.1 |
| Test Kitchen Dirty Bomb | Juggler | Test Kitchen | Rad Syrup, Rocket Hooch, Thermite Slurry | The Food Court | 27.1 | 30.5 |

### Fry Station Fried Stiff
**Brawler** (up close and in the crowd, Deep Fryer). "Golden brown and going nowhere." Get close, get them battered, and sell what's left by the crate. This one runs Fryer Oil and is built around the Batter Mitt.

- Deep Fryer set, five pieces: Kills drop +25% raw meat; +40% stack damage; +150% stack damage within 220 px; BATTERED: mutants within 220 px take +8% per stack on them (up to +300%). Five pieces: the FLARE-UP, a chance for a close volley to hit harder and cost no fuel.
- Feeding Frenzy keystone (nozzle): A kill streak: every kill adds +10% to all your stacks (an elite counts five), up to +250%. A wide nozzle: cone +80%. After 2 s without a kill the streak drains, four kills' worth a second.
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

**Set:** 5 Deep Fryer pieces. **Fuels:** Fryer Oil, Rendered Lard. **Affixes:** Potent, Recycling, Sticky. **Home:** The Flesh Farms. **Lab:** threat 28.1 at T4, 31.3 at T5.

**The exotic:** Batter Mitt (the exotic Fryer Oil shroud & grip I, in the shroud & grip slot). FRIED STIFF: A mutant Fryer Oil touched in the last 3 s is slowed 60%. Lab: +5.4 threat.

### Fry Station Rendering
**Brawler** (up close and in the crowd, Deep Fryer). "Nothing goes to waste, least of all them." Get close, get them battered, and sell what's left by the crate. This one runs Rendered Lard and is built around the Schmaltz Aorta.

- Deep Fryer set, five pieces: Kills drop +25% raw meat; +40% stack damage; +150% stack damage within 220 px; BATTERED: mutants within 220 px take +8% per stack on them (up to +300%). Five pieces: the FLARE-UP, a chance for a close volley to hit harder and cost no fuel.
- Flashpoint keystone (igniter): A stack's whole burn lands the instant it is applied, at 1.4 times its total, and at 2.8 times that on anything close (the six nearest mutants, or within 220 px). Nothing lingers: Spreading, Toxic and Hellmouth do nothing (burn duration still counts: a longer burn lands more).
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

**Set:** 5 Deep Fryer pieces. **Fuels:** Rendered Lard, Fryer Oil. **Affixes:** Potent, Recycling, Sticky. **Home:** The Flesh Farms. **Lab:** threat 28.0 at T4, 31.3 at T5.

**The exotic:** Schmaltz Aorta (the exotic Rendered Lard fuel line III, in the fuel line slot). RENDERING: Lard bites armor at x2 and shields at x1. A mutant that dies with Lard on it puts fuel back in the tank, more from a big one. Lab: +4.6 threat.

### Grease Monkey Ferment
**Brawler** (up close and in the crowd, Grease Fire). "Aged in the tank. Bites through plating." It starts as a spill and ends as a block party. Every kill is the next one's fuse. This one runs Swamp Napalm and is built around the Swamp-King Altar.

- Grease Fire set, five pieces: Stacks +60% damage; Burning kills splash 2 stacks nearby; GREASE FIRE: burning kills explode for 6 stacks in a wide blast; +60% stack damage. Five pieces: the FLARE-UP, a chance for a close volley to hit harder and cost no fuel.
- Flashpoint keystone (igniter): A stack's whole burn lands the instant it is applied, at 1.4 times its total, and at 2.8 times that on anything close (the six nearest mutants, or within 220 px). Nothing lingers: Spreading, Toxic and Hellmouth do nothing (burn duration still counts: a longer burn lands more).
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

**Set:** 5 Grease Fire pieces. **Fuels:** Swamp Napalm, Rocket Hooch. **Affixes:** Potent, Recycling, Sticky. **Home:** Smokehouse Outskirts. **Lab:** threat 27.5 at T4, 29.4 at T5.

**The exotic:** Swamp-King Altar (the exotic Swamp Napalm tank chassis III, in the tank chassis slot). FERMENT: Napalm ferments in the tank into acid: it bites shields and armor at x1.3. Lab: +2.6 threat.

### Grease Monkey Heat Sink
**Brawler** (up close and in the crowd, Grease Fire). "Burns its own fever." It starts as a spill and ends as a block party. Every kill is the next one's fuse. This one runs Thermite Slurry and is built around the Forge-Heart Altar.

- Grease Fire set, five pieces: Stacks +60% damage; Burning kills splash 2 stacks nearby; GREASE FIRE: burning kills explode for 6 stacks in a wide blast; +60% stack damage. Five pieces: the FLARE-UP, a chance for a close volley to hit harder and cost no fuel.
- Flashpoint keystone (igniter): A stack's whole burn lands the instant it is applied, at 1.4 times its total, and at 2.8 times that on anything close (the six nearest mutants, or within 220 px). Nothing lingers: Spreading, Toxic and Hellmouth do nothing (burn duration still counts: a longer burn lands more).
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

**Set:** 5 Grease Fire pieces. **Fuels:** Thermite Slurry, Rocket Hooch. **Affixes:** Potent, Recycling, Sticky. **Home:** Smokehouse Outskirts. **Lab:** threat 26.2 at T4, 28.1 at T5.

**The exotic:** Forge-Heart Altar (the exotic Thermite Slurry tank chassis III, in the tank chassis slot). HEAT SINK: Above half heat Thermite burns the gun's heat instead of fuel, and hits +50%. Lab: +1.2 threat.

### Oven Mitts Greased Feed
**Brawler** (up close and in the crowd, Oven Mitts). "It coughs. Stand clear." Lets you handle the hot ones. Recommended for close company. This one runs Rendered Lard and is built around the Schmaltz Altar.

- Oven Mitts set, five pieces: The pig heals 1 HP each time the threat level rises; COOKED: a mutant carrying 30 or more stacks does no damage when it reaches you; SECOND WIND: once a run, a hit that would kill you leaves you at 3 HP with full armor and lights everything near the truck.
- Feeding Frenzy keystone (nozzle): A kill streak: every kill adds +10% to all your stacks (an elite counts five), up to +250%. A wide nozzle: cone +80%. After 2 s without a kill the streak drains, four kills' worth a second.
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

**Set:** 5 Oven Mitts pieces. **Fuels:** Rendered Lard, Thermite Slurry. **Affixes:** Potent, Recycling, Sticky. **Home:** Rust Flats. **Lab:** threat 28.0 at T4, 30.3 at T5.

**The exotic:** Schmaltz Altar (the exotic Rendered Lard tank chassis III, in the tank chassis slot). GREASED FEED: Every 4 s the feed coughs grease over the cone: 12 Lard stacks, a 0.25 s stun and a 60% slow for 3 s. Lab: +1.0 threat.

### Oven Mitts Radiation Sickness
**Brawler** (up close and in the crowd, Oven Mitts). "They slow down. You don't." Lets you handle the hot ones. Recommended for close company. This one runs Rad Syrup and is built around the Half-Life Altar.

- Oven Mitts set, five pieces: The pig heals 1 HP each time the threat level rises; COOKED: a mutant carrying 30 or more stacks does no damage when it reaches you; SECOND WIND: once a run, a hit that would kill you leaves you at 3 HP with full armor and lights everything near the truck.
- Feeding Frenzy keystone (nozzle): A kill streak: every kill adds +10% to all your stacks (an elite counts five), up to +250%. A wide nozzle: cone +80%. After 2 s without a kill the streak drains, four kills' worth a second.
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

**Set:** 5 Oven Mitts pieces. **Fuels:** Rad Syrup, Thermite Slurry. **Affixes:** Potent, Recycling, Sticky. **Home:** Rust Flats. **Lab:** threat 27.5 at T4, 30.5 at T5.

**The exotic:** Half-Life Altar (the exotic Rad Syrup tank chassis III, in the tank chassis slot). RADIATION SICKNESS: From its first dose a mutant sickens every 2 s: 12% slower and +48% from everything each time, down to half speed and +200%. Lab: +1.1 threat.

### Whole Hog Ferment
**Brawler** (up close and in the crowd, Whole Hog). "Aged in the tank. Bites through plating." Uses every part of the mutant, and then the next mutant. This one runs Swamp Napalm and is built around the Swamp-King Altar.

- Whole Hog set, five pieces: Every kill drops its materials; Elites and bosses drop their hoard twice (not the meat); NOSE TO TAIL: a run that gets out brings one more crate for every boss killed, at a better quality.
- Flashpoint keystone (igniter): A stack's whole burn lands the instant it is applied, at 1.4 times its total, and at 2.8 times that on anything close (the six nearest mutants, or within 220 px). Nothing lingers: Spreading, Toxic and Hellmouth do nothing (burn duration still counts: a longer burn lands more).
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

**Set:** 5 Whole Hog pieces. **Fuels:** Swamp Napalm, Rendered Lard. **Affixes:** Potent, Recycling, Sticky. **Home:** The Flesh Farms. **Lab:** threat 28.2 at T4, 32.8 at T5.

**The exotic:** Swamp-King Altar (the exotic Swamp Napalm tank chassis III, in the tank chassis slot). FERMENT: Napalm ferments in the tank into acid: it bites shields and armor at x1.3. Lab: +4.0 threat.

### Whole Hog Cracked Open
**Brawler** (up close and in the crowd, Whole Hog). "Opens with a bang." Uses every part of the mutant, and then the next mutant. This one runs Thermite Slurry and is built around the Crucible Sieve.

- Whole Hog set, five pieces: Every kill drops its materials; Elites and bosses drop their hoard twice (not the meat); NOSE TO TAIL: a run that gets out brings one more crate for every boss killed, at a better quality.
- Flashpoint keystone (igniter): A stack's whole burn lands the instant it is applied, at 1.4 times its total, and at 2.8 times that on anything close (the six nearest mutants, or within 220 px). Nothing lingers: Spreading, Toxic and Hellmouth do nothing (burn duration still counts: a longer burn lands more).
- Crucible Sieve, the exotic (filter): CRACKED OPEN. Armor Thermite breaks stuns everything within 160 px for 2 s, and that mutant takes +200% from everything for 6 s.
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

**Set:** 5 Whole Hog pieces. **Fuels:** Thermite Slurry, Rendered Lard. **Affixes:** Potent, Recycling, Sticky. **Home:** The Flesh Farms. **Lab:** threat 28.6 at T4, 32.1 at T5.

**The exotic:** Crucible Sieve (the exotic Thermite Slurry filter II, in the filter slot). CRACKED OPEN: Armor Thermite breaks stuns everything within 160 px for 2 s, and that mutant takes +200% from everything for 6 s. Lab: +5.1 threat.

### Meltdown Kick
**Lancer** (long reach, one target at a time, Meltdown). "Mind the recoil. They won't." Long barrel, short temper. Two fuels meet on one mutant and the argument is loud. This one runs Rocket Hooch and is built around the Rocket Altar.

- Meltdown set, five pieces: Aging fuels (Rad Syrup) age 25% faster, +20% vs elites and bosses, and +20% stack damage beyond 300 px; Elites and bosses take +25% more from every fuel; CRITICAL MASS: a mutant carrying 30+ stacks of one fuel takes +50% from every burn. Five pieces: LONG SHOT.
- Flashpoint keystone (igniter): A stack's whole burn lands the instant it is applied, at 1.4 times its total, and at 2.8 times that on anything close (the six nearest mutants, or within 220 px). Nothing lingers: Spreading, Toxic and Hellmouth do nothing (burn duration still counts: a longer burn lands more).
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

**Set:** 5 Meltdown pieces. **Fuels:** Rocket Hooch, Ion Gel. **Affixes:** Potent, Recycling, Sticky. **Home:** Reactor Row. **Lab:** threat 25.3 at T4, 28.9 at T5.

**The exotic:** Rocket Altar (the exotic Rocket Hooch tank chassis III, in the tank chassis slot). KICK: Every 50 units of Hooch the tank kicks: everything in the cone takes 36 extra stacks and a 0.4 s stun. Lab: +1.7 threat.

### Meltdown Overload
**Lancer** (long reach, one target at a time, Meltdown). "One shield goes and nobody moves." Long barrel, short temper. Two fuels meet on one mutant and the argument is loud. This one runs Ion Gel and is built around the Capacitor Sieve.

- Meltdown set, five pieces: Aging fuels (Rad Syrup) age 25% faster, +20% vs elites and bosses, and +20% stack damage beyond 300 px; Elites and bosses take +25% more from every fuel; CRITICAL MASS: a mutant carrying 30+ stacks of one fuel takes +50% from every burn. Five pieces: LONG SHOT.
- Can Opener keystone (fuel line): Shields, armor and health all take your fuel's best multiplier, and 30% more: whatever the fuel is good against, it is good against everything. It takes the fuel line's slot: no line lane's benefit.
- Capacitor Sieve, the exotic (filter): OVERLOAD. A shield Ion Gel pops stuns everything within 110 px for 1 s, and that mutant takes +100% from everything for 4 s.
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

**Set:** 5 Meltdown pieces. **Fuels:** Ion Gel, Rocket Hooch. **Affixes:** Potent, Recycling, Sticky. **Home:** Reactor Row. **Lab:** threat 26.7 at T4, 30.9 at T5.

**The exotic:** Capacitor Sieve (the exotic Ion Gel filter II, in the filter slot). OVERLOAD: A shield Ion Gel pops stuns everything within 110 px for 1 s, and that mutant takes +100% from everything for 4 s. Lab: +2.6 threat.

### Nutcracker Static Field
**Lancer** (long reach, one target at a time, Nutcracker). "Keep your distance. It insists." For the customer whose problems wear plating. This one runs Ion Gel and is built around the Static Mitt.

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

**Set:** 5 Nutcracker pieces. **Fuels:** Ion Gel, Thermite Slurry. **Affixes:** Potent, Recycling, Sticky. **Home:** Tank Graveyard. **Lab:** threat 25.8 at T4, 28.5 at T5.

**The exotic:** Static Mitt (the exotic Ion Gel shroud & grip I, in the shroud & grip slot). STATIC FIELD: Every 2.5 s, 35 Ion stacks and a 1.5 s stun on everything within 300 px of the pig. Lab: +1.2 threat.

### Nutcracker Lance
**Lancer** (long reach, one target at a time, Nutcracker). "Thin, long and straight through." For the customer whose problems wear plating. This one runs Thermite Slurry and is built around the Forge-Heart Throat.

- Nutcracker set, five pieces: A broken shield drops Chemicals and broken armor drops Scrap; +40% vs shields and armor; A shell that breaks bursts: 60% of it comes off the same shell of mutants within 120 px; CRACK: the burst is 120%, and a shell a burst breaks bursts too.
- Flashpoint keystone (igniter): A stack's whole burn lands the instant it is applied, at 1.4 times its total, and at 2.8 times that on anything close (the six nearest mutants, or within 220 px). Nothing lingers: Spreading, Toxic and Hellmouth do nothing (burn duration still counts: a longer burn lands more).
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

**Set:** 5 Nutcracker pieces. **Fuels:** Thermite Slurry, Rocket Hooch. **Affixes:** Potent, Recycling, Sticky. **Home:** Tank Graveyard. **Lab:** threat 27.4 at T4, 29.0 at T5.

**The exotic:** Forge-Heart Throat (the exotic Thermite Slurry nozzle III, in the nozzle slot). LANCE: The cone narrows to 67% of its width and reaches 40% further; everything in the line takes +60%, and its armor x3.5. Lab: +0.9 threat.

### Coilworks Fireball
**Lancer** (long reach, one target at a time, Tesla Coilworks). "Goes up. Takes the neighbours." Stand well back. It prefers to work from across the yard. This one runs Rocket Hooch and is built around the Rocket Throat.

- Tesla Coilworks set, five pieces: +30% vs shields; Breaking a shield stuns for 1 s; ARC: every hit chains to 6 nearby mutants, and chained stacks deal +100%. Five pieces: LONG SHOT.
- Flashpoint keystone (igniter): A stack's whole burn lands the instant it is applied, at 1.4 times its total, and at 2.8 times that on anything close (the six nearest mutants, or within 220 px). Nothing lingers: Spreading, Toxic and Hellmouth do nothing (burn duration still counts: a longer burn lands more).
- Rocket Throat, the exotic (nozzle): FIREBALL. A mutant that dies with Hooch on it goes up: x0.75 of what its Hooch had left lands on everything within 90 px.
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

**Set:** 5 Tesla Coilworks pieces. **Fuels:** Rocket Hooch, Ion Gel. **Affixes:** Potent, Recycling, Sticky. **Home:** Glow Crater. **Lab:** threat 25.3 at T4, 28.7 at T5.

**The exotic:** Rocket Throat (the exotic Rocket Hooch nozzle III, in the nozzle slot). FIREBALL: A mutant that dies with Hooch on it goes up: x0.75 of what its Hooch had left lands on everything within 90 px. Lab: +0.7 threat.

### Coilworks EMP
**Lancer** (long reach, one target at a time, Tesla Coilworks). "Pop one bubble, pop the room." Stand well back. It prefers to work from across the yard. This one runs Ion Gel and is built around the Storm Crown.

- Tesla Coilworks set, five pieces: +30% vs shields; Breaking a shield stuns for 1 s; ARC: every hit chains to 6 nearby mutants, and chained stacks deal +100%. Five pieces: LONG SHOT.
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

**Set:** 5 Tesla Coilworks pieces. **Fuels:** Ion Gel, Rocket Hooch. **Affixes:** Potent, Recycling, Sticky. **Home:** Glow Crater. **Lab:** threat 28.6 at T4, 31.7 at T5.

**The exotic:** Storm Crown (the exotic Ion Gel igniter III, in the igniter slot; the fuel becomes EMP Gel). EMP: A shield Ion Gel pops deals 40% of what it held to everything within 150 px, shields first. Lab: +3.1 threat.

### Boiler Room Fireball
**Furnace** (runs hot and holds the trigger, Boiler Room). "Goes up. Takes the neighbours." Runs at a temperature the warranty calls 'ambitious' and likes it there. This one runs Rocket Hooch and is built around the Rocket Throat.

- Boiler Room set, five pieces: Heat cap +25%, +35% stack damage; Stacks +1.2% for every 1% of heat (up to +120% at full heat); PRESSURE COOKER: reaching 100% heat starts 3 s without a lockout and +50% flow, then the gun locks out and vents to 0 (once per 45 s); +60% stack damage. Five pieces: BLOWOFF.
- Fever Grip keystone (shroud): +25% stack damage per 5% heat, and heat cap +40%. A lockout at 100% heat lasts twice as long.
- Rocket Throat, the exotic (nozzle): FIREBALL. A mutant that dies with Hooch on it goes up: x0.75 of what its Hooch had left lands on everything within 90 px.
- Rocket Hooch burns hot, short and against everything. With it, Thermite Slurry. Home: the Smelter Pits.
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

**Set:** 5 Boiler Room pieces. **Fuels:** Rocket Hooch, Thermite Slurry. **Affixes:** Potent, Recycling, Sticky. **Home:** Smelter Pits. **Lab:** threat 25.0 at T4, 27.2 at T5.

**The exotic:** Rocket Throat (the exotic Rocket Hooch nozzle III, in the nozzle slot). FIREBALL: A mutant that dies with Hooch on it goes up: x0.75 of what its Hooch had left lands on everything within 90 px. Lab: +1.3 threat.

### Boiler Room Rendering
**Furnace** (runs hot and holds the trigger, Boiler Room). "Nothing goes to waste, least of all them." Runs at a temperature the warranty calls 'ambitious' and likes it there. This one runs Rendered Lard and is built around the Schmaltz Aorta.

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

**Set:** 5 Boiler Room pieces. **Fuels:** Rendered Lard, Thermite Slurry. **Affixes:** Potent, Recycling, Sticky. **Home:** Smelter Pits. **Lab:** threat 25.3 at T4, 27.8 at T5.

**The exotic:** Schmaltz Aorta (the exotic Rendered Lard fuel line III, in the fuel line slot). RENDERING: Lard bites armor at x2 and shields at x1. A mutant that dies with Lard on it puts fuel back in the tank, more from a big one. Lab: +6.0 threat.

### Hellmouth Fireball
**Furnace** (runs hot and holds the trigger, Hellmouth). "Goes up. Takes the neighbours." Found, not made. It wants the trigger held and it does not explain itself. This one runs Rocket Hooch and is built around the Rocket Throat.

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

**Set:** 5 Hellmouth pieces. **Fuels:** Rocket Hooch, Thermite Slurry. **Affixes:** Potent, Recycling, Sticky. **Home:** The Junk Bazaar. **Lab:** threat 29.4 at T4, 35.6 at T5.

**The exotic:** Rocket Throat (the exotic Rocket Hooch nozzle III, in the nozzle slot). FIREBALL: A mutant that dies with Hooch on it goes up: x0.75 of what its Hooch had left lands on everything within 90 px. Lab: +5.5 threat.

### Hellmouth Tar Pit
**Furnace** (runs hot and holds the trigger, Hellmouth). "They check in. They don't check out." Found, not made. It wants the trigger held and it does not explain itself. This one runs Swamp Napalm and is built around the Bog Mitt.

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

**Set:** 5 Hellmouth pieces. **Fuels:** Swamp Napalm, Rocket Hooch. **Affixes:** Potent, Recycling, Sticky. **Home:** The Junk Bazaar. **Lab:** threat 26.4 at T4, 26.5 at T5.

**The exotic:** Bog Mitt (the exotic Swamp Napalm shroud & grip I, in the shroud & grip slot). TAR PIT: Napalm slows 6% a stack, up to 55%. A mutant at the cap is stuck: every other hit it throws at the pig does nothing. Lab: +3.5 threat.

### Hot Plate Seeps Through
**Furnace** (runs hot and holds the trigger, Hot Plate). "Shells are a suggestion." A little heat under everything, all the time. This one runs Swamp Napalm and is built around the Jelly Sieve.

- Hot Plate set, five pieces: The far end of your flame leaves a burning patch (4 s): 32 stacks a second on mutants in it; The patch burns 64 stacks a second and slows mutants on it 30%; FIREBREAK: 96 stacks a second, and patches that touch last as long as any one is fed.
- Fever Grip keystone (shroud): +25% stack damage per 5% heat, and heat cap +40%. A lockout at 100% heat lasts twice as long.
- Jelly Sieve, the exotic (filter): SEEPS THROUGH. Under a shield or armor, Napalm burns the health beneath at x1.5. On bare health it hits +80%.
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

**Set:** 5 Hot Plate pieces. **Fuels:** Swamp Napalm, Thermite Slurry. **Affixes:** Potent, Recycling, Sticky. **Home:** Smelter Pits. **Lab:** threat 30.5 at T4, 34.4 at T5.

**The exotic:** Jelly Sieve (the exotic Swamp Napalm filter II, in the filter slot). SEEPS THROUGH: Under a shield or armor, Napalm burns the health beneath at x1.5. On bare health it hits +80%. Lab: +10.8 threat.

### Hot Plate Cracked Open
**Furnace** (runs hot and holds the trigger, Hot Plate). "Opens with a bang." A little heat under everything, all the time. This one runs Thermite Slurry and is built around the Crucible Sieve.

- Hot Plate set, five pieces: The far end of your flame leaves a burning patch (4 s): 32 stacks a second on mutants in it; The patch burns 64 stacks a second and slows mutants on it 30%; FIREBREAK: 96 stacks a second, and patches that touch last as long as any one is fed.
- Fever Grip keystone (shroud): +25% stack damage per 5% heat, and heat cap +40%. A lockout at 100% heat lasts twice as long.
- Crucible Sieve, the exotic (filter): CRACKED OPEN. Armor Thermite breaks stuns everything within 160 px for 2 s, and that mutant takes +200% from everything for 6 s.
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

**Set:** 5 Hot Plate pieces. **Fuels:** Thermite Slurry, Rocket Hooch. **Affixes:** Potent, Recycling, Sticky. **Home:** Smelter Pits. **Lab:** threat 26.0 at T4, 28.2 at T5.

**The exotic:** Crucible Sieve (the exotic Thermite Slurry filter II, in the filter slot). CRACKED OPEN: Armor Thermite breaks stuns everything within 160 px for 2 s, and that mutant takes +200% from everything for 6 s. Lab: +1.9 threat.

### Walk-In Freezer Static Field
**Miser** (cheap fuel, long burns, cool head, Walk-In Freezer). "Keep your distance. It insists." Everything in the yard, kept at a brisk standstill. This one runs Ion Gel and is built around the Static Mitt.

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

**Set:** 5 Walk-In Freezer pieces. **Fuels:** Ion Gel, Rocket Hooch. **Affixes:** Potent, Recycling, Sticky. **Home:** Static Fields. **Lab:** threat 29.3 at T4, 37.0 at T5.

**The exotic:** Static Mitt (the exotic Ion Gel shroud & grip I, in the shroud & grip slot). STATIC FIELD: Every 2.5 s, 35 Ion stacks and a 1.5 s stun on everything within 300 px of the pig. Lab: +5.9 threat.

### Walk-In Freezer Tar Pit
**Miser** (cheap fuel, long burns, cool head, Walk-In Freezer). "They check in. They don't check out." Everything in the yard, kept at a brisk standstill. This one runs Swamp Napalm and is built around the Bog Mitt.

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

**Set:** 5 Walk-In Freezer pieces. **Fuels:** Swamp Napalm, Ion Gel. **Affixes:** Potent, Recycling, Sticky. **Home:** Static Fields. **Lab:** threat 29.6 at T4, 36.2 at T5.

**The exotic:** Bog Mitt (the exotic Swamp Napalm shroud & grip I, in the shroud & grip slot). TAR PIT: Napalm slows 6% a stack, up to 55%. A mutant at the cap is stuck: every other hit it throws at the pig does nothing. Lab: +4.8 threat.

### Glacier Works Ferment
**Miser** (cheap fuel, long burns, cool head, Glacier Works). "Aged in the tank. Bites through plating." A cool head, a full tank and all the time in the world. This one runs Swamp Napalm and is built around the Swamp-King Altar.

- Glacier Works set, five pieces: The gun cools 50% faster; Burning mutants slow 30%; COLD START: Pent-Up without the behavior (+60% a second idle, up to +200%), twice as fast with it; +40% stack damage. Five pieces: SECOND HELPING.
- Flashpoint keystone (igniter): A stack's whole burn lands the instant it is applied, at 1.4 times its total, and at 2.8 times that on anything close (the six nearest mutants, or within 220 px). Nothing lingers: Spreading, Toxic and Hellmouth do nothing (burn duration still counts: a longer burn lands more).
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

**Set:** 5 Glacier Works pieces. **Fuels:** Swamp Napalm, Rendered Lard. **Affixes:** Potent, Recycling, Sticky. **Home:** Sewer Delta. **Lab:** threat 26.6 at T4, 29.2 at T5.

**The exotic:** Swamp-King Altar (the exotic Swamp Napalm tank chassis III, in the tank chassis slot). FERMENT: Napalm ferments in the tank into acid: it bites shields and armor at x1.3. Lab: +1.8 threat.

### Glacier Works Cracked Open
**Miser** (cheap fuel, long burns, cool head, Glacier Works). "Opens with a bang." A cool head, a full tank and all the time in the world. This one runs Thermite Slurry and is built around the Crucible Sieve.

- Glacier Works set, five pieces: The gun cools 50% faster; Burning mutants slow 30%; COLD START: Pent-Up without the behavior (+60% a second idle, up to +200%), twice as fast with it; +40% stack damage. Five pieces: SECOND HELPING.
- Flashpoint keystone (igniter): A stack's whole burn lands the instant it is applied, at 1.4 times its total, and at 2.8 times that on anything close (the six nearest mutants, or within 220 px). Nothing lingers: Spreading, Toxic and Hellmouth do nothing (burn duration still counts: a longer burn lands more).
- Crucible Sieve, the exotic (filter): CRACKED OPEN. Armor Thermite breaks stuns everything within 160 px for 2 s, and that mutant takes +200% from everything for 6 s.
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

**Set:** 5 Glacier Works pieces. **Fuels:** Thermite Slurry, Rendered Lard. **Affixes:** Potent, Recycling, Sticky. **Home:** Sewer Delta. **Lab:** threat 26.5 at T4, 30.2 at T5.

**The exotic:** Crucible Sieve (the exotic Thermite Slurry filter II, in the filter slot). CRACKED OPEN: Armor Thermite breaks stuns everything within 160 px for 2 s, and that mutant takes +200% from everything for 6 s. Lab: +3.7 threat.

### Slow Cooker Slick
**Miser** (cheap fuel, long burns, cool head, Slow Cooker). "Everything it touches loses its footing." Set it, forget it, come back to dinner. Nothing here is in a hurry. This one runs Rendered Lard and is built around the Tallow Mitt.

- Slow Cooker set, five pieces: +25% burn duration; tanks regen +1.5 units/s while you aren't firing; Stacks on mutants outside the cone deal +45% damage; SIMMER: every 10th unit applies 2 stacks, and stacks outside the cone deal +25% more; all fuels +57% stack damage. Five pieces: SECOND HELPING.
- Flashpoint keystone (igniter): A stack's whole burn lands the instant it is applied, at 1.4 times its total, and at 2.8 times that on anything close (the six nearest mutants, or within 220 px). Nothing lingers: Spreading, Toxic and Hellmouth do nothing (burn duration still counts: a longer burn lands more).
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

**Set:** 5 Slow Cooker pieces. **Fuels:** Rendered Lard, Fryer Oil. **Affixes:** Potent, Recycling, Sticky. **Home:** Fungal Bog. **Lab:** threat 26.8 at T4, 30.4 at T5.

**The exotic:** Tallow Mitt (the exotic Rendered Lard shroud & grip I, in the shroud & grip slot). SLICK: Whatever the gun hits, with any fuel, is slick for 2 s: slowed 50%, and it takes +30% from everything. Lab: +3.4 threat.

### Slow Cooker Heat Sink
**Miser** (cheap fuel, long burns, cool head, Slow Cooker). "Burns its own fever." Set it, forget it, come back to dinner. Nothing here is in a hurry. This one runs Thermite Slurry and is built around the Forge-Heart Altar.

- Slow Cooker set, five pieces: +25% burn duration; tanks regen +1.5 units/s while you aren't firing; Stacks on mutants outside the cone deal +45% damage; SIMMER: every 10th unit applies 2 stacks, and stacks outside the cone deal +25% more; all fuels +57% stack damage. Five pieces: SECOND HELPING.
- Flashpoint keystone (igniter): A stack's whole burn lands the instant it is applied, at 1.4 times its total, and at 2.8 times that on anything close (the six nearest mutants, or within 220 px). Nothing lingers: Spreading, Toxic and Hellmouth do nothing (burn duration still counts: a longer burn lands more).
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

**Set:** 5 Slow Cooker pieces. **Fuels:** Thermite Slurry, Rendered Lard. **Affixes:** Potent, Recycling, Sticky. **Home:** Fungal Bog. **Lab:** threat 26.8 at T4, 31.1 at T5.

**The exotic:** Forge-Heart Altar (the exotic Thermite Slurry tank chassis III, in the tank chassis slot). HEAT SINK: Above half heat Thermite burns the gun's heat instead of fuel, and hits +50%. Lab: +4.3 threat.

### Bandolier Tar Pit
**Juggler** (many tanks, many swaps, Bandolier). "They check in. They don't check out." Why choose a fuel? Wear all of them and let the mutants sort it out. This one runs Swamp Napalm and is built around the Bog Mitt.

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

**Set:** 5 Bandolier pieces. **Fuels:** Swamp Napalm, Thermite Slurry, Ion Gel. **Affixes:** Potent, Recycling, Sticky. **Home:** Scrap Mountain. **Lab:** threat 23.3 at T4, 27.2 at T5.

**The exotic:** Bog Mitt (the exotic Swamp Napalm shroud & grip I, in the shroud & grip slot). TAR PIT: Napalm slows 6% a stack, up to 55%. A mutant at the cap is stuck: every other hit it throws at the pig does nothing. Lab: +2.5 threat.

### Bandolier Cracked Open
**Juggler** (many tanks, many swaps, Bandolier). "Opens with a bang." Why choose a fuel? Wear all of them and let the mutants sort it out. This one runs Thermite Slurry and is built around the Crucible Sieve.

- Bandolier set, five pieces: +1 tank mount on any chassis (up to 4); Swapping tanks gives +50% stack damage for 3 s; QUICK DRAW: a swap within 1 s of the last costs no swap time. Five pieces: FRESH TANK.
- Gatling Drum keystone (chassis): Each unit fires from every mounted tank at once, each applying its own fuel's stack, and every tank refills like an idle one. Drains every tank together, each unit makes double heat, and every stack lands at 60%.
- Crucible Sieve, the exotic (filter): CRACKED OPEN. Armor Thermite breaks stuns everything within 160 px for 2 s, and that mutant takes +200% from everything for 6 s.
- Thermite Slurry runs hot and eats armor. With it, Rocket Hooch and Ion Gel. Home: the Scrap Mountain.
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

**Set:** 5 Bandolier pieces. **Fuels:** Thermite Slurry, Rocket Hooch, Ion Gel. **Affixes:** Potent, Recycling, Sticky. **Home:** Scrap Mountain. **Lab:** threat 23.0 at T4, 26.0 at T5.

**The exotic:** Crucible Sieve (the exotic Thermite Slurry filter II, in the filter slot). CRACKED OPEN: Armor Thermite breaks stuns everything within 160 px for 2 s, and that mutant takes +200% from everything for 6 s. Lab: +1.2 threat.

### Last Call Fried Stiff
**Juggler** (many tanks, many swaps, Last Call). "Golden brown and going nowhere." The bottom of the tank is where it does its best work. This one runs Fryer Oil and is built around the Batter Mitt.

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

**Set:** 5 Last Call pieces. **Fuels:** Fryer Oil, Rocket Hooch, Thermite Slurry. **Affixes:** Potent, Recycling, Sticky. **Home:** Dead Drive-In. **Lab:** threat 25.0 at T4, 28.7 at T5.

**The exotic:** Batter Mitt (the exotic Fryer Oil shroud & grip I, in the shroud & grip slot). FRIED STIFF: A mutant Fryer Oil touched in the last 3 s is slowed 60%. Lab: +3.1 threat.

### Last Call Critical Mass
**Juggler** (many tanks, many swaps, Last Call). "Sixty stacks and counting down." The bottom of the tank is where it does its best work. This one runs Rad Syrup and is built around the Half-Life Crown.

- Last Call set, five pieces: The horn sounds 15 s before the truck (not 10), and kills in its window pay x4 (not x3); The gun makes no heat while the truck is starting; ENCORE: when the truck arrives the horn sounds once more: another wave, another window, another 30 s.
- Gatling Drum keystone (chassis): Each unit fires from every mounted tank at once, each applying its own fuel's stack, and every tank refills like an idle one. Drains every tank together, each unit makes double heat, and every stack lands at 60%.
- Half-Life Crown, the exotic (igniter): CRITICAL MASS. At 60 Rad stacks a mutant goes critical, once: 100% of what its Rad had left hits everything within 120 px, and each gets 15 stacks.
- Rad Syrup hits harder the longer it clings. With it, Rocket Hooch and Thermite Slurry. Home: the Dead Drive-In.
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

**Set:** 5 Last Call pieces. **Fuels:** Rad Syrup, Rocket Hooch, Thermite Slurry. **Affixes:** Potent, Recycling, Sticky. **Home:** Dead Drive-In. **Lab:** threat 23.8 at T4, 26.1 at T5.

**The exotic:** Half-Life Crown (the exotic Rad Syrup igniter III, in the igniter slot; the fuel becomes Critical Mass). CRITICAL MASS: At 60 Rad stacks a mutant goes critical, once: 100% of what its Rad had left hits everything within 120 px, and each gets 15 stacks. Lab: +0.5 threat.

### Moonshine Run Slick
**Juggler** (many tanks, many swaps, Moonshine Run). "Everything it touches loses its footing." A fresh tank is a fresh start, and this one starts fresh every two seconds. This one runs Rendered Lard and is built around the Tallow Mitt.

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

**Set:** 5 Moonshine Run pieces. **Fuels:** Rendered Lard, Rocket Hooch, Thermite Slurry. **Affixes:** Potent, Recycling, Sticky. **Home:** Dead Drive-In. **Lab:** threat 26.2 at T4, 29.0 at T5.

**The exotic:** Tallow Mitt (the exotic Rendered Lard shroud & grip I, in the shroud & grip slot). SLICK: Whatever the gun hits, with any fuel, is slick for 2 s: slowed 50%, and it takes +30% from everything. Lab: +1.6 threat.

### Moonshine Run Radiation Sickness
**Juggler** (many tanks, many swaps, Moonshine Run). "They slow down. You don't." A fresh tank is a fresh start, and this one starts fresh every two seconds. This one runs Rad Syrup and is built around the Half-Life Altar.

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

**Set:** 5 Moonshine Run pieces. **Fuels:** Rad Syrup, Rocket Hooch, Thermite Slurry. **Affixes:** Potent, Recycling, Sticky. **Home:** Dead Drive-In. **Lab:** threat 24.8 at T4, 28.1 at T5.

**The exotic:** Half-Life Altar (the exotic Rad Syrup tank chassis III, in the tank chassis slot). RADIATION SICKNESS: From its first dose a mutant sickens every 2 s: 12% slower and +48% from everything each time, down to half speed and +200%. Lab: +1.4 threat.

### Potluck Fried Stiff
**Juggler** (many tanks, many swaps, Potluck). "Golden brown and going nowhere." Everyone brings a fuel. Nobody leaves hungry. This one runs Fryer Oil and is built around the Batter Mitt.

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

**Set:** 5 Potluck pieces. **Fuels:** Fryer Oil, Rendered Lard, Thermite Slurry. **Affixes:** Potent, Recycling, Sticky. **Home:** Bloat Marsh. **Lab:** threat 28.1 at T4, 33.7 at T5.

**The exotic:** Batter Mitt (the exotic Fryer Oil shroud & grip I, in the shroud & grip slot). FRIED STIFF: A mutant Fryer Oil touched in the last 3 s is slowed 60%. Lab: +5.7 threat.

### Potluck Redline
**Juggler** (many tanks, many swaps, Potluck). "The needle belongs in the red." Everyone brings a fuel. Nobody leaves hungry. This one runs Rocket Hooch and is built around the Moonshine Bellows.

- Potluck set, five pieces: A burning mutant passes 5 stacks a second to each mutant touching it; 10 stacks a second, to mutants within 40 px; PATIENT ZERO: the mutant carrying the most stacks shares half of them each second with everything within 150 px (a shared stack isn't shared again).
- Gatling Drum keystone (chassis): Each unit fires from every mounted tank at once, each applying its own fuel's stack, and every tank refills like an idle one. Drains every tank together, each unit makes double heat, and every stack lands at 60%.
- Moonshine Bellows, the exotic (pump): REDLINE. Past half heat Hooch hits harder the hotter the gun: +300% at full heat. It heats the gun 25% faster.
- Rocket Hooch burns hot, short and against everything. With it, Rendered Lard and Thermite Slurry. Home: the Bloat Marsh.
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

**Set:** 5 Potluck pieces. **Fuels:** Rocket Hooch, Rendered Lard, Thermite Slurry. **Affixes:** Potent, Recycling, Sticky. **Home:** Bloat Marsh. **Lab:** threat 25.8 at T4, 29.1 at T5.

**The exotic:** Moonshine Bellows (the exotic Rocket Hooch pump II, in the pump slot). REDLINE: Past half heat Hooch hits harder the hotter the gun: +300% at full heat. It heats the gun 25% faster. Lab: +2.0 threat.

### Test Kitchen Fried Stiff
**Juggler** (many tanks, many swaps, Test Kitchen). "Golden brown and going nowhere." Two fuels walk into a mutant. The results are peer-reviewed. This one runs Fryer Oil and is built around the Batter Mitt.

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

**Set:** 5 Test Kitchen pieces. **Fuels:** Fryer Oil, Rocket Hooch, Thermite Slurry. **Affixes:** Potent, Recycling, Sticky. **Home:** The Food Court. **Lab:** threat 28.4 at T4, 33.1 at T5.

**The exotic:** Batter Mitt (the exotic Fryer Oil shroud & grip I, in the shroud & grip slot). FRIED STIFF: A mutant Fryer Oil touched in the last 3 s is slowed 60%. Lab: +4.6 threat.

### Test Kitchen Dirty Bomb
**Juggler** (many tanks, many swaps, Test Kitchen). "Shares generously on the way out." Two fuels walk into a mutant. The results are peer-reviewed. This one runs Rad Syrup and is built around the Half-Life Throat.

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

**Set:** 5 Test Kitchen pieces. **Fuels:** Rad Syrup, Rocket Hooch, Thermite Slurry. **Affixes:** Potent, Recycling, Sticky. **Home:** The Food Court. **Lab:** threat 27.1 at T4, 30.5 at T5.

**The exotic:** Half-Life Throat (the exotic Rad Syrup nozzle III, in the nozzle slot). DIRTY BOMB: A mutant that dies with Rad Syrup on it throws 34% of its stacks, at their age, and 110 fresh ones onto each of 3 mutants nearby. Lab: +2.0 threat.

*Lab results: a robot pig wearing five set pieces, the keystone and the exotic, every part at T4 (and T5 for the T5 column) Malevolent with near-perfect rolls, starting at threat 20 at the build's home map, bosses, fuel reactions and all. Your results may vary. Not a toy. Do not refuel near open flame. Do not taste the Lard. Mutants were harmed in the making of this advertisement.

## Saves, settings and logs

### Saves
- **3 save slots.** The main menu's **SAVE SLOTS** shows what each holds (runs, best threat, Energy Sprinkles, time played, cats, parts, when it was saved) and has **PLAY**, **NEW GAME**, **IMPORT** and **DELETE** for each. Starting over or deleting a slot that holds a game asks first; deleting takes its backup and career journal too. The game opens on the slot you played last, and the Esc menu names it. Settings and the BALANCE menu are shared by every slot.
- Every version keeps its own saves, so updating never breaks your game. **IMPORT** brings the newest older version's save into a slot (that save itself isn't changed); the main menu also offers it while the slot in use has no progress.
- The game saves after every change, keeping the save before as a backup. Settings has the volume, the **MUSIC** level (v0.9.18: the ambient score, two long loops: the wastes in the Smokehouse and the menu, the burn in a run, cross-fading between them; 0 turns it off), the window size, fullscreen, fire effects, an FPS counter, VSync and a frame limit.
- **The small HUD** (v0.9.22): **[H]** in a run folds the stat window to icons and bars (the hearts, the shields, each tank's fuel icon and bar with the active one bright, the heat bar) and back to the full panel with its numbers and words; the choice is remembered.
- **Sounds and the score** (v0.9.18): starting the truck is an engine start (the key, the starter labouring, two coughs, the catch, the idle), and the score is synthesized from the game's own generator (tools/audio/make_audio.py), so it can be regenerated. The chef cat in the truck's serving window bobs, turns and pads back and forth behind the counter during a run.

### The BALANCE menu
- In the Esc menu and on the main menu: a slider for each of these, to try the game tuned your way: enemy density, enemy toughness, enemy speed, elite chance, boss beat (0 = no bosses), boss toughness, fuel reactions (0 = off), wave size at threat 0 (% of a full crowd), wave size from threat 12 on (% of a full crowd), fewer mutants, tougher mutants (how much), start threat dial: how far below your best, reputation rate, meat price, faction contracts: minutes to the next, mystery meat farm: cuts a harvest, mystery meat farm: minutes a harvest, crafting cost: energy sprinkles, crafting cost: scrap metal, crafting cost: mutant bits, crafting cost: chemicals, set blueprints: favor cost, exotic blueprints: favor price, crafting cost: tallow brick, crafting cost: napalm amber, crafting cost: slag heart, crafting cost: ion crystal, crafting cost: still copper, crafting cost: isotope seed, crafting cost: crackling.
- **LOCK** a number (or press **Space** over it) so a stray drag can't move it (RESET and RESET ALL leave it alone). Changes apply at once (mutant changes from the next wave), are saved with this version, and are written to the debug log at the start of every session, whenever they change, and with every run.

### Frame rate
- **VSYNC** on (the default) draws one frame per screen refresh, so on a 60 Hz screen the FPS counter sits at 60 however much room the machine has to spare. Turn it off to see what each fire setting really costs (the picture may tear while it's off).
- **FRAME LIMIT** caps the frames a second (30, 60, 120, 144, 165, 240); **NONE** with VSync off runs flat out. A limit keeps the graphics card cooler and quieter.
- The FPS counter is green near the limit, yellow below it and red when slow. A graphics driver set to force VSync on keeps the game at the refresh rate whatever the setting says.

### Fire effects
Every setting fires the same flamethrower: damage comes from the cone and the burn rules, never from how the fire is drawn.
- **LIVE ULTRA** (the default): the fire simulation plus burning fuel (the jet sprays fuel that catches as it flies, so it rolls and billows), fire light on the ground, the pig and the mutants, heat haze, embers and sparks, scorch marks and glowing coals where things burned, and puddles that keep burning with flames on them. v0.9.15 gave it a torch root, a deeper tonal range and smoke lit by the fire; v0.9.19 (the flame build) a **drawn flame core** (a tapered torch along the aim for the first third of the range, licking at its edges and blending into the simulation's billow, so the jet leaves the gun as one flame instead of a thin fed line), **soot** (burnt-out heat with no vapour left reads darker orange, so the body of the flame has structure that moves with the flow), **smoke puffs** (pixel-art puffs with edges, rising off burning mutants, pools, blasts and the end of the jet, over a thinner wash), an **impact splash** where the cone first touches a mutant (a flash on the body and a spray of sparks back toward the gun) with a brighter, pulsing glow on a mutant carrying 20 or more stacks, and a **rim light** on mutants within 150 px of the jet, a burning pool or a burning mutant, on the side facing the fire. v0.9.22: a wide cone (30 degrees and up) burns as **one continuous fan** instead of 2 to 5 tongues on fixed lanes: the whole sector is fed at once, blown straight out from the muzzle, with the fuel rolling across the arc as drifting sheets and thinning toward the edges, and the drawn core opens to the cone; the tongues read as prongs.
- **LIVE HIGH**: the fire simulation (the flame splashes off mutants, bends as you sweep, rains burning fuel). **LIVE LOW**: the same, chunkier and lighter on the graphics chip. **CLASSIC**: the old particle flame.
- If the game can't keep up (under 48 frames a second while firing, or under 80% of a lower frame limit) it steps down by itself (ULTRA to HIGH, HIGH to LOW), says so, and remembers it.

### Logs (for bug reports)
- With **Settings > DEBUG LOG** on (the default), each session writes a text file to a **logs** folder next to the game: your kit, every run in detail, hub actions, the crew and any errors. **OPEN LOG FOLDER** opens it.
- The result screen's **COPY RUN LOG** copies just that run, ready to paste.
- **Settings > DUMP CAREER** writes your whole career (every run, milestones, how the kit changed, hour by hour) to one file in the same folder.
- The Windows download is a debug build so the log catches every error; it can run a little slower than a release build would.

### This guide
- It's in the game (**F1**) and on the download page as **WIKI.md** (https://github.com/LichIndex/MMM-Malevolent-Meat-Master/blob/HEAD/WIKI.md), and both are written from the game's data by each build, so they always match the version you have.
