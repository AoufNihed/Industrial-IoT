# Industrial IoT Temperature Monitoring

This repository contains a project that simulates and analyzes IoT temperature sensor data for industrial machines to prevent overheating, reduce downtime, and facilitate predictive maintenance. The project uses simulated data for three machines over a one-month period, with temperature readings taken every 15 minutes.

## Project Overview

### Scenario
We monitor three industrial machines using temperature sensors to prevent overheating. Overheating can lead to machine failures, costly repairs, and production downtime.

### Data Description
- **Timestamp:** Every 15 minutes
- **Machine ID:** Identifies the machine (Machine 1, Machine 2, Machine 3)
- **Temperature (°C):** Recorded in degrees Celsius

### Project Goals
1. **Trend Analysis:** Identify temperature trends that may indicate machine wear or malfunctions.
2. **Anomaly Detection:** Detect sudden temperature spikes that may signal issues.
3. **Summary Statistics:** Calculate key metrics like mean, max, and min temperatures to define normal operating ranges.

## Steps

### Step 1: Data Simulation
Simulates one month of temperature data for three machines, with readings recorded every 15 minutes:
- **Columns:** Timestamp, MachineID, Temperature

### Step 2: Data Analysis
Analyzes the data to provide insights into temperature behavior:
- **Trend Analysis:** Uses rolling averages to identify temperature trends.
- **Summary Statistics:** Computes mean, max, and min temperatures for each machine.

### Step 3: Data Visualization
Uses visualizations to better understand data patterns:
1. **Line Plot:** Shows temperature readings over time for each machine.
2. **Heatmap:** Displays daily average temperatures, highlighting which machines typically run hotter.

## Results
Summary statistics and visualizations reveal operating temperature ranges, potential issues, and trends:
- **Machine 1:** Mean 75°C, Max 93°C, Min 56°C
- **Machine 2:** Mean 70°C, Max 85°C, Min 51°C
- **Machine 3:** Mean 65°C, Max 82°C, Min 45°C

## Dependencies
- `Python`
- `pandas`
- `numpy`
- `matplotlib`
- `seaborn`

Install dependencies:
```bash
pip install pandas numpy matplotlib seaborn
