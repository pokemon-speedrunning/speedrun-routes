## Disclaimer: This route only works on Silver. Gold would take twice as long for collision, so it isn't worth it.


**Pre-Run**

- Clear save data

- Set fast text
- If doing r29 manip, get wStartSecond 0 (currently r29 manip doesn't exist for Silver so ignore this)
- TID manip is not needed

**Run**

- Name yourself "RRRRRRR" (left->down->spam A)

- IGT track #1 for frame 2-59 (you can probably use livesplit for this?)

- Save on (5,3) facing right buffered
	* https://i.imgur.com/FQhVN9N.png
	* Just buffer start after closing last elm textbox
	* Make sure to start a timer after hitting yes on save

- Get cynda, no nickname

- IGT track #2 for frame -2 of previous IGT
	* Add ~35327 to timer
	* If this is too hard to hit, you can wait another 59 frames (~36312 offset instead, also makes first igt have frames 1-59 work)

- Save on (2,4) facing down buffered
	* https://i.imgur.com/GRIB3X7.png
	* movement: https://gunnermaniac.com/pokeworld2?map=6149#5/3/LLLDS

- Reset while saving in (0x288D, 0x2891)
  * Same timer as second igt
  * GBI - add ~2500
  * GBP/GSR - add ~1960
  * The window is ~1/16 of a millisecond, expect to fine tune your offsets

- Do r29 manip (doesn't exist yet so ignore this)
- Cynda won't have any HP after collision, so you auto-win any wild encounter.

- Name boxes on Pokemon Center 1F
  * BOX 2: . (space) . n 'd 'v l
  * BOX 3: 'e * 2 H 'e ] 'd A
  * BOX 4: 'e g 'd n U 'e h 'd
  * BOX 5: 'v & 'e H 'd 'e [ 'd
  * BOX 6: p 'e d 2 'e 4 4
  * BOX 7: A 1
  * Asterisk in box 3 is the multiplication symbol

- Walk out of center
- Take one step down (should stand here: https://gunnermaniac.com/pokeworld2?map=1#279/221)
- Save
- Type d0 grind (spam Down for grinding)
- Take 1 step down, then press A to talk to Red
- End