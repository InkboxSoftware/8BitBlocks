# 8-Bit Blocks

## Run
Open Commander X16 Emulator and run following BASIC command (assuming all relevant files are placed in folder named 8BB)
```
DOS"CD:/8BB"
LOAD "8BB.PRG"
RUN
```

### Compile Source Code
Using CC65
```
cl65.exe -t cx16 -o 8BB.PRG 8BB.s
```

### Tile Editing
Sprite and other resource tile files can be edited via [X16 Online Tile Editor](https://www.notin.tokyo/X16tiles/)


Ensure that the Two Byte Header checkbox is set to true. All project graphics files are 8bpp. 


List of sprite and tile files:
- BLOCKS
- ITEMS
- MOBS
- CRAFTSCII

Palette file:
- PAL
