# Embedded System Control with STM32 - Blinking LED

## Overview
This project is part of a course on Embedded C, focusing manipulation of hardware registers on STM32 microcontroller to control GPIO peripherals and make an LED blink.

## Key Features
- **Clock Activation**
- **Sets GPIOD pins to output mode for LED blinking**
- **Optimization using `volatile` and `const` keywords for O3 optimization on STM32CubeIDE**

## Project Structure
- `main.c`: Contains the main logic for GPIO configuration and control, including the LED blinking functionality.
- `main.h`: Contains the three different types to abstract organization of hardware registers, in order to easily control the LEDs of the board. Uses bitfields to optimize memory.

## Hardware and Tools
- **Microcontroller**: STM32F407
- **IDE**: STM32CubeIDE

## Setup and Run
1. Load the project in STM32CubeIDE.
2. Make sure the STM32 development board is connected.
3. Compile the program to the microcontroller.
