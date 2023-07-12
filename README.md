# usv_driver
To install the canbus ros interface, install the following dependencies 
```
sudo apt install ros-noetic-ros-canopen 
sudo apt install can-utils 
```
after installing the packages clone the repository into the ros workspace
```
git clone https://github.com/Muhayyuddin/usv_driver.git
```
build the ros workspace using *catkin_make* or *catkin build*

run the following script 

./can-port-initialization/slcanUp

launch the node using the launch file as below 
```
roslaunch rot_pod test_setup.launch
```
now we can see the thrusters and the pods as ros topics using *rostopic list*
# usv_navigation

usv_navigation node provides a simple example to publish the values to the pods and thrusters 



The packages in this repository are cloned from https://bitbucket.org/spinitalia/spin_mini_cat/src/dev/
