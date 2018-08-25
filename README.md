# gmapping_ROS
Implementation of gmapping ROS package which is based on Grid-based FastSLAM algorithm to map the environment.

## Steps to launch simulation 

#### Step 1 Create a catkin workspace
Skip this step if you already have a workspace
```sh
$ mkdir -p /home/workspace/catkin_ws/src/gmapping_ROS
$ cd catkin_ws/src/gmapping_ROS
$ catkin_init_workspace
$ cd ../..
$ catkin_make
```

#### Step 2 Perform a system update
```sh
$ apt-get update
```
#### Step 3 Clone the package in src
```sh
$ cd /home/workspace/catkin_ws/src/gmapping_ROS
$ git clone https://github.com/proneetsharma/gmapping_ROS.git
```
#### Step 4 Build and source your workspace
```sh
$ cd ..
$ catkin_make
$ source devel/setup.zsh
```
#### Step 5 Launch the nodes
```sh
$ ./launch.sh 
```
