# Pegasus_ML_Project

I am currently working as an ML/AI Undergraduate intern at [the Pegasus Research Group](https://pegasus.ep.wisc.edu/). 
The Pegasus-III Experiment, funded by the U.S. Department of Energy, focuses on advancing Fusion Energy and Plasma Science.

## Pegasus-III GUI (24/5 ~ 24/7)
Designed and developed a PyQt5-based GUI that imports experimental electromagnetic data from internal servers, enabling researchers to efficiently visualize and interact with the data. 

## Pegasus-III Helix Fitting Project (24/7 ~ 24/8)

During this period, we focused on developing and refining code for simulating and fitting helices to the magnetic field data collected from the Pegasus-III experiment.

### Key Achievements:

1. **Helix Simulation and Fitting:**
   - Developed a Python-based simulation model (`bdots_helix_fitting.py`) to:
     - Generate 3D helices.
     - Simulate their magnetic field values (BzDot).
     - Fit these helices to experimental data.

2. **Fitting Algorithms:**
   - Implemented various fitting algorithms, including:
     - Local optimization methods (e.g., Powell, Nelder-Mead).
     - Global optimization methods (e.g., Differential Evolution, Basin Hopping).

3. **Randomized Guessing for Improved Accuracy:**
   - Created the `loop_guess_run_fitting()` function to:
     - Handle multiple randomized guesses of the initial fitting parameters.
     - Mitigate sensitivity to poor initial guesses by exploring a wide parameter space.

4. **Error/Objective Function Visualization:**
   - Developed the `make_obj_func_plots()` method to:
     - Generate plots of the objective function for each fitting parameter.
     - Visualize the error surface and identify local minima for accurate fitting.

## Pegasus-III Audio Detection Project (24/9 ~ present)
My fellow researcher and I are working on a project to analyze audio data using deep learning techniques. 
Our goal is to detect anomalies in sounds generated by devices such as pumps and power supplies.

This project aims to develop a robust system for identifying irregularities that may indicate mechanical issues or failures, ensuring the reliability of these critical components. The system leverages advanced neural networks to recognize abnormal sound patterns, enabling early fault detection and preventive maintenance.
