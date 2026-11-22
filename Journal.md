---
title: "SPAR-75"
github: "https://github.com/Sparsh230/SPAR-75"
description: " A 75% MECHANICAL KEYBOARD "
created_at: "2026-10-06"
total_time: "22h 12m"
---

# October 6, 2026: MADE THE SPAR-75 LAYOUT IN KEYBOARD LAYOUT EDITOR
<!-- fabricate:entry 162 -->

10/06/2026
1st day-
today i have created the SPAR-75 layout in keyboard layout editor 
![](https://fabricate.hackclub-assets.com/3d2c5c36723f2ec9cd7e03a22068e6976a8f803f4a468ed5ca1b93791e93bc0e/Screenshot%202026-10-06%20231955.png)

I have selected the keycool 84 option in the presect section and done some changes 
the selected key in the image will will be rotartry encoder

**Total time spent: 30m**

# October 19, 2026: MADE THE SCHEMATIC OF KEYBOARD MATRICS
<!-- fabricate:entry 664 -->

![](https://fabricate.hackclub-assets.com/01985f594a90fd4d0c54fb855a8f9f2d8ca66df8406651ffe35f36baae2fe7e3/image-png/Screenshot%202026-10-19%20004308.png)
  MADE 12 COLUMNS AND 7 ROWS FOR SPAR 75 ,I THINK IT WILL BE THE BEST OPEN SOURCE MECHANICAL KEYBOARD BEC IT IS SPAR-75 NOT UR ORDINARY KEYBOARD ,USED KI CAD FOR THE SCHMETAIC

**Total time spent: 2h**

# October 19, 2026 (entry 2): Made new schmetics
<!-- fabricate:entry 685 -->

DAY-2

made 3 schmetics for the spar-75 
it has rgb per switch![

![](https://fabricate.hackclub-assets.com/6129483bc8c9351ad068012192bf9a6521e9f092e3a2e2846e5828cf305dfede/image-png/Screenshot%202026-10-19%20145004.png)


rotatory encoder and a oled display
![](https://fabricate.hackclub-assets.com/7e7b75f4e47d0f24c08d04b2509084771dddc3818266cdd5230522238f55747d/image-png/image.png)


and i am using pi pico2 (available in my reigon)

![](https://fabricate.hackclub-assets.com/b0bd98ddadf04a07a66d432a45465eb7de3daa2a3e8f9a00dc5a2944513e97b0/image-png/Screenshot%202026-10-19%20115851.png)


this is the best thing i am crating its fun make and this keyboard will be my first mechanical keyboard

 i will be changing sw_push name to keyboard key cuz easy for me in future

**Total time spent: 3h**

# October 22, 2026: REASSIGNING THE SCHMETIC
<!-- fabricate:entry 1035 -->

DAY 3 ![](https://fabricate.hackclub-assets.com/7e7453b4a297688d52d140b0a29c3526eed3dc3f5982c23b126a7b1c6b4246d3/image-png/Screenshot%202026-10-22%20221737.png)
  CHANGED THE VALUE OF SCHMETIC ,CHANGE SWITCH LOCATION ACC TO THE KEYBOARD LAYOUT AND THERE ARE 6 ROWS AND 16 COLUNM TOTAL KEYS-84  ,FIRST TIME MAKING HARDWARE FOR YSWS MADE A MACROPAD BEFORE BUT WITHOUT MATRICKS AND IT IS FUN TO MAKE IT WILL TOOK ME AROUND 10H MORE TO COMPLETE THE PCB + I AM PRO IN CAD SO EASILY CAN MAKE A CASE



started at 7:00 PM
      now 10:21 PM

**Total time spent: 3h 12m**

# November 3, 2026: Routed the PCB
<!-- fabricate:entry 2097 -->

week-2

Finnaly routed the pcb,
faced many problems 1st the main problem was that i routed my first pcb then open that drc and saw 500+error bec the footprint assignment was wrong and i wasted 5+h for routing , i know i was cooked ,

then i started with a new schemetic , same as previous one and i removed that led light and stuff only switches were in schemtic and then i routed the pcb i have created 


here's the PCB routing:

F.cu:
![](https://fabricate.hackclub-assets.com/1e3b5d801e9c764d0e36463eeeb478496438b64d1ec225535d0e7c05d17311d2/image-png/Screenshot%202026-11-03%20220143.png)

B.cu:
![](https://fabricate.hackclub-assets.com/db03662143bfc5cdf60c507e8088bfe335e50eccce9f95e30649fd0e7a18ff4e/image-png/Screenshot%202026-11-03%20220243.png)

3d view:

![](https://fabricate.hackclub-assets.com/f5a8d643203b7f588bdf853e18faad152faffe89ad8fcc0d5b93e3c24e37e322/image-png/Screenshot%202026-11-03%20220305.png)



total time i spent: around 7.5h but selected 6.7 because sixsevenn!!!!!

**Total time spent: 6h 42m**

# November 4, 2026: BOM
<!-- fabricate:entry 2104 -->

Making BOM
exported the pcb into a gerber file 

PCB COST:
![](https://fabricate.hackclub-assets.com/5540692ad9490e45fb7245fafa96e7beb3bb4703cbeb384d7433855b4fe4561c/image-png/Screenshot%202026-11-03%20235254.png)
  COST- 75.5$

![](https://fabricate.hackclub-assets.com/736f33b7c848063fd5439ed95b7e1c8c331cac9b67653cca3fbe7ca921160116/image-png/Screenshot%202026-11-04%20000613.png)

3d print(spool):
![](https://fabricate.hackclub-assets.com/908bbac8747a84b5a5ef1c7063a01bff6b4e61c70cfcc10892ff9bcca88aad04/image-png/Screenshot%202026-11-04%20001135.png)

  cost - 10$

Diode(1N4148):
![](https://fabricate.hackclub-assets.com/7398512504065e020686cc92c96aff54e416f39361d7c6e580cedea9ca9a7d09/image-png/Screenshot%202026-11-04%20001951.png)

COST: 2$+1$(SHIPPING)


Switches + keycap:
![](https://fabricate.hackclub-assets.com/c4f4a3482f0a1a5ac169b7a1b15a69da16008ebe4824208e5d047d3ae3462d32/image-png/Screenshot%202026-11-04%20000740.png)

cost - 36.5$


--------------------------------------------------------------------------------------------------------


Total 125$

**Total time spent: 1h**

# November 22, 2026: Made the firmware
<!-- fabricate:entry 3688 -->

Finnaly made the firmware for SPAR-75
i have used QMK Firmware,and i learned from youtube how to make a firmare
then created my own it tokk me 2h to understand ,not mentioning this and 
when i finnaly exported the firmware it was showing some problems
then i solved the the proble,solving problem took me 1.5h and the firmware is now ready
![](https://fabricate.hackclub-assets.com/f4f09231820c1388550c421767522193a44feb7e3c80f06962f9ac0dddba79b9/image-png/Screenshot%202026-11-22%20134331.png)

**Total time spent: 4h**

# November 22, 2026 (entry 2): Made KEYBOARD CASE (PLATELESS MOUNT)
<!-- fabricate:entry 3689 -->

finnaly made the keyboard case
i used onshape for cad 
i designed the keyboard case as plateless mount bec it looks cool
and i never had any keyboard with plateless keyboard

pcb 3d model
![](https://fabricate.hackclub-assets.com/daedf1807e876ba399e36ec67393bbe23c1570f1e3c559f25a9b1583f4e931cb/image-png/Screenshot%202026-11-22%20134636.png)


Case
![](https://fabricate.hackclub-assets.com/eb0790ff92e7a6554b7b74c4799a802b77f65a175d9921d9be653de534193373/image-png/Screenshot%202026-11-22%20134656.png)


assembled
![](https://fabricate.hackclub-assets.com/c02a9f7ad0c0fef68e8866ccf24d166e1a1bf7cbb9851a785e238fb801e32a86/image-png/Screenshot%202026-11-22%20134712.png)

**Total time spent: 1h 48m**

