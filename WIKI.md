# Malevolent Meat Master v0.7.7: the wiki

Everything in the game, from the game's own data (written by the build you can download, so the numbers match it). The same pages are in the game: press **F1**, or **GUIDE** in the Smokehouse or the Esc menu. [Download the game](https://github.com/LichIndex/MMM-Malevolent-Meat-Master#readme).

- [Start here](#start-here)
- [Runs, threat and drops](#runs-threat-and-drops)
- [The flamethrower](#the-flamethrower)
- [Parts and loot lanes](#parts-and-loot-lanes)
- [Sets](#sets)
- [Fuels and stills](#fuels-and-stills)
- [Mutants](#mutants)
- [Destinations and factions](#destinations-and-factions)
- [Meat, sauce and selling](#meat-sauce-and-selling)
- [The Smokehouse](#the-smokehouse)
- [Cats and the crew](#cats-and-the-crew)
- [Endgame](#endgame)
- [Saves, settings and logs](#saves-settings-and-logs)

## Start here

You're a pig with a flamethrower. You fight mutants for their meat, get out alive, turn the meat into sauced, smoked barbecue and sell it from your food truck. The money and materials you bring home build a better flamethrower, so you can go deeper, where the meat is worth more.

### The loop
1. **Fight.** Pick a destination on the **Map** tab and press **FIGHT**. Hold the left mouse button to burn: every drop of fuel that lands sets a burn on the mutant, and the burns pile up. The threat climbs a level every 30 s, and so does what they drop.
2. **Get out.** Press **E** to call the food truck. It takes 30 s to arrive; survive until then and everything comes home. Die and the run's meat and parts are lost, with part of its materials.
3. **Sauce.** In **Production > Kitchen**, brew a sauce from a recipe and ingredients and put it on your raw meat. Raw meat spoils over real time; sauced meat doesn't.
4. **Smoke.** The smoker on the food truck smokes sauced meat: a full load in 90 s of a run, and at half that speed between runs, even with the game closed.
5. **Sell.** The truck's counter sells cooked meat in real time (also while you fight or the game is closed) to whoever's turf it's parked on. A sauce that suits their taste pays more. This is where **Energy Sprinkles** (◆, the money) come from.
6. **Build.** Fuel stills, better parts at the Workbench, sets, yard upgrades. Then push deeper.

### Controls

| Action | Key |
|---|---|
| Aim | Mouse (or W/S, arrow keys) |
| Burn (hold) | Left mouse or Space |
| Next tank / pick a tank | Q or the mouse wheel / 1 to 4 |
| Call the food truck | E |
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
- Fight at the **Smokehouse Outskirts**, call the truck while you're still comfortable, and bring the meat home. A short run that gets out beats a long one that doesn't.
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
- **E** calls the food truck. It arrives in 30 s; the fight (and the threat) goes on until it does. Survive and everything comes home.
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
- Press **R** (or the Shoggoth button at the bottom left of a run) and the Shoggoth drives: it aims, burns, vents before the heat warning, swaps tanks and calls the truck. Press R again to take over. It's the same pilot that tests every build.
- **Its fee:** it eats 1 cut of meat in 5 of what drops while it drives. Nothing else.
- On the Map tab, under the destination: **ON/OFF** (runs start with it driving) and **when it calls the truck**: AUTO (2 threat levels under what your kit should hold there), only when hurt, or at a threat you pick. It always calls it at 5 HP or less.

### The Magic 8-Ball
- Hire it on the Map tab (no fee) and switch it on there or with **B** anywhere. 8 s after you're back in the Smokehouse (with no menu open) it starts a run at the turf of the faction with the **lowest reputation**, with the Shoggoth driving (its truck setting and each place's dials apply; the Shoggoth's fee too). The result screen goes back by itself after 6 s and it goes again.
- A death switches it off. B in a run switches it for the runs after this one.

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
| Boggy | Burn duration | Swamp Napalm | +20% to +45% | Junk |
| Bulging | Tank capacity | All fuels | +8% to +20% | Junk |
| Cooled | Heat | All fuels | -15% to -6% | Junk |
| Greasy | Stack damage | Rendered Lard | +10% to +25% | Junk |
| Ionized | Vs shields | Ion Gel | +20% to +45% | Junk |
| Molten | Vs armor | Thermite Slurry | +20% to +45% | Junk |
| Potent | Stack damage | All fuels | +6% to +15% | Junk |
| Pressurized | Flow | All fuels | +5% to +12% | Junk |
| Recycling | Fuel regen | All fuels | +0.6 to +1.6 | Junk |
| Smooth | Heat | Rocket Hooch | -40% to -20% | Junk |
| Sticky | Burn duration | All fuels | +8% to +20% | Junk |

### Behaviors

| Behavior | What it does | From quality |
|---|---|---|
| Chilling | Burning mutants are slowed 20% | Mutated |
| Spreading | Burns jump to 2 nearby mutants when a burning mutant dies | Mutated |
| Toxic | Kills leave a small toxic cloud that burns for a quarter second | Mutated |
| Volatile | Burning kills explode, putting 1 stack on mutants nearby | Mutated |

### Keystones
Rare T4 parts that break one rule, at a cost. They only drop (from threat 15; more in Infested runs) and are never crafted.

| Keystone | Slot | Rule | Cost | Builds | Drops from |
|---|---|---|---|---|---|
| Afterburner | Pump | Above 75% heat, flow x1.6 instead of the usual slowdown to x0.7 | Overheat damage x2 | Furnace | threat 15 |
| Backdraft Ring | Nozzle | A 360-degree ring of fire, 390 px out: no aiming, nothing slips past the sides | +30% heat, and range bonuses from lanes and sets do nothing | Brawler | threat 15 |
| Blood Line | Fuel Line | With the tank empty, keeps firing at full flow | Every 15 units cost the pig 1 armor, then 1 HP; it will kill you | Furnace, Brawler | threat 15 |
| Double Distill | Filter | +130% stack damage | Each unit costs 2 fuel and makes 30% more heat | Lancer, Furnace | threat 15 |
| Fever Grip | Shroud & Grip | +1% stack damage per 4% heat | Overheating hits the pig's HP directly, skipping armor | Furnace | threat 15 |
| Flashpoint | Igniter | A stack's whole burn damage lands the instant it is applied | Nothing lingers: Spreading, Toxic, Hellmouth and burn duration do nothing | Lancer, Brawler | threat 15 |
| Gatling Drum | Tank Chassis | Each unit fires from every mounted tank at once, each applying its own fuel's stack, and every tank refills like an idle one | Drains every tank together, and each unit makes double heat | Juggler | threat 15 |
| Shoggoth Bladder | Tank Mod | Refills 1 unit for every kill its fuel makes | No passive regen at all | Brawler | threat 15 |

### Malevolent parts
The top quality. Salvage only rolls it in Infested runs (past threat 21), each level past that adding 2 quality steps; until then it tops out at Mutated. You can still craft one, or upgrade a part's quality at the Workbench (the last step, Mutated to Malevolent, costs ×0.4).

## Sets

- Every set has a piece for each of the seven slots. Wearing **2, 3 and 4 pieces** turns on its three bonuses. A piece is a normal part of its tier and slot (it rolls a lane and affixes too).
- **Where they drop:** set pieces come from salvage crates (5% of them) and elites (40%). A set piece found at a destination comes 70% of the time from a set that drops there; the rest from any common set, and 5% from a rare one.
- **Blueprints:** breaking a piece down (Loadout > Stash) gives 10 + 2 × its quality Blueprint Shards. A set's blueprint costs 30 Shards (Workbench > SETS), then you craft its pieces for ◆ and materials. Faction reputation gives some blueprints too, and Hellmouth's needs one found Hellmouth piece first (or the Glow Cult's top reputation).

### Deep Fryer
Brawler build · Fryer Oil · drops at the Sewer Delta
- **2 pieces:** Fryer Oil kills drop +25% raw cuts
- **3 pieces:** +40% stack damage within 220 px
- **4 pieces:** BATTERED: mutants within 220 px take +1% per stack on them (up to +60%), and fried cuts sell for +50%

### Grease Fire
Brawler build · Rendered Lard · drops at the Smokehouse Outskirts
- **2 pieces:** Lard stacks +85% damage
- **3 pieces:** Lard kills splash 1 stack nearby
- **4 pieces:** GREASE BOMB: burning Lard kills explode for 2 stacks in a wide blast

### Pit Boss
Brawler build · all fuels · drops anywhere
- **2 pieces:** +15% stack damage within 220 px
- **3 pieces:** Each hit the pig takes vents 30 heat as a burst around him
- **4 pieces:** BURNING MAN: with 10+ mutants within 220 px, flow +30% and the pig takes 30% less damage

### Meltdown
Lancer build · Rad Syrup · drops at the Glow Crater
- **2 pieces:** Rad stacks age 25% faster
- **3 pieces:** Elites take +10% from Rad Syrup
- **4 pieces:** CRITICAL MASS: a mutant carrying 120+ Rad stacks takes +50% from every burn

### Steeple Works
Lancer build · all fuels · drops anywhere
- **2 pieces:** +10% burn duration
- **3 pieces:** Mutants beyond 300 px take +5% stack damage
- **4 pieces:** DEADEYE: the first unit to hit an elite each second applies 2 stacks

### Tesla Coilworks
Lancer build · Ion Gel · drops at the Glow Crater
- **2 pieces:** Ion Gel burns 10% longer
- **3 pieces:** Breaking a shield stuns for 1 s
- **4 pieces:** ARC GEL: every Ion Gel hit chains to 2 nearby mutants

### Boiler Room
Furnace build · Rocket Hooch · drops at the Smokehouse Outskirts
- **2 pieces:** Heat cap +10%
- **3 pieces:** Above 50% heat, Hooch stacks +5% damage
- **4 pieces:** PRESSURE COOKER: reaching 100% heat starts 3 s with no overheat damage and +50% flow, then heat drops to 0 (once per 45 s)

### Foundry Rig
Furnace build · Thermite Slurry · drops at the Rust Flats
- **2 pieces:** Thermite burns 10% longer
- **3 pieces:** Thermite stacks +10% damage
- **4 pieces:** MOLTEN SLAG: Thermite kills leave a brief burning pool

### Hellmouth (rare)
Furnace build · all fuels · drops anywhere
- **2 pieces:** All fuels +90% stack damage
- **3 pieces:** All fuels +20% burn duration and 30% less heat
- **4 pieces:** HELLMOUTH: stacks stop expiring while the mutant stays in the cone

### Glacier Works
Miser build · Swamp Napalm · drops at the Sewer Delta
- **2 pieces:** Napalm burns 20% longer
- **3 pieces:** Napalm-burning mutants slow 5%
- **4 pieces:** FROST NAPALM: runs cold (no heat) and slows burning mutants 10%

### Slow Cooker
Miser build · all fuels · drops anywhere
- **2 pieces:** +25% burn duration
- **3 pieces:** Stacks on mutants outside the cone deal +45% damage
- **4 pieces:** SIMMER: every 5th unit is free and every 10th applies 2 stacks; all fuels +57% stack damage

### Thrift Shop
Miser build · Rendered Lard · drops at the Smokehouse Outskirts
- **2 pieces:** Lard tank regen +3.5 units/s
- **3 pieces:** 20% of Lard units cost no fuel
- **4 pieces:** LEFTOVERS: an empty Lard tank refills 40% at once (once every 20 s); Lard stacks +140% damage

### Bandolier
Juggler build · all fuels · drops anywhere
- **2 pieces:** +1 tank mount on any chassis (up to 4)
- **3 pieces:** Inactive tanks regen 200% faster
- **4 pieces:** QUICK DRAW: a swap within 1 s of the last costs no swap time and refunds 10 units to the tank you left

### Cocktail Hour
Juggler build · all fuels · drops anywhere
- **2 pieces:** Swap time -50%
- **3 pieces:** Swapping to a different fuel gives +10% stack damage for 4 s, once per distinct fuel (up to +30%)
- **4 pieces:** MOLOTOV MIX: each swap leaves a 120 px pool of the last fuel, burning 1 stack per tick for 2 s; all fuels +120% stack damage

### Moonshine Run
Juggler build · Rocket Hooch · drops at the Smokehouse Outskirts
- **2 pieces:** Hooch tanks +50% capacity
- **3 pieces:** Swapping to Hooch fires +60% flow for 2 s
- **4 pieces:** STILL HOT: Hooch units also apply a stack of the fuel fired before them; Hooch stacks +60% damage

## Fuels and stills

Each fuel comes from its own **still** in the Production yard. Rendered Lard's still is there from the start; the others need a **blueprint**: reach the threat shown at that destination, then get out alive.

| Fuel | Still | Blueprint | Damage | vs health / shields / armor | Burn | Heat | Rule |  |
|---|---|---|---|---|---|---|---|---|
| Rendered Lard | Rendering Kettle | from the start | 1 | ×1 / ×0.5 / ×0.5 | ×1 | ×0.6 | - | Rendered from... best not to ask. Sticks to flesh, slides off metal. |
| Swamp Napalm | Bog-Gas Fermenter | Sewer Delta, threat 4 | 1 | ×1.35 / ×0.4 / ×0.5 | ×1.6 | ×0.8 | - | Gelled bog-gas. Burns forever, mostly on meat. |
| Thermite Slurry | Crucible Furnace | Rust Flats, threat 4 | 1 | ×0.7 / ×0.6 / ×2 | ×0.8 | ×1.2 | - | Eats through scrap plating like it owes money. |
| Ion Gel | Capacitor Stack | Glow Crater, threat 4 | 1 | ×0.7 / ×2.2 / ×0.6 | ×0.9 | ×1 | - | Crackling blue goop. Pops rad-shields like soap bubbles. |
| Rocket Hooch | Copper Moonshine Still | Smokehouse Outskirts, threat 8 | 1.4 | ×1.1 / ×1.1 / ×1.1 | ×0.6 | ×1.5 | - | Triple-distilled. Do not drink. Okay, maybe a sip. |
| Rad Syrup | Glow Vat | Glow Crater, threat 12 | 0.18 | ×1 / ×1 / ×0.8 | ×1.4 | ×0.7 | each stack deals +12% more for every second it has burned (up to +80%) | Sweet, sticky and glowing. The longer it clings, the worse it gets. |
| Fryer Oil | Deep-Fry Drum | Sewer Delta, threat 12 | 0.85 | ×1.2 / ×0.5 / ×0.6 | ×0.8 | ×1.3 | its kills drop cuts already fried: they skip the smoker and sell for +25% | Ten thousand batches deep. Whatever it kills comes out crispy. |

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
| Shambler | 16 | - | - | 46 | threat 0 | Shambler Shank | Mutant Bits | - |
| Skitter | 6 | - | - | 105 | threat 1 | Skitter Drumettes | Mutant Bits | Sewer Delta |
| Glowbag | 12 | 18 | - | 40 | threat 2 | Glowbag Belly | Chemicals | Glow Crater |
| Scrapper | 14 | - | 28 | 34 | threat 3 | Scrapper Ribs | Scrap Metal | Rust Flats |
| Tumor Hulk | 104 | - | 32 | 24 | threat 6 | Hulk Brisket | Scrap Metal, Mutant Bits | Sewer Delta |

- A destination's favourite mutants show up 2 threat levels early and more often.
- Shields and armor come off before health, so fuels and parts that break shells (vs shields, vs armor) matter more as those pools grow.

## Destinations and factions

### Destinations

#### Smokehouse Outskirts
Home turf. Balanced mutants, a neutral market that pays a flat 0.9x.
- **Unlock:** open from the start. **Market:** neutral (a flat ×0.9 for any sauce, no reputation).
- **Growth a level:** health ×1.17, armor ×1.17, shields ×1.17.
- **Sets:** Boiler Room, Grease Fire, Moonshine Run, Thrift Shop. **Still blueprints:** Copper Moonshine Still (threat 8).

#### Rust Flats
Rust Barons turf. Armor piles up fast; Scrapper country. Their scrap comes out of the furnace Molten.
- **Unlock:** opens at best threat 3. **Market:** Rust Barons turf.
- **Growth a level:** health ×1.12, armor ×1.28, shields ×1.1.
- **Common mutants:** Scrapper. **Extra drops:** Scrap Metal ×2.
- **Sets:** Foundry Rig. **Still blueprints:** Crucible Furnace (threat 4).

#### Glow Crater
Glow Cult turf. Shields everywhere; bring Ion Gel.
- **Unlock:** needs the food truck's engine at level 1. **Market:** Glow Cult turf.
- **Growth a level:** health ×1.18, armor ×1.1, shields ×1.24.
- **Common mutants:** Glowbag. **Extra drops:** Chemicals ×2.
- **Sets:** Meltdown, Tesla Coilworks. **Still blueprints:** Capacitor Stack (threat 4), Glow Vat (threat 12).

#### Sewer Delta
Sewer Kings turf. Meat-heavy mutants grow huge.
- **Unlock:** needs Rust Barons reputation 1. **Market:** Sewer Kings turf.
- **Growth a level:** health ×1.2, armor ×1.12, shields ×1.1.
- **Common mutants:** Tumor Hulk, Skitter. **Extra drops:** Mutant Bits ×2.
- **Sets:** Deep Fryer, Glacier Works. **Still blueprints:** Bog-Gas Fermenter (threat 4), Deep-Fry Drum (threat 12).

### Factions
Each faction owns a destination's market. They like a taste (spicy / sweet / savory, 0 to 5), pay ×1.25 for their favourite cut, and reward reputation. Reputation comes only from selling them a sauce that fits better than ×1; it doesn't raise prices, it unlocks things.

| Faction | Who | Turf | Ideal taste | Favourite cut | Reputation rewards |
|---|---|---|---|---|---|
| Rust Barons | Scrap warlords | Rust Flats | 4 / 1 / 3 | Scrapper Ribs | 1: Shows you the road into the Sewer Delta<br>2: Recipe: Baron's Brimstone Rub<br>3: Sells Glowberry Syrup (the Glow Cult loves it)<br>4: Foundry Rig blueprints |
| Glow Cult | Radioactive zealots | Glow Crater | 1 / 4 / 2 | Glowbag Belly | 1: Recipe: Halo Honey Glaze<br>2: Sells Marrow Butter (the Sewer Kings love it)<br>3: Tesla Coilworks blueprints<br>4: Hellmouth blueprints |
| Sewer Kings | Underground mutant royalty | Sewer Delta | 2 / 1 / 5 | Hulk Brisket | 1: Recipe: Royal Marrow Gravy<br>2: Sells Ghost Chili Paste (the Rust Barons love it)<br>3: Glacier Works blueprints<br>4: Grease Fire blueprints |

Reputation levels 1 to 4 need 20, 60, 150, 400 points. Three things earn it:
- **Fighting on their turf:** getting out of a run at a faction's destination earns 0.03 for every mutant killed there (an elite counts 3; an ordinary mutant counts for the ones it stands in for, see Runs). A threat-16 run brings home about 84.
- **The crew:** a cat's trip there earns 50% of the same.
- **Selling there:** a cut sold earns 2 × (fit - 1) points when the fit is over ×1.

## Meat, sauce and selling

### Cuts

| Cut | From | Base value | Favourite of |
|---|---|---|---|
| Skitter Drumettes | Skitter | ◆2 | - |
| Shambler Shank | Shambler | ◆4 | - |
| Glowbag Belly | Glowbag | ◆6 | Glow Cult |
| Scrapper Ribs | Scrapper | ◆7 | Rust Barons |
| Hulk Brisket | Tumor Hulk | ◆18 | Sewer Kings |

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

| Ingredient | Adds (spicy / sweet / savory) | Where |
|---|---|---|
| Rad Pepper | 2 / 0 / 0 | mutants and cats |
| Rust Salt | 1 / 0 / 1 | mutants and cats |
| Glow Honey | 1 / 2 / 0 | mutants and cats |
| Sludge Molasses | 0 / 2 / 1 | mutants and cats |
| Bone Marrow | 0 / 0 / 2 | mutants and cats |
| Mushroom Mash | 0 / 1 / 2 | mutants and cats |
| Glowberry Syrup | 0 / 4 / 1 | sold for ◆120 by Rust Barons (reputation 3); calico cats |
| Marrow Butter | 1 / 0 / 4 | sold for ◆120 by Glow Cult (reputation 2); calico cats |
| Ghost Chili Paste | 4 / 0 / 2 | sold for ◆120 by Sewer Kings (reputation 2); calico cats |

### Smoking
- The smoker holds 40 cuts, +40 per Smoker level. In a run it cooks (time survived / 90 s) of its load; if you die, the load comes out overcooked (×0.6).
- Between runs (and with the game closed) it smokes at 50% that speed, a batch at a time, loading itself from your sauced meat (the cuts worth most to the faction you sell to first).

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
- **Loadouts:** save the gun under a name and put it back on later; copy or import a build code to share one.
- **Stash:** filter by worn, unworn, locked, tier, slot or lane. **Lock** a part to protect it. **Scrap** a part (or SCRAP SHOWN for everything the filters show, or SCRAP JUNK) for materials; a set piece is broken down for Blueprint Shards instead. Parts you or a cat wear, locked parts and parts in a saved loadout are never scrapped.
- **Scrapping** returns 50% of the part's crafting materials (by quality) plus 1 + 2 per tier Scrap Metal, teaches you its lane, records its affixes in the **Library**, and gives Mutagen for Mutated (1) and Malevolent (5) parts.
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

### The yard and the shack

| Upgrade | Where | What it does | Max level | First level |
|---|---|---|---|---|
| Workbench | Shack | Crafted parts roll higher qualities. | 8 | ◆250 + 5 Scrap Metal |
| Sauce Kitchen | Shack | More brewing pots (1 + level/2) and faster brews. | 8 | ◆200 + 6 Mutant Bits |
| Freezer | Shack | Each level halves how fast raw meat spoils. | 5 | ◆300 + 8 Scrap Metal + 4 Chemicals |
| Pantry | Shack | +20 ingredient storage per type per level. | 8 | ◆150 + 4 Mutant Bits |
| Storage Shed | Yard | +150 storage for each material per level. | 8 | ◆200 + 8 Scrap Metal |
| Scrap Sifter | Yard | Sifts +6 Scrap Metal per hour per level. | 10 | ◆300 + 6 Scrap Metal |
| Rendering Vat | Yard | Renders +6 Mutant Bits per hour per level. | 10 | ◆300 + 6 Mutant Bits |
| Sludge Drip | Yard | Drips +6 Chemicals per hour per level. | 10 | ◆300 + 6 Chemicals |
| Catnip Plant | Yard | Cats arrive 25% faster per level. | 10 | ◆100 + 3 Mutant Bits |
| Smoker | Garage | +40 cuts cooked per run per level. | 10 | ◆250 + 6 Scrap Metal |
| Engine | Garage | Range: reach farther destinations. | 5 | ◆500 + 20 Scrap Metal |
| Serving Counter | Garage | Parked truck sells 50% faster per level. | 10 | ◆200 + 5 Mutant Bits |
| Spice Rack | Kitchen | Lets you dial Spicy up or down by 1 more per level. | 3 | ◆300 + 5 Chemicals |
| Sugar Press | Kitchen | Lets you dial Sweet up or down by 1 more per level. | 3 | ◆300 + 5 Mutant Bits |
| Stock Pot | Kitchen | Lets you dial Savory up or down by 1 more per level. | 3 | ◆300 + 5 Scrap Metal |
| Flavor Overdrive | Kitchen | Raises the taste ceiling past 5 for extreme fads. | 2 | ◆4,000 + 40 Chemicals |
| Bigger Counter | Cats | +5 cats can wait in line per level. | 6 | ◆150 + 3 Scrap Metal |

Prices in ◆ rise with each level; materials rise a step each level. Each material holds 150, +150 per Storage Shed level, and each ingredient 20, +20 per Pantry level (run loot can overfill these; vats and cats stop at them).

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

## Saves, settings and logs

### Saves
- Every version keeps its own save, so updating never breaks your game. The main menu offers to **import** the newest older save while the new one has no progress.
- The game saves after every change. Settings has the window size, fullscreen, fire effects, an FPS counter, VSync and a frame limit.

### The BALANCE menu
- In the Esc menu and on the main menu: a slider for each of these, to try the game tuned your way: enemy density, enemy toughness, enemy speed, elite chance, early waves: share of spawns, late waves: share of spawns, toughness make-up for fewer mutants, start threat: levels below your best, reputation rate, counter speed, meat price, glut after (minutes of selling), crafting cost: energy sprinkles, crafting cost: scrap metal, crafting cost: mutant bits, crafting cost: chemicals, crafting cost: blueprint shards, crafting cost: mutagen.
- **LOCK** a number so a stray drag can't move it (RESET and RESET ALL leave it alone). Changes apply at once (mutant changes from the next wave), are saved with this version, and are written to the debug log at the start of every session, whenever they change, and with every run.

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
