# Udacity Student Project: Solve SLAM Problem using RTAB-Map

1) Develop your own package to interface with the rtabmap_ros package.

2) Build upon your localization project to make the necessary changes to interface the robot with RTAB-Map. An example of this is the addition of an RGB-D camera.

3) Ensure that all files are in the appropriate places, all links are properly connected, naming is properly setup and topics are correctly mapped. Furthermore there is a need to generate the appropriate launch files to launch the robot and map its surrounding environment.

4) When robot is launched, teleop around the room to generate a proper 2D occupancy grid and 3D octomap of the environment.

5) Build your own simulated environment and apply the code you used to map the supplied environment on this environment.

Full report can refer to [here](map-my-world-robot.pdf).

## Run the Project
After completing the project, you can launch it by running the following commands first 
```bash
$ cd ~/catkin_ws
$ catkin_make
$ source devel/setup.bash
```
And then run the following in *separate* terminals 
``` bash
$ roslaunch slam_project world.launch
$ roslaunch slam_project teleop.launch
$ roslaunch slam_project mapping.launch
$ roslaunch slam_project rviz.launch
```

