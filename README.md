# Water-Level-monitoring-
## Description
This project is a water level monitoring and automatic pump control system using ESP8266 (NodeMCU). It helps to monitor water level in a tank and automatically turn the motor ON/OFF.

## Components Used
- ESP8266 NodeMCU
- Ultrasonic Sensor (HC-SR04)
- Breadboard & Jumper Wires
- 12V Power Supply
- LCD Display (16x2)

## Working
- The ultrasonic sensor measures the water level.
- ESP8266 processes the data.
- When water level is low → Pump turns ON.
- When tank is full → Pump turns OFF.

## Features
- Automatic motor control
- Water level monitoring
- Saves water and electricity

## Applications
- Home water tanks
- Agricultural irrigation
- Industrial water systems

## 🔌 Wiring Connections

### 1. HC-SR04 Ultrasonic Sensor
| HC-SR04 Pin | ESP8266 (NodeMCU) Pin |
| :--- | :--- |
| VCC | Vin (5V) |
| GND | GND |
| Trig | D7 (GPIO 14) |
| Echo | D8 (GPIO 12) |

### 2. I2C LCD Display
| I2C Module Pin | ESP8266 (NodeMCU) Pin |
| :--- | :--- |
| VCC | Vin (5V) |
| GND | GND |
| SDA | D2 (GPIO 4) |
| SCL | D1 (GPIO 5) |
