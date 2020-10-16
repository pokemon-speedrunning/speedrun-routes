# Pokemon Blue Catch 'Em All (Classic) aka 151 FTL
**CLEAR SAVE DATA FOR EACH ATTEMPT OR YOUR RUN IS INVALID**

Credits to luckytyphlosion for routing this and also writing the [original guide](https://pastebin.com/c5F57GVX)

If something isn't clear, you should watch:
  - **[1024 Charmander]** [stocchi's run (with input display)](https://youtu.be/ZFTXVDj3j14)
  - **[PP/Pidgey Strat]** [krazyd4n's run](https://youtu.be/KHEn7tNtpcA)

## Intro

- [Manip TID 0x765e (30302)](https://youtu.be/jB4u4UU4gyU)
- Name player baaaa
- Name rival ??//;;
	- note: input rival name to 7 characters, then delete last char to get proper rival name to save a bit on tossing ethers
	- i.e. input rival name to be ??//;;;, then press B to make rival name ??//;;

## Brock Through Walls

The first glitch we will perform is called Brock Through Walls.
A detailed guide on what strategy could be best for you and how to execute it can be found [here](/gen-1/red-blue/catext/reverse-badge-acquisition/resources/Brock-Through-Walls-Guide)

- **[PP/Pidgey Strat]** Viridian shop: buy
	- 10 Pokeballs
- Pick up forest antidote
- Pick up forest potion
- Fight Weedle Guy
- **[PP/Pidgey Strat]** Pewter shop: buy
  - 1escape rope  
  - 1 parlyz heal
  - 1 burn heal
  - 1 awakening
- **[1024 Charmander]** Pewter shop: buy
  - 9 Pokeballs
    - 10 if you didn't use your antidote
  - 1 burn heal
  - 1 escape rope
  - 1 antidote
    - skip if you didn't use it
  - 1 parlyz heal
- brock through walls as explained in the guide linked above

## CoolTrainer

- Your goal is to reach Mewtwo Cave, the fastest path is shown [here](https://youtu.be/7jT0nZStQNU)
	- take this path carefully: you are walking out of bounds, one false step can crash the game
- **[1024 Charmander]** Ditto manip:
	- [redbar](https://www.youtube.com/watch?v=zofvpQK4dFQ)
	- [non redbar](https://www.youtube.com/watch?v=aIE01IgqhFw&list=PLFAPrbMDJZ2LS1c8W46jPxlMB5QQpyKMv&index=4)
- **[PP/Pidgey Strat]** [Ditto manip](https://youtu.be/alE01lgqhFw)
- Swap ditto to front, use escape rope
- Get CoolTrainer glitch:
	- encounter any Rattata or a lv5 Pidgey
	- in the encounter, use trasform, then swap your moves order and run away
- Pokedex menu flash on [grass tile next to side of ledge](https://i.imgur.com/Bbh6R3V.png)
	- can do this before getting CoolTrainer, as long as you do not open any submenu
- Double distort missingno:
	- view CoolTrainer until corruption
	- flash item menu
	- view CoolTrainer again until another corruption
	- do this fast enough and get first ball missingno to skip missingno cry
	- you can also view CoolTrainerT again if audio completely fades out and you haven't caught missingno by then for another chance at skipping missingno's cry
- Toss awakening x2, double distort again (no need to worry about missingno cry this time)

## FTL Setup

- Walk to [this location](https://i.imgur.com/UjbIja3.png)
- Swap ditto with rhydon
- Swap antidote x1 (third) with awakening x255 (6th) (if used all poke balls, reference item slots)
- Toss antidote x1 (6th)
- Underflow
- Do not flash use/toss or back out/enter in to save a bit of frames (maybe)
- Swap awakening x0 with 9th slot
- Teach missingno teleport (tm30)
- Swap ether x80 into options
- Swap xblock master ball x0 with potion x0
- Toss 240 from potion x0 to get 16
- Swap potion x16 with RED in text pointer
- Save
- Take one step left
- View trainer card
- Swap bicycle (up 5) with ultra ball (up 3)
- Swap bicycle with Q r 4 h I
- Get on and off the bicycle
- The game should crash, hard reset
- Open inventory
- Toss 1 from awakening in 9th slot
- Toss all of tm55 in 8th slot (quantity 0), 7th slot (x1), 6th slot (x0 if had poke balls left, x1 if ran out of poke balls), 5th slot (x1) (BUT NOT 4TH!)
- Walk down 1 and right 1, then press A to access the player PC
- Open deposit menu
- If got PC potion: deposit []j. x1
- Deposit tm55 in fourth slot
- Deposit awakening x255
- Go to toss menu
- Toss CANCEL under potion/[]j. x1
- Toss potion x1
- Dry underflow
- Toss []j. from 5th slot in box underflow
	- Alternatively, back out and in of toss menu
	- Swap 5th []j. with 6th []j.
- Walk down to grass and get an encounter
- Use 9F in TID, then use teleport with missingno (cannot just walk back to daisy's house)
- Walk to daisy's house
- Walk right 1 to save []j. lag
- Toss 253 master balls from warping to get to 3
- Exit daisy's house
- Enter cerulean house
- Swap []j. x3 with ultra ball x1
- Scroll to tm22 x65, toss 58 to get to 7
- Swap tm22 x7 with ultra ball x1
- Swap []j. x255 in connections byte with tmtrainer item below
- Swap []j. x255 with coin case directly under the first cancel button you see (swap while cancel button is on screen to save frames)
- Swap []j. x255 with ultra ball x1 OR great ball x1 directly under cancel
	- swapping with great ball x1 saves []j. frames
- Toss []j. x175 from []j. x255 to get []j. x80
- Exit house
- Open item menu
- Scroll up until you see fire stone x[]9 (close to poké flute, above marshbadge)
- Press select on fire stone x[]9
- Scroll up until you hit a click item
- Press b three times to advance click item, then immediately press select
- Swap fire stone x[]9 with x accuracy x90
- Swap fire stone x[]9 with []4   [] "
- Toss 119 from dire hit x126 to get 7
- Scroll up, swap ether x80 in options with []4   [] "
- Toss 29 from ether x80 to get 51
- Bonk right, talk to invisible sign which is now a mart
- NOTE: selling items with OWRB skips sell jingle, be sure to sell fast!
- Sell: []j. x0/x255, parlyz heal x1, burn heal x1, 7 stacks of awakening x255 (money should be 678789)
- Buy (IN ORDER): hyper potion x99, hyper potion x99, hyper potion x20, rare candy x1
	- buy rare candy x81 if you want to preserve save file after credits
- Exit mart
- Open item menu
- Swap tm43 x243 in rival name with ether x51 in text pointer
- Toss 227 from tm43 x243 to get 16
- Scroll down, select repel x241 near super rod
- Scroll down until you hit a click item
- 3 clicks twice, then press select on click item to swap with repel x241
	- if you accidentally deselect the repels, advance past the click item and select the repel x248 near poke flute
- Press select on repel and scroll down again until you hit another click item
- 1 click 4 times to advance through
- Scroll down again until you see rare candy x1
- Scroll a bit more until the cursor is on cancel below rare candy x1 (reduces []j. lag)
- Swap repels with []j. x0 above rare candy x1
- Toss repels to get to repel x190 (241 tosses 51, 248 tosses 58)
- Exit menu, press A to talk to invisible prize vendor
- NOTE: can use repels multiple times instead of tossing (not sure on which is faster)
- By default, a repel is used each time per pokemon
- No need to change box since party count is set to 0 every time you talk to the prize vendor

## Farm
- Buy a Pokemon from the middle slot, use 1 Repel and repeat, unless the table below says otherwise
	- 2- repels: using is faster
	- 3+ repels: tossing is faster
- Buy tangela and chansey from 1st and 3rd slot respectively at some point

| after [Pokemon], use/toss [x] Repels | PP Strat  | Pidgey Strat | 1024 Charmander |
| ---------- | --------- | ------------ | --------------- |
| Oddish 		 | 5 				 | 5 				 		| 5								|
| Squirtle	 |					 |					 		| 4								|
| Charmander | 3 				 | 3 				 		|					  			|					
| Magnemite  | 3 				 | 2 				 		| 2								|
| Ponyta 		 | 5 				 | 5 				 		| 5								|
| Goldeen 	 | 2 				 | 2 				 		| 2								|
| Venusaur 	 | 2 				 | 2 				 		|									|
| Haunter 	 | 2 				 | 2 				 		| 2								|
| Electrode  | 2 				 | 2 				 		| 2								|
| Kingler 	 | 2 				 | 2 				 		| 2								|
| Muk 			 | 3 				 | 3 				 		| 3								|
| Golduck 	 | 2 				 | 2 				 		| 2								|
| Caterpie 	 | 3 				 | 3 				 		| 3								|
| Dodrio 		 | 2 				 | 2 				 		| 2								|
| Sandshrew  | 3 				 | 3 				 		| 3								|
| Dratini 	 | 3 				 | 3 				 		| 3								|
| Vulpix 		 | 4 				 | 4 				 		| 4								|
| Meowth 		 | 2 				 | 2 				 		| 2								|
| Doduo 		 | 4 				 | 4 				 		| 4								|
| Farfetch’d | 4 				 | 4 				 		| 4								|
| Mankey 		 | 2 				 | 2 				 		| 2								|
| Electabuzz | 2 				 | 2 				 		| 2								|
| Magmar 		 | 2 				 | 2 				 		| 2								|
| Machoke 	 | 2 				 | 2 				 		| 2								|
| Slowpoke 	 |  				 | 2 				 		|									|
| Growlithe  | 4 				 | 4 				 		| 4								|

**Stop after buying Kangashkan**

## HOF Warp

- Once all pokemon have been bought, toss 0 from []j. x0 directly under cancel button
- **Optional save file preservation strat**:
	- Do this before getting kangashkan, and do not do []j. x0 toss yet:
	- Toss 1 from rare candy x81 to get rare candy x80
	- Press select on rare candy x80
	- Scroll down until inventory wraps around, then scroll up until the first occurance when []j.s appear
	- Press up once more, then press select to swap rare candy x80
	- Exit menu and get kangaskhan
	- Toss 0 from []j. x0 below rare candy x80
- Press select on []j. x0 directly below last awakening x255 stack (saves []j. frames getting the []j. x0 here)
- Scroll down and press select on dire hit x7
- Scroll up a bit and press select on master ball x118
- Press select on ????? above coin case
- Exit menu and walk up to HoF
