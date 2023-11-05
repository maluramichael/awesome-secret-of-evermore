# RAMsetta Stone Secret of Evermore

Original by Phonymike - https://www.romhacking.net/documents/831/

This is a new style of document to show the conversion of SRAM locations into WRAM locations. In other words, saveram and savestate locations. It is quicker and easier to search a savestate’s data, than to trek back to find a save point to make a saveram file.

For instance, you could make one savestate before a boss fight, and then a second savestate immediately after. If you compare these specific regions of the savestate, you’ll find only a few bytes have changed. These bytes would indicate the boss is defeated. Then you could edit the sram file, and battle the boss again.

You can also use a debugging emulator like bsnes-plus and set a breakpoint for when these WRAM regions are modified. Helping to map out the entire saveram format.

# Files

* [RAMsetta Stone SoE.html](RAMsetta%20Stone%20SoE.html)