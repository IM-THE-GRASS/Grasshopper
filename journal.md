Idea: My open-source, DIY 3D printer that aims to be <$300, fast and have multi-color capabilities


Needs:
- Klipper compatibility
- Multicolor capability
- Speed
- <$300 




<br><br>




<div align="center">
  <h1>Day 1</h1>
  <h2>Feb 02-03, 2024</h2>
  <h3>4hrs, 4hrs total</h3>
  <br>
</div>
<hr>

## Overview of today:
Today is my first day working on the printer, so I will be mainly focused on research & developing a basic parts list/BOM for the toolhead of the printer

## update 1 :

I discovered the Pico MMU, Rapido ACE UHF hotend & the Sherpa mini extruder today and started planning the basic toolhead of the printer
I began to make a (sort of) BOM that mainly just logs all the prices & sources I found. 

beginning tomorrow I will begin the CAD process of attaching the Sherpa Mini & Rapido ACE UHF and make a toolhead around it.

## Current parts list: 

> [!NOTE]
> Price & Source is the case for my part individually. Retail price & retail source could be a more realistic estimate for anyone expecting to build the Grasshopper themselves.

|         ‎         |                                                          Rapido ACE UHF<br>                                                          |                                       Sherpa Mini                                       |                             Pico MMU                              |                            Nema 17 motors                             |                                           PSU                                            | Linear rods | BLTouch | Metal extrusions (Exact specs TBD)        |
|:-----------------:|:------------------------------------------------------------------------------------------------------------------------------------:|:---------------------------------------------------------------------------------------:|:-----------------------------------------------------------------:|:---------------------------------------------------------------------:|:----------------------------------------------------------------------------------------:|:-----------:| ------- | ----------------------------------------- |
| **Retail price**  |                                                             $86.90  USD                                                              |                                       $51.90 USD                                        |                             ~$70 USD                              |                                                                       |                                                                                          |             |         |                                           |
|     **Price**     |                                                         $68.41 USD (on sale)                                                         |                                  $38.39 USD (on sale)                                   |                                TBD                                |                                  $0                                   |                                            $0                                            |             |         |                                           |
|    **Source**     |                        [Trianglelabs](https://trianglelab.net/products/sherpa-mini-extruder?VariantsId=10515)                        | [TriangleLabs](https://trianglelab.net/products/sherpa-mini-extruder?VariantsId=10515)  | [Homemade](https://github.com/lhndo/LH-Stinger/wiki/Pico-MMU#bom) |                         Torn Down Ender 3 V2                          |                                   Torn Down Ender 3 V2                                   |             |         | torn down Ender 3 V2                      |
| **Retail source** |                        [Trianglelabs](https://trianglelab.net/products/sherpa-mini-extruder?VariantsId=10515)                        | [TriangleLabs](https://trianglelab.net/products/sherpa-mini-extruder?VariantsId=10515)  | [Homemade](https://github.com/lhndo/LH-Stinger/wiki/Pico-MMU#bom) |               [Aliexpress ](https://www.aliexpress.us/)               |                        [Aliexpress ](https://www.aliexpress.us/)                         |             |         | [Aliexpress ](https://www.aliexpress.us/) |
|      **Use**      | The Rapido Ace UHF seems like a great option for high flow applications with a maximum practical flow rate of <br>65mm<sup>3</sup>/s | I chose the sherpa mini based on personal preference but an Orbiter V2 could also work. |   A great lil machine to upgrade any printer to multi-material.   | Nema stepper motors are standard across almost all consumer printers. | My old ender 3 V2 has a meanwell PSU that I hope is good enough for this printer's power |             |         |                                           |
|     **count**     |                                                                  1                                                                   |                                            1                                            |                                 1                                 |                                  TBD                                  |                                            1                                             |     TBD     | 1       | TBD                                       |


