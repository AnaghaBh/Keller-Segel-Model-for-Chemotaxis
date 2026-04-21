# Keller Segel Model for Chemotaxis with an Antibiotic addition

## Overview
This project explores the fascinating field of bacterial chemotaxis, focusing on Keller-Segel models and the complex behaviors of bacteria when influenced by antibiotics. The primary goal of this research is to understand bacterial movement in response to external stimuli and the implications for antibiotic treatment.

## Purpose
The purpose of this project is to:
- Investigate the mathematical modeling of bacterial chemotaxis.
- Analyze Keller-Segel models to understand dynamics and behaviors under varying conditions.
- Study the impact of antibiotics on bacterial movement and behavior.

## Structure
The project is organized into several key directories:
- **models/**: Contains the mathematical models and simulations related to bacterial chemotaxis and Keller-Segel dynamics.
- **data/**: Includes datasets used for training and validation of models. 
- **scripts/**: A collection of scripts for data analysis, visualization, and model execution.
- **notebooks/**: Jupyter notebooks for interactive analysis and exploration of results.
- **results/**: Stores outputs from the simulations, including graphs and data files.

## Key Features
- Implementation of Keller-Segel models for simulating bacterial aggregation.
- Visualization tools for analyzing bacterial movement patterns. 
- Simulation scripts for testing different antibiotic concentrations and their effects on movement.
- Comprehensive documentation to guide users through project components.

## Mathematical Models
The project employs the Keller-Segel model, which is a system of partial differential equations describing how bacteria move towards higher concentrations of attractants, influenced by their own density and external factors such as antibiotics. Key equations and parameters used in the simulations include:
1. **Chemotaxis equations** - capturing the movement towards chemical gradients.
2. **Diffusion equations** - representing how bacteria spread in space over time.
3. **Reaction terms** - describing interactions with antibiotics and their effects on bacterial behavior.

## How to Use
To utilize this project, follow these steps:
1. **Clone the repository**:
   ```bash
   git clone https://github.com/AnaghaBh/Computational-Biology-Project.git
   cd Computational-Biology-Project
   ```
2. **Install required packages**:
   Ensure you have the necessary dependencies installed. Install them using:
   ```bash
   pip install -r requirements.txt
   ```
3. **Run simulations**:
   Navigate to the `scripts/` directory, and execute the main simulation file:
   ```bash
   python run_simulation.py
   ```
4. **Explore results**:
   Check the `results/` directory for generated data and plots.

For detailed usage and additional functions, refer to the documentation provided in the `notebooks/` folder.

## Contributions
Contributions to this project are welcome! Please refer to the CONTRIBUTING.md file for guidelines on how to contribute. 

---

_Last updated: 2026-04-21 18:05:56 (UTC)_
