# TS1000plus41
A clone of the American version of the ZX-81, the TS1000 (from Timex/Sinclair).

This is the American version of the ZX81+38 (revision 1.10), except that the video output jack has been moved to the location where the TS1000 has its RF output jack, this means that this PCB will fit into the enclosure of a TS1000. And JP4 is bridged as a default so that the computer defaults to generating NTSC (60Hz) video, note that this makes the TS1000 slower as it needs to use more CPU cycles for a 60Hz Video signal, if you have a TV that can display PAL, I suggest scratching the trace on the solderside of JP4 so that 50Hz is restored. You can solder a jumper in JP4 if you want (after scratching though the trace.

The .zip file "Kicad files for TS1000plus41.zip" contains all the necessary Kicad files, so you can create your own version of the TS1000+41. 

the file TS1000plus41.pdf is the schematic, which is nearly identical to the schematic of the ZX81+38 (revision 1.10) 

The .zip file "production files for TZ1000plus41 rev 1.0.zip" contains the gerber and drill files necessary to create A PCB for the TS1000+41. You can silply upload the .zip file to a PCB manufacturer like PCBWay. Its possible someone else has done this and got 5 PCB's, four of which he does not need and wants to re-sell, so it might be an option to try to find such a reseller.

The Bill of materials (BOM) is identical to the BOM of ZX81+38, but for completeness I have uploaded a specific TS1000+41 BOM. called "BOM for TS1000plus41.ods". .ods files are speadsheet files that can be viewed online or you can use the free OpenOffice office set with a wordprocessor, spreadsheet and more. It is open source software that works on Windows Linux and Mac computers.
