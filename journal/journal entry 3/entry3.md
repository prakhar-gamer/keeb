## Entry 3 - Added a decent GND Fill, DRC, Custom SilkScreen Desgin!
Hours: 45 min (30 min not including the time to draw the super sick silk screen)

The Very first thing I tried doing was a GND fill, but when I tried it looked liked this 
![gapfill](https://user-cdn.hackclub-assets.com/01a05568-dd67-7838-878a-9d1d8ce93151/gndGapNovias.png)
There is this massive gap in the center, and I didn't no why so I spent some time in learning about the gnd fill and why to use, and realized I don't need it for this keyboard as all my gnds were connected to the pie, but it was good practice so i decided to make it.

I ended up using GND vias to conenct it, since my problem was that the gnd pins couldnt reach the center, due to my bad tracing design, so I disded to daisy chain it through my rotary encoder and hope for the best, and had to re trace a couple chains, and ended up making it work! Here how it looked now but there was a little, but I didn't want to retrace that part lmao.

![gndfilled!](https://cdn.hackclub.com/01a05568-db77-721d-aa0b-ae8ef8fa3351/gndFillMostlyFullvias.png) (isnt that dope)

Next Thing I did was work on clearing up a bunch of errors of the DRC (i dont think the warning matter, but let see if I regret it in the future!)
![drc](https://cdn.hackclub.com/01a05568-d9a9-72a2-a261-568a318998c6/DRCErrors.png)

Main thing was the Rotary encoder's diode, and a couple gnd vias not being connected, either way just took a while to connect all the tracings and re order the little things but I ended up clearing it up.

I decided that I didn't want my pcb looking super bland so I made some custom silkScreen art for it (15 min), and slapped it on, and I'm hopping the pcb could be black because it could look sick. Here is my final PCB design that I exported as my gerbert files (gerber files).

![:D](https://cdn.hackclub.com/01a05568-d7cc-7fd7-9dc3-c3e3968fff15/DRCClear+SilkArt.png)
:DDDDD