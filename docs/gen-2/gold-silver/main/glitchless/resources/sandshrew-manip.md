# Sandshrew Manip

**Notes**:
  - This manip assumes you at least do [entrpntr's Totodile manip](toto-manip.md) 
  - Take note of stepcount, more info below

[**Maps**](https://imgur.com/a/GIYPxnL) (green tiles = A presses;  blue tiles = start flashes)

[**GSR Savestates**](https://cdn.discordapp.com/attachments/454258641134944259/528711480024236099/savestates.zip)

**Offset**: ~10.690s (no idea really, first 5 possible frames)

## Step Count

Assuming you did both r29 and the don manip made by entr, you should be at stepcount=DF if hopped ledge after Falkner's Gym, and stepcount=E0 if you didn't. For this manip it is better to not hop the ledge as it improves the success rate of frame 1 by 1/60 (it's 52/60 with stepcount=DF). Frame 2 stops working if stepcount>E7, so you have 7 tiles of movement mistakes.
Full data can be found [here](https://pastebin.com/1Tj5x7Rq).

## Paths

All of the frames perform the following movement:

```
(start -> past bill)
[1-5] R D D D A+D D A+L L D D L L
```

Depending on what frame you hit, you perform the following movements:
```
(past bill -> end)
[1] L L D L L D D D D D L D D D D R D R R R R R R R
    > Bill pattern: r->d spam (fast)
	> Successes: 53/60
		> 1x No Encounter
		> 3x Bill Hit
		> 1x Early Sandshrew (after bill)
		> 2x Geodude
```

```
[2] L A+D L L L D D D S_B D D L D D D D R D R R R R R R
    > Bill pattern: u->l->d->...
    > Successes: 57/60
		> 2x No Encounter
		> 1x Early Sandshrew (after bill)
```

```
[3] L L L D L D D D D D L D D D D R R R R D R R R R
    > Bill pattern: stuck r
    > Successes: 57/60
		> 1x Zubat
		> 2x Early Sandshrew (before bill)
```

```
[4] S_B L L D L L D D D D D L D D D D R R R R R R D R R
   > Bill pattern: r->d->r->u (slow)
   > Successes: 55/60
		> 2x Early Sandshrew (after bill)
		> 2x Rattata
		> 1x Geodude
```

```
[5] L L D L L D D D D D L D D D D D R R R R R S_B R R
    > Bill pattern: r->d->stuck r
    > Successes: 57/60
		> 1x Rattata
		> 2x Bill Hit
```