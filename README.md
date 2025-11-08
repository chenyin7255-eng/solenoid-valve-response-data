# Solenoid Valve Dynamic Response Dataset

This repository contains simulated response data for a solenoid valve, comprising 100 experimental samples with corresponding timing diagrams.

## Dataset Overview

- **Data Type**: Simulation Data
- **Samples**: 100 individual tests
- **Format**: ZIP archive containing CSV files and PNG images
- **Content**: Time-series measurements of electrical and mechanical parameters

## File Structure
solenoid_valve_response_data/
├── Normalized/  (contains 100 CSV files)
└── Raw/         (contains 100 PNG files)

## Data Format

Each CSV file contains the following columns:
- `time`: Timestamp (seconds)
- `voltage`: Applied voltage 
- `current`: Electrical current 
- `pressure_pa`: Pressure in Pascals
- `valve_opening`: Valve position/opening percentage (%)
- `pressure_psi`: Pressure in PSI 
