# Custom ZMK build for 48Key keyboard
![IMG_20240806_154132166](https://github.com/user-attachments/assets/330eb5f4-8b73-4350-888e-b4442a6cc6bc)


Find 3D printer files for this board at this (repo)[https://github.com/Glitch860/48Key/]

Parts list used for this build: 
- 18 gauge copper wire
- 28 AWG Flexible Silicone Wire
- Heat shrink
- 48 1N4148 diodes
- 48 MX style switches
- NiceNanoV2 controller
- 1 Battery helper PCB from [https://www.boardsource.xyz/]
- 5 2.5mm hex screws and nuts
- 100 mAh battery

Build Guide:

1. Start by printing the case. I did mine standing up. I used a .04mm Nozzle printing at a .2mm layer height with tree supports. The base can be printed flat with supports on the bed only if the printer bed is big enough.

2. Pop in the 48 MX switches

3. Pre coil the 48 Diodes. I did this using the end of a small screwdriver.

4. Solder all the diodes to one pin of the switch. Diodes will get wired to the row. The other leg will be soldered to the columns.

5. Using the 18 gauge copper wire solder the rows and columns. Be sure to use heat shrink on any points where the wires will touch. If they touch it will cause a short and the keyboard won't work.

6. (optional) Solder the battery helper onto the NiceNano controller
   
7. Using the 28 AWG silicone wire connect the columns and rows to the pins on the NiceNano controller.

8. Connect the battery to the battery helper (if used), otherwise connect it directly to the controller.

9. Using a soldering iron heat sink the hex nuts into the case.

10. Flash the NiceNano controller with the compile firmware. Be sure to test the keyboard

11. Add rubber feet to the base and screw the base to the case.

12. Add your keycaps and enjoy typing!


# License

<img style="height:22px!important;margin-left:3px;vertical-align:text-bottom;" src="https://mirrors.creativecommons.org/presskit/icons/cc.svg?ref=chooser-v1"><img style="height:22px!important;margin-left:3px;vertical-align:text-bottom;" src="https://mirrors.creativecommons.org/presskit/icons/by.svg?ref=chooser-v1"><img style="height:22px!important;margin-left:3px;vertical-align:text-bottom;" src="https://mirrors.creativecommons.org/presskit/icons/nc.svg?ref=chooser-v1"><img style="height:22px!important;margin-left:3px;vertical-align:text-bottom;" src="https://mirrors.creativecommons.org/presskit/icons/sa.svg?ref=chooser-v1"></a></p>

You are free to:

Share — copy and redistribute the material in any medium or format

Adapt — remix, transform, and build upon the material

The licensor cannot revoke these freedoms as long as you follow the license terms.
Under the following terms:

Attribution — You must give appropriate credit, provide a link to the license, and indicate if changes were made. You may do so in any reasonable manner, but not in any way that suggests the licensor endorses you or your use.

NonCommercial — You may not use the material for commercial purposes.

ShareAlike — If you remix, transform, or build upon the material, you must distribute your contributions under the same license as the original.

No additional restrictions — You may not apply legal terms or technological measures that legally restrict others from doing anything the license permits.
