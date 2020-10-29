# Route 29 Manip

**Notes**:
  - This manip assumes the FFFF/FFEF Toto manip was used.
  - All paths are 60/60.

**Saving**:
  - For both Lab visits exit on the left (it's faster and required for the manip to work).
  - Tile is the first tile of the Catching Tutorial NPC being loaded (2nd tree from the left). [Image](https://i.imgur.com/lgPAuic.png).
  - Make sure to BUFFER the save for both passes.
  - For pass 2 walk one right of the save tile then walk left and BUFFER the save.
---
### Resources
**Emulator Offset**: 12010

[**Movement Map 1**](https://imgur.com/a/i29RmEJ) 

[**Movement Map 2**](https://imgur.com/a/NkXcTza)

[**Practice States**](https://cdn.discordapp.com/attachments/368138878940479489/610691938995273768/r29_practice_states.zip)

---

### NPC cue

| Frame | NPC Movement |
| ----- | ------------ |
| 2 Early | Right->Up |
| 1 Early | Right->Down |
| Frame 1 | Right->Down |
| Frame 2 | Up |
| Frame 3 | Left->Down |
| 1 Late | Up->Right |
| 2 Late | Left |

---

## Paths

### Pass 1
```
[2] L L L L L L L L L L D D D L D D L L D D L L L L L L L L L L
    U U L U U U U R R R R R U U U L U L L A+L L L U L L L L L L 
    L L L U L L D L L A+L D L A+D L A+L L L L L L L L L L L L L 
    L L L L L L L L L L U U U L L L L L L L L L L L L L U U U U 
    U U U U U R R R R R U U U U U R U U U U U U U R R U U U U U 
    U U U U U U U U U U U U R U U R R U U U U L U U U
```

```
[3] L L L L L L L L L L D D D L D D L L D D L L L L L L L L L L
    U U L U U U U R R R R R U U U L U L L L L L U L A+L L L L L 
    L L L U L L D L L A+L D A+L D A+L L L L L L L L L L L L L L 
    L L L L L L L L L L L L A+U U U L L L L L L L L L L L U U U 
    U U U U U U R R R R R U U U U U R U U U U U U U U U U U R U 
    U R U U U U U U U U U U U R U U R R U U U U L U U U
```

```
[4] L L L L L L L L L L D D D L D D L L D D L L L L L L L L L U 
    U L L U U U U R R R R R U U U L L L U L L L U L L L L L L L 
    L L U L L L L A+L D D L L L A+L L L L A+L L L L L L L L L L 
    L L L L L D L A+L L L L U U U L L L L L L L L L L L U U U U 
    U U U U U R R R R R U U U U U R U U U U U U U U U U R U R U 
    U U U U U U U U U U U U R R U U R U U U U L U U U
```

### Pass 2

```
[2] L L L L L L L L L L D D D L D D L L D D L L L L L L L L L L U 
    U L U U U U R R R R R U U U L U L L A+L L L U L L L L L L L L 
    L U L L D L L A+L D L A+D L A+L L L L L L L L L L L L L L L L 
    L L L L L L L U A+U U L L L L L L L L L L L L L U U U U U U U 
    U U R U R R R R U U U U U U U U U U U U U U U L L U U L L L L 
    U U U U L U
```

```
[3] L L L L L L L L L L D D D L D D L L D D L L L L L L L L L L U 
    U L U U U U R R R R R U U U L U L L L L L U L A+L L L L L L L 
    L U L L D L L A+L D A+L D A+L L L L L L L L L L L L L L L L L 
    L L L L L A+L L L L L A+L U A+U U L L L L L L L L L U U U U U 
    U U U U U R R R R R U U U U U U U U U U U U U A+U U U U U L L 
    L U U L L U L L U
```

```
[4] L L L L L L L L L L D D D L D D L L D D L L L L L L L L L U U 
    L L U U U U R R R R R U U U L L L U L L L U L L L L L L L L L 
    U L L L L A+L D D L L L A+L L L L L L L L L L L L L L L L L L 
    L D L L L L U U L A+U L L L A+L L A+L L L L L A+L U U U U U U 
    U U U U R R R R R U U U U U U U U U U U U U U A+L U U U U L L 
    A+L U U L U L L U
```

---

## 1 Frame Early Routing

59/60 for both passes => L3 Male Pidgey in [this tile](https://gunnermaniac.com/pokeworld2?map=1#331/231)

**Pass 1**: Please see this [link](https://gunnermaniac.com/pokeworld2?map=1#345/225/LLLLLLLDDLDDDDLLLLLLLDLLLLLLLLLUUUUUURRRRRUUUULLLLLLULLLLLLLLLULLDLA+LDA+DLLA+LLA+LLLLLLLLLLLLLLLLLLLLLLLLLA+ULLUULLLLLLLLLUUUUUUUUURRRRRUUUUURUUUUUUUUUUUURURUUUUUUUUUUURRUURUUUULUU)

**Pass 2**: Please see this [link](https://gunnermaniac.com/pokeworld2?map=1#345/225/LLLLLLLDDLDDDDLLLLLLLDLLLLLLLLLUUUUUURRRRRUUUULLLLLLULLLLLLLLLULLDLA+LDA+DLLA+LLA+LLLLLLLLLLLLLLLLLLLLLLLUA+UULLLLLLLLLLLLLUUUUUUUUUURRRRRUUUUUUUUUUUUUUA+LUULUULULLLUUUL)