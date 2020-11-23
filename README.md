# Control Systems in Artificial Cardiac Pacemaker

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

### Introduction

Heart is one of the most important organs of a human body which need to work continuously and
steadily for a living organism’s metabolism to function properly. Therefore, individuals susceptible to
abnormal heart rhythms require additional systems to help their heart function normally. One such
device used is an artificial pacemaker. The pacemaker senses abnormal heart rhythms (bradycardia or
tachycardia) and emits electrical impulses to stimulate the heart muscles accordingly and maintain a
normal heart rhythm. The pacemaker performs two main functions: sensing and pacing. A combination of accelerometer,
minute ventilation and cardiac contractility sensor enables the pacemaker to provide an immediate
response to any physical activity and detect the metabolic need. The electrodes are also able to sense
contraction force of the ventricle’s chambers and predict how fast the heart needs to contract to
maintain the cardiac output. The pacing action of the pacemaker is performed by electrodes attached
to the ventricles or the atria of the patient.

To read more, please refer to the report(https://github.com/agabhi017/Control-Systems-in-Artificial-Cardiac-Pacemaker/blob/main/Report/Final-Report-140171422114415.pdf).
