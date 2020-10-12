# Crystal FFFF/FFEF 2 Frame Totodile Manipulation
 
- Do LID manip then soft reset and start a timer
- Set options to Fast, Off, Set, Stereo, Frame Type 6
- Choose the Girl and set clock to 10:01AM (yoloscroll 5:13-5:16PM if doing old Raikou) clearing final yes/no box between 1:00.5 - 1:01.5 on 2nd timer
- Clear " with Pokemon awaits! Let's go! " textbox and start IGT track timer
- After Elm is done talking go up 1 tile then down 1 tile and BUFFER your start press then press Yes to save on the last beep of IGT timer
- Start Toto timer and reset at the same time, buffer intro and press A on the last beep.
- Standard movement is D A+R R A+R U (A press on the down and the 2nd right), HOWEVER if the npc is facing right (and then switches to left) you have to Start Flash right before talking to the ball.
- After talking to ball with A keep that held and swap to B on toto cry(let go of A), keep B held and clear 4 textboxes with A followed
  by holding A on the " A received Totodile " jingle

---------------------------------------------------------------------------------------------------------------------------------------

IGT Track window 8 frames IGT frames: 0-7(0-3 give FEEE on 2nd toto, 4-7 FFEF)

**Wsops offsets:**
LID: 34621
IGT: 78740 5 Beeps, Press A on 3rd beep unless bad intro
IGT2: 79740
Toto: 12989 

**Gunners offsets:**
LID: N/A
IGT: 79517
Toto: 12818

**NOTE**: You can increase and decrease the IGT offsets in intervals of 1000 *ms* since only the IGT frame matters; IGT second is irrelevant.

---
### Frame 59 
| **Movement** | **Stats** | **NPC** |
| ------------ | --------- | ------- |
| D A+R R A+R U S_B | 0xA8CB (20/12/12/10/10/10) | Up |
| D A+R R A+R U     | 0xA3C7 (20/12/11/10/10/10) | Up |

---

### Frame 60 
| **Movement** | **Stats** | **NPC** |
| ------------ | --------- | ------- |
| D A+R R A+R U S_B | 0xF607 (20/13/12/10/10/9) | Right |
| D A+R R A+R U     | 0xF508 (21/13/11/10/10/9) | Right |
| D A+R R A+R U     | 0xF609 (20/13/12/10/10/9) | Right |

---

### Frame 61
| **Movement** | **Stats** | **NPC** |
| ------------ | --------- | ------- |
| D A+R R A+R U S_B | 0xFFFF (21/13/12/10/11/10) | Right-Left |

---

### Frame 62
| **Movement** | **Stats** | **NPC** |
| ------------ | --------- | ------- |
| D A+R R A+R U | 0xFEEE (20/13/12/10/11/10) | Up |
| D A+R R A+R U | 0xFFEF (21/13/12/10/11/10) | Up |

---
### Frame 63
| **Movement** | **Stats** | **NPC** |
| ------------ | --------- | ------- |
| D A+R R A+R U S_B | 0x06E1 (20/11/12/9/9/10) (Female)   | Right |
| D A+R R A+R U     | 0x01DD (20/11/11/10/11/10) (Female) | Right |

---

### Frame 64
| **Movement** | **Stats** | **NPC** |
| ------------ | --------- | ------- |
| D A+R R A+R U S_B | 0x4A11 (20/11/12/9/9/9)    | Up |
| D A+R R A+R U S_B | 0x4910 (20/11/12/9/9/9)    | Up |
| D A+R R A+R U     | 0x2DF7 (20/11/12/10/10/10) | Up |
| D A+R R A+R U     | 0x2CF6 (20/11/12/10/10/10) | Up |