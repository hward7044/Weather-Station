# Arduino Weather Station

A modular C++ project for the Arduino Mega 2560 to monitor temperature and humidity using a DHT sensor and display readings on a 16x2 LCD.

## Project Structure

This project uses a modular architecture to separate hardware drivers from business logic.

- **`WeatherStation.ino`**: Main entry point.
- **`src/Config.h`**: System configuration and pin definitions.
- **`src/Sensors/`**: Drivers for temperature/humidity sensors (Interface + DHT Implementation).
- **`src/Display/`**: Drivers for display screens (Interface + LCD Implementation).
- **`src/System/`**: Core system logic manager.

## Hardware Requirements

- Arduino Mega 2560
- DHT11 or DHT22 Sensor
- 16x2 LCD Display (Standard or I2C)

## Getting Started

1.  Open `WeatherStation.ino` in the Arduino IDE.
2.  Install necessary libraries (e.g., `DHT sensor library`, `LiquidCrystal`).
3.  Configure pins in `src/Config.h`.
4.  Upload to your board.
