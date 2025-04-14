
<div align="center"><h1>Day 1</h1></div>
<div align="center"><h3>Mar 26, 2025 - 11hrs</h3></div>

<hr>

The Infill grant is due in less than 5 days, so my goal for the next couple days was to speedrun the printer, and that's why I spent 10+ hours almost every day.

### update 1 :

Initially, I spent some time creating a BOM for my printer to plan out a budget & make a concept for what will be needed for the printer.2-3 hours were spent formulating a BOM that included all the necessities for a basic printer, but didn't have multicolor. 
In the future, if I can manage some budgeting I'm planning to add a [Pico MMU](https://github.com/lhndo/LH-Stinger/tree/main/User_Mods/MMU/Stinger%20Pico%20MMU%20-%20%40LH), but without the extra servo, stepper, belts, etc. added by a Pico MMU the total (excluding shipping & taxes) was already $283.82. The size of the Infill grant limits the Grasshopper's budget to <$300, and even a basic BOM was reaching far too close to that ceiling. That means I'll certainly have to adjust the BOM, but for now I'll start on CAD for a basic frame.

### update 2 :

After looking at my options for the frame of the printer, I decided to make the basic frame out of 2040 and 4040 T slot aluminum extrusions (and later 2020 extrusions). They're sturdy enough and I already had enough for almost the entire printer. 


 ![[Pasted image 20250329002239.png]]
 I made this connector in Fusion 360 that allows 4040 and 2040 extrusions to slot together at a 90 degree angle.  



![[Pasted image 20250329002521.png]]
Using those connectors, I made this basic frame that I would later fill in the gaps of.



![[Pasted image 20250329002803.png]]
For the top of the printer, I modeled some other basic connectors for 2040 and 2020 extrusions and then sed some pre-tapped extrusions for the other side. The pre-tapped extrusions use M5 screws.



### update 3 :



![[Pasted image 20250329004626.png]]
After, I mounted the linear rods and placed the Z axis stepper motor so I could then mount the bed. 

The linear rods are mounted using a 3d printed bracket that slides into the 4040 extrusions and uses M5 screws to secure itself. The top of the linear rods are supported by a 3D printed part that bridges two connectors at the top.



![[Pasted image 20250329005031.png]]
I then sketched out a part that the bed would screw into. The two linear rods stabilize it and the lead screw moves the bed up and down.



![[Pasted image 20250329005222.png]]
The bed I used was a 220W heated bed from a Creality Ender 3 V2 that I already had on hand. It uses M3 screws to fasten itself to the part that was mentioned in the last section.



### update 4 :



![[Pasted image 20250329005437.png]]
I added a box for the mainboard and Raspberry Pi Zero 2W to reside in. The box has a separated top and bottom which allows easy access to the electronics within. Both parts slide in using the slots in the 4040 aluminum extrusions and are locked into place by the connectors



![[Pasted image 20250329005748.png]]
I added screw holes to the connectors that permit M5 screws using heat set inserts to secure the connectors and prevent issues with the connectors moving slightly out of place.



![[Pasted image 20250329010020.png]]
Afterwards I began on the XY gantry at the top of the printer that would later hold the printhead and all the motion components (other than the Z axis). It uses MGN12 linear rails and 3d printed connectors. 



<div align="center"><h1>Day 2</h1></div>
<div align="center"><h3>Mar 27, 2025 - 5hrs</h3></div>

<hr>
Today was spent on mostly making the belt path of the printer. I also researched a bit more about the parts required and realized that there was no way the Grasshopper can fit a Pico MMU in the budget. Today the budget was finalized and, after accounting for a higher flow nozzle and faster stepper motors, I was overbudget by a significant amount without any gimmicks like multicolor. Because of that, I scrapped the multicolor idea and decided to pay for part of the printer out of pocket. 



Today I didn't do much in terms of CAD other than copy & pasting pulleys and belts.


In the end, this is how the belt path looked:
![[Pasted image 20250329013223.png]]

The path follows this basic idea:
![[Pasted image 20250329013510.png]]

<div align="center"><h1>Day 3</h1></div>
<div align="center"><h3>Mar 28, 2025 - 12hrs</h3></div>

<hr>
Today I didn't do much research as my BOM was mostly done but I spent my time CAD-ing the toolhead, which was by far the part of the printer I was least confident in making.

### update 1:

![[Pasted image 20250329014031.png]]
First, I placed the parts in the way they would be in the final printer. On top there's a Sherpa Mini extruder, the hotend is a Trianglelabs Dragon Ace and the fans on the side are 4020 blower fans.

### update 2:

![[Pasted image 20250329014443.png]]

After some struggle, I made this part that would connect the entire hotend together that I plan to 3D print using a heat resistant filament.

### update 3:
![[Pasted image 20250329015037.png]]
Afterwards, I built a case around the core of the hotend.



### update 4:

At this point, the printer was finished. 
![[Pasted image 20250329020400.png]]

