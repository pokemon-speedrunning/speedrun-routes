# Yellow RBA (no underflow) route by entrpntr
[original guide](https://pastebin.com/XScRtwTr), credit to krazyd4n for several seconds of improvements to the route
## Intro
- [TID Manip]()
- yellow_gfskip_intro0_title_newgame_oakreset_gfskip_intro0_title_backout_title_newgame_oakreset_gfskip_intro0_title_newgame: 0xC5E6 (50662)
  - TID manip puts HM02 and TM30 in Pewter glitch mart    
- Choose 1 char player name ("A")
- Rival name: BLUE (pre-set)
- Set options in-game to Fast/Off/Set

## Rival

- Skip PC potion
- Get Pikachu and don't nickname it
- Battle rival, spam Thundershock
  - losing is slightly faster

## Parcel quest
- Remember to hold B to walk through Pikachu
- Run from all encounters
- Go behind Oak when delivering the Parcel


## Viridian Mart
- Buy Poke Ball x5
- Backtrack to Route 1 to catch a Pidgey (run from Rattatas)
	- NOTE: Corner bonk between the ledge and Pikachu for style points
- Immediately chuck balls at L2-L4 Pidgeys
- Thundershock L5-L7 Pidgeys before catching
- Give Pidgey a 1 char nickname ("A")

## Viridian Center
- Deposit Pikachu, then heal to set warp point
- Watch Old Man catching tutorial, then head to Route 2

## Forest Manip
- [Manipulate no encounter Forest](https://www.youtube.com/watch?v=KDRDvVE3VN4)
  - 54/60 for the manip to work
- Make sure to not load the final Bug Catcher before the next manipulation
- End of manip is different from YNSC ("A" vs "ASH" affects the manip after picking up Potion)

## Deathfly Manip
- [Manipulate a L9 Pidgeotto encounter in front of the last Bug Catcher](https://www.youtube.com/watch?v=DoPt1pxHPTo)
  - 47/60 for the manip to work
  - 11/60 for a L8 Pidgey (can still 0HKO depending on your Pokemon)
- Buffer down in move menu with all Pidgeys (works even without a 2nd move)
- Buffer select in move menu with all Rattatas
  - if you don't die first turn, spam a move until you die to get the deathfly glitch
- Same as YNSC

## THE Manip
- [Manipulate a specific movement pattern from the next NPCs](https://www.youtube.com/watch?v=DonALfmjZOk)
	- 27/60 for the manip to work up to using the Town Map, hitting one of the first 4 textbox frames is ~81% for the bird to move left
- Stop Movement for ~6 frames to allow bird to start moving left, then hold right
- [Adjacent frames](http://pastebin.com/raw/qBT86ks0)
	- listed early to late, each is a 2 frame window, target = FE
	- use this to troubleshoot your failed manips
- Same as YNSC


  Backup movement: backup options for wrong NPC movement without needing to re-save:
- UP/RIGHT  = [U11, R2, U3  (A @ U8/U10/R1)](https://gunnermaniac.com/pokeworld?map=1#53/185/SRRRRRRUUUUUUUUAUUAURARUUU)
- DOWN/LEFT = [U13, R2, U1  (A @ U1/U9/R1)](https://gunnermaniac.com/pokeworld?map=1#53/185/SRRRRRRUAUUUUUUUUAUUUURARU)



## Forest Mart
- Buy
 - Max Repel x1
 - Bicycle x23
 - Bicycle x91
 - scroll down
 - Once you see "COIN" on top, you need to get past 4 click items
   - click items require pressing B **once** whenever their name prints to continue scrolling
 - 6F x7
 - ??????? (Surfboard) x1
 - Master Ball x99
 - TMTRAINER x1

## Route 2
- Swap Poke Ball with bottom Bicycle, get on Bike
- Bike to [jack tile](http://extratricky.com/pokeworld/rb/1#60,142) and turn to face left, flash TMTRAINER
 - moving left one tile is fine
- Unjack and pick up HP Up
- Go through gate and WALK to next [jack tile](http://extratricky.com/pokeworld/rb/1#68,113)
  - this jack softlocks if on bike
- flash TMTRAINER, go up 1 tile and buffer menu
- Swap HP Up with Potion
- Use HP Up but backout on party screen ("medicine re-jack")
  - if you buffered the start menu correctly, you will face up.
  - if not, you can just try again by bonking up and opening the menu
- Bike past Diglett's Cave to other side of r2, unjack
- Grind for an encounter in grass
- Use 6F , unjack, bike to Pokemon Center and heal
- Walk to tile (http://extratricky.com/pokeworld/rb/1#57,78) and flash items, continue walking to Pewter Mart

## Pewter Mart
- Sell:
	- TMTRAINER x2
	- Master Ball x3
- Buy:
 - scroll down
 - Once you see "Gold Teeth" on top, you need to get past 4 click items
 - Jack x1
 - Ether x99
 - HM02 x1
   - with TM30 on bottom of screen, which ensures cost is $1000)
 - TM30 x2

Close glitched mart, then re-open unglitched mart
- Buy:
	- Burn Heal x99
	- Escape Rope x2
	- Awakening x1
	- Antidote x99
	- Antidote x99
	- Antidote x1

## Jynx
- Walk to Museum, go upstairs to [Jynx tile](http://extratricky.com/pokeworld/rb/53#13,1)
- Flash TMTRAINER, catch Jynx with Master Ball, nickname 1 char
- unjack, **swap Jynx in front**
- Exit museum and head to Brock fan [jack tile](http://extratricky.com/pokeworld/rb/1#72,66)
- Use Burn Heal to heal Jynx's status
- swap Jack
- with Poke Ball
- use Jack
- Go to tile above Brock fan, talk to him **without unjacking**
 - sign should be visible on last row
- Brock thru Walls to Viridian Gym (fastest to go straight down, then left at the end)

> NOTE: This particular BTW method relies on an 0F23 setup in items. Specifically, starting from an odd slot, the order must be:  [item] x15 | HP Up x1 | <Max Repel/Bicycle>

## Giovanni
- Face right and jack, follow [this path](https://gunnermaniac.com/pokeworld?map=45#16/17/LUUUUUUUUUUUULLLLLLUL)
- IP, BZ, IP, IP, IP

## Blaine
Before exiting gym:
- Use Max Repel close with up
- Pick up Revive  
 - ~0.2s faster than combining Max Repel and Bike menus and getting TM38 from Blaine
- After exiting gym bike to Pallet
- Use Surfboard and [surf to Cinnabar](https://gunnermaniac.com/pokeworld?map=1#58/250/LDDDDDDDDDDDDRDDDDDDDDDDDDDDDDDDDDDDRRDDDDDDDDDDDDDDDDDDDDDDDDDDDDDDDDDDDDDDDDDDDDDDDDDDDDDDDD)
- jack and bike to enter Blaine's gym
  - must see 1 tile of water on top


- Face right and jack, follow [this path](https://i.imgur.com/JHPJqUb.png)
 - medicine re-jack on "D" and "U", unjack on "X"
- BZ, BZ, BZ+IP
  - Don't Ether during fight if out of Blizzards, since that causes instant victory (b&). Use Ice Punches instead.

## Sabrina
After the fight:
- Ether on Blizzard
- Teach Fly to Pidgey
- Teach Teleport to Jynx (over Thrash)
- Use Burn Heal if burned
- Escape Rope to Pewter
- Biketo house near Brock fan and enter/exit, jack and bike again
- unjack, [Brock thru Walls to r23](https://gunnermaniac.com/pokeworld?map=1#75/69/LLLLLLLLLLLLLLLLLLLLLLLLLLLLLLLLLLLDDDDDDDDDDDDDDDDDDDDDDDDDDDDDDDDDDDDDDDDDDDDDDDDDDDDDDDDDDDDDDDDDDDDDDDDDDDDDDDDDDDDDDDDDDDDDDDDDDDDLU)
- Walk up until Indigo Plateau map loads
  - until game turns blue
- Teleport to Pewter
- Brock thru Walls to [Saffron Gym](https://gunnermaniac.com/pokeworld?map=1#53/80/RRRRRRRRRRRRRRRRRRRRUUUUUUUUUURRRRRRRUUUUUUUUULLLLLLLLL) (still in BTW state after Teleporting)
 - keep left until game turns blue, go down until orange, right to enter gym


- Walk 1 right, jack to sabrina
- BS, BZ, BZ

## Koga
- jack again when looking up to exit gym
- Bike and Jack, Heal in Celadon Center
- Face right, jack
- medicine jack to skip the first gate, medicine jack again to skip the second gate
  - [map here](https://gunnermaniac.com/pokeworld?map=1#191/118/LLLLLLLLLLLLLLLLLLLLLLLLLDDDDDDDDLLLLLLLLLLLLLLLLLLLLLLLLLLLLLLLLLDSLLLLLLLLLLLLDDDDDDDDDDDDDDDDDDDDDDDDDDDDDRRRDDDDDDDDDDDDDDDDDDDDDDDDDDDDDDDDDDDDDDDDDDDDDDDDDDDDDDDDDDDDDDDDDDDDDDDDDDDDDDDDDDDDDDDDDDDDDDDDDDDLDDDDDDDDDDDDDDDDDDDDDDDDDDDDRRRRRRRRRRRRRRRRRRRRUSURRRRRRRRRRRRRRRRDDDDDA)


- Face down and jack to get to Koga
- IP, IP, IP, BZ

## Erika
- Jack to exit gym
- Teleport to Celadon
- Face right, bike and [jack](https://gunnermaniac.com/pokeworld?map=1#191/118/LLLLLDDDDDDDDDDDDDLLLLLLLLLLLLLLLDDDDDDDDD)
- Face down and jack to get to Erika
- IP, BS, IP

## Surge
- Jack to exit gym
- Teleport to Celadon
- Face down, bike and jack
 - full movement [here](https://gunnermaniac.com/pokeworld?map=1#191/118/RRRRRRRRRRRRRDDDDDDRRRRDDDDDRRRRRRRRRSRRRRRDDDDDDDDDDRRRRRRRRRRRRRRRRRDDDDDLSLDDADDDDDDDDDDLLDDDDDDDDRRRRRRRRRRRSDDDDDDDDDLLLLLLLLDDDDDDDDDDDDDDDDDDDDDDLLLLLDDDDAL)
- face right and medicine rejack past the first gate
- face left and medicine rejack past the second gate
- unjack and skip trainers/grass
 - can medicine rejack here facing down and medicine rejack the next step to have your sprite on screen which makes the movement easier but slightly slower
- jack to get into surge's gym
- Face left, jack to get to Surge. 1 right then up
- IP

## Misty
- Jack to exit gym
- Fly to Cerulean, walk to Misty's gym
- Use Surfboard (2 under Jack) on left side of gym to surf to Misty
- BS, BS

## Brock
- Fly to Pewter, walk right, [jack to enter the gym from the right](https://gunnermaniac.com/pokeworld?map=1#54/80/RRRRUUUUUUUUULL)
- IP, IP

## League
- Fly to Indigo
- jack through the E4
  - save a turnframe by unjacking on top of Lance
- walk past the Champion and enter the Hall of Fame
