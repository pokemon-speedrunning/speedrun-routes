# LID Frame Ranges

## Ranges:
| Frame | Trainer ID | Lottery ID |
| ----- | ---------- | ---------- |
| 6 Early | 0x62B3 (25267) | 0x1D4C (07500) |
| 5 Early | 0x91C6 (37318) | 0x71E8 (29160) |
| 4 Early | 0x3977 (14711) | 0x05D8 (01496) |
| 3 Early | 0x9157 (37207) | 0xBAC3 (47811) |
| 2 Early | 0x51D9 (20953) | 0x9EF1 (40689) |
| 1 Early | 0xF280 (62080) | 0x63FF (25599) |
| **TARGET** | **0x6F49 (28489)** | **0x03E9 (01001)** |
| 1 Late | 0xC439 (50233) | 0x7EAC (32428) |
| 2 Late | 0xF54E (62798) | 0xD34C (54092) |
| 3 Late | 0x0786 (01926) | 0x08CA (02250) |
| 4 Late | 0xEAE6 (60134) | 0x121C (04636) |
| 5 Late | 0xAC6A (44138) | 0xF74B (63307) |
| 6 Late | 0x5012 (20498) | 0xBE5C (48732) |

## Manip Lingo:

**gold** = gold (this manip does not work on Silver/Crystal, they have their own manips)

**gfskip** = buffer Start when booting the game so you skip the "Game Freak Presents" screen

**backoutx** = backout of the NEW GAME/OPTIONS screen to the title screen (buffer with B), then buffer back to the NEW GAME/OPTIONS screen (buffer with Start) x amount of times

**waitx(opt)** = wait x * 4 frames on the NEW GAME/OPTIONS screen, then enter options and buffer a backout of the options (buffer backout with Start)
- **Note**: the NEW GAME/OPTIONS screen only accepts inputs every 4 frames, so it's only a 4 frame window for timing waitx

**newgame** = buffer A to hit NEW GAME

Approximate Flowtimer offset: 28259

Adjust as needed, 4 frames = ~67 milliseconds 