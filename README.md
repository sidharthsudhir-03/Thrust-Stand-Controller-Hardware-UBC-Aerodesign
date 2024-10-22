# Thrust-Stand-Controller-Hardware-UBC-Aerodesign

## Overview
The **Thrust Stand Controller** is a hardware project designed for measuring motor performance parameters (thrust, torque, voltage, current) for RC aircraft. This controller helps optimize motor configurations and helps in motor selection for the UBC Aerodesign team's aircraft. The system integrates sensors and microcontroller-based data acquisition to provide reliable performance data.

## Features
- **Thrust and Torque Measurement**: Uses dual HX711 load cell amplifiers to measure thrust and torque from the motor.
- **Power Monitoring**: Integrated voltage and current sensors for real-time power consumption analysis.
- **Microcontroller (ATMEGA32U4-AU)**: Responsible for interfacing with sensors and controlling PWM signals for the motor's ESC.
- **USB-C Connector**: Provides both power supply and data transfer capabilities.
- **ESC PWM Control**: Allows real-time adjustments of motor speed during tests via a 2-pin header for PWM control.
- **Flexible Design**: Added GPIO pin headers and solder pads for easy expansion and motor connection.
