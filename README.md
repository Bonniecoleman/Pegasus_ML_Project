# Pegasus_ML_Project

I am currently working as a ML/AI Undergraduate intern at [the Pegasus Research Group](https://pegasus.ep.wisc.edu/). 
The Pegasus-III Experiment, funded by the U.S. Department of Energy, focuses on advancing Fusion Energy and Plasma Science.
[Published Research](https://meetings.aps.org/Meeting/DPP24/Session/JP12.74)

All code is confidential.

## Pegasus-III GUI (5/2024 ~ 7/2024)
Designed and developed a PyQt5-based GUI that imports experimental electromagnetic data from internal servers, enabling researchers to efficiently visualize and interact with the data. 

## Pegasus-III Helix Fitting Project (7/2024 ~ 8/2024)

During this period, we focused on developing and refining IgorPro code into python for simulating and fitting helices to the magnetic field data collected from the Pegasus-III experiment. 

### Key Achievements:

1. **Helix Simulation and Fitting:**
   - Developed a Python-based simulation model (`bdots_helix_fitting.py`):
     - Generate 3D helices.
     - Simulate their magnetic field values (BzDot).
     - Fit these helices to experimental data.

2. **Fitting Algorithms:**
   - Applied various optimization fitting algorithms, including:
     - Local optimization methods (e.g., Powell, Nelder-Mead).
     - Global optimization methods (e.g., Differential Evolution, Basin Hopping).

4. **Randomized Guessing for Improved Accuracy:**
   - Created the `loop_guess_run_fitting()` function:
     - Handle multiple randomized guesses of the initial fitting parameters.
     - Mitigate sensitivity to poor initial guesses by exploring a wide parameter space.

5. **Error/Objective Function Visualization:**
   - Developed the `make_obj_func_plots()` method:
     - Generate plots of the objective function for each fitting parameter.
     - Visualize the error surface and identify local minima for accurate fitting.

## [Pegasus-III Audio Detection Project (9/2024 ~ Stopped in December, 1/2025 ~ Present)](https://github.com/Bonniecoleman/Pegasus_ML_Project/tree/main/Pegasus-III%20Audio%20Detection)
My fellow researcher and I are working on a project to analyze audio data using deep learning techniques. 
Our goal is to detect anomalies in sounds generated by devices such as pumps and power supplies.

This project aims to develop a robust system for identifying irregularities that may indicate mechanical issues or failures, ensuring the reliability of these critical components. 

## Pegasus-III Cathode Spot Detection (1/2025 ~ Present)
Currently I am collaborating with a PhD student on a deep learning project to detect cathode spots in the Pegasus-III experiment's time-series data.  
Our goal is to develop a model that can accurately classify the presence and severity of cathode spots based on voltage injector.  
