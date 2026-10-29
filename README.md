# Missable-Efreet-Fix
Fix for the missable level 7 (or level 17 in Crazy Mode) Efreet Bestiary entry.

In Castlevania: Curse of Darkness, if you missed the single, one-time spawn Efreet at Baljhet Mountains before you landed the killing blow—you might have noticed your Bestiary is stuck with an unfillable `????` entry.

Starting an completed 30+ hour Crazy Mode run over from scratch just because of a single, self-destructing enemy design oversight felt unnecessary, so I used Cheat Engine to track down the Bestiary memory address and created a `.pnach` patch file to fix it.

### Important Notes:
- Backup your save: Always make a backup copy of your memory card save file before applying memory patches, just in case! (Use at your own risk)
- Game version: This patch is specifically formatted for the NTSC-U release. `SLUS-21168`, `CRC: 3A446111`
- Tested on PCSX2 v1.6.0 and v2.6.3

### Video: https://www.youtube.com/watch?v=1rSOJPA9gBU
