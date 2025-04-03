# Imogens Kicad Library
Its so good!

_Gitignores 3dmodels folder, so any additional 3D models added by user should be added to ***3rd Party*** folder._ Do not save custom shapes in 3dmodels!

## Guide
_In an *attempt* to standardise KiCAD libs, and fully integrate the design, sourcing & fabrication process, each new custom or recycled part **should** be created with (at least) the following fields (only 1 source is required but alternatives are welcome_


| Field    | Data         | Example | 
|---       |---           |---      |
|Reference | Board part ID| U2      |
|Value     | Name         | TL072   |
|Footprint | Footprint that matches supplier| Package_SO:SOIC-14_3.9x8.7mm_P1.27mm |
|Datasheet | Link to Datasheet | http://www.ti.com/lit/ds/symlink/tl071.pdf |
|Description|Device Description |Quad Low-Noise JFET-Input Operational Amplifiers, DIP-14/SOIC-14 |
|MFN      | Manufacturers Number |                |
|JLCpart   | Part Number | C2915753 (example) |
|RSpart    | Part Number | 661-0076 |
|Farnellpart| Part Number |         |
|Mouserpart| Part Number |          |
|supplier  | Link to supplier | https://uk.rs-online.com/web/p/op-amps/6610076?gb=s |
|cost      | Price from referenced link for min order Q | £0.426 |


## LED Sourcing
_I often have a need to have all the available colours of LED to hand when designing. Well...here you go, now you can too_

### JLC LED Library
| Colour 	| MF part 		| JLCpart | package | Basic? |
|---		    |---			|---		|--- |---|
|red		|BL-HUF35A-AV-TRB	|		|
|Orange		|TJ-S2012SW8TGLC0A-A5	|		|
|Amber		|BL-HJC36G-AV-TRB	|	|0605!	|
|Yellow		|KT-0805Y		|
|yellow-green	|KT-0805YG		|		|
|green		|APT2012CGCK		|	|
|emerald	|KT-0805G		|
|blue		|LTST-C170TBKT		|	|
|ice-blue	|E6C0805TKAY1UDA	|		|
|purple		|GZ2012D101TF		|	|
|pink		|XL-2012UPC		|		|	
|white		|KT-0805W		|	|

 
 ## Use
 
 Place repo in library folder in KiCAD folder and ensure paths point to the correct folder.
 
![image](https://github.com/user-attachments/assets/e1aa89fd-407d-45fc-95b7-7d91fa923c1e)

 
 
 ### Color Schem
 _The Traditional KiCAD colours are an ugly crimson & blue and remind me too much of cops. Try a nice Orange and Blue Theme for PCBeditor_
 
 Find `imogen.json` in `schemas` folder. copy to themes folder, likely:
 
 ```
 $USER\AppData\Roaming\kicad\7.0\colors
 ```

