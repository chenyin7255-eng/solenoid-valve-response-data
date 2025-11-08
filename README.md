# Solenoid Valve Dynamic Response Dataset

This repository contains simulated response data for a solenoid valve, comprising 200 experimental samples with corresponding timing diagrams.

## Dataset Overview

- **Data Type**: Simulation Data
- **Samples**: 200 individual tests
- **Format**: ZIP archive containing CSV files and PNG images
- **Content**: Time-series measurements of electrical and mechanical parameters

## File Structure
solenoid_valve_response_data.zip
├── sample_00.csv
├── sample_00.png
├── sample_01.csv
├── sample_01.png
└── ... (200 samples total)

## Data Format

Each CSV file contains the following columns:
- `time`: Timestamp (seconds)
- `voltage`: Applied voltage (V)
- `current`: Electrical current (A)
- `pressure_pa`: Pressure in Pascals (Pa)
- `valve_opening`: Valve position/opening percentage (%)
- `pressure_psi`: Pressure in PSI (psi)
