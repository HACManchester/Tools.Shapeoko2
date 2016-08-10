# Hacman - Shapeoko 2

This is a series of Docs for the use of the Shapeoko 2 currently within the Hackspace. <br>
This is currently on loan to us from Simon.
(Many thanks to Simon for the loan of the shapeoko, and Bob for the spindle PSU)

<a href="../../images/Shapeoko2.jpg"><img src="../../images/Shapeoko2.jpg" height="100%" width="100%" ></a> <br>


## Software

So far we've successfully used Chillipepr / Grbl to handle the milling, and Solidworks / HsmWorks to design the part and generate the G-Code

Todo the following software needs to be looked into

  * **FlatCAM** - Can be used to calculate G-Code for PCB Etching, although we need a Z-Min Proximity sensor to measure the level of the copper board.
  * **Aspire** - Can be used for milling graphical / artwork type patterns such as lettering or meshes.
  * **JSCut** - Open source CAM Software for generating G-Code for CNC Mills, limited to 2.5 CAM / 2 dimensional profiles similar to a laser cutter
  * **PyCAM** - Can handle STL Files and generate 3D Cam profiles, but seems not to be updated often
  * <http://wiki.linuxcnc.org/cgi-bin/wiki.pl?Cam>

The best free option may be Autodesk Fusion 360 CAM / Cad
