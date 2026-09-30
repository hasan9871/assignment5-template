# assignment5-template
Basics of programming assignment 5

## Student

Fill here:

- Name MD Shimul
- Group B

## Description of the project
Assignment 5.2


## User instruction

The 5.2 program controls a two-motor robot car and makes it follow an S-shaped route. It uses PWM to control motor speed and direction pins to control forward, backward, left, and right movement.

Main ideas:

move_forward(meters) → moves the car forward for a given distance.
reverse(meters) → moves backward.
turn_left(degrees) → turns left on the spot.
turn_right(degrees) → turns right on the spot.
turn_around() → turns the car 180°.
drive_s_route() → combines these functions to create the S-route.

The S-route is basically:

Forward 0.5 m → Left 90° → Forward 0.5 m → Left 90° → Forward 0.5 m → Right 90° → Forward 0.5 m → Right 90° → Forward 0.5 m → Turn 180° → Reverse 0.5 m.

Before starting, the program waits 5 seconds so the car can be placed on the floor.

In one sentence:

5.2 teaches us how to control a two-motor robot using functions and timing so that it can drive a predefined S-shaped route.
