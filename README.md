# CS207 Final Project
# A fork of the Pocket PiGrrl
Sean Peterson - University of Regina
*Fall 2015 *

# Overview
The goal of this project is to improve upon Adafruit’s Pocket Pigrrl design in various ways. Ultimately the plan is to roughly keep the same dimensions while also adding a Raspberry Pi 2, an audio jack, and improving durability by ensuring that everything fits snuggly. From the software standpoint the project plans on providing a method in which the save states of games can not only be backup up to a cloud service, but that will effectively sync saved games between devices that are linked to the same cloud service.

# Goals
1. The first milestone will be to build the original Pocket PiGrrl design. This will achieve a few things. Firstly, it will provide a good idea of the amount of space there is to work with. Secondly, it will help to understand the logic behind their design

2. The second milestone will be the inclusion of an audio jack. The PiGrrl currently only supports sound through a speaker which is inconvenient when there are other people in the same room as you. Doing this may require wiring a switch, to switch between the speaker and headphones.

3. The third milestone will be to use a different button design. This is because the PiGrrl uses NinjaFlex filament to print their buttons. Unfortunately this is a material not supported by the author’s 3D printer. Instead, the plan will be to take apart an original, or knock off, snes controller and use its buttons instead. This will both eliminate the noise  

4. The fourth deliverability will be to backup save states to a cloud service, and also have the saves sync between different Raspberry Pi’s that may be connected to a single account. 

5. The fifth deliverability will be to use a Raspberry Pi2 instead, while keeping the size roughly the same. This would be a welcome improvement as it would greatly improve the systems emulation capabilities. As well, this may also mean adding an improved power supply to the console. 

<h1>Build Instructions (Currently for goal 1 to goal 3)</h1>

-download CAD files from CAD folder (currently for goal 3), and print (Goal one/original design by AdaFruit found: https://www.thingiverse.com/thing:807591) <br>
-Pocket PiGrrl build instructions can be found here: https://learn.adafruit.com/pocket-pigrrl/overview <br>
(Go to goal 2 section to see how to install audio jack. <br>
-Download latest ISO image from Software folder. Install on SD card for Raspberry Pi (detailed installation instructions <br>
for different operatings systems can be found in the info file inside software directory). <br>
-Button mappings for Adafruit's PiTFT screen can be found here: https://learn.adafruit.com/pocket-pigrrl/software-1 <br>
-See goal 3 for build instruction (WILL MOVE HERE LATER)
# Known Issues/Planned fixes
-(FIXED - SEE GOAL 1) Currently the sound has major interference.. This problem seems to be a known issue as reported on the AdaFruit forums that is either resulting from the AdaFruit's amp, or the pi itself. <https://forums.adafruit.com/viewtopic.php?f=50&t=79200> <br>
-(FIXED IN GOAL 3) There's a gap between the top and bottom of the gameboy case. May need to extend sides and sand it down.<br>
-(FIXED IN GOAL 3) Magnet not doing a good job of keeping the case close, another screw in bottom right corner would work better. <br>

#Materials
Coming soon ...

# Project
Code, and diagrams can be found here: https://github.com/SeanPeterson/SeanBoy

Note: Work in progress, code/diagrams are added as worked on
This is free and unencumbered software released into the public domain.
