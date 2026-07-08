

https://github.com/user-attachments/assets/1ee9051c-e86e-42f7-88dd-97d4d8a7b334

<img width="1280" height="960" alt="Hardware3" src="https://github.com/user-attachments/assets/bc440046-b52c-400f-9c50-b53726054a40" />
<img width="1280" height="960" alt="Hardware2" src="https://github.com/user-attachments/assets/042435c3-aab3-41f5-b27a-4b2c70e98b2f" />
<img width="805" height="691" alt="Hardware" src="https://github.com/user-attachments/assets/788e03c6-b258-4e1c-aff5-e90614818948" />
# Arduino-pong
A Pong game built from scratch on an Arduino Uno using an 8×8 MAX7219 LED matrix.

This project was developed to practice embedded systems programming, real-time game loops, collision detection, and graphics rendering on an LED matrix. Instead of following a complete tutorial, the game was designed and implemented incrementally, from moving a single pixel to a fully playable Pong game.

## Features

* Player-controlled paddle using push buttons
* Ball movement with wall collisions
* Paddle collision detection
* Automatic game reset after a miss
* Modular code organized into reusable functions
* Paddle represented using a custom `struct`

## Hardware Used

* Arduino Uno
* MAX7219 8×8 LED Matrix (FC-16)
* 2 × Push Buttons
* Breadboard
* Jumper Wires

## Libraries

* MD_MAX72XX
* SPI
* MD_Parola

## Circuit Connections
MAX7219 DIN - D11
MAX7219 CS- D10
MAX7219 CLK- D13
LEFT BUTTON- D2
RIGHT BUTTON - 3
VCC- 5V
GND- GND

## How It Works

* The player controls a three-pixel paddle using two push buttons.
* The ball moves diagonally across the LED matrix.
* The ball bounces off the top, bottom, and right walls.
* If the ball hits the paddle, it bounces back.
* If the player misses the ball, the game resets.

## Concepts Practiced

* Embedded systems programming
* Real-time game loop
* Collision detection
* Object representation using structs
* Function decomposition
* LED matrix graphics
* Button input using internal pull-up resistors

## Images

<img width="805" height="691" alt="Hardware" src="https://github.com/user-attachments/assets/e9c49ae5-4e32-4cdb-b205-645523d6052e" />

<img width="1280" height="960" alt="Hardware2" src="https://github.com/user-attachments/assets/1c67fc77-4d18-48bf-8710-155a105bbe6b" />

<img width="1280" height="960" alt="Hardware3" src="https://github.com/user-attachments/assets/a8d21b89-0eae-48c6-b379-47a0e52c7015" />


## Working Video

https://github.com/user-attachments/assets/d4625cb5-de70-4923-b910-478b8ee09e57



