# Vehicle-Platoon-RL
# Cooperative RL-Based Control for Heterogeneous Vehicle Platoons

## Overview

Cooperative driving of connected and automated vehicles (CAVs) is a promising strategy for enhancing fuel efficiency, safety, and traffic flow. However, achieving safe and efficient cooperative control for multiple CAVs within a platoon, particularly in the presence of disturbances and uncertainties, remains a major challenge in intelligent transportation systems (ITSs).

This repository contains the implementation of a novel **model-free off-policy distributed cooperative control approach** for heterogeneous vehicle platoons in highway scenarios. The methodology integrates **reinforcement learning (RL)** with **robust compensating techniques**, enabling safe and efficient cooperative driving.

## Key Features

- **Model-Free Control**: Utilizes input-output system data instead of complex vehicle dynamical models to achieve optimal platoon control.
- **Integrated Control Strategy**:
  - **RL-Based Nominal Controller**: Learns optimal control policies through experiential learning.
  - **Robust Compensator**: Mitigates the effects of disturbances and uncertainties in vehicle dynamics.
- **Distributed Observer**: Based on consensus theory to estimate desired trajectories for each vehicle.
- **Analytical Stability Proof**: The robust stability of the system is proven using Lyapunov theory.

## Experimental Validation

The proposed control strategy is validated using the high-fidelity **Mixed Traffic Simulator (MiTaS)** co-simulation platform, which integrates:
- **Simulation of Urban Mobility (SUMO)**: A microscopic traffic simulator.
- **MATLAB Environment**: For detailed control algorithm implementation.

Stop-and-go driving maneuvers under traffic oscillations demonstrate the robustness and efficiency of the control system.


https://github.com/user-attachments/assets/23c5ced4-8f06-404b-acdd-34068aa121ac



## Applications

This work contributes to the development of autonomous cooperative multi-vehicle systems and intelligent transportation networks, with potential applications in:
- Reducing traffic oscillations.
- Enhancing road safety.
- Improving fuel efficiency.

---

Feel free to explore the repository for detailed implementations and simulation results.
