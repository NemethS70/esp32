ESP32-C6 ST7735 TFT 

little memo how to wire a 1.8" RGB 128x160 TFT to an ESP32-C6 controller board.

Since the evolution of the board is fast and many manufacturer made their own version, official documentation may not apply.
In my case i had difficulties to identify and figure out how to wire the TFT.

The pictures shows the wire functions and the connections by colors.

After the TFT initialization screen may shifted, that can be corrected with the "setColRowStart(2, 1);" line in the Adafruit_ST7735.cpp file befor the initialization command.
Blacklight pin not connected
