# Z80PACK Compatible Disk Images

This repository contains Z80PACK compatible `.dsk` disk images & High Nibble compatible `.unpacked` ZIPs containing new software that isn't included in Z80PACK. 

This repository is meant as a distribution point for these disk images. Source code for the programs on these disks may be found in other repositories if I have published that source.

## Compatibility

These disks have been lightly tested. They should work with:

1. Z80PACK emulation (*.dsk files)
2. The High Nibbles IMSAI 8080, VT100, DAZZLER and Tek4010 emulators
3. The High Nibbles FDC-Server `unpacked` format
4. The RTR CP/M Emulation system (CPMEMU)
5. Physical hardware / real S-100 systems that meet the requirements

The disk images typically have a `README.TXT` file with instructions etc.
There may also be a `TECH.TXT` with additional details.
Disks that expect an ANSI/VT100 terminal will also contain `SEDIT.CNF`.
This is a TERATERM configuration file that allows [TERATERM](https://teratermproject.github.io/index-en.html) to fully work with the software.

> **Note:** Files marked with `@` haven't been published yet.

## File Index

| File | Description |
|------|-------------|
| [TETRIS.DSK](https://github.com/nbreeden2/Z80PACK-Disk-Images/blob/main/TETRIS.DSK) | TETRIS written for the DAZZLER video card. Requires a DAZZLER, DAZZLER II or emulated video card. [source](https://github.com/nbreeden2/dazzler_tetris) [unpacked](https://github.com/nbreeden2/Z80PACK-Disk-Images/blob/main/tetris.unpacked.zip)|
| [SEDIT.DSK](https://github.com/nbreeden2/Z80PACK-Disk-Images/blob/main/SEDIT.DSK) | Full screen text editor (VT100/VT52/ANSI/other terminals) [source](https://github.com/nbreeden2/cpm-screen-editor) [unpacked](https://github.com/nbreeden2/Z80PACK-Disk-Images/blob/main/sedit.unpacked.zip)|
| [HEDIT.DSK](https://github.com/nbreeden2/Z80PACK-Disk-Images/blob/main/HEDIT.DSK) | Full screen HEX editor (VT100/VT52/ANSI/other terminals) [source](https://github.com/nbreeden2/cpm-hex-editor)   [unpacked](https://github.com/nbreeden2/Z80PACK-Disk-Images/blob/main/hedit.unpacked.zip)|
| [SCOPY.DSK](https://github.com/nbreeden2/Z80PACK-Disk-Images/blob/main/SCOPY.DSK) | Smart file copier, understands user spaces `A3: B15:` and has `<TAB>` expansion for filenames  [source](https://github.com/nbreeden2/cpm-smart-copy)     [unpacked](https://github.com/nbreeden2/Z80PACK-Disk-Images/blob/main/scopy.unpacked.zip)|
| `@SUTILS.DSK` | A collection of utilities for CP/M |
| `@MUSIC.DSK` | A music player and music files. Requires the Cromemco D+7AIO card (or emulated card). |
| [SAM.DSK](https://github.com/nbreeden2/Z80PACK-Disk-Images/blob/main/SAM.DSK) |  SAM - Software Automatic Mouth - A port of the SAY program from the 6502 to the Z80. Requires the Cromemco D+7AIO card (or emulated card). [unpacked](https://github.com/nbreeden2/Z80PACK-Disk-Images/blob/main/sam.unpacked.zip)|
| `@HD_PLOT_1.DSK` | Collection of Tektronix 4010 terminal images and the player program |
| `@HD_PLOT_2.DSK` | Collection of Tektronix 4010 terminal images and the player program |
| `@HD_PLOT_3.DSK` | Collection of Tektronix 4010 terminal images and the player program |
| [MANDEL.DSK](https://github.com/nbreeden2/Z80PACK-Disk-Images/blob/main/MANDEL.DSK) | Mandelbrot program for the Tektronix 4010 terminal. Requires a Tektronix 4010 terminal (or emulated 4010).  [unpacked](https://github.com/nbreeden2/Z80PACK-Disk-Images/blob/main/mandel.unpacked.zip) |
| `@BLOX.DSK` | Graphics demo for the DAZZLER. |
| `@LIFE.DSK` | Conways LIFE demo for the DAZZLER. |
| `@GDEMO.DSK` | A recreation of the Cromemco library for the DAZZLER plus demo programs ported to CPM. |
