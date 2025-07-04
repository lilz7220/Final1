# AAA* Pathfinding Algorithm (Anomaly-Aware Adaptive A*)

This project implements AAA*, an enhancement of the A* algorithm that uses anomaly-aware data (e.g. traffic, hazards) to dynamically reweight paths in a city grid.

## Features
- Real-time anomaly heatmap integration
- Dynamic path cost adjustment
- Rerouting around hazards
- Fast execution and low memory footprint

## How to Run
```bash
g++ main.cpp -o aaa_star
./aaa_star
