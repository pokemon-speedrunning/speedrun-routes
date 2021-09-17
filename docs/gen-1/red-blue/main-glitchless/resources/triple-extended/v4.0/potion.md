# Pokemon Red Triple Extended Manip v4.0 with Potion Pickup
credits to hwangbro/stringflow

Pidgey and house movement, as well as NPC cues are the same as without Potion.
The only changes are in the last stretch of forest movement.


Glossary:
  - 'r' means NPC is looking RIGHT
  - 'R' means NPC moves RIGHT
  - u->L means NPC is looking UP, then moves LEFT
  - r->D/L means NPC is looking RIGHT, then moves DOWN or LEFT

## "Main" Paths

PATH | [NPC 1](https://gunnermaniac.com/pokeworld?map=1#53/182) | [NPC 2](https://gunnermaniac.com/pokeworld?map=1#57/167) | [NPC 3](https://gunnermaniac.com/pokeworld?map=50#2/4) | [NPC 4](https://gunnermaniac.com/pokeworld?map=51#16/43) | [NPC 5](https://gunnermaniac.com/pokeworld?map=51#27/40) | STRING SHOT | PIDGEY MAP | HOUSE MAP | FOREST MAP
---- | ----- | ------ | ------ | ------ | ------ | ------------------ | ------------ | --- | ---
1 | r | R | D | d | D | 7 Frames (~295.5/370, 79.9%) | [Link](https://gunnermaniac.com/pokeworld?map=1#33/181/DRRUUURRRRRRRRRRRRRRRRRRRRRURUUUUUURUUUULUUUUUUAUUUUUUUUUUUUULLLUUUUUUUUUUURRRRUULLLLLUUU) | [Link](https://gunnermaniac.com/pokeworld?map=50#4/7/RUUUUUUU) | [Link](https://gunnermaniac.com/pokeworld?map=51#17/47/UUUURRRRRURRRUUUUUUUUUUUUUUUUUUUUUUUUUUUUUUUUUALLLLLLLLDDDDDDDLLLLUUUUUUUUUUUUULLLLLLDDDDDDDDDDDDDDDADDDLDALLLALULAUUU) |
2 | u->L | R->L | D | r->u | d | 4 Frames (~174.9/207.7, 84.2%) | [Link](https://gunnermaniac.com/pokeworld?map=1#33/181/DRRUUURRRRRRRRRRRRRRRRRRRRRURUUUUUURUUAUULUUUAUUUUUUUUUUUUUUAUULLLUUUUUUURRRRUAUUUUUUULLLLLU) | [Link](https://gunnermaniac.com/pokeworld?map=50#4/7/UUUUURUU) | [Link](https://gunnermaniac.com/pokeworld?map=51#17/47/UUAUURUARRRRRRRUUUUUUUUUUUAUUAUUUUUUUUUUUUUUUUUUUULLLLLLLLDDDDDDDLLLLUUUUUUUUUUUUULLLLLLDDDDDDDDDDDDDDDDDDLDLLLLULUUU) |
3 | r->L | L | U | u->r | r | 5 Frames (~228.6/267.3, 85.5%) | [Link](https://gunnermaniac.com/pokeworld?map=1#33/181/DRRUUURRRRRRRRRRRRRRRRRRRRRURUUUUUURAUUUUUUUUUUUUUUUUUUUULUAUULLLUUUUUUUUUURRRARUUUUAULLLLLU) | [Link](https://gunnermaniac.com/pokeworld?map=50#4/7/RUUUUUUU) | [Link](https://gunnermaniac.com/pokeworld?map=51#17/47/UUURURRURRRRRUAUUUUUUUUUUUUUUUUUUAUUUUUUUUUUUUUULLLLLLLLDDDDDDDLLLLUUUUUUUUUUUUULLLLLLDDDDDDDDDDDDDDDDDDDDLLLLLUAUS_BLUU) |
3v2 | r->D | L->R | U | d | u | | | | |
4 | u->U | L | D | l->u->r | l | 5 Frames (~237.7/263.7, 90.1%) | [Link](https://gunnermaniac.com/pokeworld?map=1#33/181/DRRUUURRRRRRRRRRRRRRRRRRRRRURUUUUUURUUUUUUUUUULAUUUUAUUUUAUUUAUULLLUUUUUUUUAURRRRUUUUUULLLLLU) | [Link](https://gunnermaniac.com/pokeworld?map=50#4/7/UUUUUURU) | [Link](https://gunnermaniac.com/pokeworld?map=51#17/47/UUUURURRRRRRRAUUUAUUUAUUUUUUUUUUUUUUUAUUUUUUUUUUUULLLLLLLLDDDDDDDLLLLUUUUUUUUUUUUULLLLLLDDDDDADDADDADDDDADDADDDDLLLLLS_BLUUUU) |
5 | d | R | U | d | l | 7 Frames (351.3/370.2, 94.9%) | [Link](https://gunnermaniac.com/pokeworld?map=1#33/181/DRRUUURRRRRRRRRRRRRRRRRRRRRURUUUUUURUUUULUUUUUUAUUUUUUUUAUUUAUULLLUUUUUUAUURRUUAURRUUUULLLLLU) | [Link](https://gunnermaniac.com/pokeworld?map=50#4/7/UUUURUUU) | [Link](https://gunnermaniac.com/pokeworld?map=51#17/47/UUUURRRRRRRURAUUUUUAUUUUUUAUUUUUUUUUUUUUUUUUAUUUUULLLLLLLLDDDDDDDLLLLUUUUUUUUUUUUULLLLLLDDDDDDDDDDDDDDDDDDLDLALLLALUUUU) |
6 | d | L | U | d | u->d | 8 Frames (388.2/421.7, 92.1%) | [Link](https://gunnermaniac.com/pokeworld?map=1#33/181/DRRUUURRRRRRRRRRRRRRRRRRRRRURUUUUUURUUUUUUUUUULAUUUUUUUUUUUUUULLLUUAUUUAURRRRAUUUUUULALLLLUUU) | [Link](https://gunnermaniac.com/pokeworld?map=50#4/7/RUUUUUUU) | [Link](https://gunnermaniac.com/pokeworld?map=51#17/47/UUURURRRRRRRUUUUUUUAUUUUAUUUUUUUUUUUUUAUUUAUUUUUUULLLLLLLLDDDDDDDLLLLUUUUUUUUUUUUULLLLLLDDDDDDDDDDDDDDADDADDS_BDLLLLALLUUUU)
6v2 | d | L | U->D | u | l->u | | | | |
6v3 | d | L->R | U->U | u | l->u | | | | |
