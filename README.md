_2nd Life_ is a complete TRS-80 Model III emulator for Atari ST, STE, TT, Falcon or compatible computers. It can be used to run most TRS-80 Model I and III programs.

It emulates the Z-80 microprocessor, video subsystem, keyboard, cassette relay, printer port, internal clock, floppy disk controller and four 80-track single sided disk drives. The emulation code is written completely in assembler, and as a result the emulated computer runs on a 16 MHz 68000 (STE) virtually as fast as the original machine. But even on an 8 Mhz ST the perceived speed is close to that of the original machine, as the emulator optimizes key ROM subroutines (I developed it on an 8 Mhz ST, so I know).

Test results from the included `SPEED.BAS` application which compares the speed to an original 2 Mhz Model III are:

| **Test** | **ST** | **STE** | **Falcon** | **TT** |
|:---------|:-------|:--------|:-----------|:-------|
| Integer  | 43%    | 85%     | 83%        | 170%   |
| Floating Point | 32%    | 59%     | 60%        | 121%   |
| Memory   | 45%    | 86%     | 88%        | 182%   |
| Text     | 170%   | 311%    | 311%       | 530%   |
| Scrolling | 60%    | 131%    | 217%       | 333%   |

The _Floating Point_ test is a good indicator of the CPU emulation speed. The perceived speed is much better though  because of the video and ROM subroutine acceleration feature.

The GEM shell is written in C and includes a font editor, keyboard layout editor, disassembler, debugger, memory dump and virtual diskdrives as icons in a window. It also offers a snapshot feature. The emulator even has joystick support (emulating TRS-80 spacebar and arrow key presses).

Besides the emulator, the package includes applications to convert disk images and transfer files between a TRS-80 and Atari ST through their parallel ports, as well as several virtual disks with TRS-80 software, a complete manual and additional documentation.

**Reviews**
  * [Atari Times](http://www.stcarchiv.de/ataritimes/09_2ndlife.php)
  * [ATOS Magazine (German)](http://www.mindrup.de/atos/online/9606/2ndlife.htm)
  * [ST Computer (German)](http://www.stcarchiv.de/stc1997/06_2ndlife_de.php)
  * [XIO3 (PDF)](http://www.strotmann.de/~cas/Infothek/XioSeptOctninesex/xio391096.pdf)

**Interesting Sites**
  * [TRS-80](http://en.wikipedia.org/wiki/TRS-80) on Wikipedia
  * [Atari ST](http://en.wikipedia.org/wiki/Atari_st) on Wikipedia
  * Software based [128x192](http://members.shaw.ca/gp2000/beamhack1.html) graphics on a real Model III
  * [TRS-80](http://www.trs-80.com/) details
  * [TRS-80](http://www.trs-80.org/) details
