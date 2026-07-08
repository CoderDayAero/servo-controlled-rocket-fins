# servo-controlled-rocket-fins

## What is it?

This project uses a potentiometer to control the position of a servo motor. When the potentiometer is turned (rotated), the Arduino reads the input and rotates the servo to the corresponding angle. This demonstrates a basic control system similar to how control surfaces on aircraft and rockets can be actuated.


## Components

* Arduino Uno R3
* Breadboard
* Servo Motor w/ wings attatched(SG90)
* Potentiometer
* (9)Jumper Wires


## How It Works

The Arduino continuously reads the analog value from the potentiometer. It then maps that value to an angle between 0° and 180° and commands the servo motor to move to that position. Turning the potentiometer changes the servo's angle in real time.


## What Went Wrong

* I was confused about how the breadboard power rails worked (like postive and negative)
* I had trouble wiring the potentiometer correctly, it was also difficult to keep in place
* The servo wasn't moving at first because of wiring issues, so I tested the servo separately to make sure it was working


## How I Solved It

* I learned how the breadboard's power rails distribute 5V and GND
* I checked each wire one at a time and confirmed the servo connections
* I tested the servo with a simple program before reconnecting the potentiometer


## What I Learned

* How to read analog input using a potentiometer
* How to control a servo motor with the Arduino Servo library
* How the `map()` function converts analog values into servo angles


## What I'll Do Next

* Add a gyroscope or accelerometer for automatic stabilization.

## Demo


https://github.com/user-attachments/assets/ef368a5c-ae91-4462-a67b-794daae0bfb6

