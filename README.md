Solar Cell Temperature Analysis in Simulink

This repository contains a Simulink project that simulates and analyzes the functionality of a solar cell and how its performance is affected by different temperatures (25°C, 50°C, and 75°C).

Overview

Solar cells are highly sensitive to temperature, which directly impacts their efficiency and power output. In this project, we use MATLAB Simulink to model a solar cell and simulate its behavior under various temperature conditions to understand the thermal effects on:

Open-Circuit Voltage (Voc)

Short-Circuit Current (Isc)

Maximum Power Output (Pmax)

Key Features

Dynamic Simulation: Simulates real-world behavior of solar cells at different operating temperatures.

Temperature Impact Analysis: Compare the solar cell's performance metrics at 25°C, 50°C, and 75°C.

Visualization: Generate plots showing variations in voltage, current, and power under different temperature conditions.

Files

solar_cell_model.slx: Simulink model of the solar cell.

temp_analysis.m: MATLAB script for post-simulation data processing and visualization.

results/: Contains simulation outputs (graphs, data files).

Installation

Clone this repository:

git clone https://github.com/RafaelMarian/Project-Solar_Cell_And_Home_Photovoltaic_System.git

Open MATLAB and set the cloned repository as your working directory.

Open the Simulink model (SolarCellTemperatureOverview.slx) in MATLAB Simulink.

Usage

Open the Simulink model.


Run the simulation to observe how temperature affects the solar cell’s performance.


Results

The following key observations were made:

At 25°C:

High efficiency and optimal power output.

At 50°C:

Decrease in open-circuit voltage, slight increase in short-circuit current.

Reduced overall efficiency.

At 75°C:

Significant drop in open-circuit voltage.

Noticeable degradation in maximum power output.

Plots in the results/ directory illustrate these changes.

Dependencies

MATLAB R2021b

Simulink toolbox

Contributing

Contributions are welcome! If you have suggestions or improvements, please create a pull request or open an issue.

License

This project is licensed under the Personal License. See the LICENSE file for details.

Acknowledgments

This project was inspired by the need to understand thermal effects on solar cell efficiency. Special thanks to the MATLAB and Simulink documentation and community forums for guidance.

Contact



