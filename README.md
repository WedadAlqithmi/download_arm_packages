# download_arm_packages


write the next lines to the terminal 

```
sudo apt-get install ros-noetic-catkin
mkdir -p ~/catkin_ws/src

cd ~/catkin_ws/

catkin_make

cd~ /catkin_ws/src

rosdep install --from-paths src --ignore-src -r –y

sudo apt-get install ros-noetic-moveit

sudo apt-get install ros-noetic-joint-state-publisher ros-noetic-joint-state-publisher-gui

sudo apt-get install ros-noetic-gazebo-ros-control joint-state-publisher

sudo apt-get install ros-noetic-ros-controllers ros-noetic-ros-control

sudo nano ~/.bashrc

source /home/"your name"/catkin_ws/devel/setup.bash

source ~/.bashrc

roslaunch robot_arm_pkg check_motors.launch
