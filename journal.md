Made by: @The Grass
Repository link: https://github.com/IM-THE-GRASS/Grasshopper/
Total hours so far: 8hrs

Idea: My open-source, DIY 3D printer that aims to be <$300, fast and have multi-color capabilities
(a knockoff bambu labs printer :P )


Needs:
- Klipper compatibility
- Multicolor capability
- Speed
- <$300 
- doesnt burn my house down

## Current total time: 5hrs





<div align="center"><h1>Day 1</h1></div>
<div align="center"><h3>Feb 03, 2025 - 4hrs</h3></div>

<hr>

Today is my first day working on the printer, so I will be mainly focused on research & developing a basic parts list/BOM for the toolhead of the printer

### update 1 :

I discovered the Pico MMU, Rapido ACE UHF hotend & the Sherpa mini extruder today and started planning the basic toolhead of the printer
I began to make a (sort of) BOM that mainly just logs all the prices & sources I found. 

~~beginning tomorrow I will begin the CAD process of attaching the Sherpa Mini & Rapido ACE UHF and make a toolhead around it.~~ (I screwed up lol)

## Current parts list: 

> [!NOTE]
> Price & Source is the case for my part individually. Retail price & retail source could be a more realistic estimate for anyone expecting to build the Grasshopper themselves.

|         ‎         |                                                          Rapido ACE UHF<br>                                                          |                                       Sherpa Mini                                       |                                         Pico MMU                                          |                            Nema 17 motors                             |                                           PSU                                            | Linear rods | BLTouch | Metal extrusions (Exact specs TBD)        |
| :---------------: | :----------------------------------------------------------------------------------------------------------------------------------: | :-------------------------------------------------------------------------------------: | :---------------------------------------------------------------------------------------: | :-------------------------------------------------------------------: | :--------------------------------------------------------------------------------------: | :---------: | ------- | ----------------------------------------- |
| **Retail price**  |                                                             $86.90  USD                                                              |                                       $51.90 USD                                        |                                         ~$70 USD                                          |                                                                       |                                                                                          |             |         |                                           |
|     **Price**     |                                                         $68.41 USD (on sale)                                                         |                                  $38.39 USD (on sale)                                   |                                            TBD                                            |                                  $0                                   |                                            $0                                            |             |         |                                           |
|    **Source**     |                        [Trianglelabs](https://trianglelab.net/products/sherpa-mini-extruder?VariantsId=10515)                        | [TriangleLabs](https://trianglelab.net/products/sherpa-mini-extruder?VariantsId=10515)  |             [DIY    ](https://github.com/lhndo/LH-Stinger/wiki/Pico-MMU#bom)              |                         Torn Down Ender 3 V2                          |                                   Torn Down Ender 3 V2                                   |             |         | torn down Ender 3 V2                      |
| **Retail source** |                        [Trianglelabs](https://trianglelab.net/products/sherpa-mini-extruder?VariantsId=10515)                        | [TriangleLabs](https://trianglelab.net/products/sherpa-mini-extruder?VariantsId=10515)  |               [DIY](https://github.com/lhndo/LH-Stinger/wiki/Pico-MMU#bom)                |               [Aliexpress ](https://www.aliexpress.us/)               |                        [Aliexpress ](https://www.aliexpress.us/)                         |             |         | [Aliexpress ](https://www.aliexpress.us/) |
|      **Use**      | The Rapido Ace UHF seems like a great option for high flow applications with a maximum practical flow rate of <br>65mm<sup>3</sup>/s | I chose the sherpa mini based on personal preference but an Orbiter V2 could also work. | "Pico Multi Material Upgrade." A great  machine to upgrade any printer to multi-material. | Nema stepper motors are standard across almost all consumer printers. | My old ender 3 V2 has a meanwell PSU that I hope is good enough for this printer's power |             |         |                                           |
|     **count**     |                                                                  1                                                                   |                                            1                                            |                                             1                                             |                                  TBD                                  |                                            1                                             |     TBD     | 1       | TBD                                       |

<div align="center"><h1>Day 2</h1></div>
<div align="center"><h3>Feb 04, 2025 -  9hrs</h3></div>

<hr>

	overall total: 8hr
	daily total : 4hr
	research: 1hr
	building: 3hr
`

### Update 1:
Today was a lot more research to ensure the parts list were compatible with each other before starting CAD. Turns out, there's a LOT of compatibility issues with this parts list I developed. First of all, the power supply I was planning to use is 330W which won't be enough for this current setup The PSU will be TBD until the rest of the parts are finished to ensure compatibility. Along with that, the Rapido ACE UHF is an impressive hotend but not nearly what it claims to be & even if it was 65mm<sup>3</sup>/s would be an outrageous flow rate for a Sherpa Mini. Instead the Grasshopper is going to use a Dragon HF hotend for extra community support and more [reasonable stats](https://www.reddit.com/r/voroncorexy/comments/o0cuxd/does_anyone_know_max_flow_rate_for_different_hot/) & [price](https://www.trianglelab.net/products/dragon-hotend?VariantsId=11396). Next, the stepper motors from the Ender 3 don't have enough force to enable the speed that the Grasshopper is projected to run at. Instead a 3 pack of motors with *questionable* quality but a great price can be found on [aliexpress](https://www.aliexpress.us/item/2255801033887365.html?spm=a2g0o.productlist.main.2.76d645af92nVLa&algo_pvid=b81d5402-f309-40b6-9f3b-66931c66e33a&algo_exp_id=b81d5402-f309-40b6-9f3b-66931c66e33a-1&pdp_npi=4%40dis%21USD%2132.09%2125.99%21%21%2132.09%2125.99%21%402103146c17387183294372792eb597%2110000015342053269%21sea%21US%214468387228%21X&curPageLogUid=UKCwPiWFbb8p&utparam-url=scene%3Asearch%7Cquery_from%3A&gatewayAdapt=glo2usa). 

### Update 2: 
After looking at a couple more options in terms of parts, I decided to start taking apart the Ender 3 to figure out exactly what i could be working with. After 3 hours of work I sorted most of the parts that were usable into a small pile. 



this includes 
- 1x screen (https://github.com/bustedlogic/DWIN_T5UIC1_LCD for driving it)
- 4x stepper motor (probably going to go unused due to the lack of power)
- 1x mobo fan
- 1x hotend fan
- 1x blower style hotend fan
- 1x heated print bed
- 1x PSU (probably going to go unused due to the incompatibilities )
- 4x 2020 metal extrusions
- 1x base
- 3x switches
It's 1am right now while I'm writing this so I'll add the parts list tomorrow morning 



