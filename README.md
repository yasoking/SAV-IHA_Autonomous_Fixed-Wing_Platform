# Autonomous Fixed-Wing UAV Simulation & AI Detection System

## Project Overview
This project is a simulation and prototype development of an autonomous fixed-wing UAV system designed for AI-based detection, navigation, and competitive scoring behavior in a multi-agent environment.

The system focuses on a drone that operates autonomously after initialization, performs QR-code-based mission activation, and engages in AI-driven detection of other drones within a simulated environment.

---

## Core Concept
- Fixed-wing UAV architecture for improved endurance and speed
- Autonomous mission start via QR code recognition
- AI-based object detection for identifying other drones
- Competitive scoring system:
  - Gain points when detecting other drones
  - Lose points when being detected
- Controller-based flight management system

---

## System Workflow
1. **Initialization**
   - UAV starts mission by reading a QR code
   - QR code defines mission parameters

2. **Autonomous Mode Activation**
   - Drone transitions into autonomous flight mode

3. **Navigation & Control**
   - Flight controlled via ground controller interface
   - Fixed-wing aerodynamic model used for efficiency

4. **AI Detection Module**
   - Computer vision model detects nearby drones
   - Detection events trigger scoring logic

5. **Scoring System**
   - +Points for detecting other drones
   - -Points when detected by others

---

## Design Rationale
A fixed-wing configuration is selected instead of a multirotor platform due to:
- Higher flight efficiency
- Longer endurance
- Higher cruise speed
- Better suitability for continuous mission coverage

Airframe design includes:
- Customizable geometry
- Adjustable airfoil profile
- 3D-printed PETG structural components

---

## Technologies (conceptual)
- Computer Vision (AI detection)
- Embedded flight control system
- UAV aerodynamics (fixed-wing modeling)
- QR code recognition system
- Ground control interface

---

## Applications
- Autonomous UAV swarm simulation
- Defense-style training environments (non-combat simulation)
- AI-based aerial detection systems
- Research in UAV autonomy and cooperative/competitive multi-agent systems

---

## Status
Prototype / Research & Simulation Stage
