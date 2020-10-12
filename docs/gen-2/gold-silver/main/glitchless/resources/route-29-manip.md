# Route 29 Manip 2.0

## Changelog

[Major]
> Changed end of Path 1 (pass #2). The previous version caused problems on Don Manip due to subtly loading the fruit tree map object in memory before Youngster Joey, which changed the "first empty slot" when loading Don (bumping RNG and causing unrecognizable patterns for Don manip, including hitting Don on Path 1. Mikey crit rate 26/60 -> 25/60.

[Minor]
> Removed the 4th A press from Path 3 (both passes) and changed the end of pass #2. The A press (the first of 2 rapid-fire A presses in the final grass patch on r29) was a troublesome one, and wasn't needed for pass #1 to get 60/60 encounterless. Mikey crit rate 17/60 -> 18/60.


## Notes

- Do the FDFF/DECF Toto manip (REQUIRED)
-  Go straight down after Toto manip and exit lab on right (saves a step, which allows both passes to begin the same).
   - Normal lab movement after naming rival / before getting Poké Balls.
- Save tile is the one closest to the Catching Tutorial Dude without him loaded (bottom row, offscreen by 2 tiles).
- Save on turnframe (pass 1 facing down, pass 2 facing right). NOTE: Pass 2 MUST be an unbuffered save.
- Hold left for the entire intro (having a button held at all times avoids some fuckery with the RNG)

---

### NPC cue

In bold are the good frames.

| Frame | NPC Movement | # of IGT Frames | IGT Frame NPC Movement | Moment of Correct NPC Cue | Moment of IGT NPC Cue |
| --- | --- | --- | --- | --- | --- | 
| 12 | Up -> Down | 2 | Left -> Up | Instant | After ~8 tiles |
| 13 | Right -> Up | 3 | 2:Right -> Down and 1: Down| Instant | Instant |
| **14** | **Right -> Left** | **2** | **Down -> Right** | **Instant** | **Instant** | 
| **15** | **Down -> Right** | **0** | **N/A** | **After ~8 tiles** | **N/A** |
| **16** | **Left** | **2** | **Up -> Down** | **N/A** | **After ~10 tiles** |
| 17 | Down -> Left -> Down | 2 | Down -> Up -> Right | Instant | Instant |
| 18 | Left | 0 | N/A | After ~11 tiles | N/A |


**NOTE**: If you miss the very first A press, the first r29 NPC turns right a few tiles earlier than expected on f15 and the manip will fail (f14 and f16 are unaffected).

---


**Offset**: ~10.875s (using FlowTimer 1.4.2; individuals may need to calibrate for their own setups)

**Maps**
  - [Pass 1](https://imgur.com/a/R5iZhvy)
  - [Pass 2](https://imgur.com/a/E3VgHos)

[**GSR Savestates**](https://cdn.discordapp.com/attachments/406585769227059211/524300529837408282/savestates.zip) 

**SAV files**
  - [Pass 1 ](https://cdn.discordapp.com/attachments/406585769227059211/524296583895056384/gold_r29_pass1.sav)
  - [Pass 2](https://cdn.discordapp.com/attachments/406585769227059211/524296587825119232/gold_r29_pass2.sav)

**Encounterless manip: 60/60 all 3 frames, pass 1 & pass 2**
  - Get Potion on the way down after Mr. Pokemon

**Mikey Crit manip**
  - Frame 14: select buffer (25/60)
  - Frame 15: select buffer (36/60)
  - Frame 16: select buffer (18/60)