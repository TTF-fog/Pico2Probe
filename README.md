# a RP2354-based debugprobe

An updated version of the original [debugprobe](https://www.raspberrypi.com/documentation/microcontrollers/debug-probe.html) with the following changes - 
- Based on the RP2354A
- USB-C (i just really hate micro-b)
- a configurable addressable RGB led

# Why did i make this?

1. Does one need to justify the act of creation? (or, in other words, why not?) (please do not take that out of context)
2. I had no way of debugging except plain UART (which is annoying), so i wanted something that would let me use an actual debugger
3. Wanted to make something using the RP2354A

# Setting Up
1. Ground the BOOT solder pad
2. Build the firmware with ```-DPICO_BOARD=pico2```
3. Drag the resultant .uf2 file into the storage device that appears

# Usage
along the same lines as the official documentation

# (Sub)Links
- [BOM](PCB/production_files/BOM.csv)
- [Design Files](PCB/Design%20Files/)
- [Schematic PDF](PCB/Design%20Files/schem.pdf/Pico2Probe.pdf)
- [Zine](zine.pdf)
- [Gerbers](PCB/production_files/GERBER-Pico2Probe.zip)

# Images
![PCB 3d view](images/tst.png)
![schematic](images/image.png)
![Routed PCB](images/image-1.png)
![Zine](images/zine.png)
