# Gazebo-office-model

This is an example office world in Gazebo: 
Follow these steps to run in Gazebo

 cd ~/Gazebo-office-model
 
 mkdir build
 
 cd build/
 
 cmake ../
 
 make # You might get errors if your system is not up to date!
 
 export GAZEBO_PLUGIN_PATH=${GAZEBO_PLUGIN_PATH}~/Gazebo-office-model/build
 
 cd ~/Gazebo-office-model/world/
 
 gazebo world
