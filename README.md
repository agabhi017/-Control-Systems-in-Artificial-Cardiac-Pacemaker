# Control-Systems-in-Artificial-Cardiac-Pacemaker

### Abstract
Control systems are largely prevalent across both mechanical and physiological
systems. In this report, we aim to study the intersection of the two by modelling and simulating the
control system of a pacemaker regulated functioning heart. The model uses some basic
assumptions and has been simplified to a closed loop feedback system which contains a PID
controller. The controller tuning was done using Simulink (MATLAB) to obtain a quick rise time,
low offset, reduced oscillations and low overshoot. Additionally, an accelerometer was used to
simulate a load on the heart that would increase the set point above 60 bpm, such as engaging in
physical activity. It was found that the modeled pacemaker system was able to successfully
adjust heart rate to these changes in set points. 
