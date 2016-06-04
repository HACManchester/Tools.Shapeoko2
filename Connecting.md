# Connecting

To connect to the device

## Putty

  * Download and install Putty from http://www.chiark.greenend.org.uk/~sgtatham/putty/download.html

  * Open putty and connect to the grbl / arduino Uno's COM Port
  * Speed: 115200
  * Databits: 8
  * StopBits: 1
  * Parity / Flow Control: None
  * http://www.shapeoko.com/wiki/index.php/G-Code

## Chilipepr

To setup serial port json server

  * Go to http://chilipeppr.com/grbl within a browser (ideally chrome)
  * In the bottom right hand corner there should be a link to the serial port json server
  * Download this as a zip / extract
  * Attach the Arduino Uno with the G-Shield / External power to the board for the motors
  * Run the serial-port-json-server.exe

To Connect to the device

  * Within Chilipepr connect to localhost
  * Within the listed devices there should be one visible, change the speed to **115200** and the type to **grbl**
  * Click the Tick box next to the device to connect

Next to just try jogging the device (moving small increments). <br>
Click the down / up arrow on the **Axes** line at the top right corner. <br>
Select the amount of mm to move the device, and click left / right / up / down etc in the different axis to test
