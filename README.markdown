<h3>PongSat Environment Sensing Datalogger</h3>

<h4>NOTICE: This isn't finished yet!!! I wouldn't try making one...</h4>

<p>The PongSat has a barometric pressure sensor, a humidity sensor, a temperature 
sensor and I2C bus for a 9DoF sensor stick (<a href=""http://www.sparkfun.com/products/10724">
SEN-10724</a>) which has on it an Accelerometer, Magnetometer and Gyroscope. The board
uses 3.3 volt logic and power.</p>

<p>This is a double sided PCB that will be able to fit inside a PingPong ball and 
so it can be used in JP Aeorspace's free Pongsat launches. All of the components are SMD, 
and so are pretty tiny, but can be harvested off a SparkFun OpenLog, and an Arduino Pro Micro 
(with the AtMega32u4).</p>

<p>Because of the 32u4 processor, this can be talked to and programmed via a USB Micro B 
connector, as commonly found on smartphone chargers. There is a I2C header with 3V3 and GND, 
but there is no FTDI or other serial connector other than the USB.</p>

<p>Because this is designed to fit in a pingpong ball, powering it can be difficult, so it 
is recommended to use two 3 volt coin cell batteries to get a total of 6 volts. The 
batteries should last a long time, but if you can find a small LiPo I'd strongly recommend 
using that.</p>

<p>None of these have ever been made in any way shape or form, so there is absolutely no 
guarantee of it being assemble-able, let alone functional. You do that at your own risk. 
After I have made on then I will say whether it works or not...</p>

<p>This project is licensed under the WTFPL (so it is in the public domain)</p>