# PI1541pcb

This is a PCB based on the Steve White schematic. You just plug on the top of a RPI 3 and you have a fully working 1541 disk emulator :). You can access to the original article from here https://cbm-pi1541.firebaseapp.com/.

# Note
This is a work in progress, several testing must be made but it should work as is. I take no responsibiltiy for any damage to any equipment that results from the use of this board. USE AT YOUR OWN RISK!

If you like the project, buy me a beer :) info@arananet.net

# Parts required

* This PCB :)
* There is two ways to connect to the C64, one is solder a DIN 6 connector for PCB and use a male 2 male cable or solder 5 cables on the other connector available on the pcb and use only a male connector on the top. 
* Level shifter board for Arduino (https://www.ebay.com/sch/i2c+logic+converter+module)
* Female 2x20 2.54 connector (to plug this pcb on top of the Raspberry Pi 3)
* 2 x 330 ohm resistor + 0805 led smd. (not required) (power and activity led)
* 5x switch-omron (B3F-31XX)
* 128x64 Oled screen (not required).
* 5v Passive buzzer (not required).
* 3x separators for Raspberry Pi (it not required but recommended since the gpio connector already keep the pcb from bending). 

* A Raspberry Pi 3 :)

* Plug the board on top of the RPI3. Then follow the instruction that Steve comment on his article.

# Updates

12/11/2019: Updated license stuff (I usually not do this but I must start it with this).

06/06/2018 - Added support for OLED screen (128x64) and buzzer.

22/05/2018 - Fixed an small issue with GND on buttons. Detected by jgilcas. Also added activity led to show "floppy" reading.

07/05/2018 - Initial release.





# Images of the PCB

<img src='https://github.com/arananet/pi1541pcb/blob/master/img/top.png'/>
<img src='https://github.com/arananet/pi1541pcb/blob/master/img/bottom.png'/>




