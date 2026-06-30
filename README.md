# Def-Space_Tech_Winter_Internship
Resources for Def-Space Tech Winter Internship done under BSERC (Bharat Space Education Research Centre)

Def-Space Google drive folder link : https://drive.google.com/drive/folders/1HwyXQ5nmKCzu3XlfTaf2C1Am5Mxi7UJG?usp=sharing

The link contains expert-led lectures on Advanced Drone Technology, Aircraft Design, Advanced Rocketry, Space Entrepreneurship, and Robotics.

# Trim, Thrust, and Power Analysis of a Cropped Delta Wing UAV

This project was completed as part of the **BSERC Winter Internship (Def-Space Tech)**. The objective was to analyze the flight performance of a cropped delta wing UAV by performing trim analysis and evaluating the thrust and power requirements during steady level flight.

The project combines concepts from aerodynamics, flight mechanics, and numerical methods to study how different flight conditions affect the aircraft's performance.

---

## Objective

The primary goals of this project were to:

- Perform trim analysis by satisfying the pitching moment equilibrium condition.
- Compute the trim elevator deflection for different angles of attack.
- Determine the flight velocity required for steady level flight.
- Calculate the thrust and power required across the flight envelope.
- Evaluate aerodynamic performance using Lift-to-Drag ratio and Endurance Parameter.
- Visualize the variation of these parameters using MATLAB.

---

## Methodology

The analysis was implemented in **MATLAB** using an iterative numerical approach.

For angles of attack ranging from **0° to 12°**, the program:

1. Computes the trim elevator deflection using the pitching moment equation.
2. Calculates the corresponding lift coefficient.
3. Determines the flight velocity required to maintain level flight.
4. Computes the drag coefficient using the drag polar.
5. Calculates:
   - Thrust Required
   - Power Required
   - Lift-to-Drag Ratio (CL/CD)
   - Endurance Parameter (CL^(3/2)/CD)

The results are then plotted against both flight velocity and angle of attack for performance analysis.

---

## Key Concepts Used

- Aircraft Trim Analysis
- Steady Level Flight
- Lift and Drag Equilibrium
- Drag Polar
- Numerical Iteration
- MATLAB Programming
- Aircraft Performance Analysis

---

## Results

The analysis highlights several important flight characteristics:

- Flight velocity decreases with increasing angle of attack.
- Trim elevator deflection changes almost linearly with angle of attack.
- The thrust required curve exhibits the expected U-shaped behaviour due to the balance between induced and parasitic drag.
- The minimum power required condition corresponds to maximum endurance.
- The maximum Lift-to-Drag ratio identifies the condition for maximum range.

---

## Tools Used

- MATLAB
- Numerical Methods
- Flight Mechanics
- Aircraft Performance Theory

---

## Learning Outcomes

Through this project, I gained practical experience in:

- Applying flight mechanics concepts to aircraft performance analysis.
- Developing iterative numerical solvers in MATLAB.
- Modeling aerodynamic behaviour using analytical equations.
- Interpreting performance curves to identify optimum flight conditions.
- Understanding the relationship between trim, drag, thrust, and power requirements in UAV design.

---

## Acknowledgement

This project was completed during the **BSERC Winter Internship (Def-Space Tech)** as part of the Aircraft Design module.
