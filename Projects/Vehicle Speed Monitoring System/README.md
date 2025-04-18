# Vehicle Speed Monitoring System

## 🧠 Concept

We simulate a wheel speed sensor (e.g., using pulse input) and calculate vehicle speed in km/h or m/s. The calculated speed will be displayed on a virtual LCD or sent over UART.

## 📐 System Design Overview

### 🔧 Inputs

- **Pulse Signal** (from a simulated wheel sensor): Each pulse = one wheel rotation.
- **Timer/Interrupt**: Used to count pulses or measure time between them.

### 📤 Outputs

- Speed value displayed on:
    - **LCD display**, or
    - **UART serial console**  
