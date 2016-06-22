# Connecting

To connect to the device

## Chilipepr

To setup serial port json server

  * Go to http://chilipeppr.com/grbl within a browser (ideally chrome)
  * In the bottom right hand corner there should be a link to the serial port json server
  * Download this as a zip / extract
  * Attach the Arduino Uno with the G-Shield to your PC via USB
  * Make sure External power to the board for the motors is switched on
  * Run the serial-port-json-server.exe

At this point the serial-port-json-server should show a black console window with the serial ports its detected listed

To Connect to the serial port server from chillipepr

  * Within Chilipepr connect to localhost (bottom right corner)
  * Within the listed devices there should be one visible, change the speed to **115200** and the type to **grbl**
  * Click the Tick box next to the device to connect

Next to just try jogging the device (moving small increments) using the arrows at the top right. <br>
Select the amount of mm to move the device, and click left / right / up / down etc in the different axis to test

To run g-code generated from CAM Software you need to drag the file in over the top of the browser window

## Putty

Putty should only be used 

  * Download and install Putty from http://www.chiark.greenend.org.uk/~sgtatham/putty/download.html

  * Open putty and connect to the grbl / arduino Uno's COM Port
  * Speed: 115200
  * Databits: 8
  * StopBits: 1
  * Parity / Flow Control: None
  * http://www.shapeoko.com/wiki/index.php/G-Code