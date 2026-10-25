
# MIDI Keypad

This project is a custom MIDI controller inspired by Kai Pereira's [MIDI Keypad project](https://github.com/KaiPereira/MIDI-Keypad). It uses a Raspberry Pi Pico to turn physical controls into MIDI input. My version adapts the original design to use the Raspberry Pi Pico and combines buttons, touch-sensitive keys, a rotary encoder and slide potentiometers to provide different ways to control MIDI instruments and software.

## Hardware Design

The controller is designed with the Raspberry Pi Pico, which reads the inputs from the different controls and handles the MIDI functionality. The design includes three physical keys, seven capacitive touch inputs, two Bourns slide potentiometers and a rotary encoder, providing a combination of digital and analog controls.

### 3D Model

A 3D representation of the controller designed in KiCad.
<img width="744" height="548" alt="image" src="https://github.com/user-attachments/assets/012180cc-708c-4651-81ce-01a4ab3408a9" />



### Schematic

<img width="1301" height="909" alt="image" src="https://github.com/user-attachments/assets/6ad1879b-d26a-4273-9b1b-cdf2cee367b1" />



## Controls

The controller includes several types of input:

- **Physical keys:** Three buttons for triggering assigned actions.
- **Capacitive touch keys:** Seven touch-sensitive inputs for triggering MIDI actions.
- **Bourns slide potentiometers:** Two sliders for controlling continuous MIDI parameters.
- **Rotary encoder:** A rotational control for navigating values or adjusting parameters.

## Code

The firmware runs on the Raspberry Pi Pico and reads the connected controls to handle their inputs and MIDI functionality. The aim is to use the controller as a physical interface for music software, with the different controls offering flexible ways to trigger notes and adjust parameters.

## About the Project
it is my first music related pcb and i am really grateful to be given the chance to learn this 
Also, the placement of the capacitive touch keys are placed like that due to being easier to use with 2 hands using the thumb, without needing to loom at the keys, being easily touched without much movement
