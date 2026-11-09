# Malevolent Meat Master

A pig with a flamethrower roasts mutants for meat. This page only hosts the Windows test builds.

**[The wiki](WIKI.md)** explains everything: runs and drops, the flamethrower, every loot lane, set, fuel and mutant, the market, cats and the endgame. It's written from the game's data with every release, and the same pages are in the game (**F1**).

## Download

**[Download v0.9.31 for Windows](https://github.com/LichIndex/MMM-Malevolent-Meat-Master/releases/download/v0.9.31/MalevolentMeatMaster_v0.9.31_windows.zip)** (43 MB). Older versions are on the [Releases page](https://github.com/LichIndex/MMM-Malevolent-Meat-Master/releases).

1. Unzip it anywhere (the Desktop is fine).
2. Double-click `MalevolentMeatMaster_v0.9.31.exe`. Nothing else to install.
3. Windows may say *Windows protected your PC*, because the game isn't code-signed. Click **More info**, then **Run anyway**. It only asks the first time.

It needs 64-bit Windows 10 or 11 and a graphics card with OpenGL 3.3 (almost any from the last ten years). If it opens to a black window or closes at once, update the graphics driver. If it runs slowly, set **Settings > FIRE EFFECTS** to LIVE HIGH, LIVE LOW or CLASSIC (it starts on LIVE ULTRA, the richest fire, and steps down by itself if your computer can't keep up). To see your real frame rate, turn **VSYNC** off in Settings (with it on, the FPS counter stops at your screen's refresh rate).

## How to play

You're a pig with a flamethrower, roasting mutants for meat. Pick a destination on the **Map** tab and press **FIGHT**. Aim with the mouse and hold the left button to burn. Fire stacks burn damage on whatever it touches, so sweep the horde and keep them all burning. Swap fuel tanks with Q, the mouse wheel or 1–4. Watch your heat: let it max out and the gun starts hurting you, so ease off the trigger to cool down. Dead mutants drop raw meat, materials, sauce ingredients and sometimes gear. The longer you stay, the higher the threat climbs, and the tougher the mutants and the better the loot. When you've had enough, press **E** to call the food truck and survive until it arrives. Or press **R** and let the Shoggoth drive: it plays the run for you and calls the truck, for 1 cut of meat in 5 (the Map tab sets when it calls the truck). If you extract, you keep everything. If you die, you lose the run's meat and gear plus part of your materials.

Back at the Smokehouse you turn the meat into money. In the Kitchen, brew a sauce from your ingredients and put it on your raw meat; raw meat spoils over time and sauced meat doesn't. The smoker on the food truck then smokes it, fast during a fight and at half speed between runs, even with the game closed. The truck's counter sells the cooked meat in real time, even while you're out fighting, to whichever faction's turf it's parked on. A sauce that matches their taste pays more. That money (Energy Sprinkles), plus your materials, buys new fuel stills, better gun parts at the Workbench and upgrades around the yard. You equip it all on the **Loadout** tab, push to higher threats, and work your way up to top-tier gear and the Infested endgame. Stray cats line up at the cat counter for a high five, and you can **hire** up to three of them: give them spare parts on the **Crew** tab and send them on expeditions of 15 minutes to 8 hours that run even while the game is closed. A part is worn by one fighter at a time, you or one cat.

| | |
|---|---|
| Aim | Mouse |
| Burn | Hold left mouse (or Space) |
| Swap tanks | Q, mouse wheel, 1–4 |
| Call the truck (extract) | E |
| Let the Shoggoth drive (it eats 1 cut of meat in 5) / take the controls back | R |
| The Magic 8-Ball on / off (back-to-back Shoggoth runs; hire it on the Map tab) | B |
| Pause / menu | Esc |
| Flamethrower sheet | Tab |
| Fullscreen | F11 or Alt+Enter |
| The guide (the wiki, in the game) | F1 |

## Your save

Saves are in `%APPDATA%\MalevolentMeatMaster_v0931\` (paste that into the Explorer address bar). Each version keeps its own save: when you get a newer version, press its main menu's **IMPORT** button (it offers your newest older save) before you start, to bring your progress along.

## Sending a debug log

The game keeps a log of each session in a **logs** folder next to the .exe (Settings > OPEN LOG FOLDER opens it). After playing, send the newest `mmm_...log` file, or press **COPY RUN LOG** on the result screen after a run and paste it into a message. **Settings > DUMP CAREER** writes your whole career so far (every run, milestone and crew trip, hour by hour) to a `career_...log` file in the same folder. The logs record the game only (your runs, the Smokehouse, errors, plus your graphics card and screen size), nothing else from your computer.

This download is a debug build so the log can catch every error. That costs about 10% more processor time, which can make it run a little slower on a weaker computer.

This is a test build: the numbers, art and sounds are placeholders and will change.
