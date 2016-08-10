# Todo

## Milling Bits

At the moment we only have a single ER11 collet of 3mm, and a couple of 3mm mill bits. <br>
Ideally we could look into the following.

  * Set of ER11 Collets of different sizes so we can use different size mill bits and drill bits
    <https://www.amazon.co.uk/ZFE-Precision-Spring-Collet-13Pcs/dp/B00QRH5D2K>
  * Some 6mm milling bits (using 3mm ones to clear an area can take a long time)
    <https://www.amazon.co.uk/gp/product/B00XTWOT9O>


## End Stops

Currently we don't have a way of homing the machine (except for manualy)

  * Some proximity sensors for end stops
    Ideally they should be Normally Closed (so that they activate on cable failure)
    DC 6-36V NPN NC Tubular Inductive Proximity Sensor Switch 4mm Detective Distance
    <https://www.amazon.co.uk/gp/product/B007Q7EC2M>
  * We also need to design a PCB with some opto-couplers to interface the proximity sensors to the controller board.
  * Some brackets to hold the proximity sensors need to be designed then ether milled or printed, we can attach with some drop in T Nuts and screws


## E-Stop Button

One idea might be an E-Stop button, although at the moment one way to stop the mill is just to yank out the USB plug while its running.
