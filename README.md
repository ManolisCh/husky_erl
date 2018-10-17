# husky_erl
This contains meta-packages for ERL's husky

# Installing ROS dependencies
```sh
sudo apt-get install ros-kinetic-lms1xx
sudo apt-get install ros-kinetic-robot-localization
sudo apt-get install ros-kinetic-interactive-marker-twist-server
sudo apt-get install ros-kinetic-twist-mux
sudo apt-get install ros-kinetic-rviz-imu-plugin
sudo apt-get install ros-kinetic-gazebo-ros-control
sudo apt-get install ros-kinetic-ros-controllers
sudo apt-get install ros-kinetic-ros-control
```

You can also use `rosdep install --from-paths src --ignore-src -r -y` from your catkin workspace. This installs all the packages that the packages in your catkin workspace depend upon but are missing on your computer. Please note this is only if the dependences are documented corrently in the package.xml .
