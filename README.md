# Gazebo-office-model

## This is an example office world in Gazebo. You need to delete build folder and follow these steps to run in Gazebo
```sh
 sudo apt-get update
 sudo apt-get upgrade -y 
 ```
## Build
```sh
 cd ~/Gazebo-office-model
 
 mkdir build
 
 cd build/
 
 cmake ../
 
 make 
 
 export GAZEBO_PLUGIN_PATH=${GAZEBO_PLUGIN_PATH}~/Gazebo-office-model/build
 ```
 
 ## Run
 ```sh
 cd ~/Gazebo-office-model/world/
 
 gazebo world
 ```
