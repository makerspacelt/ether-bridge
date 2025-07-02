<a href="LICENSE"><img src="https://badgen.net/badge/Open Source/Hardware" /></a>
<a href="https://www.kicad.org/"><img src="https://badgen.net/badge/Made with/KiCAD" /></a>
---
![PCB 3d main](gen/img_pcb_3d_main.png)


Ether-bridge

NOTE: This is only a prototype now, so things might not work, and everything might change 

This hardware is meant as an Ethernet upgrade for devices that only support
I2C/UART/RS485/CAN communications. This should be used with a device-specific
firmware that exposes SCPI commands for all functions of a particular device.


Basic target features:

* Ethernet connection
* PoE .af 12w
* CAN
* RS-485
* i2c/UART
* 1x GPIO
* LXI/SCPI support via raw TCP
* Compatibility with ESPHome and Home Assistant



Dev NOTE: before commit, run `./kibot.sh` to regenerate documentation, bom, gerbers and other assets.

* [schematics.pdf](gen/schematics.pdf)
* [pcb.pdf with dimensions](gen/pcb.pdf)
* [ibom.html](gen/single/ibom.html)


<img src="gen/img_pcb_2d_front_bare.jpg" width="19%" align="left" />
<img src="gen/img_pcb_2d_back_bare.jpg" width="19%" align="left" />
<img src="gen/img_pcb_3d_front.png" width="19%" align="left" />
<img src="gen/img_pcb_3d_back.png" width="19%" align="left" />


---




