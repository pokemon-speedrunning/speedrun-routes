# Raikou Manip
This manip is an update to **entrpntr**'s original Raikou manip (and much of the paste is stolen from him), that supports the already set attributes from the Totodile and early encounter manips, as well as some other optimizations (amounts to 22-25 seconds of time save):

- Deposit Egg earlier, saving time in movement. Also saves a few inputs on the Rival 3 fight.
- No need to change Frame Type before the Raikou manip.
- Set clock to 10:01 AM, rather than 5:1X PM. Morning centers are slightly faster than night time due to a difference in text.
- No need to waste any steps after releasing the beasts.

The manip uses the same 3-frame cluster that entrpntr used, but with much improved stats and Hidden Power:
 - 1st frame (f11):  DVs: FD9E, HP Ice 69  (L40 stats: 133/85/75/108/96/104)
 - 2nd frame (f12):  DVs: FDBF, HP Ice 70  (L40 stats: 134/85/75/109/97/105)
 - 3rd frame (f13):  DVs: FDBF, HP Ice 70  (L40 stats: 134/85/75/109/97/105)


[Video of full cluster](https://youtu.be/KjWEqbgJp9k) (the green marked tiles represent A presses)

**Approximate offset for GBP/GSR**: ~12.091 seconds

- You can use the practice ROM and/or practice save at bottom of this paste to calibrate your offset (or find a game audio cue)


Conditions that must be met for a save to work with this manip:
 - PoisonStepCount = 1 (more info below)
 - StepCount must be between 0-97 or 128-225. (a few other values also work; more info below)
 - Party Size = 2 (Croconaw + Kenya)
 - Base RTC = 10:00:00 (StartHour/StartMinute/StartSecond)
   - If you are doing Toto manip, you already do steps to ensure this.
 - Your player sprite must be the girl character, on the bike, and facing right.
 - A repel must be active and have >= 32 steps remaining.
 - No pokes in party can be poisoned. (no specific requirements other than removing PSN before saving)
 
Things that don't [appear to] matter:
 - Whether or not you've fought Greg (r37 spinner)
 - Whether the save was buffered

After the Rival 3 battle, PoisonStepCount is set to 0. PoisonStepCount increases every step you take thereafter, but goes back to 0 on every 4th step ```(0->1->2->3->0->1->2->3->0, and so on)```. Two noteworthy exceptions to this: 
  1. PoisonStepCount doesn't increase on a step where a Repel wears out; 
  2. When jumping a ledge, PoisonStepCount only increases by 1 (despite moving 2 tiles).

To ensure a working PoisonStepCount, you must repel as soon as the encounter immunity in Burned Tower runs out (turnframe + first 3 steps have immunity), then make sure to not take any extra steps after the Burned Tower Rival fight. If you do happen to take an extra step, you must waste more steps in order for PoisonStepCount to roll back to 1.

StepCount starts at 0 from New Game, and doesn't get reset. It does, however, go back to 0 on every 256th step. RNG can be affected if StepCount reaches 128 or 256 (0) during a manip. The perfect StepCount for the current route is 215 (assumes hopping the ledge twice after Kurt's house, perfect Random NPCS [Squirtbottle girl, Magnet girl], and no spinners hit). You have just barely enough wiggle room for this manip to work without having to waste extra steps beforehand, however to reach this part of the StepCount cycle you must not take more than 9 additional steps throughout the entire run up to this point. If you do happen to take more than 9 extra steps, the backup is to take enough steps before Burned Tower to reach StepCount >= 0 on the manip save, which loses ~3 seconds. NOTE: Picking up the hidden Hyper Potion in Ecruteak costs 12 StepCount.

**IMPORTANT NOTE**: If you plan to use this manip without the Early Encounter and/or Totodile manip, you must figure out how you plan around StepCount. I personally see two options: 
 - (A): Walk the same paths are the manips assume, this will make all the StepCount info above apply to you.
 - (B): Take the optimal manipless paths to pickup Totodile and through the Routes, then proceed to take enough steps to reach 
         StepCount >= 0.

The exact problem values are the following (including any deviation from the promised igt, SLIGHTY OUTDATED!!):
 - 1st frame (f11): 97, 101, 103-108, 111, 117, 126, 127, 225, 229, 231-236, 239, 245, 254
 - 2nd frame (f12): 99, 102-108, 111, 117, 126, 227, 231-236, 239, 245, 254
 - 3rd frame (f13): 102, 104-108, 111, 117, 126, 230, 232-236, 239, 242, 254



CLUSTER INFO:

    (   9 - Ecruteak NPC  =  Left         )      
    (  10 - Ecruteak NPC  =  Right->Left  )

```
[11] R R R SEL R D D D D D D U A+D R L R D // D D D D L S_B U R R U U D U U D A+D
	- Ecruteak NPC = L  (1/60 r; Raikou Failure)
	- DVs: FD9E (133/85/75/108/96/104), HP Ice 69  
	- IGT: 54/60=FD9E (Ice 69);  No Encounter = f18/30/34/39/55/57
```

```
[12] R R R SEL R D D D D D D U A+D R L R D // D A+D D L U S_B R S_B R U D
	- Ecruteak NPC = r->R
	- DVs: FDBF (134/85/75/109/97/105), HP Ice 70
	- IGT: 53/60=FDBF (Ice 70);  No Encounter = f2/3/20/21/23/33/55
```

```
[13] R R R SEL R D D D D D D U A+D R L R D // D D D S_B D U U L L L SEL R
	- Ecruteak NPC = r
	- DVs: FDBF (134/85/75/109/97/105), HP Ice 70
	- IGT: 51/60=FDBF (Ice 70);  f4=FCBE (Psychic 69);  No Encounter = f20/21/27/34/39/41/51/55
```
```
   (  14 - Ecruteak NPC  =  L     )      
   (  15 - Ecruteak NPC  =  L->R  )
```

[Practice ROM](https://cdn.discordapp.com/attachments/385855173374771210/443505030470041600/crystal_dvcheck.gbc)
 > Check pokemon stats screen for frame and DVs (f11-f13 correspond to frames 160-162 on the practice ROM)

[Practice SAV](https://cdn.discordapp.com/attachments/613450037137113089/685480959042387998/raikou_ace.sav)
  > Whenever the save is loaded, it runs ACE to set RTC to the expected state (while maintaining correct RNG)

  > This removes the hassle of having to ensure your RTC is valid for the manip

[Practice Save States](https://cdn.discordapp.com/attachments/613450037137113089/685474204468117522/raikou_practice_states.zip)