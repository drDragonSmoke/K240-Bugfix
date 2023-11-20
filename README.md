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
- Spy peeking bug fixed
- Powerplant typo fixed (20MW to 32MW)
- Powerplant gives 8mw on zero ore
- Powerplant can use asteros in stores
- Photon/plasma hardpoint price switched
- Alien ships can use their warp generator hardpoint
- Swixaran win screen changed to outro3.mgl
- Changed to single-clicks in various windows

Some YouTube videos:
https://www.youtube.com/@drDragonSmoke

Fixes made possible by disassembly analysis and assistance provided by tetracorp:
https://github.com/tetracorp/k240

Also contributed: AmigaLive:
https://www.twitch.tv/amigalive

Big thanks!
