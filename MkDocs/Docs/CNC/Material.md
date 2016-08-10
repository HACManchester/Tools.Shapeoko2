# Milling Material

## Clamping Holes

The CNC has a spoiler board located on its base. Generally, you try to avoid milling into the spoiler but it can be replaced.
It has several inserts in the bottom for securing additional material on top using a series of M6 bolts

Some of the holes should line up with the holes on the small drill press vice

<a href="../../images/CNC/Material/InsertHoles.jpg"><img src="../../images/CNC/Material/InsertHoles.jpg" height="50%" width="50%" ></a> <br>

<a href="../../images/CNC/Material/FittedBolts.jpg"><img src="../../images/CNC/Material/FittedBolts.jpg" height="50%" width="50%" ></a> <br>


### Position of Clamping Holes

In order to drill the positioning holes for the material being milled (that sits on top of the spoiler board)
First move the CNC head all the way to the bottom left, then use the Jog within Chillipepr to get it into the right offset.

From the Bottom Left Corner

  * 30mm Upwards, 0mm Right
  * 30mm Upwards, 300mm Right
  * 290mm Upwards, 0mm Right
  * 290mm Upwards, 300mm Right

Drill mount holes

  * 30mm Upwards, 0mm Right
  * 30mm Upwards, 110mm Right
  * 140mm Upwards, 0mm Right

## MDF

So far I've used MDF 12mm thick cut into sections using the table saw.
However, it's advisable to limit the depth of a pass to about 2mm or so at one time, to avoid overloading the stepper motors on the device (milling too much out at one time)

## Metal

Since the Shapeoko 2 only has Nema 17 motors, I've found that it manages mdf okay but I'm not sure if it can manage metal such as aluminium.
With metal you have to mill at the right speed, too slow and the metal sticks to the mill bit

For this you'll need to use a speeds and feeds calculator.

  * <http://www.cnccookbook.com/GWCalcFeedsSpeeds.htm>

