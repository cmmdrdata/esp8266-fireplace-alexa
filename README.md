# esp8266-fireplace-alexa
Alexa home automation using esp8266 board w/ wifi to control an electric fireplace switch 

Most of this code is directly adapted from the kakopapa/sinric github site.  
https://github.com/kakopappa/sinric/arduino_example/switch_example.ino

I added code for controlling the switch through a mosfet device 

You will need to follow the directions on the README to setup the sinric (free) account 
then create a device for the electric kettle to control.

This sketch will turn a switch to control an electric fireplace .   It uses an wemos mini d1 board which is an esp8266 
with wifi adapter built in.   You could also use a relay but the current draw from the esp will be higher when the fireplace 
switch is on. 

