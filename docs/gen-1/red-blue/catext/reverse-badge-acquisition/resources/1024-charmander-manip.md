# 1024 Charmander Manipulation
credits to entrpntr for finding the manipulation and also writing the original notes that you can find [here](https://pastebin.com/K8TLAKqY)

**Disclaimer: The 1024 Charmander Manipulation is one of the most difficult manipulation to successfully pull off in Red/Blue. It is recommended to first start with Bulbasaur to learn the general route.**

For practice/learning, we recommend applying the ISP patch pinned in #rby-category-extension to a copy of your Blue rom to create a practice rom that shows your save frame, Charmander DVs and textbox frames.

## Pre-save

Skip PC Potion

Wait to set options until Charmander save, continue holding B through Pallet Town textboxes.

Recommend starting a timer for 46.45 seconds from when your sprite lands on the bedroom stairs.
- You will press A to Save when the timer hits 0.00; this is to make sure you save on a good IGT frame.
This setup should hit in the middle of the cluster of successes from IGT frames 0-22.
    - Best option: use Flowtimer and add "46450" as an offset. Increase the number of beeps and hit 45450 if you are fast enough by going 2 beeps early
    - Less precise option: make a split at the stairs and press A when the segment timer is around xx.45
You can check if you successfully saved on a good frame (0-22) by using the practice rom.

After cutscene textboxes
  - Move your character below the Charmander ball
  - Hold UP to sidebonk into the ball; buffer START while still holding UP (this ensures your player will be facing up when reloading save; if you let go of UP before menuing, there is a good chance you'll be facing down upon reload)
  - Set options (fast text, animations off)
  - Press A to Save when timer hits 0.00


## Post-save

[Charmander Manip](https://www.youtube.com/watch?v=PDZyY1w93LA)
  - Can use [this working save](https://cdn.discordapp.com/attachments/88133858192551936/326119021768474635/charmander2_blue.sav)  to practice (Gambatte users: replace existing Blue .sav):

You have to hold A or B whenever text is scrolling (wait until jingle starts on "[5 characters name] received a CHARMANDER!" textbox to switch from holding B to A)

Make sure to be on a good frame by using the practice rom or the above save

Start by making sure that you are doing everything up through the naming screen correctly. You can do so in two methods:
  - Buffering START on the naming screen and checking DVs/stats; if everything else is done correctly, buffering START will yield a Charmander w/DVs = A90A (L5 stats = 19/11/10/11/11).
  - While using the practice rom you can open your Charmander stats and look at the textboxes numbers. They should be like this :
    - | Textbox | N.  |
      | ------- | --- |
      | TXTBX1  | 229 |
      | TXTBX2  | 47  |
      | TXTBX3  | 127 |
      | TXTBX4  | 58  |
      | Y/N BX1 | 72  |
      | Y/N BX2 | 85  |



Once satisfied that you are executing everything up to the naming screen properly, you can move on to renaming:
* You need to press A on the naming screen in the first 14 possible frames (sets Charmander's name to 'A'); aim for the early part of this window to be safe
* To time START perfectly:
    - You can using game audio cue for when to press START on naming screen (anticipate the loud tone; press start as it is about to play, may need to adjust timing slightly if consistently early/late -- use the list of nearby frames below for calibration)
    - Set up a flowtimer offset that starts at reset. You can start by using these offsets, but you will need to adjust them to your timings:
        - gambatte: 29935
        - GBI: 30459
    

Approximately 20% chance to get trolled by NPC timers in attempts even if you did everything correctly (the above .sav has good NPC timers, so trolling is not possible if practicing from that)

## How to check success-failure

Once you are confident, skip lv5 stat check and only check in-battle rolls and L6 stats  

| Frame | DVs  | L5 stats       | L6 stats       | L7 stats       |
| ----- | ---- | -------------- | -------------- | -------------- |
| 36    | D281 | 19/11/ 9/12/10 |                |                |
| 37    | 70FB | 20/10/ 9/13/11 |                |                |
| 38    | E069 | 19/11/ 9/12/10 |                |                |
| 39    | 80F7 | 19/11/ 9/13/10 |                |                |
| 40    | 399D | 20/10/10/12/11 | 22/11/11/13/12 |                |
| 41    | FB4D | 20/11/10/11/11 | 22/13/11/13/12 |                |
| 42    | D010 | 19/11/ 9/11/10 | 21/12/10/12/11 |                |
| 43    | 1637 | 20/10/ 9/11/10 | 22/11/11/13/11 |                |
| 44    | 1024 | 19/10/ 9/11/10 | 21/11/10/13/11 | 23/12/11/14/12 |
| 45    | 2F29 | 19/10/10/11/10 | 21/11/12/13/12 |                |
| 46    | F3E9 | 20/11/ 9/12/10 | 22/13/10/14/12 |                |
| 47    | 3F23 | 20/10/10/11/10 | 22/11/12/13/11 |                |
| 48    | 6C3F | 19/10/10/11/11 | 21/12/11/13/12 |                |
| 49    | E5A3 | 19/11/ 9/12/10 |                |                |
| 50    | 59F5 | 20/10/10/13/10 |                |                |
| 51    | 39CE | 20/10/10/12/11 |                |                |
| 52    | 5AE0 | 19/10/10/12/10 |                |                |


Check for "good" (i.e. non-working) defense = 3 damage (38/39) at ±0; also takes less damage at -1 thru -4 than "bad" (i.e. working) defense, but same damage ranges as bad defense for crits and stages -5 thru -6.

**Squirtle Tackle damage**
<table>
<tr><th>No Growl</th><th>Growl</th></tr><td>

| N. Tail Whips | dmg (roll) | dmg (roll) | dmg (roll) | dmg (roll) |
| ------------- | ---------- | ---------- | ---------- | ---------- |
| crit          | 5 (38/39)  | 6 ( 1/39)  |            |            |
| 0             | 4 (38/39)  | 5 ( 1/39)  |            |            |
| 1             | 5 ( 2/39)  | 6 (36/39)  | 7 ( 1/39)  |            |
| 2             | 7 (10/39)  | 8 (28/39)  | 9 ( 1/39)  |            |
| 3             | 9 (15/39)  | 10 (23/39) | 11 ( 1/39) |            |
| 4/5/6         | 13 ( 7/39) | 14 (16/39) | 15 (15/39) | 16: (1/39) |

</td><td>

| N. Tail Whips | dmg (roll) | dmg (roll) | dmg (roll) |
| ------------- | ---------- | ---------- | ---------- |
| crit          | 5 (38/39)  | 6 ( 1/39)  |            |
| 0             | 2 (38/39)  | 3 ( 1/39)  |            |
| 1             | 4 (38/39)  | 5 ( 1/39)  |            |
| 2             | 5 (38/39)  | 6 ( 1/39)  |            |
| 3             | 5 ( 2/39)  | 6 (36/39)  | 7  ( 1/39) |
| 4/5/6         | 8 (13/39)  | 9 (25/39)  | 10 ( 1/39) |

</td></table>

- You can opt to Growl turn 1, which is a guaranteed time loss, but increases chances of winning the fight from ~74.9% to ~91.5%. With Squirtle at -1 atk, you will be able to discern good defense between stages -1 and -4 (but ±0 becomes indistinguishable).
- Can become less and less cautious with confirming stats the more confident you are with the manip. 19 HP at L5, dealing just 3 damage with Scratch, and receiving expected damage from Squirtle are indicators of the right Charmander.)
