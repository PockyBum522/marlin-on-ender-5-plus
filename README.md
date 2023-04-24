# marlin-on-ender-5-plus

This is a setup for an Ender 5 Plus with:

* A stock creality display
* Creality "v2.2" silent board
* Stock BLTouch from Creality
  
The point of this repo is to get Marlin 2.1.2 working with the above setup. Hopefully it helps others who want to do the same.

I have now successfully printed with it on my ender 5 plus. The temps don't display right on the control box, but they're fine when you run it through octoprint. 

There's definitely some polishing needed, but I just wanted to share it because I couldn't find any resources for this online.

Instructions: Flash the stock display with the DGUS Reloaded files, build marlin from the marlin folder in this repo and upload to the control board. If you want to just pull out Configuration.h and configuration_adv.h, that's where most of the changes have been made.  
