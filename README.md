# robotic_arm
Robotic arm of P.N.T. Robotics &amp; Automation Solutions

## Steps to use this Robotic_Arm

Create your workspace
```
mkdir -p ~/<Workspace_name>/src
```
Clone this repository to the src folder

```
cd ~/<Workspace_name>/src
```
```
git clone https://github.com/Ojasva-Goyal/robotic_arm.git
```

Build your workspace and source setup files.

```
cd ~/<Workspace_name>

catkin_make

source devel/setup.bash

```

Launch the project

```
roslaunch moveit_projects custom.launch

```
