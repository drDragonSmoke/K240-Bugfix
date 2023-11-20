# K240-Bugfix
K240 - Amiga game - Bug fixes - Assembly

<b>playk240.asm</b><br>
Heavily annotated disassembly. To reassemble with vasm:

vasmm68k_mot -no-opt -Fhunkexe -nosym -o playk240 playk240.asm

<b>playk240</b><br>
Reassembled play file. Version notes:
- Ship repair bug fixed
- Asteros drain bug fixed
- Fleet pause bug fixed
- F-keys deactivated on fleet targeting screen
- Powerplant can use asteros in stores
- Powerplant gives 8mw on zero ore
- Photon/plasma hardpoint price switched
- Alien ships can use their warp generator hardpoint
- Swixaran win screen changed to outro3.mgl
- Powerplant typo fixed (20MW to 32MW)
- Hangar typos fixed (hanger to hangar)
- Changed to single-clicks in hangar, shipyard and fleet windows


Some YouTube videos about it:
https://www.youtube.com/@drDragonSmoke

Fixes made possible by disassembly analysis and assistance provided by tetracorp:
https://github.com/tetracorp/k240

Also contributed: AmigaLive
Big thanks!
