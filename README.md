# Fluke 9010a protection module

This is a replacement Fluke 9010a protection module. It is based on the
schematics in the Z80 pod manual, and some information from the KLOV
forums.

I drew this so I could have them fabricated and save me the trouble of
soldering the surface mount components myself. This directory includes the
BOM files required to get the boards assembled by jlcpcb.com.

While the schematic and layout includes pull-up resistors, I later learned
that the original Z80 and 6502 pods don't use pull-ups. I also didn't
realize at the time that I wouldn't be able to get parts mounted on both
sides during fabrication, so I removed the three pull-ups that were
installed by the fab on the top side (R21, R26, and R27), and I soldered
the single missing series resistor to the bottom (R4).

Ideally, if I get these fabricated again, I would either move all parts to
a single side. Or, alternatively, since the pull-ups aren't used on many
pods, I'd put all the pull-ups on the bottom side.

Change history:  
1.0 - Initial version  

To Do:  
- Move series resistor to top side, move all pull-ups to bottom.  
- Improve routing layout to look nice.  

Marc Deslauriers
2022-06-09
