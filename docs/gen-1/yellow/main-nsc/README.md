# Pokemon Yellow Any% No Save Corruption 2022 Route
**CLEAR SAVE DATA FOR EACH ATTEMPT OR YOUR RUN IS INVALID**

credits to:
- original pikawalk route: luckytyphlosion, gifvex, entrpntr, stringflow
- pikawalk-less route: entrpntr
- 5F route: gifvex, luckytyphlosion, stringflow

[Video playlist](https://youtube.com/playlist?list=PL2AJLbxMcDHftGOxRKpQleHuaBaTE9Njs)

## Intro
- Manipulate $76 in low TID byte: [video with inputs](https://youtu.be/5zrjmfCqgOs)
- Hold the A or B button while clearing textboxes with the other while the text speed option is still the default.
- Name yourself 'ASH' (preset)
- Name rival 'BLUE' (preset)

## Rival
- Set options to Fast/Off/Shift
- Skip PC potion
- Get Pikachu and don't nickname it
- Battle rival, spam Thundershock
  - losing is slightly faster

## Parcel quest
- Remember to hold B to walk through Pikachu
- Run from all encounters
- Go behind Oak when delivering the Parcel

## Catch something
- Enter the mart and buy 8 or less Pokeballs (you need at least 1 left over after catching something)
- Backtrack to Route 1 to catch any Pokemon
  - Immediately chuck balls at L2-L4 Pidgeys
  - Weaken Rattatas and L5-7 Pidgeys with Thundershock before catching
- If you get a Pidgey or a L2-L3 Rattata, name it 'A', otherwise skip naming
  - this is needed for extended gust manip later

## Viridian
- Deposit Pikachu, then heal to set warp point  
- Watch Old Man catching tutorial, then head to Route 2

## Forest
- [Manipulate no encounter Forest](https://www.youtube.com/watch?v=KDRDvVE3VN4)
  - 54/60 for the manip to work
- Potion is picked up because 5 items are needed for the final glitch
- Make sure to not load the final Bug Catcher before the next manipulation

## Deathfly Glitch
- [Manipulate a L9 Pidgeotto encounter in front of the last Bug Catcher](https://www.youtube.com/watch?v=DoPt1pxHPTo)
  - 47/60 for the manip to work
  - 11/60 for a L8 Pidgey (can still 0HKO depending on your Pokemon)
- Buffer down in move menu with all Pidgeys (works even without a 2nd move)
- Buffer select in move menu with all Rattatas
  - if you don't die first turn, spam a move until you die to get the deathfly glitch

## THE Manip
  - [Manipulate a specific movement pattern from the next NPCs](https://www.youtube.com/watch?v=DonALfmjZOk)
    - 27/60 for the manip to work up to using the Town Map, hitting one of the first 4 textbox frames is ~81% for the bird to move left
  - Stop Movement for ~6 frames to allow bird to start moving left, then hold right
  - [Adjacent frames](http://pastebin.com/raw/qBT86ks0)
    - listed early to late, each is a 2 frame window, target = FE
    - use this to troubleshoot your failed manips

## Forest mart
- Buy 90x Bike
- scroll down
- Once you see "COIN" on top, you need to get past 4 click items
  - click items require pressing B **once** whenever their name prints to continue scrolling
- Buy 30x 5f
- Buy 1 Repel
  - same slot you bought 5f from
- Buy 1 ABCDEF... glitch item
  - 1 slot above the repel you just bought
- close the mart (there's 1 click item you need to press B multiple times)
- Buffer right to move a tile
   - going down immediately will crash the game
- Exit and repel, then hop on bike

## Ace
- Walk along [this path](https://gunnermaniac.com/pokeworld?map=1#53/133/DDDDDDDDDDDDDDDDDRRRRDDDDDDDDDDDDDDDRDDDDDDDDDDDDDDDLLLULLLLLLLLLLLLLLLLLLLL)
- come to a complete stop, then [move right to this tile](https://gunnermaniac.com/pokeworld?map=1#35/179/RRRRRRR)
  - this is needed to have 22(0x16) repel steps remaining. You can actually turn frame anywhere but just remember to only do it once.
- Open the bag and scroll to the bottom, so the menu looks like this:
  - 5f
  - "4{}{}}{}{}4"
  - CANCEL
- flash the "4{}{}}{}{}4" glitch item, cursor will then reset on 5f
- use 5f, mash for a bit (you are clearing invisible textboxes) then run away from metapod.
- if all was done correctly, you will warp to HoF
