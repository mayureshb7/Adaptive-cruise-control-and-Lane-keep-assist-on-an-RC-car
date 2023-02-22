# PROJECT 2:  Adaptive cruise control and Lane keep assist on an RC car
## Submitted by: Mayuresh Bhosale

### Problem Statement:
In this project, I had to implement an algorithm for Adaptive Cruise Control and Autonomous Lane Keeping by using Two ultrasound sensors fused together. The challanging part of the experiment was to run the RC car autonomusly down the hill without hitting the wall and stopping 30 cm before the front end wall.

### Implementation
- Data sampling – Implementing one ultrasound sensor to measure the front distance from the RC vehicle. Sampling to be done as quickly as possible to detect the objects nearby quickly and allow autonomous vehicle to react accordingly.
- Setting limits – Setting the desired distances from the front wall by using if and else loop to control RC vehicle throttle and steering. (Keeping RC 30 cm from the frontal wall or obstacle)
- Pulse width modulation – Setting positive and negative values of throttle for accelerating and braking whenever required.
- PID controller – Using PID controller to tune and reduce the error in the system. Iterating the Proportional gain, Integral gain and differential gain for both the throttle and steering to allow RC vehicle follow adaptive cruise control.

Please read `Mayuresh_Bhosale_Final_Report_Project.pdf` for more details.

**Image showing RC car hardware Setup for ADAS**

![](https://github.com/mayureshb7/Adaptive-cruise-control-and-Lane-keep-assist-on-an-RC-car/blob/main/RC_CAR.png)

**Video of the ADAS test**
https://youtube.com/shorts/AurkAglt75M?feature=share
