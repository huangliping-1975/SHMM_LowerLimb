# SHMM_LowerLimb
These pages hold original data collected for experiments reported in our paper.
Data
The folder 'Data' includes all the experiments involved in the paper, for both training and testing data, it uses Matlab format. 
In each data file, there are two structs (footStatic and footMotion) of the sensor readings, 
one is a short period with no movement and another one is a longer period with the four considered activities. The struct members are, in second
Accel_WideRange(acceleration), in m/s^2
Gyro (angular rate), in deg/s
Magnetic
Quat9DOF_WideRange, quaternion
Other useful information is also included in the file:
