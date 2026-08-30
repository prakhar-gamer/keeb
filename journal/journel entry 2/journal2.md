## Entry 2 - Designed + Traced The PCB!

Hours: 2 and a half of work!, not much research this time

Durign this phase of devlopment, i genuinely thought of switching to linux. The very first issue that I had was trying to align all the keys to match the schematic structure, so the matric would be decently clean to wire up, but KiCad kept freezing up whenever I tried using Geographic Reannotation, so I just ended up manually doing it, and it took about 30 min

Strucutrally correct sequence for the Switches, but nothing else yet:
![sequaentionajklaksjd](https://cdn.hackclub.com/01a05452-26c4-7b07-9e9e-5f5622db29b9/sequencaledKeysnoAllignmentorDiode.png)

Then I started on spacing everything correctly, with like using the u system for a 60% keyboard, and it wasn't annoying but it was tedious, this took like a solid hour and a half because alligning the keys, then the diodes took forever, and I kept messing up the allignment of the key, but I was able to get it locked tf in. Also during this part I reinstalled Ki cad cause It geuininyallu was crashing everytime I double clicked on a diode, and it fixed it

![funnyimage2](https://cdn.hackclub.com/01a05452-2579-721c-ba9b-0f39e74e3b23/Alligned+DiodeKeys.png)

Tracing was annoying but not too bad, but helped my catch my bug in the rotary encoder as I missed a diode in the switch one. W advice from the docs for splitting up collumsn and rows nto the 2 different layers, I haven't done a ground fill yet. Wiring everything took like 30 min, It could have been way quicker but I didn't understand how to structure the collumn traces. 

Heres a photo of it in progress vs my traced v1! (prob need to change to make the board more optimized and did my edge cut too)
![inprogress](https://cdn.hackclub.com/01a05452-2a0e-75fc-b95a-7c8191575dab/wiringInprogress(collumns%20done).png)
vs
![final](https://cdn.hackclub.com/01a05452-28d6-7397-b5fd-5a07fde0b5f8/tracedv1+allignedKeys+Diodes.png)