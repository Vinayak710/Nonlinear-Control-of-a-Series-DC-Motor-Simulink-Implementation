# ⚙️ Nonlinear Control of a Series DC Motor — Simulink Implementation

This project implements the research paper  
**_"Nonlinear Control of a Series DC Motor: Theory and Experiment"_** by Mehta and Chiasson (IEEE, 1998) using **MATLAB/Simulink**.

It demonstrates the design and simulation of a **nonlinear feedback linearization controller** and **state observer** for a series-connected DC motor, including:

- ✅ A **speed and load-torque observer** using encoder feedback  
- ✅ A **sensorless observer** using only current measurements

---

## ✨ Key Features

- ⚡ Feedback linearization control for nonlinear motor dynamics  
- 📈 Speed and torque observer design using pole placement  
- 🔍 Sensorless estimation using coordinate transformation  
- 🧩 Full simulation of motor and observer in Simulink  
- ✅ Results closely match those presented in the original research paper

---

## 📁 Repository Structure

```plaintext
DC_Motor_Project/
├── SimulinkModel/         # Main Simulink (.slx) file
├── MATLAB_Variables/      # .mat file(s) containing model parameters
