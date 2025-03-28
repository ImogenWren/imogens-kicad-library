# Imogens Kicad Library
Its so good!

_Gitignores 3dmodels folder, so any additional 3D models added by user should be added to ***3rd Party*** folder._ Do not save custom shapes in 3dmodels!

## Guide
_In an *attempt* to standardise KiCAD libs, and fully integrate the design, sourcing & fabrication process, each new custom or recycled part should be created with the following fields_


| Field    | Data         | Example | 
|---       |---           |---      |
|Reference | Board part ID| U2      |
|Value     | Name         | TL072   |
|Footprint | Footprint that matches supplier| Package_SO:SOIC-14_3.9x8.7mm_P1.27mm |
|Datasheet | Link to Datasheet | http://www.ti.com/lit/ds/symlink/tl071.pdf |
|Description|Device Description |Quad Low-Noise JFET-Input Operational Amplifiers, DIP-14/SOIC-14 |
|JLCpart   | Part Number | C2915753 (example) |
|RSpart    | Part Number | 661-0076 |
|Farnellpart| Part Number |         |
|Mouserpart| Part Number |          |
|supplier  | Link to supplier | https://uk.rs-online.com/web/p/op-amps/6610076?gb=s |
|cost      | Price from referenced link for min order Q | £0.426 |

 
 ## Use
 
 Place repo in library folder in KiCAD folder and ensure paths point to the correct folder.
 
 ![image](https://user-images.githubusercontent.com/97303986/218597142-b3395193-c084-463d-b1ca-762e5402123e.png)
 
 
 ### Color Schem
 _The Traditional KiCAD colours are an ugly crimson & blue and remind me too much of cops. Try a nice Orange and Blue Theme for PCBeditor_
 
 Find `imogen.json` in `schemas` folder. copy to themes folder, likely:
 
 ```
 $USER\AppData\Roaming\kicad\7.0\colors
 ```

