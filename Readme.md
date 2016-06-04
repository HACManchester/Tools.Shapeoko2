# Readme

## Overview

We currently have on loan a shapeoko 2 from Simon <br>
It appears to be using an arduino uno with a gShield, with the grbl firmware and Nema 17's

## Spindle

The spindle is a spare one Bob had lying around

  * http://www.ebay.co.uk/itm/300W-DC-12-48-CNC-Carving-Milling-Spindle-Motor-24V-36V-For-Engraving-Carving-/131775304417?hash=item1eae6b92e1:g:BtQAAOSwSzdXB3vC
  * 12V - 48V / 300W

### Spindle PSU

This was originally a PSU used for the laser cutter but which is spare

  * https://endless-sphere.com/forums/viewtopic.php?f=2&t=55658
  * https://endless-sphere.com/w/index.php/S-350-36

## TODO

  * I think the voltage / current to the steppers needs adjusting, as I think it's too weak / not enough torque

  * There needs to be a fan / mount for the g-sheild to cool it down (need to do this before upping the stepper current)
  * Need to find a 24V fan from somewhere

  * Sort out a box to put everything in, including the PSU for the spindle / control board / mains socket for kettle lead
  * Look into a 2 core lead for between the spindle and the psu
  * Currently there are no end stops, ideally we want an inductive sensor on Z-Min for milling PCB's

  * We need to try calibrating the machine http://www.shapeoko.com/wiki/index.php/Calibration_and_Squaring_the_Machine
