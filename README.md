The setup is trivial. One Arduino Uno with pins in any of the analog capable
ports connects to one LED on a breadboard through several resistors in series. 
The port is specified in line 104, at the instantiation time of the FireflyLED 
object; I used port 5. 

The LED is the YSL-R531Y5C-5v yellow (585-595nm) LED from sparkfun. 

I am really bad at reading resistor bands, but I've uploaded a picture of the 
resistors to this folder as well as a picture of the whole setup so it should 
be clear to anyone attempting to reproduce the setup. 

Simply upload the code to the Uno and it will flash like a single frontalis: 
the brightness of the LED through the resistors in series seems to mimic the 
brightness of a firefly, but it's not precise. 
