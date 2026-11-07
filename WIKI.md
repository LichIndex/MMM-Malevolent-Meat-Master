# Malevolent Meat Master v0.9.0: the wiki

Everything in the game, from the game's own data (written by the build you can download, so the numbers match it). The same pages are in the game: press **F1**, or **GUIDE** in the Smokehouse or the Esc menu. [Download the game](https://github.com/LichIndex/MMM-Malevolent-Meat-Master#readme).

- [Start here](#start-here)
- [Runs, threat and drops](#runs-threat-and-drops)
- [The flamethrower](#the-flamethrower)
- [Parts and loot lanes](#parts-and-loot-lanes)
- [Sets](#sets)
- [Exotic parts](#exotic-parts)
- [Fuels and stills](#fuels-and-stills)
- [Mutants](#mutants)
- [Destinations and factions](#destinations-and-factions)
- [Meat, sauce and selling](#meat-sauce-and-selling)
- [The Smokehouse](#the-smokehouse)
- [Cats and the crew](#cats-and-the-crew)
- [Automation: the 8-Ball and the hands](#automation-the-8-ball-and-the-hands)
- [Endgame](#endgame)
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
| Scrap Metal | Mutants with armor; scrapping parts; the Scrap Sifter | Chassis, pumps, shrouds, tank mods, the truck |
| Mutant Bits | Mutants with only health; the Rendering Vat | Fuel lines, nozzles, the kitchen |
| Chemicals | Mutants with shields; the Sludge Drip | Igniters, filters, stills |
| Sauce ingredients | Mutants (12% a kill), cats, faction shops | Sauces |
| Blueprint Shards | Breaking down set pieces; tuxedo cats | Set blueprints; picking a destination's featured slot |
| Mutagen | Elites past threat 15; scrapping Mutated and Malevolent parts; radiant cats | Mutating a part's behavior |

### A first hour
- Fight at the **Smokehouse Outskirts**, start the truck while you're still comfortable, and bring the meat home. A short run that gets out beats a long one that doesn't.
- Brew **Basic Rub** or **Backyard Glaze** with whatever ingredients you have, sauce the meat, and let the smoker and counter turn it into ◆.
- Spend ◆ in the **Craft** tab on better parts, and on **armor** in the Loadout tab. Scrap the salvage you won't wear: it teaches you new lanes.
- Reach threat 3 anywhere to open the **Rust Flats**; threat 6 opens tier 2 parts.
- Watch the heat bar. Let it hit 100% and the gun burns you.

## Runs, threat and drops

### Threat
- The threat rises one level every **30 s**. Each destination grows mutants' health, armor and shields by its own rate a level (see Destinations), and on top of that every pool toughens ×1.19 a level up to threat 11 and ×1.1 a level after it.
- They also come faster (a wave every 1.7 s at first, ×0.83 a level, down to one every 0.22 s), in packs (5% more likely a level, up to 55%) and move 2% faster a level (up to ×1.6).
- **Fewer, tougher mutants:** waves come at 80% of that pace at threat 0, falling to 60% from threat 12 on. Each mutant is tougher for the ones that don't come (×1.07 at threat 0, ×1.17 from threat 12), and as many elites still turn up, so they're a bigger share of a wave deeper in. An ordinary mutant's drops count for the ones it stands in for, so a run brings home about as much as before.
- Meat is worth **+45% of its base value per threat level**, so staying longer pays, until it doesn't.
- Your best threat anywhere opens part tiers: T2 at 6, T3 at 12, T4 at 16.

### What mutants drop

| Drop | Chance a kill | Notes |
|---|---|---|
| Raw meat | 45% (elites always, 2 cuts) | Each mutant has its own cut. Worth its base × (1 + 0.45 × threat level). |
| Materials | 30% for each kind it carries, × the destination's bias (elites always, ×3) | Armor → Scrap Metal, shields → Chemicals, health only → Mutant Bits. 1 each, +1 every 6 threat levels. |
| Sauce ingredients | 12% (elites twice that) | From the destination's own mix. |
| Salvage crate (a part) | 1% + 0.1% a level, up to 3% | 5% of crates hold a set piece instead. |
| Keystone | 0.15% of crates from threat 15, 0.4% in Infested runs (×3 from elites) | Rare parts that break a rule (see Parts). |
| Mutagen | Elites past threat 15: 12% |  |
| Still blueprint | Reach the threat shown on the Map at that destination, then get out | A new fuel (see Fuels). |

- Since mutants come fewer and tougher, each ordinary one's chances above count for the ones it stands in for (×1.25 at threat 0, ×1.67 from threat 12); elites keep theirs and turn up as often as before.
- **Gear thins out deeper.** Kills a minute explode as the threat rises, so from threat 6 salvage, set pieces, keystones and elite Mutagen drop ×0.88 as often each level. Meat, materials and ingredients don't thin out.
- **Salvage tiers** follow the run's threat (T2 from 6, T3 from 12, T4 from 16). Once T3 is open a crate holds one of the top two tiers; past threat 21 (Infested) only T4.
- **Salvage quality** rises with the threat, but tops out at Mutated until the run is Infested (past threat 21).
- Each destination **features one slot a day**: its parts drop ×4 as often there (the Map shows which; 60 Blueprint Shards picks another for the rest of the day).

### Elites
- 1% chance a spawn, +0.2% a threat level and +1% a heat-dial level. They have ×3 the pools and an ELITE tag.
- They always drop 2 cuts, triple materials and a part: 40% of the time a set piece, otherwise salvage from 2 threat levels higher (gear thinning applies).

### The heat dial
Each destination has a dial from 0 to 5 on the Map. Each level:
- adds 0.03 to every growth rate (tougher mutants, faster);
- +25% crates, set pieces, blueprints and elites; +15% meat value; +20% material drops.

### Start threat
- Beside the heat dial, **START THREAT** lets a run begin at a higher threat, skipping the easy opening waves (and their drops). It reaches up to your best threat at that destination minus 7. The smoker still needs 90 s of survival from the start.

### Getting out, and dying
- **E** starts the truck under you. Its engine takes 30 s to catch; the fight (and the threat) goes on until it does, then it drives you home. Survive and everything comes home.
- The result screen sums the run up (salvage as a count by tier). **Enter**, **Space** or **E** goes back to the Smokehouse.
- **If you die** (or abandon the run): the raw meat, fried cuts, salvage and any blueprint are lost, and you lose 10% + 5% per threat level (up to 75%) of the run's materials, ingredients and Mutagen. The smoker's load comes out overcooked (worth ×0.6).

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
- Press **R** (or the Shoggoth button at the bottom left of a run) and the Shoggoth drives: it aims, burns, vents before the heat warning, swaps tanks and starts the truck. Press R again to take over. It's the same pilot that tests every build.
- **Its fee:** it eats 1 cut of meat in 5 of what drops while it drives. Nothing else.
- On the AUTOMATION tab (RUNS): **ON/OFF** (your runs start with it driving; the 8-Ball's always do) and **when it starts the truck**: AUTO (2 threat levels under what your kit should hold there), only when hurt, or at a threat you pick. It always calls it at 5 HP or less.

### The Magic 8-Ball
- It runs the pig for you, one Shoggoth run after another, working a list of goals: see **Automation: the 8-Ball and the hands**. Its settings live on the AUTOMATION tab; the Map tab has one line saying what it does next. **B** switches it on and off anywhere.

## The flamethrower

### How fire hurts
- Every unit of fuel that lands adds a **burn stack** to the mutant. A stack deals the fuel's damage every 0.25 s until it runs out: 3 s × the fuel's burn × your burn-duration bonuses. Stacks never cap, so keep the flame on a crowd and they pile up.
- Damage eats **shields first, then armor, then health**. Each fuel has its own multiplier against each (see Fuels): a fuel weak against armor barely scratches a Scrapper until something else strips it.
- **Peak DPS** (the Loadout and Tab sheets show it) = flow × burn duration × stack damage / 0.25 s: what the gun does once every unit is landing.

### The seven slots and the tank mod

| Slot | Sets | T1 | T2 | T3 | T4 |
|---|---|---|---|---|---|
| Fuel Line | Flow: fuel units a second (more stacks, more heat) | 12 flow/s | 18 flow/s | 27 flow/s | 40 flow/s |
| Nozzle | Cone width and range | 40° cone, 380 range | 42° cone, 395 range | 44° cone, 410 range | 46° cone, 425 range |
| Tank Chassis | Tank mounts (how many fuels you carry) | 1 tank mount | 2 tank mounts | 2 tank mounts | 3 tank mounts |
| Pump | Pressure: more flow | +12% flow | +18% flow | +25% flow | +35% flow |
| Igniter | Burn duration | +15% burn duration | +20% burn duration | +28% burn duration | +38% burn duration |
| Filter | Stack damage | +12% stack damage | +18% stack damage | +24% stack damage | +32% stack damage |
| Shroud & Grip | Heat cap and cooling | 130 heat cap, cools 32/s | 150 heat cap, cools 36/s | 170 heat cap, cools 42/s | 200 heat cap, cools 50/s |
| Tank Mod | Tank capacity (one per mounted tank) | +30% tank capacity | +60% tank capacity | +100% tank capacity | +160% tank capacity |

These are the tier baselines (Scavenged quality, ×1, before the lane). Quality multiplies the main stat (Junk ×0.85 up to Malevolent ×1.5), and the lane reshapes it (see Parts).

### Heat
- Firing heats the gun; the shroud sets how much heat it holds and how fast it cools. Cooling starts 0.5 s after you let go.
- At **80%** the gun hisses and flow drops to ×0.7. At **100%** it burns you while you keep firing: 1 armor a second, and once your armor is gone 1 HP every 1.5 s.
- Heat a unit = the fuel's heat × 0.4 × (1 + 15% for each tank past the first) × your heat modifiers × 2 × (30 / flow)^0.5. So heat a second grows with the square root of flow: a typical kit overheats after 5 to 8 s of solid fire at any tier.

### Fuel and tanks
- Each mounted tank holds one fuel. A tank holds 120 units, +25% per tank level of its still, then tank mods and bonuses.
- It refills at 5 units/s, +1.5 per still level. The tank you're firing from only refills 0.75 s after you stop; the others always refill.
- **Mounts:** the chassis sets them (T1 1, T2 and T3 2, T4 3); the Rack lane and the Bandolier set add one, up to 4. Each tank past the first costs 15% flow (less on a better chassis) and 15% heat. Swapping takes 0.4 s.
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

## Parts and loot lanes

### Tiers
- Parts come in **T0** (the starter parts) to **T4**. Their names are coloured by tier: T1 white, T2 green, T3 purple, T4 gold; set pieces teal. Pips show the tier too.
- You can craft (and find) a tier once your best threat reaches it: T2 at 6, T3 at 12, T4 at 16.

### Qualities

| Quality | Main stat | Affixes | Affix strength |
|---|---|---|---|
| Junk | ×0.85 | 0 | ×0.6 |
| Scavenged | ×1 | 0 to 1 | ×0.8 |
| Tuned | ×1.15 | 1 | ×1 |
| Mutated | ×1.3 | 2 | ×1.25 |
| Malevolent | ×1.5 | 3 | ×1.6 |

A part also has a 30% chance of a **behavior** (one per part, at the behavior's minimum quality and up).

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
| Lance | A needle at long range | ▲ Range x1.04, +15% burn duration | ▼ Cone x0.4 | Lancer |
| Fan | The steady all-rounder | ▲ Cone x1.5, +35% stack damage | ▼ No extra reach, and +10% heat | Juggler, Miser |
| Bloom | Lets them come close | ▲ Cone x2, +220% stack damage within 280 px, -20% heat | ▼ No extra reach, and the bonus only lands on what is already close | Brawler |

#### Tank Chassis

| Lane | Plays like | Benefit | Drawback | Builds |
|---|---|---|---|---|
| Rack | More tanks | ▲ +1 tank mount | ▼ -15% flow per extra tank, swaps take 0.6 s | Juggler |
| Saddle Tank | One big tank | ▲ One mount with +200% capacity and +200% regen | ▼ One fuel only: nothing to rotate to when it's the wrong one | Miser, Lancer, Furnace |
| Carousel | Fast hands | ▲ Swaps take 0.1 s; +30% stack damage for 1 s after a swap | ▼ -20% capacity on every tank | Juggler |

#### Pump

| Lane | Plays like | Benefit | Drawback | Builds |
|---|---|---|---|---|
| Booster | More pressure | ▲ Pressure x1.5, +10% range | ▼ +20% heat | Brawler, Furnace |
| Siphon | Refills while it fires | ▲ The active tank regens while firing, at 40% of its idle rate | ▼ No pressure: +0% flow | Miser |
| Accumulator | Saves it up | ▲ Stores pressure while idle; the first 2 s of a burst fire up to +100% flow | ▼ No pressure once the store is spent | Juggler, Lancer |

#### Igniter

| Lane | Plays like | Benefit | Drawback | Builds |
|---|---|---|---|---|
| Smoulder | Long, low burns | ▲ Burn duration x1.6 | ▼ -15% stack damage | Miser, Brawler |
| Flash | Hits now | ▲ +50% stack damage | ▼ -30% burn duration | Brawler, Juggler |
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

#### Tank Mod

| Lane | Plays like | Benefit | Drawback | Builds |
|---|---|---|---|---|
| Jerrycan | Just more | ▲ Capacity x1.4 | ▼ Swapping onto this tank takes 50% longer | Miser, Lancer |
| Drip Bottle | Small but refills | ▲ This tank regens +2 / +3 / +4 / +5 units/s | ▼ Capacity x0.5 | Miser, Juggler |
| Primer Cell | First shots hit hardest | ▲ The first 25 units from a full tank deal +60% stack damage | ▼ Capacity x0.7 | Juggler, Lancer |

### Builds
Lanes, sets and keystones lean toward five ways to play. None is required; mix what works.

| Build | Style | Lanes | Sets |
|---|---|---|---|
| Brawler | Lets them come close: wide cones, big bursts, damage up close. | Gusher, Bloom, Booster, Smoulder, Flash, Distiller, Vent Cowl | Deep Fryer, Grease Fire, Pit Boss |
| Lancer | A needle at long range: picks apart big, shielded and armored targets. | Capillary, Lance, Saddle Tank, Accumulator, Stoker, Distiller, Catalyst, Heatsink, Jerrycan, Primer Cell | Meltdown, Steeple Works, Tesla Coilworks |
| Furnace | Runs hot on purpose: holds heat and gets stronger near the top of the bar. | Spool-Up Coil, Saddle Tank, Booster, Distiller, Insulated, Vent Cowl | Boiler Room, Foundry Rig, Hellmouth |
| Miser | Makes fuel last: long burns, refills, cheap fire, one big tank. | Capillary, Fan, Saddle Tank, Siphon, Smoulder, Coarse Mesh, Heatsink, Jerrycan, Drip Bottle | Glacier Works, Slow Cooker, Thrift Shop |
| Juggler | Many tanks and fast swaps: the right fuel for every mutant. | Gusher, Fan, Rack, Carousel, Accumulator, Flash, Catalyst, Heatsink, Drip Bottle, Primer Cell | Bandolier, Cocktail Hour, Moonshine Run |

### Affixes
Numeric rolls on a part. The values are for Tuned quality; multiply by the part's affix strength (Malevolent ×1.6). An affix tied to a fuel only works on that fuel's tank.

| Affix | Raises | Fuel | Roll | From quality |
|---|---|---|---|---|
| Boggy | Fuel regen | All fuels | +8% to +20% | Junk |
| Bulging | Tank capacity | All fuels | +8% to +20% | Junk |
| Cooled | Heat | All fuels | -15% to -6% | Junk |
| Greasy | Vs health | All fuels | +5% to +12% | Junk |
| Ionized | Vs shields | All fuels | +20% to +45% | Junk |
| Molten | Vs armor | All fuels | +10% to +25% | Junk |
| Potent | Stack damage | All fuels | +6% to +15% | Junk |
| Pressurized | Flow | All fuels | +5% to +12% | Junk |
| Recycling | Fuel regen | All fuels | +0.6 to +1.6 | Junk |
| Smooth | Cooling | All fuels | +6% to +15% | Junk |
| Sticky | Burn duration | All fuels | +8% to +20% | Junk |

### Behaviors

| Behavior | What it does | From quality |
|---|---|---|
| Chilling | Burning mutants are slowed 20% | Mutated |
| Spreading | Burns jump to 2 nearby mutants when a burning mutant dies | Mutated |
| Toxic | Kills leave a toxic cloud that burns 2 stacks a tick for 2 s (70 px) | Mutated |
| Volatile | Burning kills explode, putting 1 stack on mutants nearby | Mutated |

### Keystones
Rare T4 parts that break one rule, at a cost. They only drop (from threat 15; more in Infested runs) and are never crafted.

| Keystone | Slot | Rule | Cost | Builds | Drops from |
|---|---|---|---|---|---|
| Afterburner | Pump | Above 75% heat, flow x1.3 instead of the usual slowdown to x0.7 | Overheat damage x2 | Furnace | threat 15 |
| Backdraft Ring | Nozzle | A 360-degree ring of fire, 390 px out: no aiming, nothing slips past the sides | +30% heat, and range bonuses from lanes and sets do nothing | Brawler | threat 15 |
| Blood Line | Fuel Line | With the tank empty, keeps firing at full flow | Every 30 units cost the pig 1 armor, then 1 HP; it will kill you | Furnace, Brawler | threat 15 |
| Double Distill | Filter | +130% stack damage | Each unit costs 1.5 fuel and makes 15% more heat | Lancer, Furnace | threat 15 |
| Fever Grip | Shroud & Grip | +1% stack damage per 4% heat | Overheating hits the pig's HP directly, skipping armor | Furnace | threat 15 |
| Flashpoint | Igniter | A stack's whole burn damage lands the instant it is applied | Nothing lingers: Spreading, Toxic, Hellmouth and burn duration do nothing | Lancer, Brawler | threat 15 |
| Gatling Drum | Tank Chassis | Each unit fires from every mounted tank at once, each applying its own fuel's stack, and every tank refills like an idle one | Drains every tank together, and each unit makes double heat | Juggler | threat 15 |
| Shoggoth Bladder | Tank Mod | Refills 2 units for every kill its fuel makes | Half the usual passive regen | Brawler | threat 15 |

### Malevolent parts
The top quality. Salvage only rolls it in Infested runs (past threat 21), each level past that adding 2 quality steps; until then it tops out at Mutated. You can still craft one, or upgrade a part's quality at the Workbench (the last step, Mutated to Malevolent, costs ×0.4).

## Sets

- Every set has a piece for each of the seven slots. Wearing **2, 3 and 4 pieces** turns on its three bonuses, and every bonus works on **every fuel** (since v0.7.8; the fuel transformations moved to exotic parts). A piece is a normal part of its tier and slot (it rolls a lane and affixes too).
- **Where they drop:** set pieces come from salvage crates (5% of them) and elites (40%). A set piece found at a destination comes 70% of the time from a set that drops there; the rest from any common set, and 5% from a rare one.
- **Blueprints:** breaking a piece down (Loadout > Stash) gives 10 + 2 × its quality Blueprint Shards, times (1 - 0.75 × the share of set blueprints you own; v0.8.2), so ×0.25 once you own them all. A set's blueprint costs 30 Shards (Workbench > SETS), then you craft its pieces for ◆ and materials. Faction reputation gives some blueprints too, and Hellmouth's needs one found Hellmouth piece first (or the Glow Cult's top reputation).

### Deep Fryer
Brawler build · all fuels · drops at the The Flesh Farms
- **2 pieces:** Kills drop +25% raw meat
- **3 pieces:** +40% stack damage within 220 px
- **4 pieces:** BATTERED: mutants within 220 px take +1% per stack on them (up to +60%)

### Grease Fire
Brawler build · all fuels · drops at the Smokehouse Outskirts
- **2 pieces:** Stacks +60% damage
- **3 pieces:** Burning kills splash 1 stack nearby
- **4 pieces:** GREASE FIRE: burning kills explode for 2 stacks in a wide blast

### Pit Boss
Brawler build · all fuels · drops at the Tank Graveyard
- **2 pieces:** +15% stack damage within 220 px
- **3 pieces:** Each hit the pig takes vents 30 heat as a burst around him
- **4 pieces:** BURNING MAN: with 10+ mutants within 220 px, flow +30% and the pig takes 30% less damage

### Meltdown
Lancer build · all fuels · drops at the Reactor Row
- **2 pieces:** +10% burn duration, and aging fuels (Rad Syrup) age 25% faster
- **3 pieces:** Elites take +10% from every fuel
- **4 pieces:** CRITICAL MASS: a mutant carrying 120+ stacks of one fuel takes +50% from every burn

### Steeple Works
Lancer build · all fuels · drops at the The Neon Strip
- **2 pieces:** +10% burn duration
- **3 pieces:** Mutants beyond 300 px take +5% stack damage
- **4 pieces:** DEADEYE: the first unit to hit an elite each second applies 2 stacks

### Tesla Coilworks
Lancer build · all fuels · drops at the Glow Crater
- **2 pieces:** +10% burn duration
- **3 pieces:** Breaking a shield stuns for 1 s
- **4 pieces:** ARC: every hit chains to 2 nearby mutants

### Boiler Room
Furnace build · all fuels · drops at the Smelter Pits
- **2 pieces:** Heat cap +10%
- **3 pieces:** Above 50% heat, stacks +5% damage
- **4 pieces:** PRESSURE COOKER: reaching 100% heat starts 3 s with no overheat damage and +50% flow, then heat drops to 0 (once per 45 s)

### Foundry Rig
Furnace build · all fuels · drops at the Rust Flats
- **2 pieces:** +10% burn duration
- **3 pieces:** +10% stack damage
- **4 pieces:** SLAG POOLS: kills leave a brief burning pool

### Hellmouth (rare)
Furnace build · all fuels · drops anywhere
- **2 pieces:** All fuels +90% stack damage
- **3 pieces:** All fuels +20% burn duration and 30% less heat
- **4 pieces:** HELLMOUTH: stacks stop expiring while the mutant stays in the cone

### Glacier Works
Miser build · all fuels · drops at the Sewer Delta
- **2 pieces:** +10% burn duration
- **3 pieces:** Burning mutants slow 5%
- **4 pieces:** GLACIER: every fuel runs 40% cooler, and burning mutants slow 10%

### Slow Cooker
Miser build · all fuels · drops at the Fungal Bog
- **2 pieces:** +25% burn duration
- **3 pieces:** Stacks on mutants outside the cone deal +45% damage
- **4 pieces:** SIMMER: every 5th unit is free and every 10th applies 2 stacks; all fuels +57% stack damage

### Thrift Shop
Miser build · all fuels · drops at the The Junk Bazaar
- **2 pieces:** Tanks regen +3.5 units/s
- **3 pieces:** 20% of units cost no fuel
- **4 pieces:** LEFTOVERS: an empty tank refills 40% at once (once every 20 s); +100% stack damage

### Bandolier
Juggler build · all fuels · drops at the Scrap Mountain
- **2 pieces:** +1 tank mount on any chassis (up to 4)
- **3 pieces:** Inactive tanks regen 200% faster
- **4 pieces:** QUICK DRAW: a swap within 1 s of the last costs no swap time and refunds 10 units to the tank you left

### Cocktail Hour
Juggler build · all fuels · drops at the The Food Court
- **2 pieces:** Swap time -50%
- **3 pieces:** Swapping to a different fuel gives +10% stack damage for 4 s, once per distinct fuel (up to +30%)
- **4 pieces:** MOLOTOV MIX: each swap leaves a 120 px pool of the last fuel, burning 1 stack per tick for 2 s; all fuels +120% stack damage

### Moonshine Run
Juggler build · all fuels · drops at the Dead Drive-In
- **2 pieces:** Tanks +50% capacity
- **3 pieces:** Swapping tanks fires +60% flow for 2 s
- **4 pieces:** STILL HOT: every unit also applies a stack of the fuel fired before it; +60% stack damage

## Exotic parts

Three exotic parts for every fuel in every slot (168 in all). Each one **reshapes its fuel wherever that fuel is loaded**: worn in its slot, or fitted as the tank mod on any tank. The top rank's igniter transforms the fuel (Grease Bomb, Frost Napalm, Molten Slag, Arc Gel, Smuggler's Hooch, Hot Syrup, Batter).

### Getting one
- **Blueprint:** bought from the faction that deals in the fuel (CRAFT tab > EXOTICS) with **favor**. Every reputation point you earn also earns a point of favor; spending favor never lowers your reputation level. Rank I needs reputation level 2, rank II level 3, rank III level 4.
- **Crafting:** Energy Sprinkles, Blueprint Shards, the slot's T4 material and the fuel's **exotic material**. It's always T4, on the slot's lane for its rank (rank 1 the slot's first lane, and so on), and rolls quality, affixes and a behavior like a set piece. Exotics can be refined, but not re-forged into another lane, and SCRAP SHOWN leaves them alone; scrapping one gives back half its exotic material.
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

| Rank | Reputation | Blueprint | Crafting |
|---|---|---|---|
| I | level 2 | 30 favor | ◆6,000 + 10 Blueprint Shards + 6 exotic material + the slot's T4 material |
| II | level 3 | 60 favor | ◆12,000 + 20 Blueprint Shards + 12 exotic material + the slot's T4 material |
| III | level 4 | 120 favor | ◆24,000 + 40 Blueprint Shards + 24 exotic material + the slot's T4 material |

### Rendered Lard
Blueprints from the Sewer Kings; crafted with Tallow Brick (Bloat Marsh).

| Slot | Rank | Part | Lane | Effect |
|---|---|---|---|---|
| Fuel Line | I | Tallow Feed | Gusher | +30% Lard tank capacity and +1 Lard regen/s; Lard stacks +15% damage |
| Fuel Line | II | Drippings Artery | Capillary | 15% of Lard units cost no fuel, and its tank refills at a quarter speed while it fires; Lard stacks +20% damage |
| Fuel Line | III | Schmaltz Aorta | Spool-Up Coil | LEFTOVERS: an empty Lard tank refills 50% at once (every 20 s); Lard stacks +50% damage |
| Nozzle | I | Tallow Spout | Lance | Every Lard hit also coats 1 nearby mutant |
| Nozzle | II | Drippings Maw | Fan | When a mutant burning with Lard dies, its burn jumps to 2 nearby mutants (a quarter of its stacks) |
| Nozzle | III | Schmaltz Throat | Bloom | Lard stacks deal +50% on mutants outside the cone and +30% beyond 300 px |
| Tank Chassis | I | Tallow Cradle | Rack | +45% Lard tank capacity |
| Tank Chassis | II | Drippings Rack | Saddle Tank | The Lard tank refills 50% faster |
| Tank Chassis | III | Schmaltz Altar | Carousel | The first 80 Lard units from a full tank deal +100%, and its tank refills twice as fast while another fires |
| Pump | I | Tallow Plunger | Booster | Lard stacks +15% damage |
| Pump | II | Drippings Bellows | Siphon | Lard stacks +40% damage while the gun is above 50% heat |
| Pump | III | Schmaltz Heart | Accumulator | Swapping to Lard fires +100% flow for 2 s; Lard stacks +50% damage |
| Igniter | I | Tallow Wick | Smoulder | Lard burns 25% longer, and Lard stacks +20% damage while the gun is above 50% heat |
| Igniter | II | Drippings Striker | Flash | Burning Lard kills explode for 2 stacks (80 px) |
| Igniter | III | Schmaltz Crown | Stoker | GREASE BOMB: burning Lard kills explode for 3 stacks in a wide blast (100 px); Lard stacks +40% damage |
| Filter | I | Tallow Strainer | Distiller | Lard +25% vs shields and armor |
| Filter | II | Drippings Sieve | Catalyst | Lard deals at least x1.0 against health, shields and armor, and +25% vs health |
| Filter | III | Schmaltz Kidney | Coarse Mesh | Lard stacks +40% damage, and mutants burning with it die at once under 8% health |
| Shroud & Grip | I | Tallow Mitt | Heatsink | Lard runs 25% cooler, and mutants burning with it slow 6% |
| Shroud & Grip | II | Drippings Mantle | Insulated | Lard runs 40% cooler, and mutants burning with it slow 10% |
| Shroud & Grip | III | Schmaltz Shroud | Vent Cowl | Lard runs 80% cooler, and mutants burning with it slow 20% |
| Tank Mod | I | Tallow Jug | Jerrycan | Lard kills drop +20% raw meat |
| Tank Mod | II | Drippings Keg | Drip Bottle | Elites take +45% from Lard, and the first Lard unit to hit an elite each second applies 3 stacks |
| Tank Mod | III | Schmaltz Reliquary | Primer Cell | A mutant carrying 100+ Lard stacks takes +50% from every burn, and Lard stacks deal +1% for every second they've burned (up to +100%) |

### Swamp Napalm
Blueprints from the Sewer Kings; crafted with Napalm Amber (Fungal Bog).

| Slot | Rank | Part | Lane | Effect |
|---|---|---|---|---|
| Fuel Line | I | Bog Feed | Gusher | +30% Napalm tank capacity and +1 Napalm regen/s; Napalm stacks +15% damage |
| Fuel Line | II | Jelly Artery | Capillary | 15% of Napalm units cost no fuel, and its tank refills at a quarter speed while it fires; Napalm stacks +20% damage |
| Fuel Line | III | Swamp-King Aorta | Spool-Up Coil | Napalm kills refill 3 units, an empty Napalm tank refills 40% at once (every 20 s), and the first 60 Napalm units from a full tank deal +40%; Napalm stacks +30% damage |
| Nozzle | I | Bog Spout | Lance | Every Napalm hit also coats 1 nearby mutant |
| Nozzle | II | Jelly Maw | Fan | When a mutant burning with Napalm dies, its burn jumps to 2 nearby mutants (a quarter of its stacks) |
| Nozzle | III | Swamp-King Throat | Bloom | STICKY RAIN: Napalm kills leave a burning puddle (1 stack a tick for 2 s, 70 px); Napalm stacks +40% outside the cone |
| Tank Chassis | I | Bog Cradle | Rack | +45% Napalm tank capacity |
| Tank Chassis | II | Jelly Rack | Saddle Tank | The Napalm tank refills 50% faster |
| Tank Chassis | III | Swamp-King Altar | Carousel | The first 80 Napalm units from a full tank deal +100%, and its tank refills twice as fast while another fires |
| Pump | I | Bog Plunger | Booster | Napalm stacks +15% damage |
| Pump | II | Jelly Bellows | Siphon | Napalm stacks +40% damage while the gun is above 50% heat |
| Pump | III | Swamp-King Heart | Accumulator | Swapping to Napalm fires +100% flow for 2 s; Napalm stacks +50% damage |
| Igniter | I | Bog Wick | Smoulder | Napalm burns 25% longer, and Napalm stacks +20% damage while the gun is above 50% heat |
| Igniter | II | Jelly Striker | Flash | Burning Napalm kills explode for 2 stacks (80 px) |
| Igniter | III | Swamp-King Crown | Stoker | FROST NAPALM: Napalm runs cold (no heat) and mutants burning with it slow 15% |
| Filter | I | Bog Strainer | Distiller | Napalm +25% vs shields and armor |
| Filter | II | Jelly Sieve | Catalyst | Napalm deals at least x1.0 against health, shields and armor, and +25% vs health |
| Filter | III | Swamp-King Kidney | Coarse Mesh | Napalm stacks +40% damage, and mutants burning with it die at once under 8% health |
| Shroud & Grip | I | Bog Mitt | Heatsink | Napalm runs 25% cooler, and mutants burning with it slow 6% |
| Shroud & Grip | II | Jelly Mantle | Insulated | Napalm runs 40% cooler, and mutants burning with it slow 10% |
| Shroud & Grip | III | Swamp-King Shroud | Vent Cowl | Napalm runs 80% cooler, and mutants burning with it slow 20% |
| Tank Mod | I | Bog Jug | Jerrycan | Napalm kills drop +20% raw meat |
| Tank Mod | II | Jelly Keg | Drip Bottle | Elites take +45% from Napalm, and the first Napalm unit to hit an elite each second applies 3 stacks |
| Tank Mod | III | Swamp-King Reliquary | Primer Cell | A mutant carrying 100+ Napalm stacks takes +50% from every burn, and Napalm stacks deal +1% for every second they've burned (up to +100%) |

### Thermite Slurry
Blueprints from the Rust Barons; crafted with Slag Heart (Smelter Pits).

| Slot | Rank | Part | Lane | Effect |
|---|---|---|---|---|
| Fuel Line | I | Slag Feed | Gusher | +30% Thermite tank capacity and +1 Thermite regen/s; Thermite stacks +15% damage |
| Fuel Line | II | Crucible Artery | Capillary | 15% of Thermite units cost no fuel, and its tank refills at a quarter speed while it fires; Thermite stacks +20% damage |
| Fuel Line | III | Forge-Heart Aorta | Spool-Up Coil | Thermite kills refill 3 units, an empty Thermite tank refills 40% at once (every 20 s), and the first 60 Thermite units from a full tank deal +40%; Thermite stacks +30% damage |
| Nozzle | I | Slag Spout | Lance | Every Thermite hit also coats 1 nearby mutant |
| Nozzle | II | Crucible Maw | Fan | When a mutant burning with Thermite dies, its burn jumps to 2 nearby mutants (a quarter of its stacks) |
| Nozzle | III | Forge-Heart Throat | Bloom | Thermite stacks deal +50% on mutants outside the cone and +30% beyond 300 px |
| Tank Chassis | I | Slag Cradle | Rack | +45% Thermite tank capacity |
| Tank Chassis | II | Crucible Rack | Saddle Tank | The Thermite tank refills 50% faster |
| Tank Chassis | III | Forge-Heart Altar | Carousel | The first 80 Thermite units from a full tank deal +100%, and its tank refills twice as fast while another fires |
| Pump | I | Slag Plunger | Booster | Thermite stacks +15% damage |
| Pump | II | Crucible Bellows | Siphon | Thermite stacks +40% damage while the gun is above 50% heat |
| Pump | III | Forge-Heart Heart | Accumulator | Swapping to Thermite fires +100% flow for 2 s; Thermite stacks +50% damage |
| Igniter | I | Slag Wick | Smoulder | Thermite burns 25% longer, and Thermite stacks +10% damage while the gun is above 50% heat |
| Igniter | II | Crucible Striker | Flash | Burning Thermite kills explode for 2 stacks (80 px) |
| Igniter | III | Forge-Heart Crown | Stoker | MOLTEN SLAG: Thermite kills leave a burning pool (2 stacks a tick for 1.5 s, 60 px); Thermite +30% vs armor |
| Filter | I | Slag Strainer | Distiller | Thermite +25% vs shields and armor |
| Filter | II | Crucible Sieve | Catalyst | Thermite deals at least x1.0 against health, shields and armor, and +25% vs health |
| Filter | III | Forge-Heart Kidney | Coarse Mesh | SLAG CUTTER: Thermite +60% vs shields and armor, and mutants burning with it die at once under 10% health |
| Shroud & Grip | I | Slag Mitt | Heatsink | Thermite runs 25% cooler, and mutants burning with it slow 6% |
| Shroud & Grip | II | Crucible Mantle | Insulated | Thermite runs 40% cooler, and mutants burning with it slow 10% |
| Shroud & Grip | III | Forge-Heart Shroud | Vent Cowl | Thermite runs 80% cooler, and mutants burning with it slow 20% |
| Tank Mod | I | Slag Jug | Jerrycan | Thermite kills drop +20% raw meat |
| Tank Mod | II | Crucible Keg | Drip Bottle | Elites take +45% from Thermite, and the first Thermite unit to hit an elite each second applies 3 stacks |
| Tank Mod | III | Forge-Heart Reliquary | Primer Cell | A mutant carrying 100+ Thermite stacks takes +50% from every burn, and Thermite stacks deal +1% for every second they've burned (up to +100%) |

### Ion Gel
Blueprints from the Glow Cult; crafted with Ion Crystal (Static Fields).

| Slot | Rank | Part | Lane | Effect |
|---|---|---|---|---|
| Fuel Line | I | Static Feed | Gusher | +30% Ion Gel tank capacity and +1 Ion Gel regen/s; Ion Gel stacks +15% damage |
| Fuel Line | II | Capacitor Artery | Capillary | 15% of Ion Gel units cost no fuel, and its tank refills at a quarter speed while it fires; Ion Gel stacks +20% damage |
| Fuel Line | III | Storm Aorta | Spool-Up Coil | Ion Gel kills refill 3 units, an empty Ion Gel tank refills 40% at once (every 20 s), and the first 60 Ion Gel units from a full tank deal +40%; Ion Gel stacks +30% damage |
| Nozzle | I | Static Spout | Lance | Every Ion Gel hit also coats 1 nearby mutant |
| Nozzle | II | Capacitor Maw | Fan | When a mutant burning with Ion Gel dies, its burn jumps to 2 nearby mutants (a quarter of its stacks) |
| Nozzle | III | Storm Throat | Bloom | Ion Gel stacks deal +50% on mutants outside the cone and +30% beyond 300 px |
| Tank Chassis | I | Static Cradle | Rack | +45% Ion Gel tank capacity |
| Tank Chassis | II | Capacitor Rack | Saddle Tank | The Ion Gel tank refills 50% faster |
| Tank Chassis | III | Storm Altar | Carousel | The first 80 Ion Gel units from a full tank deal +100%, and its tank refills twice as fast while another fires |
| Pump | I | Static Plunger | Booster | Ion Gel stacks +15% damage |
| Pump | II | Capacitor Bellows | Siphon | Ion Gel stacks +40% damage while the gun is above 50% heat |
| Pump | III | Storm Heart | Accumulator | Swapping to Ion Gel fires +100% flow for 2 s; Ion Gel stacks +50% damage |
| Igniter | I | Static Wick | Smoulder | Ion Gel burns 25% longer, and Ion Gel stacks +20% damage while the gun is above 50% heat |
| Igniter | II | Capacitor Striker | Flash | Burning Ion Gel kills explode for 2 stacks (80 px) |
| Igniter | III | Storm Crown | Stoker | ARC GEL: every Ion Gel hit chains to 3 nearby mutants, and breaking a shield stuns for 1 s; Ion Gel stacks +40% damage |
| Filter | I | Static Strainer | Distiller | Ion Gel +25% vs shields and armor |
| Filter | II | Capacitor Sieve | Catalyst | Ion Gel deals at least x1.0 against health, shields and armor, and +25% vs health |
| Filter | III | Storm Kidney | Coarse Mesh | OVERLOAD: Ion Gel +80% vs shields, and breaking a shield stuns for 1.5 s |
| Shroud & Grip | I | Static Mitt | Heatsink | Ion Gel runs 25% cooler, and mutants burning with it slow 6% |
| Shroud & Grip | II | Capacitor Mantle | Insulated | Ion Gel runs 40% cooler, and mutants burning with it slow 10% |
| Shroud & Grip | III | Storm Shroud | Vent Cowl | Ion Gel runs 80% cooler, and mutants burning with it slow 20% |
| Tank Mod | I | Static Jug | Jerrycan | Ion Gel kills drop +20% raw meat |
| Tank Mod | II | Capacitor Keg | Drip Bottle | Elites take +45% from Ion Gel, and the first Ion Gel unit to hit an elite each second applies 3 stacks |
| Tank Mod | III | Storm Reliquary | Primer Cell | A mutant carrying 100+ Ion Gel stacks takes +50% from every burn, and Ion Gel stacks deal +1% for every second they've burned (up to +100%) |

### Rocket Hooch
Blueprints from the Rust Barons; crafted with Still Copper (Scrap Mountain).

| Slot | Rank | Part | Lane | Effect |
|---|---|---|---|---|
| Fuel Line | I | Mash Feed | Gusher | +30% Hooch tank capacity and +1 Hooch regen/s; Hooch stacks +15% damage |
| Fuel Line | II | Moonshine Artery | Capillary | 15% of Hooch units cost no fuel, and its tank refills at a quarter speed while it fires; Hooch stacks +20% damage |
| Fuel Line | III | Rocket Aorta | Spool-Up Coil | Hooch kills refill 3 units, an empty Hooch tank refills 40% at once (every 20 s), and the first 60 Hooch units from a full tank deal +40%; Hooch stacks +30% damage |
| Nozzle | I | Mash Spout | Lance | Every Hooch hit also coats 1 nearby mutant |
| Nozzle | II | Moonshine Maw | Fan | When a mutant burning with Hooch dies, its burn jumps to 2 nearby mutants (a quarter of its stacks) |
| Nozzle | III | Rocket Throat | Bloom | Hooch stacks deal +50% on mutants outside the cone and +30% beyond 300 px |
| Tank Chassis | I | Mash Cradle | Rack | +45% Hooch tank capacity |
| Tank Chassis | II | Moonshine Rack | Saddle Tank | The Hooch tank refills 50% faster |
| Tank Chassis | III | Rocket Altar | Carousel | The first 80 Hooch units from a full tank deal +100%, and its tank refills twice as fast while another fires |
| Pump | I | Mash Plunger | Booster | Hooch stacks +15% damage |
| Pump | II | Moonshine Bellows | Siphon | Hooch stacks +40% damage while the gun is above 50% heat |
| Pump | III | Rocket Heart | Accumulator | Swapping to Hooch fires +100% flow for 2 s; Hooch stacks +50% damage |
| Igniter | I | Mash Wick | Smoulder | Hooch burns 25% longer, and Hooch stacks +10% damage while the gun is above 50% heat |
| Igniter | II | Moonshine Striker | Flash | Burning Hooch kills explode for 2 stacks (80 px) |
| Igniter | III | Rocket Crown | Stoker | STILL HOT: Hooch units also apply a stack of the fuel fired before them; Hooch stacks +60% damage |
| Filter | I | Mash Strainer | Distiller | Hooch +25% vs shields and armor |
| Filter | II | Moonshine Sieve | Catalyst | Hooch deals at least x1.0 against health, shields and armor, and +25% vs health |
| Filter | III | Rocket Kidney | Coarse Mesh | Hooch stacks +40% damage, and mutants burning with it die at once under 8% health |
| Shroud & Grip | I | Mash Mitt | Heatsink | Hooch runs 25% cooler, and mutants burning with it slow 6% |
| Shroud & Grip | II | Moonshine Mantle | Insulated | Hooch runs 40% cooler, and mutants burning with it slow 10% |
| Shroud & Grip | III | Rocket Shroud | Vent Cowl | PRESSURE COOKER: with Hooch loaded, reaching 100% heat starts 3 s with no overheat damage and +50% flow, then heat drops to 0 (once per 45 s); Hooch runs 20% cooler |
| Tank Mod | I | Mash Jug | Jerrycan | Hooch kills drop +20% raw meat |
| Tank Mod | II | Moonshine Keg | Drip Bottle | Elites take +45% from Hooch, and the first Hooch unit to hit an elite each second applies 3 stacks |
| Tank Mod | III | Rocket Reliquary | Primer Cell | A mutant carrying 100+ Hooch stacks takes +50% from every burn, and Hooch stacks deal +1% for every second they've burned (up to +100%) |

### Rad Syrup
Blueprints from the Glow Cult; crafted with Isotope Seed (The Neon Strip).

| Slot | Rank | Part | Lane | Effect |
|---|---|---|---|---|
| Fuel Line | I | Glowing Feed | Gusher | +30% Rad Syrup tank capacity and +1 Rad Syrup regen/s; Rad Syrup stacks +15% damage; while Rad Syrup is loaded the gun's flow +6% |
| Fuel Line | II | Isotope Artery | Capillary | 15% of Rad Syrup units cost no fuel, and its tank refills at a quarter speed while it fires; Rad Syrup stacks +20% damage; while Rad Syrup is loaded the gun's flow +9% |
| Fuel Line | III | Half-Life Aorta | Spool-Up Coil | Rad Syrup kills refill 3 units, and an empty Rad Syrup tank refills 40% at once (every 20 s); Rad Syrup stacks +30% damage; while Rad Syrup is loaded the gun's flow +12% |
| Nozzle | I | Glowing Spout | Lance | Every Rad Syrup hit also coats 1 nearby mutant |
| Nozzle | II | Isotope Maw | Fan | When a mutant burning with Rad Syrup dies, its burn jumps to 2 nearby mutants (a quarter of its stacks) |
| Nozzle | III | Half-Life Throat | Bloom | Rad Syrup stacks deal +50% on mutants outside the cone and +30% beyond 300 px |
| Tank Chassis | I | Glowing Cradle | Rack | +45% Rad Syrup tank capacity |
| Tank Chassis | II | Isotope Rack | Saddle Tank | The Rad Syrup tank refills 50% faster |
| Tank Chassis | III | Half-Life Altar | Carousel | The first 80 Rad Syrup units from a full tank deal +100%, and its tank refills twice as fast while another fires |
| Pump | I | Glowing Plunger | Booster | Rad Syrup stacks +15% damage |
| Pump | II | Isotope Bellows | Siphon | Rad Syrup stacks +20% damage, and +25% more while the gun is above 50% heat; while Rad Syrup is loaded the gun's flow +9% |
| Pump | III | Half-Life Heart | Accumulator | Swapping to Rad Syrup fires +100% flow for 2 s; Rad Syrup stacks +50% damage |
| Igniter | I | Glowing Wick | Smoulder | Rad Syrup burns 40% longer, and its stacks deal +15% damage; while Rad Syrup is loaded the gun's flow +6% |
| Igniter | II | Isotope Striker | Flash | Burning Rad Syrup kills explode for 2 stacks (80 px) |
| Igniter | III | Half-Life Crown | Stoker | CRITICAL MASS: a mutant carrying 100+ Rad stacks takes +50% from every burn, and Rad Syrup ages 50% faster; Rad Syrup stacks +40% damage |
| Filter | I | Glowing Strainer | Distiller | Rad Syrup +25% vs shields and armor; while Rad Syrup is loaded the gun's flow +6% |
| Filter | II | Isotope Sieve | Catalyst | Rad Syrup deals at least x1.0 against health, shields and armor, and +25% vs health |
| Filter | III | Half-Life Kidney | Coarse Mesh | Rad Syrup stacks +40% damage, and mutants burning with it die at once under 8% health |
| Shroud & Grip | I | Glowing Mitt | Heatsink | Rad Syrup runs 25% cooler, and mutants burning with it slow 6% |
| Shroud & Grip | II | Isotope Mantle | Insulated | Rad Syrup runs 40% cooler, and mutants burning with it slow 10% |
| Shroud & Grip | III | Half-Life Shroud | Vent Cowl | Rad Syrup runs 80% cooler, and mutants burning with it slow 20% |
| Tank Mod | I | Glowing Jug | Jerrycan | Rad Syrup kills drop +20% raw meat |
| Tank Mod | II | Isotope Keg | Drip Bottle | Elites take +45% from Rad Syrup, and the first Rad Syrup unit to hit an elite each second applies 3 stacks |
| Tank Mod | III | Half-Life Reliquary | Primer Cell | HALF-LIFE: Rad Syrup ages 60% faster, and elites take +50% from it |

### Fryer Oil
Blueprints from the Sewer Kings; crafted with Crackling (The Food Court).

| Slot | Rank | Part | Lane | Effect |
|---|---|---|---|---|
| Fuel Line | I | Batter Feed | Gusher | +30% Fryer Oil tank capacity and +1 Fryer Oil regen/s; Fryer Oil stacks +15% damage; while Fryer Oil is loaded the gun's flow +6% |
| Fuel Line | II | Crackling Artery | Capillary | 15% of Fryer Oil units cost no fuel, and its tank refills at a quarter speed while it fires; Fryer Oil stacks +20% damage |
| Fuel Line | III | Deep-Fry Aorta | Spool-Up Coil | Fryer Oil kills refill 3 units, an empty Fryer Oil tank refills 40% at once (every 20 s), and the first 60 Fryer Oil units from a full tank deal +40% |
| Nozzle | I | Batter Spout | Lance | Every Fryer Oil hit also coats 1 nearby mutant |
| Nozzle | II | Crackling Maw | Fan | When a mutant burning with Fryer Oil dies, its burn jumps to 2 nearby mutants (a quarter of its stacks) |
| Nozzle | III | Deep-Fry Throat | Bloom | SPLATTER: Fryer Oil stacks +80% within 220 px of the muzzle |
| Tank Chassis | I | Batter Cradle | Rack | +45% Fryer Oil tank capacity |
| Tank Chassis | II | Crackling Rack | Saddle Tank | The Fryer Oil tank refills 50% faster |
| Tank Chassis | III | Deep-Fry Altar | Carousel | The first 80 Fryer Oil units from a full tank deal +100%, and its tank refills twice as fast while another fires |
| Pump | I | Batter Plunger | Booster | Fryer Oil stacks +15% damage |
| Pump | II | Crackling Bellows | Siphon | Fryer Oil stacks +40% damage while the gun is above 50% heat |
| Pump | III | Deep-Fry Heart | Accumulator | Swapping to Fryer Oil fires +100% flow for 2 s; Fryer Oil stacks +50% damage |
| Igniter | I | Batter Wick | Smoulder | Fryer Oil burns 40% longer, and its stacks deal +15% damage; while Fryer Oil is loaded the gun's flow +6% |
| Igniter | II | Crackling Striker | Flash | Burning Fryer Oil kills explode for 2 stacks (80 px) |
| Igniter | III | Deep-Fry Crown | Stoker | BATTERED: mutants within 220 px take +1.2% per stack on them (up to +70%), and Fryer Oil's fried cuts sell for +50% (not +25%); Fryer Oil stacks +30% damage |
| Filter | I | Batter Strainer | Distiller | Fryer Oil +25% vs shields and armor; while Fryer Oil is loaded the gun's flow +6% |
| Filter | II | Crackling Sieve | Catalyst | Fryer Oil deals at least x1.0 against health, shields and armor, and +25% vs health |
| Filter | III | Deep-Fry Kidney | Coarse Mesh | Fryer Oil stacks +40% damage, and mutants burning with it die at once under 8% health |
| Shroud & Grip | I | Batter Mitt | Heatsink | Fryer Oil runs 25% cooler, and mutants burning with it slow 6% |
| Shroud & Grip | II | Crackling Mantle | Insulated | Fryer Oil runs 40% cooler, and mutants burning with it slow 10% |
| Shroud & Grip | III | Deep-Fry Shroud | Vent Cowl | Fryer Oil runs 80% cooler, and mutants burning with it slow 20% |
| Tank Mod | I | Batter Jug | Jerrycan | Fryer Oil kills drop +20% raw meat |
| Tank Mod | II | Crackling Keg | Drip Bottle | Elites take +45% from Fryer Oil, and the first Fryer Oil unit to hit an elite each second applies 3 stacks |
| Tank Mod | III | Deep-Fry Reliquary | Primer Cell | A mutant carrying 100+ Fryer Oil stacks takes +50% from every burn, and Fryer Oil stacks deal +1% for every second they've burned (up to +100%) |

## Fuels and stills

Each fuel comes from its own **still** in the Production yard. Rendered Lard's still is there from the start; the others need a **blueprint**: reach the threat shown at that destination, then get out alive.

| Fuel | Still | Blueprint | Damage | vs health / shields / armor | Burn | Heat | Rule |  |
|---|---|---|---|---|---|---|---|---|
| Rendered Lard | Rendering Kettle | from the start | 1 | ×1 / ×0.5 / ×0.5 | ×1 | ×0.6 | - | Rendered from... best not to ask. Sticks to flesh, slides off metal. |
| Swamp Napalm | Bog-Gas Fermenter | Sewer Delta, threat 4 | 1 | ×1.35 / ×0.4 / ×0.5 | ×1.6 | ×0.8 | - | Gelled bog-gas. Burns forever, mostly on meat. |
| Thermite Slurry | Crucible Furnace | Rust Flats, threat 4 | 1 | ×0.7 / ×0.6 / ×2 | ×0.8 | ×1.2 | - | Eats through scrap plating like it owes money. |
| Ion Gel | Capacitor Stack | Glow Crater, threat 4 | 1 | ×0.7 / ×2.2 / ×0.6 | ×0.9 | ×1 | - | Crackling blue goop. Pops rad-shields like soap bubbles. |
| Rocket Hooch | Copper Moonshine Still | The Junk Bazaar, threat 8 | 1.4 | ×1.1 / ×1.1 / ×1.1 | ×0.6 | ×1.5 | - | Triple-distilled. Do not drink. Okay, maybe a sip. |
| Rad Syrup | Glow Vat | Reactor Row, threat 12 | 0.18 | ×1 / ×1 / ×0.8 | ×1.4 | ×0.7 | each stack deals +12% more for every second it has burned (up to +80%) | Sweet, sticky and glowing. The longer it clings, the worse it gets. |
| Fryer Oil | Deep-Fry Drum | The Flesh Farms, threat 12 | 0.85 | ×1.2 / ×0.5 / ×0.6 | ×0.8 | ×1.3 | its kills drop cuts already fried: they skip the smoker and sell for +25% | Ten thousand batches deep. Whatever it kills comes out crispy. |

Damage is per stack per tick; burn multiplies the 3 s a stack lasts; heat multiplies the heat each unit makes.

### Stills
- The yard has 8 still plots; 2 are open at the start and the rest open in pairs:

|  | Opens | Cost |
|---|---|---|
| Expansion 1 | plots 3 and 4 | ◆400 + 15 Scrap Metal |
| Expansion 2 | plots 5 and 6 | ◆2,000 + 50 Scrap Metal + 25 Chemicals |
| Expansion 3 | plots 7 and 8 | ◆7,000 + 140 Scrap Metal + 70 Chemicals + 70 Mutant Bits |
- **Still level** (up to 10): +1.5 fuel regen a second each. **Tank level** (up to 10): +25% tank capacity each. Both cost ◆ (rising each level) and materials.
- **Attachments:** each still has 4 sub-slots (2 regen, 2 tuning) that open at still levels 1 to 4. An attachment only affects that still's fuel, levels up to 5, and swapping one resets that slot to level 1.

| Attachment | Sub-slot | Effect |
|---|---|---|
| Drip Feeder | regen | +1.0 fuel regen/s per level |
| Potency Mixer | tuning | +8% stack damage per level |
| Gel Thickener | tuning | +10% burn duration per level |
| Breaker Catalyst | tuning | +10% vs shields and armor per level |
| Cool Runner | tuning | -8% heat per level |

## Mutants

Pools below are at threat 0; they grow with the destination's rates and the difficulty curve every level. Elites have ×3.

| Mutant | Health | Shields | Armor | Speed | Shows up from | Meat | Drops | Common at |
|---|---|---|---|---|---|---|---|---|
| Shambler | 16 | - | - | 46 | threat 0 | Shambler Shank | Mutant Bits | Dead Drive-In, The Flesh Farms, Fungal Bog |
| Skitter | 6 | - | - | 105 | threat 1 | Skitter Drumettes | Mutant Bits | The Junk Bazaar, The Food Court, Scrap Mountain, The Neon Strip, Sewer Delta |
| Glowbag | 12 | 18 | - | 40 | threat 2 | Glowbag Belly | Chemicals | Dead Drive-In, Smelter Pits, Glow Crater, Reactor Row, The Neon Strip, Static Fields, Fungal Bog |
| Scrapper | 14 | - | 28 | 34 | threat 3 | Scrapper Ribs | Scrap Metal | The Junk Bazaar, Rust Flats, Scrap Mountain, Tank Graveyard, Smelter Pits, Reactor Row, Bloat Marsh |
| Tumor Hulk | 104 | - | 32 | 24 | threat 6 | Hulk Brisket | Scrap Metal, Mutant Bits | The Food Court, Tank Graveyard, Static Fields, Sewer Delta, The Flesh Farms, Bloat Marsh |

- A destination's favourite mutants show up 2 threat levels early and more often.
- Shields and armor come off before health, so fuels and parts that break shells (vs shields, vs armor) matter more as those pools grow.

## Destinations and factions

### Destinations
Sixteen places in four themes, four places each (since v0.8.0). A theme's places grow their mutants at the same rates (the same difficulty), with a different mix of mutants each; every place but the Outskirts is the turf of its own faction, and the new ones open one after another with the reputation of the place before. Each set has one home, each still blueprint and each exotic material drops at one place.

- **Balanced** (Health, armor and shields grow alike): Smokehouse Outskirts, The Junk Bazaar, Dead Drive-In, The Food Court
- **Armor** (Armor grows fastest: bring something that melts plates): Rust Flats, Scrap Mountain, Tank Graveyard, Smelter Pits
- **Shield** (Shields grow fastest: bring something that pops them): Glow Crater, Reactor Row, The Neon Strip, Static Fields
- **Health** (Raw health grows fastest: big meaty mutants): Sewer Delta, The Flesh Farms, Fungal Bog, Bloat Marsh

#### Smokehouse Outskirts
Home turf. Balanced mutants, a neutral market that pays a flat 0.9x.
- **Unlock:** open from the start. **Market:** neutral (a flat ×0.9 for any sauce, no reputation).
- **Theme:** Balanced. **Growth a level:** health ×1.17, armor ×1.17, shields ×1.17.
- **Sets:** Grease Fire. **Still blueprints:** none. **Exotic material:** none.

#### The Junk Bazaar
Bazaar Hagglers turf. A swap meet under tarps; skitters steal from the stalls.
- **Unlock:** opens at best threat 6. **Market:** Bazaar Hagglers turf.
- **Theme:** Balanced. **Growth a level:** health ×1.17, armor ×1.17, shields ×1.17.
- **Common mutants:** Skitter, Scrapper. **Extra drops:** none.
- **Sets:** Thrift Shop. **Still blueprints:** Copper Moonshine Still (threat 8). **Exotic material:** none.

#### Dead Drive-In
Reel Cult turf. The last film still loops; shamblers shuffle in for the late show.
- **Unlock:** needs Bazaar Hagglers reputation 1. **Market:** Reel Cult turf.
- **Theme:** Balanced. **Growth a level:** health ×1.17, armor ×1.17, shields ×1.17.
- **Common mutants:** Shambler, Glowbag. **Extra drops:** none.
- **Sets:** Moonshine Run. **Still blueprints:** none. **Exotic material:** none.

#### The Food Court
Mallrat Gangs turf. A gutted mall; hulks nest in the fry pits.
- **Unlock:** needs Reel Cult reputation 1. **Market:** Mallrat Gangs turf.
- **Theme:** Balanced. **Growth a level:** health ×1.17, armor ×1.17, shields ×1.17.
- **Common mutants:** Tumor Hulk, Skitter. **Extra drops:** none.
- **Sets:** Cocktail Hour. **Still blueprints:** none. **Exotic material:** Crackling (threat 10).

#### Rust Flats
Rust Barons turf. Armor piles up fast; Scrapper country. Their scrap comes out of the furnace Molten.
- **Unlock:** opens at best threat 3. **Market:** Rust Barons turf.
- **Theme:** Armor. **Growth a level:** health ×1.12, armor ×1.28, shields ×1.1.
- **Common mutants:** Scrapper. **Extra drops:** Scrap Metal ×2.
- **Sets:** Foundry Rig. **Still blueprints:** Crucible Furnace (threat 4). **Exotic material:** none.

#### Scrap Mountain
Tin Monks turf. A peak of crushed cars; scrappers and skitters climb it in swarms.
- **Unlock:** needs Rust Barons reputation 2. **Market:** Tin Monks turf.
- **Theme:** Armor. **Growth a level:** health ×1.12, armor ×1.28, shields ×1.1.
- **Common mutants:** Scrapper, Skitter. **Extra drops:** Scrap Metal ×2.
- **Sets:** Bandolier. **Still blueprints:** none. **Exotic material:** Still Copper (threat 10).

#### Tank Graveyard
Ironsides turf. Rusted tanks in rows; hulks wear the turrets.
- **Unlock:** needs Tin Monks reputation 1. **Market:** The Ironsides turf.
- **Theme:** Armor. **Growth a level:** health ×1.12, armor ×1.28, shields ×1.1.
- **Common mutants:** Scrapper, Tumor Hulk. **Extra drops:** Scrap Metal ×2.
- **Sets:** Pit Boss. **Still blueprints:** none. **Exotic material:** none.

#### Smelter Pits
Slag Brothers turf. Open furnaces; the scrappers come out glowing hot.
- **Unlock:** needs The Ironsides reputation 1. **Market:** Slag Brothers turf.
- **Theme:** Armor. **Growth a level:** health ×1.12, armor ×1.28, shields ×1.1.
- **Common mutants:** Scrapper, Glowbag. **Extra drops:** Scrap Metal ×2.
- **Sets:** Boiler Room. **Still blueprints:** none. **Exotic material:** Slag Heart (threat 10).

#### Glow Crater
Glow Cult turf. Shields everywhere; bring Ion Gel.
- **Unlock:** needs the truck's engine at level 1. **Market:** Glow Cult turf.
- **Theme:** Shield. **Growth a level:** health ×1.18, armor ×1.1, shields ×1.24.
- **Common mutants:** Glowbag. **Extra drops:** Chemicals ×2.
- **Sets:** Tesla Coilworks. **Still blueprints:** Capacitor Stack (threat 4). **Exotic material:** none.

#### Reactor Row
Reactor Choir turf. Cooling towers hum hymns; glowbags drift between them.
- **Unlock:** needs Glow Cult reputation 1. **Market:** Reactor Choir turf.
- **Theme:** Shield. **Growth a level:** health ×1.18, armor ×1.1, shields ×1.24.
- **Common mutants:** Glowbag, Scrapper. **Extra drops:** Chemicals ×2.
- **Sets:** Meltdown. **Still blueprints:** Glow Vat (threat 12). **Exotic material:** none.

#### The Neon Strip
Neon Saints turf. Casino signs that never went dark; skitters under every one.
- **Unlock:** needs Reactor Choir reputation 1. **Market:** Neon Saints turf.
- **Theme:** Shield. **Growth a level:** health ×1.18, armor ×1.1, shields ×1.24.
- **Common mutants:** Glowbag, Skitter. **Extra drops:** Chemicals ×2.
- **Sets:** Steeple Works. **Still blueprints:** none. **Exotic material:** Isotope Seed (threat 10).

#### Static Fields
Storm Callers turf. Lightning rods to the horizon; shielded hulks walk through the strikes.
- **Unlock:** needs Neon Saints reputation 1. **Market:** Storm Callers turf.
- **Theme:** Shield. **Growth a level:** health ×1.18, armor ×1.1, shields ×1.24.
- **Common mutants:** Glowbag, Tumor Hulk. **Extra drops:** Chemicals ×2.
- **Sets:** none of its own. **Still blueprints:** none. **Exotic material:** Ion Crystal (threat 10).

#### Sewer Delta
Sewer Kings turf. Meat-heavy mutants grow huge.
- **Unlock:** needs Rust Barons reputation 1. **Market:** Sewer Kings turf.
- **Theme:** Health. **Growth a level:** health ×1.2, armor ×1.12, shields ×1.1.
- **Common mutants:** Tumor Hulk, Skitter. **Extra drops:** Mutant Bits ×2.
- **Sets:** Glacier Works. **Still blueprints:** Bog-Gas Fermenter (threat 4). **Exotic material:** none.

#### The Flesh Farms
Meat Ranchers turf. Pens of mutant cattle that got loose; the hulks are the bulls.
- **Unlock:** needs Sewer Kings reputation 1. **Market:** Meat Ranchers turf.
- **Theme:** Health. **Growth a level:** health ×1.2, armor ×1.12, shields ×1.1.
- **Common mutants:** Tumor Hulk, Shambler. **Extra drops:** Mutant Bits ×2.
- **Sets:** Deep Fryer. **Still blueprints:** Deep-Fry Drum (threat 12). **Exotic material:** none.

#### Fungal Bog
Spore Mothers turf. Knee-deep mushrooms; shamblers sprout from the mud.
- **Unlock:** needs Meat Ranchers reputation 1. **Market:** Spore Mothers turf.
- **Theme:** Health. **Growth a level:** health ×1.2, armor ×1.12, shields ×1.1.
- **Common mutants:** Shambler, Glowbag. **Extra drops:** Mutant Bits ×2.
- **Sets:** Slow Cooker. **Still blueprints:** none. **Exotic material:** Napalm Amber (threat 10).

#### Bloat Marsh
Gluttons' Court turf. A swamp of rendered fat; the biggest hulks wallow here.
- **Unlock:** needs Spore Mothers reputation 1. **Market:** Gluttons' Court turf.
- **Theme:** Health. **Growth a level:** health ×1.2, armor ×1.12, shields ×1.1.
- **Common mutants:** Tumor Hulk, Scrapper. **Extra drops:** Mutant Bits ×2.
- **Sets:** none of its own. **Still blueprints:** none. **Exotic material:** Tallow Brick (threat 10).

### Factions
Each faction owns a destination's market. They like a taste (spicy / sweet / savory, 0 to 5), pay ×1.25 for their favourite cut, and reward reputation. Reputation comes only from selling them a sauce that fits better than ×1; it doesn't raise prices, it unlocks things.

| Faction | Who | Turf | Ideal taste | Favourite cut | Reputation rewards |
|---|---|---|---|---|---|
| Bazaar Hagglers | Swap-meet traders | The Junk Bazaar | 3 / 3 / 2 | Shambler Shank | 1: Shows you the way to the Dead Drive-In<br>2: Recipe: Haggler's Hash Rub<br>3: Sells Marrow Butter<br>4: Thrift Shop blueprints |
| Reel Cult | Film-loop preachers | Dead Drive-In | 1 / 4 / 3 | Skitter Drumettes | 1: Shows you the way to the Food Court<br>2: Recipe: Buttered Popcorn Glaze<br>3: Sells Glowberry Syrup<br>4: Moonshine Run blueprints |
| Mallrat Gangs | Escalator raiders | The Food Court | 3 / 2 / 4 | Glowbag Belly | 1: Recipe: Food Court Teriyaki<br>2: Sells Ghost Chili Paste<br>3: Sells Glowberry Syrup<br>4: Cocktail Hour blueprints |
| Rust Barons | Scrap warlords | Rust Flats | 4 / 1 / 3 | Scrapper Ribs | 1: Shows you the road into the Sewer Delta<br>2: Recipe: Baron's Brimstone Rub<br>3: Sells Glowberry Syrup (the Glow Cult loves it)<br>4: Foundry Rig blueprints |
| Tin Monks | Junk-welding hermits | Scrap Mountain | 3 / 1 / 4 | Scrapper Ribs | 1: Shows you the way to the Tank Graveyard<br>2: Recipe: Solder Salt Rub<br>3: Sells Marrow Butter<br>4: Bandolier blueprints |
| The Ironsides | Tread-riding road warriors | Tank Graveyard | 5 / 1 / 2 | Hulk Brisket | 1: Shows you the way to the Smelter Pits<br>2: Recipe: Diesel Pepper Dust<br>3: Sells Ghost Chili Paste<br>4: Pit Boss blueprints |
| Slag Brothers | Furnace-stoking cultists | Smelter Pits | 4 / 2 / 3 | Scrapper Ribs | 1: Recipe: Slag Sear<br>2: Sells Ghost Chili Paste<br>3: Sells Marrow Butter<br>4: Boiler Room blueprints |
| Glow Cult | Radioactive zealots | Glow Crater | 1 / 4 / 2 | Glowbag Belly | 1: Recipe: Halo Honey Glaze<br>2: Sells Marrow Butter (the Sewer Kings love it)<br>3: Tesla Coilworks blueprints<br>4: Hellmouth blueprints |
| Reactor Choir | Hymn-singing technicians | Reactor Row | 1 / 5 / 1 | Glowbag Belly | 1: Shows you the way to the Neon Strip<br>2: Recipe: Hymnal Honey<br>3: Sells Glowberry Syrup<br>4: Meltdown blueprints |
| Neon Saints | Casino ghouls | The Neon Strip | 2 / 4 / 3 | Skitter Drumettes | 1: Shows you the way to the Static Fields<br>2: Recipe: Neon Candy Glaze<br>3: Sells Glowberry Syrup<br>4: Steeple blueprints |
| Storm Callers | Lightning-rod nomads | Static Fields | 4 / 3 / 1 | Shambler Shank | 1: Recipe: Ozone Rub<br>2: Sells Ghost Chili Paste<br>3: Sells Glowberry Syrup<br>4: Tesla Coilworks blueprints |
| Sewer Kings | Underground mutant royalty | Sewer Delta | 2 / 1 / 5 | Hulk Brisket | 1: Recipe: Royal Marrow Gravy<br>2: Sells Ghost Chili Paste (the Rust Barons love it)<br>3: Glacier Works blueprints<br>4: Grease Fire blueprints |
| Meat Ranchers | Mutant cattle barons | The Flesh Farms | 2 / 2 / 5 | Hulk Brisket | 1: Shows you the way to the Fungal Bog<br>2: Recipe: Rancher's Red-Eye Gravy<br>3: Sells Marrow Butter<br>4: Deep Fryer blueprints |
| Spore Mothers | Mushroom matriarchs | Fungal Bog | 1 / 3 / 4 | Shambler Shank | 1: Shows you the way to Bloat Marsh<br>2: Recipe: Spore Butter Baste<br>3: Sells Marrow Butter<br>4: Slow Cooker blueprints |
| Gluttons' Court | Swollen swamp nobles | Bloat Marsh | 3 / 4 / 3 | Hulk Brisket | 1: Recipe: Gluttony Glaze<br>2: Sells Glowberry Syrup<br>3: Sells Marrow Butter<br>4: Grease Fire blueprints |

Reputation levels 1 to 4 need 20, 60, 150, 400 points. Three things earn it:
- **Fighting on their turf:** getting out of a run at a faction's destination earns 0.03 for every mutant killed there (an elite counts 3; an ordinary mutant counts for the ones it stands in for, see Runs). A threat-16 run brings home about 84.
- **The crew:** a cat's trip there earns 50% of the same.
- **Selling there:** a cut sold earns 2 × (fit - 1) points when the fit is over ×1.
- Every point also earns a point of **favor** with that faction, to spend on exotic blueprints (see Exotic parts) without losing reputation.

## Meat, sauce and selling

### Cuts

| Cut | From | Base value | Favourite of |
|---|---|---|---|
| Skitter Drumettes | Skitter | ◆2 | Reel Cult, Neon Saints |
| Shambler Shank | Shambler | ◆4 | Bazaar Hagglers, Storm Callers, Spore Mothers |
| Glowbag Belly | Glowbag | ◆6 | Mallrat Gangs, Glow Cult, Reactor Choir |
| Scrapper Ribs | Scrapper | ◆7 | Rust Barons, Tin Monks, Slag Brothers |
| Hulk Brisket | Tumor Hulk | ◆18 | The Ironsides, Sewer Kings, Meat Ranchers, Gluttons' Court |

- A cut's value is its base × (1 + 0.45 × the threat level it dropped at) (+15% per heat-dial level).
- **Raw meat spoils:** it loses 10% of its value an hour, down to 20%. Each Freezer level halves that. Sauce it to stop the clock.
- The **Shoggoth Hatch** takes every raw cut at ×0.05 of its value: a dump for leftovers, not a business.

### The chef cat
- **Production > Kitchen > CHEF** hires a chef cat to run the kitchen. No fee up front: it takes **6% of every meat sale** for as long as it works there, and you can let it go any time.
- Whenever a pot is free and there's more raw meat than sauce on the way, it brews the best sauce it can from the recipes and ingredients you have, with the taste dials set as close as your dial upgrades reach, for the faction your smoker target names (or where the truck is parked). It sauces raw meat as sauces finish, the best-fitting sauce and the most valuable cuts first.
- It works on real time like the rest of the kitchen: while you fight and while the game is closed. You can still brew by hand.

### Sauce
- **Brew** (Production > Kitchen): pick a recipe, fill its ingredient slots (one of each slotted ingredient per batch) and set the taste dials. A batch makes **60 portions** and takes 3 minutes (faster with Kitchen levels, which also add pots). One portion sauces one cut.
- A sauce's taste = the recipe's base + its ingredients, then the dials (the Spice Rack, Sugar Press and Stock Pot let you nudge each taste by 1 more per level). Each taste caps at 5 (Flavor Overdrive raises the cap for extreme fads).

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
- Between runs (and with the game closed) it smokes at 50% that speed, a batch at a time, loading itself from your sauced meat (the cuts worth most to the faction you sell to first).

### Faction contracts (v0.8.2)
- Every faction whose turf is open and whose reputation with you is level 1 or more posts one order at a time (Kitchen, **DEALS**): its favourite cut, sauced or smoked (not overcooked) with its strongest taste at its ideal minus one or more, some of one common ingredient, and a fee. Sizes grow with your best threat T (up to 30): 30 + 4 × T cuts, 10 + 2 × T of the ingredient (no more than your Pantry holds), ◆200 × T^1.5.
- **DELIVER** pays 1 + T/10 **Flux** (for tempering past +5) and 20 + 2 × T reputation (and with it favor). The next order comes 4 hours later. **NEW ORDER NOW** swaps the order for another for 20 of that faction's favor.

### Feasts (v0.8.2)

| Feast | Cut | Ingredients | For the next run |
|---|---|---|---|
| Firebelly Chili | Scrapper Ribs | Rad Pepper + Rust Salt | +10% stack damage for the run |
| Hulk Roast | Hulk Brisket | Bone Marrow + Mushroom Mash | +25% armor for the run |
| Frosted Shanks | Shambler Shank | Glow Honey + Rust Salt | 15% less heat for the run |
| Glowbag Pie | Glowbag Belly | Glow Honey + Sludge Molasses | +50% reputation from the run |

- Cooked in the Kitchen (**FEAST**) from 20 + 2 × T cuts of its kind (raw, sauced or smoked), 5 + T/2 of each ingredient and ◆50 × T^1.5 (T: your best threat, up to 30). The next run eats it (not the Gauntlet). **EVERY RUN** (AUTOMATION > KITCHEN) cooks the one you pick before each run, yours and the 8-Ball's, whenever you have what it takes.

### Selling
- Park the truck on a destination (Map tab) to sell to its faction. The counter sells one cut every 10 s, 50% faster per Serving Counter level, in real time, also while you fight or the game is closed.
- **Glut:** when more cooked meat waits than the counter sells in 10 minutes, the crew sells fast enough to bring it down to that in 10 minutes, at a discount: (normal speed / glut speed) ^ 0.7 a cut, so twice as fast sells at ×0.62. Meat never piles up for long.
- **Price of a cut** = its value × the sauce's value × **fit** × favourite cut (×1.25) × (1 - fatigue).
- **Fit** runs from ×1.5 (the sauce's taste sits right on the faction's ideal) down to ×0.6 (6 or more taste points away, counted straight-line across the three tastes). The neutral Outskirts market pays a flat ×0.9 and gives no reputation.
- **Fatigue:** each cut sold adds 1% to that faction's fatigue for the sauce's strongest taste, up to 30%; it wears off at 20% an hour. Rotating sauces pays a little; volume still wins.
- **Fads:** every 4 hours a new fad shifts one of a faction's tastes up or down by 2 for 12 hours. The Map shows today's tastes.

## The Smokehouse

The hub between runs. Tabs: **Loadout**, **Craft**, **Refine**, **Production**, **Map**, **Crew**; the cat counter is always on the right. **HIDE MAP** in Production folds the yard picture into a short list of the buildings and widens the panel.

### Loadout
- The seven part slots, a tank mod for each mounted tank, the fuel in each tank, and armor. The preview pig rebuilds as you swap.
- **Loadouts:** save the gun under a name and put it back on later; copy or import a build code to share one. Every 8-Ball order keeps one of its own, **ORDER: <NAME>**, kept up to date with the best you own for it (v0.8.8).
- **Stash:** filter by worn, unworn, locked, tier, slot or lane. **Lock** a part to protect it (**Space** locks or unlocks the selected part, here and in the Refine tab). **Scrap** a part (or SCRAP SHOWN for everything the filters show, or SCRAP JUNK) for materials; a set piece is broken down for Blueprint Shards instead. Parts you or a cat wear, locked parts and parts in a saved loadout are never scrapped.
- **Scrapping** returns 50% of the part's crafting materials (by quality) plus 1 + 2 per tier Scrap Metal, teaches you its lane, records its affixes in the **Library**, and gives Mutagen for Mutated (1) and Malevolent (5) parts.
- **EQUIP BEST** (top left of the Loadout tab): with the Magic 8-Ball holding an order, the best you have for that ad (its keystone, its lanes highest tier first, 4 of its set's pieces, its exotic upgrade, its fuels and tank mods); otherwise the parts and tank mods that give the kit the most **power** (the estimate the crew and the Shoggoth use), keeping a keystone you wear and any set bonus you've reached, leaving your fuels alone. It never takes a part off a cat. A Showroom ad's **PUT IT ON** does the same for that ad.
- **Loot filter** (the LOOT button): choose which salvage to keep (tiers, lanes, qualities, slots, only upgrades over what you wear, behaviors; sets, Malevolent parts and keystones can always be kept). The rest is scrapped on the way home, from your runs and the crew's. SALVAGE NOW applies it to the stash.

### Craft and Refine (the Workbench)
- **CRAFT tab, PARTS:** pick a slot and a tier, then any lane you know. A part costs ◆ plus its slot's material (6, 15, 35, 80 for T1 to T4). Workbench levels raise the odds of a better quality.
- **CRAFT tab, SET BLUEPRINTS:** buy set blueprints with Shards and craft the pieces (they roll a lane at your best tier). **BENCH & LIBRARY:** Workbench upgrades, quality odds, the lane blueprints you know and the Library.
- **REFINE tab:** filter the parts on the left (worn, unworn, on the crew, locked, in a loadout, with a behavior, below Malevolent; slot, lane, tier, quality, or an affix the part carries), pick one, and refine it on the right. **REFINE THIS PART** in the Loadout tab opens it there.
  - **Quality up** one step at a time (◆ and materials; Mutated to Malevolent costs ×0.4).
  - **Reroll** one affix (◆; the second affix you touch on a part adds materials, the third Shards). Each try on the same affix costs 30% more, up to ×2.
  - **Optimize** an affix: +10% of its range toward the top, paid in the slot's material.
  - **Recalibrate** an affix into one your Library has recorded for that slot, at the recorded value (no stronger than the part's quality allows), for twice the reroll price.
  - **Mutate** the behavior (or add one at Mutated quality and up) for Mutagen: 1 (T1 and T2), 2 (T3), 4 (T4).
  - **Re-forge** a part into another lane of its slot that you know, keeping its tier, quality, affixes and behavior, for twice the tier's material and a quarter of the part's price.
  - **Temper** (v0.8.2) a Malevolent T4 part, +1 to +10: each level lifts its primary stat, its lane's benefit lines and its affix rolls (+2% for the first level, a little less each level after, ×1.16 at +10). Level n costs ◆12,000 × 1.4^(n-1), 60 × n of the slot's material, 4 × n Shards and n Mutagen, and from +6 also (n - 5) **Flux** (from faction contracts). A tempered part shows +n after its name.

### The yard and the shack

| Upgrade | Where | What it does | Max level | First level |
|---|---|---|---|---|
| Workbench | Shack | Crafted parts roll higher qualities. | 8 | ◆250 + 5 Scrap Metal |
| Sauce Kitchen | Shack | More brewing pots (1 + level/2) and faster brews. | 8 (18 with the second band) | ◆200 + 6 Mutant Bits |
| Freezer | Shack | Each level halves how fast raw meat spoils. | 5 | ◆300 + 8 Scrap Metal + 4 Chemicals |
| Pantry | Shack | +20 ingredient storage per type per level (+50 a level past 8). | 8 (18 with the second band) | ◆150 + 4 Mutant Bits |
| Storage Shed | Yard | +150 storage for each material per level (+600 a level past 8). | 8 (18 with the second band) | ◆200 + 8 Scrap Metal |
| Scrap Sifter | Yard | Sifts +6 Scrap Metal per hour per level (+18 a level past 10). | 10 (20 with the second band) | ◆300 + 6 Scrap Metal |
| Rendering Vat | Yard | Renders +6 Mutant Bits per hour per level (+18 a level past 10). | 10 (20 with the second band) | ◆300 + 6 Mutant Bits |
| Sludge Drip | Yard | Drips +6 Chemicals per hour per level (+18 a level past 10). | 10 (20 with the second band) | ◆300 + 6 Chemicals |
| Catnip Plant | Yard | Cats arrive 25% faster per level. | 10 (20 with the second band) | ◆100 + 3 Mutant Bits |
| Smoker | Garage | +40 cuts cooked per run per level. | 10 (20 with the second band) | ◆250 + 6 Scrap Metal |
| Engine | Garage | Range: reach farther destinations. | 5 | ◆500 + 20 Scrap Metal |
| Serving Counter | Garage | Parked truck sells 50% faster per level. | 10 (20 with the second band) | ◆200 + 5 Mutant Bits |
| Spice Rack | Kitchen | Lets you dial Spicy up or down by 1 more per level. | 3 | ◆300 + 5 Chemicals |
| Sugar Press | Kitchen | Lets you dial Sweet up or down by 1 more per level. | 3 | ◆300 + 5 Mutant Bits |
| Stock Pot | Kitchen | Lets you dial Savory up or down by 1 more per level. | 3 | ◆300 + 5 Scrap Metal |
| Flavor Overdrive | Kitchen | Raises the taste ceiling past 5 for extreme fads. | 2 | ◆4,000 + 40 Chemicals |
| Bigger Counter | Cats | +5 cats can wait in line per level. | 6 (16 with the second band) | ◆150 + 3 Scrap Metal |

Prices in ◆ rise with each level; materials rise a step each level.

- **The second band** (v0.8.2). The Kitchen, Pantry, Storage Shed, the three vats, the Catnip Plant, the Smoker, the Serving Counter and the Bigger Counter go 10 levels past their old top at steep prices: level max+k costs the last old level's ◆ × 2 × 1.25^(k-1), plus 60 × k of the building's material and 5 × k Shards. Each level does what the building's levels always did (the Shed adds 600 storage a level there, the Pantry 50, a vat 18 an hour). The Overseer buys them too.
- **Storage** (v0.8.2: for everything). Each material holds 150, +150 per Storage Shed level, and each ingredient 20, +20 per Pantry level. Runs, crew trips, scrapping, cats and vats all stop at these: what doesn't fit is **sold** for 0.25 Sprinkles a unit of material and 1 an ingredient (the result screen says STORAGE FULL). What you already hold past a cap is kept.

### While you're away
Brewing, the vats, spoilage, fatigue, cats, the smoker, sales and crew trips all run on real time and catch up when you come back.

## Cats and the crew

### The cat counter
- Stray cats line up at the counter, one every 20 s (25% faster per Catnip Plant level). Up to 10 wait in line, +5 per Bigger Counter level.
- **High five** the cat at the front for what it brings, or **hire** it for your crew.

| Cat | High five brings | How often | Knack on the crew |
|---|---|---|---|
| Long-haired cat | Energy Sprinkles (2 + 0.5 per best threat level) | 26% | Brings home 25% more meat |
| Short-haired cat | Scrap Metal | 16% | +50% Scrap Metal |
| Glowing cat | Chemicals | 14% | +50% Chemicals |
| Mutant cat | Mutant Bits | 14% | +50% Mutant Bits |
| Hairless cat | a sauce ingredient | 14% | Twice the sauce ingredients |
| Calico cat | a rare ingredient | 7% | 1 in 4 ingredients it finds is a rare one |
| Tuxedo cat | 1 to 2 Blueprint Shards | 5% | Finds set pieces twice as often |
| Radiant cat | 1 Mutagen | 4% | Mutagen from elites from threat 10 (not 15), twice as often |

**Lures** (bought once, one active at a time) make a group of cats show up ×3 as often:
- **Brushed Yarn** (◆250): Long-haired cats (Energy Sprinkles) show up 3x as often.
- **Laser Pointer** (◆250): Material cats (short-haired, glowing and mutant) show up 3x as often.
- **Glowing Fish** (◆250): Ingredient cats (hairless and calico) show up 3x as often.

### The crew
- Hire up to **3 cats** off the counter: ◆300, ◆2,000, ◆8,000 for the first, second and third. Its coat is its knack (table above).
- **Kit them** on the Crew tab with your spare parts and fuels: the same seven slots, tanks and tank mods. A part is worn by one fighter at a time, you or one cat. BEST FREE PARTS fills a kit from parts nobody wears.
- **Expeditions:** send a cat to an open destination at a threat up to your best, for 15 minutes, 1 hour, 4 hours, 8 hours. It fights on its own (also with the game closed) and brings home what a run would: meat, materials, ingredients, salvage (through your loot filter), set pieces and Mutagen. Longer trips bring more, but less a minute.
- The planner shows the threat the cat's kit should hold, the **odds** of a clean trip (3% to 97%) and the expected haul. A trip that goes wrong brings home 20% to 60% of the haul, and the cat rests for a while (25% of the trip, at least 10 minutes).
- **RECALL** brings a cat home early with a quarter of the haul. While it's out, its parts stay with it.
- The **chef cat** is a separate hire, in Production > Kitchen > CHEF (see Meat, sauce and selling).

### The Overseer
- A big floating eye over the Production yard (or THE OVERSEER at the top of the folded list). Click it to wake it (no fee) and it **buys Production upgrades for you**: the cheapest one you can afford first, at most one every 4 s, never touching the share of your Energy Sprinkles the hands keep back (AUTOMATION tab).
- You pick what it may buy (AUTOMATION > YARD): **stills** (building a still for a blueprint you own, still and tank levels, levels of attachments you've fitted, yard expansions; never a new attachment), **the shack**, **the yard**, **the garage**, **kitchen dials** (off at first) and **the cat counter**. Its panel shows what it buys next (or saves up for), and what it has bought and spent.
- It works while the game runs, runs included (quietly; it's in the debug log), not while the game is closed. Switch it off or close its eye any time.

## Automation: the 8-Ball and the hands

Every automation setting is on the **AUTOMATION** tab. Hands are still hired where they live: the **Magic 8-Ball** on the AUTOMATION tab (or the Map's 8-Ball line), the **chef cat** in Production > Kitchen > CHEF, the **Overseer** by clicking its eye over the yard. **High fives** stay yours.

### The Magic 8-Ball
- Hire it (no fee) and switch it on with its switch or **B** anywhere. 8 s after you're back in the Smokehouse (with no menu open) it starts a run, with the Shoggoth driving (its truck setting and each place's heat dial apply; the Shoggoth's fee too). The result screen goes back by itself after 6 s and it goes again. B in a run switches it for the runs after this one.
- It works **its list of goals**, top first. A goal that can't move now (waiting on a fee, a full Shed, an offer) is skipped and says why. Each goal shows what it does next, a progress bar and its **budget**.

### Two lists
- **The 8-Ball's list**: its runs work it. **The crew's list**: the cats' trips work it, with **CREW FARMS TOO** on (CREW). **<>** on a goal hands a goal from one list to the other. A best-threat goal can't go on the crew's list: their trips don't raise your best threat.
- **Goals:** reputation with a faction (or **every open faction** to a level: the one furthest behind first), favor, opening a map (or every map), Scrap, Bits or Chemicals, an exotic part, an exotic blueprint, faction contracts (one faction or all, so many or keep going), a best threat (one place or anywhere), Energy Sprinkles, and builds (orders from the Showroom).
- **How a goal plans:** reputation and favor are fought for on the faction's turf, and a locked turf is opened first (back along the chain of factions, or by pushing your best threat, or by buying the truck engine). Materials: the open map that yields most of them (with the Shed full, the hands build it up first; past the biggest Shed, a full Shed is as done as it gets). An exotic: the reputation and favor for its blueprint, the blueprint, its material at its home (from threat 10, where your kit holds it), then the craft. Contracts: the cut where its mutant is common (with the chef saucing for that faction), the ingredient where it's found, then the delivery. Sprinkles: meat from the deepest place the kit holds. What the hands can do without a run (buy the truck engine or a blueprint, craft the exotic, deliver a contract) they do between runs.
- **Budgets** (BUDGET on each goal, going round): until it's done (the default), 5, 10, 25 runs (trips for the crew), 15, 30, 60, 120 minutes of runs, or for a build **until every part it wears is at your top tier**. A goal whose budget is spent leaves the list.
- **When things go badly:** 2 runs in a row that don't move a goal **pause** it for 20 minutes (or until your kit's power is up 10%), and the next goal takes over. 2 deaths in a row **lower its threat by 1** (where the run starts and where the Shoggoth starts the truck) until the kit's power is up the same way; when it can't go lower the goal pauses. 2 crew trips in a row that go wrong pause a crew goal. II pauses a goal by hand; GO brings a paused one back now.
- **When a list is empty** (or every goal waits): the 8-Ball fights where reputation is **lowest**, farms the **missing exotic blueprints** (fuels you've built first, the lowest rank first; it buys them when it can), or **stops**. The crew **helps the 8-Ball** with its goal (the default), or does one of those, or **stays home**. With no goal, 2 deaths in a row lower the 8-Ball's threat too, and when it can't go lower it switches off.

### Runs
- **Where its runs start:** **YOUR DIAL** (each map's START THREAT dial), **COMFORTABLE** (5 levels under where the Shoggoth starts the truck, the default) or **PUSH** (as high as the dial may go: your best there minus 7). A best-threat goal always starts as high as it may and starts the truck at its target, or at what the kit holds there if that's lower (AUTO stops 2 under what the kit holds); when the kit holds no more than your best, the goal waits for more power. Exotic materials start no lower than threat 8.
- **The Shoggoth's settings** (your runs and the 8-Ball's): see Shoggoth Remote Control.
- With a build to farm it buys that place's **targeted-loot pick** (60 shards) for the slot the build needs most, unless that's already today's featured slot there (PICKS).
- **THE WEEKLY GAUNTLET** (off at first): its first run each week is this week's Gauntlet, once you can enter it. A Gauntlet death doesn't count against it.

### Builds
- **Orders.** Press **ORDER IT** on a Showroom ad and the 8-Ball farms for that build (it's hired for free if it wasn't). Each run it goes where the next missing piece drops, in this order: a missing fuel's still blueprint (where it drops), 4 set pieces (at the set's home), lane parts below your top tier and the keystone (at the build's home), then the exotic upgrade's faction favor (at that faction's turf) and material (where it drops). With everything in, it farms the build's home for better rolls; a place that isn't open yet is skipped. Building stills stays yours: the ad's plan marks it YOU.
- **Custom orders** (v0.8.8). **+ CUSTOM ORDER** on the Showroom tab starts a build of your own from the kit you wear; **CUSTOMIZE** on an ad starts one from that ad. Pick its set (or none), keystone (or none), a lane for every slot, the tank mods, up to 3 affixes, up to 4 fuels (the first is the signature), one exotic for any gun slot, and its home map, then **ORDER IT**: the 8-Ball farms, crafts and puts it on like any ad. **DELETE** throws it away with its orders.
- **Order loadouts** (v0.8.8). Every order keeps a saved loadout, **ORDER: <NAME>** on the Loadout tab: the best kit you own for it right now (what the 8-Ball would put on), kept up to date as parts come in, are crafted or go. You can rename it. When the order is matched its loadout stays, as an ordinary one; cancel the order and its loadout goes too, unless you renamed it. Delete it while the order is on and that order keeps none. Like every saved loadout, its parts are never scrapped.
- **The order list**: every order names **who it's for** (**FOR:** on the Showroom ad and on the goal): you, or a cat on the crew. A build for you goes on the 8-Ball's list, one for a cat on the crew's. An order leaves its list when whoever it's for wears the whole ad (or, with TOP TIER, when every part is at your top tier).
- **Its loot.** New salvage an order wants (its keystone, its exotic, its set's pieces and parts on its lanes, from one tier below your top) is **locked** on the way home, kept whatever your loot filter says, and **put on** when it's the best you have for the ad. With **EQUIP BEST AFTER EACH RUN** on (the default; WORKSHOP) it re-equips the whole kit for the ad after every run until you wear it all (every slot on its lane at your top tier, its keystone, 4 set pieces, its fuels and tank mods): then the ad is **matched**. For each job in an ad (a slot's lane, a set piece's slot, its keystone, its exotic, a tank mod for each fuel) the 8-Ball keeps the best part you have (one per order that needs the job); new loot worse than that isn't locked, and parts it locked that turn obsolete or whose order is gone are **let go** (unlocked, and scrapped with SCRAP WHAT NO ORDER WANTS on, never keystones or exotics). Your own locks are never touched. Parts locked before v0.8.3 don't say who locked them: **UNLOCK n LOCKED PARTS NO ORDER USES** (WORKSHOP) frees them after asking (yours too).
- **Builds for the crew**: an ad ordered **FOR:** a cat is farmed, crafted and equipped for that cat just as for you: the plan counts only parts that cat could wear, and the parts go onto the cat whenever it's home. The crew tab shows a cat's order and **WEAR ITS ORDER**.

### Workshop
- **Crafting for the order** (CRAFT FOR THE ORDERS, off at first): Before and after each 8-Ball run it crafts what the 8-Ball's first order still lacks: set pieces up to 4 (buying a piece's blueprint with shards first), a lane part at your top tier for every slot and tank mod below it (lanes whose blueprint you know), and the exotic upgrade (its blueprint with favor, then the craft). What it makes is locked. It makes at most 6 things a go, and with EQUIP BEST AFTER EACH RUN on puts them on.
- **TEMPER WORN PARTS** (off at first): before each 8-Ball run it tempers the Malevolent T4 parts you wear, the least tempered first.
- **SCRAP WHAT NO ORDER WANTS** (off at first). Loot from runs and crew trips that no order on either list wants is scrapped on the way home, in place of the loot filter (keystones and exotics are always kept). **SCRAP n NOW** does the same to your stash (never parts that are worn, locked, on a cat, in a saved loadout, keystones or exotics).
- **The stash** has no limit, but past 500 parts the Smokehouse's lists slow down: you're warned when it goes over.

### One reserve
- **THE HANDS KEEP** 0%%, 10%%, 25%% (the default), 50%% or 75%% of your Energy Sprinkles: the 8-Ball (crafting, blueprints, the truck engine, tempering) and the Overseer never spend into it.

### The crew, the kitchen and the yard
- **CREW FARMS TOO** (CREW): the 8-Ball sends every idle, rested cat out by itself: a cat with an order wears it first, the others take the best free parts (never ones another order wants), and they go where the crew's list says, at the highest threat they're safe at, for the trip length you pick (15 minutes to 8 hours). Cats are only sent while the game runs.
- **KITCHEN:** the chef cat's status (a contract goal points it at that faction), and **EVERY RUN**: a feast cooked before every run whenever you have what it takes.
- **YARD:** the Overseer's switch, what it may buy and what it buys next (see Cats and the crew).
- **LOG:** what the hands did lately, newest first.

## Endgame

### Infested runs
Past threat **21** a run turns Infested:
- salvage is T4 only, and Malevolent parts drop (each level adds 2 quality steps);
- every level adds a **mutator** (below), and each one raises salvage quality and Mutagen;
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

### Mutagen and Shards
- **Mutagen:** elites past threat 15 (12%), scrapping Mutated (1) and Malevolent (5) parts, radiant cats. Spend it to mutate behaviors.
- **Blueprint Shards:** breaking down set pieces, tuxedo cats. Spend them on set blueprints (30) and a destination's featured slot (60).

### Where to push
- Compare destinations by their growth: the Rust Flats piles on armor, the Glow Crater shields, the Sewer Delta health. Bring fuels and parts that answer the pool that grows fastest there.
- The Shoggoth's AUTO truck setting and the crew planner both use the same estimate of what your kit holds at a destination: a good guide to how deep to go.

## The Showroom (tested builds)

The Smokehouse's **SHOWROOM** tab sells flamethrowers. The ads are jokes; the builds are real: the balance lab's 60 endgame builds, four for every set, all tested under the same balance (v0.9.0). It stocks 10 at a time, 2 of each style, with **new stock after every run**: it shows every ad of a style before it shows one again, so a new game and five runs show all of them; an ad on order stays listed until the order is done, and the guide below has them all. In the game each ad also checks its parts list against your stash, links to the set blueprints and the fuel's exotics, and has **ORDER NOW!**: the Magic 8-Ball's plan for the build, what you wear of it, **ORDER IT** (the 8-Ball then farms for it: where to fight and which targeted-loot pick to buy; with an order already in hand, **ADD TO THE LIST**), **FOR:** (you or a cat on the crew, v0.8.2), **PUT IT ON** (equips the best you have for it) and **LOOT FILTER FOR THIS BUILD** (keeps the build's lanes). **CUSTOMIZE** (v0.8.8) starts a custom order from the ad, and **+ CUSTOM ORDER** one from the kit you wear: your own build, ordered like an ad.

**Reading an ad.** A build is a lane for every slot, a keystone (most builds have one), a tank mod, 4 pieces of its set in any slots (each piece rolls a lane of its slot, so keep the ones on the build's lanes), its fuels (the first is the signature) and three affixes worth hunting on every part. **Lab** is the threat a robot pig held at the build's home map, starting at threat 20, with every part T4 Malevolent and affixes at 90% of their range (3 seeds). The **exotic upgrade** is the best of the build's three strongest exotics in the lab (any gun slot but the keystone's), worn in place of that slot's piece, and what it added (2 seeds); a build whose exotics added under 0.1 has none.

| Build | Style | Set | Fuels | Home | Lab |
|---|---|---|---|---|---|
| Fry Cook Deluxe | Brawler | Deep Fryer | Fryer Oil, Rendered Lard | Sewer Delta | 26.1 |
| Pit Boss Cage Match | Brawler | Pit Boss | Rendered Lard, Thermite Slurry, Ion Gel | Smokehouse Outskirts | 25.7 |
| Swamp Grease Deluxe | Brawler | Grease Fire | Swamp Napalm, Rendered Lard | Sewer Delta | 25.7 |
| Grease Bomber 3000 | Brawler | Grease Fire | Rendered Lard, Rocket Hooch | Smokehouse Outskirts | 24.8 |
| Static Shock Pit | Brawler | Pit Boss | Ion Gel, Rendered Lard | Static Fields | 24.4 |
| Greasy Spoon Special | Brawler | Grease Fire | Fryer Oil, Rendered Lard | Bloat Marsh | 24.1 |
| Food Court Fireball | Brawler | Grease Fire | Rocket Hooch, Rendered Lard | The Food Court | 24.1 |
| Bog Brawler | Brawler | Pit Boss | Swamp Napalm, Rendered Lard | The Food Court | 23.7 |
| Lard Lad Fry Station | Brawler | Deep Fryer | Rendered Lard, Thermite Slurry | Smokehouse Outskirts | 23.2 |
| Armor Fritter | Brawler | Deep Fryer | Thermite Slurry, Rendered Lard | Tank Graveyard | 23.1 |
| Drive-In Brawler | Brawler | Pit Boss | Fryer Oil, Rendered Lard | Dead Drive-In | 22.8 |
| Glow-Fry Combo | Brawler | Deep Fryer | Rad Syrup, Rendered Lard | The Junk Bazaar | 22.2 |
| Critical Bog | Lancer | Meltdown | Swamp Napalm, Rendered Lard | Fungal Bog | 29.2 |
| Lard Reactor | Lancer | Meltdown | Rendered Lard, Swamp Napalm | Bloat Marsh | 26.3 |
| Steeple Glowscope | Lancer | Steeple Works | Rad Syrup, Rendered Lard | Sewer Delta | 26.3 |
| Arc Lancer Pro | Lancer | Tesla Coilworks | Ion Gel, Rendered Lard | Glow Crater | 25.9 |
| Smelter Spark | Lancer | Tesla Coilworks | Thermite Slurry, Rendered Lard | Smelter Pits | 25.5 |
| Electric Fryer | Lancer | Tesla Coilworks | Fryer Oil, Rendered Lard | The Flesh Farms | 25.3 |
| Bell Tower Bootlegger | Lancer | Steeple Works | Rocket Hooch, Thermite Slurry | Rust Flats | 25.2 |
| Glow Coil 9000 | Lancer | Tesla Coilworks | Rad Syrup, Ion Gel | Glow Crater | 24.1 |
| Neon Deadeye | Lancer | Steeple Works | Ion Gel, Rendered Lard | The Neon Strip | 23.9 |
| Reactor Row Rifle | Lancer | Meltdown | Ion Gel, Rendered Lard | Reactor Row | 23.8 |
| Steeple Marksman | Lancer | Steeple Works | Thermite Slurry, Rendered Lard | Rust Flats | 23.4 |
| Meltdown Sniper | Lancer | Meltdown | Rad Syrup, Ion Gel | Glow Crater | 23.4 |
| Hellmouth Food Court Edition | Furnace | Hellmouth | Swamp Napalm, Rendered Lard | The Food Court | 25.6 |
| Hellmouth Home Edition | Furnace | Hellmouth | Rocket Hooch, Thermite Slurry | Smokehouse Outskirts | 25.5 |
| Storm Throat | Furnace | Hellmouth | Ion Gel, Rendered Lard | Static Fields | 25.1 |
| Boiler Room Pressure Cooker | Furnace | Boiler Room | Rocket Hooch, Rendered Lard | Smokehouse Outskirts | 24.4 |
| Pressure Fryer | Furnace | Boiler Room | Fryer Oil, Rendered Lard | The Flesh Farms | 24.3 |
| Still Life | Furnace | Foundry Rig | Rocket Hooch, Rendered Lard | Smokehouse Outskirts | 24.1 |
| Forge Fryer | Furnace | Foundry Rig | Fryer Oil, Rendered Lard | The Junk Bazaar | 24.0 |
| Mountain Mouth | Furnace | Hellmouth | Thermite Slurry, Rendered Lard | Scrap Mountain | 23.9 |
| Isotope Forge | Furnace | Foundry Rig | Rad Syrup, Rendered Lard | Dead Drive-In | 23.4 |
| Foundry Furnace | Furnace | Foundry Rig | Thermite Slurry, Rendered Lard | Rust Flats | 23.3 |
| Pot Boiler | Furnace | Boiler Room | Rendered Lard, Thermite Slurry | Smokehouse Outskirts | 22.7 |
| Reactor Kettle | Furnace | Boiler Room | Rad Syrup, Ion Gel | Glow Crater | 22.6 |
| Bargain Bog | Miser | Thrift Shop | Swamp Napalm, Rendered Lard | Bloat Marsh | 27.7 |
| Sunday Roast | Miser | Slow Cooker | Rendered Lard, Swamp Napalm | Sewer Delta | 26.3 |
| Slow Cooker | Miser | Slow Cooker | Swamp Napalm, Rendered Lard | Sewer Delta | 26.2 |
| Frost Miser | Miser | Glacier Works | Swamp Napalm, Rendered Lard | Sewer Delta | 25.6 |
| Bathtub Special | Miser | Thrift Shop | Rocket Hooch, Thermite Slurry | Smelter Pits | 25.5 |
| Cold Forge | Miser | Glacier Works | Thermite Slurry, Rendered Lard | Tank Graveyard | 24.6 |
| Thrift Shop Special | Miser | Thrift Shop | Rendered Lard | Smokehouse Outskirts | 24.3 |
| Neon Simmer | Miser | Slow Cooker | Ion Gel, Rendered Lard | The Neon Strip | 24.2 |
| Glacier Glow | Miser | Glacier Works | Rad Syrup, Rendered Lard | Fungal Bog | 23.9 |
| Ice Capacitor | Miser | Glacier Works | Ion Gel, Rendered Lard | Reactor Row | 23.9 |
| Secondhand Isotope | Miser | Thrift Shop | Rad Syrup, Rendered Lard | The Junk Bazaar | 23.4 |
| Crock-Pot Fryer | Miser | Slow Cooker | Fryer Oil, Rendered Lard | Dead Drive-In | 22.9 |
| Lardolier | Juggler | Bandolier | Rendered Lard, Swamp Napalm, Thermite Slurry | Bloat Marsh | 29.8 |
| Bog Bandolier | Juggler | Bandolier | Swamp Napalm, Rendered Lard, Thermite Slurry | Fungal Bog | 28.3 |
| Moonshine Run Express | Juggler | Moonshine Run | Rocket Hooch, Rendered Lard, Thermite Slurry | Smokehouse Outskirts | 27.8 |
| The Bandolier | Juggler | Bandolier | Thermite Slurry, Rendered Lard, Ion Gel, Swamp Napalm | Smokehouse Outskirts | 27.6 |
| Fryer Run | Juggler | Moonshine Run | Fryer Oil, Rendered Lard, Swamp Napalm | The Flesh Farms | 27.5 |
| Static Bandolier | Juggler | Bandolier | Ion Gel, Rendered Lard, Thermite Slurry | Static Fields | 27.3 |
| Three-Still Special | Juggler | Moonshine Run | Rendered Lard, Thermite Slurry, Ion Gel | The Food Court | 26.9 |
| Fry-Up Cocktail | Juggler | Cocktail Hour | Fryer Oil, Rendered Lard, Thermite Slurry | The Junk Bazaar | 26.5 |
| Last Call | Juggler | Cocktail Hour | Rocket Hooch, Rendered Lard, Thermite Slurry | Dead Drive-In | 26.3 |
| Bog Run | Juggler | Moonshine Run | Swamp Napalm, Rendered Lard, Thermite Slurry | Smokehouse Outskirts | 26.1 |
| Cocktail Hour | Juggler | Cocktail Hour | Ion Gel, Rendered Lard, Thermite Slurry | Glow Crater | 25.9 |
| Rust Belt Cocktail | Juggler | Cocktail Hour | Thermite Slurry, Rendered Lard, Ion Gel | Rust Flats | 25.2 |

### Fry Cook Deluxe
**Brawler** (up close and in the crowd, Deep Fryer). "Whatever it kills comes out crispy." Ten thousand batches deep and still bubbling. Get up close, get them battered, and sell the leftovers by the crate. Ask about our family-size tank!

- Deep Fryer set: kills drop more raw meat, +40% stack damage within 220 px, and with 4 pieces BATTERED: every stack on a close mutant makes it take more (up to +60%).
- No keystone: the lab wore Deep Fryer in all seven slots.
- Fryer Oil's kills drop fried cuts, which sell for more. With it, Lard for flesh. Home: the Sewer Delta.
- Bloom nozzle (twice the cone, +220% up close), Gusher line (+35% flow) and Flash igniter (+50% stack damage, shorter burns).
- Booster pump (+50% pressure), Distiller filter (stack damage x1.5) and Vent Cowl (let go above half heat for a burst). Tanks: a Carousel (0.1 s swaps that hit harder right after) and Drip Bottles (small tanks that refill fast).

| Slot | Part |
|---|---|
| Fuel Line | Gusher |
| Nozzle | Bloom |
| Tank Chassis | Carousel |
| Pump | Booster |
| Igniter | Flash |
| Filter | Distiller |
| Shroud & Grip | Vent Cowl |
| Tank Mod | Drip Bottle on every tank |

**Set:** 4 Deep Fryer pieces. **Fuels:** Fryer Oil, Rendered Lard. **Affixes:** Boggy, Sticky, Greasy. **Home:** Sewer Delta. **Lab:** threat 26.1.

**Exotic upgrade:** Crackling Maw (the exotic Fryer Oil nozzle II, in place of the nozzle piece). When a mutant burning with Fryer Oil dies, its burn jumps to 2 nearby mutants (a quarter of its stacks). Lab: +1.0 threat.

### Pit Boss Cage Match
**Brawler** (up close and in the crowd, Pit Boss). "Step into the cage. Bring three fuels." The more of them crowd in, the meaner you get. Three fuels on the rack: one for flesh, one for armor, one for shields. Nobody leaves the cage.

- Pit Boss set: more stack damage close in, every hit you take vents heat as a burst around you, and with 4 pieces BURNING MAN: with 10 or more mutants close, +30% flow and 30% less damage taken.
- No keystone: the lab wore Pit Boss in all seven slots.
- Rendered Lard runs cool and sticks to flesh. With it, Thermite for armor and Ion Gel for shields. Home: the Smokehouse Outskirts.
- Lance nozzle (a narrow needle with longer burns), Gusher line (+35% flow) and Flash igniter (+50% stack damage, shorter burns).
- Booster pump (+50% pressure), Distiller filter (stack damage x1.5) and Vent Cowl (let go above half heat for a burst). Tanks: a Rack (+1 tank mount) and Primer Cells (the first 25 units from a full tank hit +60% harder).

| Slot | Part |
|---|---|
| Fuel Line | Gusher |
| Nozzle | Lance |
| Tank Chassis | Rack |
| Pump | Booster |
| Igniter | Flash |
| Filter | Distiller |
| Shroud & Grip | Vent Cowl |
| Tank Mod | Primer Cell on every tank |

**Set:** 4 Pit Boss pieces. **Fuels:** Rendered Lard, Thermite Slurry, Ion Gel. **Affixes:** Potent, Sticky, Recycling. **Home:** Smokehouse Outskirts. **Lab:** threat 25.7.

**Exotic upgrade:** Schmaltz Shroud (the exotic Rendered Lard shroud & grip III, in place of the shroud & grip piece). Lard runs 80% cooler, and mutants burning with it slow 20%. Lab: +1.0 threat.

### Swamp Grease Deluxe
**Brawler** (up close and in the crowd, Grease Fire). "Burns forever. Then explodes." Bog-gas gel that clings for days, in a gun that makes every kill go off. Fill it up, wade in, and let the swamp do the talking.

- Grease Fire set: +60% stack damage, burning kills splash a stack nearby, and with 4 pieces they explode for 2 stacks in a wide blast. One kill lights the next.
- No keystone: the lab wore Grease Fire in all seven slots.
- Swamp Napalm burns longest of any fuel, and hardest on meat. With it, Lard for flesh. Home: the Sewer Delta.
- Lance nozzle (a narrow needle with longer burns), Gusher line (+35% flow) and Smoulder igniter (burns last 60% longer).
- Siphon pump (refills the tank while it fires), Distiller filter (stack damage x1.5) and Vent Cowl (let go above half heat for a burst). Tanks: a Carousel (0.1 s swaps that hit harder right after) and Drip Bottles (small tanks that refill fast).

| Slot | Part |
|---|---|
| Fuel Line | Gusher |
| Nozzle | Lance |
| Tank Chassis | Carousel |
| Pump | Siphon |
| Igniter | Smoulder |
| Filter | Distiller |
| Shroud & Grip | Vent Cowl |
| Tank Mod | Drip Bottle on every tank |

**Set:** 4 Grease Fire pieces. **Fuels:** Swamp Napalm, Rendered Lard. **Affixes:** Potent, Greasy, Molten. **Home:** Sewer Delta. **Lab:** threat 25.7.

**Exotic upgrade:** Swamp-King Shroud (the exotic Swamp Napalm shroud & grip III, in place of the shroud & grip piece). Napalm runs 80% cooler, and mutants burning with it slow 20%. Lab: +1.7 threat.

### Grease Bomber 3000
**Brawler** (up close and in the crowd, Grease Fire). "Every kill goes off. So does the next one." Tired of mutants that die quietly? The Grease Bomber turns every kill into a party favor for everyone standing nearby. Neighbors hate it! (The neighbors are mutants.)

- Grease Fire set: +60% stack damage, burning kills splash a stack nearby, and with 4 pieces they explode for 2 stacks in a wide blast. One kill lights the next.
- Blood Line keystone: with the tank empty it keeps firing at full flow, paid for in armor, then HP. Watch the bar.
- Rendered Lard runs cool and sticks to flesh. With it, Rocket Hooch for the big ones. Home: the Smokehouse Outskirts.
- Lance nozzle (a narrow needle with longer burns) and Smoulder igniter (burns last 60% longer).
- Booster pump (+50% pressure), Coarse Mesh (one unit in five free) and Vent Cowl (let go above half heat for a burst). Tanks: a Rack (+1 tank mount) and Jerrycans (+40% capacity).

| Slot | Part |
|---|---|
| Fuel Line | Blood Line (keystone) |
| Nozzle | Lance |
| Tank Chassis | Rack |
| Pump | Booster |
| Igniter | Smoulder |
| Filter | Coarse Mesh |
| Shroud & Grip | Vent Cowl |
| Tank Mod | Jerrycan on every tank |

**Set:** 4 Grease Fire pieces. **Fuels:** Rendered Lard, Rocket Hooch. **Affixes:** Greasy, Potent, Recycling. **Home:** Smokehouse Outskirts. **Lab:** threat 24.8.

**Exotic upgrade:** Drippings Sieve (the exotic Rendered Lard filter II, in place of the filter piece). Lard deals at least x1.0 against health, shields and armor, and +25% vs health. Lab: +0.6 threat.

### Static Shock Pit
**Brawler** (up close and in the crowd, Pit Boss). "Shields down, gloves off." Ion Gel pops shields like soap bubbles, and the Pit Boss makes you meaner every time they crowd in. Built for the Static Fields; works anywhere with a crowd.

- Pit Boss set: more stack damage close in, every hit you take vents heat as a burst around you, and with 4 pieces BURNING MAN: with 10 or more mutants close, +30% flow and 30% less damage taken.
- Blood Line keystone: with the tank empty it keeps firing at full flow, paid for in armor, then HP. Watch the bar.
- Ion Gel pops shields: more than double damage on them. With it, Lard for flesh. Home: the Static Fields.
- Bloom nozzle (twice the cone, +220% up close) and Flash igniter (+50% stack damage, shorter burns).
- Siphon pump (refills the tank while it fires), Distiller filter (stack damage x1.5) and Vent Cowl (let go above half heat for a burst). Tanks: a Rack (+1 tank mount) and Jerrycans (+40% capacity).

| Slot | Part |
|---|---|
| Fuel Line | Blood Line (keystone) |
| Nozzle | Bloom |
| Tank Chassis | Rack |
| Pump | Siphon |
| Igniter | Flash |
| Filter | Distiller |
| Shroud & Grip | Vent Cowl |
| Tank Mod | Jerrycan on every tank |

**Set:** 4 Pit Boss pieces. **Fuels:** Ion Gel, Rendered Lard. **Affixes:** Greasy, Ionized, Sticky. **Home:** Static Fields. **Lab:** threat 24.4.

**Exotic upgrade:** Tallow Spout (the exotic Rendered Lard nozzle I, in place of the nozzle piece). Every Lard hit also coats 1 nearby mutant. Lab: +0.5 threat.

### Greasy Spoon Special
**Brawler** (up close and in the crowd, Grease Fire). "Fried, splashed and exploded. In that order." Breakfast all day, for everyone within eighty pixels. Fryer Oil does the frying, the Grease Fire does the rest, and you never stop to refuel.

- Grease Fire set: +60% stack damage, burning kills splash a stack nearby, and with 4 pieces they explode for 2 stacks in a wide blast. One kill lights the next.
- Blood Line keystone: with the tank empty it keeps firing at full flow, paid for in armor, then HP. Watch the bar.
- Fryer Oil's kills drop fried cuts, which sell for more. With it, Lard for flesh. Home: the Bloat Marsh.
- Bloom nozzle (twice the cone, +220% up close) and Flash igniter (+50% stack damage, shorter burns).
- Booster pump (+50% pressure), Distiller filter (stack damage x1.5) and Insulated shroud (holds 60% more heat). Tanks: a Rack (+1 tank mount) and Drip Bottles (small tanks that refill fast).

| Slot | Part |
|---|---|
| Fuel Line | Blood Line (keystone) |
| Nozzle | Bloom |
| Tank Chassis | Rack |
| Pump | Booster |
| Igniter | Flash |
| Filter | Distiller |
| Shroud & Grip | Insulated |
| Tank Mod | Drip Bottle on every tank |

**Set:** 4 Grease Fire pieces. **Fuels:** Fryer Oil, Rendered Lard. **Affixes:** Potent, Greasy, Sticky. **Home:** Bloat Marsh. **Lab:** threat 24.1.

**Exotic upgrade:** Schmaltz Throat (the exotic Rendered Lard nozzle III, in place of the nozzle piece). Lard stacks deal +50% on mutants outside the cone and +30% beyond 300 px. Lab: +0.8 threat.

### Food Court Fireball
**Brawler** (up close and in the crowd, Grease Fire). "Table for one? Table for everyone." Rocket Hooch hits hard on anything, and the Grease Fire makes every kill splash. Stay cool, stay close, and tip your server.

- Grease Fire set: +60% stack damage, burning kills splash a stack nearby, and with 4 pieces they explode for 2 stacks in a wide blast. One kill lights the next.
- No keystone: the lab wore Grease Fire in all seven slots.
- Rocket Hooch hits hardest of any fuel, on everything, but runs hot and burns short. With it, Lard for flesh. Home: the Food Court.
- Bloom nozzle (twice the cone, +220% up close), Capillary line (fewer, meaner, cooler drops) and Stoker igniter (big targets take more the more they carry).
- Siphon pump (refills the tank while it fires), Distiller filter (stack damage x1.5) and Insulated shroud (holds 60% more heat). Tanks: a Carousel (0.1 s swaps that hit harder right after) and Drip Bottles (small tanks that refill fast).

| Slot | Part |
|---|---|
| Fuel Line | Capillary |
| Nozzle | Bloom |
| Tank Chassis | Carousel |
| Pump | Siphon |
| Igniter | Stoker |
| Filter | Distiller |
| Shroud & Grip | Insulated |
| Tank Mod | Drip Bottle on every tank |

**Set:** 4 Grease Fire pieces. **Fuels:** Rocket Hooch, Rendered Lard. **Affixes:** Molten, Pressurized, Sticky. **Home:** The Food Court. **Lab:** threat 24.1.

**Exotic upgrade:** Schmaltz Shroud (the exotic Rendered Lard shroud & grip III, in place of the shroud & grip piece). Lard runs 80% cooler, and mutants burning with it slow 20%. Lab: +2.1 threat.

### Bog Brawler
**Brawler** (up close and in the crowd, Pit Boss). "Hugs that stick." Swamp Napalm burns forever on meat, so get close and stay close. The Pit Boss loves a crowd, and so does the bog.

- Pit Boss set: more stack damage close in, every hit you take vents heat as a burst around you, and with 4 pieces BURNING MAN: with 10 or more mutants close, +30% flow and 30% less damage taken.
- Blood Line keystone: with the tank empty it keeps firing at full flow, paid for in armor, then HP. Watch the bar.
- Swamp Napalm burns longest of any fuel, and hardest on meat. With it, Lard for flesh. Home: the Food Court.
- Bloom nozzle (twice the cone, +220% up close) and Flash igniter (+50% stack damage, shorter burns).
- Booster pump (+50% pressure), Distiller filter (stack damage x1.5) and Insulated shroud (holds 60% more heat). Tanks: a Rack (+1 tank mount) and Drip Bottles (small tanks that refill fast).

| Slot | Part |
|---|---|
| Fuel Line | Blood Line (keystone) |
| Nozzle | Bloom |
| Tank Chassis | Rack |
| Pump | Booster |
| Igniter | Flash |
| Filter | Distiller |
| Shroud & Grip | Insulated |
| Tank Mod | Drip Bottle on every tank |

**Set:** 4 Pit Boss pieces. **Fuels:** Swamp Napalm, Rendered Lard. **Affixes:** Potent, Boggy, Sticky. **Home:** The Food Court. **Lab:** threat 23.7.

**Exotic upgrade:** Swamp-King Shroud (the exotic Swamp Napalm shroud & grip III, in place of the shroud & grip piece). Napalm runs 80% cooler, and mutants burning with it slow 20%. Lab: +1.6 threat.

### Lard Lad Fry Station
**Brawler** (up close and in the crowd, Deep Fryer). "If it moves, batter it." The classic. Lard for the meat, Thermite for the tin cans, and a fry basket that never lets the oil go cold.

- Deep Fryer set: kills drop more raw meat, +40% stack damage within 220 px, and with 4 pieces BATTERED: every stack on a close mutant makes it take more (up to +60%).
- Blood Line keystone: with the tank empty it keeps firing at full flow, paid for in armor, then HP. Watch the bar.
- Rendered Lard runs cool and sticks to flesh. With it, Thermite for armor. Home: the Smokehouse Outskirts.
- Bloom nozzle (twice the cone, +220% up close) and Flash igniter (+50% stack damage, shorter burns).
- Booster pump (+50% pressure), Distiller filter (stack damage x1.5) and Insulated shroud (holds 60% more heat). Tanks: a Rack (+1 tank mount) and Jerrycans (+40% capacity).

| Slot | Part |
|---|---|
| Fuel Line | Blood Line (keystone) |
| Nozzle | Bloom |
| Tank Chassis | Rack |
| Pump | Booster |
| Igniter | Flash |
| Filter | Distiller |
| Shroud & Grip | Insulated |
| Tank Mod | Jerrycan on every tank |

**Set:** 4 Deep Fryer pieces. **Fuels:** Rendered Lard, Thermite Slurry. **Affixes:** Potent, Pressurized, Sticky. **Home:** Smokehouse Outskirts. **Lab:** threat 23.2.

**Exotic upgrade:** Drippings Maw (the exotic Rendered Lard nozzle II, in place of the nozzle piece). When a mutant burning with Lard dies, its burn jumps to 2 nearby mutants (a quarter of its stacks). Lab: +1.0 threat.

### Armor Fritter
**Brawler** (up close and in the crowd, Deep Fryer). "Deep-fries tanks. Yes, the metal ones." Thermite eats through plating like it owes money, and the fryer makes sure what's inside comes out golden. The Tank Graveyard has never smelled better.

- Deep Fryer set: kills drop more raw meat, +40% stack damage within 220 px, and with 4 pieces BATTERED: every stack on a close mutant makes it take more (up to +60%).
- Blood Line keystone: with the tank empty it keeps firing at full flow, paid for in armor, then HP. Watch the bar.
- Thermite Slurry eats armor: double damage on plating. With it, Lard for flesh. Home: the Tank Graveyard.
- Lance nozzle (a narrow needle with longer burns) and Smoulder igniter (burns last 60% longer).
- Siphon pump (refills the tank while it fires), Distiller filter (stack damage x1.5) and Insulated shroud (holds 60% more heat). Tanks: a Rack (+1 tank mount) and Jerrycans (+40% capacity).

| Slot | Part |
|---|---|
| Fuel Line | Blood Line (keystone) |
| Nozzle | Lance |
| Tank Chassis | Rack |
| Pump | Siphon |
| Igniter | Smoulder |
| Filter | Distiller |
| Shroud & Grip | Insulated |
| Tank Mod | Jerrycan on every tank |

**Set:** 4 Deep Fryer pieces. **Fuels:** Thermite Slurry, Rendered Lard. **Affixes:** Potent, Molten, Pressurized. **Home:** Tank Graveyard. **Lab:** threat 23.1.

**Exotic upgrade:** Tallow Mitt (the exotic Rendered Lard shroud & grip I, in place of the shroud & grip piece). Lard runs 25% cooler, and mutants burning with it slow 6%. Lab: +0.5 threat.

### Drive-In Brawler
**Brawler** (up close and in the crowd, Pit Boss). "Dinner and a fight. Mostly the fight." Pull up, roll down the window, and cook everything that comes near the car. Every kill is a fried cut for the road.

- Pit Boss set: more stack damage close in, every hit you take vents heat as a burst around you, and with 4 pieces BURNING MAN: with 10 or more mutants close, +30% flow and 30% less damage taken.
- Blood Line keystone: with the tank empty it keeps firing at full flow, paid for in armor, then HP. Watch the bar.
- Fryer Oil's kills drop fried cuts, which sell for more. With it, Lard for flesh. Home: the Dead Drive-In.
- Bloom nozzle (twice the cone, +220% up close) and Flash igniter (+50% stack damage, shorter burns).
- Booster pump (+50% pressure), Distiller filter (stack damage x1.5) and Insulated shroud (holds 60% more heat). Tanks: a Rack (+1 tank mount) and Drip Bottles (small tanks that refill fast).

| Slot | Part |
|---|---|
| Fuel Line | Blood Line (keystone) |
| Nozzle | Bloom |
| Tank Chassis | Rack |
| Pump | Booster |
| Igniter | Flash |
| Filter | Distiller |
| Shroud & Grip | Insulated |
| Tank Mod | Drip Bottle on every tank |

**Set:** 4 Pit Boss pieces. **Fuels:** Fryer Oil, Rendered Lard. **Affixes:** Potent, Recycling, Sticky. **Home:** Dead Drive-In. **Lab:** threat 22.8.

**Exotic upgrade:** Schmaltz Shroud (the exotic Rendered Lard shroud & grip III, in place of the shroud & grip piece). Lard runs 80% cooler, and mutants burning with it slow 20%. Lab: +1.7 threat.

### Glow-Fry Combo
**Brawler** (up close and in the crowd, Deep Fryer). "Glows in the fryer. Glows in the dark." Rad Syrup gets worse the longer it clings, and in a fryer it clings forever. Two-for-one at the Junk Bazaar, while supplies last.

- Deep Fryer set: kills drop more raw meat, +40% stack damage within 220 px, and with 4 pieces BATTERED: every stack on a close mutant makes it take more (up to +60%).
- Blood Line keystone: with the tank empty it keeps firing at full flow, paid for in armor, then HP. Watch the bar.
- Rad Syrup hits softly at first, but its stacks grow the longer they cling. With it, Lard for flesh. Home: the Junk Bazaar.
- Bloom nozzle (twice the cone, +220% up close) and Flash igniter (+50% stack damage, shorter burns).
- Booster pump (+50% pressure), Distiller filter (stack damage x1.5) and Vent Cowl (let go above half heat for a burst). Tanks: a Rack (+1 tank mount) and Jerrycans (+40% capacity).

| Slot | Part |
|---|---|
| Fuel Line | Blood Line (keystone) |
| Nozzle | Bloom |
| Tank Chassis | Rack |
| Pump | Booster |
| Igniter | Flash |
| Filter | Distiller |
| Shroud & Grip | Vent Cowl |
| Tank Mod | Jerrycan on every tank |

**Set:** 4 Deep Fryer pieces. **Fuels:** Rad Syrup, Rendered Lard. **Affixes:** Potent, Boggy, Recycling. **Home:** The Junk Bazaar. **Lab:** threat 22.2.

**Exotic upgrade:** Half-Life Crown (the exotic Rad Syrup igniter III, in place of the igniter piece; the fuel becomes Hot Syrup). CRITICAL MASS: a mutant carrying 100+ Rad stacks takes +50% from every burn, and Rad Syrup ages 50% faster; Rad Syrup stacks +40% damage. Lab: +1.6 threat.

### Critical Bog
**Lancer** (long reach, one target at a time, Meltdown). "Everything at once, all the time." Every tank fires at once, and the bog gel never lets go. Past a hundred and twenty stacks, everything takes half again. Ask about our bulk discount.

- Meltdown set: longer burns (and Rad Syrup ages faster), elites take +10% from every fuel, and with 4 pieces CRITICAL MASS: a mutant carrying 120+ stacks of one fuel takes +50% from every burn.
- Gatling Drum keystone: every unit fires from every tank at once, each with its own fuel, and every tank refills like an idle one. Double heat, so mind the gauge.
- Swamp Napalm burns longest of any fuel, and hardest on meat. With it, Lard for flesh. Home: the Fungal Bog.
- Lance nozzle (a narrow needle with longer burns), Capillary line (fewer, meaner, cooler drops) and Stoker igniter (big targets take more the more they carry).
- Booster pump (+50% pressure), Distiller filter (stack damage x1.5) and Vent Cowl (let go above half heat for a burst). Tanks: Drip Bottles (small tanks that refill fast).

| Slot | Part |
|---|---|
| Fuel Line | Capillary |
| Nozzle | Lance |
| Tank Chassis | Gatling Drum (keystone) |
| Pump | Booster |
| Igniter | Stoker |
| Filter | Distiller |
| Shroud & Grip | Vent Cowl |
| Tank Mod | Drip Bottle on every tank |

**Set:** 4 Meltdown pieces. **Fuels:** Swamp Napalm, Rendered Lard. **Affixes:** Molten, Greasy, Pressurized. **Home:** Fungal Bog. **Lab:** threat 29.2.

**Exotic upgrade:** Swamp-King Shroud (the exotic Swamp Napalm shroud & grip III, in place of the shroud & grip piece). Napalm runs 80% cooler, and mutants burning with it slow 20%. Lab: +1.5 threat.

### Lard Reactor
**Lancer** (long reach, one target at a time, Meltdown). "Splits the atom. And the meat." Two tanks, one trigger: Lard and Napalm fire together and pile the stacks high. Critical mass is just a matter of time.

- Meltdown set: longer burns (and Rad Syrup ages faster), elites take +10% from every fuel, and with 4 pieces CRITICAL MASS: a mutant carrying 120+ stacks of one fuel takes +50% from every burn.
- Gatling Drum keystone: every unit fires from every tank at once, each with its own fuel, and every tank refills like an idle one. Double heat, so mind the gauge.
- Rendered Lard runs cool and sticks to flesh. With it, Napalm for long burns. Home: the Bloat Marsh.
- Lance nozzle (a narrow needle with longer burns), Capillary line (fewer, meaner, cooler drops) and Stoker igniter (big targets take more the more they carry).
- Booster pump (+50% pressure), Distiller filter (stack damage x1.5) and Heatsink shroud (sheds heat 60% faster). Tanks: Primer Cells (the first 25 units from a full tank hit +60% harder).

| Slot | Part |
|---|---|
| Fuel Line | Capillary |
| Nozzle | Lance |
| Tank Chassis | Gatling Drum (keystone) |
| Pump | Booster |
| Igniter | Stoker |
| Filter | Distiller |
| Shroud & Grip | Heatsink |
| Tank Mod | Primer Cell on every tank |

**Set:** 4 Meltdown pieces. **Fuels:** Rendered Lard, Swamp Napalm. **Affixes:** Potent, Greasy, Molten. **Home:** Bloat Marsh. **Lab:** threat 26.3.

**Exotic upgrade:** Schmaltz Shroud (the exotic Rendered Lard shroud & grip III, in place of the shroud & grip piece). Lard runs 80% cooler, and mutants burning with it slow 20%. Lab: +2.5 threat.

### Steeple Glowscope
**Lancer** (long reach, one target at a time, Steeple Works). "Elites first. Questions never." Rad Syrup on every elite, two stacks at a time, from both tanks at once. They get worse the longer they live. They don't live long.

- Steeple Works set: longer burns, more damage beyond 300 px, and with 4 pieces DEADEYE: the first unit to hit an elite each second applies 2 stacks.
- Gatling Drum keystone: every unit fires from every tank at once, each with its own fuel, and every tank refills like an idle one. Double heat, so mind the gauge.
- Rad Syrup hits softly at first, but its stacks grow the longer they cling. With it, Lard for flesh. Home: the Sewer Delta.
- Lance nozzle (a narrow needle with longer burns), Capillary line (fewer, meaner, cooler drops) and Stoker igniter (big targets take more the more they carry).
- Booster pump (+50% pressure), Distiller filter (stack damage x1.5) and Vent Cowl (let go above half heat for a burst). Tanks: Primer Cells (the first 25 units from a full tank hit +60% harder).

| Slot | Part |
|---|---|
| Fuel Line | Capillary |
| Nozzle | Lance |
| Tank Chassis | Gatling Drum (keystone) |
| Pump | Booster |
| Igniter | Stoker |
| Filter | Distiller |
| Shroud & Grip | Vent Cowl |
| Tank Mod | Primer Cell on every tank |

**Set:** 4 Steeple Works pieces. **Fuels:** Rad Syrup, Rendered Lard. **Affixes:** Potent, Greasy, Boggy. **Home:** Sewer Delta. **Lab:** threat 26.3.

**Exotic upgrade:** Half-Life Crown (the exotic Rad Syrup igniter III, in place of the igniter piece; the fuel becomes Hot Syrup). CRITICAL MASS: a mutant carrying 100+ Rad stacks takes +50% from every burn, and Rad Syrup ages 50% faster; Rad Syrup stacks +40% damage. Lab: +0.7 threat.

### Arc Lancer Pro
**Lancer** (long reach, one target at a time, Tesla Coilworks). "One spark. Three mutants. Zero shields." Professional-grade lightning in a convenient gel. Point it at the shiny one and watch the sparks find its friends.

- Tesla Coilworks set: longer burns, breaking a shield stuns for a second, and with 4 pieces ARC: every hit chains to 2 nearby mutants.
- Gatling Drum keystone: every unit fires from every tank at once, each with its own fuel, and every tank refills like an idle one. Double heat, so mind the gauge.
- Ion Gel pops shields: more than double damage on them. With it, Lard for flesh. Home: the Glow Crater.
- Bloom nozzle (twice the cone, +220% up close), Capillary line (fewer, meaner, cooler drops) and Stoker igniter (big targets take more the more they carry).
- Booster pump (+50% pressure), Distiller filter (stack damage x1.5) and Vent Cowl (let go above half heat for a burst). Tanks: Primer Cells (the first 25 units from a full tank hit +60% harder).

| Slot | Part |
|---|---|
| Fuel Line | Capillary |
| Nozzle | Bloom |
| Tank Chassis | Gatling Drum (keystone) |
| Pump | Booster |
| Igniter | Stoker |
| Filter | Distiller |
| Shroud & Grip | Vent Cowl |
| Tank Mod | Primer Cell on every tank |

**Set:** 4 Tesla Coilworks pieces. **Fuels:** Ion Gel, Rendered Lard. **Affixes:** Pressurized, Sticky, Recycling. **Home:** Glow Crater. **Lab:** threat 25.9.

**Exotic upgrade:** Drippings Sieve (the exotic Rendered Lard filter II, in place of the filter piece). Lard deals at least x1.0 against health, shields and armor, and +25% vs health. Lab: +1.5 threat.

### Smelter Spark
**Lancer** (long reach, one target at a time, Tesla Coilworks). "Melts the plating. Then the lights." Thermite for the armor, lightning for everything standing next to it. Built in the Smelter Pits by people who got tired of scraping.

- Tesla Coilworks set: longer burns, breaking a shield stuns for a second, and with 4 pieces ARC: every hit chains to 2 nearby mutants.
- Gatling Drum keystone: every unit fires from every tank at once, each with its own fuel, and every tank refills like an idle one. Double heat, so mind the gauge.
- Thermite Slurry eats armor: double damage on plating. With it, Lard for flesh. Home: the Smelter Pits.
- Lance nozzle (a narrow needle with longer burns), Capillary line (fewer, meaner, cooler drops) and Stoker igniter (big targets take more the more they carry).
- Booster pump (+50% pressure), Distiller filter (stack damage x1.5) and Vent Cowl (let go above half heat for a burst). Tanks: Primer Cells (the first 25 units from a full tank hit +60% harder).

| Slot | Part |
|---|---|
| Fuel Line | Capillary |
| Nozzle | Lance |
| Tank Chassis | Gatling Drum (keystone) |
| Pump | Booster |
| Igniter | Stoker |
| Filter | Distiller |
| Shroud & Grip | Vent Cowl |
| Tank Mod | Primer Cell on every tank |

**Set:** 4 Tesla Coilworks pieces. **Fuels:** Thermite Slurry, Rendered Lard. **Affixes:** Boggy, Molten, Sticky. **Home:** Smelter Pits. **Lab:** threat 25.5.

**Exotic upgrade:** Forge-Heart Shroud (the exotic Thermite Slurry shroud & grip III, in place of the shroud & grip piece). Thermite runs 80% cooler, and mutants burning with it slow 20%. Lab: +0.7 threat.

### Electric Fryer
**Lancer** (long reach, one target at a time, Tesla Coilworks). "Zapped, then crisped." Lightning chains it, the fryer finishes it, and every burn lands the moment it hits. The Flesh Farms supply the meat.

- Tesla Coilworks set: longer burns, breaking a shield stuns for a second, and with 4 pieces ARC: every hit chains to 2 nearby mutants.
- Flashpoint keystone: a stack's whole burn lands the instant it hits. Nothing lingers, so longer burns do nothing here.
- Fryer Oil's kills drop fried cuts, which sell for more. With it, Lard for flesh. Home: the Flesh Farms.
- Lance nozzle (a narrow needle with longer burns) and Capillary line (fewer, meaner, cooler drops).
- Accumulator pump (a strong first burst), Distiller filter (stack damage x1.5) and Heatsink shroud (sheds heat 60% faster). Tanks: a Rack (+1 tank mount) and Primer Cells (the first 25 units from a full tank hit +60% harder).

| Slot | Part |
|---|---|
| Fuel Line | Capillary |
| Nozzle | Lance |
| Tank Chassis | Rack |
| Pump | Accumulator |
| Igniter | Flashpoint (keystone) |
| Filter | Distiller |
| Shroud & Grip | Heatsink |
| Tank Mod | Primer Cell on every tank |

**Set:** 4 Tesla Coilworks pieces. **Fuels:** Fryer Oil, Rendered Lard. **Affixes:** Potent, Greasy, Sticky. **Home:** The Flesh Farms. **Lab:** threat 25.3.

**Exotic upgrade:** Drippings Sieve (the exotic Rendered Lard filter II, in place of the filter piece). Lard deals at least x1.0 against health, shields and armor, and +25% vs health. Lab: +0.5 threat.

### Bell Tower Bootlegger
**Lancer** (long reach, one target at a time, Steeple Works). "Rings the bell on every elite." Rocket Hooch hits everything hard, Thermite handles the plating, and the Steeple picks out the big ones. Made in a bathtub on Rust Flats.

- Steeple Works set: longer burns, more damage beyond 300 px, and with 4 pieces DEADEYE: the first unit to hit an elite each second applies 2 stacks.
- Gatling Drum keystone: every unit fires from every tank at once, each with its own fuel, and every tank refills like an idle one. Double heat, so mind the gauge.
- Rocket Hooch hits hardest of any fuel, on everything, but runs hot and burns short. With it, Thermite for armor. Home: the Rust Flats.
- Lance nozzle (a narrow needle with longer burns), Capillary line (fewer, meaner, cooler drops) and Stoker igniter (big targets take more the more they carry).
- Booster pump (+50% pressure), Distiller filter (stack damage x1.5) and Vent Cowl (let go above half heat for a burst). Tanks: Jerrycans (+40% capacity).

| Slot | Part |
|---|---|
| Fuel Line | Capillary |
| Nozzle | Lance |
| Tank Chassis | Gatling Drum (keystone) |
| Pump | Booster |
| Igniter | Stoker |
| Filter | Distiller |
| Shroud & Grip | Vent Cowl |
| Tank Mod | Jerrycan on every tank |

**Set:** 4 Steeple Works pieces. **Fuels:** Rocket Hooch, Thermite Slurry. **Affixes:** Potent, Molten, Sticky. **Home:** Rust Flats. **Lab:** threat 25.2.

**Exotic upgrade:** Forge-Heart Shroud (the exotic Thermite Slurry shroud & grip III, in place of the shroud & grip piece). Thermite runs 80% cooler, and mutants burning with it slow 20%. Lab: +0.4 threat.

### Glow Coil 9000
**Lancer** (long reach, one target at a time, Tesla Coilworks). "One glow to rule the crater." Rad Syrup and Ion Gel in one coil: the shields pop, the syrup lands all at once, and the sparks carry it to the next one.

- Tesla Coilworks set: longer burns, breaking a shield stuns for a second, and with 4 pieces ARC: every hit chains to 2 nearby mutants.
- Flashpoint keystone: a stack's whole burn lands the instant it hits. Nothing lingers, so longer burns do nothing here.
- Rad Syrup hits softly at first, but its stacks grow the longer they cling. With it, Ion Gel for shields. Home: the Glow Crater.
- Lance nozzle (a narrow needle with longer burns) and Capillary line (fewer, meaner, cooler drops).
- Booster pump (+50% pressure), Distiller filter (stack damage x1.5) and Heatsink shroud (sheds heat 60% faster). Tanks: a Rack (+1 tank mount) and Primer Cells (the first 25 units from a full tank hit +60% harder).

| Slot | Part |
|---|---|
| Fuel Line | Capillary |
| Nozzle | Lance |
| Tank Chassis | Rack |
| Pump | Booster |
| Igniter | Flashpoint (keystone) |
| Filter | Distiller |
| Shroud & Grip | Heatsink |
| Tank Mod | Primer Cell on every tank |

**Set:** 4 Tesla Coilworks pieces. **Fuels:** Rad Syrup, Ion Gel. **Affixes:** Potent, Greasy, Sticky. **Home:** Glow Crater. **Lab:** threat 24.1.

**Exotic upgrade:** Storm Aorta (the exotic Ion Gel fuel line III, in place of the fuel line piece). Ion Gel kills refill 3 units, an empty Ion Gel tank refills 40% at once (every 20 s), and the first 60 Ion Gel units from a full tank deal +40%; Ion Gel stacks +30% damage. Lab: +0.5 threat.

### Neon Deadeye
**Lancer** (long reach, one target at a time, Steeple Works). "Shoots the lights out." Long reach, shields gone, and every burn lands the moment it hits. Built for the Neon Strip's shiny regulars.

- Steeple Works set: longer burns, more damage beyond 300 px, and with 4 pieces DEADEYE: the first unit to hit an elite each second applies 2 stacks.
- Flashpoint keystone: a stack's whole burn lands the instant it hits. Nothing lingers, so longer burns do nothing here.
- Ion Gel pops shields: more than double damage on them. With it, Lard for flesh. Home: the Neon Strip.
- Lance nozzle (a narrow needle with longer burns) and Capillary line (fewer, meaner, cooler drops).
- Accumulator pump (a strong first burst), Distiller filter (stack damage x1.5) and Heatsink shroud (sheds heat 60% faster). Tanks: a Rack (+1 tank mount) and Primer Cells (the first 25 units from a full tank hit +60% harder).

| Slot | Part |
|---|---|
| Fuel Line | Capillary |
| Nozzle | Lance |
| Tank Chassis | Rack |
| Pump | Accumulator |
| Igniter | Flashpoint (keystone) |
| Filter | Distiller |
| Shroud & Grip | Heatsink |
| Tank Mod | Primer Cell on every tank |

**Set:** 4 Steeple Works pieces. **Fuels:** Ion Gel, Rendered Lard. **Affixes:** Potent, Greasy, Sticky. **Home:** The Neon Strip. **Lab:** threat 23.9.

**Exotic upgrade:** Drippings Rack (the exotic Rendered Lard tank chassis II, in place of the tank chassis piece). The Lard tank refills 50% faster. Lab: +0.6 threat.

### Reactor Row Rifle
**Lancer** (long reach, one target at a time, Meltdown). "Pops shields from the next postcode." Ion Gel on a long, narrow beam, and every burn lands the instant it hits. Reactor Row has never been so quiet.

- Meltdown set: longer burns (and Rad Syrup ages faster), elites take +10% from every fuel, and with 4 pieces CRITICAL MASS: a mutant carrying 120+ stacks of one fuel takes +50% from every burn.
- Flashpoint keystone: a stack's whole burn lands the instant it hits. Nothing lingers, so longer burns do nothing here.
- Ion Gel pops shields: more than double damage on them. With it, Lard for flesh. Home: Reactor Row.
- Lance nozzle (a narrow needle with longer burns) and Capillary line (fewer, meaner, cooler drops).
- Accumulator pump (a strong first burst), Distiller filter (stack damage x1.5) and Heatsink shroud (sheds heat 60% faster). Tanks: a Rack (+1 tank mount) and Primer Cells (the first 25 units from a full tank hit +60% harder).

| Slot | Part |
|---|---|
| Fuel Line | Capillary |
| Nozzle | Lance |
| Tank Chassis | Rack |
| Pump | Accumulator |
| Igniter | Flashpoint (keystone) |
| Filter | Distiller |
| Shroud & Grip | Heatsink |
| Tank Mod | Primer Cell on every tank |

**Set:** 4 Meltdown pieces. **Fuels:** Ion Gel, Rendered Lard. **Affixes:** Potent, Greasy, Sticky. **Home:** Reactor Row. **Lab:** threat 23.8.

**Exotic upgrade:** Drippings Sieve (the exotic Rendered Lard filter II, in place of the filter piece). Lard deals at least x1.0 against health, shields and armor, and +25% vs health. Lab: +0.8 threat.

### Steeple Marksman
**Lancer** (long reach, one target at a time, Steeple Works). "Picks the big one. Every time." From the bell tower, every elite is a target and every second counts. Keep the gun warm and the big ones fall first.

- Steeple Works set: longer burns, more damage beyond 300 px, and with 4 pieces DEADEYE: the first unit to hit an elite each second applies 2 stacks.
- Fever Grip keystone: +1% stack damage for every 4% heat. Keep it warm, but overheating skips your armor.
- Thermite Slurry eats armor: double damage on plating. With it, Lard for flesh. Home: the Rust Flats.
- Lance nozzle (a narrow needle with longer burns), Capillary line (fewer, meaner, cooler drops) and Stoker igniter (big targets take more the more they carry).
- Booster pump (+50% pressure) and Distiller filter (stack damage x1.5). Tanks: a Rack (+1 tank mount) and Primer Cells (the first 25 units from a full tank hit +60% harder).

| Slot | Part |
|---|---|
| Fuel Line | Capillary |
| Nozzle | Lance |
| Tank Chassis | Rack |
| Pump | Booster |
| Igniter | Stoker |
| Filter | Distiller |
| Shroud & Grip | Fever Grip (keystone) |
| Tank Mod | Primer Cell on every tank |

**Set:** 4 Steeple Works pieces. **Fuels:** Thermite Slurry, Rendered Lard. **Affixes:** Molten, Potent, Recycling. **Home:** Rust Flats. **Lab:** threat 23.4.

**Exotic upgrade:** Forge-Heart Crown (the exotic Thermite Slurry igniter III, in place of the igniter piece; the fuel becomes Molten Slag). MOLTEN SLAG: Thermite kills leave a burning pool (2 stacks a tick for 1.5 s, 60 px); Thermite +30% vs armor. Lab: +0.5 threat.

### Meltdown Sniper
**Lancer** (long reach, one target at a time, Meltdown). "Named for range. Built for hugs." Marketing named it before Engineering finished it: it's a close-range gun now. Rad Syrup's whole burn lands the instant it hits, the stacks pile past a hundred and twenty, and then everything takes half again.

- Meltdown set: longer burns (and Rad Syrup ages faster), elites take +10% from every fuel, and with 4 pieces CRITICAL MASS: a mutant carrying 120+ stacks of one fuel takes +50% from every burn.
- Flashpoint keystone: a stack's whole burn lands the instant it hits. Nothing lingers, so longer burns do nothing here.
- Rad Syrup hits softly at first, but its stacks grow the longer they cling. With it, Ion Gel for shields. Home: the Glow Crater.
- Bloom nozzle (twice the cone, +220% up close) and Gusher line (+35% flow).
- Booster pump (+50% pressure), Distiller filter (stack damage x1.5) and Vent Cowl (let go above half heat for a burst). Tanks: a Rack (+1 tank mount) and Primer Cells (the first 25 units from a full tank hit +60% harder).

| Slot | Part |
|---|---|
| Fuel Line | Gusher |
| Nozzle | Bloom |
| Tank Chassis | Rack |
| Pump | Booster |
| Igniter | Flashpoint (keystone) |
| Filter | Distiller |
| Shroud & Grip | Vent Cowl |
| Tank Mod | Primer Cell on every tank |

**Set:** 4 Meltdown pieces. **Fuels:** Rad Syrup, Ion Gel. **Affixes:** Potent, Sticky, Recycling. **Home:** Glow Crater. **Lab:** threat 23.4.

**Exotic upgrade:** Storm Altar (the exotic Ion Gel tank chassis III, in place of the tank chassis piece). The first 80 Ion Gel units from a full tank deal +100%, and its tank refills twice as fast while another fires. Lab: +1.3 threat.

### Hellmouth Food Court Edition
**Furnace** (runs hot and holds the trigger, Hellmouth). "Served hot, all day." Swamp Napalm hits meat hard, the Hellmouth makes it +90% harder, and Flashpoint lands every burn the instant it hits. The Food Court is closed for cleaning.

- Hellmouth set (rare, drops anywhere): all fuels +90% stack damage and 30% less heat. (Its 4-piece does nothing with Flashpoint; the +90% is what the lab wore it for.)
- Flashpoint keystone: a stack's whole burn lands the instant it hits. Nothing lingers, so longer burns do nothing here.
- Swamp Napalm burns longest of any fuel, and hardest on meat. With it, Lard for flesh. Home: the Food Court.
- Lance nozzle (a narrow needle with longer burns) and Spool-Up Coil (flow climbs to x1.6 as you hold).
- Booster pump (+50% pressure), Distiller filter (stack damage x1.5) and Insulated shroud (holds 60% more heat). Tanks: a Rack (+1 tank mount) and Drip Bottles (small tanks that refill fast).

| Slot | Part |
|---|---|
| Fuel Line | Spool-Up Coil |
| Nozzle | Lance |
| Tank Chassis | Rack |
| Pump | Booster |
| Igniter | Flashpoint (keystone) |
| Filter | Distiller |
| Shroud & Grip | Insulated |
| Tank Mod | Drip Bottle on every tank |

**Set:** 4 Hellmouth pieces. **Fuels:** Swamp Napalm, Rendered Lard. **Affixes:** Potent, Sticky, Boggy. **Home:** The Food Court. **Lab:** threat 25.6.

**Exotic upgrade:** Jelly Sieve (the exotic Swamp Napalm filter II, in place of the filter piece). Napalm deals at least x1.0 against health, shields and armor, and +25% vs health. Lab: +1.4 threat.

### Hellmouth Home Edition
**Furnace** (runs hot and holds the trigger, Hellmouth). "Hold the trigger. The Hellmouth does the rest." The rare one, now available for the home! Every fuel hits +90% harder and runs cooler, Flashpoint lands each burn the instant it hits, and the Spool-Up Coil rewards a long, steady hold.

- Hellmouth set (rare, drops anywhere): all fuels +90% stack damage and 30% less heat. (Its 4-piece does nothing with Flashpoint; the +90% is what the lab wore it for.)
- Flashpoint keystone: a stack's whole burn lands the instant it hits. Nothing lingers, so longer burns do nothing here.
- Rocket Hooch hits hardest of any fuel, on everything, but runs hot and burns short. With it, Thermite for armor. Home: the Smokehouse Outskirts.
- Lance nozzle (a narrow needle with longer burns) and Spool-Up Coil (flow climbs to x1.6 as you hold).
- Booster pump (+50% pressure), Distiller filter (stack damage x1.5) and Vent Cowl (let go above half heat for a burst). Tanks: a Rack (+1 tank mount) and Primer Cells (the first 25 units from a full tank hit +60% harder).

| Slot | Part |
|---|---|
| Fuel Line | Spool-Up Coil |
| Nozzle | Lance |
| Tank Chassis | Rack |
| Pump | Booster |
| Igniter | Flashpoint (keystone) |
| Filter | Distiller |
| Shroud & Grip | Vent Cowl |
| Tank Mod | Primer Cell on every tank |

**Set:** 4 Hellmouth pieces. **Fuels:** Rocket Hooch, Thermite Slurry. **Affixes:** Potent, Sticky, Recycling. **Home:** Smokehouse Outskirts. **Lab:** threat 25.5.

**Exotic upgrade:** Forge-Heart Altar (the exotic Thermite Slurry tank chassis III, in place of the tank chassis piece). The first 80 Thermite units from a full tank deal +100%, and its tank refills twice as fast while another fires. Lab: +1.1 threat.

### Storm Throat
**Furnace** (runs hot and holds the trigger, Hellmouth). "Hold the trigger. Hold it." The coil spins up, the shields go down, and the hotter it runs the harder it bites. Built for the Static Fields' worst weather.

- Hellmouth set (rare, drops anywhere): all fuels +90% stack damage, longer burns and 30% less heat, and with 4 pieces stacks stop expiring while the mutant stays in the cone.
- Fever Grip keystone: +1% stack damage for every 4% heat. Keep it warm, but overheating skips your armor.
- Ion Gel pops shields: more than double damage on them. With it, Lard for flesh. Home: the Static Fields.
- Lance nozzle (a narrow needle with longer burns), Spool-Up Coil (flow climbs to x1.6 as you hold) and Stoker igniter (big targets take more the more they carry).
- Booster pump (+50% pressure) and Distiller filter (stack damage x1.5). Tanks: a Carousel (0.1 s swaps that hit harder right after) and Drip Bottles (small tanks that refill fast).

| Slot | Part |
|---|---|
| Fuel Line | Spool-Up Coil |
| Nozzle | Lance |
| Tank Chassis | Carousel |
| Pump | Booster |
| Igniter | Stoker |
| Filter | Distiller |
| Shroud & Grip | Fever Grip (keystone) |
| Tank Mod | Drip Bottle on every tank |

**Set:** 4 Hellmouth pieces. **Fuels:** Ion Gel, Rendered Lard. **Affixes:** Potent, Greasy, Boggy. **Home:** Static Fields. **Lab:** threat 25.1.

**Exotic upgrade:** Storm Throat (the exotic Ion Gel nozzle III, in place of the nozzle piece). Ion Gel stacks deal +50% on mutants outside the cone and +30% beyond 300 px. Lab: +1.3 threat.

### Boiler Room Pressure Cooker
**Furnace** (runs hot and holds the trigger, Boiler Room). "Whistles when it's ready." Build the heat, hit a hundred percent, and the Pressure Cooker turns it into three seconds of free fire. Then do it again.

- Boiler Room set: a bigger heat cap, more damage above half heat, and with 4 pieces PRESSURE COOKER: reaching 100% heat starts 3 s with no overheat damage and +50% flow, then the heat drops to zero (once every 45 s).
- Flashpoint keystone: a stack's whole burn lands the instant it hits. Nothing lingers, so longer burns do nothing here.
- Rocket Hooch hits hardest of any fuel, on everything, but runs hot and burns short. With it, Lard for flesh. Home: the Smokehouse Outskirts.
- Lance nozzle (a narrow needle with longer burns) and Spool-Up Coil (flow climbs to x1.6 as you hold).
- Booster pump (+50% pressure), Distiller filter (stack damage x1.5) and Insulated shroud (holds 60% more heat). Tanks: a Rack (+1 tank mount) and Jerrycans (+40% capacity).

| Slot | Part |
|---|---|
| Fuel Line | Spool-Up Coil |
| Nozzle | Lance |
| Tank Chassis | Rack |
| Pump | Booster |
| Igniter | Flashpoint (keystone) |
| Filter | Distiller |
| Shroud & Grip | Insulated |
| Tank Mod | Jerrycan on every tank |

**Set:** 4 Boiler Room pieces. **Fuels:** Rocket Hooch, Rendered Lard. **Affixes:** Potent, Sticky, Recycling. **Home:** Smokehouse Outskirts. **Lab:** threat 24.4.

**Exotic upgrade:** Mash Mitt (the exotic Rocket Hooch shroud & grip I, in place of the shroud & grip piece). Hooch runs 25% cooler, and mutants burning with it slow 6%. Lab: +0.7 threat.

### Pressure Fryer
**Furnace** (runs hot and holds the trigger, Boiler Room). "Fifteen PSI of crispy." Seal the lid, crank the heat, and fry under pressure. The hotter it runs, the harder it hits, and the Flesh Farms supply the batter.

- Boiler Room set: a bigger heat cap, more damage above half heat, and with 4 pieces PRESSURE COOKER: reaching 100% heat starts 3 s with no overheat damage and +50% flow, then the heat drops to zero (once every 45 s).
- Fever Grip keystone: +1% stack damage for every 4% heat. Keep it warm, but overheating skips your armor.
- Fryer Oil's kills drop fried cuts, which sell for more. With it, Lard for flesh. Home: the Flesh Farms.
- Lance nozzle (a narrow needle with longer burns), Spool-Up Coil (flow climbs to x1.6 as you hold) and Smoulder igniter (burns last 60% longer).
- Siphon pump (refills the tank while it fires) and Distiller filter (stack damage x1.5). Tanks: a Carousel (0.1 s swaps that hit harder right after) and Drip Bottles (small tanks that refill fast).

| Slot | Part |
|---|---|
| Fuel Line | Spool-Up Coil |
| Nozzle | Lance |
| Tank Chassis | Carousel |
| Pump | Siphon |
| Igniter | Smoulder |
| Filter | Distiller |
| Shroud & Grip | Fever Grip (keystone) |
| Tank Mod | Drip Bottle on every tank |

**Set:** 4 Boiler Room pieces. **Fuels:** Fryer Oil, Rendered Lard. **Affixes:** Potent, Greasy, Cooled. **Home:** The Flesh Farms. **Lab:** threat 24.3.

**Exotic upgrade:** Deep-Fry Aorta (the exotic Fryer Oil fuel line III, in place of the fuel line piece). Fryer Oil kills refill 3 units, an empty Fryer Oil tank refills 40% at once (every 20 s), and the first 60 Fryer Oil units from a full tank deal +40%. Lab: +0.9 threat.

### Still Life
**Furnace** (runs hot and holds the trigger, Foundry Rig). "Pours hot, burns hotter." A copper still bolted to a furnace: Rocket Hooch hits everything, every burn lands at once, and the heat never quite catches up.

- Foundry Rig set: longer burns, +10% stack damage, and with 4 pieces SLAG POOLS: kills leave a brief burning pool.
- Flashpoint keystone: a stack's whole burn lands the instant it hits. Nothing lingers, so longer burns do nothing here.
- Rocket Hooch hits hardest of any fuel, on everything, but runs hot and burns short. With it, Lard for flesh. Home: the Smokehouse Outskirts.
- Lance nozzle (a narrow needle with longer burns) and Capillary line (fewer, meaner, cooler drops).
- Siphon pump (refills the tank while it fires), Distiller filter (stack damage x1.5) and Insulated shroud (holds 60% more heat). Tanks: a Rack (+1 tank mount) and Jerrycans (+40% capacity).

| Slot | Part |
|---|---|
| Fuel Line | Capillary |
| Nozzle | Lance |
| Tank Chassis | Rack |
| Pump | Siphon |
| Igniter | Flashpoint (keystone) |
| Filter | Distiller |
| Shroud & Grip | Insulated |
| Tank Mod | Jerrycan on every tank |

**Set:** 4 Foundry Rig pieces. **Fuels:** Rocket Hooch, Rendered Lard. **Affixes:** Sticky, Boggy, Cooled. **Home:** Smokehouse Outskirts. **Lab:** threat 24.1.

**Exotic upgrade:** Mash Plunger (the exotic Rocket Hooch pump I, in place of the pump piece). Hooch stacks +15% damage. Lab: +1.4 threat.

### Forge Fryer
**Furnace** (runs hot and holds the trigger, Foundry Rig). "Cast iron, extra crispy." The fryer is a forge now. Every burn lands the moment it hits, kills leave slag on the floor, and the meat comes out fried.

- Foundry Rig set: longer burns, +10% stack damage, and with 4 pieces SLAG POOLS: kills leave a brief burning pool.
- Flashpoint keystone: a stack's whole burn lands the instant it hits. Nothing lingers, so longer burns do nothing here.
- Fryer Oil's kills drop fried cuts, which sell for more. With it, Lard for flesh. Home: the Junk Bazaar.
- Lance nozzle (a narrow needle with longer burns) and Capillary line (fewer, meaner, cooler drops).
- Siphon pump (refills the tank while it fires), Distiller filter (stack damage x1.5) and Insulated shroud (holds 60% more heat). Tanks: a Carousel (0.1 s swaps that hit harder right after) and Drip Bottles (small tanks that refill fast).

| Slot | Part |
|---|---|
| Fuel Line | Capillary |
| Nozzle | Lance |
| Tank Chassis | Carousel |
| Pump | Siphon |
| Igniter | Flashpoint (keystone) |
| Filter | Distiller |
| Shroud & Grip | Insulated |
| Tank Mod | Drip Bottle on every tank |

**Set:** 4 Foundry Rig pieces. **Fuels:** Fryer Oil, Rendered Lard. **Affixes:** Potent, Sticky, Cooled. **Home:** The Junk Bazaar. **Lab:** threat 24.0.

**Exotic upgrade:** Drippings Sieve (the exotic Rendered Lard filter II, in place of the filter piece). Lard deals at least x1.0 against health, shields and armor, and +25% vs health. Lab: +1.5 threat.

### Mountain Mouth
**Furnace** (runs hot and holds the trigger, Hellmouth). "Swallows the scrap pile." Thermite into the Hellmouth: armor melts, burns never stop while they stay in the cone, and Scrap Mountain gets a little smaller every run.

- Hellmouth set (rare, drops anywhere): all fuels +90% stack damage, longer burns and 30% less heat, and with 4 pieces stacks stop expiring while the mutant stays in the cone.
- No keystone: the lab wore Hellmouth in all seven slots.
- Thermite Slurry eats armor: double damage on plating. With it, Lard for flesh. Home: Scrap Mountain.
- Lance nozzle (a narrow needle with longer burns), Spool-Up Coil (flow climbs to x1.6 as you hold) and Smoulder igniter (burns last 60% longer).
- Booster pump (+50% pressure), Distiller filter (stack damage x1.5) and Insulated shroud (holds 60% more heat). Tanks: a Carousel (0.1 s swaps that hit harder right after) and Jerrycans (+40% capacity).

| Slot | Part |
|---|---|
| Fuel Line | Spool-Up Coil |
| Nozzle | Lance |
| Tank Chassis | Carousel |
| Pump | Booster |
| Igniter | Smoulder |
| Filter | Distiller |
| Shroud & Grip | Insulated |
| Tank Mod | Jerrycan on every tank |

**Set:** 4 Hellmouth pieces. **Fuels:** Thermite Slurry, Rendered Lard. **Affixes:** Potent, Molten, Boggy. **Home:** Scrap Mountain. **Lab:** threat 23.9.

**Exotic upgrade:** Schmaltz Shroud (the exotic Rendered Lard shroud & grip III, in place of the shroud & grip piece). Lard runs 80% cooler, and mutants burning with it slow 20%. Lab: +2.6 threat.

### Isotope Forge
**Furnace** (runs hot and holds the trigger, Foundry Rig). "Runs hot. Glows hotter." Rad Syrup in a furnace built to run hot: the warmer the gun, the harder every stack hits, and the syrup just keeps getting worse.

- Foundry Rig set: longer burns, +10% stack damage, and with 4 pieces SLAG POOLS: kills leave a brief burning pool.
- Fever Grip keystone: +1% stack damage for every 4% heat. Keep it warm, but overheating skips your armor.
- Rad Syrup hits softly at first, but its stacks grow the longer they cling. With it, Lard for flesh. Home: the Dead Drive-In.
- Lance nozzle (a narrow needle with longer burns), Capillary line (fewer, meaner, cooler drops) and Smoulder igniter (burns last 60% longer).
- Booster pump (+50% pressure) and Distiller filter (stack damage x1.5). Tanks: a Carousel (0.1 s swaps that hit harder right after) and Jerrycans (+40% capacity).

| Slot | Part |
|---|---|
| Fuel Line | Capillary |
| Nozzle | Lance |
| Tank Chassis | Carousel |
| Pump | Booster |
| Igniter | Smoulder |
| Filter | Distiller |
| Shroud & Grip | Fever Grip (keystone) |
| Tank Mod | Jerrycan on every tank |

**Set:** 4 Foundry Rig pieces. **Fuels:** Rad Syrup, Rendered Lard. **Affixes:** Potent, Greasy, Boggy. **Home:** Dead Drive-In. **Lab:** threat 23.4.

**Exotic upgrade:** Drippings Sieve (the exotic Rendered Lard filter II, in place of the filter piece). Lard deals at least x1.0 against health, shields and armor, and +25% vs health. Lab: +1.2 threat.

### Foundry Furnace
**Furnace** (runs hot and holds the trigger, Foundry Rig). "Runs hot. Stays hot. Melts everything." Fire the furnace and keep it fed. The hotter it runs, the harder it hits, and Thermite takes the plating off everything in front of it.

- Foundry Rig set: longer burns, +10% stack damage, and with 4 pieces SLAG POOLS: kills leave a brief burning pool.
- Fever Grip keystone: +1% stack damage for every 4% heat. Keep it warm, but overheating skips your armor.
- Thermite Slurry eats armor: double damage on plating. With it, Lard for flesh. Home: the Rust Flats.
- Lance nozzle (a narrow needle with longer burns), Gusher line (+35% flow) and Smoulder igniter (burns last 60% longer).
- Booster pump (+50% pressure) and Distiller filter (stack damage x1.5). Tanks: a Rack (+1 tank mount) and Jerrycans (+40% capacity).

| Slot | Part |
|---|---|
| Fuel Line | Gusher |
| Nozzle | Lance |
| Tank Chassis | Rack |
| Pump | Booster |
| Igniter | Smoulder |
| Filter | Distiller |
| Shroud & Grip | Fever Grip (keystone) |
| Tank Mod | Jerrycan on every tank |

**Set:** 4 Foundry Rig pieces. **Fuels:** Thermite Slurry, Rendered Lard. **Affixes:** Molten, Potent, Pressurized. **Home:** Rust Flats. **Lab:** threat 23.3.

**Exotic upgrade:** Crucible Rack (the exotic Thermite Slurry tank chassis II, in place of the tank chassis piece). The Thermite tank refills 50% faster. Lab: +1.2 threat.

### Pot Boiler
**Furnace** (runs hot and holds the trigger, Boiler Room). "Lard, pressure, regret (theirs)." Cheap fuel, a big boiler and no patience. Every burn lands at once, and when the gauge hits the red, it pours.

- Boiler Room set: a bigger heat cap, more damage above half heat, and with 4 pieces PRESSURE COOKER: reaching 100% heat starts 3 s with no overheat damage and +50% flow, then the heat drops to zero (once every 45 s).
- Flashpoint keystone: a stack's whole burn lands the instant it hits. Nothing lingers, so longer burns do nothing here.
- Rendered Lard runs cool and sticks to flesh. With it, Thermite for armor. Home: the Smokehouse Outskirts.
- Lance nozzle (a narrow needle with longer burns) and Capillary line (fewer, meaner, cooler drops).
- Siphon pump (refills the tank while it fires), Distiller filter (stack damage x1.5) and Insulated shroud (holds 60% more heat). Tanks: a Carousel (0.1 s swaps that hit harder right after) and Jerrycans (+40% capacity).

| Slot | Part |
|---|---|
| Fuel Line | Capillary |
| Nozzle | Lance |
| Tank Chassis | Carousel |
| Pump | Siphon |
| Igniter | Flashpoint (keystone) |
| Filter | Distiller |
| Shroud & Grip | Insulated |
| Tank Mod | Jerrycan on every tank |

**Set:** 4 Boiler Room pieces. **Fuels:** Rendered Lard, Thermite Slurry. **Affixes:** Recycling, Boggy, Sticky. **Home:** Smokehouse Outskirts. **Lab:** threat 22.7.

**Exotic upgrade:** Tallow Plunger (the exotic Rendered Lard pump I, in place of the pump piece). Lard stacks +15% damage. Lab: +1.4 threat.

### Reactor Kettle
**Furnace** (runs hot and holds the trigger, Boiler Room). "Whistles in the glow." Rad Syrup and Ion Gel on the boil: shields pop, burns land at once, and the pressure valve does the rest. Built for the Glow Crater.

- Boiler Room set: a bigger heat cap, more damage above half heat, and with 4 pieces PRESSURE COOKER: reaching 100% heat starts 3 s with no overheat damage and +50% flow, then the heat drops to zero (once every 45 s).
- Flashpoint keystone: a stack's whole burn lands the instant it hits. Nothing lingers, so longer burns do nothing here.
- Rad Syrup hits softly at first, but its stacks grow the longer they cling. With it, Ion Gel for shields. Home: the Glow Crater.
- Lance nozzle (a narrow needle with longer burns) and Capillary line (fewer, meaner, cooler drops).
- Booster pump (+50% pressure), Distiller filter (stack damage x1.5) and Insulated shroud (holds 60% more heat). Tanks: a Rack (+1 tank mount) and Jerrycans (+40% capacity).

| Slot | Part |
|---|---|
| Fuel Line | Capillary |
| Nozzle | Lance |
| Tank Chassis | Rack |
| Pump | Booster |
| Igniter | Flashpoint (keystone) |
| Filter | Distiller |
| Shroud & Grip | Insulated |
| Tank Mod | Jerrycan on every tank |

**Set:** 4 Boiler Room pieces. **Fuels:** Rad Syrup, Ion Gel. **Affixes:** Potent, Ionized, Cooled. **Home:** Glow Crater. **Lab:** threat 22.6.

**Exotic upgrade:** Storm Altar (the exotic Ion Gel tank chassis III, in place of the tank chassis piece). The first 80 Ion Gel units from a full tank deal +100%, and its tank refills twice as fast while another fires. Lab: +0.6 threat.

### Bargain Bog
**Miser** (cheap fuel, long burns, cool head, Thrift Shop). "Burns forever. Costs nothing." Swamp Napalm that lasts forever, every fifth unit free, and a distill that doubles the bite. The best deal in the Bloat Marsh, maybe anywhere.

- Thrift Shop set: faster regen, one unit in five free, and with 4 pieces LEFTOVERS: an empty tank refills 40% at once (every 20 s), and +100% stack damage.
- Double Distill keystone: +130% stack damage, for 1.5 fuel a unit and a little more heat.
- Swamp Napalm burns longest of any fuel, and hardest on meat. With it, Lard for flesh. Home: the Bloat Marsh.
- Lance nozzle (a narrow needle with longer burns), Gusher line (+35% flow) and Stoker igniter (big targets take more the more they carry).
- Booster pump (+50% pressure) and Vent Cowl (let go above half heat for a burst). Tanks: a Rack (+1 tank mount) and Drip Bottles (small tanks that refill fast).

| Slot | Part |
|---|---|
| Fuel Line | Gusher |
| Nozzle | Lance |
| Tank Chassis | Rack |
| Pump | Booster |
| Igniter | Stoker |
| Filter | Double Distill (keystone) |
| Shroud & Grip | Vent Cowl |
| Tank Mod | Drip Bottle on every tank |

**Set:** 4 Thrift Shop pieces. **Fuels:** Swamp Napalm, Rendered Lard. **Affixes:** Boggy, Greasy, Molten. **Home:** Bloat Marsh. **Lab:** threat 27.7.

**Exotic upgrade:** Swamp-King Shroud (the exotic Swamp Napalm shroud & grip III, in place of the shroud & grip piece). Napalm runs 80% cooler, and mutants burning with it slow 20%. Lab: +1.4 threat.

### Sunday Roast
**Miser** (cheap fuel, long burns, cool head, Slow Cooker). "Low and slow. Mostly slow for them." Lard and Napalm, a wide bloom and every fifth drop on the house. Stacks pile up on everything outside the cone. The Sewer Delta's favorite recipe.

- Slow Cooker set: +25% burn duration, stacks on mutants outside the cone deal +45%, and with 4 pieces SIMMER: every 5th unit is free, every 10th applies 2 stacks, and all fuels deal +57%.
- No keystone: the lab wore Slow Cooker in all seven slots.
- Rendered Lard runs cool and sticks to flesh. With it, Napalm for long burns. Home: the Sewer Delta.
- Bloom nozzle (twice the cone, +220% up close), Gusher line (+35% flow) and Stoker igniter (big targets take more the more they carry).
- Booster pump (+50% pressure), Coarse Mesh (one unit in five free) and Vent Cowl (let go above half heat for a burst). Tanks: a Rack (+1 tank mount) and Drip Bottles (small tanks that refill fast).

| Slot | Part |
|---|---|
| Fuel Line | Gusher |
| Nozzle | Bloom |
| Tank Chassis | Rack |
| Pump | Booster |
| Igniter | Stoker |
| Filter | Coarse Mesh |
| Shroud & Grip | Vent Cowl |
| Tank Mod | Drip Bottle on every tank |

**Set:** 4 Slow Cooker pieces. **Fuels:** Rendered Lard, Swamp Napalm. **Affixes:** Boggy, Greasy, Molten. **Home:** Sewer Delta. **Lab:** threat 26.3.

**Exotic upgrade:** Bog Strainer (the exotic Swamp Napalm filter I, in place of the filter piece). Napalm +25% vs shields and armor. Lab: +1.2 threat.

### Slow Cooker
**Miser** (cheap fuel, long burns, cool head, Slow Cooker). "Set it and forget it." Put it on, walk away, come back to dinner. Stacks build up on everything outside the cone, and every fifth drop is on the house.

- Slow Cooker set: +25% burn duration, stacks on mutants outside the cone deal +45%, and with 4 pieces SIMMER: every 5th unit is free, every 10th applies 2 stacks, and all fuels deal +57%.
- Double Distill keystone: +130% stack damage, for 1.5 fuel a unit and a little more heat.
- Swamp Napalm burns longest of any fuel, and hardest on meat. With it, Lard for flesh. Home: the Sewer Delta.
- Bloom nozzle (twice the cone, +220% up close), Gusher line (+35% flow) and Stoker igniter (big targets take more the more they carry).
- Booster pump (+50% pressure) and Vent Cowl (let go above half heat for a burst). Tanks: a Rack (+1 tank mount) and Drip Bottles (small tanks that refill fast).

| Slot | Part |
|---|---|
| Fuel Line | Gusher |
| Nozzle | Bloom |
| Tank Chassis | Rack |
| Pump | Booster |
| Igniter | Stoker |
| Filter | Double Distill (keystone) |
| Shroud & Grip | Vent Cowl |
| Tank Mod | Drip Bottle on every tank |

**Set:** 4 Slow Cooker pieces. **Fuels:** Swamp Napalm, Rendered Lard. **Affixes:** Potent, Boggy, Recycling. **Home:** Sewer Delta. **Lab:** threat 26.2.

**Exotic upgrade:** Swamp-King Shroud (the exotic Swamp Napalm shroud & grip III, in place of the shroud & grip piece). Napalm runs 80% cooler, and mutants burning with it slow 20%. Lab: +1.4 threat.

### Frost Miser
**Miser** (cheap fuel, long burns, cool head, Glacier Works). "Pennies per mutant. Ice in its veins." Why burn money when you can burn mutants? Cool, cheap and patient, with a filter that doubles the bite of every drop.

- Glacier Works set: longer burns, burning mutants slow down, and with 4 pieces GLACIER: every fuel runs 40% cooler.
- Double Distill keystone: +130% stack damage, for 1.5 fuel a unit and a little more heat.
- Swamp Napalm burns longest of any fuel, and hardest on meat. With it, Lard for flesh. Home: the Sewer Delta.
- Bloom nozzle (twice the cone, +220% up close), Capillary line (fewer, meaner, cooler drops) and Stoker igniter (big targets take more the more they carry).
- Booster pump (+50% pressure) and Vent Cowl (let go above half heat for a burst). Tanks: a Rack (+1 tank mount) and Primer Cells (the first 25 units from a full tank hit +60% harder).

| Slot | Part |
|---|---|
| Fuel Line | Capillary |
| Nozzle | Bloom |
| Tank Chassis | Rack |
| Pump | Booster |
| Igniter | Stoker |
| Filter | Double Distill (keystone) |
| Shroud & Grip | Vent Cowl |
| Tank Mod | Primer Cell on every tank |

**Set:** 4 Glacier Works pieces. **Fuels:** Swamp Napalm, Rendered Lard. **Affixes:** Boggy, Potent, Greasy. **Home:** Sewer Delta. **Lab:** threat 25.6.

**Exotic upgrade:** Schmaltz Altar (the exotic Rendered Lard tank chassis III, in place of the tank chassis piece). The first 80 Lard units from a full tank deal +100%, and its tank refills twice as fast while another fires. Lab: +1.1 threat.

### Bathtub Special
**Miser** (cheap fuel, long burns, cool head, Thrift Shop). "Free refills. Some restrictions apply." Rocket Hooch from the bathtub, Thermite for the plating, and a Shoggoth Bladder that refills on every kill. Hit hard, kill often, never run dry.

- Thrift Shop set: faster regen, one unit in five free, and with 4 pieces LEFTOVERS: an empty tank refills 40% at once (every 20 s), and +100% stack damage.
- Shoggoth Bladder keystone on the first tank: every kill its fuel makes refills 2 units.
- Rocket Hooch hits hardest of any fuel, on everything, but runs hot and burns short. With it, Thermite for armor. Home: the Smelter Pits.
- Bloom nozzle (twice the cone, +220% up close), Gusher line (+35% flow) and Smoulder igniter (burns last 60% longer).
- Booster pump (+50% pressure), Distiller filter (stack damage x1.5) and Vent Cowl (let go above half heat for a burst). Tanks: a Rack (+1 tank mount).

| Slot | Part |
|---|---|
| Fuel Line | Gusher |
| Nozzle | Bloom |
| Tank Chassis | Rack |
| Pump | Booster |
| Igniter | Smoulder |
| Filter | Distiller |
| Shroud & Grip | Vent Cowl |
| Tank Mod | Shoggoth Bladder (keystone) on the first tank, Drip Bottle on the rest |

**Set:** 4 Thrift Shop pieces. **Fuels:** Rocket Hooch, Thermite Slurry. **Affixes:** Potent, Molten, Sticky. **Home:** Smelter Pits. **Lab:** threat 25.5.

**Exotic upgrade:** Rocket Crown (the exotic Rocket Hooch igniter III, in place of the igniter piece; the fuel becomes Smuggler's Hooch). STILL HOT: Hooch units also apply a stack of the fuel fired before them; Hooch stacks +60% damage. Lab: +1.2 threat.

### Cold Forge
**Miser** (cheap fuel, long burns, cool head, Glacier Works). "Freezes the tank. Melts the armor." Thermite strips the plating, the glacier slows everything down, and the warmer the grip the harder it hits. Built for the Tank Graveyard.

- Glacier Works set: longer burns, burning mutants slow down, and with 4 pieces GLACIER: every fuel runs 40% cooler.
- Fever Grip keystone: +1% stack damage for every 4% heat. Keep it warm, but overheating skips your armor.
- Thermite Slurry eats armor: double damage on plating. With it, Lard for flesh. Home: the Tank Graveyard.
- Bloom nozzle (twice the cone, +220% up close), Capillary line (fewer, meaner, cooler drops) and Stoker igniter (big targets take more the more they carry).
- Booster pump (+50% pressure) and Distiller filter (stack damage x1.5). Tanks: a Rack (+1 tank mount) and Drip Bottles (small tanks that refill fast).

| Slot | Part |
|---|---|
| Fuel Line | Capillary |
| Nozzle | Bloom |
| Tank Chassis | Rack |
| Pump | Booster |
| Igniter | Stoker |
| Filter | Distiller |
| Shroud & Grip | Fever Grip (keystone) |
| Tank Mod | Drip Bottle on every tank |

**Set:** 4 Glacier Works pieces. **Fuels:** Thermite Slurry, Rendered Lard. **Affixes:** Potent, Molten, Sticky. **Home:** Tank Graveyard. **Lab:** threat 24.6.

**Exotic upgrade:** Forge-Heart Aorta (the exotic Thermite Slurry fuel line III, in place of the fuel line piece). Thermite kills refill 3 units, an empty Thermite tank refills 40% at once (every 20 s), and the first 60 Thermite units from a full tank deal +40%; Thermite stacks +30% damage. Lab: +0.5 threat.

### Thrift Shop Special
**Miser** (cheap fuel, long burns, cool head, Thrift Shop). "One tank. One trigger. No refunds." Everything in this gun was somebody else's, and now it's yours. One big tank of Lard that refills itself, and a filter that makes every drop count twice.

- Thrift Shop set: faster regen, one unit in five free, and with 4 pieces LEFTOVERS: an empty tank refills 40% at once (every 20 s), and +100% stack damage.
- Double Distill keystone: +130% stack damage, for 1.5 fuel a unit and a little more heat.
- Rendered Lard runs cool and sticks to flesh. One fuel, nothing else. Home: the Smokehouse Outskirts.
- Lance nozzle (a narrow needle with longer burns), Capillary line (fewer, meaner, cooler drops) and Smoulder igniter (burns last 60% longer).
- Siphon pump (refills the tank while it fires) and Heatsink shroud (sheds heat 60% faster). Tanks: a Saddle Tank (one mount, triple the capacity and regen) and Primer Cells (the first 25 units from a full tank hit +60% harder).

| Slot | Part |
|---|---|
| Fuel Line | Capillary |
| Nozzle | Lance |
| Tank Chassis | Saddle Tank |
| Pump | Siphon |
| Igniter | Smoulder |
| Filter | Double Distill (keystone) |
| Shroud & Grip | Heatsink |
| Tank Mod | Primer Cell on every tank |

**Set:** 4 Thrift Shop pieces. **Fuels:** Rendered Lard. **Affixes:** Greasy, Molten, Recycling. **Home:** Smokehouse Outskirts. **Lab:** threat 24.3.

**Exotic upgrade:** Schmaltz Shroud (the exotic Rendered Lard shroud & grip III, in place of the shroud & grip piece). Lard runs 80% cooler, and mutants burning with it slow 20%. Lab: +1.6 threat.

### Neon Simmer
**Miser** (cheap fuel, long burns, cool head, Slow Cooker). "Simmers shields." Ion Gel on a slow simmer: a wide cone, long burns and a Shoggoth that refills on every kill. The Neon Strip's shields go soft by the second.

- Slow Cooker set: +25% burn duration, stacks on mutants outside the cone deal +45%, and with 4 pieces SIMMER: every 5th unit is free, every 10th applies 2 stacks, and all fuels deal +57%.
- Shoggoth Bladder keystone on the first tank: every kill its fuel makes refills 2 units.
- Ion Gel pops shields: more than double damage on them. With it, Lard for flesh. Home: the Neon Strip.
- Fan nozzle (a wide cone, +35% stack damage), Capillary line (fewer, meaner, cooler drops) and Smoulder igniter (burns last 60% longer).
- Booster pump (+50% pressure), Coarse Mesh (one unit in five free) and Vent Cowl (let go above half heat for a burst). Tanks: a Rack (+1 tank mount).

| Slot | Part |
|---|---|
| Fuel Line | Capillary |
| Nozzle | Fan |
| Tank Chassis | Rack |
| Pump | Booster |
| Igniter | Smoulder |
| Filter | Coarse Mesh |
| Shroud & Grip | Vent Cowl |
| Tank Mod | Shoggoth Bladder (keystone) on the first tank, Drip Bottle on the rest |

**Set:** 4 Slow Cooker pieces. **Fuels:** Ion Gel, Rendered Lard. **Affixes:** Potent, Boggy, Greasy. **Home:** The Neon Strip. **Lab:** threat 24.2.

**Exotic upgrade:** Drippings Sieve (the exotic Rendered Lard filter II, in place of the filter piece). Lard deals at least x1.0 against health, shields and armor, and +25% vs health. Lab: +0.9 threat.

### Glacier Glow
**Miser** (cheap fuel, long burns, cool head, Glacier Works). "Slow, cold and radioactive." Rad Syrup clings longer when nothing can run. The glacier slows them, the syrup gets worse, and the warm grip makes every stack meaner.

- Glacier Works set: longer burns, burning mutants slow down, and with 4 pieces GLACIER: every fuel runs 40% cooler.
- Fever Grip keystone: +1% stack damage for every 4% heat. Keep it warm, but overheating skips your armor.
- Rad Syrup hits softly at first, but its stacks grow the longer they cling. With it, Lard for flesh. Home: the Fungal Bog.
- Lance nozzle (a narrow needle with longer burns), Capillary line (fewer, meaner, cooler drops) and Smoulder igniter (burns last 60% longer).
- Siphon pump (refills the tank while it fires) and Coarse Mesh (one unit in five free). Tanks: a Rack (+1 tank mount) and Jerrycans (+40% capacity).

| Slot | Part |
|---|---|
| Fuel Line | Capillary |
| Nozzle | Lance |
| Tank Chassis | Rack |
| Pump | Siphon |
| Igniter | Smoulder |
| Filter | Coarse Mesh |
| Shroud & Grip | Fever Grip (keystone) |
| Tank Mod | Jerrycan on every tank |

**Set:** 4 Glacier Works pieces. **Fuels:** Rad Syrup, Rendered Lard. **Affixes:** Potent, Greasy, Sticky. **Home:** Fungal Bog. **Lab:** threat 23.9.

**Exotic upgrade:** Schmaltz Aorta (the exotic Rendered Lard fuel line III, in place of the fuel line piece). LEFTOVERS: an empty Lard tank refills 50% at once (every 20 s); Lard stacks +50% damage. Lab: +0.6 threat.

### Ice Capacitor
**Miser** (cheap fuel, long burns, cool head, Glacier Works). "Cold. Collected. Crackling." Ion Gel on ice: a wide cone, a cool head, a tank that refills while it fires and a distill that doubles the bite. Reactor Row's shields don't stand a chance.

- Glacier Works set: longer burns, burning mutants slow down, and with 4 pieces GLACIER: every fuel runs 40% cooler.
- Double Distill keystone: +130% stack damage, for 1.5 fuel a unit and a little more heat.
- Ion Gel pops shields: more than double damage on them. With it, Lard for flesh. Home: Reactor Row.
- Fan nozzle (a wide cone, +35% stack damage), Capillary line (fewer, meaner, cooler drops) and Smoulder igniter (burns last 60% longer).
- Siphon pump (refills the tank while it fires) and Heatsink shroud (sheds heat 60% faster). Tanks: a Rack (+1 tank mount) and Drip Bottles (small tanks that refill fast).

| Slot | Part |
|---|---|
| Fuel Line | Capillary |
| Nozzle | Fan |
| Tank Chassis | Rack |
| Pump | Siphon |
| Igniter | Smoulder |
| Filter | Double Distill (keystone) |
| Shroud & Grip | Heatsink |
| Tank Mod | Drip Bottle on every tank |

**Set:** 4 Glacier Works pieces. **Fuels:** Ion Gel, Rendered Lard. **Affixes:** Potent, Ionized, Greasy. **Home:** Reactor Row. **Lab:** threat 23.9.

**Exotic upgrade:** Schmaltz Throat (the exotic Rendered Lard nozzle III, in place of the nozzle piece). Lard stacks deal +50% on mutants outside the cone and +30% beyond 300 px. Lab: +1.2 threat.

### Secondhand Isotope
**Miser** (cheap fuel, long burns, cool head, Thrift Shop). "Pre-owned. Still glowing." Somebody's old reactor fuel in a somebody's old gun. Wide cone, long burns, and every fifth drop free. The Junk Bazaar threw in the gloves.

- Thrift Shop set: faster regen, one unit in five free, and with 4 pieces LEFTOVERS: an empty tank refills 40% at once (every 20 s), and +100% stack damage.
- No keystone: the lab wore Thrift Shop in all seven slots.
- Rad Syrup hits softly at first, but its stacks grow the longer they cling. With it, Lard for flesh. Home: the Junk Bazaar.
- Fan nozzle (a wide cone, +35% stack damage), Capillary line (fewer, meaner, cooler drops) and Smoulder igniter (burns last 60% longer).
- Booster pump (+50% pressure), Coarse Mesh (one unit in five free) and Heatsink shroud (sheds heat 60% faster). Tanks: a Rack (+1 tank mount) and Drip Bottles (small tanks that refill fast).

| Slot | Part |
|---|---|
| Fuel Line | Capillary |
| Nozzle | Fan |
| Tank Chassis | Rack |
| Pump | Booster |
| Igniter | Smoulder |
| Filter | Coarse Mesh |
| Shroud & Grip | Heatsink |
| Tank Mod | Drip Bottle on every tank |

**Set:** 4 Thrift Shop pieces. **Fuels:** Rad Syrup, Rendered Lard. **Affixes:** Potent, Pressurized, Greasy. **Home:** The Junk Bazaar. **Lab:** threat 23.4.

**Exotic upgrade:** Drippings Sieve (the exotic Rendered Lard filter II, in place of the filter piece). Lard deals at least x1.0 against health, shields and armor, and +25% vs health. Lab: +1.4 threat.

### Crock-Pot Fryer
**Miser** (cheap fuel, long burns, cool head, Slow Cooker). "Set it, forget it, sell it." Long, slow burns from a wide cone, a tank that refills while it fires, and a Shoggoth that refills it on every kill. Comes back as fried cuts.

- Slow Cooker set: +25% burn duration, stacks on mutants outside the cone deal +45%, and with 4 pieces SIMMER: every 5th unit is free, every 10th applies 2 stacks, and all fuels deal +57%.
- Shoggoth Bladder keystone on the first tank: every kill its fuel makes refills 2 units.
- Fryer Oil's kills drop fried cuts, which sell for more. With it, Lard for flesh. Home: the Dead Drive-In.
- Fan nozzle (a wide cone, +35% stack damage), Capillary line (fewer, meaner, cooler drops) and Smoulder igniter (burns last 60% longer).
- Siphon pump (refills the tank while it fires), Coarse Mesh (one unit in five free) and Heatsink shroud (sheds heat 60% faster). Tanks: a Rack (+1 tank mount).

| Slot | Part |
|---|---|
| Fuel Line | Capillary |
| Nozzle | Fan |
| Tank Chassis | Rack |
| Pump | Siphon |
| Igniter | Smoulder |
| Filter | Coarse Mesh |
| Shroud & Grip | Heatsink |
| Tank Mod | Shoggoth Bladder (keystone) on the first tank, Drip Bottle on the rest |

**Set:** 4 Slow Cooker pieces. **Fuels:** Fryer Oil, Rendered Lard. **Affixes:** Potent, Pressurized, Sticky. **Home:** Dead Drive-In. **Lab:** threat 22.9.

**Exotic upgrade:** Drippings Sieve (the exotic Rendered Lard filter II, in place of the filter piece). Lard deals at least x1.0 against health, shields and armor, and +25% vs health. Lab: +1.1 threat.

### Lardolier
**Juggler** (many tanks, many swaps, Bandolier). "The fastest draw in the marsh." Lard, Napalm and Thermite across your chest, a swap within a second for free, and a bloom that cooks everything close. It's mostly Lard, and it's very good.

- Bandolier set: an extra tank mount (up to 4), idle tanks refill much faster, and with 4 pieces QUICK DRAW: a swap within a second of the last is instant and refunds 10 units.
- No keystone: the lab wore Bandolier in all seven slots.
- Rendered Lard runs cool and sticks to flesh. With it, Napalm for long burns and Thermite for armor. Home: the Bloat Marsh.
- Bloom nozzle (twice the cone, +220% up close), Gusher line (+35% flow) and Flash igniter (+50% stack damage, shorter burns).
- Booster pump (+50% pressure), Catalyst filter (+35% vs shields and armor) and Vent Cowl (let go above half heat for a burst). Tanks: a Carousel (0.1 s swaps that hit harder right after) and Drip Bottles (small tanks that refill fast).

| Slot | Part |
|---|---|
| Fuel Line | Gusher |
| Nozzle | Bloom |
| Tank Chassis | Carousel |
| Pump | Booster |
| Igniter | Flash |
| Filter | Catalyst |
| Shroud & Grip | Vent Cowl |
| Tank Mod | Drip Bottle on every tank |

**Set:** 4 Bandolier pieces. **Fuels:** Rendered Lard, Swamp Napalm, Thermite Slurry. **Affixes:** Pressurized, Greasy, Sticky. **Home:** Bloat Marsh. **Lab:** threat 29.8.

**Exotic upgrade:** Jelly Maw (the exotic Swamp Napalm nozzle II, in place of the nozzle piece). When a mutant burning with Napalm dies, its burn jumps to 2 nearby mutants (a quarter of its stacks). Lab: +0.7 threat.

### Bog Bandolier
**Juggler** (many tanks, many swaps, Bandolier). "Quick draws from a sticky holster." Napalm, Lard and Thermite in a quick-draw harness, and Blood Line keeps it firing when they all run dry. The Fungal Bog never saw it coming.

- Bandolier set: an extra tank mount (up to 4), idle tanks refill much faster, and with 4 pieces QUICK DRAW: a swap within a second of the last is instant and refunds 10 units.
- Blood Line keystone: with the tank empty it keeps firing at full flow, paid for in armor, then HP. Watch the bar.
- Swamp Napalm burns longest of any fuel, and hardest on meat. With it, Lard for flesh and Thermite for armor. Home: the Fungal Bog.
- Bloom nozzle (twice the cone, +220% up close) and Flash igniter (+50% stack damage, shorter burns).
- Booster pump (+50% pressure), Catalyst filter (+35% vs shields and armor) and Vent Cowl (let go above half heat for a burst). Tanks: a Carousel (0.1 s swaps that hit harder right after) and Drip Bottles (small tanks that refill fast).

| Slot | Part |
|---|---|
| Fuel Line | Blood Line (keystone) |
| Nozzle | Bloom |
| Tank Chassis | Carousel |
| Pump | Booster |
| Igniter | Flash |
| Filter | Catalyst |
| Shroud & Grip | Vent Cowl |
| Tank Mod | Drip Bottle on every tank |

**Set:** 4 Bandolier pieces. **Fuels:** Swamp Napalm, Rendered Lard, Thermite Slurry. **Affixes:** Pressurized, Greasy, Sticky. **Home:** Fungal Bog. **Lab:** threat 28.3.

**Exotic upgrade:** Jelly Maw (the exotic Swamp Napalm nozzle II, in place of the nozzle piece). When a mutant burning with Napalm dies, its burn jumps to 2 nearby mutants (a quarter of its stacks). Lab: +1.3 threat.

### Moonshine Run Express
**Juggler** (many tanks, many swaps, Moonshine Run). "Three stills. One trigger. No speed limit." Swap fast and every drop drags the last fuel along with it. Hooch hits hard, Lard handles flesh, Thermite handles plating, and the Shoggoth refills on every kill.

- Moonshine Run set: tanks +50% capacity, swapping fires +60% flow for 2 s, and with 4 pieces STILL HOT: every unit also applies a stack of the fuel fired before it, and +60% stack damage.
- Shoggoth Bladder keystone on the first tank: every kill its fuel makes refills 2 units.
- Rocket Hooch hits hardest of any fuel, on everything, but runs hot and burns short. With it, Lard for flesh and Thermite for armor. Home: the Smokehouse Outskirts.
- Bloom nozzle (twice the cone, +220% up close), Gusher line (+35% flow) and Flash igniter (+50% stack damage, shorter burns).
- Booster pump (+50% pressure), Catalyst filter (+35% vs shields and armor) and Vent Cowl (let go above half heat for a burst). Tanks: a Carousel (0.1 s swaps that hit harder right after).

| Slot | Part |
|---|---|
| Fuel Line | Gusher |
| Nozzle | Bloom |
| Tank Chassis | Carousel |
| Pump | Booster |
| Igniter | Flash |
| Filter | Catalyst |
| Shroud & Grip | Vent Cowl |
| Tank Mod | Shoggoth Bladder (keystone) on the first tank, Primer Cell on the rest |

**Set:** 4 Moonshine Run pieces. **Fuels:** Rocket Hooch, Rendered Lard, Thermite Slurry. **Affixes:** Boggy, Sticky, Recycling. **Home:** Smokehouse Outskirts. **Lab:** threat 27.8.

**Exotic upgrade:** Forge-Heart Shroud (the exotic Thermite Slurry shroud & grip III, in place of the shroud & grip piece). Thermite runs 80% cooler, and mutants burning with it slow 20%. Lab: +1.9 threat.

### The Bandolier
**Juggler** (many tanks, many swaps, Bandolier). "Four fuels. Fastest draw in the wasteland." Four tanks across your chest and a hand that never stops. Swap twice in a second and the second swap is instant and pays you back. There's a fuel for everything out there.

- Bandolier set: an extra tank mount (up to 4), idle tanks refill much faster, and with 4 pieces QUICK DRAW: a swap within a second of the last is instant and refunds 10 units.
- Shoggoth Bladder keystone on the first tank: every kill its fuel makes refills 2 units.
- Thermite Slurry eats armor: double damage on plating. With it, Lard for flesh, Ion Gel for shields and Napalm for long burns. Home: the Smokehouse Outskirts.
- Bloom nozzle (twice the cone, +220% up close), Gusher line (+35% flow) and Flash igniter (+50% stack damage, shorter burns).
- Booster pump (+50% pressure), Distiller filter (stack damage x1.5) and Vent Cowl (let go above half heat for a burst). Tanks: a Rack (+1 tank mount).

| Slot | Part |
|---|---|
| Fuel Line | Gusher |
| Nozzle | Bloom |
| Tank Chassis | Rack |
| Pump | Booster |
| Igniter | Flash |
| Filter | Distiller |
| Shroud & Grip | Vent Cowl |
| Tank Mod | Shoggoth Bladder (keystone) on the first tank, Drip Bottle on the rest |

**Set:** 4 Bandolier pieces. **Fuels:** Thermite Slurry, Rendered Lard, Ion Gel, Swamp Napalm. **Affixes:** Pressurized, Sticky, Molten. **Home:** Smokehouse Outskirts. **Lab:** threat 27.6.

**Exotic upgrade:** Jelly Maw (the exotic Swamp Napalm nozzle II, in place of the nozzle piece). When a mutant burning with Napalm dies, its burn jumps to 2 nearby mutants (a quarter of its stacks). Lab: +0.6 threat.

### Fryer Run
**Juggler** (many tanks, many swaps, Moonshine Run). "Every swap a fresh batch." Fryer Oil, Lard and Napalm on a carousel: every drop drags the last fuel along and every kill refills the Shoggoth. Comes back as fried cuts.

- Moonshine Run set: tanks +50% capacity, swapping fires +60% flow for 2 s, and with 4 pieces STILL HOT: every unit also applies a stack of the fuel fired before it, and +60% stack damage.
- Shoggoth Bladder keystone on the first tank: every kill its fuel makes refills 2 units.
- Fryer Oil's kills drop fried cuts, which sell for more. With it, Lard for flesh and Napalm for long burns. Home: the Flesh Farms.
- Bloom nozzle (twice the cone, +220% up close), Gusher line (+35% flow) and Flash igniter (+50% stack damage, shorter burns).
- Booster pump (+50% pressure), Catalyst filter (+35% vs shields and armor) and Heatsink shroud (sheds heat 60% faster). Tanks: a Carousel (0.1 s swaps that hit harder right after).

| Slot | Part |
|---|---|
| Fuel Line | Gusher |
| Nozzle | Bloom |
| Tank Chassis | Carousel |
| Pump | Booster |
| Igniter | Flash |
| Filter | Catalyst |
| Shroud & Grip | Heatsink |
| Tank Mod | Shoggoth Bladder (keystone) on the first tank, Drip Bottle on the rest |

**Set:** 4 Moonshine Run pieces. **Fuels:** Fryer Oil, Rendered Lard, Swamp Napalm. **Affixes:** Potent, Greasy, Sticky. **Home:** The Flesh Farms. **Lab:** threat 27.5.

**Exotic upgrade:** Swamp-King Crown (the exotic Swamp Napalm igniter III, in place of the igniter piece; the fuel becomes Frost Napalm). FROST NAPALM: Napalm runs cold (no heat) and mutants burning with it slow 15%. Lab: +2.0 threat.

### Static Bandolier
**Juggler** (many tanks, many swaps, Bandolier). "Quick draw, quicker shields-down." Ion Gel first, Lard and Thermite behind it, and a swap within a second is free. Built for the Static Fields' quick draws.

- Bandolier set: an extra tank mount (up to 4), idle tanks refill much faster, and with 4 pieces QUICK DRAW: a swap within a second of the last is instant and refunds 10 units.
- No keystone: the lab wore Bandolier in all seven slots.
- Ion Gel pops shields: more than double damage on them. With it, Lard for flesh and Thermite for armor. Home: the Static Fields.
- Bloom nozzle (twice the cone, +220% up close), Gusher line (+35% flow) and Flash igniter (+50% stack damage, shorter burns).
- Booster pump (+50% pressure), Catalyst filter (+35% vs shields and armor) and Vent Cowl (let go above half heat for a burst). Tanks: a Carousel (0.1 s swaps that hit harder right after) and Primer Cells (the first 25 units from a full tank hit +60% harder).

| Slot | Part |
|---|---|
| Fuel Line | Gusher |
| Nozzle | Bloom |
| Tank Chassis | Carousel |
| Pump | Booster |
| Igniter | Flash |
| Filter | Catalyst |
| Shroud & Grip | Vent Cowl |
| Tank Mod | Primer Cell on every tank |

**Set:** 4 Bandolier pieces. **Fuels:** Ion Gel, Rendered Lard, Thermite Slurry. **Affixes:** Greasy, Pressurized, Sticky. **Home:** Static Fields. **Lab:** threat 27.3.

**Exotic upgrade:** Capacitor Maw (the exotic Ion Gel nozzle II, in place of the nozzle piece). When a mutant burning with Ion Gel dies, its burn jumps to 2 nearby mutants (a quarter of its stacks). Lab: +0.6 threat.

### Three-Still Special
**Juggler** (many tanks, many swaps, Moonshine Run). "Three fuels, one trigger." Lard, Thermite and Ion Gel on a carousel: every drop drags the last fuel along, and a fast swap fires a burst. The Food Court's busiest stall.

- Moonshine Run set: tanks +50% capacity, swapping fires +60% flow for 2 s, and with 4 pieces STILL HOT: every unit also applies a stack of the fuel fired before it, and +60% stack damage.
- No keystone: the lab wore Moonshine Run in all seven slots.
- Rendered Lard runs cool and sticks to flesh. With it, Thermite for armor and Ion Gel for shields. Home: the Food Court.
- Bloom nozzle (twice the cone, +220% up close), Gusher line (+35% flow) and Flash igniter (+50% stack damage, shorter burns).
- Booster pump (+50% pressure), Catalyst filter (+35% vs shields and armor) and Heatsink shroud (sheds heat 60% faster). Tanks: a Carousel (0.1 s swaps that hit harder right after) and Drip Bottles (small tanks that refill fast).

| Slot | Part |
|---|---|
| Fuel Line | Gusher |
| Nozzle | Bloom |
| Tank Chassis | Carousel |
| Pump | Booster |
| Igniter | Flash |
| Filter | Catalyst |
| Shroud & Grip | Heatsink |
| Tank Mod | Drip Bottle on every tank |

**Set:** 4 Moonshine Run pieces. **Fuels:** Rendered Lard, Thermite Slurry, Ion Gel. **Affixes:** Potent, Pressurized, Sticky. **Home:** The Food Court. **Lab:** threat 26.9.

**Exotic upgrade:** Crucible Maw (the exotic Thermite Slurry nozzle II, in place of the nozzle piece). When a mutant burning with Thermite dies, its burn jumps to 2 nearby mutants (a quarter of its stacks). Lab: +0.3 threat.

### Fry-Up Cocktail
**Juggler** (many tanks, many swaps, Cocktail Hour). "Pools of oil, pools of fire." Fryer Oil, Lard and Thermite in the shaker: every swap leaves a burning pool, and the Shoggoth refills on every kill. Comes back as fried cuts.

- Cocktail Hour set: swaps take half the time, each different fuel you swap to adds +10% (up to +30%), and with 4 pieces MOLOTOV MIX: each swap leaves a pool of the last fuel, and all fuels deal +120%.
- Shoggoth Bladder keystone on the first tank: every kill its fuel makes refills 2 units.
- Fryer Oil's kills drop fried cuts, which sell for more. With it, Lard for flesh and Thermite for armor. Home: the Junk Bazaar.
- Bloom nozzle (twice the cone, +220% up close), Gusher line (+35% flow) and Flash igniter (+50% stack damage, shorter burns).
- Booster pump (+50% pressure), Catalyst filter (+35% vs shields and armor) and Vent Cowl (let go above half heat for a burst). Tanks: a Carousel (0.1 s swaps that hit harder right after).

| Slot | Part |
|---|---|
| Fuel Line | Gusher |
| Nozzle | Bloom |
| Tank Chassis | Carousel |
| Pump | Booster |
| Igniter | Flash |
| Filter | Catalyst |
| Shroud & Grip | Vent Cowl |
| Tank Mod | Shoggoth Bladder (keystone) on the first tank, Drip Bottle on the rest |

**Set:** 4 Cocktail Hour pieces. **Fuels:** Fryer Oil, Rendered Lard, Thermite Slurry. **Affixes:** Greasy, Boggy, Sticky. **Home:** The Junk Bazaar. **Lab:** threat 26.5.

**Exotic upgrade:** Forge-Heart Shroud (the exotic Thermite Slurry shroud & grip III, in place of the shroud & grip piece). Thermite runs 80% cooler, and mutants burning with it slow 20%. Lab: +1.1 threat.

### Last Call
**Juggler** (many tanks, many swaps, Cocktail Hour). "Every swap's a round." Rocket Hooch, Lard and Thermite: swap fast, leave pools of fire, and the Hooch hits hard on everything. The Drive-In's last show of the night.

- Cocktail Hour set: swaps take half the time, each different fuel you swap to adds +10% (up to +30%), and with 4 pieces MOLOTOV MIX: each swap leaves a pool of the last fuel, and all fuels deal +120%.
- No keystone: the lab wore Cocktail Hour in all seven slots.
- Rocket Hooch hits hardest of any fuel, on everything, but runs hot and burns short. With it, Lard for flesh and Thermite for armor. Home: the Dead Drive-In.
- Bloom nozzle (twice the cone, +220% up close), Gusher line (+35% flow) and Flash igniter (+50% stack damage, shorter burns).
- Booster pump (+50% pressure), Catalyst filter (+35% vs shields and armor) and Heatsink shroud (sheds heat 60% faster). Tanks: a Carousel (0.1 s swaps that hit harder right after) and Primer Cells (the first 25 units from a full tank hit +60% harder).

| Slot | Part |
|---|---|
| Fuel Line | Gusher |
| Nozzle | Bloom |
| Tank Chassis | Carousel |
| Pump | Booster |
| Igniter | Flash |
| Filter | Catalyst |
| Shroud & Grip | Heatsink |
| Tank Mod | Primer Cell on every tank |

**Set:** 4 Cocktail Hour pieces. **Fuels:** Rocket Hooch, Rendered Lard, Thermite Slurry. **Affixes:** Potent, Pressurized, Sticky. **Home:** Dead Drive-In. **Lab:** threat 26.3.

**Exotic upgrade:** Moonshine Maw (the exotic Rocket Hooch nozzle II, in place of the nozzle piece). When a mutant burning with Hooch dies, its burn jumps to 2 nearby mutants (a quarter of its stacks). Lab: +0.4 threat.

### Bog Run
**Juggler** (many tanks, many swaps, Moonshine Run). "Runs on swamp and spite." Napalm, Lard and Thermite on the run, a burst on every swap, and Blood Line keeps it firing when the tanks are dry. Pay in armor, then in blood.

- Moonshine Run set: tanks +50% capacity, swapping fires +60% flow for 2 s, and with 4 pieces STILL HOT: every unit also applies a stack of the fuel fired before it, and +60% stack damage.
- Blood Line keystone: with the tank empty it keeps firing at full flow, paid for in armor, then HP. Watch the bar.
- Swamp Napalm burns longest of any fuel, and hardest on meat. With it, Lard for flesh and Thermite for armor. Home: the Smokehouse Outskirts.
- Fan nozzle (a wide cone, +35% stack damage) and Flash igniter (+50% stack damage, shorter burns).
- Accumulator pump (a strong first burst), Catalyst filter (+35% vs shields and armor) and Heatsink shroud (sheds heat 60% faster). Tanks: a Carousel (0.1 s swaps that hit harder right after) and Drip Bottles (small tanks that refill fast).

| Slot | Part |
|---|---|
| Fuel Line | Blood Line (keystone) |
| Nozzle | Fan |
| Tank Chassis | Carousel |
| Pump | Accumulator |
| Igniter | Flash |
| Filter | Catalyst |
| Shroud & Grip | Heatsink |
| Tank Mod | Drip Bottle on every tank |

**Set:** 4 Moonshine Run pieces. **Fuels:** Swamp Napalm, Rendered Lard, Thermite Slurry. **Affixes:** Potent, Pressurized, Sticky. **Home:** Smokehouse Outskirts. **Lab:** threat 26.1.

**Exotic upgrade:** Drippings Maw (the exotic Rendered Lard nozzle II, in place of the nozzle piece). When a mutant burning with Lard dies, its burn jumps to 2 nearby mutants (a quarter of its stacks). Lab: +0.9 threat.

### Cocktail Hour
**Juggler** (many tanks, many swaps, Cocktail Hour). "Shaken, stirred, and set on fire." Every swap leaves a pool of the last fuel burning on the floor, and every tank fires at once. Ion for shields, Lard for flesh, Thermite for plating.

- Cocktail Hour set: swaps take half the time, each different fuel you swap to adds +10% (up to +30%), and with 4 pieces MOLOTOV MIX: each swap leaves a pool of the last fuel, and all fuels deal +120%.
- Gatling Drum keystone: every unit fires from every tank at once, each with its own fuel, and every tank refills like an idle one. Double heat, so mind the gauge.
- Ion Gel pops shields: more than double damage on them. With it, Lard for flesh and Thermite for armor. Home: the Glow Crater.
- Bloom nozzle (twice the cone, +220% up close), Gusher line (+35% flow) and Flash igniter (+50% stack damage, shorter burns).
- Booster pump (+50% pressure), Catalyst filter (+35% vs shields and armor) and Vent Cowl (let go above half heat for a burst). Tanks: Primer Cells (the first 25 units from a full tank hit +60% harder).

| Slot | Part |
|---|---|
| Fuel Line | Gusher |
| Nozzle | Bloom |
| Tank Chassis | Gatling Drum (keystone) |
| Pump | Booster |
| Igniter | Flash |
| Filter | Catalyst |
| Shroud & Grip | Vent Cowl |
| Tank Mod | Primer Cell on every tank |

**Set:** 4 Cocktail Hour pieces. **Fuels:** Ion Gel, Rendered Lard, Thermite Slurry. **Affixes:** Pressurized, Sticky, Ionized. **Home:** Glow Crater. **Lab:** threat 25.9.

**Exotic upgrade:** Capacitor Maw (the exotic Ion Gel nozzle II, in place of the nozzle piece). When a mutant burning with Ion Gel dies, its burn jumps to 2 nearby mutants (a quarter of its stacks). Lab: +2.4 threat.

### Rust Belt Cocktail
**Juggler** (many tanks, many swaps, Cocktail Hour). "Shaken, then melted." Thermite first for Rust Flats' plating, Lard and Ion behind it, and every swap leaves a burning pool. Mix well, serve hot.

- Cocktail Hour set: swaps take half the time, each different fuel you swap to adds +10% (up to +30%), and with 4 pieces MOLOTOV MIX: each swap leaves a pool of the last fuel, and all fuels deal +120%.
- No keystone: the lab wore Cocktail Hour in all seven slots.
- Thermite Slurry eats armor: double damage on plating. With it, Lard for flesh and Ion Gel for shields. Home: the Rust Flats.
- Bloom nozzle (twice the cone, +220% up close), Gusher line (+35% flow) and Flash igniter (+50% stack damage, shorter burns).
- Booster pump (+50% pressure), Catalyst filter (+35% vs shields and armor) and Vent Cowl (let go above half heat for a burst). Tanks: a Carousel (0.1 s swaps that hit harder right after) and Primer Cells (the first 25 units from a full tank hit +60% harder).

| Slot | Part |
|---|---|
| Fuel Line | Gusher |
| Nozzle | Bloom |
| Tank Chassis | Carousel |
| Pump | Booster |
| Igniter | Flash |
| Filter | Catalyst |
| Shroud & Grip | Vent Cowl |
| Tank Mod | Primer Cell on every tank |

**Set:** 4 Cocktail Hour pieces. **Fuels:** Thermite Slurry, Rendered Lard, Ion Gel. **Affixes:** Potent, Molten, Sticky. **Home:** Rust Flats. **Lab:** threat 25.2.

**Exotic upgrade:** Schmaltz Shroud (the exotic Rendered Lard shroud & grip III, in place of the shroud & grip piece). Lard runs 80% cooler, and mutants burning with it slow 20%. Lab: +0.5 threat.

*Lab results: a robot pig wearing every part at T4 Malevolent with near-perfect rolls, starting at threat 20 at the build's home map. Your results may vary. Not a toy. Do not refuel near open flame. Do not taste the Lard. Mutants were harmed in the making of this advertisement.

## Saves, settings and logs

### Saves
- **3 save slots.** The main menu's **SAVE SLOTS** shows what each holds (runs, best threat, Energy Sprinkles, time played, cats, parts, when it was saved) and has **PLAY**, **NEW GAME**, **IMPORT** and **DELETE** for each. Starting over or deleting a slot that holds a game asks first; deleting takes its backup and career journal too. The game opens on the slot you played last, and the Esc menu names it. Settings and the BALANCE menu are shared by every slot.
- Every version keeps its own saves, so updating never breaks your game. **IMPORT** brings the newest older version's save into a slot (that save itself isn't changed); the main menu also offers it while the slot in use has no progress.
- The game saves after every change, keeping the save before as a backup. Settings has the window size, fullscreen, fire effects, an FPS counter, VSync and a frame limit.

### The BALANCE menu
- In the Esc menu and on the main menu: a slider for each of these, to try the game tuned your way: enemy density, enemy toughness, enemy speed, elite chance, early waves: share of spawns, late waves: share of spawns, toughness make-up for fewer mutants, start threat: levels below your best, reputation rate, counter speed, meat price, glut after (minutes of selling), crafting cost: energy sprinkles, crafting cost: scrap metal, crafting cost: mutant bits, crafting cost: chemicals, crafting cost: blueprint shards, crafting cost: mutagen, exotic blueprints: favor price, crafting cost: tallow brick, crafting cost: napalm amber, crafting cost: slag heart, crafting cost: ion crystal, crafting cost: still copper, crafting cost: isotope seed, crafting cost: crackling.
- **LOCK** a number (or press **Space** over it) so a stray drag can't move it (RESET and RESET ALL leave it alone). Changes apply at once (mutant changes from the next wave), are saved with this version, and are written to the debug log at the start of every session, whenever they change, and with every run.

### Frame rate
- **VSYNC** on (the default) draws one frame per screen refresh, so on a 60 Hz screen the FPS counter sits at 60 however much room the machine has to spare. Turn it off to see what each fire setting really costs (the picture may tear while it's off).
- **FRAME LIMIT** caps the frames a second (30, 60, 120, 144, 165, 240); **NONE** with VSync off runs flat out. A limit keeps the graphics card cooler and quieter.
- The FPS counter is green near the limit, yellow below it and red when slow. A graphics driver set to force VSync on keeps the game at the refresh rate whatever the setting says.

### Fire effects
Every setting fires the same flamethrower: damage comes from the cone and the burn rules, never from how the fire is drawn.
- **LIVE ULTRA** (the default): the fire simulation plus burning fuel (the jet sprays fuel that catches as it flies, so it rolls and billows), fire light on the ground, the pig and the mutants, heat haze, embers and sparks, scorch marks and glowing coals where things burned, and puddles that keep burning with flames on them.
- **LIVE HIGH**: the fire simulation (the flame splashes off mutants, bends as you sweep, rains burning fuel). **LIVE LOW**: the same, chunkier and lighter on the graphics chip. **CLASSIC**: the old particle flame.
- If the game can't keep up (under 48 frames a second while firing, or under 80% of a lower frame limit) it steps down by itself (ULTRA to HIGH, HIGH to LOW), says so, and remembers it.

### Logs (for bug reports)
- With **Settings > DEBUG LOG** on (the default), each session writes a text file to a **logs** folder next to the game: your kit, every run in detail, hub actions, the crew and any errors. **OPEN LOG FOLDER** opens it.
- The result screen's **COPY RUN LOG** copies just that run, ready to paste.
- **Settings > DUMP CAREER** writes your whole career (every run, milestones, how the kit changed, hour by hour) to one file in the same folder.
- The Windows download is a debug build so the log catches every error; it can run a little slower than a release build would.

### This guide
- It's in the game (**F1**) and on the download page as **WIKI.md** (https://github.com/LichIndex/MMM-Malevolent-Meat-Master/blob/HEAD/WIKI.md), and both are written from the game's data by each build, so they always match the version you have.
