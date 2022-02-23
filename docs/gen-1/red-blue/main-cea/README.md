<img align="left" src="https://user-images.githubusercontent.com/22380063/155185929-1dd8cde1-7bb6-430a-b479-89f39a1c4e3e.gif">

# Pokemon Blue - Catch 'Em All

Autumn 2020 route & guide

## Before We Begin

Before doing runs of this category, it is suggested you are familiar with the following concepts, techniques, and glitches: <ins>(updated links welcome)</ins>

- Item Underflow
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

Catch ‘Em All has been speedrun and influenced by many people in the community, including but not limited to:

Ætienne, Besson, Chivu, Dabomstew, Decon, DerTeppich, Driekiann, eddaket, entrpntr, ExtraTricky, gifvex, Grogir, HorouIchigo, Keizaron, krazyd4n, luckytyphlosion, MrWint, PicklePlop, pokeguy, randalleatscheese, Sanqui, Shenanagans, Sidosh, SinH4, Sinstar, Smurfy, Snairam, stocchi, stringflow, TehHammerShow, VaultButler, werster,

and the good people at [PokemonSpeedruns](https://discord.gg/NjQFEkc), Glitch City Research Institute, & TASVideos.

ty!

## The Route

### Intro

<img align="right" src="https://user-images.githubusercontent.com/22380063/155191148-110bca8d-81e8-48e6-85f2-3360e1280669.png">

Clear save data before each attempt with Up + Select + B on the title screen.

Hard reset and [manipulate the trainer ID 54878](https://youtu.be/upzxy_0KW7A).

Hold the A or B button while clearing textboxes with the other, as the text speed option is still the default.

Name the player a one-character name like `A` or `I`.

Name the rival `AaRRSA*`, where the asterisk is the character below S.

### Pallet Town

Open the start menu and set the options to Fast/Off/Shift.

Optional: Withdraw the Potion from the PC.

You will be choosing Bulbasaur as the starter for the run:

- Advanced runners can choose to manipulate Bulbasaur's DVs for optimal fights and an always-working special stat for the Brock Through Walls glitch later on. However this is **not** recommended for beginner runners as the manipulation can be very difficult to execute if you do not have much experience with clearing textboxes during RNG manipulations.

- For beginners it is recommended to take a random Bulbasaur instead. Note having a bad attack stat on your Bulbasaur can make you lose turns on the Rival and Weedle Guy fights. In addition, the fastest setup for the Brock Through Walls glitch ("Pidgey Strats") only has a 9/16 (~56%) chance of working with a random Bulbasaur. 

Do **not** nickname the Bulbasaur as the name length is a requirement for the upcoming RNG manipulations to work.

To manipulate Bulbasaur: walk below the ball, then hold Up and press Start to buffer the menu, which is required for the manip to work. Save and hard reset then execute the manip's intro. After loading the save buffer a start flash, buffer A to interact with the ball, then while holding A or B clear every textbox perfectly (4 frame windows), including the Yes for Bulbasaur and the No for nicknaming.

The IGT success rate on this manip is 56/60, but due to NPC timers the manip will fail an additional ~15% of the time.

More info can be [found on pastebin](https://pastebin.com/L14vtxJS), and a video with inputs can be [found here](https://youtu.be/VjLFyiX5JdA).

If you received a random Bulbasaur, it can be beneficial to check the summary immediately in the upcoming battle and remember the special stat for when it levels up, in order to better know how likely the Bulbasaur will work for Pidgey Strats. The trainer ID is displayed in the bottom right corner of the summary, so you can use this time to double check it as well.

### Rival Fight

Use Tackle on every turn. Heal up with a Potion if at 6 health or below. Winning the fight is mandatory.

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

Non-manipulated Bulbasaurs can pick up [the tree potion](https://gunnermaniac.com/pokeworld?map=1#54/166) before leaving, especially if they took damage while gaining experience, but another potion is on the way.

### Route 2

<img align="right" src="https://user-images.githubusercontent.com/22380063/155193530-9f993033-1fe3-4cef-a86d-c52935a58b75.png">

Manipulate a Pidgey encounter & catch with `nopal(ab)` and the path shown. This Pidgey will always have HP that works for Brock Through Walls and will always catch, so a random Pidgey is not a viable alternative.

It is recommended you extend the Pidgey manip into a Caterpie by clearing Pidgey's textboxes and Pokedex entry perfectly, then by moving `L R R U` afterwards. For beginners, or if an issue occurs, a solo Caterpie manip is an option once inside Viridian Forest.

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

<img align="right" src="https://user-images.githubusercontent.com/22380063/155194140-a2bafcf7-916a-41b3-bc0e-935b4566204d.png">

Hold B after the textboxes to be able to Brock Through Walls.

Navigate to Diglett's Cave. The simplest path to avoid the out-of-bounds area is to turn after the mart door, as shown in the picture.

### Diglett's Cave

Brock Through Walls ends upon entering the first cavern.

Save the game immediately after climbing down the ladder. Hard reset and use the [Diglett's Cave Manip](#rng-manipulations) with `pal` for no encounters, or use the [Dugtrio Manip](#rng-manipulations) with `pal` for an early Dugtrio (and 1 less space in Box 1).

### Vermilion City

Enter Vermilion Center. Deposit all Pokemon except Pidgey then heal before leaving.

<img align="right" src="https://user-images.githubusercontent.com/22380063/155194713-ac6b5fce-23ee-4671-b14c-2f7e250d36fe.png">

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

* Swap slot 1 with badges
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
* Swap the Master Ball x1 with Pewter script (Poke Ball x0 many slots down)
* Swap the Master Ball again with Route 4 script (down 1)
* Withdraw all-but-1 Pewter Gym script (down 1)
* Withdraw all-but-1 Route 3 script (up 2)
* Swap the Master Ball x1 with Route 11 script (down, 11 from Ultra Ball x0)
* Withdraw all-but-1 Route 20 script (down 2)
* Withdraw all-but-1 Route 16 script (up 1)
* Withdraw all-but-1 Route 21 script (up 4)
* Withdraw all-but-1 Route 17 script (up 1)

Leave the center using the left doormat tile to warp to Celadon then enter the mart from the right door.

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

Your money should be **$49xx** after you buy all the items listed.

### Item Underflow #2

<img align="right" src="https://user-images.githubusercontent.com/22380063/155201353-2a7c0569-d55b-45af-83f4-2ca5f864cfa3.png">

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
- Move 3 tiles left
- Swap slot 6 with CANCEL x145 (Jack) in rival name
- Swap vtm in rival name with HM04 in TLP2
- Swap TM18 x42 in x coord with Ice Heal x15 in width
- Toss 6 TM18s
- Flash map (close then open the start menu)
- Swap the TM18s back with Ice Heal x15
- Swap vtm back with the HM04, now in rival name
- Toss 7 from TM41 x80 directly below
- Flash WA4 (press A on it so the Use/Toss window comes up, then press B)
- Throw a Master Ball from TID1 (down 2)

Cure Ekans with the Parlyz Heals directly below, then switch Ekans to slot 1.

For each of the following manips, you do not need to move before saving.

|||
|---|---|
| <img align="right" src="https://user-images.githubusercontent.com/22380063/155202912-aa8ef90d-2602-4a32-ac15-8f5f3b7735e2.png"> 1) Manip **Paras** with <ins>extra text while saving</ins>. **Use 9F** before catching. | <img align="right" src="https://user-images.githubusercontent.com/22380063/155204771-03fcdd86-fe20-4199-9e1a-baa569c925ef.png"> 2) Manip **NidoranF** with `hop1`, `fsback`. **Use 9F** before catching. |
|||
| <img align="right" src="https://user-images.githubusercontent.com/22380063/155205070-72dd5f85-6a63-497a-99b9-76f273c0c5f4.png"> 3) Manip **NidoranM** with `nopal(ab)`, `fsback`. **Use 9F** before catching. | <img align="right" src="https://user-images.githubusercontent.com/22380063/155205193-78e9745f-6233-4a1b-8b7f-705bd85f76a5.png"> 4) Manip **Exeggcute** with `pal(hold)`. (Do not use 9F.) |

After appearing in Lavender, move **4** tiles down to Route 12. Close the menu and catch **Mr. Mime**.

After the trainer fly, open the menu and swap Poke Doll x1 with a Helix Fossil stack way down in underflow.

Fly to Celadon with Pidgey and enter the center, then do the following menu:

- Swap Cascadebadge (already on it) with vtm in rival name
- Swap Ultra Ball x0 in brightness with Master Ball x6 in warping
- Toss 28 Ultra Balls now in warping

Leave the center to warp to Cerulean Cave.

### Cerulean Cave

Walk below the item ball: (you currently have 3 steps of encounter immunity!)

- Swap "4" x77 in map data with Full Restore x77 in text pointer
- Swap 4 again with TM41 in rival name
- Talk to the item ball, catch the **Golem** that appears

Cerulean Cave is filled with Pokemon we call **bonuses**. They are typically evolutions of Pokemon we catch throughout the run. Catching bonuses will save withdrawing the pre-evolution, candying it, watching it evolve, and depositing it. In general, if it's on your screen and you don't have it, catch it unless the notes say otherwise.

Every single wild encounter in Cerulean Cave is a bonus. Proper use of dsum can save a lot of time here. Pokemon worth catching in order from best to worst: **Hypno**, **Kadabra**, **Dodrio**, **Sandslash**, **Magneton**, **Parasect**, **Venomoth**, **Electrode**, **Rhydon**, **Marowak**, **Wigglytuff**, **Raichu**, **Golbat**.

You are limited on box space so do not catch more than 10 of the above (Magneton does not count towards the 10). Do **not** catch Chansey and Ditto, as those will be obtained later.

※ If you catch 3 or less (2 or less if manipped dugtrio) bonuses between Cerulean Cave and Seafoam, you are able to skip the next box change. Shellder manip will have <ins>extra text while saving</ins>.

| |
|---|
| Cerulean Cave 2F |
| ![](https://user-images.githubusercontent.com/22380063/155207962-8666bdc9-e152-4322-b317-ca94d84b0a6c.png) |
| Cerulean Cave 1F (entry floor) |
| ![](https://user-images.githubusercontent.com/22380063/155210392-de79e23e-502a-44ce-a7fb-be5bb2e16839.png) |
| Cerulean Cave B1F |
| ![](https://user-images.githubusercontent.com/22380063/155210328-4e35a86e-c07c-48f6-825f-e57bc02ccd7e.png) |

Catch things on any floor until you are satisfied then go to the basement.

Move **2** tiles above the ladder and open the menu:

- Swap Super Repel x1 with Parlyz Heal x224 in TID2
- Swap Super Repel again with the Old Amber in brightness directly below
- Swap Great Ball x0 in x coord with the Soulbadge in tileset
- Bike down and catch Mewtwo

After Mewtwo, move **3** tiles left then continue to search for an unneeded encounter by alternating up and down steps. LG for Tauros:

- Use 9F
- Swap Awakenings in slot 4 with "4" in rival name
- Swap Awakenings again with HM04 in TLP2
- Toss 32 TM27s in TLP1
- Flash map
- Toss 1 TM27 in TLP1
- Swap Awakenings back with the HM04, now in rival name
- Flash WA4 in options then throw a preoptions Master Ball

<img align="right" src="https://user-images.githubusercontent.com/22380063/155210507-5403055a-7cd3-448c-b9cb-d2528b30b0cc.png">

Manip **Chansey** with <ins>extra text while saving</ins>. You do not need to move before saving for this manip.

In the manipped encounter:

- Swap Parlyz Heal x224 with Thunderbadge in x coord
- Swap TM27 in map ID with the Old Amber in TID2 (**top** Old Amber stack)
- Swap the Master Ball stack in TID1 with the Master Ball stack in preoptions to merge them (swap order matters)
- Throw a preoptions Master Ball

You will be crazywarped to Route 20, close the menu and catch **Alakazam**.

Talk to the item ball to your right and catch **Kangaskhan**.

If you didn't catch **Magneton** in Cerulean Cave: bike upwards to another item ball, talk to it, and catch it. Before menuing, move left as needed so the cave entrance tile will be covered by the start menu.

Open the item bag:

- Swap Thunderbadge in items with Old Amber in map ID
- Swap Thunderbadge again with Pokedex in width
- Fly to Celadon, enter the center, and **change boxes**
- Walk to the **left** doormat tile
- Swap Master Ball x6 in warping with PCEKANS in rival name

Leave the center to warp to Seafoam B2F.

### Seafoam Islands

<img align="right" src="https://user-images.githubusercontent.com/22380063/155216050-2ecc5dc7-937e-4537-8070-28a3cfa67438.png">

Corner bonk to the right of the bottom ladder for encounters.

In your first unneeded encounter LG for **Magikarp**:

- Use 9F
- Swap HM04 in TLP2 with Max Potion x0 in roaming
- Swap HM04 again with BLUE in text pointer
- Swap TM50 x0 1 above with Pokedex, also 1 above
- Flash map
- Swap Pokedex back with TM50 x0
- Swap HM04 back with Max Potion x0 in TLP2
- Flash WA4 in options then throw a preoptions Master Ball

<img align="right" src="https://user-images.githubusercontent.com/22380063/155216348-77707ef5-ed50-4051-998a-cbdfaee8dedc.png">

Manip **Shellder** with `pal`, `fsback` (not cycling yet) if you didn't catch one before the LG, otherwise save and soft reset.

| |
|---|
| Seafoam B3F |
| ![](https://user-images.githubusercontent.com/22380063/155216451-a534d463-8954-4caf-8d73-bbdb3f477588.png) |
| Seafoam B4F |
| ![](https://user-images.githubusercontent.com/22380063/155216476-53785a4b-02c4-47b8-b6c8-cedc9b134ae6.png) |

<img align="right" src="https://user-images.githubusercontent.com/22380063/155216967-0532ff73-4adb-46b2-b5cf-c1dc25d191e7.png">

Hop on the bicycle and take the ladder to B3F. 

Catch **Psyduck** and **Seel**.

Afterwards jack through the wall shown in the picture and take the ladder to the basement.

In the basement catch **Krabby** and **Staryu**, then jack over the water to catch **Articuno**.

Use an Escape Rope from badges. Enter the center and **change boxes**.

Walk to the **left** doormat tile and swap Master Ball x5 in warping with roaming TMs.

Leave the center to warp to Victory Road 2F.

### Victory Road

Take the ladder you appear on by moving **up then down** to avoid an encounter.

After, immediately do the following menu:

- Swap GARY x89 in map data with Thunderbadge in x coord
- Toss all-but-1 from the GARY stack

| |
|---|
| Victory Road 1F |
| ![](https://user-images.githubusercontent.com/22380063/155217252-c1f2cccf-f652-42c3-9750-41644a0ac2d3.png) |

Corner bonk above the ladder for an encounter before hopping on the bicycle.

Catch everything but 1 of: **Machop**, **Geodude**, **Zubat**, **Onix**.

<img align="right" src="https://user-images.githubusercontent.com/22380063/155217410-8b064680-b547-4a9f-8896-d0c84accd0a7.png">

Once you have all but 1, get an encounter on the tile in the picture and LG for **Machamp**:

- Use 9F
- Swap HM04 in TLP2 with Volcanobadge in text pointer
- Flash map
- Swap the HM04 back with the Volcanobadge
- Flash the item in x coord (down 1) then throw a Master Ball from warping
- Save + Quit, manip the final encounter <ins>(read the next part before catching)</ins>

|||
|---|---|
| <img align="right" src="https://user-images.githubusercontent.com/22380063/155217831-e4a7b174-9317-418d-8602-61ac55b33cd2.png"> **Machop** with `pal(hold)` | <img align="right" src="https://user-images.githubusercontent.com/22380063/155217670-b9f38e86-a448-471a-8f9e-18f486d605a4.png"> **Geodude** with `pal` |
|||
| <img align="right" src="https://user-images.githubusercontent.com/22380063/155217999-6d7eefde-8b2f-464f-92c0-4216f7dfcb9d.png"> **Zubat** with `pal(hold)` | <img align="right" src="https://user-images.githubusercontent.com/22380063/155218039-da4427d6-f9ed-4753-bb6b-36b84076143c.png"> **Onix** with `pal(hold)`, `fsback` |

In the manipped encounter:

- Swap Cascadebadge with the nameless item in map ID (above HM04)
- Swap the item in x coord (down 2) with Pokedex in width
- Swap j. x197 in warping with Pokedex in roaming
- Throw a Master Ball (up 3)

### Route 11 #1

<img align="right" src="https://user-images.githubusercontent.com/22380063/155220877-f95c72e3-015f-49e4-b41c-4366e13e74c7.png">

You will be crazywarped to Route 11, close the menu and catch **Scyther**.

The sprites may be in different positions relative to the map graphics, so always use the sprites for positioning.

Talk to the sailor to your right and catch **Moltres**.

Bike upwards to an item ball, talk to it, and catch **Koffing**. <ins>Warning:</ins> out of bounds is the row above the item ball.

<img align="right" src="https://user-images.githubusercontent.com/22380063/155221028-d5b336ea-eac5-4996-ba41-445ac81cce74.png">

After both crazywarp catches, move to the tile shown in the picture (relative to sprite positions) and use jack while facing down. Move **7** tiles left into Vermilion, then hold right until you enter Diglett's Cave.

Catch at least a **Diglett**, then leave the cave and head back to Route 11.

### Route 11 #2

<img align="right" src="https://user-images.githubusercontent.com/22380063/155221175-2de3147e-e7e1-4168-a95b-bbc0b7546b22.png">

Search for wild encounters near the gambler to the south.

Catching random Drowzee or Sandshrew is generally not worth it unless they are level 13+ or level 14+ respectively.

"Natural" LGs are done by doing the following in a wild encounter:

- Use 9F
- Move to the tile pictured
- Flash "4" then throw a Master Ball

In your first unneeded encounter LG for **Growlithe** (**unjack** and move to the tile).

Manip **Drowzee** if you still need it. If it's already caught, manip **Sandshrew** instead. If you caught both of them already, move to one of the Metapod tiles then **use** "4" to generate a Metapod encounter and run away from it.

|||
|---|---|
| <img align="right" src="https://user-images.githubusercontent.com/22380063/155221425-8f8b5ea3-d1c3-4c62-b0ec-d44cb575b8c8.png"> Drowzee with `nopal(ab)` | <img align="right" src="https://user-images.githubusercontent.com/22380063/155221512-2ebad2f9-9444-4ce0-a9b8-4cbb9478b678.png"> Sandshrew with `pal`, `hop1` |

Get another wild encounter and LG for **Venonat**.

If you did not catch Venomoth, flash "4" on the Hitmonchan tile before moving to the Venonat tile (to make Venonat come at a higher level).

Manip **Sandshrew** if you still need it (**unjack** and move to the Growlithe tile), otherwise follow the Metapod instructions above.

Get a final wild encounter and LG for **Hitmonchan**. Fly to Celadon directly after.

Enter the center and **change boxes**. Open the menu while at the PC:

- Swap jack in slot 6 with Fire Stone x15
- Swap jack again with Moon Stone x10 in roaming
- Swap jack again with north connection (j. x255)
- Swap HM04 in TLP2 with Ultra Ball x0 in brightness

Walk **1** tile up and **buffer Start** to enter Tower 4F.

### Pokemon Tower + Route 21

Manip **Gastly**. If the manip fails due to IGT, do the backup manip instead of resaving.

|||
|---|---|
| <img align="right" src="https://user-images.githubusercontent.com/22380063/155223053-bc334cef-9a42-485f-b824-6873447ebf55.png"> Primary with `pal`, `hop1`, `fsback x2` | <img align="right" src="https://user-images.githubusercontent.com/22380063/155223196-aff75d95-f606-4b3c-ae51-f9df929687f8.png"> Backup with `nopal(ab)`, `gfwait` |

In the manipped encounter:

- Swap Fire Stone x15 in slot 6 with CANCEL x95 in map ID
- Throw a preoptions Master Ball

You will be crazywarped to Route 21. Hop on the bicycle in the trainer fly menu, then catch the **Magmar** that appears.

An item ball will walk to you; catch **Vulpix**. Bike down to talk to the item ball and catch **Fearow**. Bike left then up to talk to the last item ball and catch **Gengar**. <ins>Warning:</ins> the fisherman has a range of 4, do not get seen while he is still there.

<img align="right" src="https://user-images.githubusercontent.com/22380063/155223492-5b3fa58c-00ff-4ae1-be23-e01d540ac243.png">

Search for wild encounters on the tile in the picture. Only catch Pidgeotto if it's level 32, **never** catch Tangela.

LG for **Tentacool** in your first unneeded encounter:

- Use 9F
- Swap HM04 in TLP2 in with Bike Voucher in width
- Swap HM04 again with Moon Stone x0 in x coord
- Swap HM04 again with Soulbadge in tileset
- Flash map
- Swap HM04 again with Moon Stone x0 in width
- Swap HM04 again with Bike Voucher in TLP2
- Flash WA4 in options then throw a preoptions Master Ball

Manip **Pidgeotto** if you still need it, otherwise save and soft reset.

|||
|---|---|
| <img align="right" src="https://user-images.githubusercontent.com/22380063/155223722-fbc2477c-097b-48c4-a9eb-a677163dc575.png"> Primary with `fsback` | <img align="right" src="https://user-images.githubusercontent.com/22380063/155223832-576144a4-b8ab-4ba7-826f-f4cdc0ef35ea.png"> Backup with `pal(hold)`, `hop1` |

<img align="right" src="https://user-images.githubusercontent.com/22380063/155224069-e99764c4-9e0e-49af-b7ef-1a72b028c549.png">

Find another encounter, now on the tile in this picture, and LG for **Charmander**:

- Use 9F
- Swap Burn Heal in inventory with Poke Flute in money
- Swap Burn Heal again with Ultra Ball x0 in brightness
- Swap Burn Heal again with HM04 in TLP2
- Toss 8 from the Fire Stone stack above (map ID)
- Flash map
- Toss 8 from the Fire Stone stack again
- Swap Burn Heal back with the HM04
- Flash WA4 in options then throw a preoptions Master Ball

Manip **Tangela** with `pal(hold)`, `fsback x2`. You do not need to move before saving for this manip.

| |
|---|
| ![](https://user-images.githubusercontent.com/22380063/155224196-20cf4ec0-f553-4b8b-9c6e-069c54868427.png) |

Fly to Celadon directly after.

### Route 16

In Celadon move **1** tile left, swap Great Ball in inventory with Rare Candy x0 in x coord, then hop on the bicycle in map ID.

<img align="right" src="https://user-images.githubusercontent.com/22380063/155224630-4849b62e-8389-4cc9-8752-0b0913f71bea.png">

Follow the path shown, it will lead you to Route 16 with a trainer fly waiting. Catch the **Dragonite** that appears.

Use jack to get on the tree to the right of **Snorlax**, then play the Poke Flute to wake it up (no need to unjack for this).

| |
|---|
| Route 16 |
| ![](https://user-images.githubusercontent.com/22380063/155224776-0d3391f1-a81e-4248-be17-89ceecb15e8f.png) |

Just like in Victory Road, catch everything but 1 of: **Spearow**, **Rattata**, and **Doduo**.

<img align="right" src="https://user-images.githubusercontent.com/22380063/155224893-2e6b214b-a228-408f-abce-f57bf9589b19.png">

In the first unneeded encounter LG for **Rhyhorn**.

After catching Rhyhorn, move **1** tile up, **swap Master Balls into slot 1** (swap with Bicycle), then **use** "4" and catch the **Metapod** that appears.

Undo the swap the next time you open the item menu.

After having caught all but 1 from the list above, get an encounter and LG for **Kabuto**.

If you are missing Spearow or Doduo use "4" on the **right** Horsea tile, or if you are missing Rattata use it on the **left** Horsea tile.

Run from the Metapod encounter (which gives you flipped sprites!).

Alternate up and down steps until you get an encounter, then do the following:

- Use 9F
- Open items (do **not** flash map or trainer card)
- Flash "4" and throw a Master Ball to catch **Horsea**
- Swap the unnamed item in rival name (from Victory Road) with x coord, which is either a Repel or an Escape Rope
- Save + Quit, manip the final encounter

||||
|---|---|---|
| <img align="right" src="https://user-images.githubusercontent.com/22380063/155227880-cd7f4005-fa99-4374-8b07-92d91034d899.png"> Spearow with `pal`, `hop2` | <img align="right" src="https://user-images.githubusercontent.com/22380063/155228075-bf9e6ed4-32b7-4b31-b4b7-75b9287968d3.png"> Rattata with `nopal(ab)` | <img align="right" src="https://user-images.githubusercontent.com/22380063/155228124-3bf4fc67-3adc-437d-a932-c9ac75fae7b7.png"> Doduo with `nopal(ab)`, `fsback` |

After the manip encounter ends, bike left until you are outside the grass, then hold down until the start menu opens. Fly to Pewter and catch **Mew**.

### Pewter City + Route 3

Enter the center, **change boxes**, then leave the center.

Use jack and bike to the **right** of the gym guy used for Brock Through Walls. Unjack and talk to him, then while holding Select move right until a trainer fly ("brock fly") textbox opens. Close it and catch the **Goldeen**.

<img align="right" src="https://user-images.githubusercontent.com/22380063/155230903-4dca417f-5de6-4d10-b895-577f7b027b87.png">

After the brock fly, open the item menu, swap jack in slot 6 with Fire Stone x99, then toss 12 from Awakening x182 in map ID. You are now on the green tile in the picture, bike to the grass to search for an encounter.

<ins>Warning:</ins> if you go 1 tile too far left you will be back in Pewter.

Catch the encounter if it's a **Jigglypuff**, otherwise LG for **Cubone**.

<img align="right" src="https://user-images.githubusercontent.com/22380063/155231104-b126ccb5-3bcc-4a3d-8d8b-d43671567926.png">

Manip Jigglypuff with `gfwait` if you still need one. If it's already caught, move to the Metapod tile in the picture then **use** "4" to generate a Metapod encounter and run away from it.

Bike back to the tile you arrived at originally and move **1** tile left to return to Pewter. After the gym guy's text, move right then left to reload Pewter, then go left some more and talk to the gym guy again. While holding B, make your way towards the gym. **Flash the start menu** before entering.

In the trainer fly menu do the following:

- Swap Super Potion x83 from inventory with Ultra Ball x0 in brightness
- Swap Super Potion x83 again with j. x2 in warping

Exit the menu and catch **Oddish**. Exit the gym to warp to the Power Plant.

### Power Plant

| |
|---|
| ![](https://user-images.githubusercontent.com/22380063/155231318-4cd11fcb-1059-496f-9cd0-70821a3ff11a.png) |

Dsum for either a **Magnemite** or a **Pikachu** (the other can be manipped later). Do not catch Voltorb. At some point, talk to **Zapdos** and catch it too.

<img align="right" src="https://user-images.githubusercontent.com/22380063/155231422-82e3f61f-d382-4a60-8a3f-f6bb63a1365c.png">

After Zapdos, walk to the tile in the picture and do the following:

- Swap Fire Stone x99 in slot 6 with jack
- Swap Awakening x20 in rival name with HM04 in TLP2
- Toss all-but-8 from Max Elixer x136 above
- Walk **1** tile right and talk to the ball, catch **Voltorb**

<img align="right" src="https://user-images.githubusercontent.com/22380063/155231511-515dbf5b-804f-4d26-bca7-3696e08124e3.png">

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
- Toss 4 from JACK x255 one slot above (if not tossable, flash toss Antidotes)
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

Enter the center and **change boxes**.

Use Bicycle in map ID to bike to the prize corner and purchase:

- **Pinsir**, **Porygon**, and **Dratini** from the middle window,
- **Abra**, **Nidorino**, and **Clefairy** from the left window.

Leave the prize corner and bike to Route 7.

| |
|---|
| Route 7 |
| ![](https://user-images.githubusercontent.com/22380063/155231986-40c01ff4-7b5c-47f0-b273-1d00abd90e3f.png) |

<img align="right" src="https://user-images.githubusercontent.com/22380063/155232081-501b77f1-ef5a-4aec-90fd-726dd724b8ef.png">

Dsum for either a **Bellsprout** or a **Meowth** (the other can be manipped later).

In your first unneeded encounter you will LG for Mankey. The tile you move to depends on what you will do after the LG:

If you still need **Bellsprout** or **Meowth**, move to the **left Mankey tile** and manip after.

If you caught both, move to the **right Mankey tile** and utilize the Metapod tile after. Move to the Metapod tile in the picture then **use** "4" to generate a Metapod encounter and run away from it.

|||
|---|---|
| <img align="right" src="https://user-images.githubusercontent.com/22380063/155232249-5ef53d1b-cb1a-4f44-b928-76453dcc7ed5.png"> Bellsprout | <img align="right" src="https://user-images.githubusercontent.com/22380063/155232305-663439c8-3e4f-49d3-9b0b-00649cf60e90.png"> Meowth with `pal`, `hop2`, `fsback` |

After having caught Bellsprout and Meowth, get an encounter and LG for **Ivysaur**:

<img align="right" src="https://user-images.githubusercontent.com/22380063/155237933-970b3299-115c-4ca9-81cb-0a9353c32c4f.png">

- Use 9F
- Unjack, enter the guardhouse to your right
- Walk **1** tile right and **1** tile up, face left
- Swap Helix Fossil with HM03 in TLP2
- Swap Ultra Ball x0 in brightness with Master Ball x18 in warping
- Toss 21 Ultra Balls
- Flash map
- Flash WA4 in options then throw a preoptions Master Ball
- Swap HM03, now in inventory, with Helix Fossil in TLP2

**Hold left** to leave the guardhouse and warp to Silph Co 11F.

Take the teleporter pad you arrive on, talk to the hostage to receive **Lapras**, and take the teleporter pad back to 11F.

<img align="right" src="https://user-images.githubusercontent.com/22380063/155238058-73db5f2b-b3ce-4598-8b11-38b3b0645f42.png">

From the teleporter walk **2** tiles left then **2** tiles down (must be facing downwards).

LG for **Weedle**:

- Swap HM04 in TLP2 with Master Ball x0 in x coord
- Swap Moon Stone x16 in tileset with Pokedex in width
- Toss 3 Moon Stones
- Flash **trainer card**
- Swap the Moon Stones back with the Pokedex
- Toss all-but-8 from the j. x255 in north connection
- Toss the entire TM50 stack below
- Flash "4" and throw a Master Ball

Walk **1** tile up (hold up, there is a long delay before you can move). After, flash the start menu, walk **1** tile down and **1** tile up to enter Cinnabar center.

### Cinnabar Island

Inside the center, swap Revive x93 with Master Ball x118 in TID1, then again with Poke Doll x94 in text pointer. Talk to Nurse Joy, who now revives fossils, and give her a Helix Fossil. **Undo the last swap** then leave the center.

Enter the center again and swap the Revives with the Poke Dolls again. Talk to Nurse Joy to receive **Omanyte**, give her an Old Amber, and **undo the swap**. **Change boxes** then leave the center.

<img align="right" src="https://user-images.githubusercontent.com/22380063/155238352-33ca15a1-de1c-42c8-aa03-3638d3ea3e2a.png">

Enter the center again(!) and walk to the tile in the picture. Swap the Revives with the Poke Dolls one more time, then LG for **Jynx**:

- Swap Card Key in map data with HM04 in TLP2
- Flash map
- Swap Card Key back with HM04, now in map data
- Flash WA4 in options then throw a preoptions Master Ball
- Catch **Ditto** by throwing another preoptions Master Ball
- Unjack

Talk to Nurse Joy to receive **Aerodactyl**. Leave the center (don't undo any swaps).

<img align="right" src="https://user-images.githubusercontent.com/22380063/155238435-f4cfbc6b-8606-435c-b341-9d5f455f3a44.png">

Walk to the tile in the picture to do the first menu:

- Swap Poke Doll x94, now in TID1, with Pokedex in north connection (**second** Pokedex scrolling down)
- Swap Poke Dolls again with TM35 x198 (down 2)
- Toss 33 TM35s
- Swap Poke Dolls again with "44yPC" in text pointer
- Toss 1 Poke Doll

<img align="right" src="https://user-images.githubusercontent.com/22380063/155238508-323b1e62-a770-40f8-96cb-76350e373f61.png">

Walk below the sign next to the gym and **face right** to do the second menu:

- Swap Pokedex in width with Moon Stone x0 in tileset
- Toss 17 Moon Stones
- Swap HM04 in TLP2 with Ultra Ball x0 in brightness
- Toss all-but-3 Ultra Balls
- Flash map

The setup for "Eevee Factory" is now complete. Follow the instructions to catch **Lickitung**, **Eevee**, **Slowpoke**, **Eevee**, **Poliwag**, and **Eevee**.

<img align="right" src="https://user-images.githubusercontent.com/22380063/155238660-e320ae90-4f55-421b-aa7f-0031ab93bd4d.png">

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
- Unjack, close the menu
- <ins>Hold left (not up)</ins> to walk **1** tile left, **1** tile up, **2** tiles left, **3** tiles down
- Face left and press A to receive **Eevee**

Walk **4** tiles up to enter Mansion 1F.

### Cinnabar Mansion

| |
|---|
| ![](https://user-images.githubusercontent.com/22380063/155238988-996874dd-64a3-44ba-8e2d-ae382844b9d3.png) |

Dsum for both **Grimer** and **Ponyta**. Muk and Weezing can appear as bonuses.

<img align="right" src="https://user-images.githubusercontent.com/22380063/155239034-096427ec-bd9c-458d-851f-d7fe50f052ac.png">

Jack through the wall to your right, then corner bonk on the tile in the picture for encounters (you do not need to unjack).

In your first unneeded encounter LG for **Electabuzz**:

- Use 9F
- Swap Poke Flute in inventory with HM05 in TLP2
- Flash map
- Flash WA4 in options then throw a preoptions Master Ball

<img align="right" src="https://user-images.githubusercontent.com/22380063/155239094-66eee864-7bea-4c95-9512-d0c63e5599ae.png">

Manip **Weezing** with <ins>extra text while saving</ins>, or if you somehow caught one naturally, manip **Muk** instead.

|||
|---|---|
| Weezing | `pal`, `hop2`, `fsback`, `D S_B R R R` |
|||
| Muk | `nopal(ab)`, `fsback`, `D` |

After having caught Grimer, Ponyta, and Weezing, use an Escape Rope <ins>from badges</ins>, then enter Vermilion center.

### Audio Fade Out ("AFO")

Walk below the PC, face up, and menu to set up the AFO glitch city:

- Swap HM04 in TLP2 with Master Ball x5 in warping
- Toss 1 from the Master Balls you just swapped
- Swap HM04 again for the j. x255 in north connection
- Swap roaming TMs for Poke Ball x7 in width
- Toss 6 TMs
- Flash map
- Toss the entire stack of Parlyz Heal x65 below
- Swap "4" with Ultra Ball x0 in inventory (above Rare Candies)

In this glitch city, flashing "4" will cause the audio to fade out for about 33 seconds. All jingles do not have a delay during the fade out, such as using Rare Candies, the cries when depositing and withdrawing Pokemon, and changing boxes. An evolution will cause the fade out to end immediately, so flash 4 again after each one. (You shouldn't bother scrolling to and flashing 4 for stone evolutions.)

Evolve everything you need to in boxes 7 through 2 this way. (Box 1 will always be filled with Pokemon that do not evolve.)

When done, deposit all but 1 Pokemon then do the following menu:

- Swap Master Ball x118 (above "4") with HM04 in north connection (**second** HM04 scrolling down)
- Swap "F" in text pointer (up 2) with TM40 x192 in width
- Swap Master Ball x4 in TLP2 with Ultra Ball x0 in brightness

<img align="right" src="https://user-images.githubusercontent.com/22380063/155239403-28ea962b-fd79-4a2e-9027-30c5f26140eb.png">

Walk **1** tile up to warp to the Hall of Fame!

Timing ends when the screen fully fades to white after 151 Pokemon are displayed in the Pokedex.

### The End

## RNG Manipulations

|||
|---|---|
| ![](https://user-images.githubusercontent.com/22380063/155239721-a1eb1599-de1f-424d-9cb5-e4f40d564601.png) | Pidgey into Caterpie Manip<br>[Pokeworld Link 1](https://gunnermaniac.com/pokeworld?local=13#4/56/UUAURAURRURAU) \| [Pokeworld Link 2](https://gunnermaniac.com/pokeworld?local=13#8/50/LRRU)<br>nopal(ab), fastest buffers<br><br>59/60 pidgey, 56/60 extended<br>Frame 15: Caterpie yoloball fail<br>Frame 36: No Pidgey encounter<br>Frame 37: No Caterpie encounter<br>Frame 47: Rattata encounter on extended |
|||
| ![](https://user-images.githubusercontent.com/22380063/155239981-893caa0e-02ac-472f-974d-442d1e74d6e4.png) | Non-extended Caterpie Manip<br>[Pokeworld Link](https://gunnermaniac.com/pokeworld?local=51#21/43/UURRRRUUUUUUUUUUUUUUUUUUUUUUUUUUUUUUUULLLLLLLLDDDDDDDLLLLLAUUUUUUUUUUUAUUALLLLDDADDDDDDDDDDDDDDLLAD)<br>nopal, fastest buffers<br><br>57/60<br>Frame 25: Caterpie yoloball fail<br>Frame 36: [Metapod encounter](https://gunnermaniac.com/pokeworld?map=51#25/25)<br>Frame 37: [Kakuna encounter](https://gunnermaniac.com/pokeworld?map=51#12/16) |
|||
| ![](https://user-images.githubusercontent.com/22380063/155240101-2aacf855-ff67-4e13-a1a1-e937797577e1.png) | Diglett's Cave Manip<br>[Pokeworld Link](https://gunnermaniac.com/pokeworld?local=197#5/5/DDDDDDDDDADDDARRRADDDADRRRRDDDDADDDDRRRRRRARRRRRRDRRRRRRRRRRRRRD)<br>pal, fastest buffers<br><br>58/60<br>Frame 30: [L15 Diglett encounter](https://gunnermaniac.com/pokeworld?map=197#5/7)<br>Frame 36: [L16 Diglett encounter](https://gunnermaniac.com/pokeworld?map=197#5/9) |
|||
| ![](https://user-images.githubusercontent.com/22380063/155240101-2aacf855-ff67-4e13-a1a1-e937797577e1.png) | Dugtrio Manip<br>[Pokeworld Link](https://gunnermaniac.com/pokeworld?map=197#5/5/DDDDDDDDDADDDARRRADDDADRRRRDDDDADDDDRRRRRRARRRRRRDRRRARRRS_BRRRRDDDRRUUU)<br>pal, fastest buffers<br><br>56/60<br>Frame 29: Dugtrio yoloball fail<br>Frame 30: [L15 Diglett encounter](https://gunnermaniac.com/pokeworld?map=197#5/7)<br>Frame 36: [L16 Diglett encounter](https://gunnermaniac.com/pokeworld?map=197#5/9)<br>Frame 37: [L19 Diglett encounter](https://gunnermaniac.com/pokeworld?map=197#34/31) |
|||
| ![](https://user-images.githubusercontent.com/22380063/155242113-a76502e3-3b09-4191-a0d8-d6896b174a42.png) | Deathfly Manip<br>[Pokeworld Link](https://gunnermaniac.com/pokeworld?local=22#4/6/RRRRARRRRU)<br>nopal(ab), fastest buffers<br><br>58/60<br>Frame 25: Sandshrew uses Sand Attack<br>Frame 36: No encounter |
|||
| ![](https://user-images.githubusercontent.com/22380063/155242196-b5fd4731-8c52-4139-aed4-af88fb594443.png) | Paras Manip<br>[Pokeworld Link](https://gunnermaniac.com/pokeworld?local=217#5/1/DDDDDRRRRRRR)<br>nopal, fastest buffers<br><br>59/60<br>Frame 36: No encounter |
|||
| ![](https://user-images.githubusercontent.com/22380063/155242305-a04cf28b-708a-43bd-99d9-371b806eeca1.png) | Nidoran Female Manip<br>[Pokeworld Link](https://gunnermaniac.com/pokeworld?local=217#12/1/RR)<br>nopal, hop1, fsback<br><br>60/60 |
|||
| ![](https://user-images.githubusercontent.com/22380063/155242358-976c19c8-5cee-4d0b-9480-a14ea43d80b2.png) | Nidoran Male manip<br>[Pokeworld Link](https://gunnermaniac.com/pokeworld?local=217#14/1/RRRAR)<br>nopal(ab), fsback<br><br>59/60<br>Frame 58: No encounter |
|||
| ![](https://user-images.githubusercontent.com/22380063/155242438-b9b35463-f7b3-4f18-9318-bec2c9eeea26.png) | Exeggcute Manip<br>[Pokeworld Link](https://gunnermaniac.com/pokeworld?local=217#18/1/RRRDADDDDRR)<br>pal(hold), fastest buffers<br><br>58/60<br>Frame 36: No encounter<br>Frame 37: Pidgey from dv fly |
|||
| ![](https://user-images.githubusercontent.com/22380063/155242502-ee4c6cce-58ab-4e0a-8920-debf1719bb7b.png) | Chansey Manip<br>[Pokeworld Link](https://gunnermaniac.com/pokeworld?local=227#19/1/US_BUUU)<br>nopal, fastest buffers<br><br>58/60<br>Frame 36: No encounter<br>Frame 37: Starmie from dv fly |
|||
| ![](https://user-images.githubusercontent.com/22380063/155242601-69dacf8b-c2fb-491b-bf18-afb4f38a66ef.png) | Shellder Manip<br>[Pokeworld Link](https://gunnermaniac.com/pokeworld?local=160#26/14/US_BL)<br>pal, fsback<br><br>59/60<br>Frame 36: No encounter |
|||
| ![](https://user-images.githubusercontent.com/22380063/155242690-53a6a9a2-6717-4d23-a5b6-c8a2b94efeb7.png) | Machop Manip<br>[Pokeworld Link](https://gunnermaniac.com/pokeworld?local=194#15/0/DDDDDDS_BRRRRRRRS_BLL)<br>pal(hold)<br><br>58/60<br>Frame 36: No encounter<br>Frame 37: No encounter |
|||
| ![](https://user-images.githubusercontent.com/22380063/155242690-53a6a9a2-6717-4d23-a5b6-c8a2b94efeb7.png) | Zubat Manip<br>[Pokeworld Link](https://gunnermaniac.com/pokeworld?local=194#15/0/DDDDDARRRRS_BR)<br>pal(hold)<br><br>58/60<br>Frame 36: No encounter<br>Frame 37: Blastoise from dv fly |
|||
| ![](https://user-images.githubusercontent.com/22380063/155242690-53a6a9a2-6717-4d23-a5b6-c8a2b94efeb7.png) | Onix Manip<br>[Pokeworld Link](https://gunnermaniac.com/pokeworld?local=194#15/0/RRRADDDS_BRRRR)<br>pal(hold), fsback<br><br>58/60<br>Frame 58: No encounter<br>Frame 59: Tangela from dv fly |
|||
| ![](https://user-images.githubusercontent.com/22380063/155242690-53a6a9a2-6717-4d23-a5b6-c8a2b94efeb7.png) | Geodude Manip<br>[Pokeworld Link](https://gunnermaniac.com/pokeworld?local=194#15/0/DDDDDDDARRRRRRRS_BLL)<br>pal<br><br>58/60<br>Frame 36: No encounter<br>Frame 37: [L39 Onix encounter](https://gunnermaniac.com/pokeworld?local=194#15/6) |
|||
| ![](https://user-images.githubusercontent.com/22380063/155242946-33c9af46-fac5-4d29-8f35-adce851f8563.png) | Sandshrew Manip<br>[Pokeworld Link](https://gunnermaniac.com/pokeworld?local=22#15/17/UUUUUARR)<br>pal, hop1<br><br>59/60<br>Frame 36: No encounter |
|||
| ![](https://user-images.githubusercontent.com/22380063/155242946-33c9af46-fac5-4d29-8f35-adce851f8563.png) | Drowzee Manip<br>[Pokeworld Link](https://gunnermaniac.com/pokeworld?local=22#15/17/UUURR)<br>nopal(ab), fastest buffers<br><br>58/60<br>Frame 36: No encounter<br>Frame 37: [L13 Spearow encounter](https://gunnermaniac.com/pokeworld?local=22#17/14) |
|||
| ![](https://user-images.githubusercontent.com/22380063/155243080-e7ec74ac-a629-494a-be9b-19dc4a4db58d.png) | Primary Gastly Manip<br>[Pokeworld Link](https://gunnermaniac.com/pokeworld?local=145#3/9/DRDRRRADRRRADRR)<br>pal, hop1, fsback, fsback<br><br>58/60<br>Frame 20: Arbok from dv fly<br>Frame 21: No encounter |
|||
| ![](https://user-images.githubusercontent.com/22380063/155243080-e7ec74ac-a629-494a-be9b-19dc4a4db58d.png) | Backup Gastly Manip<br>[Pokeworld Link](https://gunnermaniac.com/pokeworld?local=145#3/9/DRDRDDRADRRRARURR)<br>nopal(ab), gfwait<br><br>56/60 (works on the missing 2/60 above)<br>Frame 19; 36; 37; 48: No encounter |
|||
| ![](https://user-images.githubusercontent.com/22380063/155243233-db085d0e-18db-42ca-a222-b654a5371c3e.png) | Primary Pidgeotto Manip<br>[Pokeworld Link](https://gunnermaniac.com/pokeworld?local=32#10/4/RRR)<br>nopal, fsback<br><br>59/60<br>Frame 58: No encounter |
|||
| ![](https://user-images.githubusercontent.com/22380063/155243233-db085d0e-18db-42ca-a222-b654a5371c3e.png) | Backup Pidgeotto Manip<br>[Pokeworld Link](https://gunnermaniac.com/pokeworld?local=32#10/4/RRRDDD)<br>pal(hold), hop1<br><br>59/60 (works on the missing 1/60 above)<br>Frame 36: No encounter |
|||
| ![](https://user-images.githubusercontent.com/22380063/155243360-2f90c839-c3da-4c08-93f9-1fafebf5d4e2.png) | Tangela Manip<br>[Pokeworld Link](https://gunnermaniac.com/pokeworld?local=32#13/2/DDDD)<br>pal(hold), fsback, fsback<br><br>58/60<br>Frame 20: No encounter<br>Frame 21: Missingno. from dv fly |
|||
| ![](https://user-images.githubusercontent.com/22380063/155243459-5b16cad6-61a7-45ce-a330-ec4553330dce.png) | Rattata Manip<br>[Pokeworld Link](https://gunnermaniac.com/pokeworld?local=27#28/5/DDDDADDD)<br>nopal(ab), fastest buffers<br><br>59/60<br>Frame 36: [L20 Doduo encounter](https://gunnermaniac.com/pokeworld?local=27#28/12) |
|||
| ![](https://user-images.githubusercontent.com/22380063/155243578-3f2d632e-fcab-4b33-a8ff-cfbbc4985d91.png) | Spearow Manip<br>[Pokeworld Link](https://gunnermaniac.com/pokeworld?local=27#29/5/DD)<br>pal, hop2<br><br>59/60<br>Frame 36: Rhyhorn from dv fly |
|||
| ![](https://user-images.githubusercontent.com/22380063/155243689-7992993b-75a5-4c60-a7ae-bd82db60331d.png) | Jigglypuff Manip<br>[Pokeworld Link](https://gunnermaniac.com/pokeworld?local=14#58/0/DDDDDDDDRR)<br>nopal, gfwait<br><br>59/60<br>Frame 36: No encounter |
|||
| ![](https://user-images.githubusercontent.com/22380063/155243713-8ae3be99-68fe-42b5-be14-3b681b7ad61a.png) | Magnemite Manip<br>[Pokeworld Link](https://gunnermaniac.com/pokeworld?local=83#8/11/DDURD)<br>pal(hold), fastest buffers<br><br>58/60<br>Frame 36: No encounter<br>Frame 37: [L24 Pikachu encounter](https://gunnermaniac.com/pokeworld?local=83#9/13) |
|||
| ![](https://user-images.githubusercontent.com/22380063/155243713-8ae3be99-68fe-42b5-be14-3b681b7ad61a.png) | Pikachu Manip<br>[Pokeworld Link](https://gunnermaniac.com/pokeworld?local=83#8/11/DDUUUDD)<br>pal, fastest buffers<br><br>59/60<br>Frame 36: No encounter |
|||
| ![](https://user-images.githubusercontent.com/22380063/155243747-13bbc95e-5e28-47a2-bf27-c1a5430d9013.png) | Bellsprout Manip<br>[Pokeworld Link](https://gunnermaniac.com/pokeworld?local=18#8/15/UUUAUUUUUUU)<br>nopal, fastest buffers<br><br>59/60<br>Frame 36: No encounter |
|||
| ![](https://user-images.githubusercontent.com/22380063/155243747-13bbc95e-5e28-47a2-bf27-c1a5430d9013.png) | Meowth Manip<br>[Pokeworld Link](https://gunnermaniac.com/pokeworld?local=18#8/15/UUUAUUUUUUAUUU)<br>pal, hop2, fsback<br><br>60/60 |
|||
| ![](https://user-images.githubusercontent.com/22380063/155243814-032c853b-3944-4829-b772-c1625eb24992.png) | Weezing Manip<br>[Pokeworld Link](https://gunnermaniac.com/pokeworld?local=165#12/26/DS_BRRR)<br>pal, hop2, fsback<br><br>58/60<br>Frame 58: No encounter<br>Frame 59: [L37 Muk encounter](https://gunnermaniac.com/pokeworld?local=165#15/27) |
|||
| ![](https://user-images.githubusercontent.com/22380063/155243814-032c853b-3944-4829-b772-c1625eb24992.png) | Muk Manip<br>[Pokeworld Link](https://gunnermaniac.com/pokeworld?local=165#12/26/D)<br>nopal(ab), fsback<br><br>60/60 |

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
