# led-badge
attiny85 with 9 RGB LEDs

There are two JST connectors on the back:

2-pin - takes 3.3 to 6 VDC

4-pin - programming port, left-to-right correspond to pins 7,6,5,1 on the attiny

To reprogram, set up a regular Arduino Uno as an ISP and connect the badge's programming port pins to pins 10-13 on the Uno.

https://create.arduino.cc/projecthub/arjun/programming-attiny85-with-arduino-uno-afb829

Once your code is loaded, you can use those pins to control or read external devices.  The LED string is on physical pin 3, which is pin 4 in code (Why do they do this?).

