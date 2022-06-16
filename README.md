## Environment
This repository was developed and tested on Ubuntu 18.04 with ROS Melodic.

## Install Dependencies
To make the simulation run on your laptop, you first need to apt install the following packages:
```
sudo apt install ros-melodic-joint-state-publisher-gui
sudo apt-get install ros-melodic-moveit
```

## spot_arm_description
  You can access the hardware description of spot arm (stl, urdf, ...)
  You can launch the code to visualize the CAD of the arm and see the angle limits of each joints.
  
  ![alt text](https://github.com/estherRay/Spot-Arm/blob/main/ArmDescription.png)
  
## spot_moveit_config
  The simulation of the Arm for motion planning uses Moveit controller.
  
  Gazebo simulation / visualization available.
  
  ![alt text](https://github.com/estherRay/Spot-Arm/blob/main/ArmMoveIt.png)
