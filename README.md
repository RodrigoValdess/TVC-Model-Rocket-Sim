# TVC-Model-Rocket-Sim

Thrust vector controlled model rocket simulink simulation. Allows user to tune PID gains 

**INSTRUCTIONS**:

- Watch Video on how to import the tf1 

- tf1 is the servo delay of the servos, this simulation only works with 9g servos

- In order to tune, imput both Com to tvc and inside the 3dof input the Mass moment of inertia

- Once done input a high number on the D gain and have the rest at 0, change this gain until its the smallest number that makes the ossilations increase over time

- then input that number inside the division block. What is given back is your gain, proceed to do this for the P gain and lastly the I gain

-----------------------------
