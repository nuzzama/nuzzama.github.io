---
title: Project Works
---
## Multi-model unscented Kalman filter-smoother for wind estimation (_Present_)      

![Coop project](/assets/img/Nahid.gif)

**Funding agency: National Science Foundation (NSF), Grant: 1925147**

-	Developed a Multiple Model Unscented Kalman Smoother (MM-UKS) algorithm for real-time wind estimation using a quadcopter
-	Integrated Gaussian Process Regression (GPR) to model drag force uncertainty, enhancing robustness in wind estimation
-	Analyzed interacting and non-interacting MM-UKS variants, demonstrating trade-offs in accuracy and uncertainty in estimation

## Comparative analysis between field-oriented control and uncontrolled current operation (_Aug 2017-Aug 2019_)
-	Modeled a Brushless dc (BLDC) motor with state-space representation to perform multivariable control of phase currents and torque
-	Analyzed BLDC motor with field oriented or vector control, reference frame theory and designed PI controller for current control
-	Developed Simulink simulation of the BLDC motor with and without vector control to find the factors affecting performance
-	Performed frequency response analysis and found that vector control system has higher bandwidth but the uncontrolled current system has higher delay and stability margins
-	Tested both systems for speed and position controlling with P, PD and PI controllers and analyzed experimental data in MATLAB

## Speed and position control of a brushed motor with flywheel attachment	(_2018_)
-	Modeled the mechanical and electrical dynamics of the system to design multivariable controllers for speed and position control
-	Designed PID controllers by adding design constraints (overshoot and settling time) in MATLAB control system designer toolbox
-	Calculated observer gains and feedback gains for a full state observer for pole placement to achieve required system dynamics
-	Implemented the designed PID controller and the full state observer in LabVIEW graphical programming to control the actual plant
-	Connected real-time box to establish communication between plant hardware and LabVIEW and performed HIL control system testing
-	Used LabVIEW data acquisition (DAQ) process to record plant input and output data and analyzed the controller performance

## Inverted pendulum cart controlling	(_2018_)
-	Developed non-linear dynamic equations and state-space model of the underactuated inverted pendulum cart with only one actuator
-	Designed controller and feedback gains in MATLAB from design constraints to stabilize the inverted pendulum with only cart motion
-	Implemented the controller in LabVIEW and used Bluetooth communication to connect LabVIEW with the hardware
-	Used LabVIEW DAQ to record system responses and tuned the controller to make the system more robust under disturbances

## Maze solving robot with shortest return path algorithm	(_2018_)
-	Developed maze solving algorithm and implemented with c++ object-oriented programming in 32-bit stm32 microcontroller
-	Connected sensors and motors with microcontroller where the microcontroller uses 5 passive infrared (IR) sensors to follow a line 
-	Developed shortest return path algorithm where the robot keeps track of turns and distance traveled and returns using polar coordinates
-	Performed PID tuning to increase the speed and make the robot more stable and robust under disturbances

## Controlling a robotic arm with hand gesture (_2013_)
-	Worked as the team leader in a group of five to build a robotic arm and contributed to prototype design and construction
-	Used three motors as actuators for three degrees of motion of the robotic arm
-	Programmed a microcontroller with 4 light-dependent resistor (LDR) sensors to detect hand movement by tracking light variation.

