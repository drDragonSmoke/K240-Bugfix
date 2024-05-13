# K240-Bugfix
K240 - Amiga game - Bug fixes - Assembly

<b>playk240.asm (version)</b><br>
Heavily annotated disassembly. To reassemble with vasm (remove version from name):

vasmm68k_mot -no-opt -Fhunkexe -nosym -o playk240 playk240.asm

<b>playk240 (version)</b><br>
Reassembled play file. To use (remove version from name):

Put in: <i>[your K240 gamefiles folder]\Hard Drives\data\ </i><br>

It will replace the original file, so you might want to save it first.<br>

Version notes:
- Ship repair bug fixed
- Asteros drain bug fixed
- Fleet freeze bug fixed
- Spy peeking bug fixed
- Yard alerts bug fixed
- Scout ship ore bug fixed
- OSD ships armor bug fixed 
- Powerplant typo fixed (20MW to 32MW)
- Powerplant gives 8mw on zero ore
- Powerplant can use asteros in stores
- Photon/plasma hardpoint price switched
- Alien ships can use their warp generator hardpoint
- Swixaran win screen changed to outro3.mgl
- Changed to single left-clicks in various windows

References:
- <a href="https://tetracorp.github.io/k240/game-mechanics/bugs.html">Various bugs</a>
- <a href="https://tetracorp.github.io/k240/game-mechanics/bugs-photon-plasma.html">Photon vs. Plasma</a>
- <a href="https://github.com/tetracorp/k240/issues/13">Fleet freeze bug</a>
- <a href="https://tetracorp.github.io/k240/fun/powerplant-sucks.html">The Powerplant sucks</a>

A few YouTube videos:
https://www.youtube.com/@drDragonSmoke

Fixes made possible by disassembly analysis and assistance provided by <i>tetracorp</i><br>
https://github.com/tetracorp/k240

Also contributed: <i>AmigaLive</i><br>
https://www.twitch.tv/amigalive

Big thanks!
