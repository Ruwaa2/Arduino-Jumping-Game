# Arduino-Jumping-Game


## Features And Capabilities: 
1. This project displays a jumping game on the LCD.
2. The pushbutton is pressed each time the player wants to jump.
3. While playing the game, a red light will be turned off.
4. If the player loses the game, the red light will be turned on until they restart the game.
5. The counter will be displayed on the LCD to indicate the score of the player for this round.


### The Circuit Diagram of The Jumping Game Project to Demonstrate the Connections 
1. Connect LCD GND to Arduino GND
2. Connect LCD VCC to Arduino 5V
3. Connect LCD SDA to Arduino A4
4. Connect LCD SCL to Arduino A5
5. Connect One Side of the Pushbutton to Arduino Pin 2
6. Connect the Other Side of the Pushbutton to Arduino GND
7. Connect the Negative Side of The LED to Arduino GND
8. Connect the Positive Side of The LED to Arduino Pin 3

#

#### Description For Each Component: #
- Arduino Uno Board <br /> 
A programmable open-source controller board that can be integrated to be used in a variety of electronic projects
- Breadboard <br />
A construction base used for developing an electronic circuit and wiring for projects with microcontroller boards
- LCD Module with I2C <br />
LCD is a type of display that uses the liquid crystals for its operation. Since the Arduino has a limited number of input/output pins, I2C enables the connection to more devices
- Connection Wires <br />
Flexible strands of metal used for establishing electrical conductivity between two devices of an electrical circuit
- Pushbutton <br />
A component that connects two points in a circuit when pressed
- LED <br />
A small powerful light 
- 220K Resistors <br />
Are used to limit the amount of current going to certain components in the circuit
