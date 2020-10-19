# Pokemon Yellow Any% No Save Corruption
**CLEAR SAVE DATA FOR EACH ATTEMPT OR YOUR RUN IS INVALID**

credit to stringflow/entrpntr for this guide

 [Video playlist](https://www.youtube.com/playlist?list=PLQpdNvoYOPZy1hhIrnVSbpOSe38BdwwDK)

## Intro
- Set options to Fast/Off/Shift
- Name yourself 'ASH'
- Name rival '×S×'
  - [×] being the multiplication symbol, not lowercase X

## Rival
- Skip PC potion
- Get Pikachu and don't nickname it
- Battle rival, spam Thundershock
  - Winning or losing doesn't matter

## Parcel quest
- Remember to hold B to walk through Pikachu
- Run from all encounters
- Go behind Oak when delivering the Parcel

## Catch something
- Enter the mart and buy 5+ Pokeballs (you need at least 1 left over after catching something)
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
- Potion is picked up because 3+ items are needed for the final glitch
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
- Buy 1 TMTRAINER (glitched item, 2nd slot in buy menu)
- Exit mart
- Buffer right to move a tile before exiting
  - going down immediately will crash the game
- Walk back to Viridian Mart

## Viridian Mart
- Upon entering, walk 1 left and "attempt" to save (press B at the Yes/No dialog)
- Toss TMTRAINER x116 (you currently have 186, so mash down to get to 116)
- Walk 2 up and flash your item bag
- Open shop and attempt to sell TMTRAINER
  - you will get "I can't put a price on that."
- Buy 1 more TMTRAINER (2nd in buy menu), then close the shop
- Walk 2 down and "attempt" to save again
- Toss TMTRAINER x1, then toss your top 2 items (Poke Ball, Potion)
- "Attempt" to save again and walk 2 right

## Underflow
- [Video tutorial](https://www.youtube.com/watch?v=ofcFqkG3BQg)
- Toss TMTRAINER x253 from the *first* slot
- Swap slot 1 with slot 2 twice (causes the stacks to merge)
- Before scrolling down, "attempt" to use TMTRAINER (not necessary, but avoids 1 click item)
- Scroll down past a load of []x[] items until you hit some "real" items.
  - Swap TM41 x[]6 with TM41 x80 (rival name)
  - Swap TM41 x99 with item below Thunderbadge (map script ptr)
  - Swap Thunderbadge (map text ptr) with Helix Fossil (map id)
- Close the menu
  - if everything was done correctly, you will warp to the Hall of Fame
