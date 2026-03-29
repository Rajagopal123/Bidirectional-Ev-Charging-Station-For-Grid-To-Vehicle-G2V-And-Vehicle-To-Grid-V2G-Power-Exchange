# Bidirectional-Ev-Charging-Station-For-Grid-To-Vehicle-G2V-And-Vehicle-To-Grid-V2G-Power-Exchange
Developed a bidirectional EV charging station enabling G2V and V2G power flow using dq-PLL control and LCL filtering. Simulated multi-EV coordination with stable DC bus voltage, low THD, and controlled power exchange based on battery SOC, demonstrating improved grid support and energy management.

# Bidirectional EV Charging Station (G2V & V2G)

## Overview

This project presents a bidirectional EV charging system enabling controlled power flow between grid and multiple EVs using dq-PLL based control.

## Key Features

* Grid-to-Vehicle (G2V) and Vehicle-to-Grid (V2G) operation
* dq-axis current control with PLL synchronization
* LCL filter for harmonic reduction
* Multi-EV coordination using shared DC bus

## System Architecture

<img width="1040" height="423" alt="image" src="https://github.com/user-attachments/assets/bcda7076-a33f-47f3-8921-9583fa4a0fac" />


## Simulation Models

* Single EV (G2V mode)
* Single EV (V2G mode)
* Multi-EV bidirectional operation

## Results

### G2V Mode

* Stable DC bus at 800V
* Smooth sinusoidal grid current
* SOC increases

### V2G Mode

* Power injected into grid
* Unity power factor operation
* SOC decreases

### Multi-EV Mode

* Simultaneous charging and discharging
* Balanced DC bus voltage
* Coordinated power sharing

## Tools Used

* MATLAB/Simulink
* Control: dq-axis, PLL, PI controllers

## Key Insight

The system demonstrates that coordinated EV fleets can act as distributed energy storage, improving grid stability and enabling smart energy management.

## How to Run

1. Open Simulink model
2. Run respective case (G2V / V2G / Multi-EV)
3. Observe voltage, current, and SOC outputs

