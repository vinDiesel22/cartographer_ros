# LiDAR SLAM

## Getting Started

To run the state estimation node using slam output. First run the cartographer node (change the path for the rosbag !)

```
roslaunch cartographer_ros demo_db19.launch bag_filename:=/home/osama/ros_workspaces/db19/straight_4_06-12.bag 

```
run the state estumation launch file

```
roslaunch basicstateestimation stateestimation.launch

```



