# Project 4 - Map My World

To build
```
cd catkin_ws
catkin_make
```

#### To run

Open a Terminal :

```
source devel/setup.bash
roslaunch my_robot world.launch 
```
Open 2nd Terminal :

```
Make "teleop_twist_keyboard.py" executable.
source devel/setup.bash
rosrun teleop_twist_keyboard teleop.launch 
```
Open 3rd Terminal:

```
source devel/setup.bash
roslaunch mapping mapping.launch
```

#### Mapped World

<img src="https://github.com/PranaliDesai/Project4_Map_my_world/blob/master/Mapped.png" width="800">

[Link](https://drive.google.com/open?id=1S5Kyb942bZJAn25aeaI-dYAFPYKhdsTB) to Rtabmap.db
