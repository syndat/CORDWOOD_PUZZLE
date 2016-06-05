# CORDWOOD_PUZZLE
Processing JAVA code for CORDWOOD PUZZLE

This is a demo patch to show how you can control the arduino over the standard firmata protokol from processing.
It uses the GUI-library G4P for the buttons. The CORDWOOD PUZZLE is from BOLDPORT CLUB!
Find details here: http://www.boldbort.com

1) clone the .zip file and expand it on your hard drive.

2) load the standardfirmata sketch from examples (arduino IDE 1.6.9) on your arduino

3) install arduino and P4G library in processing 3.3.1

4) Open GUI_CordWood sketch from expandes zip folder

5) change in line 20 arduino = new Arduino(this, "COM5", 57600); to the correct COM-Port

6) Connect the CORDWOOD PUZZLE to PIN D2-D7 and GND and %V

7) Run the sketch and have fun!
