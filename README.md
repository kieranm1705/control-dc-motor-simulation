# control-dc-motor-simulation
# DC Motor Control Simulation using MATLAB and Simulink

This repository contains all files related to the control and simulation of a brushed DC motor using proportional feedback, as part of my Control Engineering coursework at Manchester Metropolitan University.

## Project Summary

A second-order model of a DC motor was developed using datasheet values from Maxon and RS PRO. Simulations were performed in both open-loop and closed-loop configurations. A proportional controller was implemented to study its effect on system performance. MATLAB and Simulink were used for time- and frequency-domain analysis.

## Tools Used
- MATLAB R2023a
- Simulink
- Control System Toolbox
- Datasheet parameters from RS and Maxon

##  Repository Structure
control-dc-motor-simulation/
├── code/
│ ├── motor_model.m # Open-loop model and step response
│ ├── closed_loop_response.m # Proportional controller test (Kp)
│ ├── frequency_analysis.m # Bode and Nyquist plots
│ └── simulink_model.slx # Simulink closed-loop model
├── figures/
│ ├── figure1_open_loop_response.png
│ ├── figure2_simulink_model.png
│ ├── figure3_closed_loop_response_kp20.png
│ ├── figure4_bode_plot.png
│ └── figure5_nyquist_plot.png
├── report/
│ └── control_engineering_report.pdf
└── README.md
## Key Figures

- **Figure 1**: Open-loop response
- **Figure 2**: Simulink model of closed-loop system
- **Figure 3**: Closed-loop response with \( K_p = 20 \)
- **Figure 4**: Bode plot showing stable frequency behaviour
- **Figure 5**: Nyquist plot confirming system stability
## How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/kieran-mason/control-dc-motor-simulation.git
   cd control-dc-motor-simulation/code
Open MATLAB and run each script individually:
    motor_model
closed_loop_response
frequency_analysis
To open the Simulink model:

matlab
Copy
Edit
open('simulink_model.slx')
