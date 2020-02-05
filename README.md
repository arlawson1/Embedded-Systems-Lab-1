# Embedded-Systems-Lab-1
A finite-state machine used to control an on-board LED and an external LED

This lab is intended to introduce the students to basic i/o interfacing with an Arduino.

It is intended to be easy and simple, as to help the students learn the basic functions
  and methods of the Arduino IDE.

The objective of this lab is to use the serial monitor to collect input and change state
  based on the input. Upon startup, the LEDs are both off. When the user inputs the letter
  'g', the LEDs will start blinking out of sync (on-board LED on for 2 seconds, off for 1
  second. External LED off for 2 seconds, on for 1 second). Upon inputting the letter 's',
  the LEDs will stop blinking and return to the OFF state.
