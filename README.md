# Raven - Custom 42 key split ergonomic keyboard 
## **Documentation - IMPORTANT PLEASE READ ALL**
This is the second keyboard I've designed, the Raven (or Raven 42) named after the bird for its wing-like design and deep purple color, much like my original prototype. I desgined the case and plate in AutoDesk Fusion, and the PCB in KiCad.

Raven is designed to use a PCB, but can be handwired if you desire. The case and plate have been designed to be easily 3d printed. This keyboard does not utilize standoffs or screws, but is desinged to simply sit in the case, using rubber bumpers to prevent the pcb from moving while typing in or out of the case.

### Parts Needed
- 42 MX style switches
- 42 1N4148 diodes
- 42 1u keycaps
- 2 nice!nano v2 or suitable clone
- 2 110 mAh 3.7v lithium ion battery
- 8mm x 2mm rubber bumper (for case feet / pcb)
- 11mm x 5 mm rubber bumper (for case feet)

### 3D Printing 
When 3D printing the case and plate, I would recommend 100% infill or as close to 100% as possible to ensure the best acoustics. Lower infill = a more hollow sound.

### Optional Case Silicon Pour
A great way to improve acoustics of this or any board is a silicon pour. With some simple 2 part silicone, that you can get from somewhere like Amazon, you can pour a thin layer of silicone at the bottom of the case. The holes in the bottom of the care are designed to hold the silicone layer better when fully cured.

### PCB
The gerber file provided can be uploaded to a website like JLCPCB or PCBWay to be manufactured for you. The total cost of the pcb should be around 20 dollars. (I have found that JLC is usually cheaper than PCBWay but you can check both)

Note: When solderinig on the microcontroller, the top pins on the right and left will not be attached to the pcb to give space to attach the battery.

### Firmware
I have provided my files for my ZMK config that you can use to change the keymap and recompile if you wish. I press B with my right hand, so you will likely need to change it. If you do not know how to edit a keymap or compile firmware, you can watch this youtube video, https://www.youtube.com/watch?v=O_urj-rF3bQ&t=2s, or read the ZMK documentation.
