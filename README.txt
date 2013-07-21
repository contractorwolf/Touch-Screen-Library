I modified the original to allow for better usage at a USB device.  Now the Arduino will output the data from 
the touchscreen as a comma delim list that is ended with a *.  This allows parsers (i.e. a PC) to consume the 
data more easily.  Wiring is done the same and indicated in the comments of the .ino file.

This is the 4-wire resistive touch screen firmware for Arduino. Works with all Arduinos and the Mega


To install, click DOWNLOAD SOURCE in the top right corner, and rename the uncompressed folder "TouchScreen". 
See our tutorial at http://www.ladyada.net/library/arduino/libraries.html on Arduino Library installation
