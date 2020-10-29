# Brock Through Walls aka BTW guide

Brock Through Walls is a glitch performed in various red-blue glitched runs.
There are various ways to set up this glitch, but it is ultimately triggered by talking to the Pewter City Youngster from the right instead of the left, which was non intended to be possible.
For a more in-depth explanation on how and why the glitch works, check out [this](https://archives.glitchcity.info/wiki/Brock_Through_walls.html) GlithCity's article:


This guide is meant to explain what Brock Through Walls strategy  are commonly used through a speedrun, what you should pick and how to perform it.


Ranked from fastest to slowest and also from hardest to easiest
1. 1024 Charmander
2. Pidgey Strat
  - with Bulbasaur manipulation
  - without Bulbasaur manipulation
3. PP strats

## 1024 Charmander
This is the hardest but also faster method.
It requires a 1-frame rename after multiples 4-frames textboxes.
Because of this, this method should be used only by runners aiming for top times, and only after a lot of practice.

A guide to the manipulation itself can be found [here](/gen-1/red-blue/catext/reverse-badge-acquisition/resources/1024-charmander-manip)

After correctly performing it, Weedle fight must be done in specific way to assure correct PP after the fight.

### Weedle guy

Two basic options
1.  (swap Scratch/Growl), Growl x2, Scratch x7  
2.   Scratch x6  (only ~5% to kill); if Weedle's still alive:
    - if 1 Scratch kills (guaranteed to kill if no Gen 1 misses)  ::  (swap Scratch/Growl), Growl x2, Scratch x1
    - if 1 Scratch doesn't kill (only possible if Gen 1 missed)   ::  Scratch x2

### Fight notes
1. Safe  (~77.1% to win fight and exit with 38/28 PP)
    - 2 damage from Poison Sting at -2 (normally does 3 damage)
    - If you kill Weedle in 6 turns, you will need to burn a Scratch on a wild encounter (and getting encounters is b&)
    - If you Gen 1 miss and have to use an 8th Scratch to kill, your run is dead (takes too long to get a good PP setup)

2. Risky  (~70.9% to win fight and exit with working PP  ::  ~4.97% for 29/40,  ~64.3% for 38/28,  ~1.69% for 27/40)
    - Probably only makes sense if grinding for a godly time (more likely to kill run than save time)
    - Can capitalize on luck if you kill Weedle in 6 turns (~15 seconds saved in fight, 7 seconds lost from Brock skip)
    - Can usually recover from any Scratch Gen 1 misses

### Brock Skip

If you haven't menued by the time you hit the post-Forest gate (and if you don't need to let poison tick more), menu and put your cursor over SAVE while in the gatehouse (minimal lag + saves a turnframe).

**Brock Skip** _TODO_ what is old brock skip?
- If 9 turn fight (38 Growl & 28 Scratch), do normal Brock skip (go left; need to hold B while walking)
- If 6 turn fight (29 Scratch & 40 Growl), do "old" Brock skip (left input is disabled)
- If 8 turn fight (27 Scratch & 40 Growl), do "old" Brock skip (left input is disabled)

NOTE: 5 turn fight (40 Growl & 30 Scratch) can also do normal Brock skip, but a 5 turn Weedle fight is about a 1 in 2.6 million chance, so it's a TAS-only consideration.

## Pidgey Strat
This is slower than 1024 Charmander and faster than PP Strat.
It requires some specific Bulbasaur DVs, so manipulating him can assure these are perfect, but even without it the chance are around 56% to get a workable Bulbasaur.

### with Bulbasaur Manipulation
#### [1 second slower manip without IGT tracking](https://youtu.be/VjLFyiX5JdA)
- 56/60 manipwith perfect attack/special, bad defense
- textbox stats on practice rom: 231 50 129 55 | 74/81

#### [1 second faster manip with IGT tracking needed](https://youtu.be/0uN46d8nGHo)
- Skip PC potion
- 38/60 manip with perfect attack/special/defense, saves 93 frames to the 56/60 one
-	textbox stats on practice rom: 132 207 30 212 | 231/0

Both these manips gets bulba from the bottom, requiring a buffered save. Buffer a flash start, buffer A to talk to the ball, clear every textbox within their 4 frame window while holding A or B, then say no to renaming.
Both fail 15% of the time because of bad NPC timers

Continue from ###Pidgey _TODO_ make a link

### without Bulbasaur manipulation
- Pick PC potion
- Pick Bulbasaur
- Spam Tackle
  - Potion if needed (scratch does around 4 [6])
- On level up, check the special stat value.
  - 12 Special: Switch to PP strat or reset and try again
  - 13 Special: Kill one extra encounter. Lv2 Pidgeys or Lv2/3 Rattatas are preferred
  - 14 Special: Run from anything you see, no extra experience needed

### Pidgey  
- You will need to catch a Pidgey with the current HP value (8-10-13-15-16-17). You can either:
  - Catch a random Pidgey and hope it has good HP
  - Do Pidgey manipulation

   1 character Bulbasaur        | full name Bulbasaur          
   ---------------------------- | ----------------------------
  [1 character player name](https://youtu.be/a4joVzaCMXk) | _TODO_ from 151autumn route |
  [5 characters player name](https://youtu.be/Ua0ZyWffYpU) | NA as far as i know          |

- After Weedle Guy, check the special stat value again:
  - 15 Special: Reset or switch to PP STRAT
  - 16 Special: Continue the run with Pidgey Strat

### Brock Skip:
  1. Set your cursor over the SAVE option (dont save quite yet)
  2. Head to Route 3 exit, staying one tile above the sign
  3. Trigger the cutscene
  4. When the "Follow Me" textbox appears, clear it with the B button
  5. **Instantly** after pressing B **hold** the START button
  6. If you did it right, your start menu should pop up
  7. Hit SAVE (you are already over it) and soft reset after the game saves
    - If your start menu didn't open, you hit start too late. Just go back and try again
  8. Once the game reset, load the savefile normally
  9. After clearing the last textbox, **hold** RIGHT until you can hear the music change to Route 3 music
  10. Go back to the guy and stand right next to him
    - Talk to the guy, after clearing the last textboxes **hold** B and take a couple of steps RIGHT
    - If the game crashed, your Pidgey had bad HP or your Bulbasaur didn't have 16 Special
        - If that happens, reset and try again

## PP Strat
This is the slowest strat but it's also the only one that doesn't require any RNG manipulation and also works 100% of the time.
We recommend this to anyone who wants to learn/practice the whole run and don't want to reset early game too often.
- Pick PC potion
- Pick Bulbasaur
- Spam Tackle
  - Potion if needed (scratch does around 4 [6])
- Run from every encounter, fight Weedle Guy
- After Weedle Guy, search for encounters in the grass until you find either a Metapod or a Kakuna.
- Once in the wild encounter battle:
  - Switch your moves around using the SELECT button until your move order is the following:
    1. Leech Seed
    2. Tackle
    3. Growl
  - Now, you want to make sure that you setup your PP
    1. Leech Seed PP doesn't matter
    2. Growl should have exactly 36PP
    3. Tacke should have exactly 16PP
  - If you still need to reach Lv6, also kill the encounter
    - spam Leech Seed if your PPs are already set
  - You dont want to reach Lv9, so run away if you are Lv8 the encounter is about to die

### Brock Skip:
  1. Set your cursor over the SAVE option (dont save quite yet)
  2. Head to Route 3 exit, staying one tile above the sign
  3. Trigger the cutscene
  4. When the "Follow Me" textbox appears, clear it with the B button
  5. **Instantly** after pressing B **hold** the START button
  6. If you did it right, your start menu should pop up
  7. Hit SAVE (you are already over it) and soft reset after the game saves
    - If your start menu didn't open, you hit start too late. Just go back and try again
  8. Once the game reset, load the savefile normally
  9. After clearing the last textbox, **hold** RIGHT until you can hear the music change to Route 3 music
  10. Go back to the guy and stand right next to him
    - Open your Pokemon menu
        - If you have more than 1 pokemon, also swap Bulbasaur to last
    - Talk to the guy and take a couple of steps RIGHT
    - If the game crashed, your moves were in the wrong order or your PP's were setup wrong
        - If that happen, reset and try again
