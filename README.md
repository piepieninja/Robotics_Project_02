# Robotics Project 02

asdf, yeet

### Set Up

done within existing catkin workspace: `~/catkin_ws/src` . Place this project there.

run: `catkin_make` to generate this project

To install PR2 omnidirectional robot:
```bash
$ sudo apt-get install ros-kinetic-pr2-gazebo
$ rosdep install pr2_gazebo
$ rosmake pr2_gazebo
```
To run (link: http://wiki.ros.org/pr2_simulator/Tutorials) :
```bash
$ roslaunch gazebo_ros empty_world.launch
$ roslaunch pr2_gazebo pr2.launch
```
To move install pr2_teleop (link: http://wiki.ros.org/pr2_simulator/Tutorials/WorkingWithGazeboOverRos):
```bash
sudo apt-get install ros-kinetic-pr2-teleop
```

Then type:
```bash
$ roslaunch pr2_teleop teleop_keyboard.launch
```

Control keys:
Use 'WASD' to translate
Use 'QE' to yaw
Press 'Shift' to run
