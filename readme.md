# wlpad
wlpad is a simple wireless numpad, designed around a moko MK08A module, and fitting both Hi-Tek 725 as well as MX switches. While the PCB is the same for both switch types, the plate is different.

### Features
* Runs ZMK firmware on a Moko MK08A module - firmware can be found in my [zmk-config](https://github.com/ebastler/zmk-config) repo
* Hi-Tek 725 and Cherry MX compatibility
* Molex Picoblade connectors for battery and plate connection
* Charge indicator LED, some WS2812_2020 and a small 128x32px OLED can be placed on the plate

This PCB was painly made as a proof-of-concept for my Hi-Tek 725 footprints, and to try the MK08A module and MAX17048 fuel gauge chip on an actual PCB. The latter already found its way into my [Osprey](https://github.com/ebastler/osprey). 

rc1.0 had some issues (vertical 2u keys rotated by 180°, LEDs on plate connected to GND instead of VDD), which were addressed by the current rc1.1 version. However, the rc1.1 version has not been (and probably will not be) prototyped - use at your own risk. Please report back if you successfully tested such a PCB.

### Renders (rc1.1)
![topside](wlpad\fab\wlpad-.top.png) ![botside](wlpad\fab\wlpad-.bottom.png)

### Pixtures (rc1.0)
![botside](img\wlpad_top.jpg)
