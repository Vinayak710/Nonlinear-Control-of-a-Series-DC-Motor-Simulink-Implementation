Nonlinear Control of a Series DC Motor — Simulink Implementation
This project implements the research paper "Nonlinear Control of a Series DC Motor: Theory and Experiment" by Mehta and Chiasson (IEEE, 1998) in MATLAB/Simulink.

It demonstrates the design and simulation of a nonlinear feedback linearization controller and state observer for a series-connected DC motor, including both:

A speed and load-torque observer using encoder feedback

A sensorless observer using current measurements only

✨ Key Features
Feedback linearization control for nonlinear motor dynamics

Speed and torque observer design using pole placement

Sensorless estimation with coordinate transformation

Full simulation of motor system in Simulink

Matching results with the original paper’s theoretical predictions

📁 Contents
SimulinkModels/: Simulink .slx files

Plots/: Output graphs of speed, torque, voltage, etc.

Docs/: Notes on observer design, gains, and implementation steps

📚 Reference
Mehta, S., & Chiasson, J. (1998). Nonlinear control of a series DC motor: theory and experiment. IEEE Transactions on Industrial Electronics, 45(1), 134–141.
