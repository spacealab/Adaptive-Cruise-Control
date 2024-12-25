# Adaptive Cruise Control
# Adaptive Cruise Control System Simulation

## Overview

This project focuses on the **analysis and evaluation of an adaptive cruise control (ACC) system** under dynamic traffic conditions. The simulation is implemented using **MATLAB** and **Simulink**, integrating multiple components like sensors, controllers, and vehicle dynamics to ensure accurate performance evaluation.

### Key Objectives
1. Optimize fuel consumption.
2. Enhance driving safety.
3. Reduce driver fatigue.
4. Evaluate and improve control algorithms under realistic traffic conditions.

---

## Project Details

### Simulation Scenario
The simulation involves:
- **Road Environment**: A curved highway section with a radius of 850 meters.
- **Vehicles**:
  - **Ego Vehicle (purple)**: Equipped with the ACC system.
  - **Other Vehicles**: Includes one vehicle moving in the same direction and another in the opposite direction.

#### Dynamic Conditions
1. The ego vehicle adjusts its speed to maintain a safe distance from the vehicle ahead.
2. The vehicle ahead changes lanes, allowing the ego vehicle to return to its original speed.

---

### Key Features
1. **Sensor Fusion**: Utilizes sensor data for real-time adjustments.
2. **Algorithm Efficiency**: Evaluates the stability and adaptability of the ACC algorithm.
3. **Traffic Scenarios**:
   - Acceleration.
   - Constant-speed driving.
   - Deceleration.

---

## Simulation Results
- Initial phase: Ego vehicle maintains a constant speed of 20 m/s with safe distancing.
- Mid-phase: Reduced speed to maintain safe following distance.
- Final phase: Ego vehicle accelerates to target speed after the lead vehicle changes lanes.

### Conclusion
The ACC system demonstrated reliable responses to dynamic traffic scenarios, maintaining safety and efficiency.

---

## How to Use the Repository
1. Clone the repository:
   ```bash
   git clone https://github.com/spacealab/acc-simulation.git
