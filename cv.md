---
layout: page
title: CV of Nahid Uzzaman
Subtitle: nahid.uzzaman@okstate.edu
---
## Skills
-	Kalman Filters: Kalman Filter (KF), Extended Kalman Filter (EKF), Adaptive KF (AKF) with learning covariance from data
-	Machine Learning: Neural Network (NN), Deep Learning, Gaussian process regression (GPR), Regression, LSTM, RNN, CNN
-	Classical control theory: PID control, frequency response analysis, Bode plot, Nyquist plot, root locus, feedforward, feedback control, PID tuning, stability margins, second order system, loop shaping, model in loop (MIL), hardware in loop (HIL)
-	Modern control theory: state space (state matrices), digital control, continuous control, state machine, discrete controller, multivariable control, non-linear systems, linear systems, full state observer, single-input single-output (SISO), multi-input multi-output (MIMO), controllability, observability, LQR, optimal control, optimal state estimation, Kalman filter, extended Kalman filter
-	Motor control: Permanent magnet brushless DC motor (BLDC), scalar control, vector control, field-oriented control
-	Tools: MATLAB, Simulink, MATLAB Control System Designer, LabVIEW, AutoCAD, Oscilloscope, Microsoft office
-	Programming language: MATLAB, Python, C, C++, PyQt GUI development, Bash, Github
-	Micro-Controller: STM32 (32 bit), PIC (8 bit), Arduino, AVR



## Education
- PhD in Mechanical Engineering | Oklahoma State University (_December 2025_)
- Master of Science in Mechanical Engineering | Kansas State University, Manhattan, KS (_August 2019_)
- Bachelor of Science in Mechanical Engineering | Military Institute of Science and Technology (MIST), Dhaka, Bangladesh (_January 2016_)

## Research Experience
### PhD Research, Oklahoma State University	(_August 2020 – present_)
**Multi-model unscented Kalman filter-smoother for wind estimation (_Jan 2024 - Present_)**
-	Developed a Multiple Model Unscented Kalman Smoother (MM-UKS) algorithm for real-time wind estimation using a quadcopter
-	Integrated Gaussian Process Regression (GPR) to model drag force uncertainty, enhancing robustness in wind estimation
-	Analyzed interacting and non-interacting MM-UKS variants, demonstrating trade-offs in accuracy and uncertainty in estimation

**Novel adaptive Kalman filter for systems with unknown state-dependent noise covariances (_Jan 2023 - Dec 2023_)**
-	Developed a variational Bayesian adaptive Kalman filter (VB-AKF) to estimate system states with state-dependent covariances
-	Variational Bayesian inference of Wishart process is combined with the Kalman filter (KF) to address limitations of traditional KF
-	Validated VB-AKF through simulations, demonstrating its effectiveness in improving state estimation accuracy

**Predicting uncertainties using machine learning: variational Wishart processes (VWP) (_Aug 2021 - Dec 2022_)**
-	Developed three novel VWP algorithms for predicting dynamic covariance of datasets with both uncertain input and uncertain output 
-	Designed variational inference techniques for the VWP utilizing sparse Gaussian process regression (GPR)
-	Conducted simulations demonstrating superior reliability and accuracy of proposed algorithms through comparative analysis


### Masters Research, Kansas State University (_August 2017-August2019_)
**Comparative analysis between field-oriented control and uncontrolled current operation (_Aug 2017-Aug 2019_)**
-	Modeled a Brushless dc (BLDC) motor with state-space representation to perform multivariable control of phase currents and torque
-	Analyzed BLDC motor with field oriented or vector control, reference frame theory and designed PI controller for current control
-	Developed Simulink simulation of the BLDC motor with and without vector control to find the factors affecting performance
-	Performed frequency response analysis and found that vector control system has higher bandwidth but the uncontrolled current system has higher delay and stability margins
-	Tested both systems for speed and position controlling with P, PD and PI controllers and analyzed experimental data in MATLAB


**Speed and position control of a brushed motor with flywheel attachment (_2018_)**
-	Modeled the mechanical and electrical dynamics of the system to design multivariable controllers for speed and position control
-	Designed PID controllers by adding design constraints (overshoot and settling time) in MATLAB control system designer toolbox
-	Calculated observer gains and feedback gains for a full state observer for pole placement to achieve required system dynamics
-	Implemented the designed PID controller and the full state observer in LabVIEW graphical programming to control the actual plant
-	Connected real-time box to establish communication between plant hardware and LabVIEW and performed HIL control system testing
-	Used LabVIEW data acquisition (DAQ) process to record plant input and output data and analyzed the controller performance

**Inverted pendulum cart controlling (_2018_)**
-	Developed non-linear dynamic equations and state-space model of the underactuated inverted pendulum cart with only one actuator
-	Designed controller and feedback gains in MATLAB from design constraints to stabilize the inverted pendulum with only cart motion
-	Implemented the controller in LabVIEW and used Bluetooth communication to connect LabVIEW with the hardware
-	Used LabVIEW DAQ to record system responses and tuned the controller to make the system more robust under disturbances



## Professional Experience
**Graduate Research Assistant, Oklahoma State University (_Aug 2020-Present_)**
-	Developed variational Wishart process algorithms to predict dynamic covariance of dataset that has uncertain input and out
-	Developed a novel variational Bayesian adaptive Kalman filter (VB-AKF) for systems with state-dependent noise covariance matrices
**Graduate Teaching Assistant, Oklahoma State University (_Aug 2020-Present_)**
-	Teach Python programming language and application of Python in solving various engineering problems 
**Research Intern, Kansas State University (_Sep 2019-Jul 2020_)**
-	Designed affordable lab equipment for an introductory control theory course using a Brushless DC (BLDC) motor
-	Determined when to replace field-oriented control with uncontrolled current input, cutting costs by eliminating sensors and controllers
-	Investigated nonlinear friction presence and assessed data quality when nonlinearities were disregarded.

**Graduate Teaching Assistant, Kansas State University (_Aug 2017-May 2019_)**
-	Taught classical control techniques, MATLAB coding and debugging and experimental analysis for control system testing
-	Conducted labs and lectured about related theories such as modeling of dynamic systems and control system design
-	Demonstrated PID controller designing and obtaining experimental frequency response data to generated empirical bode plots 
Lecturer of Mechanical Engineering, City University, Bangladesh		          			          July 2016-Apr 2017
-	Developed and taught Mechanical Engineering courses: Mechanical Engineering Drawing and Drafting, Mechanics of Machinery, Thermodynamics and HVAC, Mechatronics and Robotics.

## Publications
-	N. Uzzaman and H. Bai, "A novel variational Bayesian adaptive Kalman filter for systems with unknown state-dependent noise covariance matrices," 2024 American Control Conference (ACC), Toronto, ON, Canada, 2024, pp. 1192-1197, doi: 10.23919/ACC60939.2024.10644401. 
-	N. Uzzaman and H. Bai, "Dynamic covariance prediction using variational Wishart processes with uncertain inputs," 2023 American Control Conference (ACC), San Diego, CA, USA, 2023, pp. 125-130, doi: 10.23919/ACC55779.2023.10155969. 
-	W. N. White, E. Patterson and N. Uzzaman, “A Voltage Control Paradigm for Economic Brushless DC Motor Control,” 2020 American Control Conference (ACC), Denver, CO, USA, 2020, pp. 4289-4294, doi: 10.23919/ACC45564.2020.9147439.


## Awards and Honors
-	MIST Commandant’s list of honor for academic excellence,2015
-	3rd position, Mechatronic project competition, ICEEICT, Jahangir Nagar University, Bangladesh,2015
-	Best project award, Faculty of ME, Military Institute of Science and Technology (MIST), Bangladesh,2014
-	Champion, ME Mechatronic project competition, Islamic University of Technology, Bangladesh, Sept 2014
-	Champion, EE Mechatronic project competition, Islamic University of Technology, Bangladesh, June 2014
-	MIST Commandant’s list of honor for academic excellence, 2013





