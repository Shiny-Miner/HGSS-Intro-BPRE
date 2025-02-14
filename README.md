# HGSS style gamefreak intro!
Credits : Kaiser, Compumax and the people who made this template (Touched, etc)
## Compiling the code
- Place a rom named BPRE.gba
- And if you have armips,devkitarm in path, go in powershell and run command ``make``
- A folder named build should appear which now has your rom called rom.gba
### Note:
To place it at a custom offset, open main.s , at its line 13 , ``.org 0x08800000`` change this to your custom offset. Remember, change the 08 to 09 if the offset is at 1000000.
It means 0x9800000 represents offsets 0x1800000.

#### Showcase



https://github.com/user-attachments/assets/ebeb251d-8584-429a-993d-227fa99099e5

