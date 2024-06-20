# Tera2321
Info on Tera2321 SoC (dell Wyse 5030 and other) 

## What is it ?
It's a zero client using the PCoIP protocol mostly for enterprises, used to connect people to a virtual environment and 
used just a gateway with minimal capabilities.

Front

![Front](/5030_Front.jpg)

Back

![Back](/5030_Back.jpg)

## Specs:
| FEATURES    | DESCRIPTION |
| --------- | ------- |
|**Processor**| Teradici TERA2321 PCoIP (MIPS 4KXX)        |
|           |Core logic speed—600 MHz         |
|**Memory DRAM controller**| * Memory banks—One, 32–bit|
|           |* DRAM technology—DDR3 SD RAM, 1.5 V  |
|           |* Configuration—Single, Solder down, Cannot be installed by an user.         |
|           |* Capacity—512 MB        |
|**Power**           |12V 2.5Amp         |
|**I/O peripheral support**|DisplayPort 1.1, DVI-I port, 1 VGA adapter |
|           | four external USB 2.0 ports (2 front, and 2 back)|
|**Networking**           |10/100/1000 Base-T Gigabit Ethernet          |
|           |Optional Fiber SFP Module Ready—Mutually exclusive with RJ45|
|**Flash**           |256MBIT SPI 16SOP|
|**Audio**           |Composite Audio 1/8-inch mini jack         |
|           |Output: 1/8-inch mini jack        |

## Useful ?
Possibly, with dual screen outputs, audio,USBs and 1GBit ethernet.

## OS/SOC
There is almost no information regrading this SOC (Tera2321) the only clue that it's a MIPS architecture was from the bootlog

And it runs [ThreadX](https://github.com/eclipse-threadx/threadx) (RTOS) [Wiki](https://en.wikipedia.org/wiki/ThreadX)

So I have not idea what to do with that.

## Pictures ot the PCB

## Terminal pads
Baud rate 57600
