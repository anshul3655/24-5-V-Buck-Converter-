DC-DC Buck Converter Simulation (24V to 5V)

This repository contains the $MATLAB/Simulink$ files for a 24V to 5V DC-DC Buck Converter, demonstrating skills in power electronics and closed-loop control.

 Project Specifications

* Input Voltage (V_in): 24V
* Output Voltage V_out: 5V
* Load Current I_out: 1 A R = 5Omega
* Control: PID Closed-Loop Control
* Switching Frequency f: 50kHz

 Technologies Used

* MATLAB
* Simulink
* Simscape Electrical

## 🧮 Design Summary

* Duty Cycle (D):20.8
* Inductor L: 270 H (Calculated for 30% ripple current)
* Capacitor C:22 micro F (Calculated for 1% voltage ripple)

 Simulink Model & Results

The closed-loop system uses a PID controller to maintain a stable 5V output.


<img width="1188" height="411" alt="image" src="https://github.com/user-attachments/assets/f8fb8a71-9b08-41fd-a5c5-a84f6af2fb0e" />

# Key Results

1.  Steady-State Output:The output voltage successfully stabilizes at 5V  with minimal ripple.
   

2.  Load Regulation: The controller maintains 5V even when the load is changed (e.g. 5 Omega to 10 Omega ), proving its robustness.
   

3.  Efficiency: The simulated efficiency is [ 92.5%].

# How to Use

1.  Clone the repository.
2.  Open `BuckConverterClosedLoop_PID.slx` in MATLAB/Simulink.
3.  Run the simulation to see the results.

