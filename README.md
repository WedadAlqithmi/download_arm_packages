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
```

godown and paste the next line too 

```

source /home/"your name"/catkin_ws/devel/setup.bash

```
then press on ctrl+ o >>> enter >> ctrl+ x, then paste the next lines too 

```

source ~/.bashrc

roslaunch robot_arm_pkg check_motors.launch

``` 
thelast line will launch the arm package 





![ros package arm](https://user-images.githubusercontent.com/108210044/182048719-f5d791dc-e509-40bf-9028-22a6547e964f.PNG)
