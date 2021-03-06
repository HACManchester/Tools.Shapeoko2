# Device Overview

We currently have on loan a shapeoko 2 from Simon <br>
It appears to be using an Arduino uno with a gShield, with the grbl firmware and Nema 17's


## Firmware Overview

Currently the Shapeoko2 uses an Arduino Uno with a G-Shield connected to 4 Nema 17 Stepper motors

  * <https://www.inventables.com/technologies/gshield>
  * <https://github.com/grbl/grbl>
  * <http://www.shapeoko.com/wiki/index.php/Grbl_Configuration>
  * <https://github.com/grbl/grbl/wiki/Configuring-Grbl-v0.8#grbls-xval-settings-and-what-they-mean>

The original version of the firmware was 0.8c which ran at a baud of **9600** <br>
This has now been updated to version 0.9j which now uses a baud of **115200**


## Power Supplies

There are 2 PSU's in use

  * The first one (the black power brick) powers the fan and Arduino / shield / stepper motors
  * The second one (the silver one in the enclosure) powers the spindle and can be turned on / off using the switch on the back of the box.


## Spindle

The spindle is a spare one Bob had lying around

  * <http://www.ebay.co.uk/itm/300W-DC-12-48-CNC-Carving-Milling-Spindle-Motor-24V-36V-For-Engraving-Carving-/131775304417?hash=item1eae6b92e1:g:BtQAAOSwSzdXB3vC>
  * 12V - 48V / 300W


### Spindle PSU

This was originally a PSU used for the laser cutter but which is spare

  * <https://endless-sphere.com/forums/viewtopic.php?f=2&t=55658>
  * <https://endless-sphere.com/w/index.php/S-350-36>

## Calibration

So far everything seems to be in check.
I've set the stepper current so that the stepper motors don't get too hot, also the pulley on the X Axis should now be set correctly

  * Currently there are no end stops, ideally we want an inductive sensor on Z-Min for milling PCB's
  * is there any additional steps we could pull from here: <http://www.shapeoko.com/wiki/index.php/Calibration_and_Squaring_the_Machine>

## Tool Heads

For the collets we have ER11 collets located within the cream box next to the lathe <br>
For milling bits, we have some next to the proxon mill we can use
