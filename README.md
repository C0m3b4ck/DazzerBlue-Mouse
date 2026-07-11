# DazzerBlue TRAMYS44940 Mouse in KiCAD 
[@PrinterFixer](https://www.youtube.com/@PrinterFixer)
[Video title here](VIDEO HERE - IF THERE IS NONE THEN IT IS NOT DONE)

KiCAD project with GERBER and DRILL files of the DazzerBlue TRAMYS44940 mouse PCB from 2018/09/25, remade manually by me, C0m3b4ck. All models of all components are in place, the PCB is of accurate size. The only inacurracies are the connections, which aren't 1:1 to the actual PCB. The microswitch and the rotary encoder are the exact same but from different companies (couldn't find original companies).

**The mouse is end-of-life.**

## Purpose

This repository preserves the complete investigation of the DazzerBlue TRAMYS44940 mouse hardware: project files, documentation and images.
It is intended as a technical reference for anyone analyzing, repairing, or getting inspired by the DazzerBlue TRAMYS44940 design and the V101S-based optical mouse architecture.

## GERBER, DRILL and BOM (click to download)
* [Full labelling and components](https://github.com/C0m3b4ck/DazzerBlue-Mouse/blob/main/DazzerBlue-GERBER-DRILL.7z)
* [Bill of Materials in .CSV](https://github.com/C0m3b4ck/DazzerBlue-Mouse/blob/main/DazzerBlue-BOM.csv)
## Components:
* V101S IC - [unofficial documentation made](https://github.com/C0m3b4ck/DazzerBlue-Mouse/blob/main/DOCS/V101S-unofficial.pdf),
* 2x Illinois KXM Capacitor 100uf - [documentation included](https://github.com/C0m3b4ck/DazzerBlue-Mouse/blob/main/DOCS/Omron-D2F-01-A-datasheet.pdf),
* 68ohm resistor,
* 3x Omron D2F-01 microswitch - [documentation included](https://github.com/C0m3b4ck/DazzerBlue-Mouse/blob/main/DOCS/Omron-D2F-01-A-datasheet.pdf) (same as on PCB but from a different company),
* 2-pin LED,
* 3-pin AlpsAlpine Rotary Encoder,

## Repository layout

- `DOCS/` — component datasheets and board photos.
- 'DazzerBlue-proj/DazzerBlue-proj.kicad_pro' - project file.
- 'DazzerBlue-proj' - project directory.
- `DazzerBlue-GERBER-DRILL.7z` — archived Gerber/drill package.

## Images
| | | | |
|---|---|---|---|
| <div align="center"><img src="DOCS/pcb_underside.png" alt="Virtual PCB underside" width="250"><br><sub>PCB 3D view in KiCAD - underside.</sub></div> | <div align="center"><img src="DOCS/pcb_top.png" alt="Virtual PCB top" width="250"><br><sub>PCB 3D view in KiCAD - top view.</sub></div> | <div align="center"><img src="DOCS/pcb_left.png" alt="Virtual PCB left" width="250"><br><sub>PCB 3D view in KiCAD - left.</sub></div> | <div align="center"><img src="DOCS/pcb_right.png" alt="Virtual PCB right" width="250"><br><sub>PCB 3D view in KiCAD - right.</sub></div> |
| <div align="center"><img src="DOCS/irl_bottom.png" alt="PCB underside" width="250"><br><sub>The underside of the PCB.</sub></div> | <div align="center"><img src="DOCS/irl_top.png" alt="PCB top view" width="250"><br><sub>View of the PCB from top.</sub></div> | <div align="center"><img src="DOCS/irl_left.png" alt="PCB left view" width="250"><br><sub>View of the PCB from the left.</sub></div> | <div align="center"><img src="DOCS/irl_right.png" alt="PCB right view" width="250"><br><sub>View of the PCB from the right.</sub></div> |
| <div align="center"><img src="DOCS/IMG_6143.png" alt="Stock board overview" width="250"><br><sub>The mouse case, stock photo.</sub></div> | <div align="center"><img src="DOCS/IMG_6684.png" alt="Full case and cable from top" width="250"><br><sub>Full mouse case and cable view from top.</sub></div> |  |  |
| <div align="center"><div align="center"><img src="DOCS/sketch1.png" alt="Schematic" width="250"><br><sub>Schematic of full circuit.</sub></div> |  |  |

## Credits

**Project made manually by C0m3b4ck from 08/07/2026 to 10/07/2026.**
* Unofficial V101S documentation written by C0m3b4ck,
* V101S and 4pin_male_5mm_10mm made by C0m3b4ck,
* Alpine Rotary Encoder from [AlpsAlpine](https://www.alpsalpine.com/j/)
* D2F-01 microswitch from [Omron](https://www.omron.com/global/en/),
* KXM Capacitor from Illinois capacitor (website shut down),
