# SMART TRAFFIC LIGHT SYSTEM

## 1. Introduction

- This project implements a Smart Traffic Light Control System using the AT89C51 (8051) microcontroller. The system is designed and simulated in Proteus Design Suite.

- It manages traffic flow at a two-direction intersection through automated traffic signal sequencing, countdown displays, IR obstacle sensors, and manual control buttons.

- The main objective is to improve traffic management and demonstrate embedded system programming using 8051 Assembly Language.

## 2. Features

- Automatic Traffic Control: Alternates traffic signals between two directions.

- Traffic Light Sequencing: Controls red, yellow, and green LEDs with predefined timing.

- Countdown Display: Displays the remaining signal time using four 7-segment displays.

- IR Obstacle Detection: Integrates IR sensors for vehicle detection.

- Manual Traffic Control: Uses push buttons to prioritize a selected traffic direction.

- Safe Signal Transition: Provides a yellow-light transition before switching traffic priority when necessary.

## 3. Hardware Components

- AT89C51 (Main microcontroller)

- IR Obstacle Sensors (Vehicle detection)

- Red LEDs (Stop signal) 13s

- Yellow LEDs (Warning signal) 3s

- Green LEDs (Go signal) 10s

- 7-Segment Displays (Countdown timer)

- Push Buttons (Manual traffic control)

- Resistors (Current limiting and circuit protection)

## 4. Manual Control

- The system provides three control inputs:

    + P2.3: Activates a yellow-yellow warning state before restarting the traffic sequence.

    + P2.4: Prioritizes Direction 1 (Green) while Direction 2 remains Red.

    + P2.5: Prioritizes Direction 2 (Green) while Direction 1 remains Red.

- The manual priority buttons require approximately 5 seconds of continuous pressing. When a direction needs to transition to Red, the system provides a 2-second yellow transition.

## 5. How to Run

- Clone this repository.

- Open the Proteus project file in Proteus 8 Professional.

- Check the microcontroller program configuration.

- Load the compiled HEX file into the AT89C51 if it is not already configured.

- Start the simulation.

- Observe the traffic signals and countdown displays.

- Test the manual control buttons.

## 6. Future Improvements

- Implement adaptive traffic timing based on real-time vehicle density.

- Improve vehicle detection using multiple sensors.

- Add pedestrian crossing functionality.

- Integrate wireless monitoring and remote control.

- Deploy the system on real embedded hardware.

## 7. Author

Duong Hoang Khang

Computer Engineering Student
University of Information Technology (UIT)