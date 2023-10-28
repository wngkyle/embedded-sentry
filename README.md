# Embedded Sentry

### Table of Contents

- [Introduction](#introduction)
- [User Guide](#user-guide)
- [Built With](#built-with)
- [Technologies Used](#technologies-used)

### Introduction

The aim of this project is to create a gesture-controlled lock, providing users with the ability to define and activate a custom gesture for locking and unlocking. To unlock the device, users must replicate the same gesture that they recorded. The outcome of the gesture verification will be conveyed through LED strips on the device, accompanied by a musical effect played through the built-in speaker. A successful attempt will illuminate the LEDs in a soothing green, while an unsuccessful one will be signaled by a red LED display. In the event of three consecutive failed attempts, the device will automatically lock itself for a period of 3 minutes. After this duration, users can resume their attempts to input the gesture.

<p align="center">
  <img height="550px" src="https://github.com/wngkyle/embedded-sentry/assets/99611120/c6e68636-969e-444c-bf95-e83f734c7603" />
</p>

## User Guide

- Starting Gesture Recording
  - To begin recording your custom gesture, press the right button located on the board. This will activate the recording mode. 
- Unlocking the Board
  - To enter and check your gesture for unlocking the board, press the left button on the board. 
- Recording Mode Indicator
  - When in recording mode, you will notice that the small on-board LED is illuminated, indicating that the board is actively recording your gesture.
- Gesture Verification Outcome
  - After entering your gesture, the on-board LED will light up, conveying the result of the check. If the Neo Pixels illuminate in red, accompanied by an incorrect sound effect from the built-in speaker, it signifies that the entered gesture is incorrect. In contrast, if the Neo Pixels display a green color and you hear a correct sound effect from the onboard speaker, your entered gesture is correct. 
- Additional Monitoring Options
  - You can also access the serial monitor to check the current mode (whether it's in the record or enter mode), the check result (correct or incorrect), and the recorded values, providing you with a more detailed view of the device's operation.




### Built With


### Technologies Used
