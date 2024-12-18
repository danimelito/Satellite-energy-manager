# Satellite Energy Management System

This repository contains a Python-based simulation for managing the energy flow of a satellite, specifically the balance between plasma motor energy consumption and solar panel energy generation. The project is designed to provide an educational example of energy management in space systems and includes features like battery monitoring, operational mode switching, and visualizations.

---

## Features
- **Battery Management**: Simulates the battery level based on energy consumption and solar charging.
- **Mode Switching**: Automatically switches between idle, plasma motor operation, and solar charging based on battery levels.
- **Solar Panel Simulation**: Includes random fluctuations to simulate varying solar energy input.
- **Critical Alerts**: Prints warnings when battery levels drop below a critical threshold.
- **Graphs**: Visualizes battery levels and operational modes over time using Matplotlib.

---

## Requirements
To run the code, ensure you have the following installed:
- Python 3.8 or later
- Matplotlib

Install required dependencies:
```bash
pip install matplotlib
```

---

## Getting Started
### Clone the Repository
```bash
git clone https://github.com/your-username/satellite-energy-manager.git
cd satellite-energy-manager
```

### Run the Simulation
1. Open the `satellite_manager.py` file in your preferred IDE or code editor.
2. Execute the script:
   ```bash
   python satellite_manager.py
   ```
3. Observe the outputs in the terminal and view the generated plots.

---

## Simulation Parameters
The simulation allows you to customize the following parameters:
- **Battery Capacity**: Total battery capacity in watt-hours (Wh).
- **Motor Consumption**: Power consumption of the plasma motor in watts (W).
- **Solar Panel Generation**: Base power generation of the solar panels in watts (W).
- **Duration**: Total simulation time in seconds.
- **Time Step**: Interval for updating the simulation, in seconds.
