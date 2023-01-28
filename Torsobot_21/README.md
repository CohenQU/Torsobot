# Torsobot

IMU: read and interpret the data from Yostlab IMU sensor and publish the angle data to a topic 
Encoder: read and interpret the data from Pololu encoder  and publish the speed to a topic
Controller: Merge both IMU and Encoder data streams. Control law inplemented. 
angle_reset: used to initialize the robot pose upon start. This was extensively used during testing to ensure that the robot started in the same condition 

