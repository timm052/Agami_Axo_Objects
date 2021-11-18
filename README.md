# Agami
The Agami is a synthesiser control board that connects to the [Axoloti](http://www.axoloti.com/). It is built primarily around two MCP23017 IO Expanders, one for 13 keys/3 buttons, the other for 8 encoders. A small I2C screen is also included, as are 14 WS2812C LEDs. The address of the IO expanders is selectable, allowing two Agami boards to be chained together, and connected to the Axoloti. As there is no microcontroller used, all elements are controlled directly from the Axoloti via I2C.

Schematic:
![Agami Schematic](/Schematic.png)

PCB Layout:
![PCB Design](/PCB.png)

Prototype Board:
![Prototype Board](/Board.jpg)
