# Building the unit
Some tools and parts are required for this project:
* Soldering iron, solder, heatshrink or electrical tape
* 3d printer or printed parts
* Shock unit (CaiXianlin). See the [Openshock docs](https://openshock.org/hardware/shockers/caixianlin/) for buying guides
* Flexible wire with good insulation, I reccomend 22 gauge or better, and silicone jacketing
* 3.5mm Panel Mount Jack. I use [these](https://www.amazon.com/dp/B0C9MDDLNG?psc=1) but there are lots of identical parts
* Phillips head screwdriver
Note: Pishock units should be compatible with this mod, but the PCB landing pads are different. If you're feeling adventurous, go for it. I don't have one to experiement with

![Shock Unit](Images/ShockerFront.webp)

## Print the Shock Adapter
![Printed Shock Adapter](Images/CoverRender.PNG)
The housing should be printed front down (The STL is already oriented correctly) with 0.2 layer height out of PLA or better, I use ASA. Supports are required for the flats around the screw holes, I have had good luck with PrusaSlicer's organic supports.

## Remove the front of the shocker
![Cover Removed](Images/CoverOff.jpg)
Remove the four phillips head screws from the front of the unit. You should be able to lift the PCB out.

## Solder the jack
![Jack with all 3 pins](Images/Jack3Pins.jpg)
![Spare pin removed](Images/Jack2Pins.jpg)
Locate the center (Longest pin) on the base of the jack and cut it off flush with the jack. This pin is connected to the brass ring at the top of the jack, and could provide an unexpected path for the shock if attached. 
![Jack with wires soldered](Images/JackSoldered.jpg)
![Heatshrink applied](Images/JackShrunk.jpg)
Solder a (roughly) 1.5 inch length of wire to each remaining terminal, and seal with heatshrink or electrical tape.

## Install the jack
![Nut in housing](Images/NutInserted.jpg)
![Jack in housing](Images/JackInstalled.jpg)
Drop the hex nut provided with the jack into the slot on the printed front plate, and then feed the wires and jack into it from the top. Tighten it into place. Hand tight is fine, or pliers to snug it down. 

## Solder to the PCB
![Soldered to PCB](Images/Soldered.jpg)
Gently rock and pull at the battery to lift it from the adhesive tape. Be careful of the power wires, and don't use a tool for this step. You don't want to puncture the battery or short out the electronics. The two paired solder pads that output to the prongs should be easy to access. Solder one wire to each pair of pads, taking care to get a good joint, and not overheating it enough to drop the metal contact off the other side. 

## Reassemble the shocker
![Partly reassembled](Images/Repacked.jpg)
Carefully press the battery back into place, and close the housing with the new front plate in place. The jack should be on the same side as the daughterboard with the LEDs, so the center LED can shine through the small hole next to the jack. The two metal prongs that extend from the PCB must be pressed against the two rubber blocks inside the back of the shell. Be careful not to pinch or damage the wires, or the battery. Reinstall the four screws. 

## Using the unit 
![Finished](Images/Finished.jpg)
Congratulations! The shocker should work normally (prongs) or with your choice of TENS electrodes! When using electrodes, you MUST slide the [Backing Plate](Docs/BackingOptions.md) over the prongs. Leaving them exposed will provide unexpected and dangerous current paths. Keep the pads no more than an inch apart, and use caution with placement. Larger pads will dull the sensation, I have had the best luck with pads just about an inch in area. You can trim most pads with household scissors to adjust the sensation. 
