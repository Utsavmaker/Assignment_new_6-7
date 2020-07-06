First time.
Extract the package into ~/catkin_ws/src
Execute following commands into terminal

$cd catkin_ws
$catkin_make
$source devel/setup.bash

Every time when you need to run the drone.

$roslaunch drone_gazebo drone.launch 

$rosservice call /enable_motors "enable: true"

$rosrun nodes_practical takeoff_land.py

$rosnode list


