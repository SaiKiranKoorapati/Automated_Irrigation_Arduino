AUTOMATED IRRIGATION SYSTEM BASED ON SOIL MOISTURE USING IOT
Overview:
This project introduces an automated irrigation system based on a low-power microcontroller, specifically utilizing an Arduino Uno board. The system integrates a moisture sensor, an LCD display, a relay, a water motor, and a GSM module for message alerts. It efficiently manages watering based on soil moisture levels and provides real-time notifications to users via SMS.

Components:
Arduino Uno: The microcontroller responsible for processing sensor data, controlling the water motor, and managing GSM communication.
Moisture Sensor: Detects the humidity level in the soil.
LCD Display: Provides real-time feedback on the status of the soil moisture sensor.
Relay: Controls the operation of the water motor based on sensor readings.
Water Motor: Supplies water to the soil when activated.
GSM Module: Enables communication with mobile networks for sending SMS notifications.

Functionality:
The moisture sensor continuously monitors the humidity level in the soil. When the humidity falls below a certain threshold indicating dry soil, the water motor is activated via the relay to irrigate the soil. The status of the soil moisture sensor is displayed in real-time on the LCD display, providing users with immediate feedback on soil conditions. Additionally, if the soil moisture level remains low for an extended period, the system triggers the GSM module to send SMS alerts to the user, notifying them of the need for irrigation.

Usage:
1)Connect the moisture sensor, LCD display, water motor, relay, and GSM module to the Arduino Uno board.
2)Upload the provided Arduino sketch to the Arduino Uno board.
3)Power on the system.
4)Monitor the LCD display for real-time updates on soil moisture levels and irrigation status.
5)Receive SMS alerts on your mobile device when the soil moisture level requires attention.
