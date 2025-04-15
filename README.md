# DSWT
Designing and simulating the wind turbine vensys 170
This group project was developed as part of the "Design and Simulation of Wind Turbines" course at the Technical University of Berlin
## 📌 Overview
The goal of this project is to design the Horizontal Axis Wind Turbine VENSYS 170 and certify it through a selection of relevant aeroelastic load simulations. This is done in a group of 4 people
## 🧰 Tools
- QBlade is mainly used to design the wind turbine, create wind profiles, and run simulations.
- IEC Wind was also used alongside to create wind profiles.
- PDAP alongside a python script is used for post-processing purposes.
## 📅 Project Timeline & Workflow
### 1. Designing the Blade
The first step of the project is designing the blade. Each of the group members is to find suitable airfoils in order to build the most suited blade that could work under the conditions and dimensions given by the manufacturer of the wind turbine. After analyzing their Lift to Drag ratio and Angle of Attacks, the chosen airfoils are NACA 4838 for the root, AH 94-W-301 and NACA 3428 for the mid-span, NACA 3220, NACA 3721and NACA 2418 for the tip.
<p align="center">
  <img src="./assets/1.jpg" alt="Lift to Drag Ratio vs. Angle of Attack" width="600"/>
</p>
### 2. Optimizing the Blade
Next step is to optimize the blade (both twist and chord length)  

### 3. Aerodynamic performance
After designing the blade, the next step is an aerodynamic analysis of the control of the wind turbine to see the efficiency of the control systems and to keep the power production withinthe capacity, which is 5.8  Attention should be paid to the control of the pitch angle to keep the turbine at its optimal output and to avoid mechanical or electrical issues.

### 4. Building up the turbine

Up to this part, weved done the project together in a group and discussed it together. The next tasks are split because they're not really connected to each other. My part is to  do a fatigue load analysis within the blade roots according to IEC 61400.
### 4. Fatigue Load Analysis
