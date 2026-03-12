# 🚗 Vehicle Control System

## 📖 Overview

The **Vehicle Control System** is a C-based simulation that models a vehicle’s core functionalities.  
This interactive program allows users to:

- Control the engine state (ON/OFF)
- Adjust vehicle speed based on traffic light signals
- Manage room and engine temperatures using sensors

It provides a **menu-driven interface** for real-time interaction, making it an ideal project for learning **embedded systems** and **C programming concepts**.

---

## ⚙️ Features

- **Engine Control**: Turn the vehicle engine ON or OFF
- **Traffic-Aware Speed Management**:
  - **Green (G/g)** → Speed = 100 km/h
  - **Orange (O/o)** → Speed = 30 km/h
  - **Red (R/r)** → Vehicle stops
- **Room Temperature Control**: Adjusts cabin temperature automatically based on sensor readings
- **Engine Temperature Management**: Maintains safe engine temperature using a controller (if enabled)
- **Interactive Menu**: User-friendly interface for all vehicle operations

---

## 🛠 Installation & Usage

### Prerequisites

- C Compiler (e.g., GCC)
- Terminal or command-line interface

### Steps

1. **Clone the repository**:
   ```bash
   git clone https://github.com/YoussefAdel170/Vehicle-Control-System.git
   ```
2. **Navigate into the project directory**
   ```bash
   cd Vehicle-Control-System
   ```
3. **Compile the program:**
   ```bash
   gcc vehicle_control_system.c -o vehicle_control_system
   ```
4. **Run the program:**
   ```bash
   ./vehicle_control_system
   ```
5. **Interact via the menu:**
   ```
    a. Turn on the vehicle engine
    b. Turn off the vehicle engine
    c. Quit the system
   ```
6. **Once the engine is ON, access sensor options:**
   - Set traffic light color
   - Set room temperature
   - Set engine temperature (if controller is enabled)
