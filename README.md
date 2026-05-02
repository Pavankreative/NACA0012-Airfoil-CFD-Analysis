# NACA0012-Airfoil-CFD-Analysis
Computational Fluid Dynamics simulation of NACA 0012 airfoil at different angles of attack using SimScale
# NACA 0012 Airfoil CFD Analysis using SimScale

**Project for JRF / Research Assistant Applications**  
**Author**: Pavankumar  
**Date**: May 2026

## Objective
To perform incompressible CFD simulations on the classic NACA 0012 airfoil at different angles of attack and analyse lift and drag characteristics.

## Tools Used
- SimScale (cloud-based CFD platform)
- Post-processing in SimScale workbench

## Cases Simulated
- 0° Angle of Attack
- 5° Angle of Attack

## Methodology
- Incompressible steady-state simulation
- k-ω SST turbulence model
- Velocity inlet, pressure outlet, no-slip wall
- Refined mesh around airfoil

## Results

### Force Summary
| Angle | Total Drag Force (N) | Total Lift Force (N) | Observation |
|-------|----------------------|----------------------|-----------|
| 0°    | 13.57                | ~0                   | Symmetric flow, zero lift |
| 5°    | 3.23                 | small positive       | Lift increases with angle |

### Key Plots (see `results/` folder)
- Pressure contours
- Velocity magnitude
- Force convergence plots
- Residual convergence

## Observations
- Flow remains attached at 5°.
- Lift coefficient increases with angle of attack as expected.
- Good convergence achieved in both cases.

## Future Work (Planned)
- Simulations at 8°, 10°, 12° angles
- Stall angle prediction
- Comparison with experimental data (Abbott & von Doenhoff)
- 3D wing extension

## How to Reproduce
1. Create a free account on [SimScale](https://www.simscale.com)
2. Search and duplicate public NACA 0012 projects
3. Modify the inlet velocity direction for different angles
4. Run and post-process

## Portfolio Purpose
This project demonstrates the ability to set up, run, and analyse real CFD simulations using cloud tools — valuable skill for research roles in Aerospace / Mechanical Engineering.

---
**GitHub Portfolio**: Pavankreative/NACA0012-Airfoil-CFD-Analysis
