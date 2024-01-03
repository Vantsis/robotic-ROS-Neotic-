Your machine must have following version installed on it
- ROS Neotic (Ubuntu 20.04)
Extract the package into the src folder of your workspace

Open the terminal and build the package into it by command lines: 

$ cd ~/catkin_ws
$ catkin_make
$ source ~/catkin_ws/devel/setup.bash

- For downloading the Pioneer robot
- Run the following command
$ sudo apt-get install ros-noetic-p2os-driver ros-noetic-p2os-teleop ros-noetic-p2os-launch ros-noetic-p2os-urdf

After that launch pioneer robot in gazebo simulator by 
$ roslaunch p2os_urdf pioneer3dx.gazebo.launch

To launch the trajectory of robot
$ rosrun pioneer_sims pioneer.py

Note: Make the python script executable before run
