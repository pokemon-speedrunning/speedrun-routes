# Pokemon Red Triple Extended Manip v4.0
credits to hwangbro/stringflow

Glossary:
  - 'r' means NPC is looking RIGHT
  - 'R' means NPC moves RIGHT
  - u->L means NPC is looking UP, then moves LEFT
  - r->D/L means NPC is looking RIGHT, then moves DOWN or LEFT

## "Main" Paths

PATH | [NPC 1](https://gunnermaniac.com/pokeworld?map=1#53/182) | [NPC 2](https://gunnermaniac.com/pokeworld?map=1#57/167) | [NPC 3](https://gunnermaniac.com/pokeworld?map=50#2/4) | [NPC 4](https://gunnermaniac.com/pokeworld?map=51#16/43) | [NPC 5](https://gunnermaniac.com/pokeworld?map=51#27/40) | STRING SHOT | PIDGEY MAP | HOUSE MAP | FOREST MAP
---- | ----- | ------ | ------ | ------ | ------ | ------------------ | ------------ | --- | ---
1 | r | R | D | d | D | 5 Frames (~145.5/158.5, 91.8%) | [Link](https://gunnermaniac.com/pokeworld?map=1#33/181/DRRUUURRRRRRRRRRRRRRRRRRRRRURUUUUUURUUUULUUUUUUAUUUUUUUUUUUUULLLUUUUUUUUUUURRRRUULLLLLUUU) | [Link](https://gunnermaniac.com/pokeworld?map=50#4/7/RUUUUUUU) | [Link](https://gunnermaniac.com/pokeworld?map=51#17/47/UUUURRRRRURRRUUUUUUUUUUUUUUUUUUUUUUUUUUUUUUUUUALLLLLLLLDDDDDDDLLLLUUUUUUUUUUUUULLLLLLDDDDDDDDDDDDDDDDDDLDLLLLUUU) |
2 | u->L | R->L | D | r->u | d | 5 Frames (~249.3/259.8, 96%) | [Link](https://gunnermaniac.com/pokeworld?map=1#33/181/DRRUUURRRRRRRRRRRRRRRRRRRRRURUUUUUURUUAUULUUUAUUUUUUUUUUUUUUAUULLLUUUUUUURRRRUAUUUUUUULLLLLU) | [Link](https://gunnermaniac.com/pokeworld?map=50#4/7/UUUUURUU) | [Link](https://gunnermaniac.com/pokeworld?map=51#17/47/UUAUURUARRRRRRRUUUUUUUUUUUAUUAUUUUUUUUUUUUUUUUUUUULLLLLLLLDDDDDDDLLLLUUUUUUUUUUUUULLLLLLDDDDDDDDDDDDDDDDDDLDLLLLUUU) |
3 | r->L | L | U | u->r | r | 4 Frames (~200.2/214.1, 93.5%) | [Link](https://gunnermaniac.com/pokeworld?map=1#33/181/DRRUUURRRRRRRRRRRRRRRRRRRRRURUUUUUURAUUUUUUUUUUUUUUUUUUUULUAUULLLUUUUUUUUUURRRARUUUUAULLLLLU) | [Link](https://gunnermaniac.com/pokeworld?map=50#4/7/RUUUUUUU) | [Link](https://gunnermaniac.com/pokeworld?map=51#17/47/UUURURRURRRRRUAUUUUUUUUUUUUUUUUUUAUUUUUUUUUUUUUULLLLLLLLDDDDDDDLLLLUUUUUUUUUUUUULLLLLLDDDDDDDDDDDDDDDDDDDLLLLLUAUU) |
3v2 | r->D | L->R | U | d | u | | | | |
4 | u->U | L | D | l->u->r | l | 6 Frames (~283.3/316.9, 89.4%) | [Link](https://gunnermaniac.com/pokeworld?map=1#33/181/DRRUUURRRRRRRRRRRRRRRRRRRRRURUUUUUURUUUUUUUUUULAUUUUAUUUUAUUUAUULLLUUUUUUUUAURRRRUUUUUULLLLLU) | [Link](https://gunnermaniac.com/pokeworld?map=50#4/7/UUUUUURU) | [Link](https://gunnermaniac.com/pokeworld?map=51#17/47/UUUURURRRRRRRAUUUAUUUAUUUUUUUUUUUUUUUAUUUUUUUUUUUULLLLLLLLDDDDDDDLLLLUUUUUUUUUUUUULLLLLLDDDDDADDADDADDDDDDDDDDLLLLLAUUU) |
5 | d | R | U | d | l | 8 Frames (407.2/423.5, 96.2%) | [Link](https://gunnermaniac.com/pokeworld?map=1#33/181/DRRUUURRRRRRRRRRRRRRRRRRRRRURUUUUUURUUUULUUUUUUAUUUUUUUUAUUUAUULLLUUUUUUAUURRUUAURRUUUULLLLLU) | [Link](https://gunnermaniac.com/pokeworld?map=50#4/7/UUUURUUU) | [Link](https://gunnermaniac.com/pokeworld?map=51#17/47/UUUURRRRRRRURAUUUUUAUUUUUUAUUUUUUUUUUUUUUUUUAUUUUULLLLLLLLDDDDDDDLLLLUUUUUUUUUUUUULLLLLLDDDDDDDDDDDDDDDDDDDLLLLLAUUU) |
6 | d | L | U | d | u->d | 5 Frames (252.9/263.8, 95.9%) | [Link](https://gunnermaniac.com/pokeworld?map=1#33/181/DRRUUURRRRRRRRRRRRRRRRRRRRRURUUUUUURUUUUUUUUUULAUUUUUUUUUUUUUULLLUUAUUUAURRRRAUUUUUULALLLLUUU) | [Link](https://gunnermaniac.com/pokeworld?map=50#4/7/RUUUUUUU) | [Link](https://gunnermaniac.com/pokeworld?map=51#17/47/UUURURRRRRRRUUUUUUUAUUUUAUUUUUUUUUUUUUAUUUAUUUUUUULLLLLLLLDDDDDDDLLLLUUUUUUUUUUUUULLLLLLDDDDDDDDDDDDDDDDDDLDLLLLUUU)
6v2 | d | L | U->D | u | l->u | | | | |
6v3 | d | L->R | U->U | u | l->u | | | | |

``` PATH 1
Pidgey:
    SUCCESS (3181/3420, ~53/57)
    r,R: 53/57

    FAIL
    u,L: 1/57
    d,L: 1/57
    d->L,R: 1/57
    r,R: 1/57

Forest:
    SUCCESS (3170/3181, ~52.83/53)
    D,d,d 49/53
    D,d,u 1/53
    D,u,l 1/53
    D,u,D 1/53
    U->D->D,r,r 1/53

Path 2
Pidgey:
    SUCCESS (3182/3420, ~53/57)
    u->L,R->L: 53/57

    FAIL
    u,L: 1/57
    r,L: 1/57
    L->U,R: 1/57
    u->L,R->L: 1/57

Forest:
    SUCCESS (3117/3182, ~52/53)
    D,r->u,d, 47/53
    D,r->u->l,u->d, 1/53
    U,r->u->d,u->d->r, 1/53
    D->U,d,d, 1/53
    D,r->l,u, 1/53
    D->U->D,r->u,r->l, 1/53
    D,r->u->r,r->l, 1/53

Path 3
Pidgey:
    SUCCESS (3233/3240) (~54/57)
    r->L,L: 41/57
    r->D,L->R: 12/57
    d,L: 1/57

    FAIL
    r->L,R: 1/57
    r->L,L: 1/57
    u->D->U,L: 1/57

Forest:
    SUCCESS (3212/3223, ~53.5/54)
    r->L, L
        L,U,u->r,r 33/54
        L,U,d,u, 4/54
        L,U,u,r, 1/54
        L,D,u->r,u, 1/54
        L,U,d,u->l->d->l, 1/54
        L,D->D,l,r, 1/54
        L,U,d->r,u, 1/54

    r->D, L->R
        U,d,u 10/54
        U,d->r->l,u, 1/54

    d, L
        D,r,u: 1/54

Path 4
Pidgey:
    SUCCESS (3181/3240, ~53/57)
    u->U,L: 53/57

    FAIL
    L->U,L->R: 1/57
    r->U,L: 1/57
    r->D,L->R: 1/57
    u->U,L: 1/57

Forest:
    SUCCESS (3169/3181, ~52.8/53)
    D,l->u->r,l, 38/53
    D,d->u,r->d->u, 5/53
    D,d->u,d->l, 2/53
    D,l->u,u->d, 1/53
    D,l->u,d->l->r, 1/53
    D,u,l, 1/53
    U->U,r,d, 1/53
    D,l->r,d->l->r, 1/53
    U,r,r->u, 1/53
    D,d->u,d, 1/53

Path 5
Pidgey:
    SUCCESS (3178/3240, ~53/57)
    d,R: 53/57

    FAIL
    d,L->r: 1/57
    u->U,L: 1/57
    u->L,L: 1/57
    d,R: 1/57

Forest:
    SUCCESS (3176/3178, ~52.9/53)
    U,d,l, 50/53
    U,u,r->d 1/53
    U,l->u,d->u, 1/53
    U,d,u->d->r, 1/53

Path 6
Pidgey:
    SUCCESS (3181/3240, ~53/57)
    d,L: 47/57
    d,L->R: 6/57

    FAIL
    L,R: 1/57
    d->R->L,L: 1/57
    u->U,R: 1/57
    d,L: 1/57

Forest:
    SUCCESS (3165/3181, ~52.8/53)
    d, L
        U,d,u->d, 33/53
        U->D,u,l->u, 7/53
        D,r->d,l->u->r, 1/53
        U,d,l, 1/53
        U,u,u, 1/53
        U,u,u->d, 1/53
        U->U,u,l->u, 2/53
        U->D,r->l,u->d, 1/53

    d, L->R
        U->U,u,l->u: 6/53
