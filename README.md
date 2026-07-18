# 🔥 Arduino Fire Fighting Robot

## Overview

This project is an Arduino UNO-based Fire Fighting Robot that detects fire using three flame sensors. The robot automatically moves toward the fire source and activates a water pump through a relay while a servo motor sprays water to extinguish the fire.

---

## Features

- Automatic fire detection
- Autonomous navigation
- Water pump control using relay
- Servo-controlled water spraying
- Arduino UNO based system
- Three flame sensors for fire direction detection

---

## Components Used

- Arduino UNO
- L298N Motor Driver
- 4 DC BO Motors
- Servo Motor (SG90)
- Relay Module
- Water Pump
- 3 Flame Sensors
- 18650 Li-ion Batteries
- Chassis
- Jumper Wires

---

## Circuit Diagram

![Circuit Diagram](Images/Circuit_Diagram.png)

---

## Pin Connections

| Component | Arduino Pin |
|-----------|-------------|
| Flame Sensor Left | A0 |
| Flame Sensor Center | A1 |
| Flame Sensor Right | A2 |
| Left Motor IN1 | D5 |
| Left Motor IN2 | D6 |
| Right Motor IN1 | D9 |
| Right Motor IN2 | D10 |
| Relay Module | D7 |
| Servo Motor | D3 |

---

## How It Works

1. Reads values from three flame sensors.
2. Detects the direction of the fire.
3. Turns toward the flame.
4. Moves closer to the fire.
5. Activates the water pump.
6. Sweeps the servo motor to spray water.
7. Stops after extinguishing the fire.

---

## Author

**Preetham Girigowda**