# Thermal-conductivity-of-non-homogenous-materials-
This document studies the thermal conductivity of neoprene and the impact of its porosity. It explores 1D and 2D thermal flux modeling to understand the insulation of wetsuits. Statistical analysis reveals that thermal resistance depends heavily on the air occupation rate.

# 2D Thermal Simulation of Materials with Inclusions

**[Click here to view the Project Presentation](TIPE_Presentation_finale.pdf)**

## Project Description
This project contains a Jupyter Notebook dedicated to simulating heat diffusion within a two-dimensional (2D) material. The model accounts for the presence of inclusions (such as air bubbles or neoprene beads) distributed throughout the base material. 

The main objective is to analyze the thermal behavior of the composite material and deduce its **surface thermal resistance**. Parametric studies are also conducted to observe the impact of the inclusions' size and spacing (lattice parameter) on the overall insulation.

## Features
*   **Geometry creation**: Modeling a 2D spatial grid with distinct thermal properties (conductivity, density, heat capacity) for the base material and the inclusions.
*   **Thermal diffusion simulation**: Solving the heat equation with specific boundary conditions (hot/cold walls, adiabatic walls).
*   **Calculations**: Automatic determination of the model's thermal resistance.
*   **Parametric studies**: Analysis of the thermal resistance evolution as a function of the inclusion radius and lattice parameter.

## Prerequisites
To run this code, you will need **Python 3** and the following scientific libraries:
*   `numpy`
*   `matplotlib`
*   `scipy`

If you haven't installed them yet, you can do so via your terminal or command prompt using the following command:
```bash
pip install numpy matplotlib scipy jupyter
