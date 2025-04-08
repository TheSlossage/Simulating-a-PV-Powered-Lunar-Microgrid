# Feasibility of PV Generation as a sole provider for an industrialized lunar microgrid

This repository contains multiple Simulink models for simulating a PV-powered industrial lunar microgrid designed for my honours project. It is freely available for academic and research use.

## Contents
Simulink Models
- Sensitivity_Analysis.slx - A model for testing the effect of different irradiances on PV Generation
- Simulation_3221.slx - A model simulating the microgrid performance during a 10 minute period of peak operations
- Simulation_3222.slx - A model simulating the microgrid performance during a 10 minute period of minimal
- Simulation_3231.slx - A model simulating the microgrid performance during a 708 hour period on the time scale 1s=1h
- Simulation_3232.slx - A model simulating the microgrid performance when PV Generation Ceases on the time scale 1s=1h 
- Simulation_3241.slx - A model simulating the microgrid performance during 18 year period on the time scale 1s=1week
- Parameter_Definitions.m - Defines variables for simulations
- `README.md`: This file
- `LICENSE`: Open-source license
- `CITATION.cff`: Citation information

## Requirements

- MATLAB R2023a or later
- Simulink
- Toolboxes: Simscape>Electrical>Specialized Power Systems

## Usage

1. Clone this repository:
   https://github.com/TheSlossage/Simulating-a-PV-Powered-Lunar-Microgrid

2. Open MATLAB and set the folder as the current directory.

3. Open the model "Parameter_Definitions.m" to define the variables.

4. Open any simulation file you'd like to run

5. Click Run in the Simulink toolbar

6. The Data will be displayed on the respective Scopes
