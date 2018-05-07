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
* 330 ohm resistor + 0805 led smd. (not required)
* 5x switch-omron (B3F-31XX)
* 3x separators for Raspberry Pi (it not required but recommended since the gpio connector already keep the pcb from bending). 

* A Raspberry Pi 3 :)

* Plug the board on top of the RPI3. Then follow the instruction that Steve comment on his article.

# Images of the PCB

<img src='https://github.com/arananet/pi1541pcb/blob/master/img/1.png'/>
<img src='https://github.com/arananet/pi1541pcb/blob/master/img/2.png'/>

# Updates

07/05/2018 - Initial release.


