# Lab 2: Traffic Light System

This lab involves creating a traffic light system using GPIOs and a state machine.

## Task Description

The task description can be found in the [task-description.md](task-description.md) file.

## Solution

The solution files are located in the `traffic_light_system` directory.

- `traffic_light_system/main/app_main.c`: Main application code that initializes the lights and runs the traffic light logic.
- `traffic_light_system/main/gpio_lights.c`: Contains functions to initialize and set the GPIO states for the traffic lights.
- `traffic_light_system/main/gpio_lights.h`: Header file for GPIO light functions.
- `traffic_light_system/main/traffic_light_logic.c`: Contains the core logic for the traffic light state machine.
- `traffic_light_system/main/traffic_light_logic.h`: Header file for the traffic light logic functions and enum definitions.

## How to Build and Run

1. Set up the ESP-IDF environment:

   ```sh
   . $HOME/esp/esp-idf/export.sh
   ```

2. Build the project:

   ```sh
   cd traffic_light_system
   idf.py build
   ```

3. Flash the firmware to the ESP32 board:

   ```sh
   idf.py flash
   ```

4. Monitor the serial output:
   ```sh
   idf.py monitor
   ```
