# Don Manip (a.k.a. "Donnies")

### Save tile (facing left): 

![test](https://i.imgur.com/4zAMLFE.png)

### Maps: 
 - [Here](https://imgur.com/a/iuObJK1) (green tiles = A presses;  blue tiles = start flashes)
 - **NOTE**: For A presses after ledgejumps, avoid pressing A until the player hop animation is between the ledge tile and the grass tile; pressing A too early will make it fail to register when you land on the grass tile.
 
### [GSR Savestates](https://cdn.discordapp.com/attachments/266357733840650240/527909270075736114/savestates.zip)

### [SAV file](https://cdn.discordapp.com/attachments/266357733840650240/527716926928060426/gold_donnies.sav)

**Offset**: ~10.850s

**Notes**:
  - Call Mom (and give Berry) on the S&Q menu before Don manip
  - Step Count for this manip assumes both the FDFF/DECF Toto manip and r29 manips were used.
  - It is expected that the in-game clock will always display 10:1x after the S&Q for this manip.
---

## Paths

All of the paths use this movement:
```
L U U U U U U U L U U U U A+U R U U U R U R A+R 
```
   > Successes: 299/300

And depending on what frame you hit, the movement must be as follows:

```
[12] R U U A+U U R U U U U U U A+R R R R R U A+U U U U L L L A+L L L L L L L L D L L L L D A+L L L L U L L L L U U 
```
   > Successes: 59/60   (f46: hit Don)

```
[13] U U R U U U R U S_B U U U R R R R R U U U U U U L L L L L A+L L L L L L D L L L L L D A+L L A+L L U U L L L U
```   
> Successes: 58/60   (f17: L5 Caterpie, last tile of r31 patch 1)
>                    (f19: L4 Caterpie, 2nd last tile of r31 patch 1)

```
[14] U U R U U U S_B R U U U U R U R R R R U A+U U U U L L L L L L L L L L L D L L L L L D L L A+L L U L U A+L L U 
```   
   > Successes: 59/60   ( f1: L3 Pidgey, 2nd last tile of r31 patch 1)

```
[15] R U U R U U U S_B U U U U U R R R R R U A+U U U U L L L L L L L L L L L D L L L L L D L L L L L L L U U U 
```   
   > Successes: 60/60


*NOTE TO SELF*: Removing the 2nd A press (while 1 tile above Don) changes RNG and is still 299/300 for the Don pass; routing paths without the A press could yield potential improvements.

---

## NPC Cues   

**NOTE**: Only the relevant patterns up until Don is passed are denoted
 ```               
[ 10: encounter before Don ]
[ 11: r (-> u -> d -> r -> l), with a 2/60 IGT for u; not routed currently for the sake of simplicity ]
```
```
12: u   (-> l -> d -> r -> l)

    - f33/f34    =  r -> d -> l -> u -> l  
                    [first 2 switches are ~6 frames apart]
```

```
13: r -> d -> r -> d          (last 2 switches are ~6 frames apart)

    - f32/f33    =  r -> u -> r -> d
    - f23        =  r -> d -> r -> l
    - f37        =  r -> d -> r
```
```
14: r -> d -> r -> d -> r     (first 2 switches are ~2 frames apart)

    - f8/f9/f45  =  r -> d -> r -> d -> r             
                    [slower switches]
    - f31/f32    =  r -> d -> l -> u -> r -> u        
                    [first 2 switches are still ~2 frames apart]
    - f36        =  r -> d -> l -> u -> d -> r -> d   
                    [first 2 switches are still ~2 frames apart]
    - f54        =  r -> d -> r -> d -> l             
                    [first 2 switches are still ~2 frames apart; stuck left at end]
```

```
15: l   (-> u -> r)
```

```
[16: encounter before Don]
[17: encounter before Don]
```


**SIMPLER EXPLANATION FOR NPC CUES**

f14 is fully discernible from f13, including the IGTs. There is one common IGT (3/60) on f14 with a slower r->d->r->d->r pattern. An r->d->l pattern where the first two switches are instantaneous covers the remaining f14 IGTs (3/60). The r->d->l pattern with slightly more delay between the switches is the f12 IGT (2/60). Any other pattern that starts with r is f13.