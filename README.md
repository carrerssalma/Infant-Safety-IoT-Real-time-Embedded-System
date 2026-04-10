# 👶 Infant Safety IoT – Real-time Embedded System

A real-time baby monitoring system built with an STM32 microcontroller, designed to detect environmental and physiological risks and trigger automated alerts.

## Features
- Monitors temperature, heart rate, oxygen level, motion, and smoke
- Controls actuators (fan, alarm) based on sensor thresholds
- Real-time scheduler for concurrent task management
- SMS alerts for critical events

## Tech Stack
- **Language:** C
- **Hardware:** STM32 microcontroller, sensors, actuators
- **Concepts:** Real-time scheduling, embedded systems, IoT

## How it works
Each sensor runs as an independent task managed by a real-time scheduler. When a threshold is exceeded, the system triggers the appropriate actuator and sends an SMS alert.
