# Differential_Drive_Classic_Control
Differential Drive robot implemented using Pybullet and Gym
## Authors
Adithya Sharma C A and Shreya Kishor
## License and Copyright
BSD -3 <br/>
Copyright © 2023. All rights lie with Adithya Sharma C A and Shreya Kishor.
## Needed packages
pybullet - pip install pybullet <br/>
numpy - pip install numpy <br/>
gym - pip install gym <br/>
matplotlib - pip install matplotlib
## File desriptions
### 4_wheel_differential_drive_robot.urdf
This is URDF model of the robot. Collision parameters and mass values have been incorporated.
### error_plate.urdf
URDF file to represent the landing plate of the robot.
### map3.urdf
URDF file to represent a confined space
### classical_control.ipynb
The robot has been modelled to travel in the entire plane bounded by the map.<br/>
Uses classical controllers for linear velocity and angular velocity. Has an algorithm for taking curved turns and navigate to required end points.
