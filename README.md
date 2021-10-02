# Fade-LED
## Abstract 
This example demonstrates the use of the analogWrite() function in fading an LED off and on. AnalogWrite uses pulse width modulation (PWM), turning a digital pin on and off very quickly with a different ratio between on and off, to create a fading effect.

## Hardware Components:

 - Arduino Uno
 - LED 

## Development Tools Used:

- PROTEUS 8 - for simulation
- Arduino - for programming

## Hardware Connection:

- D10 of Arduino Uno is connected to the LED

## Usage:
- Download the schematic.pdsprj file->open in PROTEUS 8 tool.

<img src=https://user-images.githubusercontent.com/84024571/134051278-ef52d6a8-f286-4eba-aab5-8d7341b1935e.PNG width="800" height="400">

- Download code. ino and open in the Arduino tool.
- Go to tools ->select Board->select Arduino UNO.
- Click on “Verify” button and copy the generated hex file path from Arduino as described in following link
  https://www.instructables.com/HOW-TO-GET-HEX-FILE-FROM-ARDUINO-/
- Go to PROTEUS 8->Click on Arduino Uno->Edit Component window will pop up ->paste the hex file path in Program file->Click OK.

<img src=https://user-images.githubusercontent.com/84024571/132992989-2161269d-0baf-4f56-9f3c-890b1d71bbe5.PNG width="800" height="400">

- Click on the Run button.

## Output:

<img src=https://user-images.githubusercontent.com/84024571/134051871-8abd34ce-3e35-45ca-b4c9-07c0c6008901.PNG width="800" height="400">






