# Embedded-Systems-Project-STM32
This repository contains the project files for a temperature-controlled DC fan, a project completed as part of the ELK 346 at Istanbul Technical University. The system is based on a Nucleo G031K8 microcontroller, uses a thermistor to measure ambient temperature, controls the operation of a DC fan using PWM, and displays information on a 2x16 LCD through I2C communication.

## Project Overview
This embedded system project revolves around controlling a DC fan's operation based on the surrounding environment's ambient temperature. The main components used include a Nucleo G031K8 microcontroller, a thermistor for temperature sensing, a transistor to drive the DC fan, a 2x16 LCD for displaying temperature and fan status, and additional resistors and capacitors for circuit protection and filtering.

The DC fan is controlled using Pulse Width Modulation (PWM), which allows for precision control of the fan speed. The LCD uses I2C communication to display relevant information.

## Components
1. Nucleo G031K8 Microcontroller: The brain of the system, used to process data from the thermistor, control the operation of the DC fan through PWM, and communicate with the LCD via I2C.
2. HD44780 2x16 LCD: Uses I2C communication to display current temperature readings and the status of the DC fan.
3. DC Fan: The device controlled by the system using PWM, its operation depends on the temperature data gathered.
4. Thermistor: A temperature sensing device, it provides the microcontroller with data about the ambient temperature.
