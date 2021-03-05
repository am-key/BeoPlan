# BeoPlan
 This repo contains everything under /catkin_ws/src
 
 
 For simulation
$ roslaunch ommp_bringup sim_bringup.launch world:=simple robot:=ommp_sim

To again launch the robot in the Gazebo alongside the controllers etc..

Then you can try for example the following commands

$ roslaunch ommp_moveit_interface moveit.launch

$ rosrun ommp_moveit_interface set_start_pos.py

$ roslaunch ommp_navigation gmapping.launch

$ roslaunch ommp_control teleop.launch
