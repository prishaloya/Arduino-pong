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




