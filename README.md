# Arduino-TvrECUOBD
Arduino project - connects to MBE ECU and converts to OBD

This project was created to retrieve data from a TVR Cerbera MBE ECU (should work with all MBE ECUs in TVRs), and convert the data to an OBD compliant output for use in OBD applications on a smartphone, more particularly Harry's Lap Timer application for video overlay purposes.

It is by no means complete in that it mostly gathers data necessary for the lapTimer application, however the basics are there for it to be improved upon and made more generic for OBD (e.g. fault codes, etc...).

The hardware this was build and tested on is as follows:
-Freeduino Serial v2.0
-Seeed CAN BUS Shield V1.2
-PLX Kiwi3 CanBus to Bluetooth OBD
-Homemade serial shield for debugging (https://arduinodiy.files.wordpress.com/2012/03/max232.jpg)

