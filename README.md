This is a Realtime Clock for Amiga 500 and Amiga 1000 Computers, wich\
will fit under the 68k CPU or any turboboard for 68k sockets.\
\
For use in Amiga1000 and Kick1.3 you need a patched setclock binary.\
For use in Amiga1000 and Kick >= 2.0 you need a patched battclock_resource modul.\
All these needed files are in (A1kSimpleClock.lha)
\
\
1 * MSM62X42BGS (Clockchip),\
alternative you can use an Epson RTC-72423A instead (pincompatible and in Digikey BOM)\
\
1 * MS920SE (3V Lithium Accu Cell)\
\
These both are available at Mouser or Aliexpress, the Epson Chip is available at Digikey,too.\
\
JP1\
ON = Amiga1000\
OFF = Amiga500/2000\
\
IMPORTEND,\
IC3 needs to be an AC/ACT Type, slower types like HC or HCT won't work!\
\
**Diode orientation**\
\
D1 = Kathode on the right -->|--\
D2 = Kathode on the left --|<--\
D3 = Kathode down\
ah, btw. every SOD123 Schottky Diode with uf<=0.3V will work\
\
**DISCLAIMER!!!!**\
**THIS IS A HOBBYIST PROJECT! I'M NOT RESPONSIBLE IF IT DOESN'T WORK OR DESTROYS YOUR VALUABLE DATA OR HARDWARE!**\
\
https://mytube.madzel.de/videos/watch/4dbfa021-77f8-47c4-a0fa-2a3ab73ecad1
