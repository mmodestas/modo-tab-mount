---
title: Power Supply PCB
---

[PCB](/docs/images/pic_pcb_1.png)

# PCB & Documentation

The project includes a custom PCB with ESP32-C3 microcontroller for providing 5V to Tablet. It also has ouput for optional LED strip, surrounding sides of the holder plate part - for status indication or nigth light. 

Firmware is build with ESPHome, so smarthome users can utilize other available ports. See Schematics for details.

## Specs
- Power supply module: MeanWell IRM-10-5
- Input: 85-265V AC
- Output: 5V / 2A via flat USB-C cable  
- ESP32-C3 for smart switching and LED control

![PCB](images/pcb-top.jpg)

### Downloads
- [Schematics (PDF)](files/schematics.pdf)  
- [Gerber Files (ZIP)](files/gerbers.zip)
