# PicoCalc-Quick-Guide

<H1>Bootloaders</H1>


<h2>From the Factory</h2>
The bootloader that came with the PicoCalc (as of December 2025) is

PicoCalc_Bootloader_v0.5.uf2 <BR>

This bootloader will only load BIN files <BR>

Available from:
https://github.com/clockworkpi/PicoCalc/blob/master/Bin/PicoCalc%20SD/firmware/PicoCalc_Bootloader_v0.5.uf2 <BR>

<h2> U2F Loader </h2>
This Bootloader will load U2F Files, it can be use to daiy-chain the BIN loader above. <BR>

Available from:
https://github.com/pelrun/uf2loader<BR>

Installation: <BR>
The Bootloader https://github.com/pelrun/uf2loader/releases/download/v2.3/bootloader_pico.uf2 is flashed to the Pico via USB <BR>
The https://github.com/pelrun/uf2loader/releases/download/v2.3/BOOT2040.uf2 file needs to live in SD_ROOT

<h1>Emulation</h1>

<h2>Mac Emulation</h2>
Available from:
https://github.com/benob/picocalc-umac <BR>
A System 7 Disk Image is  available from the above <BR>
Place the disk image umac0.img in SD_ROOT <BR>
A second disk image can be placed as umac1.img <BR>
A Mac ROM Image is  available from the above <BR>
Place the ROM image in SD_ROOT/roms <BR>


<h2>CP/M Emulation</h2>

Available from:
https://github.com/guidol70/RunCPM_RPi_Pico <BR>

Disk Images
https://github.com/guidol70/RunCPM

Installation: <BR>
Place U2F file in SD_ROOT/pico1-apps <BR>
Place disk image files in SD_ROOT/[DISK_LETTER]/[USER_NUMBER] <BR>
Operating System files should be in <SD_ROOT>/A/0 <BR>

<h2>NES</h2>
Available from: https://github.com/clockworkpi/PicoCalc/tree/master/Code/NES <BR>
This page points to: https://github.com/clockworkpi/PicoCalc/blob/master/Bin/PicoCalc%20SD/firmware/PicoCalc_NES_v1.0.uf2 <BR>

<h2>GameBoy</h2>

Available from:
https://github.com/TheKiwil/PocketPico <BR>



