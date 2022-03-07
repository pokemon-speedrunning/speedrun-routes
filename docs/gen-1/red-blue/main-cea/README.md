<img align="left" src="https://i.imgur.com/uvKl6UX.gif">

# Pokemon Blue: Catch 'Em All

Autumn 2020 route & guide, last updated <ins>6 March 2022</ins>

## Before We Begin

Before doing runs of this category, it helps to be familiar with the following concepts, glitches, and techniques: <ins>(updated links welcome)</ins>

- [Item Underflow slots](https://glitchcity.wiki/Expanded_bag_item_documentation_(Generation_I))
- RNG Manipulation and [its lingo](https://pastebin.com/QdgbSu35)
- Trainer Fly
- Lol Glitch ("LG")
- Jack state
- Crazywarp
- Dsum manipulation

## Tools

The end of this document has additional resources which you may find useful for quick reference and in-depth routing.

- BobChao87's Pokedex Counter: [Windows](https://www.dropbox.com/s/0ep5qgbtlzp0h4h/PokedexCounter_v1.5.1_Windows.zip) | [Mac](https://www.dropbox.com/s/rssbtzbyf08nt37/PokedexCounter_v1.5.1_MacOSX.zip) | [Linux](https://www.dropbox.com/s/qu6iodxpgk2yspz/PokedexCounter_v1.5.1_Linux.zip) | [Browser](https://pco.bobchao87.com/#/app/main)
- Gambatte-Speedrun: [Windows & Mac](https://github.com/pokemon-speedrunning/gambatte-speedrun/releases) (emulator)

## Credits

Catch 'Em All has been speedrun and influenced by many people in the community, including but not limited to:

Ætienne, Besson, Chivu, Dabomstew, Decon, DerTeppich, Driekiann, eddaket, entrpntr, ExtraTricky, gifvex, Grogir, HorouIchigo, Keizaron, krazyd4n, luckytyphlosion, MrWint, PicklePlop, pokeguy, randalleatscheese, Sanqui, Shenanagans, Sidosh, SinH4, Sinstar, Smurfy, Snairam, stocchi, stringflow, TehHammerShow, VaultButler, werster,

and the good people at [PokemonSpeedruns](https://discord.gg/NjQFEkc), Glitch City Research Institute, & TASVideos.

ty!

## The Route

### Intro

<img align="right" src="https://i.imgur.com/qF5VB9p.png">

Clear save data before each attempt with Up + Select + B on the title screen.

Hard reset and [manipulate the trainer ID 54878](https://youtu.be/upzxy_0KW7A).

Hold the A or B button while clearing textboxes with the other while the text speed option is still the default.

Name the player a one-character name like `A` or `I`.

Name the rival `AaRRSA*`, where the asterisk is the character below S.

### Pallet Town

Open the start menu and set the options to Fast/Off/Shift.

Optional: Withdraw the Potion from the PC.

You will be choosing **Bulbasaur** as the starter for the run:

- Advanced runners can choose to manipulate Bulbasaur's DVs for optimal fights and an always-working special stat for the Brock Through Walls glitch later on. This is not recommended for beginners because the manipulation can be very difficult to execute if you do not have experience clearing textboxes during RNG manipulations.

- Beginner runners should take a random Bulbasaur instead. Note having a bad attack stat on your Bulbasaur can make you lose turns on the Rival and Weedle Guy fights, and the fastest setup for the Brock Through Walls glitch ("Pidgey Strats") only has a 9/16 (~56%) chance of working with a random Bulbasaur. 

Do **not** nickname the Bulbasaur, the name length is a requirement for the upcoming RNG manipulations to work.

To manipulate Bulbasaur: walk below the ball, then hold Up and press Start for a buffered save (required). Save, hard reset, and execute the manip's intro. After loading the save buffer a start flash, buffer A to interact with the ball, then while holding A or B clear every textbox perfectly, including the Yes for Bulbasaur and the No for nicknaming.

The IGT success rate on this manip is 56/60, but due to NPC timers the manip will fail an additional ~15% of the time.

More info can be [found on pastebin](https://pastebin.com/L14vtxJS) and a video with inputs can be [found here](https://youtu.be/VjLFyiX5JdA).

If you take a random Bulbasaur, you can check its stats at the start of the upcoming battle. Remember the special stat until it levels up in order to better know how likely the Bulbasaur will work for Pidgey Strats. The trainer ID is displayed in the bottom right corner of the stats screen so you can use this time to double check it as well.

### Rival Fight

Use Tackle on every turn. Heal up with a Potion if at 6 health or below. Winning the fight is required.

After defeating the Charmander you will level up to 6. If you did not manipulate the Bulbasaur now is the perfect time to check your special stat:

- 11 special -> 12 special at level 6 = reset (no chance of working)
- 11 special -> 13 special at level 6 = go for level 8 (50% chance to work)
- 12 special -> 13 special at level 6 = go for level 8 (100% chance to work)
- 12 special -> 14 special at level 6 = go for level 7 (33% chance to work)
- 13 special -> 14 special at level 6 = go for level 7 (100% chance to work)

Note regardless of the level 5 special stat, 13 at 6 will always try to go for level 8, and 14 at 6 will always try to go for level 7. A manipulated Bulbasaur will always go for level 7.

### Route 1

If you are going for level 8 you have to kill one encounter for experience: level 2-3 Rattata or level 2 Pidgey is ideal. This will level Bulbasaur from 6 to 8 after the Weedle Guy fight, skipping learning Leech Seed at level 7. Backup PP strats will want to kill additional encounters to reach level 7 before Weedle Guy in this case.

Run from all other encounters and deliver the parcel, then head back to Viridian.

### Viridian City

Enter Viridian Mart and buy:

- 3-5 Poke Balls
- 1 Parlyz Heal

Non-manipulated Bulbasaurs can pick up [the tree potion](https://gunnermaniac.com/pokeworld?map=1#54/166) before leaving, especially if they took damage while gaining experience, but another potion later will be faster to pick up.

### Route 2

<img align="right" src="https://i.imgur.com/MCefV9n.png">

Manipulate a **Pidgey** encounter & catch with `nopal(ab)` and the path shown. This Pidgey will always have HP that works for Brock Through Walls and will always catch, so a random Pidgey is not a viable alternative.

Ideally you extend the Pidgey manip into a **Caterpie** by clearing Pidgey's textboxes and Pokedex entry perfectly, then by moving `L R R U` afterwards. For beginners, or if an issue occurs, a solo Caterpie manip is an option once inside Viridian Forest.

### Viridian Forest

If you still need a Caterpie, use the [Non-extended Caterpie Manip](#rng-manipulations) inside the forest.

Otherwise, [follow this path](https://gunnermaniac.com/pokeworld?map=51#17/47/UUUURRRRRRRRRUUUUUUUUULUURRUAUAUAUAUAUAUAUAUAUAUAUALLUUUUUUUUUUULLALLALLALLADADADADADADADALLLLAUAUAUAUAUAUAUAUAUAUAUUULLLLLLDDDADADADADADADADADADADADADADADADADALLLLALLUUUU) because many tiles in Viridian Forest do not give encounters, which are indicated in green on this map.

Pick up the Antidote in both cases.

Non-manipulated Bulbasaurs can pick up [the hidden potion](https://gunnermaniac.com/pokeworld?local=51#1/18) before the trainer battle, especially if they took damage while gaining experience.

Spam Tackle to defeat Weedle Guy. Heal up with a Potion if at 3 health or below. Bulbasaur must have 16 special when it levels up after this battle. If so, continue to Pewter.

If not, you may be able to switch to PP strats to meet the requirements for Brock Through Walls instead of forfeiting the attempt. PP strats require Bulbasaur to:

- be level 8
- know Leech Seed in slot 1
- know Tackle in slot 2 with 16 PP remaining
- know Growl in slot 3 with 36 PP remaining

Find wild encounters until these conditions are met.

### Pewter City

Open the start menu and move the cursor to Save.

Enter Pewter Mart and buy:

- 1 Potion, unless you have one
- 1 Burn Heal
- 1 Escape Rope (into slot 6)

Brock Skip by holding Start after clearing the gym guy's last textbox with B, saving the game, and soft resetting.

After loading the save, walk to Route 3 and back to reload Pewter, then talk to the gym guy from the right. (PP strats need to swap Bulbasaur to the last party slot here before talking to the gym guy.)

<img align="right" src="https://i.imgur.com/pG2E8zC.png">

Hold B after the textboxes to be able to Brock Through Walls.

Navigate to Diglett's Cave. The simplest path to avoid the out-of-bounds area is to turn after the mart door, as shown in the picture.

### Diglett's Cave

Brock Through Walls ends upon entering the first cavern.

Save the game immediately after climbing down the ladder. Hard reset and use the [Diglett's Cave Manip](#rng-manipulations) with `pal` for no encounters, or use the [Dugtrio Manip](#rng-manipulations) with `pal` for an early Dugtrio (and 1 less space in Box 1).

### Vermilion City

Enter Vermilion Center. Deposit all Pokemon except Pidgey then heal before leaving.

<img align="right" src="https://i.imgur.com/m1QUvIU.png">

Go to Route 11 to do the deathfly manip with `nopal(ab)`. After respawning in Vermilion, talk to [the Dux girl](https://gunnermaniac.com/pokeworld?map=1#235/193) but say no to the trade, then flash the start menu before leaving her house. Returning to Route 11 will open the start menu and closing it will activate the Missingno deathfly. Stall (don't run) until you black out.

Repeat the above but this time toss 2 Escape Ropes before you save for the manip.

### Item Underflow #1

Enter Vermilion center after dying to the second Missingno. Walk to the PC to do the following menus.

Item PC:

- Deposit all Poke Balls
- Deposit all Potions
- Swap slot 3 with slot 5, then deposit all of an Escape Rope stack above

Item bag:

- Toss all of slot 1, twice
- Toss all-but-2 of slot 1
- Swap slot 1 with slot 2, twice; this achieves item underflow

* Swap slot 1 with badges (the slot below j. x[]9 in options)
* Swap the slot above options ("preoptions") with Master Ball x5 in warping
* Toss all-but-6 of the j. stack now in warping
* Swap "vtm" x64 in map data with options
* Swap vtm again with WA4 in rival name

Item PC:

- Withdraw all of slot 1, twice
- Withdraw all-but-2 of slot 1
- Swap slot 1 with slot 2; this achieves PC underflow

* Withdraw 1 from coins (the slot above the first nonzero j. quantity)
* Withdraw 36 Full Restores
* Withdraw 255 Master Balls from the x0 stack a few slots down
* Swap the Master Ball x1 with Pewter City script (Poke Ball x0 many slots down)
* Swap the Master Ball again with Route 4 script (down 1)
* Withdraw all-but-1 Pewter Gym script (down 1)
* Withdraw all-but-1 Route 3 script (up 2)
* Swap the Master Ball x1 with Route 11 script (down, 11 from Ultra Ball x0)
* Withdraw all-but-1 Route 20 script (down 2)
* Withdraw all-but-1 Route 16 script (up 1)
* Withdraw all-but-1 Route 21 script (up 4)
* Withdraw all-but-1 Route 17 script (up 1)

Leave the center using the left doormat tile to warp to Celadon, then enter the mart using the right door.

### Celadon Shopping

Head straight for the 2nd floor's left cashier.

Sell:

- All of the j. stack in slot 3

Buy:

- 20 Awakenings
- 2 Parlyz Heals
- 78 Ice Heals
- 1 Burn Heal
- 4 Antidotes
- 1 Super Repel
- 93 Revives
- 83 Super Potions
- 1 Great Ball

Take the stairs twice to the 4th floor.

Buy:

- 5 Leaf Stones
- 5 Water Stones
- 5 Thunderstones
- 99 Fire Stones
- 15 Fire Stones
- 1 Poke Doll

Your money must be **$49xx** after you buy all the items listed.

### Item Underflow #2

<img align="right" src="https://i.imgur.com/z3Cszl1.png">

Open the item bag while facing left on the tile **1** to your right:

- Swap Full Restores in slot 3 with slot 5
- Toss all of slot 3
- Toss all of slot 1, 18 times
- Toss all-but-2 of slot 1
- Swap slot 1 with slot 2, twice
- Swap Master Ball x0 with Bicycle in x coord
- Swap HM04 in TLP2 with Master Ball x0, now in x coord
- Walk **2** tiles left
- Teach HM02 to Pidgey
- Toss 38 from j. x255 in north connection

Walk **1** tile up and flash the start menu to enter the Safari Zone.

### Safari Zone

Take **4** steps to the right and open the item bag:

- Swap Poke Ball x0 in x coord with TM17 x42 in map ID
- Swap 9F in TID2 with Parlyz Heals in slot 5
- Swap 9F again with Full Restores in slot 3
- Hop on the bicycle

Bike **4** tiles to the right, then alternate left and right steps until you get an encounter. In the encounter do the following menu to LG for **Ekans**:

- Use 9F (then press Start)
- Move **3** tiles left
- Swap Ice Heals in slot 6 with CANCEL x[]5 ("jack") in rival name
- Swap vtm in rival name with HM04 in TLP2
- Swap TM18 x42 in x coord with Ice Heal x15 in width
- Toss 6 TM18s
- Flash map (close then open the start menu)
- Swap the TM18s back with Ice Heal x15
- Swap vtm back with the HM04, now in rival name
- Flash WA4 (press A on it so the Use/Toss window comes up, then press B)
- Throw a Master Ball from TID1 (down 2)

Cure Ekans with the Parlyz Heals directly below, then switch Ekans to slot 1.

For each of the following manips, you do not need to move before saving.

|||
|---|---|
| <img align="right" src="https://i.imgur.com/c8aTlei.png"> 1) Manip **Paras** with <ins>extra text while saving</ins>. **Use 9F** before catching. | <img align="right" src="https://i.imgur.com/Y1rvWlE.png"> 2) Manip **NidoranF** with `hop1`, `fsback`. **Use 9F** before catching. |
|||
| <img align="right" src="https://i.imgur.com/qKKPhwX.png"> 3) Manip **NidoranM** with `nopal(ab)`, `fsback`. **Use 9F** before catching. | <img align="right" src="https://i.imgur.com/UXdJ6LF.png"> 4) Manip **Exeggcute** with `pal(hold)`. (Do not use 9F.) |

After appearing in Lavender, move **4** tiles down to Route 12. Close the menu and catch **Mr. Mime**.

After the trainer fly, open the menu and swap Poke Doll x1 with a Helix Fossil stack way down in underflow.

Fly to Celadon with Pidgey and enter the center, then do the following menu:

- Swap Cascadebadge (already on it) with vtm in rival name
- Swap Ultra Ball x0 in brightness with Master Ball x6 in warping
- Toss 28 Ultra Balls now in warping

Leave the center to warp to Cerulean Cave.

### Cerulean Cave

Walk below the item ball: (you currently have 3 steps of encounter immunity!)

- Swap Old Amber in brightness with Parlyz Heal x[]4 in TID2
- Swap TM41 x80 in rival name with "4" x77 in map data
- Swap TM41 again with Full Restore x77 in text pointer
- Toss 7 TM41s
- Talk to the item ball, catch the **Golem** that appears

Cerulean Cave is filled with Pokemon we call **bonuses**. They are typically evolutions of Pokemon we catch throughout the run. Catching bonuses will save withdrawing the pre-evolution, candying it, watching it evolve, and depositing it. In general, if it's on your screen and you don't have it, catch it unless the notes say otherwise.

Every wild encounter in Cerulean Cave is a bonus. Proper use of dsum manipulation here can save a lot of time. Pokemon worth catching in order from best to worst: **Hypno**, **Kadabra**, **Dodrio**, **Sandslash**, **Magneton**, **Parasect**, **Venomoth**, **Electrode**, **Rhydon**, **Marowak**, **Wigglytuff**, **Raichu**, **Golbat**.

You are limited on box space so do not catch more than 10 (9 if manipped Dugtrio) of the above. Magneton does not count towards the limit. Do **not** catch Chansey and Ditto, those two will be obtained later.

| |
|---|
| Cerulean Cave 2F |
| ![](https://i.imgur.com/MrZkiVk.png) |
| Cerulean Cave 1F (entry floor) |
| ![](https://i.imgur.com/lKPzIYd.png) |
| Cerulean Cave B1F |
| ![](https://i.imgur.com/1CGlg6h.png) |

Catch things on any floor until you are satisfied then go to the basement.

Move **2** tiles above the ladder and open the menu:

- Swap Revive x93 in inventory with Master Ball x[]3 in TID1
- Swap Great Ball x0 in x coord with the Soulbadge in tileset
- Bike down and catch **Mewtwo**

After Mewtwo, move **3** tiles left then continue to search for an unneeded encounter by alternating up and down steps. LG for **Tauros**:

- Use 9F
- Swap Awakenings in slot 4 with "4" in rival name
- Swap Awakenings again with HM04 in TLP2
- Toss all-but-8 TM27s in TLP1
- Flash map
- Toss 1 TM27 in TLP1
- Swap Old Amber in brightness (**bottom** Old Amber stack) with Master Ball x[]8 in warping
- Swap Awakenings back with the HM04, now in rival name
- Flash WA4 in options then throw a preoptions Master Ball

<img align="right" src="https://i.imgur.com/M0rtiv5.png">

Manip **Chansey** with <ins>extra text while saving</ins>. You do not need to move before saving for this manip.

In the manipped encounter:

- Swap Master Ball x[]3 in inventory (**not** main stack) with Master Ball x4 in preoptions
- Swap Old Amber in TID2 with TM27 x7 in map ID
- Throw a Master Ball (up 1)

You will be crazywarped to Route 20, close the menu and catch **Alakazam**.

Bike left to an item ball, talk to it, and catch **Kangaskhan**.

If you didn't catch **Magneton** in Cerulean Cave: bike upwards to another item ball, talk to it, and catch it.

Fly to Pewter, enter the center, and **change boxes**. Walk **2** tiles left and **1** tile down, then open the menu:

- Swap PCEKANS x[]0 in rival name with Master Ball x2 in warping
- Swap Antidote x1 in x coord with Ultra Ball x0 in brightness

Walk **1** tile right then **hold down** to warp to Seafoam B2F.

### Seafoam Islands

<img align="right" src="https://i.imgur.com/K7m7zHK.png">

Corner bonk to the right of the bottom ladder for encounters.

In your first unneeded encounter LG for **Magikarp**:

- Use 9F
- Swap Master Ball x2 in rival name with Old Amber in brightness
- Swap HM04 in TLP2 with Max Potion x0 in roaming
- Swap HM04 again with BLUE in text pointer
- Swap TM50 x0 1 above with Pokedex, also 1 above
- Flash map
- Swap Pokedex back with TM50 x0
- Swap HM04 back with Max Potion x0 in TLP2
- Flash WA4 in options then throw a preoptions Master Ball

<img align="right" src="https://i.imgur.com/vo0uq5G.png">

Manip **Shellder** with `pal`, `fsback` (not cycling yet) if you didn't catch one before the LG, otherwise save and soft reset.

| |
|---|
| Seafoam B2F |
| ![](https://i.imgur.com/cBEc97H.png) |
| Seafoam B3F |
| ![](https://i.imgur.com/0X9mMgf.png) |
| Seafoam B4F |
| ![](https://i.imgur.com/4cFWgKv.png) |

<img align="right" src="https://i.imgur.com/fgT6BOX.png">

Hop on the bicycle and take the ladder to B3F. 

Catch **Psyduck** and **Seel**.

Afterwards jack through the wall shown in the picture and take the ladder to the basement.

In the basement catch **Krabby**, **Staryu**, and jack across the water to catch **Articuno**.

When done, swap Super Repel x1 in inventory with Old Amber in brightness, then use an Escape Rope from badges.

Enter the center and **change boxes**. Open the menu while at the PC:

- Swap Ultra Ball x0 in brightness with HM04 in TLP2
- Swap Potion x6 in tileset with Parlyz Heal x65 in roaming
- Swap roaming TMs with north connection (j. x255)

Walk **1** tile up to enter Victory Road 2F.

### Victory Road

| |
|---|
| Victory Road 2F |
| ![](https://i.imgur.com/JHwSXLy.png) |
| Victory Road 1F |
| ![](https://i.imgur.com/QllNbLU.png) |

Bonk for an encounter before hopping on the bicycle.

Catch everything but 1 of: **Machop**, **Geodude**, **Zubat**, **Onix**. At some point while searching, decide when to take the ladder you arrived on to move towards the next LG on 1F.

<img align="right" src="https://i.imgur.com/P3EThWG.png">

Once you have all but 1, get an encounter on the tile in the picture (do **not** approach from the right) and LG for **Machamp**:

- Use 9F
- Swap Old Amber in brightness with HM04 in TLP2
- Swap Old Amber again with Volcanobadge in text pointer
- Flash map
- Swap the Volcanobadge, now in TLP2, with the HM04, now in brightness
- Flash WA4 in options then throw a preoptions Master Ball
- Manip the final encounter <ins>(read the next part before catching)</ins>

|||
|---|---|
| <img align="right" src="https://i.imgur.com/O8DschK.png"> Zubat with `pal` | <img align="right" src="https://i.imgur.com/fL4g3XK.png"> Geodude |
|||
| <img align="right" src="https://i.imgur.com/9EoPf1h.png"> Onix with `fsback` | <img align="right" src="https://i.imgur.com/R0BVzBx.png"> Machop with `pal`, `hop2`, `fsback` |

In the manipped encounter:

- Swap Cascadebadge in rival name with the nameless item in map ID (above HM04)
- Swap Master Ball x5 in warping with Parlyz Heal x17 in tileset
- Throw a Master Ball

### Route 11 #1

<img align="right" src="https://i.imgur.com/nnfUgdb.png">

You will be crazywarped to Route 11, close the menu and catch **Scyther**.

The sprites may be in different positions relative to the map graphics, so always use the sprites for positioning. The sprites may also be offscreen to the left after Scyther.

Bike to the item ball, talk to it, and catch **Koffing**. <ins>Warning:</ins> out of bounds is the row above the item ball.

Talk to the sailor below and catch **Moltres**.

<img align="right" src="https://i.imgur.com/CPVEUiy.png">

After both crazywarp catches, exit Route 11 by moving left on the row below Moltres until the sprites have disappeared. Move back to the right and enter Diglett's Cave, which may be partially covered by other graphics.

Catch at least a **Diglett**, then leave the cave and head back to Route 11.

### Route 11 #2

<img align="right" src="https://i.imgur.com/7RgqpMF.png">

Search for wild encounters near the gambler to the south.

"Natural" LGs are done by doing the following in a wild encounter:

- Use 9F
- Move to the tile pictured
- Flash "4" then throw a Master Ball

In your first unneeded encounter LG for **Growlithe** (**unjack** and move to the tile).

Manip **Drowzee** if you still need it. If it's already caught, manip **Sandshrew** instead. If you caught both of them already, move to one of the Metapod tiles then **use** "4" to generate a Metapod encounter and run away from it.

|||
|---|---|
| <img align="right" src="https://i.imgur.com/kEoWeA9.png"> Drowzee with `nopal(ab)` | <img align="right" src="https://i.imgur.com/rF75UTq.png"> Sandshrew with `pal`, `hop1` |

Get another wild encounter and LG for **Venonat**.

If you did not catch Venomoth, flash "4" on the Hitmonchan tile before moving to the Venonat tile (to make Venonat come at a higher level).

Manip **Sandshrew** if you still need it (**unjack** and move to the Growlithe tile), otherwise follow the Metapod instructions above.

Get a final wild encounter and LG for **Hitmonchan**. Fly to Celadon directly after.

Enter the center, deposit NidoranM, then **change boxes**. Open the menu while at the PC:

- Swap jack in slot 6 with Fire Stone x15
- Swap jack again with HM04 in TLP2
- Swap jack again with Ultra Ball x0 in brightness
- Swap jack again with north connection (j. x255)

Walk **1** tile up and **buffer Start** to enter Tower 4F.

### Pokemon Tower + Route 21

Manip **Gastly**. If the manip fails due to IGT, do the backup manip instead of resaving.

|||
|---|---|
| <img align="right" src="https://i.imgur.com/xyiLIgM.png"> Primary with `pal`, `hop1`, `fsback x2` | <img align="right" src="https://i.imgur.com/IruxmHJ.png"> Backup with `nopal(ab)`, `gfwait` |

In the manipped encounter:

- Swap Fire Stone x15 in slot 6 with CANCEL x95 in map ID
- Throw a preoptions Master Ball

You will be crazywarped to Route 21. Hop on the bicycle in the trainer fly menu, then catch the **Magmar** that appears.

An item ball will walk to you; catch **Vulpix**. Bike down to talk to the item ball and catch **Fearow**. Bike left then up to talk to the last item ball and catch **Gengar**. <ins>Warning:</ins> the fisherman has a range of 4, do not get seen while he is still there.

<img align="right" src="https://i.imgur.com/CDsJhbG.png">

Search for wild encounters on the tile in the picture. Only catch Pidgeotto if it's level 32, **never** catch Tangela.

In your first unneeded encounter LG for **Tentacool**:

- Use 9F
- Swap Old Amber in rival name with Moon Stone x0 in x coord
- Swap Ultra Ball x0 in brightness with HM04 in TLP2
- Swap Ultra Ball again with Bike Voucher in width
- Flash map
- Swap Ultra Ball back with the Bike Voucher
- Swap Ultra Ball back with the HM04
- Flash WA4 in options then throw a preoptions Master Ball

Manip **Pidgeotto** if you still need it, otherwise save and soft reset.

|||
|---|---|
| <img align="right" src="https://i.imgur.com/yPbkzx3.png"> Primary with `fsback` | <img align="right" src="https://i.imgur.com/okZSsNT.png"> Backup with `pal(hold)`, `hop1` |

<img align="right" src="https://i.imgur.com/4Phpw3z.png">

Find another encounter, now on the tile in this picture, and LG for **Charmander**:

- Use 9F
- Swap Burn Heal x1 in inventory with Poke Flute in money
- Swap Burn Heal again with Ultra Ball x0 in brightness
- Swap Burn Heal again with HM04 in TLP2
- Toss 8 from the Fire Stone stack above (map ID)
- Flash map
- Toss 8 from the Fire Stone stack again
- Swap Burn Heal back with the HM04
- Flash WA4 in options then throw a preoptions Master Ball

Manip **Tangela**. You do not need to move before saving for this manip.

| |
|---|
| <img align="right" src="https://i.imgur.com/8vNMicz.png"> Tangela with `pal(hold)`, `fsback x2` |

Fly to Celadon directly after.

### Route 16

In Celadon move **1** tile left, swap Great Ball x1 in inventory with Rare Candy x0 in x coord, then hop on the bicycle in map ID.

<img align="right" src="https://i.imgur.com/Emo674H.png">

Follow the path shown, it will lead you to Route 16 with a trainer fly waiting. Catch the **Dragonite** that appears.

Use jack to get on the tree to the right of **Snorlax**, then play the Poke Flute to wake it up (you don't need to unjack).

| |
|---|
| Route 16 |
| ![](https://i.imgur.com/MWKm80b.png) |

Just like in Victory Road, catch everything but 1 of: **Spearow**, **Rattata**, and **Doduo**.

<img align="right" src="https://i.imgur.com/4t1Qy3h.png">

In the first unneeded encounter LG for **Rhyhorn**.

After catching Rhyhorn, move **1** tile up, **swap Master Balls into slot 1** (swap with Bicycle), then **use** "4" and catch the **Metapod** that appears.

Undo the swap the next time you open the item menu.

Once you have all but 1 of the required wild Pokemon, get an encounter and LG for **Kabuto**.

If you are missing Spearow or Doduo use "4" on the **right** Horsea tile, or if you are missing Rattata use it on the **left** Horsea tile.

Run from the Metapod encounter (which gives you flipped sprites!).

Alternate up and down steps until you get an encounter, then do the following:

- Use 9F
- Open items (do **not** flash map or trainer card)
- Flash "4" and throw a Master Ball to catch **Horsea**
- Swap Master Ball x[]8 in inventory (**not** main stack) with Moon Stone x0 in rival name
- Swap the unnamed item in rival name (from Victory Road) with x coord, which is either a Repel or an Escape Rope
- Manip the final encounter

||||
|---|---|---|
| <img align="right" src="https://i.imgur.com/f2eSneP.png"> Spearow with `pal`, `hop2` | <img align="right" src="https://i.imgur.com/Bw0vz21.png"> Doduo with `nopal(ab)`, `fsback` | <img align="right" src="https://i.imgur.com/QAl4Gpi.png"> Rattata with `nopal(ab)` |

After the manip encounter ends, bike left until you are outside the grass, then hold down until the start menu opens. Fly to Pewter and catch **Mew**.

### Pewter City + Route 3

Enter the center, **change boxes**, then leave the center.

Use jack and bike to the **right** of the gym guy used for Brock Through Walls. Unjack and talk to him, then while holding Select move right until a trainer fly ("brock fly") textbox opens. Close it and catch the **Goldeen**.

<img align="right" src="https://i.imgur.com/9zEXBwi.png">

After the brock fly, open the item menu, swap jack in slot 6 with Fire Stone x99, then toss 12 from Awakening x182 in map ID. You are now on the green tile in the picture, bike to the grass to search for an encounter.

<ins>Warning:</ins> if you go 1 tile too far left you will be back in Pewter.

Catch the encounter if it's a **Jigglypuff**, otherwise LG for **Cubone**.

<img align="right" src="https://i.imgur.com/lsBwMzA.png">

Manip Jigglypuff with `gfwait` if you still need one. If it's already caught, move to the Metapod tile in the picture then **use** "4" to generate a Metapod encounter and run away from it.

Bike back to the tile you arrived at originally and move **1** tile left to return to Pewter. After the gym guy's text, move right then left to reload Pewter, then go left some more and talk to the gym guy again. While holding B, make your way towards the gym. **Flash the start menu** before entering.

In the trainer fly menu do the following:

- Evolve Exeggcute, NidoranF, Paras (if needed), and Nidorina
- Swap Super Potion x83 in inventory with Ultra Ball x0 in brightness
- Swap Super Potion x83 again with j. x2 in warping

Exit the menu and catch **Oddish**. Exit the gym to warp to the Power Plant.

### Power Plant

| |
|---|
| ![](https://i.imgur.com/17FX3Cv.png) |

Dsum for either a **Magnemite** or a **Pikachu** (the other can be manipped later). Do not catch Voltorb. At some point, talk to **Zapdos** and catch it too.

<img align="right" src="https://i.imgur.com/rv7mAXt.png">

After Zapdos, walk to the tile in the picture and do the following:

- Swap Fire Stone x99 in slot 6 with jack
- Swap Awakening x20 in rival name with HM04 in TLP2
- Toss all-but-8 from Max Elixer x136 above
- Walk **1** tile right and talk to the ball, catch **Voltorb**

<img align="right" src="https://i.imgur.com/qInnztJ.png">

Get an encounter **1** tile down from where you talked to Voltorb, then LG for **Farfetch'd**:

- Use 9F
- Flash **trainer card**
- Flash "4"
- Throw a Master Ball

If you still need **Magnemite** or **Pikachu**, do one of the following manips.

In the manipped encounter, **use 9F while holding a direction** (double input works).

|||
|---|---|
| Magnemite | `pal(hold)`, `D D U R D` |
|||
| Pikachu | `pal`, `D D U U U D D` |

Otherwise, **use 9F in the menu while holding left or right**.

After "9F warping" walk **1** tile right, jack **1** tile up, press Down and hold while opening the start menu, and unjack. (You need to see yourself **facing down**.)

LG for **Squirtle** & friends:

- Swap Antidote x4 in inventory with Coin Case in TLP2
- Toss 4 from "JACK" x255 one slot above (if not tossable, flash toss Antidotes)
- Swap Ultra Ball x0 in brightness with Potion x2 in tileset
- **If you 9F warped from a manip, throw a Master Ball from warping**
- Swap Parlyz Heal x1 in x coord with j. x64 in map data (4 slots down)
- Swap Burn Heal x84 in text pointer with Poke Ball x4 in width
- Toss 73 Burn Heals
- Swap the Poke Ball x4, now in text pointer, with Ice Heal x78 in rival name
- Close the menu, talk to the cashier now in front of you to get **Hitmonlee**
- Flash WA4 in options then throw a preoptions Master Ball
- Fly to Celadon

### Route 7 + Silph Co.

Enter the center, deposit Pidgey, Paras(ect), Nidoqueen, and Exeggutor, then **change boxes**.

Use Bicycle in map ID to bike to the prize corner and purchase:

- **Abra**, **Clefairy**, and **Nidorino** from the left window
- **Dratini**, **Pinsir**, and **Porygon** from the middle window

<img align="right" src="https://i.imgur.com/o5fYYEN.png">

Leave the prize corner and bike to Route 7.

Get an encounter and catch it if it's **Bellsprout**. If it's not, LG for **Mankey**. The tile you move to depends on what you will do after the LG:

If you need Bellsprout, move to the **left Mankey tile** and manip after.

If you already caught Bellsprout, move to the **right Mankey tile** and utilize the Metapod tile after. Move to the Metapod tile in the picture then **use** "4" to generate a Metapod encounter and run away from it.

| |
|---|
| <img align="right" src="https://i.imgur.com/kzMYCjP.png"> Bellsprout |

After having caught Bellsprout and Mankey, get an encounter and LG for **Ivysaur**:

<img align="right" src="https://i.imgur.com/wHdfGOJ.png">

- Use 9F
- Unjack, enter the guardhouse to your right
- Walk **1** tile right and **1** tile up, face left
- Swap Poke Flute with HM04 above Helix Fossil
- Swap Helix Fossil with HM03 in TLP2
- Swap Ultra Ball x0 in brightness with Master Ball x18 in warping
- Toss 21 Ultra Balls
- Flash map
- Flash WA4 in options then throw a preoptions Master Ball
- Swap HM03, now in inventory, with Helix Fossil in TLP2

**Hold left** to leave the guardhouse and warp to Silph Co 11F.

Take the teleporter pad you arrive on, talk to the hostage to receive **Lapras**, and take the teleporter pad back to 11F.

<img align="right" src="https://i.imgur.com/hW51Tuv.png">

From the teleporter walk **2** tiles left then **2** tiles down (must be facing downwards).

LG for **Weedle**:

- Swap HM04 in TLP2 with Master Ball x0 in x coord
- Swap Moon Stone x16 in tileset with Pokedex in width
- Toss 3 Moon Stones
- Flash map
- Toss all-but-8 from j. x255 in north connection
- Toss 1 from Master Ball x0 in TLP2
- Toss 1 from TM35 x22 in TLP1
- Flash WA4 in options then throw a preoptions Master Ball
- Flash **trainer card**
- Flash WA4 in options

Close the menu and wait to enter Cinnabar center.

### Cinnabar Island

Inside the center, swap Revive x93 in TID1 with Poke Doll x94 in text pointer. Talk to Nurse Joy, who now revives fossils, and give her a Helix Fossil. **Undo the last swap** then leave the center.

Enter the center again and swap the Revives with the Poke Dolls again. Talk to Nurse Joy to receive **Omanyte**, give her an Old Amber, and **change boxes**.

<img align="right" src="https://i.imgur.com/K2toQQL.png">

Walk to the tile in the picture to start the LG for **Jynx**: <ins>Warning:</ins> Moving to the doormat tiles from above may cause you to leave and lose the Revives.

- Swap Card Key in map data with HM04 in TLP2
- Flash map
- Flash NEW NAME in TLP1
- Swap Card Key back with HM04
- Swap Revive x93 in text pointer with south connection (1 below CANCEL)
- Unjack

Leave the center, enter the mart, and open the menu:

- Swap Revives (already on it) with "4" in text pointer. This 4 is a click item, which requires pressing B **once** whenever its name prints to continue scrolling.
- Catch Jynx by throwing a preoptions Master Ball 
- Catch **Ditto** by throwing another preoptions Master Ball

<img align="right" src="https://i.imgur.com/nXZBsdc.png">

Talk to the mart guy to receive **Aerodactyl**.

LG for **Meowth** on the tile in the picture:

- Flash WA4 in options then throw a preoptions Master Ball
- Unjack

<img align="right" src="https://i.imgur.com/aA3TuOc.png">

Leave the mart and walk to the tile in the picture to do the first menu:

- Swap Poke Doll x94, now in TID1, with Pokedex in north connection (**second** Pokedex scrolling down)
- Swap Poke Dolls again with TM35 x198 (down 2)
- Toss 33 TM35s
- Swap Poke Dolls again with "44yPC" in text pointer
- Use 1 Poke Doll

Talk to the sign next to the gym once to receive **Eevee**. 

<img align="right" src="https://i.imgur.com/HaM6wnQ.png">

**Face right** to do the second menu:

- Swap Pokedex in width with Moon Stone x0 in tileset
- Toss 17 Moon Stones
- Swap HM04 in TLP2 with Ultra Ball x0 in brightness
- Toss all-but-3 Ultra Balls
- Flash map

The setup for "Eevee Factory" is now complete. Follow the next instructions to catch Lickitung, Eevee, Slowpoke, Eevee, and Poliwag.

<img align="right" src="https://i.imgur.com/hwBdghB.png">

(While learning, you may find it helpful to watch a run complete this section, because the map graphics will not fully update to match the picture.)

The picture shows where the three LGs are located on the glitched map.

You begin on the Lickitung tile, and talking to the Lickitung tile gives you an Eevee.

<ins>Warning:</ins> walking to the top row of tiles pictured will take you to Mansion 1F. Do not cross the connection until you have completed this section.

LG for **Lickitung**:

- (Flash map if you did not already)
- Flash WA4 in options then throw a preoptions Master Ball
- Close the menu, move **1** tile up, unjack
- Face down and press A to receive **Eevee**

LG for **Slowpoke**:

- Flash WA4 in options then throw a preoptions Master Ball
- Unjack, close the menu
- Press (hold) A to receive **Eevee**

LG for **Poliwag**:

- Walk **1** tile right, **2** tiles up, **3** tiles right
- Face left and flash WA4 to active jack, move down **1** tile
- Flash WA4 in options then throw a preoptions Master Ball

Walk **2** tiles up after a delay (you don't need to unjack) to enter Mansion 1F.

### Cinnabar Mansion

Swap HM04 in TLP2 with Poke Flute in inventory, then manip **Weezing** with <ins>extra text while saving</ins>. You do not need to move before saving for this manip.

| |
|---|
| <img align="right" src="https://i.imgur.com/z8KlzpG.png"> Weezing with `pal(hold)` |

| |
|---|
| ![](https://i.imgur.com/pQ7EITv.png) |

Dsum for either a **Grimer** or a **Ponyta** (the other can be manipped later). Muk can appear as a bonus.

<img align="right" src="https://i.imgur.com/phbDTnb.png">

Make sure your three-step-rule will end then use jack to get on the tile in the picture. Bonk for an encounter (you don't need to unjack) and LG for **Electabuzz**:

- Use 9F
- Flash map
- Flash "4" then throw a Master Ball

Manip one of the following:

|||
|---|---|
| <img align="right" src="https://i.imgur.com/g8fPXm1.png"> Grimer with `hop1` | <img align="right" src="https://i.imgur.com/UkY3NTF.png"> Ponyta with `pal(hold)` |
|||
| <img align="right" src="https://i.imgur.com/opi33H2.png"> Muk wih `nopal(ab)`, `fsback` | <img align="right" src="https://i.imgur.com/GawJkTb.png"> Weezing with `pal`, `hop2`, `fsback` |

After having caught Grimer, Ponyta, and Weezing, use an Escape Rope <ins>from badges</ins>, then enter Vermilion center.

### Audio Fade Out ("AFO")

Walk below the PC, face up, and menu to set up the AFO glitch city:

- Swap HM04 in TLP2 with Master Ball x5 in warping
- Toss 1 from the Master Balls you just swapped
- Swap HM04 again with j. x255 in north connection
- Swap roaming TMs with Poke Ball x7 in width
- Toss 6 TMs
- Flash map
- Toss the entire stack of Parlyz Heal x65 below
- Swap "4" with Ultra Ball x0 in inventory (above Rare Candies)

In this glitch city, flashing "4" will cause the audio to fade out for about 33 seconds. All jingles do not have a delay during the fade out, such as using Rare Candies, the cries when depositing and withdrawing Pokemon, and changing boxes. An evolution will cause the fade out to end immediately, so flash 4 again after each one. (You shouldn't bother scrolling to and flashing 4 for stone evolutions.)

Evolve everything you need to in boxes 7 through 2 this way. (Box 1 will always be filled with Pokemon that do not evolve.)

When done, deposit all but 1 Pokemon then do the following menu:

- Swap Master Ball x[]8 in rival name with HM04 in north connection (**second** HM04 scrolling down)
- Swap "F" in text pointer (up 2) with TM40 x[]2 in width
- Swap Master Ball x4 in TLP2 with Ultra Ball x0 in brightness

<img align="right" src="https://i.imgur.com/ErqwNmg.png">

Walk **1** tile up to warp to the Hall of Fame!

Timing ends when the screen fully fades to white after 151 Pokemon are displayed in the Pokedex.

### The End

## RNG Manipulations

|||
|---|---|
| ![](https://i.imgur.com/6rMpeCF.png) | Pidgey into Caterpie Manip<br>[Pokeworld Link 1](https://gunnermaniac.com/pokeworld?local=13#4/56/UUAURAURRURAU) \| [Pokeworld Link 2](https://gunnermaniac.com/pokeworld?local=13#8/50/LRRU)<br>nopal(ab), fastest buffers<br><br>59/60 pidgey, 56/60 extended<br>Frame 15: Caterpie yoloball fail<br>Frame 36: No Pidgey encounter<br>Frame 37: No Caterpie encounter<br>Frame 47: Rattata encounter on extended |
|||
| ![](https://i.imgur.com/plw6lqS.png) | Non-extended Caterpie Manip<br>[Pokeworld Link](https://gunnermaniac.com/pokeworld?local=51#21/43/UURRRRUUUUUUUUUUUUUUUUUUUUUUUUUUUUUUUULLLLLLLLDDDDDDDLLLLLAUUUUUUUUUUUAUUALLLLDDADDDDDDDDDDDDDDLLAD)<br>nopal, fastest buffers<br><br>57/60<br>Frame 25: Caterpie yoloball fail<br>Frame 36: [Metapod encounter](https://gunnermaniac.com/pokeworld?map=51#25/25)<br>Frame 37: [Kakuna encounter](https://gunnermaniac.com/pokeworld?map=51#12/16) |
|||
| ![](https://i.imgur.com/DiPPZTA.png) | Diglett's Cave Manip<br>[Pokeworld Link](https://gunnermaniac.com/pokeworld?local=197#5/5/DDDDDDDDDADDDARRRADDDADRRRRDDDDADDDDRRRRRRARRRRRRDRRRRRRRRRRRRRD)<br>pal, fastest buffers<br><br>58/60<br>Frame 30: [L15 Diglett encounter](https://gunnermaniac.com/pokeworld?map=197#5/7)<br>Frame 36: [L16 Diglett encounter](https://gunnermaniac.com/pokeworld?map=197#5/9) |
|||
| ![](https://i.imgur.com/DiPPZTA.png) | Dugtrio Manip<br>[Pokeworld Link](https://gunnermaniac.com/pokeworld?map=197#5/5/DDDDDDDDDADDDARRRADDDADRRRRDDDDADDDDRRRRRRARRRRRRDRRRARRRS_BRRRRDDDRRUUU)<br>pal, fastest buffers<br><br>56/60<br>Frame 29: Dugtrio yoloball fail<br>Frame 30: [L15 Diglett encounter](https://gunnermaniac.com/pokeworld?map=197#5/7)<br>Frame 36: [L16 Diglett encounter](https://gunnermaniac.com/pokeworld?map=197#5/9)<br>Frame 37: [L19 Diglett encounter](https://gunnermaniac.com/pokeworld?map=197#34/31) |
|||
| ![](https://i.imgur.com/3dN1VAT.png) | Deathfly Manip<br>[Pokeworld Link](https://gunnermaniac.com/pokeworld?local=22#4/6/RRRRARRRRU)<br>nopal(ab), fastest buffers<br><br>58/60<br>Frame 25: Sandshrew uses Sand Attack<br>Frame 36: No encounter |
|||
| ![](https://i.imgur.com/rT5Q9nb.png) | Paras Manip<br>[Pokeworld Link](https://gunnermaniac.com/pokeworld?local=217#5/1/DDDDDRRRRRRR)<br>nopal, fastest buffers<br><br>59/60<br>Frame 36: No encounter |
|||
| ![](https://i.imgur.com/gmL4a46.png) | Nidoran Female Manip<br>[Pokeworld Link](https://gunnermaniac.com/pokeworld?local=217#12/1/RR)<br>nopal, hop1, fsback<br><br>60/60 |
|||
| ![](https://i.imgur.com/2xFaI1s.png) | Nidoran Male manip<br>[Pokeworld Link](https://gunnermaniac.com/pokeworld?local=217#14/1/RRRAR)<br>nopal(ab), fsback<br><br>59/60<br>Frame 58: No encounter |
|||
| ![](https://i.imgur.com/1K22K0J.png) | Exeggcute Manip<br>[Pokeworld Link](https://gunnermaniac.com/pokeworld?local=217#18/1/RRRDADDDDRR)<br>pal(hold), fastest buffers<br><br>58/60<br>Frame 36: No encounter<br>Frame 37: Pidgey from dv fly |
|||
| ![](https://i.imgur.com/qSi4ogz.png) | Chansey Manip<br>[Pokeworld Link](https://gunnermaniac.com/pokeworld?local=227#19/1/US_BUUU)<br>nopal, fastest buffers<br><br>58/60<br>Frame 36: No encounter<br>Frame 37: Starmie from dv fly |
|||
| ![](https://i.imgur.com/lDHntsX.png) | Shellder Manip<br>[Pokeworld Link](https://gunnermaniac.com/pokeworld?local=160#26/14/US_BL)<br>pal, fsback<br><br>59/60<br>Frame 36: No encounter |
|||
| ![](https://i.imgur.com/po2JqdC.png) | Zubat Manip<br>[Pokeworld Link](https://gunnermaniac.com/pokeworld?local=194#15/0/RRRS_BS_BLLAL)<br>pal, fastest buffers<br><br>58/60<br>Frame 36: No encounter<br>Frame 37: Blastoise from dv fly |
|||
| ![](https://i.imgur.com/po2JqdC.png) | Geodude Manip<br>[Pokeworld Link](https://gunnermaniac.com/pokeworld?local=194#15/0/RRS_BRS_BS_BLLL)<br>nopal, fastest buffers<br><br>58/60<br>Frame 36: [L26 Zubat encounter](https://gunnermaniac.com/pokeworld?local=194#17/0)<br>Frame 37: No encounter |
|||
| ![](https://i.imgur.com/po2JqdC.png) | Onix Manip<br>[Pokeworld Link](https://gunnermaniac.com/pokeworld?local=194#15/0/RRRDDS_BDS_BL)<br>nopal, fsback<br><br>58/60<br>Frame 58: No encounter<br>Frame 59: Machoke from dv fly |
|||
| ![](https://i.imgur.com/po2JqdC.png) | Machop Manip<br>[Pokeworld Link](https://gunnermaniac.com/pokeworld?local=194#15/0/RRRDDDL)<br>pal, hop2, fsback<br><br>58/60<br>Frame 58: No encounter<br>Frame 59: Arcanine from dv fly |
|||
| ![](https://i.imgur.com/msGkpdL.png) | Drowzee Manip<br>[Pokeworld Link](https://gunnermaniac.com/pokeworld?local=22#15/17/UUURR)<br>nopal(ab), fastest buffers<br><br>58/60<br>Frame 36: No encounter<br>Frame 37: [L13 Spearow encounter](https://gunnermaniac.com/pokeworld?local=22#17/14) |
|||
| ![](https://i.imgur.com/msGkpdL.png) | Sandshrew Manip<br>[Pokeworld Link](https://gunnermaniac.com/pokeworld?local=22#15/17/UUUUUARR)<br>pal, hop1<br><br>59/60<br>Frame 36: No encounter |
|||
| ![](https://i.imgur.com/FK7kPrg.png) | Primary Gastly Manip<br>[Pokeworld Link](https://gunnermaniac.com/pokeworld?local=145#3/9/DRDRRRADRRRADRR)<br>pal, hop1, fsback, fsback<br><br>58/60<br>Frame 20: Arbok from dv fly<br>Frame 21: No encounter |
|||
| ![](https://i.imgur.com/FK7kPrg.png) | Backup Gastly Manip<br>[Pokeworld Link](https://gunnermaniac.com/pokeworld?local=145#3/9/DRDRDDRADRRRARURR)<br>nopal(ab), gfwait<br><br>56/60 (works on the missing 2/60 above)<br>Frame 19; 36; 37; 48: No encounter |
|||
| ![](https://i.imgur.com/rVfUc87.png) | Primary Pidgeotto Manip<br>[Pokeworld Link](https://gunnermaniac.com/pokeworld?local=32#10/4/RRR)<br>nopal, fsback<br><br>59/60<br>Frame 58: No encounter |
|||
| ![](https://i.imgur.com/rVfUc87.png) | Backup Pidgeotto Manip<br>[Pokeworld Link](https://gunnermaniac.com/pokeworld?local=32#10/4/RRRDDD)<br>pal(hold), hop1<br><br>59/60 (works on the missing 1/60 above)<br>Frame 36: No encounter |
|||
| ![](https://i.imgur.com/WGX3ruS.png) | Tangela Manip<br>[Pokeworld Link](https://gunnermaniac.com/pokeworld?local=32#13/2/DDDD)<br>pal(hold), fsback, fsback<br><br>58/60<br>Frame 20: No encounter<br>Frame 21: Missingno. from dv fly |
|||
| ![](https://i.imgur.com/Dyy76n5.png) | Spearow Manip<br>[Pokeworld Link](https://gunnermaniac.com/pokeworld?local=27#29/5/DD)<br>pal, hop2<br><br>59/60<br>Frame 36: Rhyhorn from dv fly |
|||
| ![](https://i.imgur.com/Dyy76n5.png) | Doduo Manip<br>[Pokeworld Link](https://gunnermaniac.com/pokeworld?local=27#29/5/DDD)<br>nopal(ab), fsback<br><br>58/60<br>Frame 36: No encounter<br>Frame 37: No encounter |
|||
| ![](https://i.imgur.com/Yn2UgRC.png) | Rattata Manip<br>[Pokeworld Link](https://gunnermaniac.com/pokeworld?local=27#28/5/DDDDADDD)<br>nopal(ab), fastest buffers<br><br>59/60<br>Frame 36: [L20 Doduo encounter](https://gunnermaniac.com/pokeworld?local=27#28/12) |
|||
| ![](https://i.imgur.com/HH3DpGT.png) | Jigglypuff Manip<br>[Pokeworld Link](https://gunnermaniac.com/pokeworld?local=14#58/0/DDDDDDDDRR)<br>nopal, gfwait<br><br>59/60<br>Frame 36: No encounter |
|||
| ![](https://i.imgur.com/Cx3evTa.png) | Magnemite Manip<br>[Pokeworld Link](https://gunnermaniac.com/pokeworld?local=83#8/11/DDURD)<br>pal(hold), fastest buffers<br><br>58/60<br>Frame 36: No encounter<br>Frame 37: [L24 Pikachu encounter](https://gunnermaniac.com/pokeworld?local=83#9/13) |
|||
| ![](https://i.imgur.com/Cx3evTa.png) | Pikachu Manip<br>[Pokeworld Link](https://gunnermaniac.com/pokeworld?local=83#8/11/DDUUUDD)<br>pal, fastest buffers<br><br>59/60<br>Frame 36: No encounter |
|||
| ![](https://i.imgur.com/9h54TuN.png) | Bellsprout Manip<br>[Pokeworld Link](https://gunnermaniac.com/pokeworld?local=18#8/15/UUUAUUUUUUU)<br>nopal, fastest buffers<br><br>59/60<br>Frame 36: No encounter |
|||
| ![](https://i.imgur.com/nubIFes.png) | Weezing Manip<br>[Pokeworld Link](https://gunnermaniac.com/pokeworld?local=165#5/10/URRRUUUS_BUS_BLLLLAUU)<br>pal(hold), fastest buffers<br><br>58/60<br>Frame 36: [L34 Ponyta encounter](https://gunnermaniac.com/pokeworld?local=165#8/6)<br>Frame 37: [L37 Muk encounter](https://gunnermaniac.com/pokeworld?local=165#4/3) |
|||
| ![](https://i.imgur.com/9C6CTIK.png) | Grimer Manip<br>[Pokeworld Link](https://gunnermaniac.com/pokeworld?local=165#4/2/D)<br>nopal, hop1<br><br>59/60<br>Frame 36: No encounter |
|||
| ![](https://i.imgur.com/9C6CTIK.png) | Ponyta Manip<br>[Pokeworld Link](https://gunnermaniac.com/pokeworld?local=165#4/2/DADDLLUAUL)<br>pal(hold), fastest buffers<br><br>59/60<br>Frame 36: No encounter |
|||
| ![](https://i.imgur.com/9C6CTIK.png) | Muk Manip<br>[Pokeworld Link](https://gunnermaniac.com/pokeworld?local=165#4/2/D)<br>nopal(ab), fsback<br><br>60/60 |
|||
| ![](https://i.imgur.com/9C6CTIK.png) | Weezing Manip<br>[Pokeworld Link](https://gunnermaniac.com/pokeworld?local=165#4/2/DS_LLL)<br>pal, hop2, fsback<br><br>58/60<br>Frame 58: No encounter<br>Frame 59: [L37 Muk encounter](https://gunnermaniac.com/pokeworld?local=165#1/3) |

## Brock Flies

```
6320 FIRE_STONE x99: ODDISH L73, HOLD(←→B), IGNORED*(↑→sBA), menu, 142f
5F91 (0x91) x95: GOLDEEN L170, HOLD(↓↑sB), IGNORED*(↑SBA), nomenu, 172f
```

The data provided in this section is intended to be a technical reference for those looking to improve or change the route.

## ROM LGs

```
12 251 42 3 1 1: L74 Ivysaur 18
0 23 12 10 0 1: L186 Charmander 15
2 251 11 11 1 1: L239 Squirtle 71
16 22 1 13 1 1: L165 Weedle 134
3 0 100 36 1 1: L173 Ekans 75
0 44 1 239 0 1: L32 Poliwag 57
17 5 27 15 0 1: L224 Machamp 32
0 30 45 0 0 0: L78 Tentacool 237
0 42 1 239 1 1: L245 Slowpoke 78
22 9 14 20 1 0: Lcopy Farfetch'd 252
0 31 2 239 0 1: L1 Lickitung 16
6 30 48 7 1 0: L59 Jynx 1
22 21 73 15 0 0: L1 Electabuzz 53
17 8 14 15 1 1: L18 Tauros 176
17 158 17 100 0 0: L33 Magikarp 135
```

The data provided in this section is intended to be a technical reference for those looking to improve or change the route.

## Links & Resources

Manip links

- [RNG manipulation video playlist](https://www.youtube.com/playlist?list=PLGhm5bU72JPTU-i7sOyURd3s05UjHunJR)
- [Bulbasaur manip info](https://pastebin.com/L14vtxJS)

Speedruns

- [Previous route](https://docs.google.com/document/d/1xvEJZVDT0q-xk_Lnp-RB8i4tgQ1r-618hcEQa0-x4Sw/edit)
- [stocchi's 1:37:56 with previous route](https://www.youtube.com/watch?v=1xtSuZiVcAQ)
- [speedrun.com leaderboard](https://www.speedrun.com/pkmnredblue#Catch_Em_All)

Routing

- [Pokeworld](https://gunnermaniac.com/pokeworld?map=1)
- [Roaming items](https://pastebin.com/raw/T5gHcAtb)
- [DV flies](https://pastebin.com/raw/ETwXsiAG)
- [Brock fly pointers](https://github.com/stringflow/psr/blob/master/blue/151_no_item_underflow/brockfly.md)
- [Natural LGs](https://github.com/stringflow/psr/blob/master/blue/151_no_item_underflow/ctlg.md)
- [Tileset-LG sets](https://pastebin.com/raw/wgMR5dV4)
- [Tileset locations](https://pastebin.com/raw/NTe20zq8)

Disassembly

- [pret/pokered](https://github.com/pret/pokered)
- [Assembly instruction details](https://pastebin.com/raw/bHn8y18B)
- [Item underflow slots](https://glitchcity.wiki/Expanded_bag_item_documentation_(Generation_I))
