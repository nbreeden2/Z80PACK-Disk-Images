# Z80PACK AND FDC-Server Compatible Disk Images

This repository contains Z80PACK compatible `.dsk` disk images & High Nibble compatible `.unpacked` ZIPs containing new software that isn't included in Z80PACK. 

This repository is meant as a distribution point for these disk images. Source code for the programs on these disks may be found in other repositories if I have published that source.

## Compatibility

These disks have been lightly tested. They should work with:

1. Z80PACK emulation (*.dsk files)
2. The [High Nibbles](https://thehighnibble.com/imsai8080/) IMSAI 8080, VT100, DAZZLER and Tek4010 emulators
3. The [High Nibbles](https://thehighnibble.com/imsai8080/) FDC-Server `unpacked` format
4. The RTR CP/M Emulation system (CPMEMU)
5. Physical hardware / real S-100 systems that meet the requirements and are properly configured

The disk images typically have a `USER` file with instructions etc.
There may also be a `TECH` file with additional details, build instructions etc. Any disk image that can be assembled/compiled on that image will have the proper assembler/compiler already on the disk.
Disks that expect an ANSI/VT100 terminal will also contain `SEDIT.CNF`.
This is a TERATERM configuration file that allows [TERATERM](https://teratermproject.github.io/index-en.html) to fully work with the software.

> **Note:** Files marked with `@` haven't been published yet.

## File Index

| File | Description |
|------|-------------|
| [TETRIS.DSK](https://github.com/nbreeden2/Z80PACK-Disk-Images/blob/main/TETRIS.DSK) | TETRIS written for the DAZZLER video card. Requires a DAZZLER, DAZZLER II or emulated video card. [source](https://github.com/nbreeden2/dazzler_tetris) [unpacked](https://github.com/nbreeden2/Z80PACK-Disk-Images/blob/main/tetris.unpacked.zip)|
| [SEDIT.DSK](https://github.com/nbreeden2/Z80PACK-Disk-Images/blob/main/SEDIT.DSK) | Full screen text editor (VT100/VT52/ANSI/other terminals) [source](https://github.com/nbreeden2/Z80PACK-Disk-Images/blob/main/hd-sutil.unpacked.zip) [unpacked](https://github.com/nbreeden2/Z80PACK-Disk-Images/blob/main/sedit.unpacked.zip)|
| [HEDIT.DSK](https://github.com/nbreeden2/Z80PACK-Disk-Images/blob/main/HEDIT.DSK) | Full screen HEX editor (VT100/VT52/ANSI/other terminals) [source](https://github.com/nbreeden2/Z80PACK-Disk-Images/blob/main/hd-sutil.unpacked.zip)   [unpacked](https://github.com/nbreeden2/Z80PACK-Disk-Images/blob/main/hedit.unpacked.zip)|
| [SCOPY.DSK](https://github.com/nbreeden2/Z80PACK-Disk-Images/blob/main/SCOPY.DSK) | Smart file copier, understands user spaces `A3: B15:` and has `<TAB>` expansion for filenames  [source](https://github.com/nbreeden2/Z80PACK-Disk-Images/blob/main/hd-sutil.unpacked.zip)  [unpacked](https://github.com/nbreeden2/Z80PACK-Disk-Images/blob/main/scopy.unpacked.zip)|
| [SUTIL.DSK](https://github.com/nbreeden2/Z80PACK-Disk-Images/blob/main/SUTIL.DSK) | Smart utilities and editors for CPM. Source image has full build environemnt [source](https://github.com/nbreeden2/Z80PACK-Disk-Images/blob/main/hd-sutil.unpacked.zip)  [unpacked](https://github.com/nbreeden2/Z80PACK-Disk-Images/blob/main/sutil.unpacked.zip)|
| [PLAYZ80.DSK](https://github.com/nbreeden2/Z80PACK-Disk-Images/blob/main/PLAYZ80.DSK)  | A music player and music files. Requires A Z80 and a Cromemco D+7AIO card (or emulated card).  [unpacked](https://github.com/nbreeden2/Z80PACK-Disk-Images/blob/main/playZ80.unpacked.zip) |
| [playZ80.music.zip](https://github.com/nbreeden2/Z80PACK-Disk-Images/blob/main/playZ80.music.DSK)  | A collection of BACH for the PLAYZ80 music player. |
| [SAM.DSK](https://github.com/nbreeden2/Z80PACK-Disk-Images/blob/main/SAM.DSK) |  SAM - Software Automatic Mouth - A port of the SAY program from the 6502 to the Z80. Requires the Cromemco D+7AIO card (or emulated card). [unpacked](https://github.com/nbreeden2/Z80PACK-Disk-Images/blob/main/sam.unpacked.zip)|
| `@HD_PLOT_1.DSK` | Collection of Tektronix 4010 terminal images and the player program |
| `@HD_PLOT_2.DSK` | Collection of Tektronix 4010 terminal images and the player program |
| `@HD_PLOT_3.DSK` | Collection of Tektronix 4010 terminal images and the player program |
| [MANDEL.DSK](https://github.com/nbreeden2/Z80PACK-Disk-Images/blob/main/MANDEL.DSK) | Mandelbrot program for the Tektronix 4010 terminal. Requires a Tektronix 4010 terminal (or emulated 4010).  [unpacked](https://github.com/nbreeden2/Z80PACK-Disk-Images/blob/main/mandel.unpacked.zip) |
| `@BLOX.DSK` | Graphics demo for the DAZZLER. |
| `@LIFE.DSK` | Conways LIFE demo for the DAZZLER. |
| `@GDEMO.DSK` | A recreation of the Cromemco library for the DAZZLER plus demo programs ported to CPM. |
