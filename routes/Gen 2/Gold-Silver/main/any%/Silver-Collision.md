note: route only works on silver :^)

(format shamelessly copied from gifvex's crysany collision route)

clear save data

set fast text, get wStartSecond 0, no TID manip needed (can skip ss0 if not doing r29 manip)

(also r29 manip doesn't exist yet so just ignore ss0)

name yourself "RRRRRRR" (left down spam A)

IGT track #1 for frame 2-59 (just yolo this lol) 

save on (5,3) facing right buffered
  * https://i.imgur.com/FQhVN9N.png
  * just buffer start after closing last elm textbox
  * make sure to start a timer after hitting yes on save

get cynda, no nickname

IGT track #2 for frame -2 of previous IGT
  * add ~35327 to timer
  * if this is too hard to hit, you can wait another 59 frames (~36312 offset instead, also makes first igt have frames 1-59 work)

save on (2,4) facing down buffered
  * https://i.imgur.com/GRIB3X7.png
  * movement: https://gunnermaniac.com/pokeworld2?map=6149#5/3/LLLDS

reset while saving in (0x288D, 0x2891)
  * same timer as second igt
  * GBI - add ~2500
  * GBP/GSR - add ~1960
  * The window is ~1/16 of a millisecond, expect to fine tune your offsets

manip no encounters?

name boxes on Pokemon Center 2F
  * BOX 2: . (space) . n 'd 'v l
  * BOX 3: 'e * 2 H 'e ] 'd A
  * BOX 4: 'e g 'd n U 'e h 'd
  * BOX 5: 'v & 'e H 'd 'e [ 'd
  * BOX 6: p 'e d 2 'e 4 4
  * BOX 7: A 1
  * asterisk in box 3 is the multiplication symbol

walk out of center
take one step down (should stand here: https://gunnermaniac.com/pokeworld2?map=1#279/221)
save
type d0 grind
take 1 step down, then press A to talk to Red
end