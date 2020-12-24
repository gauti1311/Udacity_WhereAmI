# UD_WHERE_AM_I
udacity robotics nanodegree project for localization (AMCL) using ROS and Gazebo simulation.

## Installation
```
cd catkin_ws/src/
git clone https://github.com/gauti1311/UD_WHERE_AM_I
```
## Build
```
cd ~/catkin_ws
caktin_make
```
## Run the Project
```
source devel/setup.bash
roslaunch my_robot world.launch

roslaunch my_robot amcl.launch
```

To run teleop node
```
rosrun teleop_twist_keyboard teleop_twist_keyboard.py 
```
![UD_WHERE_AM_I](amcl.png)  
