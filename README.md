# State Estimation

State estimation and Slam Repo

### Installing

Running the cartographer installation script

```
db019_state_estimation/install_cartographer.sh

```

catkin_make_isolated is used as Cartographer and ceres_solver are not catkin packages.


```
catkin_make_isolated --install --use-ninja

```

The workspace space has to be sourced using:

```
source install_isolated/setup.bash

```



## Getting Started

To run the state estimation node using slam output. First run the cartographer node (change the path for the rosbag !)

```
roslaunch cartographer_ros demo_db19.launch bag_filename:=/home/osama/ros_workspaces/db19/straight_4_06-12.bag 

```
run the state estumation launch file

```
roslaunch basicstateestimation stateestimation.launch

```



