The library for interfacing with the Golem Krang robot. The include/kore.hpp includes the main interface mode such as the choice of grippers, the use of the left or the right arm of the robot etc. 

Note that this library is based on the Ach interprocess architecture (Dantam et al. '15). The shared-memory interfaces we adopted avoids the head-of-line blocking issue in comparison to TCP/UDP protocols used by ROS.

The code was written by Can Erdogan, Saul Reynolds-Haertle and Munzir Zafar.
